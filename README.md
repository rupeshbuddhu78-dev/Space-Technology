# Space Technology Website

A static, multi-page website introducing space exploration and technology. The site is built with HTML and uses local image assets; it does not require a build step or JavaScript runtime.

## Pages

- `index.html` — home page with a featured spacecraft, projects, mission statement, and latest blog posts.
- `about.html` — information and template-style content about the site.
- `project.html` — featured projects, including the Mars Curiosity Rover and International Space Station.
- `blog.html` — sample space-related blog posts.
- `Contact.html` — contact form layout.

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a web browser.

Keep the image files in the repository root alongside the HTML files so the pages can load their images correctly. The site can also be hosted as a static website, for example with GitHub Pages.

## Project notes

- The pages link to one another using relative paths.
- The contact form is currently presentation-only: it has no configured server or form-submission endpoint.
- The featured video on the home page uses a placeholder source and will not play until a video URL or file is provided.
- The pages use older HTML presentation attributes (such as `<font>` and table-based layouts). A future improvement would be to move presentation into CSS and use semantic, responsive page structure.
