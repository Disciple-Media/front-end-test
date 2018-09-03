# Disciple Front-End Tech Test

This project is designed to exercise your VueJS, JavaScript, and CSS skills.

It is set up with a single page comprised of two areas:

- Actions Area
- Main Content Area

The main content area contains an instance of each of three components – a text
field, an image, and a button.

The actions area contains a button labelled with the name of the text field
component.  At the moment, the button does nothing.

This is also a completely unstyled, very ugly page!


## Goals

- The actions area should show buttons for all three component types.
- The main content area should start out empty.
- When a button in the actions area is pressed, it should add an instance of
  that component type to the main content area.
- The page should use a two-column layout, with the actions area in a sidebar
  next to the main content area.


## Test

- Open the page.
- Click each of the buttons twice.
- The content area should contain:
	- Text field
	- Text field
	- Image
	- Image
	- Button
	- Button


## Hints

- Vue’s `:is` will be helpful.


## Extra Credit

- What happens if we add a fourth component?  How can we make this more
  extensible?
- Make the page look nicer.


## Getting Started

```
yarn install
yarn serve
```
