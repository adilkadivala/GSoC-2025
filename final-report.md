<div align="center">
    <h1 align="center">
        Open Technologies Alliance - GFOSS | MyUni
    </h1>
    <h2 align="center">
        Final Work Report for Google Summer of Code 2025 under <span style="color: #f0970a;"> <b>Open Technologies Alliance - GFOSS</b></span> for the <span style="color: #c47b06;"><strong>MyUni</strong></span> project
    </h2>
    <p align="center">
        <img src="./assets/report-banner.jpeg" />
    </p>
    <h2> Contributor Info </h2>
    <div container>
        <table>
            <tr>
                <td width="50%">
                    <h5>&#8226; Name - Adil Kadival </h5>
                    <h5>&#8226; Organization - <a href="https://github.com/open-source-uom" target="_blank">Open Source UoM (GFOSS)</a> </h5>
                    <h5>&#8226; Email - <a href="https://mailto:adilkadivala560@gmail.com" target="_blank">adilkadivala560@gmail.com</a> </h5>
                    <h5>&#8226; GitHub - <a href="https://github.com/adilkadivala" target="_blank">Adil Kadivala</a></h5>
                    <h5>&#8226; LinkedIn - <a href="https://www.linkedin.com/in/adilkadivala" target="_blank">Adil Kadival</a></h5>
                    <h5>&#8226; Twitter - <a href="https://x.com/adil_kadival" target="_blank">adil_kadival</a></h5>
                </td>
                <td width="950px">
                <a href="https://github.com/adilkadivala"><img src="./assets/profile.jpeg" height="250px" width="250px;" alt=""/></a>
                </td>
            </tr>
        </table>
    </div>
    <h2> Mentors' Info </h2>
    <div align="left">
        <h5>&#8226; Mentor - <a href="https://github.com/Tsalmas-Anastasios" target="_blank">Tsalmas Anastasios</a></h5>
        <h5>&#8226; Mentor - <a href="https://github.com/iosifidis" target="_blank">Efstathios Iosifidis</a></h5>
        <h5>&#8226; Assisting Mentor - <a href="https://github.com/dimsparagis0210" target="_blank">Dimitris Sparagis</a></h5>
    </div>
    <br />
</div>

# Table of Contents

1. [Project Overview](#project-overview)
2. [Repositories](#repositories)
3. [Work Summary](#work-summary)

   * [1. Designing UI/UX](#1-designing-uiux)
   * [2. Frontend Development](#2-frontend-development)
   * [3. Backend Development](#3-backend-development)
   * [4. DevOps & Deployment](#4-devops--deployment)
4. [Challenges & Learnings](#challenges--learnings)
5. [Conclusion](#conclusion)

---

## Project Overview

The **MyUni** project is a **comprehensive student and faculty management platform** designed to modernize the existing MyUoM app for Greek universities. It aims to deliver a unified solution that supports students, faculty, and administrators through responsive design, modern tooling, and extensible features.

During **Google Summer of Code 2025**, I contributed to **end-to-end development** across design, frontend, backend, CI/CD, and deployment. My contributions ensured that the MyUni platform is scalable, user-friendly, and production-ready.

---

## Repositories

I actively worked on three repositories, all supporting light/dark themes and responsive layouts:

* **myuni-backend** – Server-side logic, APIs, authentication, caching, and email services.
* **myuni-frontend-student** – Student portal with academic details, announcements, and a drag-and-drop website builder.
* **myuni-frontend-admin** – Admin portal with CMS, user management, and event control.

---

## Work Summary

### 1. Designing UI/UX

At the start, I created layouts in **Figma** for both student and admin portals. The focus was on:

* Modern, clean, and minimal design.
* Accessibility standards.
* Fully responsive layouts for desktop, tablet, and mobile.
* Support for light and dark themes.

**Examples**:

* **Auth Pages**

<img src="./assets/auth.png" />

* **Student Portal Layout**

<img src="./assets/student-portal.png" width="900px"/>

* **Admin Portal Layout**

<img src="./assets/admin-portal.png" width="900px"/>

---

### 2. Frontend Development

After design approval, I built the portals with **React (Vite) + TypeScript**, **ShadCN**, and **Tailwind CSS**. Key contributions include:

* **CMS (Admin):** Built using **Tiptap editor**, enabling admins to create and manage rich content.
* **Website Builder (Student):** Implemented a drag-and-drop page builder with **Puck Editor**, including ready-to-use responsive components.
* **Error Boundaries:** Prevented full app crashes by isolating component-level errors.
* **Reusable Components:** Followed best practices for maintainability and scalability.

---

### 3. Backend Development

The backend was implemented with **Express.js, TypeScript, Prisma ORM, PostgreSQL**, and **Redis** for caching. Major contributions include:

* **Authentication system** with secure sessions.
* **Email service integration** for OTP and verification.
* **API development** tested with Postman and integrated with the frontend.
* **Scalable architecture** using an OOP-based project template.

This was my first time adapting to an OOP backend template, which proved challenging but greatly enhanced my skills.

---

### 4. DevOps & Deployment

To ensure a production-ready system, I focused on DevOps and hosting:

* **CI/CD Pipelines:** Automated build, test, and deployment workflows using GitHub Actions.
* **Dockerization:** Built Docker images for both frontend and backend services.
* **AWS Deployment:** Hosted the complete application stack on **AWS EC2** for reliability and scalability.

---

## Challenges & Learnings

* **Challenge:** Adapting to OOP backend architecture.

  * **Learning:** Improved understanding of structured code, design patterns, and modularization.

* **Challenge:** Ensuring full responsiveness and accessibility.

  * **Learning:** Strengthened CSS and responsive design expertise.

* **Challenge:** Implementing CI/CD pipelines and Docker orchestration.

  * **Learning:** Gained real-world DevOps skills for continuous integration and delivery.

---

## Conclusion

My GSoC 2025 journey with **Open Technologies Alliance - GFOSS** has been transformative. I contributed across:

* Designing interfaces with Figma.
* Developing student and admin portals with React, TypeScript, and Tailwind.
* Building backend services with Express.js, Prisma, and PostgreSQL.
* Setting up Dockerized deployments and automated CI/CD pipelines.
* Hosting the system on AWS for production-readiness.

This experience strengthened my skills in **full-stack development, scalable architectures, DevOps, and open-source collaboration**.

### Looking Forward

I plan to continue contributing to MyUni by:

* Expanding features like analytics and advanced personalization.
* Improving test coverage and developer documentation.
* Supporting wider university adoption.
* Mentoring future contributors who join GSoC.

This project marks a milestone in my open-source career, and I am excited to remain part of the community and contribute further. Love you Open-Sourec and Thanks to `Open Technology (GFOSS)` for giving me this Oppertunity.
