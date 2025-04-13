# Camp Activity Sign-Up System – Capstone Project Wiki

## Requirements

> “A system that makes the life of the afternoon coordinator easy while pleasing as many campers as possible.”

### Functional Requirements

- The system shall allow counselors to quickly assign 20 campers to an activity.
- The system shall be able to handle 18 cabins that need to be signed up within 30 minutes.
- The system shall be accessible and easy for any afternoon program director to use.
- The system shall eliminate camper miscommunication between sign-ups and actual assignments.
- The system shall randomly assign cabin sign-up priority.

### Nice-to-Have Features

- The system could be mobile-friendly.

### Key Principles

- **Efficient**
- **Accessible**
- **Accurate**

---

## Meeting Minutes

### 🗓️ Jan 23, 2025
- Provide an overview of expectations from the school, client, and my side.
- Collected availability and goals from the client.
- Scheduled recurring meetings.

### 🗓️ Feb 7, 2025
- Presented different solutions with pros and cons of each and pitched what I thought worked best.
- Gathered more detailed requirements.
- Demonstrated an early Figma prototype.
- Started work on the database design.

### 🗓️ Feb 21, 2025
- Mapped out a day-in-the-life schedule of the camp.
- Discussed implementation in alignment with real camp workflow.
- Co-created an afternoon coordinator and counselor daily plan.
- _Helped clarify the intent behind requirements and allowed for idea exchanges._

### 🗓️ Mar 6, 2025
- Demonstrated a scalable database with Django admin where non-tech experts can use to create/view/edit data entries.
- Showcased automation features like when a counselor is created, an account with a username and password is automatically generated.
- Made critical fields undeletable to preserve logic.
- Added guidance notes and custom UI buttons on the admin page tailored to camp operations.

### 🗓️ Mar 20, 2025
- Showed a working UI with entry examples.
- Ensured mobile-friendliness and ease of use.
- Added dark mode for nighttime usability.
- Built user-friendly error pages for data issues.
- Optimized system performance.
- Collected feedback for future improvements.

> _Weekly meetings were also held with TA Omkar for guidance._

---

## Contributions

### 👤 Joseph Mansour (Solo Developer)

- Requirements gathering  
- Planning & organization  
- Database design  
- API development  
- UI & UX design  
- Implementation  
- Figma prototyping  
- GitHub repo management  
- Testing & documentation  

---

## Challenges & Resolutions

- **Database design**: Had to ensure scalability and align with microservices.
- **Choosing the right system model**: Evaluated multiple ways of implementing the system before landing on the current one.
- **Delayed client communication**: Client was only available on a bi-weekly basis; used prototypes, pros and cons list, presentations to bridge the gap.
- **Understanding how the system would be used**: Created a detailed day schedule outlining when and how the afternoon coordinator and counselors would interact with the app during camp activities.
- **Tool unfamiliarity**: Learned Django, Figma, and database architecture from scratch.
- **Validation**: Invested time early in confirming direction to avoid wasted dev time.

> 🔁 Averaged ~15 hours/week

---

## First Semester Progress ✅

I’m very happy with the progress. Both me and the client are satisfied with where things stand. While working solo slowed development, it was a client requirement. I’ve laid strong backend and structural foundations, and future development will be fast and efficient.

---

## Second Semester Plan 🚀

Next term will focus heavily on frontend development. The admin and backend are solid; now the priority is counsellor interaction. I aim to complete the UI, integrate with the existing API, and simulate a real camp day.

Planned deliverables:
- Camper sign-up interface
- Activity roster views
- Admin tools to create/edit activities
- Usability testing with real camp schedules

---

## Designs & Diagrams

### 🖼️ Interface Concepts

<img src="image.png" alt="Figma Concept 1" width="400"/>
<img src="image-1.png" alt="Figma Concept 2" width="400"/>

### 🕒 Daily Schedule Breakdown

#### Camp Schedule
<img src="https://github.com/user-attachments/assets/69a36f45-9f3a-44e0-95ce-4918b85d1650" width="400"/>

#### Afternoon Coordinator Schedule
<img src="https://github.com/user-attachments/assets/4c8907df-a3f6-497b-8eb2-3065a111ee70" width="400"/>

#### Staff/Counsellor Schedule
<img src="https://github.com/user-attachments/assets/a70adf80-0eab-4bc6-9ed1-92ab0f18fddc" width="400"/>

#### All Together
<img src="https://github.com/user-attachments/assets/e4b6c4f1-3eb7-41ce-94fe-67983ba84006" width="400"/>

> **In red:** Camp-T Counselor/CIT Schedule  
> **In gray:** Afternoon Coordinator Schedule  


### 🗄️ Database Design

<img src="image-6.png" alt="Database Schema" width="1000"/>

### 🛠️ Architecture & Tools

<img src="image-7.png" alt="System Architecture" width="800"/>
