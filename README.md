# Mentorship-Engagement Platform (TFY-Aligned)
This project is a mobile mentorship engagement platform designed to support nonprofits working with youth and families. The app focuses on improving mentor-mentee consistency, accountability, and outcomes through structured check-ins, goal-tracking, and engagement insights.  

The project demonstrates:
* Full-stack mobile development (frontend, backend, auth, database)
* Clean, maintainable code and documentation
* Ethical, lightweight use of data to support human-centered program
* Real-world software development practices aligned with social impact work

## Project Checklist
### Day 1: Planning & Foundations  
- [X] Define project scope & MVP goals
- [X] Document core user roles and flows (login -> dashboard -> check-in -> goals)
- [X] Initialize React Native/Expo project
- [X] Setup Firebase project (Auth + Firestore)
- [X] Write initial ReadMe with mission and scopes
### Day 2: App Structure & Navigation
- [ ]  Implement app navigation (auth flow + main tabs)
- [ ]  Create base screen components
- [ ]  Build reusable UI Components
- [ ]  Add placeholder screens for key features
### Day 3: Authentication & User Profiles
- [ ] Implement Firebase Authentication (email/password)
- [ ] Add role-based user profille (Mentor/Mentee)
- [ ] Persist profile data in Firestore
- [ ] Enable profile creation and editing
### Day 4: Mentorship Core
- [ ] Implement mentor/mentee relationship model
- [ ] Allow users to view matched mentor/mentee profiles
- [ ] Store mentorship links in Firestore
- [ ] Handle edge cases (missing profile data)
### Day 5: Weekly Check In
- [ ] Build weekly check-in form (mood, wins, challenges)
- [ ] Save check-ins to Firestore
- [ ] Display historical check-ins timeline view
- [ ] Enable mentors to review check-ins
### Day 6: Goals & Engagement Signals
- [ ] Implement goal creation and updates
- [ ] Track goal progress over time
- [ ] Add basic engagement indicators (e.g., missed check-ins)
- [ ] Polish UI and improve usability
### Day 7: Testing, Documentation, & Demo
- [ ] Manually test all core user flows
- [ ] Refactor code for readability and consistency
- [ ] Finalize README and documentation
- [ ] Add screenshots or demo GIFs
- [ ] Prepare short project summary for sharing

## Problem Statement
Non-profit mentorship programs rely on:  
* Manual check-ins
* Inconsistent documentation
* Limited visibility into engagement and progress
This makes it difficult for mentors and program staff to:  
* Track weekly engagement
* Support goal-setting and accountability
* Identify when participants may need additional support
## Solution
The app provides a lightweight digital system for mentorship programs that support:
* User Authentication
  * Secure sign-in using FireBase Authentication
  * Basic role distinction (mentor/mentee)
* Mentor & Mentee Profile
  * Store interests, goals, and availability
  * Persistent data in Firestore
* Weekly Check Ins
  * Mentees submit weekly reflections (moods, wins, challenges)
  * Mentors can review past check-ins
* Goal Tracking
  * Create and update mentorship goals
  * Track progress over time
* Engagement Signals (Basic)
  * Simple indicators based on check-in consistency
  * Designed to be ML-ready in future iterations  
This project focuses on core functionality and clairty, not production-scale features.
## Tech Stack
**Frontend**: React Native  
**Backend/Database**: Firebase (Auth + Firestore)  
**Language**: TypeScript/JavaScript  
**Version Control**: Git & Github  
## Project Structure
```
src/  
  components/  
  screens/  
  navigation/  
  services/  
docs/  
  user-flow.md  
  user-roles.md  
README.md  
```
## Limitations
This project does not include:
* Admin dashboard
* Push notification
* Advanced mentor-mentee matching
* Automated ML models
* Production deployment  
These are documented as future enhancements
## Future Improvements
* Smarter mentor–mentee recommendations
* Engagement risk prediction using historical data
* Admin analytics dashboard
* Push notification reminders
* Accessibility audits and improvements

## Why This Project Matters
This project is designed to reflect real nonprofit workflows, where technology supports, rather than replaces human relationships. It prioritizes trust, consistency, and measurable outcomes while remaining simple, maintainable, and scalable.
