# Event Page Criteria — Checklist

- [x] Page has a `header` element

  - [x] `header` contains an `h1` with the exact text: "Event Hub"
  - [x] `header` contains a `nav` element
    - [x] `nav` contains an unordered list (`ul`) with two list items (`li`)
      - [x] First list item: an `a` element with text "Upcoming Events" and `href="#upcoming-events"`
      - [x] Second list item: an `a` element with text "Past Events" and `href="#past-events"`

- [x] Page has a `main` element that contains the sections

  - [x] `main` contains two `section` elements

- [x] First `section` has id `upcoming-events`

  - [x] `#upcoming-events` contains an `h2` with text "Upcoming Events"
  - [x] `#upcoming-events` contains two `article` elements
    - [x] Each `article` includes an `h3` for the event title
    - [x] Each `article` includes a `p` for the event description (optional date can be included)

- [x] Second `section` has id `past-events`
  - [x] `#past-events` contains an `h2` with text "Past Events"
  - [x] `#past-events` contains two `article` elements
    - [x] Each `article` includes an `h3` for the event title
    - [x] Each `article` includes a `p` for the event description (optional date can be included)
    - [x] Each `article` includes an `img` element with a valid `src` and an `alt` attribute
  - [x] (Optional) Images may use these URLs:
    - [x] <https://cdn.freecodecamp.org/curriculum/labs/past-event1.jpg>
    - [x] <https://cdn.freecodecamp.org/curriculum/labs/past-event2.jpg>

Note: You may use any text for event titles, descriptions, and dates. The checklist items above map directly to the project acceptance criteria.
