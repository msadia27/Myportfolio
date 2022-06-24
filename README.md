User Story:

AS AN employer
I WANT to view a potential employee's deployed portfolio of work samples
SO THAT I can review samples of their work and assess whether they're a good candidate for an open position

Acceptance Criteria:

GIVEN I need to sample a potential employee's previous work

WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them (nav bar, when I click the link, it scrolls down to the section of the page)

WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section

WHEN I click on the link to the section about their work (TITLE OF EACH SECTION ON THE IMAGE)
THEN the UI scrolls to a section with titled images of the developer's applications 

WHEN I am presented with the developer's first application (main work is presented larger on the website, than the secondary)
THEN that application's image should be larger in size than the others (responsiveness)

WHEN I click on the images of the applications
THEN I am taken to that deployed application (link to webpage)

WHEN I resize the page or view the site on various screens and devices (flexbox/wrap layout) + media queries, viewport should resize to phone if viewed on mobile device, if make screen bigger or smaller it should resize
THEN I am presented with a responsive layout that adapts to my viewport