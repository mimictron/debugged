# Debugging Assignment Files

Welcome to the Debugging Assignment repository! This repository contains the resources for the debugging assignment in the Web Design Tools course. Students will debug the provided HTML and CSS files to meet W3C standards and accessibility guidelines.

## Files Included

1. **index.html**

   - Contains intentional errors for students to identify and fix.
   - Errors include issues with HTML syntax, structure, accessibility, and semantic correctness.

2. **style.css**

   - Includes intentional errors related to CSS syntax, selectors, and properties.

3. **Expected Site Design**
   - Includes a screenshot of the error-free page (`images/expected-site-design.png`) to serve as a reference for students.

### File Structure

```
debugging-html-css/
├── css/
│   ├── style.css
│   ├── layout.css
├── images/
│   ├── easter-bunny-150-profile.png
│   ├── expected-site-design.png
├── index.html
├── README.md
```

## Objective

The goal of this assignment is to:

- Develop debugging skills by identifying and correcting errors in HTML and CSS.
- Improve familiarity with W3C standards and accessibility best practices.
- Practice using debugging tools and validators to ensure standards-compliant code.
- Learn to document errors and resolutions in a structured manner.

## Instructions

1. **Clone this repository** to your local machine:

   ```bash
   git clone <repository-url>
   ```

2. Open the `index.html` and `style.css` files in your favorite text editor or IDE (e.g., Visual Studio Code).

3. Identify the errors in both files. Use tools like:

   - [W3C HTML Validator](https://validator.w3.org/)
   - [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)
   - [Wave Accessibility Checker](https://wave.webaim.org/)

4. Update the `<aside>` element list in the `index.html` file.

   - Inside the `<aside>` list, describe each error and provide an explanation of the resolution.

5. Resolve all identified errors in the `index.html` and `style.css` files by:

   - Commenting out the original error code.
   - Adding the corrected code directly below the commented-out error code.

6. Once all errors are corrected:

   - Commit your changes and push them to your own GitHub repository.
   - Deploy the corrected project to GitHub Pages.

7. Submit your GitHub repository link and GitHub Pages link as instructed in the course.

## Tools and Resources

- [W3C HTML Validator](https://validator.w3.org/)
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)
- [Wave Accessibility Checker](https://wave.webaim.org/)
- [MDN Web Docs](https://developer.mozilla.org/)

## License

This repository is for educational purposes only. All content is copyrighted by the course instructor and may not be distributed without permission.

---

Happy debugging!

## Errors Found and corrected

# index.html

- Line 3 missing language attribute, added lang="en" to html tag
- Line 6 missing meta charset, added meta charset="UTF-8"
- Line 8 trailing slash in meta tag, slash removed (uneeded for void elements in HTML5)
- Line 11 missing path for layout.css, add css/ to path
- Line 21 missing alt attribute to img tag, added attribute and path
- Line 67 missing closing tag for h3, added /h3
- The following corrections were made so the site would more closely match the reference image:
  - line 78/79 changed h5 to h3
  - line 73/74 changed h4 to h3
  - line 86 commented out page breaks

# style.css

- Line 33 incomplete color code, changed color code to #B2D732
- Line 44 space between 5 vw, removed space for correct syntax
- Line 68 typo, changed me to em
- Line 87 invalid color code, changed code to #FE2712
- Line 98 Invalid attribute value for text decoration, changed all to underline
- The following corrections were made so the site would more closely match the reference image:
  - Line 27 changed max-width from 15vw to 8vw
  - Line 18 added padding to header
