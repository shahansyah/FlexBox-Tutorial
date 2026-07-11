
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=35&pause=1000&color=D90000&center=true&vCenter=true&width=500&height=70&lines=%F0%9F%92%A5+FlexBox+Tutorials+%F0%9F%92%A5" alt="Typing SVG" />
</p>
<p align="center"> 
    <img src="https://img.shields.io/badge/Status-Production-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Version-1.0.2-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Build-Stable-green?style=for-the-badge" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
</p>


>**"DI Sini Gw Membuat Dokumentasi Tentang Apa Itu Flexbox"**--FlexBox adalah Dokumentasi yang sengaja gw buat agar menjadi bahan rujukan pembelajaran yang mudah tanpa harus mengikuti tutorial cukup memahami beberapa atribut dasar maka kalian akan mudah untuk memahami step selanjutnya thanks.

>**“Here, I'm Creating Documentation on What Flexbox Is”**—Flexbox is documentation I created specifically to serve as an easy-to-use learning resource. You don’t need to follow a tutorial; just understand a few basic attributes, and you’ll easily grasp the next steps. Thanks.

## ⚒️ Spesifikasi Arsitektur / Architectural Specifications

This project demonstrates how to use FlexBox in CSS, as outlined in this documentation...
## 📂️ Struktur yang ada di dalamnya / The structure inside it 
|Struktur      |Spesifikasi                          | Specifications                       |
| :------------| :-----------------------------------|--------------------------------------|
| `index.html` | membangun kerangka dasar web        | builds the basic web framework       |     
| `style.css`  | untuk mengatur tampilan HTML        | to style the HTML                    |
| `container1` | penjelasan dasar FlexBox            | basic explanation of FlexBox         |
| `container2` | box-sizing,Display,justify-content  | box-sizing, display, justify-content |
| `container3` | flex-warp,max-width                 | flex-wrap, max-width                 |
| `container4` | transition,overflow                 | transition, overflow                 |
| `container5` | membuat kotak dan tulisan responsive| creating responsive boxes and text   |

---

## 📝 Explanation by structure
 - **container1**:
 - What Are You Doing Here?
- MText Manipulation with Interactive Effects (.contoh1)
-   Concept: Using @keyframes to manipulate the position (translate) and rotation (rotate) of elements.

  Result: When the cursor hovers over a paragraph with the .rotate class, the text responds with a dynamic shaking/wobbling effect to enhance user interactivity.

1. Flexible Layout and Transition Animations (.example2)

    Concept: Application of CSS Flexbox with the `justify-content: space-around` property to align child elements horizontally.

    Result: Creates an arrangement of four multicolored boxes that rotate continuously and automatically. The boxes are designed to rotate in opposite directions (clockwise and counterclockwise) using two different variations of @keyframes for rotation.

2. Demonstration of Element Size Calculations/Box Model (.wadah)
Concept: A simulation comparing the browser’s default behavior (content-box) with the use of the `box-sizing: border-box` property.
Results:
Elements without `box-sizing: border-box` will overflow the container’s boundaries because the browser adds the values of `width`, `padding`, and `border` together.
Elements with `box-sizing: border-box` remain precisely within the container because the browser automatically includes the padding and border space in the calculation of the element’s total width (100%).
4. Semantic Multi-Column Page Structure (.main-container)

    Concept: Creating a component-based web page layout (layouting) that divides content into several supporting columns (sidebars).

    Structural Components:

        .main-sidebar: Used as the main content/article area that contains long blocks of text.

        .sidebar1: Functions as a navigation menu containing a list of hyperlinks using list elements (<ul> and <li>).

        .sidebar2: Functions as a secondary column or additional information area on the side of the page.

    Result: This structure is designed to be styled using CSS Flexbox or Grid so that the three divs can be arranged horizontally into a responsive 3-column layout.

 - **container2**:
 - What Are You Doing Here?

    Creating a Main Container (.container2): You wrap all three services in a single large box with a maximum width of 800px, neatly centered on the page (margin: 50px auto), and give it a thick decorative frame with a carved pattern (groove).

    Applying the Content Card Design (.service): You establish a uniform set of rules for each service card, such as adding space inside the card (padding: 20px) and spacing between cards vertically (margin-bottom: 20px).

    Creating a Unique Identity Using Multi-Classes: You use class combinations (such as .service.one, .service.two, etc.) to color the background of each card specifically with different colors (Red, Pink, and Brown) and frame them with a thin black line.

    Box Model Consistency: You reapply `box-sizing: border-box` to the container and cards to ensure that element sizing remains accurate and precise, and does not overflow due to the addition of padding or borders.
 - **container3**:
 - What Are You Doing Here?

    1.Creating a Flexible Gallery with a Container (.container3): You enable Flexbox (display: flex) on the gallery’s main container, then add a crucial property: flex-wrap: wrap. This property forces the images to wrap to the next line instead of crowding together side by side. This container also features a striking blue-to-yellow-green gradient.

    2.Setting the Default Image Size (Mobile View): By default, you set the .thumbnail class to have a width of 50%. This means that on small screens, the images will automatically be split into two columns side by side (since $50\% \times 2 = 100\%$).

   3.Applying Media Queries for Responsiveness (Laptop View): You add the @media (min-width: 600px) rule. When the website is opened on a screen wider than 600px (such as a tablet or laptop):

⚒️The width of `.thumbnail` changes to 25%, so the images automatically rearrange into 4 columns side by side ($25\% \times 4 = 100\%$).

⚒️You also change `.container2` (from the previous code)—which was originally stacked vertically—to be arranged horizontally side-by-side (`display: flex; justify-content: space-between;`) with each service occupying 30% of the width.
 - **container4**:
 - What Are You Doing Here?

    Creating a Card Grid Layout: You wrap your list of favorite heroes using a `.container4` that enables Flexbox (`display: flex`) and `flex-wrap: wrap`. This causes the hero cards to line up side by side and automatically wrap neatly to the bottom, forming new rows when space runs out.

    Designing a Modern Card Component: You create a modern .card structure with a static width of 300px, gently rounded corners (border-radius: 20px), a light gray background, and the overflow: hidden property so that the hero image in the header is neatly cropped to follow the card’s curve.

    Implementing Micro-Interactions:

        You’ll add a custom transition effect using the timing function `cubic-bezier(0.25, 1, 0.1, 1)` to manipulate the size (transform) and shadow (box-shadow).

        Interactive Effect: When the mouse cursor hovers over a card (.card:hover), the card significantly enlarges by 140% (scale(1.4)) and smoothly reveals a very thick black shadow beneath it. This creates a visual effect as if the card is floating forward toward the user’s screen.

  - **container5**:
 - What Are You Doing Here?  


    Creating a Static Container (.container5): You create a perfectly square container measuring 500px x 500px with a thick black border, centered on the page, and enable Flexbox mode (display: flex).

    The Perfect Centering Trick with margin: auto: On .kotak1, you set the margin property to margin: auto. Since its parent (.container5) is a Flex container, setting margin: auto on a child element automatically pushes that box exactly to the center of its container, both vertically and horizontally.

    Positioning Text Inside a Box: You can also make `.kotak1` a Flex container and set `margin: auto` on the `span` element inside it. The same trick works again: your name will automatically be centered both vertically and horizontally within `.kotak1`.

## Okay, I guess that’s all for the documentation I’ve put together. I hope it’s useful to you and helps with your studies 😊️.
 ---
