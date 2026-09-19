# CSC-372 Assignment 2

## Project Description

This responsive Campus Event Guide helps UNCG students discover campus activities and open an event's details page. The intended audience is students looking for academic, cultural, athletic, outdoor, and student-government events.

## Layout Decisions

- CSS Grid creates the upcoming-events layout on `index.html`, including a full-width featured event and smaller event cards.
- CSS Grid creates the two-column event-details layout on `event.html`, with the main content on the right and a narrow information rail on the left.
- Flexbox handles the shared navigation, event-card content, footer columns, registration metadata, and the related-events rail. The related-events rail uses `flex-wrap` so cards can move to a new line when space is limited.
- The visual system uses UNCG-inspired navy, gold, white, and gray with local OTF fonts loaded through `@font-face`.

## Responsive Design

- At `1000px` and below, content margins and hero navigation sizing are reduced.
- At `700px` and below, event and about layouts become single-column layouts, the event sidebar moves below the main content, and the sidebar stops scrolling so it can expand naturally.
- Both pages include the viewport meta element. The pages were checked at desktop and narrow viewport widths to verify navigation, grids, sidebar order, image sizing, and wrapped related-event content.

## Semantic HTML

- `header` and `nav` identify the shared site navigation.
- `main` identifies the primary content area, with exactly one `main` element per page.
- `section` groups the hero, event listings, event details, and about content.
- `article` identifies individual event cards and independent event information.
- `aside` contains event registration details and related events.
- `figure` and `img` group event imagery, while `time` provides machine-readable event dates.
- `footer` contains contact information, copyright, and useful navigation links.

## Sources

- Event and campus content was written for this assignment, with UNCG news pages used as editorial references: [UNCG Connections at the N.C. Folk Festival](https://www.uncg.edu/news/uncg-connections-at-n-c-folk-festival/) and [What's New at the G](https://www.uncg.edu/news/whats-new-at-the-g-2026/).
- Images and SVG assets are stored locally in `images/`. Their original licensing or attribution should be recorded here before public release if any asset came from an external source.
- Local fonts: Sofia Pro Regular, Sofia Pro Bold, and Pluto Sans Heavy OTF files in `fonts/`.

## Testing

Both pages were checked for valid HTML/CSS in VS Code, and the layouts were reviewed at desktop and narrow viewport widths. Navigation links, event detail links, same-page bookmarks, image alt text, and responsive sidebar order were also checked.
