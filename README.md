# Assignment 2 — CSS Flexbox & Grid Layouts

 **Student:** Sayazhan Berdibayeva
 **Group:** IT-2501
 **Live Demo:** [https://berdibayevaaa.github.io/assignment2/](https://berdibayevaaa.github.io/assignment2/)

## 📖 Project Overview
This project demonstrates modern layout techniques using pure CSS (Flexbox & Grid) without external frameworks. All individual tasks are consolidated into a cohesive, responsive book sanctuary platform featuring consistent spacing, semantic structure, and interactive hover states.

 Task 0: Navigation Bar (Flexbox)
* Applied `display: flex` with `justify-content: space-between` to separate the logo and action controls.
* Used `align-items: center` to ensure vertical alignment of navigation links and buttons.
* Styled interactive states with smooth transitions.
<img width="1585" height="566" alt="image" src="https://github.com/user-attachments/assets/9ad20a5d-6548-453b-8ac2-fc4d4834cd01" />
<img width="688" height="611" alt="image" src="https://github.com/user-attachments/assets/f769107b-0621-41e0-9fc6-86da8b71263b" />

 Task 1: Genre Cards Row (Flexbox)
* Arranged cards horizontally using `display: flex` and equal spacing via `gap`.
* Utilized `flex: 1` on each card to maintain equal widths across the row.
* Inner card content is organized with `flex-direction: column` and `flex-grow: 1` on paragraphs so buttons stay aligned at the bottom.
* **Hover Interaction:** Implemented a lift effect (`translateY(-6px)`) and deeper box-shadow on `:hover`.
<img width="1587" height="677" alt="image" src="https://github.com/user-attachments/assets/300e8d96-a172-4c75-bb50-ea9a2a0a7111" />
<img width="1416" height="1005" alt="image" src="https://github.com/user-attachments/assets/9c07cdce-1bf0-48f2-84d2-ea9e2846384c" />

 Task 2: Page Grid Skeleton (CSS Grid)
* Structured the overall site layout using CSS Grid with named areas:
  * `header` spanning the top.
  * `main` for primary content and `sidebar` for metadata/about info.
  * `footer` stretching across the bottom.
* Defined layout tracks with `grid-template-columns: 1fr 280px;` and `grid-template-rows: auto 1fr auto;`.
<img width="1587" height="914" alt="image" src="https://github.com/user-attachments/assets/a3a50711-7ca7-4b2a-bac5-98d4fe924224" />
<img width="957" height="888" alt="image" src="https://github.com/user-attachments/assets/b2a37e54-30db-47a9-b621-fdbeb729f1a3" />

Task 3: Featured Book Covers (Grid 3x3)
* Designed a balanced 3×3 gallery using `display: grid` and `grid-template-columns: repeat(3, 1fr)`.
* Applied `object-fit: cover` to preserve image aspect ratios cleanly.
* Added an absolute dark overlay with book titles that smoothly fades in on `:hover` (`opacity: 1`).
<img width="1152" height="900" alt="image" src="https://github.com/user-attachments/assets/a9879fa6-c4dc-4c85-a006-a9a08d182944" />
<img width="1316" height="998" alt="image" src="https://github.com/user-attachments/assets/80cc5863-049f-42fa-88eb-6d4508490dd4" />

Task 4: Combined Showcase & Sidebar
* Built a combined section organizing special project releases on the left and informative details on the right.
* Utilized Flexbox within individual release cards to align covers, text, and action buttons.
* Included interactive genre tag pills utilizing `flex-wrap: wrap`.
<img width="1277" height="542" alt="image" src="https://github.com/user-attachments/assets/fd6ee5ad-c953-475e-b272-ac2a7070e541" />
<img width="1263" height="996" alt="image" src="https://github.com/user-attachments/assets/fb8e1542-1373-470b-a7fd-10b5b21d2de2" />

 Project Summary & Conclusion
This assignment provided a comprehensive, hands-on exploration of core CSS layout mechanisms without reliance on external CSS frameworks or libraries. Throughout the development of BookHaven, the primary objective was to master the distinct structural paradigms of Flexbox and CSS Grid, learning how they complement each other to create intuitive, resilient, and responsive web interfaces.
By establishing a solid architectural foundation with CSS Grid, I was able to define the overall two-dimensional macro-structure of the website—effortlessly orchestrating the header, an expandable main content area, an informational sidebar, and a full-bleed footer. This clear separation of visual concerns ensured that each page region preserved its semantic purpose and spatial hierarchy. In contrast, Flexbox served as the essential tool for one-dimensional micro-layouts: standardizing navigation flow, enforcing equal-height alignment across dynamic content cards, and pinning interactive buttons consistently to the bottom of cards.
Furthermore, integrating advanced CSS properties such as `object-fit: cover` and relative/absolute coordinate positioning enabled sophisticated visual components, including the 3×3 gallery with interactive hover overlays and dynamic card elevation states. Ultimately, consolidating these isolated technical criteria into a single, functional digital platform not only reinforced semantic markup best practices but also demonstrated the efficiency, predictability, and expressive power of modern pure CSS.


