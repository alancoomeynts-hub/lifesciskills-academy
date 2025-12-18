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
- Provide contact point for potential industry contracts to develop bespoke training for employees or potentially fund an intake of a course for employees

## User Personas
- Science and engineering graduates looking to upskill for life manufacturing industry.
- Industry workers without quallification looking to certify and advance their careers.
- Non-industry workers looking to transition.
- HR departments looking to create Bespoke training for their manufacturing company or fund private course intakes for employers.

## User Stories
### 1. Easily navigatible and responsive website design.
   User story: As a graduate, I would like easy access to access to course information and course enquiry forms.

#### Acceptance Criteria:
  - Responsive on mobile/tablet/desktop using Bootstrap breakpoints.
  - All key pages and sections (Home/Courses/Events/Testimonials/ Industry Training/Enquire Now) linked in navbar dropdown.
  - Ensure the Navigation bar collapses on mobile after modal/form interactions

#### Tasks
   - Create easily navigable website using responsive design principles and best practice using Bootstrap navbar and grid components.
   - Create Responsiveness utilizing Bootstrap breakpoints, using drawer for smaller screens.
   
      
### 2. Highly Quality presention of information on LifeSciSkills Academy courses (Must Have)
   User Story: As a potential student, I would like to see details of each course offering so I can compare and the enquiry.
  #### Acceptance Criteria
   - Courses page provides programs details, presentation in accessible and responsive way
   - Form accessible below course details to collect enquiry information.
   - Form must be complete before submission and user recives feedback on successful submission.
   - Hero image with grid cards of available program on home page. January 2026 Intake now open + Funded Places available
  #### Tasks:
   - Create navbar and tabs containing details of each course: Academic eligibilty, Course curriculum, price, duration and delivery method.
   - Implement Form with validation to collect information: coure of interest,preferred deliverivy location, name, phone, email, lead source, employment status and additional message.
   - Implement hero image with overlay of Bootstrap cards to show programs available for next intake. Grid must be responsive, transparent for Hero image to come through.
   - Call to Action button in navbar to quickly open enquiry form. For larger screen implement CTA button in the top right corner. On mobile CTA button is a sticky button on the bottom right.
   - Direct to success page on form submission.
    
### 3. Events and Webinars (Must Have)
   User Story: As current employee, I would like to choose a course I feel would be the best pick to advance my career. I would like to sign up for a webinar or an Open day to  assesswhat your courses can offer me.

#### Acceptance Criteria
   - Events section on home page with table of upcoming webinar and open day events.
   - Card grid on event page of upcoming events.
   -  Form to register intent to attend and submit enquiry. Form requires event name, course of interest,preferred delivery location, name, phone, email, lead source, employment status and additional message.
   

 #### Tasks
   - Section on Home page - Invitation to register for an event.
   - Table of upcoming events
   - Events page with card grid of upcoming events
   - Registration form to collect details.
   - Direct to success page on registration.
       
      
### 4. Career Guidance (Should Have)
User Story: As a career transitioner, I want a guidance form so I get advice without knowing exact course fit.
#### Acceptance Criteria
- Footer link dedicated section with career advice form
- Form collects goals, background, preferred location (no course selection required)
  
#### Tasks
- Create CTA and link to HTML form in Footer
- Form fields: career goals (textarea), current role, location preference, name, email, phone, message
- Direct to success page on submission
    
### 5. Testimonials (Should Have)
 User Story: As a potential student or HR associate, I want a testimonials carousel so I trust your life sciences course and training programs.
#### Acceptance Criteria
 - Responsive Bootstrap carousel on homepage 
 - Mix of quote cards from alumni (name, role, company, quote)
 - Auto-rotate + manual navigation, mobile swipe support
 - logos section of companies LifeSciSkills Academy has created bespoked training for.
   
#### Tasks
-	Implement Bootstrap carousel with testimonials section on home
-	Showcases a mix of testimonial cards and videos.
-	Ensure carousel is mobile friendly 
-	Responsive grid of logos 

### 6. B2B Contact Form (Must Have)
   User Story: As an HR associate for manufacturing company, I want a contact form to arrange bespoke training or private intake.
#### Acceptance Criteria
- Dedicated section in course page with access from navbar
- Dedicated B2B form with company fields + training needs
- Fields: company name, team size, training type, budget range, contact details
- Success message: "B2B specialist will respond within 24hrs"
#### Tasks
- Link to B2B section on navbar
-	Create B2B form fields: company, role, employees, training needs (select), dates
-	Form validation
-	Responsive form layout with Bootstrap grid





# Website Layout Planning

## Home page

### Navbar - Home Courses Events Testimonials Enquire Now

### Main
- Hero Image Header - January Intake now Open + Grid with overlaid course cards - Learn more button links to Courses page
- Section Grid with Events table - link to events page for registration
- Testimonials Carousel (videos + quotes PARTNER logos slider)

### Footer
-Address
-Contact Us - Career Advice
-Social media links

# Courses Page
###Navbar - Home Courses Events Testimonials Enquire Now
### Intro Header
### Main
-  Section Nav tab with details of each course
-  Section B2b Contact - Modal Form
-  Section Enquiry Form

### Footer
-Address
-Contact Us Modal form - Career Advice
-Social media links

# Events Page 
### Navbar - Home Courses Events Testimonials Enquire Now
### Intro Header

### Main
- Section Table with upcoming webinars
- Section Registration Form
  
### Footer
-Address with map iframe modal
-Contact Us - Career Advice - modal form
-Social media links
# Bugs
 - Enquire now button felt out of place in the drawer on nav screen. To solve I made the button display none by default and used a media button to make it visible again at 992px breakpoint.
 - Expected issue adding sticky CTA button for mobile screen. Hoping following source can help out: https://stackoverflow.com/questions/39617803/sticky-bottom-button-only-on-mobile

# Code
- Code for responsive grid from Bootstrap documents, implementation inspired by grid layout video from Boardwalk games project, modified to fit project.
- Code for navbar from bootstrap documentation, customised for website. Brand logo generated by Logo.com
- Class to prevent navbar blocking main content inspired by boardwalk games project. Padding value adjust in dev tools to fit project.
- Transform and transition properties added to button hover classes after reading about CSS button properties on W2C. Source: https://www.w3schools.com/css/css3_buttons.asp

Resources:

Colour palette selected from Color Hunt  https://colorhunt.co/palette/1b3c53456882d2c1b6f9f3ef
Logos generated by Logo.com














