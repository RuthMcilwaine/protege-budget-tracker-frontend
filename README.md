### App Access
This project is no longer actively deployed, but you can view screenshots in the [`docs/`](./docs) folder.

[Link to former deployment (now inactive)](https://proteges-budget-tracker.netlify.com)

---

### GitHub repository:

- Frontend: [https://github.com/RuthMcilwaine/protege-budget-tracker-frontend](https://github.com/RuthMcilwaine/protege-budget-tracker-frontend)
- Backend: [https://github.com/ruthmci/backend-Protege-Budget-Tracker](https://github.com/RuthMcilwaine/protege-budget-tracker-backend)  

---

## Project Description

Our client, Mark, manages proteges within MYOB. Each protege is assigned a learning budget annually, currently tracked via Excel and Slack requests. Mark wants a web app to streamline managing proteges and their budgets, enabling him to:

- View a list of proteges  
- Create, edit, or delete proteges  
- View and manage expenses for each protege  
- Track budgets and spending  

This app aims to replace the manual Excel process and potentially integrate with another protege app Mark uses.

---

## Tech Stack

- **Axios:** Promise-based HTTP client for browser and Node.js  
- **Express:** Minimal and flexible Node.js web framework  
- **Node.js:** JavaScript runtime outside the browser  
- **Now:** Rapid backend deployment  
- **Netlify:** Frontend deployment platform  
- **MongoDB:** Database to store data  
- **Git & GitHub:** Version control  
- **Visual Studio Code:** Preferred text editor  
- **Figma:** Design tool  
- **HTML/CSS/JavaScript:** For rendering views  
- **Bootstrap:** CSS framework for responsive design  

---

## Design Documentation

### OO Diagram

![OO Diagram](https://user-images.githubusercontent.com/31295147/61612469-03351280-aca2-11e9-9a5f-7d8b4abbfb21.png)

---

### Design Process / Wireframes

![Design Concept](https://github.com/RuthMcilwaine/protege-budget-tracker-frontend/blob/master/docs/Design%20Concept.png)

---

### User Stories

![User Stories](https://github.com/RuthMcilwaine/protege-budget-tracker-frontend/blob/master/docs/User%20Stories.jpg)

I am a protege manager, I want to:

- Keep a record of all the proteges and their purchases in the program  
- See an overview of total spent in the FMA  
- See a detailed view of the total spend of individual proteges  
- Track the protege learning budget  
- View individual protege details  
- See the overview for each protege  
- Analyse how the proteges are spending, sort purchases by category and by amount  
- Log amount spent by individual proteges  
- Create a new protege  
- Update a protege's details  
- Sort purchases by category or by spend  
- Delete protege from view/archive (status update, read-only)  
- Edit budget item or amount  
- Sign up new users  
- Upload images of the proteges to help identify them  

…so that I can:

- Track how much is left in the Future Makers Academy learning budget  
- Track how much is remaining in their overall budget  
- See what proteges are finding most valuable as a source of learning  
- Check the protege’s individual budget  
- Manage and edit the protege list and expenses  
- Make sure not to go over the FMA budget  
- Ensure each protege stays within their budget  
- Keep expenses up to date  
- See only the current list of proteges  
- Edit any typos made previously  

---

## Test Coverage of User Stories

### User Testing

![User Testing](https://github.com/RuthMcilwaine/protege-budget-tracker-frontend/blob/master/docs/User%20Testing%20I.png)

---

### User / Client Testing

![User Client Testing](https://github.com/RuthMcilwaine/protege-budget-tracker-frontend/blob/master/docs/User:Client%20testing.png)

---

### Client Feedback

![Client Feedback](https://github.com/RuthMcilwaine/protege-budget-tracker-frontend/blob/master/docs/Client%20testing:feedback.png)

---

### Development Site Testing

| Test                                  | First Test                                  | Second Test                                | Final Test                                |
|-------------------------------------|--------------------------------------------|--------------------------------------------|--------------------------------------------|
| View all proteges with spend and balance  | ✅                                          | ✅                                          | ✅                                          |
| View one protege with spend and balance   | ✅                                          | ✅                                          | ✅                                          |
| Edit a protege's details                | Not rendering change on view page          | ✅                                          | ✅                                          |
| Data validation on protege add and edit | Handling duplicate email on backend but not frontend | ❌                                          | ✅                                          |
| Delete a protege                      | ✅                                          | ✅                                          | ✅                                          |
| View protege items and balance         | ✅                                          | ✅                                          | ✅                                          |
| Add a purchase                       | ✅                                          | ✅                                          | ✅                                          |
| Edit a purchase                      | ✅                                          | ✅                                          | ✅                                          |
| Delete a purchase                   | ✅                                          | ✅                                          | ✅                                          |
| Data validation on protege add and edit | Not handling 'expenditure required' on backend or frontend | ❌                                          | ✅                                          |

---

### Production Site Testing

| Test                                  | First Test                                  | Second Test                                | Third Test                                |
|-------------------------------------|--------------------------------------------|--------------------------------------------|--------------------------------------------|
| View all proteges with spend and balance  | ✅                                          | ✅                                          | ✅                                          |
| View one protege with spend and balance   | ✅                                          | ✅                                          | ✅                                          |
| Edit a protege's details                | Not rendering change on view page          | ✅                                          | ✅                                          |
| Data validation on protege add and edit | Handling duplicate email on backend but not frontend | ❌                                          | ✅                                          |
| Delete a protege                      | ✅                                          | ✅                                          | ✅                                          |
| View protege items and balance         | ✅                                          | ✅                                          | ✅                                          |
| Add a purchase                       | ❌                                          | ❌                                          | ✅                                          |
| Edit a purchase                      | ✅                                          | ✅                                          | ✅                                          |
| Delete a purchase                   | ❌                                          | ❌                                          | ✅                                          |
| Data validation on protege add and edit | Not handling 'expenditure required' on backend or frontend | ❌                                          | ✅                                          |

---

## Workflow Diagram of the User Journeys

![Workflow Diagram](https://github.com/RuthMcilwaine/protege-budget-tracker-frontend/blob/master/docs/Workflow%20Diagram.png)

---

## Database Entity Relationship Diagrams

![Entity Relationship Diagrams](https://github.com/RuthMcilwaine/protege-budget-tracker-frontend/blob/master/docs/ERD.png)

---

## Data Flow Diagram

![Data Flow Diagram](https://github.com/RuthMcilwaine/protege-budget-tracker-frontend/blob/master/docs/Dataflow%20Diagram.png)

---

## Details of Project Management & Planning

![Team Charter](https://github.com/RuthMcilwaine/protege-budget-tracker-frontend/blob/master/docs/Team%20Charter.jpg)

---

![Kanban Week 1](https://github.com/RuthMcilwaine/protege-budget-tracker-frontend/blob/master/docs/kanban%20I.jpg)

---

![Kanban Week 2](https://github.com/RuthMcilwaine/protege-budget-tracker-frontend/blob/master/docs/Kanban%20II.jpg)

---

## Project Plan & Timeline

![Project plan & timeline](https://github.com/RuthMcilwaine/protege-budget-tracker-frontend/blob/master/docs/Project%20Timeline.png)

---

## Screenshots of Trello Boards

### Trello I

![Trello I](https://github.com/RuthMcilwaine/protege-budget-tracker-frontend/blob/master/docs/Trello%20I.png)

---

### Trello II

![Trello II](https://github.com/RuthMcilwaine/protege-budget-tracker-frontend/blob/master/docs/Trello%20II.png)

---

### Trello III

![Trello III](https://github.com/RuthMcilwaine/protege-budget-tracker-frontend/blob/master/docs/Trello%20III.png)

---

## Post Project Review

![Retro](https://github.com/RuthMcilwaine/protege-budget-tracker-frontend/blob/master/docs/Retro.jpg)

---

## Client Communication & Feedback

- Initial meetings with client Mark defined MVP and app requirements.  
- Wireframes and prototypes shared for feedback and refinement.  
- Client was very satisfied with the final product after testing rounds.  
- A client satisfaction survey was completed (see [Survey Results](https://github.com/RuthMcilwaine/protege-budget-tracker-frontend/blob/master/docs/Client%20survey%20results.pdf)).

---

## Project Retrospective

- Daily stand-ups and client meetings helped maintain momentum and clear direction.  
- Challenges included MongoDB usage, testing, and managing extensive meetings/planning.  
- Future improvements: more pair programming, earlier client MVP confirmation, and enhanced backend/frontend collaboration.

---

## Knowledge & Skills Demonstrated

- Programming: JavaScript, React, Node.js, Express, MongoDB  
- Testing: Unit, integration, and user testing  
- Design: UX wireframes, ER diagrams, data flows  
- Project Management: Planning, communication, retrospectives  
- Client interaction & empathy to ensure needs were met  

---

## Contact & Additional Documentation

- See the `/docs` folder for detailed diagrams, user stories, design files, and planning artifacts.  
