
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
- **Container1**:
1.MText Manipulation with Interactive Effects (.contoh1)
-   Concept: Using @keyframes to manipulate the position (translate) and rotation (rotate) of elements.

  Result: When the cursor hovers over a paragraph with the .rotate class, the text responds with a dynamic shaking/wobbling effect to enhance user interactivity.

2. Flexible Layout and Transition Animations (.example2)

    Concept: Application of CSS Flexbox with the `justify-content: space-around` property to align child elements horizontally.

    Result: Creates an arrangement of four multicolored boxes that rotate continuously and automatically. The boxes are designed to rotate in opposite directions (clockwise and counterclockwise) using two different variations of @keyframes for rotation.

3. Demonstration of Element Size Calculations/Box Model (.wadah)
Concept: A simulation comparing the browser’s default behavior (content-box) with the use of the `box-sizing: border-box` property.
Results:
Elements without `box-sizing: border-box` will overflow the container’s boundaries because the browser adds the values of `width`, `padding`, and `border` together.
Elements with `box-sizing: border-box` remain precisely within the container because the browser automatically includes the padding and border space in the calculation of the element’s total width (100%).

