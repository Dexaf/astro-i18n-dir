To maintain ssr/ssg, the pages are structured as follows:

1. The Page layout contains the navbar, footer, content slots, and meta tags.

2. Page uses the actual page content as its slot.

3. To share the page structure without duplicating it, the content will be kept in the content folder.

Inside the language folders is only the routing file that passes the language and translation strings to the content and layout.

4. For the structure of the translation files, refer to the README.md file in the i18n folder.
