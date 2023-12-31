# Learn Accessibility by Building a Quiz

Accessibility is making your webpage easy for all people to use – even people with disabilities.

In this course, you'll build a quiz webpage. You'll learn accessibility tools such as keyboard shortcuts, ARIA attributes, and design best practices.

Project with 68 steps

# Accessibility
1. Lang="en" in <html>
2. Charset in <meta charset="UTF-8">
3. a viewport definition tells the browser how to render the page. Including one betters visual accessibility on mobile, and improves SEO (search engine optimization). in <meta name="viewport" content="width=device-width, initial-scale=1.0">
4. Another important meta element for accessibility and SEO is the description definition. The value of the content attribute is used by search engines to provide a description of your page. in <meta name="description" content="Lear html accessibility quiz">
5. Given title: <title>Accessibility: Building a Quiz</title>
6. Given The <header> element (be used to introduce the page, as well as provide a navigation menu:  <img>, <h1>, and <nav> element) and the <main> element (that will contain the core content of your page).
7. Create a <section> in <form> to semantically separate the content.
8. Add attribute role: To increase the page accessibility, the role attribute can be used to indicate the purpose behind an element on the page to assistive technologies. The role attribute is a part of the Web Accessibility Initiative (WAI), and accepts preset values.
9. Every region role requires a label, which helps screen reader users understand the purpose of the region. One method for adding a label is to add a heading element inside the region and then reference it with the aria-labelledby attribute.h2 element with an id matching the corresponding aria-labelledby
10. **Typeface** plays an important role in the accessibility of a page. Some fonts are easier to read than others, and this is especially true on low-resolution screens. *Verdana*, and *sans-serif* family.
11. **Navigation within the page**, give each anchor element an href corresponding to the id of some elements.
12. It is important to **link each input to the corresponding label element**. This provides assistive technology users with a visual reference to the input. This is done by giving the label a for attribute, which contains the id of the input.
13. Keeping in mind best-practices for form <inputs>, give each input an appropriate **type** and **name** attribute. Then, give **placeholder** attribute.
14. **label** and **placeholder**: A **placeholder** is actually not a best-practice for accessibility; too often, users confuse the placeholder text with an actual input value - they think there is already a value in the input. Relying on the **label** being the best-practice.
15. abbreviation is not best-practice for screen-reader: <label for="date-birth">D.O.B:<span class="sr-only">(Date of Birth)</span></label>
16. Two final semantic HTML elements for this project are the <footer> and <address> elements. The <footer> element is a container for a collection of content that is related to the page, and the <address> element is a container for contact information for the author of the page. After the main element, add one footer element, and nest one address element within it.
