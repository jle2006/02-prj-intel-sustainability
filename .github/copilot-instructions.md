
# Copilot Instructions: Intel Sustainability Journey Webpage

## Audience & Coding Style
- Students are beginners learning HTML and CSS.
- Always provide the simplest, most beginner-friendly code possible.
- Use clear comments to explain each part of the code.
- Do **not** use advanced CSS layout methods (like grid) unless specifically requested.

## Project Structure
- `index.html`: Main webpage. Contains header, timeline cards, and instructions for students.
- `style.css`: All custom styles. Start simple; use only basic selectors and properties unless asked otherwise.
- `img/`: Contains images for timeline cards and the Intel logo. Use these images in the timeline as appropriate.

## Key Patterns & Conventions
- Timeline is built with a series of `<div>` cards inside a `<section>`. Each card represents a milestone year.
- Images for each card should be referenced from the `img/` folder (e.g., `img/1.jpg`).
- The Intel logo (`img/intel-header-logo.svg`) is used in the header and should be resized with CSS.
- Responsive design is encouraged, but keep solutions simple (use media queries, not grid/flex unless asked).
- Add hover effects and transitions using only basic CSS (e.g., `:hover`, `transition`).
- All code should be well-commented for learning purposes.

## Developer Workflow
- No build tools or frameworks are used—edit HTML and CSS directly.
- Preview changes by opening `index.html` in a browser or using the Codespaces preview.
- No tests or scripts are present; focus is on static site development.
- Commit and push changes regularly to GitHub.

## Example: Adding a Timeline Card
```html
<div>
	<h2>Year</h2>
	<h3>Event Title</h3>
	<img src="img/1.jpg" alt="Description" />
	<p>Event description goes here.</p>
</div>
```

## Additional Guidance
- Do not introduce JavaScript unless specifically requested.
- If asked to add accessibility features, use semantic HTML and `alt` text for images.
- If unsure, prefer clarity and simplicity over cleverness.
