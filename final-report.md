<div align="center">
    <h1 align="center">
        Open Technologies Alliance - Gfoss |  MyUni
    </h1>
    <h2 align="center">
        Final Work Report for the Google Summer of Code 2025 under <span style="color: #f0970a;"> <b> Open Technologies Alliance - Gfoss </b></span> for the <span style="color: #c47b06;"><strong> MyUni </strong></span> project
    </h2>
    <p align="center">
        <img src="./assets/report-banner.jpeg" />
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
    </p>
    <h2> Contributor Info. </h2>
    <div container>
        <table>
            <tr>
                <td width="50%">
                    <h5>&#8226; Name - Adil Kadival </h5> 
                    <h5>&#8226; Organization - <a href="https://github.com/open-source-uom" target="_blank">Open Source Uom (Gfoss)</a> </h5> 
                    <h5>&#8226; Email - <a href="https://mailto:adilkadivala560@gmail.com" target="_blank">adilkadivala560@gmail.com</a> </h5> 
                    <h5>&#8226; GitHub - <a href="https://github.com/adilkadivala" target="_blank">Adil kadivala</a></h5> 
                    <h5>&#8226; Linkedin - <a href="https://www.linkedin.com/in/adilkadivala" target="_blank">Adil kadival</a></h5> 
                    <h5>&#8226; Twitter - <a href="https://x.com/adil_kadival" target="_blank">adil_kadival</a></h5>
                </td>
                <td width="950px">
                <a href="https://github.com/adilkadivala"><img src="./assets/profile.jpeg" height="250px" width="250px;" alt=""/></a>
                </td>
            </tr>
        </table>
    </div>
    <h2> Mentors' Info. </h2>
    <div align="left">
        <h5>&#8226; Mentor - <a href="https://github.com/Tsalmas-Anastasios" target="_blank">Tsalmas Anastasios</a></h5>
        <h5>&#8226; Mentor - <a href="https://github.com/iosifidis" target="_blank">Efstathios Iosifidis</a></h5>
        <h5>&#8226; Assisting Mentor - <a href="https://github.com/dimsparagis0210" target="_blank">Dimitris Sparagis</a></h5>
    </div>
    <br />

</div>

<h2 align="center"> Project Details </h2>

The **MyUni** project is “_a complete University student and faculty management platform_”, It is unified platform designed to modernize and extend the current MyUoM app for Greek universities. In the project I've worked on three repositories, fully responsive and supported with dark and light mode.  

- **myuni-backend** 
- **myuni-frontend-admin** 
- **myuni-frontend-student** 

### myuni-backend

Myuni backend repository containes all server side logic for myuni-stduent and myuni-admin, I've implemeted in the system robust authentication system, a scalable backend, real-time data synchronization with the morden technology like Express.js, Type-Script, with Prisma Orm, and Email service.   

### myuni-frontend-admin

myuni-frontend-admin is the client-side repository containes logic for admin users, In which Admin can handle Academic, and announcement, events, and easily see All users with the role, and can handle easily CMS 

### myuni-frontend-student

myuni-frontend-student is the client-side repository for admin students, In which Student can see thier academic information, and announcement, events, and stduent can make easily website using just drag and drop.
<br />

## GSoC Project Page

- [GSoC 2025 with Open Technologies Alliance - GFOSS - My-uni](https://summerofcode.withgoogle.com/programs/2025/projects/tz6ymx0o)

## GSoC Project Proposal

- [Project Proposal](https://github.com/adilkadivala/GSoC-2025/blob/main/proposal.pdf)

## Project Repository | Organization page

here is a Github organization page, 

- [Open Source UoM](https://github.com/open-source-uom)

## GSoC Blogs

- [My GSoC joourney has started](https://dub.sh/midterm-end)
- [From Dreamer to contributor](https://dub.sh/dreamTocontribut)
- [GSoC midterm](https://dub.sh/gsoc-midterm)
- [GSoC modterm-end](https://dub.sh/midterm-end)

<br />


## Work Summary

### **1. Creating the Design Document**

At the outset of my project, I focused on establishing a strong foundation by creating a comprehensive design document that consisted of a [Product Requirements Document (PRD)](https://github.com/sugarlabs/musicblocks-v4/blob/gsoc-2024/week-11-12/modules/masonry/docs/functional-specification/PRD.md), a [Data Flow Diagram (DFD)](https://github.com/sugarlabs/musicblocks-v4/blob/gsoc-2024/week-11-12/modules/masonry/docs/architecture/MasonryDFD.drawio.png), and an initial technical specification. The PRD outlined the different types of bricks — Data, Expression, Statement, and Block — and described their individual characteristics, such as appearance, interaction methods, and connection points. I also defined how these bricks would function within the Music Blocks environment, considering their color coding, input/output ports, labels, and interactive elements.

In addition, I developed a DFD to illustrate the interactions between the various components of the Masonry framework, such as the bricks, the palette, the workspace, and the stack of bricks. This diagram helped visualize the flow of information and the relationships between different modules, serving as a roadmap for further development.

   <img src="https://github.com/user-attachments/assets/dd5bf1b8-769c-4206-9b3a-d160365996f7" width="650px" />

The initial technical specification was drafted to guide the implementation process. However, as the project evolved and requirements became clearer, I revised this document to better align with the overall objectives. These documents were instrumental in ensuring that all community members were aligned on the framework's goals, requirements, and design principles. They also provided a clear blueprint for the development process, which helped keep the project on track and focused.

### **2. Prototyping Different Brick Stack Approaches**

One of the early challenges I faced was determining the best method for representing and manipulating the bricks in the workspace. To explore different possibilities, I developed three prototypes:

- **SVG Bricks**: I first experimented with creating bricks using scalable vector graphics (SVG). This approach offered flexibility in terms of design and scaling but had some limitations in terms of integrating with HTML elements.
- **Div Bricks**: Next, I created a prototype using HTML div elements styled with CSS. While this method provided good compatibility across browsers, it lacked the scalability and flexibility needed for a dynamic visual programming environment.
- **SVG Bricks with Foreign Object Elements**: Finally, I explored combining SVG elements with HTML using the foreign object element. This approach allowed me to integrate richer content and interactivity within the SVG canvas, making it easier to manipulate bricks with advanced features like drag-and-drop, inline text editing, and context menus.

  <img src="https://github.com/user-attachments/assets/06773e94-dd79-4ba7-ab5f-a22c51d78fd8" width="400px" />
  <img src="https://github.com/user-attachments/assets/a4f2cc14-703d-43a0-b063-35d8fdb3d12a" width="400px" />

After thorough testing and evaluation, I decided to use the third approach — SVG with foreign object elements — due to its superior flexibility, scalability, and compatibility with the drag-and-drop functionality required for the framework.

### **3. Rewriting Brick Components and Classes**

With the final decision on the brick representation method in place, I moved forward with rewriting the brick components and their corresponding classes to align with the finalized design. This involved:

- **Refactoring the Codebase**: I reorganized the brick classes to ensure that each type adhered to its designated properties and functionalities, such as inline text editing, and connection points. I also made sure the bricks were visually distinct, scalable, and compatible with the drag-and-drop functionality.
- **Fixing Bounding Box Scale Errors**: During this process, I identified and fixed several bounding box errors that were affecting the rendering of bricks in the workspace. These fixes ensured that the bricks were accurately represented and properly aligned, which was critical for creating a seamless user experience.
- **Integrating Storybook**: To facilitate development and testing, I integrated Storybook into the project. This tool allowed me to visually render and test each brick component in isolation, making it easier to identify and resolve issues quickly. By rendering the bricks in Storybook, I was able to verify their appearance, behavior, and interactions before integrating them into the main workspace.

**Here are some of the Storybook screenshots:**

<img src="https://github.com/user-attachments/assets/a6b549d4-4772-4e9a-b008-3ee80e173d9f" width="450px" />
<img src="https://github.com/user-attachments/assets/3033dafa-4a27-43ef-a396-5d77b3b978d6" width="450px" />
<img src="https://github.com/user-attachments/assets/3529b2e4-676f-4deb-bf31-d04f24fb426f" width="450px" />
<img src="https://github.com/user-attachments/assets/54a62848-145d-4fb4-8dcb-53cde75d1e4b" width="450px" />

### **4. Creating a Tree Structure for the Brick Stack**

To effectively manage the organization and hierarchy of bricks within the workspace, I developed a tree structure for the stack of bricks. This structure allows for a clear visual and logical representation of how bricks connect and interact, which is particularly useful for managing nested or grouped bricks. The tree-based approach supports complex programming sequences by allowing users to see the relationships between different bricks and manipulate them easily.

![image](https://github.com/user-attachments/assets/45332c84-4cd2-4108-a80c-77f86c5a59dc)

### **5. Creating a Dummy Workspace and Enabling Drag-and-Drop**

To test and refine the brick manipulation features within the Masonry framework, I created a dummy workspace that allowed for drag-and-drop functionality. This involved implementing the core mechanics for dragging bricks from the palette and dropping them onto the workspace, connecting them to other bricks, and rearranging them as needed.

By creating this test environment, I was able to validate the usability and performance of the drag-and-drop functionality.

[Screencast from 02-09-24 03:25:42 PM IST.webm](https://github.com/user-attachments/assets/0d501226-034f-43d1-b7b4-6f0b94c04f0a)

## Pull Requests

| Title                                                                             | Link                                                         | Lines of Code Changed |
| --------------------------------------------------------------------------------- | ------------------------------------------------------------ | --------------------- |
| Add design document for Masonry (previously Project-builder/code-builder)         | [#404](https://github.com/sugarlabs/musicblocks-v4/pull/404) | `+1,475  −0`          |
| docs(masonry): add PRD and DFD                                                    | [#408](https://github.com/sugarlabs/musicblocks-v4/pull/408) | `+972  −0`            |
| feat(masonry): create tech-spec and add demo workspace and render stack of bricks | [#409](https://github.com/sugarlabs/musicblocks-v4/pull/409) | `+4,716 −513`         |
| feat(masonry): create tree for the stack of bricks                                | [#410](https://github.com/sugarlabs/musicblocks-v4/pull/410) | `1,554 −276`          |
| feat(masonry) : Fix errors in Brick and render storybook                          | [#411](https://github.com/sugarlabs/musicblocks-v4/pull/411) | `+2,318 −29`          |
| feat(masonry) : Render dummy Stack of Bricks                                      | [#412](https://github.com/sugarlabs/musicblocks-v4/pull/412) | `+1,818 −4,806`       |

Merged work - https://github.com/sugarlabs/musicblocks-v4/pull/434.

Code can be found [here](https://github.com/sugarlabs/musicblocks-v4/tree/develop/modules/masonry).

## **Conclusion**

Overall, my work on the Masonry project during GSoC 2024 has involved a mix of design, prototyping, and development activities. I began by creating a solid foundation with a thorough design document, explored different implementation methods through prototyping, and iteratively developed and tested the framework's components. Throughout the project, I have documented my progress, shared my findings with the community, and refined the framework based on feedback and evolving requirements.

This experience has not only strengthened my technical skills but also provided valuable insights into the collaborative, iterative nature of open-source development. I look forward to continuing to contribute to the Music Blocks project and helping to create a more accessible and engaging visual programming environment for users around the world.


