# Moodle HTML customizations

Each HTML file represents a fragment inserted into Moodle's HTML editor, not a standalone web page.

- `homepage/`: four separate HTML blocks on Home.
- `dashboard/welcome.html`: welcome panel.
- `course/introduction.html`: course summary.
- `course/lessons/`: bilingual section headings (in HTML comments) and summaries.

The `.multilang` spans require a configured Moodle multilang filter. The lesson files intentionally contain **no live file links**: educational resources must be attached through Moodle's file manager. The homepage illustration is not included; replace the placeholder with an image you own or have permission to publish.

This folder is a reference copy. Editing it does not update the live Moodle site.
