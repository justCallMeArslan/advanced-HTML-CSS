@media tips:

- @media print can be used for styling site when t sent for printing.

- its better to use @media only for designed in project sizes, and keep natural
  responsiveness as long as

- there is a thing called @container query, which is used for container characteristics,
  instead of viewport or device screen size.


All three can be used equally:

@media (min-width: 30em) and (max-width: 50em) {
  /* … */
}

@media (30em <= width <= 50em) {
  /* … */
}

@media (50em >= width >= 30em) {
  /* … */
}