--Readme document for *Timothy Le*, *leth4@uci.edu*--

A reminder on academic integrity, as described in the syllabus.

In general, the course staff expects that you will look at code and examples from many online resources as part of the assignments, particularly to resolve syntax and understand frameworks. We expect that you'll use other libraries you find, and will even require it in some assignments. These practices are often critical to the work of developers today. The best developers are adept at interpreting the examples they see, customizing them to their specific situation, and citing their sources so they can find them later. We expect you to do the same.

While learning from examples is encouraged, attempting to pass an existing project or example from the web as your own is not allowed. If you ever have a question about what is or is not appropriate, feel free to ask the course staff!

Talking to classmates about class material, assignment requirements, etc. is a great way to verify ideas and get feedback. But this distinctly does *not* permit attempting to pass off someone else’s code as your own. Talking over ideas and approaches is allowed, but the work that you produce and submit must be your own.

1. How many assignment points do you believe you completed?

Estimated 9/10 (the design score is subjective).
- 1/1 Readme
- 2/2 Basic HTML content
- 1/1 Basic CSS styling
- 1/1 Advanced feature
- 2/2 Responsive layout
- 1/1 Passes validation checks
- 1/2 Embraces spirit of the assignment

2. What (a) basic features, (b) CSS features, and (c) advanced features did you include in your portfolio?

(a) Basic features
- Headings and paragraphs for the introduction, education, experience, and contact sections
- External links to UC Irvine, a resume, and my LinkedIn n                                                              
- Semantic nav, header, main, section, and footer elements

(b) CSS features
- Padding and margins for readable spacing
- Background, text, and link colors
- DM Sans from Google Fonts, with Arial and sans-serif fallbacks

(c) Advanced features
- Responsive navigation bar with links to each section
- Nested CSS selectors for links in the navigation and header
- Highlighted text color (golden, my easter egg)

3. Did you ignore any of the warnings or errors presented by the accessibility checker? If so, why does this not seem like an accessibility concern? If it's useful, you can consolidate your thoughts on multiple warnings/errors if the rationale is similar.

AChecker reported 0 known problems, 0 likely problems, and 35 potential problems under WCAG 2.0 AA. 
Its potential were just warnings that required a person to look at it.  The page uses English left-to-right text, meaningful link labels, headings in order, and no quotations or visual-only lists. It has one page, so the portfolio does not need a site map. 
The navigation bar and main landmark make the content easy to reach without a separate skip link. The title describes the page. None of the potential checks identified a real accessibility error.

The W3C CSS validator reported 0 errors and one warning that imported style sheets are not checked when CSS is submitted as direct input. That warning refers to the Google Fonts import, not a syntax error in style.css.


4. How long, in hours, did it take you to complete this assignment?

I worked on the assignment over two weeks, for a total of about 12 hours.


5. What online resources did you consult when completing this assignment? (list specific URLs, describe queries to Generative AI, or use of AI-based code completion)

https://validator.w3.org/nu/ - checked index.html for HTML errors and warnings.
https://jigsaw.w3.org/css-validator/validator - checked style.css for CSS errors.
https://achecks.org/checker/index.php - checked index.html against WCAG 2.0 AA.
https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&display=swap - imported the DM Sans font.
OpenAI Codex - I used AI to make a list/cheatsheet of HTML tags to reference, and verify that the site meets the assignment requirements. 


6. What classmates or other individuals did you consult as part of this assignment? What did you discuss?
I did not consult classmates or other people.


7. Is there anything special we need to know in order to run your code?

Open index.html directly. It uses a relative link to style.css. If Google Fonts is unavailable, the page falls back to Arial or another sans-serif font.
