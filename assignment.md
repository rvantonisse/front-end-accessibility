# Audit exercise; Pedal Faster

- Onderzoek de oefensite op toegankelijkheid.
- Schrijf op wat er fout is en hoe je dit kunt verbeteren.
- Maak de oefensite toegankelijk.

## general / site structure

1. Missing title tag

    Fix by adding title

2. Missing lang attribute on html

    Fix by adding `lang="en"`

3. Semantic html - use html5 tags

    Refactor markup to use html5 tags like: header, nav, main, article, footer

    - Navigation sections

        Refactor menu to `<nav />` with nested list `<ul />` and add screen reader only heading `<h2 class="sr-only" />`. Remove `/` as item separator from content and add with css.

        Refactor service menu to nav


## home.html

### Issues & Fixes

1. Missing alt attribute on img tags

    Fix by adding `alt=""` (empty because presentational images)

2. Missing semantic structure

    - Main content section

        Main section first as article and list of articles as actual lists (might be lists of different topics) or make it semantically one list and style each item as grid_3


## Contact.html

### Issues & Fixes

1. Heading level 1 incorrect text; should be contact?

2. Missing alt attributes

3. Form labels are missing not refferring to input counterpart

    Fix by adding `for` atribute at labels and `id` to form element
