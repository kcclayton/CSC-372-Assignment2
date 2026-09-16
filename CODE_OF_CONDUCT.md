# Assignment 2 Specifications
### Intro
The university’s Office of Student Engagement needs a small website that helps students discover campus activities. Create a responsive Campus Event Guide with a home page and a featured event details page. You may invent the university name, organizations, events, locations, and schedule details.

### Deliverables
- [ ] Two HTML pages: index.html and event.html
- [ ] One external stylesheet: css/styles.css
- [ ] An images folder containing all local images
- [ ] A README.md explaining design decisions and sources
- [ ] A GitHub repository with at least five meaningful commits

### Project Structure
Assignment-2/
├── index.html
├── event.html
├── css/
│   └── styles.css
├── images/
│    ├── event-1.jpeg
│    ├── event-2.jpeg
│    ├── event-3.jpeg
└── README.md

### Page 1: Home Page (`index.html`)
- [ ] Site header and navigation
- [ ] Website name or logo and a short tagline
- [ ] Primary navigation linking to Home, Upcoming Events section, About section, and the Featured Event page
- [ ] Semantic structure using header, nav, ul, li, and a elements

##### Hero section
- [ ] A meaningful heading and short introductory paragraph
- [ ] A link styled as a button that moves to the upcoming events section
- [ ] A decorative or informative image with appropriate alternative text
- [ ] Upcoming events grid
- [ ] At least 5 event cards
- [ ] Each card includes an image, event name, date/time, location, category, short description, and meaningful View Details link
- [ ] Cards use CSS Grid with at least two different widths

##### About section
- [ ] A heading and one or two explanatory paragraphs
- [ ] A list of at least three benefits or services

##### Footer
- [ ] Copyright statement
- [ ] Contact email or placeholder
- [ ] At least two useful navigation links

### Page 2: Event Details (`event.html`)
- [ ] Shared header and navigation
- [ ] Use the same general header and navigation structure as the home page
- [ ] Navigation between index.html and event.html must work correctly

##### Event introduction
- [ ] Event name, large image, category, date/time, location, and an introductory description

##### Main content and sidebar
- [ ] Create a two-column desktop layout using CSS Grid
- [ ] Main column: description, attendee expectations, schedule or agenda, at least one list, and accessibility or participation information
- [ ] Sidebar: date, time, location, organizer, admission information, and a registration link styled as a button
- [ ] On narrow screens, move the sidebar below the main content

##### Related events
- [ ] Include at least three compact event cards
- [ ] Use Flexbox and allow the cards to wrap when horizontal space is limited

##### Footer
- [ ] Use the same general footer treatment as the home page

#### Technical Requirements
##### A. Semantic HTML
- [ ] Use meaningful elements, including header, nav, main, section, article, aside, footer, figure, figcaption, and time where appropriate.
- [ ] Use exactly one main element on each page.
- [ ] Give every informative image meaningful alt text. 

##### B. CSS Box Model
- [ ] Apply margin, padding, border, width or max-width, and box-sizing appropriately.
- [ ] Do not create spacing with repeated <br> elements or empty paragraphs.

##### C. Flexbox
- [ ] Use Flexbox in at least two meaningful locations, such as navigation, hero content, related events, or footer content.
- [ ] At least one Flexbox container must demonstrate alignment, spacing, and/or wrapping using properties such as justify-content, align-items, gap, and flex-wrap.
- [ ] Using display: flex by itself is not sufficient evidence of Flexbox understanding.

##### D. CSS Grid
- [ ] Use Grid for the upcoming event cards on index.html, and the main content/sidebar layout on event.html.

##### E. Responsive Design
- [ ] Include the viewport meta element on both pages.
- [ ] Include at least two media queries.
- [ ] JavaScript is not required. On narrow screens, navigation may wrap or become vertical.

##### F. CSS Organization and Design
- [ ] Use one external stylesheet. Do not use inline CSS or style elements.

### Restrictions
- Do not use Bootstrap, Tailwind CSS, CSS component libraries, JavaScript, website builders, or prebuilt templates.
- Do not use generated layout code that you cannot explain.
- You may use your own or appropriately licensed images. Credit sources in README.md when required.

### README Requirements
- Project Description: Explain the site’s purpose and intended audience.
- Layout Decisions: Identify where you used Flexbox and Grid and explain why each was appropriate.
- Responsive Design: List your breakpoints, describe what changes at each, and state how you tested the pages.
- Semantic HTML: Identify at least four semantic elements and explain why each was appropriate.
- Sources: Credit images, fonts, and borrowed content.