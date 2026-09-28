Assignment 2 — Web Development
Student: Sayazhan Berdibayeva
Grup: It-2501
Live Demo: [https://berdibayevaaa.github.io/assignment2/](https://berdibayevaaa.github.io/assignment2/)


What this project is about
In this assignment, I created a web layout for an online book dashboard called "BookHaven". My main goal was to practice CSS Flexbox and CSS Grid without using any external frameworks like Bootstrap[cite: 1]. I decided to combine everything into a clean dashboard look and chose a colorful dopamine-style palette (lavender, soft coral, and mint tones).
Here is how I implemented each part step by step:

## Task 0: Navigation Bar
First, I created the top header for the website[cite: 1].
* I used `display: flex` on the navbar and added `justify-content: space-between` so the logo sits on the left while the navigation links and button stay on the right[cite: 1].
* I also set `align-items: center` to make sure all items are vertically aligned, and used `gap` so the links don't stick to each other[cite: 1].
<img width="1892" height="122" alt="image" src="https://github.com/user-attachments/assets/b69c48a7-6b97-424e-8dfb-9a2666fc64bb" />


## Task 1: Genre Cards Row
Next, I built a row of 3 book genre cards to test Flexbox behavior[cite: 1].
* First, I wrapped them in a container with `display: flex`[cite: 1].
* Then, I added `flex: 1` to each card so they all take up the exact same width automatically[cite: 1].
* Inside the cards, I turned the content into a flex column (`flex-direction: column`) and set `flex-grow: 1` on the text[cite: 1]. This keeps all cards at the same height and pushes the buttons to the bottom evenly[cite: 1].
* Lastly, I added a `:hover` state with `transform: translateY` and a shadow to make it feel interactive[cite: 1].
<img width="1552" height="584" alt="image" src="https://github.com/user-attachments/assets/82eb0e5b-1eae-4332-8332-aaed0ef28fd9" />


## Task 2: Page Grid Layout
After that, I worked on the main page structure using CSS Grid Areas[cite: 1].
* Instead of calculating margins manually, I defined the whole page skeleton with `grid-template-areas`[cite: 1].
* I split it into four clear areas: `header` on top, `sidebar` on the left, `main` for all the content, and `footer` at the bottom[cite: 1].
* I used `240px 1fr` for columns so the sidebar has a fixed width while the main area takes up the remaining space[cite: 1].
<img width="319" height="883" alt="image" src="https://github.com/user-attachments/assets/b34748d7-7302-4052-933d-624316086332" />


## Task 3: Book Cover Gallery
For the gallery, I wanted to showcase 9 book covers in an even 3x3 layout[cite: 1].
* I created a CSS Grid container with `grid-template-columns: repeat(3, 1fr)` and added a `gap` between items[cite: 1].
* To keep the cover pictures looking sharp and prevent them from stretching, I used `object-fit: cover`[cite: 1].
* Then, I added a dark overlay with the book title over each image[cite: 1]. By default, its opacity is set to 0, but when hovering over the card, it smoothly fades in with `opacity: 1`[cite: 1].
<img width="1327" height="1027" alt="image" src="https://github.com/user-attachments/assets/1d829c16-f516-430c-af44-fff7346fc4cd" />
<img width="1004" height="946" alt="image" src="https://github.com/user-attachments/assets/99a0335f-8479-4604-85f8-fe3467190634" />
<img width="311" height="710" alt="image" src="https://github.com/user-attachments/assets/15094508-5cfb-4d0c-b8b6-c79bd4798cbf" />

## Task 4: Featured Releases Section
Finally, I combined both Grid and Flexbox in the bottom section[cite: 1].
* First, I used CSS Grid to split the section into two main columns: the releases list on the left and the curator's note on the right[cite: 1].
* Inside the release cards, I used Flexbox to align the thumbnails, headings, and details neatly[cite: 1].
* I also used Flexbox with `flex-wrap: wrap` for the hashtag badges so they arrange themselves properly[cite: 1].
<img width="1901" height="559" alt="image" src="https://github.com/user-attachments/assets/9917b3ae-7f77-4aef-864f-d5dfa0f8df19" />
<img width="1259" height="776" alt="image" src="https://github.com/user-attachments/assets/8aaa266c-6503-43df-a799-85d75379936c" />
<img width="937" height="754" alt="image" src="https://github.com/user-attachments/assets/47f2f8f1-0bc4-456a-9a6e-62636fde23f2" />
<img width="1024" height="771" alt="image" src="https://github.com/user-attachments/assets/3afb11c0-df0a-48ea-9595-194f3779bde0" />
<img width="894" height="919" alt="image" src="https://github.com/user-attachments/assets/13dd3ecf-9b99-4f44-a9a1-d8f843fa9960" />


## How to check the code
1. Open the repository folders (`task0-navbar`, `task1-cards`, etc.) to view the code for each separate task[cite: 7].
2. Or open the live link above to view the whole dashboard running via GitHub Pages[cite: 1, 12].
