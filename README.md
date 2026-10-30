BrightPath Studio
A responsive landing page for BrightPath Studio, built as a personal web development and technical SEO project.
Overview
BrightPath Studio is a small business website concept. I built this page to practise creating a clean, accessible web experience and implementing structured data that helps search engines understand page content.
Features
- Responsive layout for desktop and mobile
- Simple navigation and contact links
- Services and about sections
- Semantic HTML structure
- JSON-LD structured data using Schema.org vocabulary
Structured Data
The page includes the following JSON-LD schema types:
- Organization — describes BrightPath Studio
- WebSite — describes the website
- WebPage — describes the main webpage and its relationship to the website and organization
I added the structured data in the <head> section of index.html and checked the live page using the Schema.org Markup Validator.
Built With
- HTML5
- CSS3
- JSON-LD
- Schema.org
- GitHub Pages
Run Locally
1. Clone this repository:
   git clone https://github.com/abhijeet272727/brightpath-schema-markup.git
2. Open the project folder.
3. Open index.html in your browser.
No build tools or dependencies are required.
Live Website
https://abhijeet272727.github.io/brightpath-schema-markup/
Validation
You can validate the live structured data at:

https://validator.schema.org/

Paste the live website URL into the validator to inspect the detected Organization, WebSite, and WebPage entities.
