# LifeSciSkills Academy

## Primary Goals:
 - Showcase range of programs in life sciences manufacturing offered by LifeSciSkills Academy
 - Generate leads for potential students and contacts for B2B development.

## Business Goals
 - Generate Course enrolment via multiple nurturing pathways.
 - Generate B2B partnerships.
 - Build Brand Awareness.

## User Needs
- Easily navigable website with intuitive form discovery.Reached in 3 clicks or less
- Multiple Enrolment pathways to start journey to student. Reached in 3 clicks or less
- Direct enquiry form access.
- Access to career guidance and invite to webinar and open days to start nurturing journey.
- Provide contact point for potential industry contracts to develop bespoke training for employees or potentially fund an intake of a course for employees.
- 

## User Personas
- Science and engineering graduates looking to upskill for life manufacturing industry.
- Industry workers without quallification looking to certify and advance their careers.
- Non-industry workers looking to transition.
- HR departments looking to create Bespoke training for their manufacturing company or fund private course intakes for employers.

## User Stories
- As a graduate, I would like easy access to access to course information and course enquiry forms.
- As an HR associate for manufacturing company, I want a contact form to arrange bespoke training or private intake.
- As a potential student, I would like to see details of each course offering so I can compare and the enquiry.
- As current employee, I would like to choose a course I feel would be the best pick to advance my career. I would like to sign up for a  webinar or an Open day to  assesswhat your courses can offer me.
- As a career transitioner, I want a guidance form so I get advice without knowing exact course fit.
- As a potential student or HR associate, I want a testimonials carousel so I trust your life sciences course and training programs.

## Wireframes

- Home Page (320px-576px-768px>1200px): ![Home page wireframe](wireframes\home-page-wireframe.png)

# Features
This website is built as a responsive, static site using HTML, CSS with Bootstrap to provide an intuitive user experience for potential students of LifeSciSkill Academy.
Key features include:
## 1. Responsive Navigation Bar
- Fixed-top navbar with brand logo, navigation links, and an "Enquire" call-to-action button.
- Mobile-friendly offcanvas menu that slides in from the right, with smooth closing on link clicks.
- Includes links to Home, Courses, Events, Testimonials, and Career Guidance.
- Technical Details: Uses Bootstrap's navbar and offcanvas components, with JavaScript for offset scrolling to account for the fixed navbar height.

### Screenshots
![Navbar](screenshots\navbar-desktop.webp)
![Navbar Drawer](screenshots\navbar-drawer.webp)
## 2. Hero Carousel
- Automatic image carousel showcasing key messages:  for this demo version it shows course intake announcements, open days, and graduation highlights.
- Includes overlay text captions with calls-to-action (e.g., "Learn More" buttons linking to courses or events).
- Technical Details: Built with Bootstrap carousel, enhanced with custom CSS for caption styling.
### Screenshots
![Hero Image Carousel with logo](screenshots\hero-image-1.webp)
![Hero Image 2 showing glassomorphic overlay](screenshots\hero-image-2.webp)

## 3. Courses Section
- Grid of Bootstrap cards featuring images that showcase the types of courses offered: Pharmaceutical Manufacturing, Business, Medical Devices, and Digital Transformation.
- Each card links to the detailed courses page; includes a "Learn More" button for easy access.
- Responsive layout that adapts from 1 column on mobile to 4 columns on large screens.
- Technical Details: Uses Bootstrap grid and cards, styled with custom CSS
### Screenshots
![Courses Section on Home Page](screenshots\course-home.webp)

## 4. Events Section
- Table listing upcoming webinars and open days with dates, times, and event names.
- Includes a "Register Now" button linking to the events page.
- Informational text about live events for lead nurturing.
- Technical Details: Bootstrap table with hover effects; responsive design ensures readability on all devices.
### Screenshots
![Events Section on Home Page](screenshots\events-section.webp)
## 5. Testimonials Carousel
- Video carousel featuring student testimonials to build trust and credibility.
- Navigation controls for manual browsing.
- Technical Details: Bootstrap carousel with <video> elements style and made respponsive with CSS.
![Testimonials Section on Home Page](screenshots\testimonials.webp)

## 6. Sticky Call-to-Action (CTA)
-On mobiles, the Enquire button in navbar is replaced by a floating "Enquire" button in the right thumb position for persistent access to enquiry forms throughout the website.
-Links directly to the course enquiry form.
-Technical Details: HTML button positioned with CSS position: sticky.

![Sticky CTA button on mobile screens](screenshots\sticky-cta-mobile.webp)

## 7. Footer with Contact Information
Comprehensive contact details: address, phone, email, and social media links.
Includes a "Career Guidance" section with a direct link to Career guidance form.
Social media icons for Instagram, Facebook, and X.
Technical Details: Implemented using Bootstrap grid layout, utility classes and Font Awesome icons.

![Footer](screenshots\footer.webp)

## 8. Lead Generation Forms and Pathways
Multiple enquiry pathways: direct "Enquire" buttons, career guidance form, and event registration.
Forms are accessible within 3 clicks from the homepage, aligning with user needs.
Technical Details: Forms implemented with Bootstrap form controls and responsive grid. Forms redirect to success page on submission of form.  

![Enquiry Form](screenshots\enquiry-form.webp)
![Enquiry Form Redirect page on submission of form](screenshots\enquiry-form-submission.webp)


## 9. Detailed Courses Page with Tabs
Interactive tabbed interface for exploring courses
Each tab displays details of a course: delivery locations, entry requirements, curriculum overview, and funding information which allows users to compare courses easily without page reloads.
Technical Details: Built with Bootstrap nav-pills and tab content. Customised with CSS

![screenshot of course tabs](screenshots\courses-tab.webp)

## 10. Events Page with Accordion
Collapsible accordion layout for detailed event information, enabling users to expand specific events for more details (e.g., descriptions, registration links).
Supports multiple events with clean, space-efficient design.
Technical Details: Uses Bootstrap accordion component; ensures only one panel expands at a time for better UX.

![Screenshot of Events Accordion](screenshots\events-accordion.webp)

# Future Improvements
Due to time constraints, a full B2B section (e.g., dedicated corporate training forms and partnership inquiries) was not implemented but could have been added to better support HR departments and industry partners for bespoke training or funded course intakes. This would enhance the site's alignment with B2B business goals as outlined in the user needs.

Additionally, a journal or newsletter signup section could have been included to allow users to subscribe for updates on new courses, events, and industry insights, further supporting lead nurturing and brand awareness.

# Bugs

# Testing
## W3C Validators
- No errors returned for HTML and CSS W3C Validator and Jigsaw respectively. 

## Lighthouse Automated Testing
Lighthouse audited the deployed site using Navigation mode across Performance, Accessibility, and Best Practices categories. Performance and Accessibility reached 99% by addressing these optimizations:

### Performance Optimizations
- Compressed WebP images via tinypng.com to reduce file sizes

- Added <link rel="preload"> for hero images to improve LCP

- Adjust Google Fonts import to remove unused fonts

- Set explicit width/height attributes on navbar logo.

### Accessibility Fixes
- Updated main content buttons to primary navy background instead of blue to give better contrast with gold text - for better WCAG compliance.

# Credits

- Perplexity AI used for text content,and hexcode to rgba conversions
- Code for responsive grid from Bootstrap documents, implementation inspired by grid layout video from Boardwalk games project, modified to fit project.
- Code for navbar from bootstrap documentation, customised for website. Brand logo generated by Logo.com
- Class to prevent navbar blocking main content inspired by boardwalk games project. Padding value adjust in dev tools to fit project.
- Box shadow, Transform and transition k walkthrough project.
- Site images and videos generated by Artlist.io using Nano Banana model.
- Template for section structure inspired by boardwalk games project. Customised using custom css and bootstrap classes to fit project.
- Hero image carousel added from bootstrap customised to fit theme of project.
- Events section and form created using bootstrap. Customised to project.
- Course information section implemented using nav and tabs from bootstrap and customised to project theme. Text content for fake course generated using Perplexity AI and editted to fit project.
- Course Enquiry form created using Bootstrap form control. Customised to fit project theme.
-Centering of bootstrap carousel captions as suggested by https://www.freecodecamp.org/news/how-to-center-an-absolute-positioned-element/
- Glassy carousel captions as described by https://blog.openreplay.com/create-glassmorphic-ui-css/
- Accordion on events page from Bootstrap. Customised to fit project theme, targeted Bootstrap variables to change component styles.
-JS script to close menu after navigation was taken from Boardwalk Games Project code and modified by VS Code agent to fit project. My understanding is the provided code was designed to work on collapse navbars and not offcanvas drawers
-Event information presented using Bootstrap Accordion. Customised to fit project.properties added to button hover classes after reading about CSS button properties on W3C. Source: https://www.w3schools.com/css/css3_buttons.asp
- Used bootstrap utility classes to structure and arrange footer, Styling of footer inspired by Boardwalk Games.
- Forms based on bootstrap form control. Grid implementation inspired by boardwalk games project. Styles and additional input fields added to suit project.
- Business model inspired by Innopharma Education.
- Favicons used are from Font Awesome.
- Fonts come from Google Fonts import.
 - Enquire now button felt out of place in the drawer on nav screen. To solve I made the button display none by default and used a media button to make it visible again at 992px breakpoint.
 - Sticky CTA button for mobile/ touchscreens: Inspired by https://stackoverflow.com/questions/39617803/sticky-bottom-button-only-on-mobile
   Customised to fit project using CSS tutorial on W3S.
- Had some trouble centring images in the hero carousel. Tried to use background property initially before realising this does not work on img elements. Options were to remove img element and use background on carousel-item or  use object-fit: center on img elementsas suggested by W3C: https://www.w3schools.com/css/css3_object-fit.asp
- Initally the carousel caption backgrounds were overflowing when container becomes too small for contents. Solution media query to to set max-height for small screens and flex to captions to dynamically adjust height and centre the contents. Overflow was also issue when height is restricted, problem for phones in landscape mode (height <~600px>). Solution to add landscape orientation media query to adjust caption background height. Solution source: https://www.w3schools.com/css/css3_mediaqueries_ex.asp
- I had difficult overriding bootstrap tables and nav-pills classes. Using devtools saw bootstrap table class has higher specificity variables. Used custom CSS to target these and customise table text color, background and cell borders, and the text of inactive nav-pills. Source: https://blog.getbootstrap.com/2022/05/16/using-bootstrap-css-vars/

# Bugs
- Displacement glitch in hero carousel on index.html when carousel transitions to and from image 1. Maybe be related to additional caption overlay.

### Media

- Images and videos generated by Artlist.io
- Colour palette selected from Color Hunt  https://colorhunt.co/palette/1b3c53456882d2c1b6f9f3ef


















