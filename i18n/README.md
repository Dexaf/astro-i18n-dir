It all starts with interfaces:

1. Base contains the layout interfaces (navbar, footer, and common meta tags).

2. Create an interface file for each page, with the same name (e.g., index.astro > index.interface.astro). Place translations there, and overwrite the meta data by inheriting from base.interface.ts.

3. Inside Translations, there's a folder for each language. Within it, there's a translation object that inherits from the relevant interface.

4. When creating the page, insert the layout, the content component in the slot, and pass the translation.
