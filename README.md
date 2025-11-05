# Hypermedia-Project-Part-1
Design and development of my Curriculum Vitae website.

My page is segmented into four primary section blocks, each corresponding to a major theme of the CV.

1. Hero section: This section acts as the introduction. It's structured as a two part grid that contains my face/identity (.photo-container) and a key personal data summary (.contact-box). This section also contains the website's primary navigation menu (.main-nav). This uses fragment identifiers (#about, #work, #contact) to act as a table of contents that allows the users to jump to these sections.
2. About section: A straightforward text section providing a summary of skills, education and language proficiencies.
3. Work section: This section uses a three-column grid (.work-grid) to show my work history. Each job is a .work-item, which allows for easy comparison.
4. Contact section: The final section is also a grid, split into two columns. One column provides an interactive element (the .contact-form), while the other shows key contact information again for quick reference without having to return all the way up.

A global header sits above all, providing persistent site identity (.logo) and external social media links, separated from the main page navigation.
