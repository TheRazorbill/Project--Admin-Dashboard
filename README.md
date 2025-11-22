# Admin Dashboard

<img width="1919" height="1011" alt="Screenshot 2025-11-22 071005" src="https://github.com/user-attachments/assets/a37c8c98-5661-4e16-9d71-dc11a8509186" />

[🔴 Live Demo](https://seu-usuario.github.io/admin-dashboard/) | [📄 The Odin Project Assignment](https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-admin-dashboard)

## 📝 About the Project

This project is a solution to the **Admin Dashboard** assignment from **The Odin Project** (Intermediate HTML and CSS Course).

The main objective of this assignment was to build a complex dashboard layout using **CSS Grid**. It involved translating a static design file into a functional web page, focusing on layout structure, positioning, and semantic HTML.

### 🎯 Objectives & Requirements
- Use **CSS Grid** for the main layout (Sidebar, Header, Main Content).
- Practice nesting Grid containers within other Grid containers.
- Structure the layout using semantic HTML elements.
- Integrate external assets (SVG icons and Google Fonts).

## 🛠️ Built With

- **HTML5**: Semantic markup for structure.
- **CSS3**:
  - **CSS Grid**: Used for the macro layout and complex component positioning.
  - **Flexbox**: Used for aligning items within smaller components (like buttons and user info).
  - **CSS Variables**: For color scheme management.
- **Assets**:
  - Icons: [Material Design Icons](https://materialdesignicons.com/)
  - Font: [Roboto](https://fonts.google.com/specimen/Roboto)

## 🧩 Features

- **Sidebar Navigation**: Branding and navigational links laid out with Grid.
- **Header Section**: Includes a search bar, notification icons, and user profile information.
- **Main Content Area**:
  - **Projects Grid**: A card-based layout displaying current projects.
  - **Announcements & Trending**: Side sections utilizing distinct grid areas.

## 💡 What I Learned

This project reinforced my understanding of two-dimensional layouts. Specifically:

1.  **Grid Areas vs. Line-based positioning**: I practiced defining explicit grid templates to manage the sidebar and header relationship.
2.  **Nesting**: Learning that Grids can (and often should) be nested to create modular layouts.
3.  **Layout Strategy**: Breaking down a visual design into rectangular regions before writing code.

```css
/* Example of the main grid layout structure used */
.container {
  display: grid;
  grid-template-columns: 1fr 4fr;
  grid-template-rows: auto 1fr;
  grid-template-areas:
    "sidebar header"
    "sidebar main";
}
