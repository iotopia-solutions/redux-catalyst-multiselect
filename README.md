# redux-catalyst-multiselect

A Redux-based MultiSelect component, in ES6, with filtering

MultiSelectPicker is a simple, multi-select control with search filtering, storing all its state in the Redux store.
Pass in props of availableOptions to populate the 'from' (available options) side of the multiselect, and initialOptions for the 'to' (picked options) side.

### Features
* Configurable CSS for Search / Filter area, Select, and Buttons
* Configurable Button Labels
* Assign / Unassign all items
* Filterable for both selects, togglable

### TODO:
* Fix issue with more than 1 select not getting moved over when using Ctrl+Select
* Implement initiallyPicked list functionality
* ARIA support

Credits: using some initial multi-select code from https://github.com/scottshid

