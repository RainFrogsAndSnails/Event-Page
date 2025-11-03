# Event Page Criteria — Checklist

- [ ] Page has a `header` element

  - [ ] `header` contains an `h1` with the exact text: "Event Hub"
  - [ ] `header` contains a `nav` element
    - [ ] `nav` contains an unordered list (`ul`) with two list items (`li`)
      - [ ] First list item: an `a` element with text "Upcoming Events" and `href="#upcoming-events"`
      - [ ] Second list item: an `a` element with text "Past Events" and `href="#past-events"`

- [ ] Page has a `main` element that contains the sections

  - [ ] `main` contains two `section` elements

- [ ] First `section` has id `upcoming-events`

  - [ ] `#upcoming-events` contains an `h2` with text "Upcoming Events"
  - [ ] `#upcoming-events` contains two `article` elements
    - [ ] Each `article` includes an `h3` for the event title
    - [ ] Each `article` includes a `p` for the event description (optional date can be included)

- [ ] Second `section` has id `past-events`
  - [ ] `#past-events` contains an `h2` with text "Past Events"
  - [ ] `#past-events` contains two `article` elements
    - [ ] Each `article` includes an `h3` for the event title
    - [ ] Each `article` includes a `p` for the event description (optional date can be included)
    - [ ] Each `article` includes an `img` element with a valid `src` and an `alt` attribute
  - [ ] (Optional) Images may use these URLs:
    - [ ] <https://cdn.freecodecamp.org/curriculum/labs/past-event1.jpg>
    - [ ] <https://cdn.freecodecamp.org/curriculum/labs/past-event2.jpg>

Note: You may use any text for event titles, descriptions, and dates. The checklist items above map directly to the project acceptance criteria.
