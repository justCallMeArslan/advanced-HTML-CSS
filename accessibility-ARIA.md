WAI-ARIA is the Web Accessible Initiative's Accessible Rich Internet Applications.

The five rules of ARIA:

1. Always use native HTML elements and attributes over ARIA when possible.
2. Never chnage natiive semantics, unless no other choice.
3. All interactive ARIA controls must be usable with a keyboard.
4. Never use role = "presentation" or aria-hidden="true" on focusable elements.
5. All interactive elements must have an accessible name.

ARIA can modify only the semantics or context ofan element, and cant:

- Modify an element's appearance
- Modify an element's behavior
- Add focusability
- Add keyboard event handling
