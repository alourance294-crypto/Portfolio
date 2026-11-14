# Andile Lourence Nhleko
## Junior Web Developer

---

## Contact

- **Phone:** 072-489-0230
- **Email:** 231269552@mycput.ac.za
- **LinkedIn:** linkedin.com/in/andile-nhleko-a95b5b350
- **Address:** 143 Sir Lowry Rd, Woodstock, Cape Town, 8001

---

## Profile

A Junior Web Developer with a strong foundation in HTML5, CSS3, and JavaScript,
focused on building responsive and user-friendly websites. Currently completing a
Diploma in ICT while developing practical web projects and continuously improving
front-end development skills. Passionate about clean code, modern design, and
learning new web technologies.

---

## Education

**Methula High School**
Matric — 2022

**Cape Peninsula University of Technology**
Diploma in ICT, Major in Multimedia — 2024–2026

---

## Skills

- **Web Technologies:** HTML, CSS, JavaScript
- **Programming Languages:** Python, PHP (in progress)
- **Frameworks:** Bootstrap
- **Soft Skills:** Teamwork, Communication, Problem-solving

---

## Tools

- VS Code
- PyCharm
- XAMPP & WAMP
- MySQL

---

## Work Experience

**Web Developer** — Tertiary Projects (2024–Present)

- *Personal Portfolio Website (2024):* Designed and developed a personal website
  portfolio showcasing projects and skills. Implemented responsive design principles
  to ensure accessibility on various devices.
- *Web Development Project (University Assignment, 2025):* Created a web application
  using HTML, CSS, and JavaScript. Collaborated with peers to enhance user experience
  through effective design.

---

## References

**Ms. Nontsikelelо Mahlutshana**
Administration (Faculty Assistant)
- Phone: +27 21 460 3107
- Email: MahlutshanaН@cput.ac.za

**Faculty Contact**
- Phone: +27 21 460 9010
- Email: vukuzan@cput.ac.za

---

# Portfolio Reflections (STAR Method)

## Reflection 1: Coding my CV in Markdown

**Situation:** I needed to create a professional CV that would display correctly on GitHub and be version-controlled.

**Task:** Write my entire CV using only GitHub Flavoured Markdown (GFM) without using PDFs or word processors.

**Action:** I learned Markdown syntax including headers (`#`), horizontal rules (`---`), bold text (`**`), and lists (`-`). I structured my CV into clear sections: Contact, Profile, Education, Skills, Tools, Work Experience, and References. I committed changes incrementally to track my progress.

**Result:** My CV is now fully coded in Markdown, displays cleanly on GitHub, and can be updated easily with git commits. This demonstrates my ability to document myself using developer tools.

---

## Reflection 2: Mock Interview Video Experience

**Situation:** As part of work readiness training, I needed to demonstrate my communication and interview skills by recording a mock interview.

**Task:** Record a 2-3 minute professional mock interview video answering common ICT interview questions and embed it into my GitHub portfolio.

**Action:** I prepared answers using the STAR method for behavioral questions like "Tell me about a challenging project." I used my smartphone in a quiet room with good lighting, practiced my responses to maintain eye contact with the camera, and edited the video for clarity. I then uploaded it to YouTube as an unlisted video and embedded it using an iframe.

**Result:** The video showcases my confidence, communication skills, and technical knowledge. I received positive feedback from peers on my clear explanations and professional demeanor.

---

## Reflection 3: Publishing on GitHub Pages

**Situation:** I needed to deploy my static Markdown portfolio to the live web so potential employers could view it without needing a GitHub account.

**Task:** Configure GitHub Pages to serve my `README.md` file as a live website at a custom URL.

**Action:** I created a repository named `andilenhleko.github.io` (matching my GitHub username). I uploaded my `README.md` and any images to the main branch. Then I went to Settings > Pages, selected "Deploy from branch" under source, chose the `main` branch with `/root` folder, and saved. I waited approximately 2 minutes for the GitHub Actions build to complete.

**Result:** My portfolio is now live at [https://andilenhleko.github.io]( https://alourance294-crypto.github.io/Portfolio/). I can share this URL on my CV and LinkedIn. I learned how static site hosting works and gained confidence with GitHub's deployment tools.

---

# Mock Interview Video

Below is my mock interview video demonstrating my communication skills and technical knowledge.

## 🎥 Demo Video

Click the image below to watch my demo.

[![Demo Video](https://img.youtube.com/vi/EJrncQMGuf0/hqdefault.jpg)](https://www.youtube.com/shorts/EJrncQMGuf0)

# PRP370S Digital Agile Portfolio – UniMarket 
**Date Range:** 14 July – 23 October 2026  
**Tech Stack:** React 18 + Vite, Node.js + Express, MySQL, Brevo SMTP, PayFast  

---

## 1. Agile Team Charter

### Agile Team Charter: Evidence

**Shared Purpose**  
Our goal was to design and build UniMarket, a verified student-to-student marketplace for Cape Peninsula University of Technology (CPUT) students to safely buy and sell affordable textbooks, laptops, and study essentials.

**Team Members and Focus Areas**  
* **Andile Nhleko (AN) – Frontend & UI/UX:** Designed the wireframes and built the React + Vite pages, responsive layouts, navigation, product browsing, search bar, and user profile screens.
* **Aliziwe Ncoko (AN) – User Research & Content:** Led the student survey, analyzed user feedback, created user personas, wrote Help Center content, and structured presentation slides.
* **Lihle Tuta (LT) – Backend & Database:** Set up the Node.js and Express server, designed the MySQL database tables, and built the REST API endpoints.
* **Ntotole Mpalakane (NM) – Security & Integrations:** Integrated Brevo SMTP for 6-digit student email verification, set up PayFast payments, handled password/code hashing, and built the meetup code logic.
* **Xolile Ludidi (XL) – Testing, QA & Trello Management:** Managed our Trello board, wrote test cases, tested features across devices, and tracked bug fixes before demos.

**Working Agreements**  
* **Daily Check-Ins:** Quick 15-minute standups every morning at 09:00 to share progress and flag blockers early.
* **GitHub Workflow:** Everyone worked on separate branches in our shared repository and tested changes before merging into `main`.
* **Task Tracking:** Every task had to be logged on Trello and moved across `Product Backlog`, `In progress`, and `Completed`.
* **Decision Making:** Any disagreement on design or features was settled by checking our survey findings and voting as a group within 24 hours.

![Agile Team Charter](./team-charter.png)

### Agile Team Charter: Reflection
Putting our Team Charter together early helped us avoid confusion once coding started. In Week 1, we struggled with late replies in our group chat and different versions of our presentation slides floating around. Going back to our charter rules—especially the 09:00 daily check-ins and keeping all tasks on Trello—made a big difference by Week 3. Because each person owned a clear area of the project, we could build the frontend, backend, and security features at the same time without overwriting each other's work.

---

## 2. User Stories and Tasks

### User Stories and Tasks: Evidence

We wrote our user stories from the perspective of CPUT students and broke each one into smaller checklist items on our Trello cards:

* **Student Verification (US-01):** As a CPUT student, I want to register and verify my account using a 6-digit email code so that I know I am dealing with real students.  
  * *Tasks (Authentication System – 17/17 completed):* Design signup flow, build login and signup forms, validate email and password inputs, encrypt passwords, send hashed 6-digit codes via Brevo SMTP, build auth APIs, and test login/logout sessions.
* **Browsing and Searching (US-02):** As a student buyer, I want to search and filter items by category and price so that I can quickly find affordable textbooks and laptops.  
  * *Tasks (Marketplace Functionality – 18/18 completed):* Build product listing and detail pages, add search bar, create category and price filters, connect product APIs, and test mobile responsiveness.
* **Managing Listings (US-03):** As a student seller, I want to upload, edit, and remove my own listings with photos so that I can sell items I no longer need.  
  * *Tasks (Frontend & Marketplace – 36/36 completed):* Create upload form, build edit and delete actions, connect upload endpoints to MySQL, and test image uploads.
* **In-App Messaging (US-04):** As a buyer or seller, I want to message the other person inside UniMarket so that we can arrange safe campus meetups without sharing private numbers.  
  * *Tasks (Integration – 18/18 completed):* Build chat screen, create message database model, connect chat routes to frontend, and verify message delivery.
* **Secure Checkout and Meetup Code (US-05):** As a buyer, I want to pay through PayFast and get a 6-digit meetup code so that my payment is recorded safely before the handover.  
  * *Tasks (API Design & Backend – 35/35 completed):* Create order model, connect PayFast API callbacks, generate hashed 6-digit meetup codes, and test payment status updates.
* **Seller Ratings (US-06):** As a student user, I want to rate and review sellers after a completed purchase so that reliable traders build trust on campus.  
  * *Tasks (Marketplace Functionality – 18/18 completed):* Create review model, build rating UI, and restrict reviews to verified completed orders.
* **Admin Oversight (US-07):** As an administrator, I want a dashboard to view verification logs and manage users so that the platform stays safe.  
  * *Tasks (Backend & Testing – 35/35 completed):* Add role-based access middleware, build admin endpoints, and test user/verification management.

![Trello User Story and Tasks](./trello-user-stories.png)

### User Stories and Tasks: Reflection
Writing user stories from a student's point of view kept us focused on real problems—like avoiding scams and finding cheaper study gear—instead of adding unnecessary features. Breaking each story into small Trello checklist items made bigger features like PayFast integration and email verification feel much less overwhelming. It also helped us realize in Week 2 which features were realistic for our skill level and allowed us to assign tasks based on what each teammate was best at.

---

## 3. Product Backlog

### Product Backlog: Evidence

Our Product Backlog consisted of 16 prioritized Trello cards covering research, design, development, testing, and deployment. Security and core marketplace functions were prioritized first, and all 16 cards reached 100% checklist completion:

1. **Discovery & Research (19/19):** Defined project goals, scope, target users, competitor comparison, user personas, and user journeys.
2. **Conduct Survey & Data Collection (18/18):** Created the student survey, shared links, collected responses, removed duplicates, and organized preferences.
3. **Data Analysis & Insights (16/16):** Analyzed buying and selling habits, identified student pain points, and summarized feature recommendations.
4. **UX & UI Design (19/19):** Chose our color palette and typography, designed the logo, and created screen designs for login, signup, home, marketplace, chat, profile, and checkout.
5. **Wireframes & Prototyping (18/18):** Sketched and digitized wireframes for all 12 screens, linked user flows, and tested navigation.
6. **UI Design System (18/18):** Created reusable buttons, cards, forms, icons, spacing rules, and accessibility checks.
7. **System Architecture (18/18):** Mapped out our frontend, backend, and MySQL database layers, data flow diagrams, and security structure.
8. **API Design & Planning (18/18):** Planned all GET, POST, PUT, and DELETE endpoints, request/response formats, validation rules, and error handling.
9. **Backend Development (17/17):** Configured Express, connected MySQL, built User, Product, Category, Message, Order, and Review models, and tested routes.
10. **Frontend Development (18/18):** Built the React + Vite pages, navigation bar, reusable components, API connections, and responsive layouts.
11. **Authentication System (17/17):** Built registration, login, logout, password reset, input validation, password hashing, and Brevo 6-digit email verification.
12. **Marketplace Functionality (18/18):** Implemented product listings, uploads, search, category/price filters, favorites, and ratings/reviews.
13. **Integration (18/18):** Connected the React frontend to the Express backend, MySQL database, chat module, and PayFast checkout flow.
14. **Testing & Debugging (18/18):** Executed test cases for login, uploads, search, filters, chat, and APIs, logged bugs, and retested fixes.
15. **Deployment Preparation (18/18):** Configured environment variables, hosted the live build on Netlify, verified SSL and database backups, and ran security checks.
16. **Final Presentation & Submission (18/18):** Built presentation slides, added system diagrams and screenshots, rehearsed our demo, and submitted project files.

![Product Backlog Trello Board](./trello-product-backlog.png)

### Product Backlog: Reflection
Keeping an ordered Product Backlog stopped us from wasting time on minor visual tweaks before the core system worked. After receiving peer feedback in Week 2, we moved trust and security items—such as CPUT student email verification, password hashing, and PayFast verification—to the top of our priority list. Reviewing the backlog regularly helped us adjust our scope when we ran into technical challenges while still keeping track of everything needed to finish the project.

---

## 4. Sprint Backlog

### Sprint Backlog: Evidence

We managed our workflow on Trello using a three-column Kanban board (`Product Backlog`, `In progress`, `Completed`) and pulled cards into active work across our sprints:

* **Discovery & Design Phase (14 – 24 July 2026):** Focused on validating the problem and finalizing wireframes. Cards completed: *Discovery & Research*, *Conduct Survey & Data Collection*, *Data Analysis & Insights*, *UX & UI Design*, *Wireframes & Prototyping*, and *UI Design System*.
* **Sprint 1 – Core Website Build (28 – 31 July 2026):** Focused on delivering a working website where users could register, browse, search, and message sellers. Cards completed: *System Architecture*, *API Design & Planning*, *Frontend Development*, and *Marketplace Functionality*.
* **Sprint 2 – Security & Payments (4 – 7 August 2026):** Focused on replacing simulated flows with real security and payment tools. Cards completed: *Backend Development*, *Authentication System*, and *Integration* (including Brevo SMTP verification, PayFast integration, cryptographic hashing, meetup codes, and the Admin Dashboard).
* **Sprint 3 – Final Polish & Deployment (20 – 23 October 2026):** Focused on stability, Help Center content, and final submission readiness. Cards completed: *Testing & Debugging*, *Deployment Preparation*, and *Final Presentation & Submission*.

![Sprint Backlog Trello Board](./trello-sprint-backlog.png)

### Sprint Backlog: Reflection
Breaking the work into short sprints kept us focused on clear weekly goals instead of leaving everything for the end. In Sprint 1, aiming for a working demo by Friday forced us to fix our mobile CSS and search bar bugs quickly. In Sprint 2, dedicating the entire week to security and payments gave us enough time to test Brevo email codes and PayFast callbacks properly without breaking the pages we had already built.

---

## 5. Agile Logbook

### Agile Logbook: Evidence

#### Week 1: Presentation Preparation & Initial Pitch (14 – 17 July 2026)

**Tuesday, 14 July 2026**  
* **Completed:** Met as a team to plan the UniMarket pitch, reviewed the slide outline, and divided speaking sections.  
* **Next:** Write my section of the slides, practice my delivery, and confirm alignment with the group.  
* **Impediments:** Slow replies in the group chat caused delays, and sharing slide files back and forth caused minor formatting shifts.

**Wednesday, 15 July 2026**  
* **Completed:** Finished my slides, combined everyone's sections, and ran through the presentation several times to check timing.  
* **Next:** Deliver my section clearly during class and help teammates if any technical issues come up.  
* **Impediments:** Our class timetables clashed, making it hard to find a time when all five of us could rehearse together.

**Thursday, 16 July 2026**  
* **Completed:** Presented the UniMarket concept to the class, explaining how the platform makes campus buying and selling safer and cheaper.  
* **Next:** Review the feedback we received and note what we can improve in our next presentation.  
* **Impediments:** Minor file-opening delays before presenting added unnecessary stress.

**Friday, 17 July 2026**  
* **Completed:** Held a team debrief to discuss what went well and where our communication fell short.  
* **Next:** Start preparing earlier next week and keep all project files in one shared folder.  
* **Impediments:** None.

---

#### Week 2: Feedback, Redesign & Second Presentation (21 – 24 July 2026)

**Tuesday, 21 July 2026**  
* **Completed:** Reviewed peer feedback from our first pitch and started updating our slides to make UniMarket's value clearer.  
* **Next:** Finish revising my slides and research simple, student-friendly e-commerce layouts.  
* **Impediments:** Balancing all the peer suggestions without overcrowding our slides.

**Wednesday, 22 July 2026**  
* **Completed:** Shared updated slides with the group and brainstormed core features: seller ratings, in-app chat, and clean category navigation.  
* **Next:** Sketch rough wireframes for the main screens and check in on teammates' progress.  
* **Impediments:** Deciding which features we could realistically build within our timeframe.

**Thursday, 23 July 2026**  
* **Completed:** Created initial wireframe sketches for the homepage, marketplace, and product detail screens and gathered team feedback.  
* **Next:** Turn the sketches into clean digital wireframes and rehearse the updated presentation.  
* **Impediments:** Agreeing on a consistent color scheme and layout style across all screens.

**Friday, 24 July 2026**  
* **Completed:** Finalized the digital wireframes, completed our full presentation run-through, and incorporated user ratings and messaging into the prototype flow.  
* **Next:** Practice answering potential Q&A questions about how our platform works.  
* **Impediments:** None.

---

#### Week 3: Sprint 1 – Building the Core Website (28 – 31 July 2026)

**Tuesday, 28 July 2026**  
* **Completed:** Kicked off development, set up our shared GitHub repository and local environments, and divided coding tasks.  
* **Next:** Build the homepage layout, navigation bar, and initial product listing page.  
* **Impediments:** A few teammates had local environment setup issues, which we resolved together.

**Wednesday, 29 July 2026**  
* **Completed:** Finished the homepage and product listing pages, added a search bar, and started building the product detail page.  
* **Next:** Complete the product detail page, start the login/registration screens, and check layouts on mobile viewports.  
* **Impediments:** CSS elements were misaligning on smaller mobile screens, and the search bar needed debugging.

**Thursday, 30 July 2026**  
* **Completed:** Fixed the mobile CSS alignment bugs, got the search filter working, finished the login/registration UI, and helped debug the chat screen.  
* **Next:** Test all pages together and fix any remaining bugs before our live demo.  
* **Impediments:** Login sessions occasionally dropped, and chat messages required manual refreshing to appear.

**Friday, 31 July 2026**  
* **Completed:** Fixed the login session and chat refresh bugs, tested the full user journey, and updated our presentation for a live demo.  
* **Next:** Rehearse the live demo flow and prepare for technical questions.  
* **Impediments:** Concern about Wi-Fi stability during the live demonstration.

---

#### Week 4: Sprint 2 – Security Hardening & Payment Integration (4 – 7 August 2026)

**Tuesday, 4 August 2026**  
* **Completed:** Refined navigation routing across all pages and improved search filtering speed on the active product list.  
* **Next:** Polish the product detail layout and map out frontend fields for student email verification.  
* **Impediments:** Making sure new commits did not break existing working pages on the shared branch.

**Wednesday, 5 August 2026**  
* **Completed:** Finalized responsive layouts for the cart and checkout screens and reviewed the database fields needed for order tracking.  
* **Next:** Build the user profile settings view and prepare the frontend checkout form for PayFast.  
* **Impediments:** Ensuring our database order table properly stores external payment transaction references.

**Thursday, 6 August 2026**  
* **Completed:** Added profile settings options, connected the frontend registration flow to the Brevo SMTP 6-digit email verification API, and started the Admin Dashboard UI.  
* **Next:** Complete the PayFast checkout flow and test the 6-digit meetup confirmation code screen.  
* **Impediments:** Testing PayFast sandbox callbacks thoroughly to prevent duplicate order entries.

**Friday, 7 August 2026**  
* **Completed:** Completed PayFast checkout integration, verified that passwords, OTP codes, and transaction references are hashed, finished the Admin Dashboard, and deployed a test build to Netlify.  
* **Next:** Build the Help Center (FAQ) page and verify secure logout redirects.  
* **Impediments:** Confirming that the order confirmation screen updates reliably after every PayFast callback.

---

#### Week 5: Sprint 3 – Final Polish & Presentation Readiness (20 – 23 October 2026)

**Tuesday, 20 October 2026**  
* **Completed:** Audited our live Netlify site for broken links or styling glitches and drafted the Help Center (FAQ) page explaining email verification and meetup codes.  
* **Next:** Test registration, login, and password reset across both desktop and mobile browsers.  
* **Impediments:** Minor session token persistence issue on page reload, which we patched in the auth middleware.

**Wednesday, 21 October 2026**  
* **Completed:** Finished the Help Center (FAQ) page, verified that logout clears user sessions cleanly, and checked all 16 Trello cards against our live features.  
* **Next:** Run full end-to-end tests covering item uploads, chat, PayFast checkout, and seller ratings.  
* **Impediments:** Handling edge cases like empty form submissions and oversized image uploads.

**Thursday, 22 October 2026**  
* **Completed:** Added input and file-size validation, completed full end-to-end testing from signup to seller rating, and verified our MySQL backups.  
* **Next:** Finalize our GitHub portfolio documentation and run a timed rehearsal of our final presentation.  
* **Impediments:** None.

**Friday, 23 October 2026**  
* **Completed:** Verified all screenshots and sections in our GitHub portfolio and completed our final team walkthrough of the live UniMarket platform.  
* **Next:** Submit the GitHub Pages link on Blackboard and present our final project.  
* **Impediments:** None.

### Agile Logbook: Reflection
Writing daily standup entries helped us spot problems early instead of letting them pile up before presentations. Looking back across the five weeks, I can see clear progress—from early communication hiccups in Week 1 and mobile CSS issues in Week 3, to smoothly integrating Brevo email verification and PayFast payments in Week 4. Recording our blockers each day forced us to solve technical issues immediately, and acting on peer feedback in Week 2 turned UniMarket into a much stronger, safer product for students.
