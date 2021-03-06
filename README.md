NashvesTN
=====================
### Code Badges
- build status icon
- coverage status icon

### Screenshots
forthcoming

### Description
NashvesTN is a tool to connect people.  This app makes it easier for a user to connect with the transient population of Nashville, TN.  We have made it easier to donate either to an organization or a specefic person affilated with that organization.  After scanning the QR code on their badge you can then read their story, see their photo, find out about their aspirations and click the button to donate.

### Models
```
#User Model
-
```

```
#Donee Model
-
```

```
#Patron Model
-
```

```
#Donation Model
-
```

### Database
```
#User Collection
- name
- email
- role
- patron

Auth
- hashedPassword
- provider
- salt
- facebook
- google
```

```
#Donee Collection
- alias
- name
- email
- createdOn
- modifiedOn
- createdBy
- active
- photo
- story
- skills
- goal
- updates
- donations
```

```
#Patron Collection
- name
- userId
- createdOn
- modifiedOn
- lastLogin
```

```
#Donation Collection
- doneeId
- patronId
- programId
- amount
- date
```
### Features
- [x] MEAN Stack: MongoDB (with Mongoose), Express, Angular, & Node
- [x] Web Admin Dashboard (for administrators)
- [x] Mobile Companion App: Ionic & Cordova (for patrons)
- [x] QR code reader
- [x] Payment processing via Stripe
- [x] Social login
- [ ] Report generation
- [ ] Social sharing
- [ ] Feature 9
- [ ] Feature 10

### Running Tests
```bash
$ npm install
$ npm test
```

### Contributors
- [Melanie L. Fryman](https://github.com/mlfryman)
- [Brian Hiatt](https://github.com/bchiatt)
- [Jeremy Jones](https://github.com/banjeremy)
- [Kayla Jones](https://github.com/kaylalynjones)
- [Sarah Pearson](https://github.com/SarahMPearson)
- [Joy Pratt](https://github.com/JoyP)
- [Jessica Raines](https://github.com/jessicafraines)
- [Gregg Reece](https://github.com/undeadfish)
- [Shruti Sharma](https://github.com/shrutijalewar)

### License
- [MIT](LICENSE)
