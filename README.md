# Home-Based Business Website for Moms

This project is a website designed to inspire and empower single moms and stay-at-home housewives to start their own home-based businesses. The homepage features a warm, intuitive, and emotionally resonant experience, crafted to guide users seamlessly through the journey of discovering and starting their dream business.


# Project Requirements Documentation

This folder contains all the necessary files to start developing the VentureStart website. Below is a brief description of each file and its purpose:

## Color Scheme 
See the file `colors.txt' for hex values of color scheme.


## Content Files

- **content_home.md** - Sample content for the homepage, including section titles, marketing copy, and button text. Use this file as a reference for populating the homepage sections.

- **dog-walking-service.md** - Example Hugo content file with complete front matter and markdown content for a business idea detail page. This serves as a template for all business idea pages and demonstrates the correct structure, formatting, and content organization.

## Mockups

- **mockup_home.html** - HTML mockup of the homepage with styling and structure. This demonstrates the visual layout, including the hero section, features section, business idea cards, and benefits section.

- **mockup_listings.html** - HTML mockup of the business ideas listing page, showing the grid layout of business idea cards, filtering system, and navigation elements.

- **mockup_detail.html** - HTML mockup of a detailed business idea page, showing the layout of the content area, sidebar widgets, and navigation components.

## Wireframes

- **wireframe_detailpage.html** - Basic wireframe for the business idea detail page showing the content structure without styling. This focuses on the positioning of elements and content hierarchy.

- **wireframe_homepage.html** - Basic wireframe for the homepage showing the content structure without styling. This focuses on the layout and organization of the main sections.

## Development Notes

1. The website should be built using Hugo with the structure and formatting demonstrated in the content files.

2. The mockups provide the visual design direction and should be implemented with responsive considerations.

3. The sidebar on the detail page should include all the widgets shown in the mockup (Table of Contents, Share, Related Ideas, Question Form, etc.)

4. All pages should be responsive, with special attention to the sidebar on detail pages, which should collapse on mobile devices.

5. The styling should follow the color scheme shown in the mockups:
   - Primary: #3366CC (Rich Blue)
   - Secondary: #FF9933 (Warm Orange)
   - Accent colors as demonstrated in the mockups

Please refer to the mockups and content files for implementation details, and reach out if any clarification is needed.

---

## **Site Structure**
The website will include the following key pages:

1. **Homepage: Ex. home_mockup.html**
   - Features a warm, inviting hero section with a motivational headline and call-to-action button.
   - Displays a grid of business idea cards, each with an image, title, description, and a "Learn More" button.
   - Designed to evoke hope, clarity, and empowerment through relatable visuals and intuitive navigation.

2. **Browse Details Page: Ex. detail_mockup.html**
   - Provides detailed information about specific business ideas.
   - Includes step-by-step guidance, tips, and resources to help users get started.

For reference, see the example HTML files in the `/requirements` folder:
- `home_mockup.html`
- `detail_mockup.html`

---

## Site Location
The developer will use the `/site` subfolder to add their site files for hugo site.

---

## **Git Branch Instructions**
Developers must **not** use the `main` branch directly. Instead, follow these steps to create and use a feature branch:

1. **Clone the repository** (if you haven't already):
   ```bash
   git clone https://github.com/DolphinAnalyticsAI/connies-website.git
   ```

2. **Navigate to the project folder**:
   ```bash
   cd connies-website
   ```

3. **Create a new feature branch** named with your first name (e.g., `feature/xxxxxxx`):
   ```bash
   git checkout -b feature/your-name
   ```

4. **Do your work** in the `/site` subfolder. Make sure to follow the design and functionality specifications in the `/requirements` folder.

5. **Commit your changes** with clear and descriptive messages:
   ```bash
   git add .
   git commit -m "Add your descriptive commit message here"
   ```

6. **Push your feature branch** to the remote repository:
   ```bash
   git push origin feature/your-name
   ```

7. **Create a Pull Request (PR)** from your feature branch to the `main` branch for review.

---

## DISREGARD THE LEGACY FOLDERS
`/docs`
`/mockups`


---

Thank you for contributing! Let’s build something amazing together. 🚀