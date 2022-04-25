---
layout: project
studentName: "Jordan Keiller"
supervisorName: "Dr Rachel Menzies"
projectTitle: "Extending Computing's Online Peer Review System"
projectImage: "jordankeiller.png"
---
## How does Peer Review work?

Peer Review provides an anonymised way for an individual to provide feedback on their peers, usually completed after a project or task where the responder and reviewee(s) were part of the same team. A new web application was created to extend the already existing system to the whole university, with more freedom given to those who create and manage peer reviews.

<hr>
## How does the system work?
The system is split into two perspectives. There is a **student** perspective and an **admin** perspective. A student is able to provide anonymous feedback on their peers, i.e., no-one will be able to see what one student has said about another aside from only the admin that assigned the review request.

The first step is to login to the system. The system utilises the university's Single Sign On, meaning that anyone from across the entire university can use the system so long as they have a University of Dundee email address/login.

**Admin Perspective**

- **Create a template of questions**. Freedom for an admin to ask as many questions as they like and tailor it as much as they want for their peer review, with flexibility to choose from multipile different question types (e.g. open-text, star ratings, satisifed ratings etc)
- **Create a review request**. An admin chooses their template that they created to assign students to the peer review, which has to be completed by a deadline of an admin's choice.
- **View Responses**. All review requests, irrespective of whether they are open or closed, an admin is able to view responses that students submitted and be shown useful statistics like completion rates and total number of people that responded out of those that were assigned.

**Student Perspective**

- **Create Response**. A student answers the questions that an admin has setup in their template on each individual that is in their team, and also leave a comment on their group as a whole if an admin enabled this option in the template.
- **Edit Response**. After a response has been submitted, a student can edit, update and save their response as many times as they like up until the deadline closes.
- **View Response**. Once the deadline for the review request has passed, it's no longer possible for a student to edit their responses. However, they can still view responses they gave for historical reasons.

<hr>

## Project Media

In the system itself, there is a "Help" page which users have access to. The page consists of 7 YouTube videos which are recorded in the narrative of the user. Students are only able to see 3 of the 7 videos which guide them through the student dashboard and completion of a peer review, whereas an admin can see all 7 videos, the additional 4 being a guide through the admin dashboard.

### Admin Dashboard

In the admin dashboard, an admin is able to create a template of questions which are then used to create a review request which is assigned to students. Afterwards, an admin is then able to view the responses that their review request received. It's also possible for any admin to add additional admins from within the dashboard, meaning the system isn't reliant on a singular person for granting permissions. The **YouTube playlist below (4 videos)** shows this in practice, recorded in the narrative of an admin, and available on the "Help" page as previously described.

<iframe width="100%" height="315" src="https://www.youtube.com/embed/videoseries?list=PLVjKnuPH5aeDbgY0ECSRnRGW2ckOby0mG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Student Dashboard

In the student dashboard, a student is able to submit a new response, edit an already existing response, and view responses on review requests that they have been assigned to from an admin. The **YouTube playlist below (3 videos)** shows this in practice, recorded in the narrative of a student, and available on the "Help" page as previously described.

<iframe width="100%" height="315" src="https://www.youtube.com/embed/videoseries?list=PLVjKnuPH5aeCYFDPWbg9MqZNSVaN-wdlt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<hr>

## Technology Stack

The web application was built using [Next.JS](https://nextjs.org/) as a frontend, [Node.JS](https://nodejs.org/en/) as a backend and [MongoDB](https://www.mongodb.com/) for the database. [Material UI](https://mui.com/), which is a [React](https://reactjs.org/) component library for creating user interfaces, was also heavily used throughout the project.

<hr>

## Contact

If you have any questions, interested in the system more generally, then please feel free to reach out to me on my personal email:
<br/>**keillerj538@gmail.com**

<a href="mailto:keillerj538@gmail.com?subject=[QMB.ONE] Peer Review System"><button type="button" class="btn btn-primary btn-lg">Email Me</button></a>
