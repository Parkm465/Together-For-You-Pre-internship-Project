# Core User Flows
These flows describe how the users interact with the system from entry to ongoing engagement
## Flow 1: User Onboarding
### **Actors:** Mentors, Mentees
1. User opens app
2. User signs in or logs in using email/password
3. User selects role (Mentor/Mentee)
4. User completes profile setup
5. User is redirected to dashboard  
### **Outcome:**
User has a persistent account and role-specific access.
## Flow 2: Mentor-Mentee Assignment
### **Actors:** Mentors, Mentees
1. Mentee completes profile (interest, goals)
2. Mentor completes profile (availability, skills)
3. System establishes mentor-mentee relationship
4. Both can view each other's profile
### **Outcome:**  
Mentorship relationship is established and stored.
## Flow 3: Weekly Check-in Submission
### **Actors:** Mentee
1. Mentee navigates to "Weekly Check-ins"
2. Mentee completes reflection:
    * Moods
    * Wins
    * Challenges
3. Check-in is saved to the database
4. Confirmation shown to user
### **Outcome:**  
Engagement data is captured consistently.
## Flow 4: Mentor Review & Notes
### **Actors:** Mentor
1. Mentor navigates to mentee profile
2. Mentor views latest check-ins
3. Mentor adds private session notes
4. Notes are stored securely
### **Outcome:**  
Mentor documents progress while preserving trust.
## Flow 5: Goal Creation and Tracking
### **Actors:** Mentor, Mentee
1. Mentee creates or updates a goal
2. Mentor reviews and provides feedback
3. Progress updates are logged
4. Goal completion status updates over time
### **Outcome:**  
Mentorship is goal-driven and measureable.
## Flow 6: Engagement Monitoring (Basic)
### **Actors:** Mentor
1. System checks check-ins frequency.
2. Engagement indicator updates (e.g., missed check-ins)
3. Mentor uses signal to follow up proactively
### **Outcome:**  
Early disengagement is identified without automation bias.

## Design Principles Behind These Flows
* **Trust-First**: Mentors cannot alter mentee reflections
* **Low Friction**: Minimal steps to complete weekly actions
* **Human-centered**: Data supports conversations, not decisions
* **Privacy-awareness**: Access limited to assigned relationships
