**CV Website – Marc Lòpez Olmo**

Single-page website presenting my curriculum vitae: profile, work experience, education, skills and languages. Project for the Hypermedia course (Part 1).

🔗 Live page: https://YOUR-USERNAME.github.io/REPOSITORY-NAME/
🎨 Figma project: https://www.figma.com/design/xh6OdX3ux36qNzDzaABGDG/CV-Web-page-desing?node-id=0-1&t=dgySNmwg4CK7rmlT-1 
1. Project Analysis
   
1.1 User Profile (User Persona)

Marc Lòpez Olmo, 38 – Talent Acquisition Manager (HR) at a web and video game development studio

	
Context	Works at a mid-sized company hiring juniors and interns. Every week she reviews between 30 and 50 applications, mostly from her office computer and sometimes from her phone.
Goal	Decide in under a minute whether a candidate deserves an interview.
What she expects to find	Who the candidate is, what they have done, which technologies they know, where they studied and how to contact them, without having to search for it.
Frustrations	Cluttered websites, animations that slow down loading, information hidden behind menus, and contact details that are hard to find.
Digital skills	High. She is used to LinkedIn and online portfolios, but doesn't want to waste time navigating.

Design takeaway: the page must be clear, scannable at a glance, fast, and always show the contact details.

**1.2 Information Architecture**

Since this is a static single-page site, the information architecture consists of distributing the CV sections along a single vertical scroll split into two columns, following the reading logic of a traditional CV.

Left column (36%) – quick-reference information. It contains the photo and three short blocks: Contact (phone, email and location, all as actionable links), Education (degrees with title and years) and Skills (HTML and CSS, JavaScript and Design). These are short pieces of data that a recruiter looks for almost automatically, so they are grouped in a stable, high-contrast sidebar.

Right column (64%) – narrative content. It starts with the header (name and job title), which answers the user's first question: "who is this?". It is followed, in this order, by:

Personal profile: a short paragraph summarizing motivation and professional approach.
Work experience: three jobs in reverse chronological order (most recent first). Each one shows job title, company, dates and a brief description.
Languages: a list with the level of each language, placed last because it is complementary information.

The sections on the right share the same structure (a black circle with the title and a vertical timeline line), so the reader learns the pattern in the first section and then only has to focus on the content. The HTML order follows the visual order, which also benefits accessibility and screen-reader navigation.

**1.3 Visual Design**

Color palette. I chose a strictly monochrome palette: black, white and very dark greys. This gives the page a professional, timeless look, maximizes text contrast (better readability and accessibility) and keeps color from distracting from the content. The black of the left column, the job-title bar and the section circles creates a visual thread connecting the whole page.

Typography. I use two Google Fonts families. Archivo (regular and bold) is used only for the name, in uppercase with a strong weight contrast between "MARC" and "LÒPEZ OLMO", to give it personality and hierarchy. Raleway is used for all the remaining text: it is a clean, geometric and highly readable typeface, and its range of weights (400, 500, 600) establishes hierarchy between headings, job titles and descriptions without adding more fonts. Companies are set in bold italics to distinguish them from job titles, which are in uppercase.

Page layout. A two-column CSS grid (36% / 64%) with a maximum width of 1131 px, centered on the screen. This proportion is a classic reference in vertical CV formats and gives the main content enough room. The dark sidebar creates a strong contrast with the white reading area.

Recurring elements. The black circles accompanying each section title and the vertical timeline line visually organize the page and reinforce the idea of a professional journey. The text in the right column is justified with hyphenation to obtain compact, regular blocks.

Screen adaptation. Font sizes, spacing and sidebar margins use the clamp() function, so they scale fluidly with the window width. The circular photo includes a fallback silhouette, so the design doesn't break if the image is missing.

References. Minimalist black-and-white two-column CV templates (Canva, Behance and Pinterest style), with a dark sidebar and a typographic header.
