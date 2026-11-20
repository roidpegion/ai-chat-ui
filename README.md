# Lumen UI prototypes

Design prototypes for Lumen, a dark work assistant. Everything here is design only: nothing connects to Outlook, Teams or any other service, and all people, companies and messages are made-up examples.

## Files

| File | What it is |
|---|---|
| `assistant.html` | The current direction: an assistant that reads Outlook, Teams and the calendar. Items can open as an inline preview or in a reader panel that grows out of the card. |
| `concepts.html` | The earlier chat-style prototype with the same Graphite Sand look, kept for reference. |

## How to view

Open either file in a browser (double-click it). Each file is self-contained, with its CSS and JavaScript inline. It needs internet only for the Geist font from Google Fonts and falls back to the system font without it.

## Design notes

- Look: Graphite Sand. Warm charcoal background, pale sand accent, faint animated light beams, film grain.
- Type: Geist and Geist Mono.
- Motion tokens: `--ease-out: cubic-bezier(.22, 1, .36, 1)` for text and panels, `--spring: cubic-bezier(.34, 1.56, .64, 1)` for objects such as the sidebar pill and popovers. New content fades in from a soft blur.
- Built in plain HTML, CSS and JavaScript so it is quick to change. A production build would port it to React, for example with Tailwind and Motion.
