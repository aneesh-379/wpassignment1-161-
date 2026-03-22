# EduForge — Simple Online Learning Website

A simple static website built with plain HTML5, CSS and JavaScript.
Covers all syllabus requirements for Web Technologies Lab.

---

## Project Files

| File               | Purpose                                      |
|--------------------|----------------------------------------------|
| index.html         | Home page with banner and intro cards        |
| courses.html       | Course listing with 6 course cards           |
| course-detail.html | Course detail, curriculum, instructor, enroll|
| register.html      | Registration form with JS validation         |
| login.html         | Login form with JS validation                |
| contact.html       | Contact info + inquiry form with validation  |
| styles.css         | Single external CSS file for all pages       |
| courses.xml        | Course data in XML format                    |
| courses-style.css  | CSS to style courses.xml in the browser      |
| courses.xsd        | XSD schema to validate courses.xml           |

---

## Syllabus Coverage

### 1. HTML5 & CSS
- Semantic HTML5 elements: nav, header, section, footer, form
- External CSS file (styles.css) with CSS variables, Grid, Flexbox
- Hover effects on buttons, cards and links
- Responsive layout with media queries

### 2. Forms & JavaScript Validation
- Register: name length, email pattern, password length, confirm match, terms checkbox
- Login: required fields, email pattern, demo credentials check
- Contact: all fields validated before submit

### 3. XML & XSD
- courses.xml — well-formed XML with course data
- courses.xsd — XSD schema with type restrictions, enumerations, patterns
- courses-style.css — CSS applied to XML, open courses.xml in browser to view styled output

---

## How to View XML Styled in Browser
1. Open `courses.xml` in Google Chrome or Firefox
2. The browser reads the `<?xml-stylesheet?>` link and applies `courses-style.css`
3. Each course appears as a styled card

---

## GitHub Pages Deployment

1. Create a GitHub account at https://github.com
2. Click **New Repository** — name it `eduforge`, set it to Public
3. Upload all project files (drag and drop or use the upload button)
4. Go to **Settings → Pages**
5. Under Source: select **Deploy from a branch → main → / (root)**
6. Click **Save**
7. Your site will be live at: `https://your-username.github.io/eduforge/`

---

## Demo Login
- Email: demo@eduforge.com
- Password: Demo@1234
