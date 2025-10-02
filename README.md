# Debugging Assignment Files

Welcome to the Debugging Assignment repository! This repository contains the resources for the debugging assignment in the Web Design Tools course. Students will debug the provided HTML and CSS files to meet W3C standards and accessibility guidelines.

## Files Included

##Warning: This document appears to be written in English. Consider adding lang="en" (or variant) to the html start tag.

##Error: Element meta is missing one or more of the following attributes: charset, content, http-equiv, itemprop, name, property.

## Info: Trailing slash on void elements has no effect and interacts badly with unquoted attribute values.

## Error: An img element must have an alt attribute, except under certain conditions. For details, consult guidance on providing text alternatives for images.


1. **index.html**
   - Contains intentional errors for students to identify and fix.
   - Errors include issues with HTML syntax, structure, accessibility, and semantic correctness.

2. **style.css**
   - Includes intentional errors related to CSS syntax, selectors, and properties.

   color: #B2;/* Invalid color value. Hex codes must have 3 or 6 characters. */

    /* Corrected color value below */
    color: #B2B2B2;

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

4. Resolve all identified errors in the `index.html` and `style.css` files by:
   - Commenting out the original error code.
   - Adding the corrected code directly below the commented-out error code.

5. Once all errors are corrected:
   - Commit your changes and push them to your own GitHub repository.
   - Deploy the corrected project to GitHub Pages.

6. Submit your GitHub repository link and GitHub Pages link as instructed in the course.

## Tools and Resources

- [W3C HTML Validator](https://validator.w3.org/)
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)
- [Wave Accessibility Checker](https://wave.webaim.org/)
- [MDN Web Docs](https://developer.mozilla.org/)

## License

This repository is for educational purposes only. All content is copyrighted by the course instructor and may not be distributed without permission.

---

Happy debugging!
