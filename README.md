# NIKE-DASHBOARD
Dashboard Overview 

This dashboard is a product-focused interactive showcase designed using Power BI to present sneaker models in a clean, brand-aligned layout. It combines visual storytelling with user-driven interactivity, similar to an e-commerce product detail experience.

Layout & Design Structure
1. Main Product Display (Center Panel)

The central area highlights the selected sneaker model (currently Air Jordan 10 Retro).

It uses a high-resolution hero image to draw attention and act as the focal point of the dashboard.

This section dynamically updates based on user interaction with the navigation buttons.

2. Product Information Panel (Right Side)

Displays:

Product Name (Air Jordan 10 Retro)

Marketing Description explaining comfort, performance, and branding

This text is context-sensitive, meaning it changes automatically when a different sneaker is selected.

Reinforces a storytelling approach rather than raw tabular data.

3. Thumbnail Views (Bottom Right)

Shows multiple angles of the selected sneaker (top view, sole, side view).

Enhances product understanding without overwhelming the main visual.

These images are synchronized with the selected sneaker using Power BI image switching logic.

4. Vertical Sneaker Selector (Left Panel)

The sneakers arranged vertically on the left side act as interactive buttons.

Each sneaker image is implemented as a Power BI Button (or image with action).

Clicking a sneaker:

Triggers a bookmark

Switches the main sneaker image

Updates the product name, description, and thumbnails

📌 This replaces traditional slicers, offering a more intuitive and visually engaging navigation experience.

Power BI Technical Implementation (Behind the Scenes)

Bookmarks are used to control:

Image visibility

Text changes

Selected product state

Buttons with action = Bookmark enable seamless switching between sneaker models.

Layering & Selection Pane ensure only the relevant sneaker visuals are shown at any time.

The layout avoids heavy charts, focusing instead on UX-driven design, which is ideal for:

Product catalogs

Brand storytelling dashboards

Executive presentations

Business & UX Value

Mimics a retail or brand website experience inside Power BI

Reduces cognitive load by showing one product at a time

Enhances engagement through click-based exploration

Demonstrates advanced Power BI skills beyond standard reports

One-Line Summary (Perfect for Interviews)

“This Power BI dashboard uses bookmark-driven buttons to create an interactive product showcase, where vertically arranged sneaker images act as navigation controls to dynamically switch the displayed sneaker, its visuals, and descriptive content.”

If you want, I can also:

Help you explain this to non-technical stakeholders

Convert this into an interview-ready Power BI project explanation

Break down step-by-step how to build it in Power BI
