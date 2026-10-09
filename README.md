# Vera Khat — Personal Portfolio

A responsive, single-page portfolio built with plain HTML, CSS, and JavaScript. No build tools or frameworks are required.

## Open the website

Open `index.html` in a browser, or use the Live Server extension in VS Code for a local preview.

## Project structure

```text
portfolio/
├── index.html
├── style.css
├── script.js
├── images/
│   ├── profile.svg
│   ├── project1.svg
│   ├── project2.svg
│   ├── project3.svg
│   ├── project4.svg
│   ├── project5.svg
│   └── project6.svg
└── README.md
```

The local SVG illustrations are editable placeholders, so the portfolio works without downloading or configuring image assets. Replace them with your own photos and project screenshots if you prefer.

## Personalize your portfolio

1. In `index.html`, replace the location, email address, phone number, institution name, and expected graduation year placeholders with your details.
2. Update the social links to point to your own profiles.
3. For each project, change the project description and replace the `href="#contact"` links with its actual live demo and repository URLs. Design projects can link to an image gallery or design file instead of GitHub.
4. Adjust the skill progress percentages in `index.html` by changing each skill meter's `--level` value (for example, `style="--level:62%"`).
5. Replace the SVG illustrations in `images/` with your own artwork. Keep each filename the same, or update the matching `src` in `index.html`.
6. Change the palette by editing the CSS custom properties at the top of `style.css`.

## Contact form

The contact form validates required fields in the browser and displays a friendly confirmation. It does not send, store, or transmit form data. Connect it to a backend or form service if you later need to receive submissions.

## External resources

Google Fonts and Font Awesome are loaded from their CDNs for typography and icons. The website content and placeholder images remain local.
