**Project Title: Terminal-Style Developer Portfolio**

**Overview:**
This project is a fully interactive, terminal-style portfolio for showcasing a developer's skills, background, goals, and social presence. It is built using HTML, CSS, and vanilla JavaScript, providing a unique and engaging user experience that emulates a real command-line interface (CLI). Inspired by classic terminal environments, this portfolio offers visitors a nostalgic and professional way to explore the developer's profile.

**Key Features:**

* **Terminal UI:** Mimics the aesthetics and behavior of a Unix-style shell, complete with a blinking cursor, typed commands, and prompt line.
* **ASCII Art:** Features animated ASCII art at the top to immediately capture attention and establish a retro-terminal vibe.
* **Command-based Navigation:** Users can type commands like `about`, `skills`, `projects`, `goals`, `socials`, `clear`, and `theme [name]` to view different sections.
* **Markdown Support:** Uses the `marked.js` library to render markdown content (like `about` and `goals`) into styled HTML.
* **Project Fetching:** Fetches and displays public GitHub repositories dynamically via the GitHub API.
* **Themes:** Allows users to change the color theme of the terminal (e.g., Matrix, Ubuntu, Light) with a simple `theme` command.
* **Command History:** Supports command history navigation with arrow keys and basic autocomplete with `Tab`.
* **Responsive Design:** Styled with Fira Code font and optimized for different screen sizes.

**Tech Stack:**

* **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
* **API Integration:** GitHub REST API for project listings
* **Markdown Parsing:** marked.js library for rendering markdown
* **Fonts & Style:** Fira Code monospace font, pre-defined color themes

**Usage:**

* Designed as a personal developer portfolio but can be adapted for CVs, tech resumes, or developer blogs.
* Especially suited for developers with a Linux, hacking, or retro computing aesthetic.

**Future Improvements:**

* Add support for typing animations across all outputs.
* Include file-based navigation with `cat`, `ls`, etc. for enhanced realism.
* Improve accessibility and keyboard-only navigation.
* Add language toggle or i18n support.
