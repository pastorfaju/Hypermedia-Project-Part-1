# Hypermedia-Project-Part-1
Design and development of my Curriculum Vitae website.

My page is segmented into four primary section blocks, each corresponding to a major theme of the CV.

1. Hero section: This section acts as the introduction. It's structured as a two part grid that contains my face/identity (.photo-container) and a key personal data summary (.contact-box). This section also contains the website's primary navigation menu (.main-nav). This uses fragment identifiers (#about, #work, #contact) to act as a table of contents that allows the users to jump to these sections.
2. About section: A straightforward text section providing a summary of skills, education and language proficiencies.
3. Work section: This section uses a three-column grid (.work-grid) to show my work history. Each job is a .work-item, which allows for easy comparison.
4. Contact section: The final section is also a grid, split into two columns. One column provides an interactive element (the .contact-form), while the other shows key contact information again for quick reference without having to return all the way up.

A global header sits above all, providing persistent site identity (.logo) and external social media links, separated from the main page navigation.

The visual design is centered on achieving a clean, professional and minimalistic aesthetic that prioritizes readability and clear information.

The core of this design is its cohesive color palette. I've used a soft lavender (#c4c3dd) as the primary background for the main hero and contact sections. This is complemented by a light neutral grey (#ebebf0) for the about sectiona and each individual work cards. This creates a subtle visual distinction between content blocks, and it's easy on the user's eye without being overwhelming. All text is in dark grey or black to ensure maxim readability combining with these light backgrounds.

The font is another key pillar. I selected the Roboto sans-serif font for its modern, clean and highly legible letter forms. There's also a visual hierarchy built with this font:
- Section titles: These are all uppercase, centered and given a distinct underline. This acts as a clear anchor of each section on the page.
- Job titles: These are also uppercase to create a clear label on each position in my work history.
- Body text: Paragraphs are given a line height of 1.6 to ensure the text is spacious and easy to read.

The layout is defined by a clear grid structure. Content is centered with containers that prevent it from stretching too much. Sections have vertical padding (5rem), which separates cleanly each part of the CV.
