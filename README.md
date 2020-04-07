# CareConsult
[Live Site](https://ecstatic-leavitt-3a8f13.netlify.com/)

## Why CareConsult
The Covid-19 pandemic is straining healthcare systems around the globe. CareConsult was created to connect licensed volunteer health professionals with patients at home to reduce the burden on hospitals and clinics.

## Contribute 
- Join our [Slack Channel #free-covid-consultations @ COVID19 Global Hackathon](https://join.slack.com/t/globalcovidhackathon/shared_invite/zt-d25lrhkl-UAKmMq4h_zNzCQhqnNsbfw)
- Introduce yourself and let us know what you're working on or if you want to pair with one of us

### Pending Tasks
- [ ] Fix Resize/Delete Events
- [ ] Improve Footer Component
- [ ] More branding/marketing assets (text, images)
- [ ] Social Media Assets/Strategy
- [ ] Better design
- [ ] Fix Signup (@Marcos on the ticket)
- [x] Hide Login Button When Logged In
- [x] Calendar Component ([suggestion](https://github.com/jquense/react-big-calendar))
- [x] SignUp/SignIn screens frontend

#### Pending User Stories
- [ ] User (“Patient”) Logged: Schedule Appointment
- [ ] User (“Provider”) Logged: Open Available Time Slot (block Patients from opening time slots)
- [x] Add roles: Patient / Provider
- [x] Not Logged: Show Available Slots
- [x] Provider Logged Schedule Available Slot

### Wireframe
![wireframe](care-consult-wireframe-v1.png)

## Other Features
- Video chat functionality? Maybe it only needs audio for POC. Could use Jitsi 
- Ability for providers to initiate verification process
- Would need to hook into various state medical board DBs in the US
- Ability for platform to take into account license expiration date
- Add other types of certified health professionals? Psychologists etc. 
- Seed list of providers? Can start with NYC medical board website and scrape Dr list? 

### Installation

```bash
git clone git@github.com:marcoscannabrava/free-covid-consultation-calendar.git care-consult
cd care-consult
yarn
yarn develop
```

# Tech Stack
- [React + Gatsby](https://www.gatsbyjs.org/)
- [Firebase](https://firebase.google.com/)
- [Netlify](https://www.netlify.com/)
- kudos to: [gatsby-starter-netlify-cms](https://github.com/netlify-templates/gatsby-starter-netlify-cms)
