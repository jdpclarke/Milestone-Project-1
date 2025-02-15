# FE Funding 4 U (FF4U) - Milestone Project 1

**A website providing easy guidance on funding available for adults in the Further Education sector in England.**

![Responsive Mockup](https://github.com/jdpclarke/Milestone-Project-1/blob/8e53a35f874546d49c216cc0bc37a687dd57a498/Assets/README/Example%20Screens.png)

## 1. Overview

FE Funding 4 U (FF4U) is a website designed to simplify the often-complex process of finding funding for Further Education courses in England. It targets adults who are considering returning to education or upskilling but are unsure about the financial support available. The site provides clear information about the Education and Skills Funding Agency (ESFA), the Adult Skills Fund (ASF), various funding models (fully funded, co-funded, loans), and links to key resources. The goal is to empower users to explore their funding options and confidently embark on their learning journey.

This project focuses on creating a responsive and user-friendly website with a clear information architecture. It addresses accessibility considerations and follows best practices for web development.

## 2. User Experience (UX)

### User Stories

#### Feature 1: Easy Navigation and Understanding

- **As a user,** I want the website to be easy to navigate and understand, even if I'm not familiar with funding terminology. I want clear explanations of acronyms and jargon.

  - **Acceptance Criteria:**

    - The website has a clear and intuitive navigation menu.
    - A consistent page layout is used throughout the site.
    - The website uses clear and concise language.

  - **Tasks:**
    - Design and implement the navigation menu.
    - Create a consistent page template.
    - Review all content for clarity and conciseness.
    - Conduct usability testing to ensure ease of navigation.

#### Feature 2: Mobile Responsiveness

- **As a user on a mobile device,** I want the website to be responsive and display correctly on my smaller screen, ensuring a seamless experience.

  - **Acceptance Criteria:**

    - The website adapts to different screen sizes and orientations.
    - The layout, images, and text resize appropriately on mobile devices.
    - The website is usable on touchscreens.

  - **Tasks:**
    - Implement responsive design using CSS media queries and Bootstrap.
    - Test the website on various mobile devices and screen sizes.
    - Ensure touch screen compatibility.

#### Feature 3: Information about ESFA

- **As a potential student,** I want to easily find information about the ESFA and its role in funding adult education so that I can understand the overall funding landscape.

  - **Acceptance Criteria:**

    - A dedicated section on the ESFA is present on the website.
    - The section explains the ESFA's mission and responsibilities related to adult education funding.
    - The information is presented in clear, concise language, avoiding jargon or providing definitions for technical terms.
    - Links to the official ESFA website are provided for further reading.

  - **Tasks:**
    - Research and gather information about the ESFA.
    - Write content for the ESFA section, ensuring clarity and accuracy.
    - Create the HTML structure for the ESFA section.
    - Style the section using CSS.
    - Add links to the official ESFA website.

#### Feature 4: Understanding Funding Models

- **As an adult learner,** I want to understand the different funding models available (fully funded, co-funded, Advanced Learner Loan) so that I can assess which options are most relevant to my circumstances.

  - **Acceptance Criteria:**

    - Each funding model (fully funded, co-funded, Advanced Learner Loan) is clearly explained in its own section.
    - The explanations include eligibility criteria, application processes, and any associated costs.
    - Examples of courses or situations where each funding model might apply are provided.
    - The information is accessible and easy to understand, even for users unfamiliar with funding terminology.

  - **Tasks:**
    - Research and document the various funding models.
    - Create separate sections for each funding model.
    - Write clear explanations for each model, including eligibility and application information.
    - Add examples to illustrate each model.
    - Style the funding model sections.

#### Feature 5: Exploring Career Paths and Funding

- **As someone considering a career change,** I want to explore potential career paths and see what funding opportunities are available for relevant courses so that I can plan my next steps.

  - **Acceptance Criteria:**

    - The website provides links to resources for exploring career paths (e.g., job market information, career advice websites).
    - Information on how to find funded courses related to specific career areas is included.
    - The website clearly explains how funding can support career changes.

  - **Tasks:**

    - Research and identify relevant career exploration resources.
    - Create a section on career change and funding.
    - Provide links to career resources.
    - Explain how to find funded courses related to career changes.
    - Style the career change section.

#### Feature 6: Clear Website Introduction

- **As a first-time visitor,** I want a clear explanation of what the website offers so I can quickly understand if it's relevant to me.

  - **Acceptance Criteria:**

    - The homepage includes a concise and compelling introduction to the website's purpose.
    - The introduction clearly states the target audience and the services provided.
    - Key benefits of using the website are highlighted.
    - The introduction is visually appealing and easy to read.

  - **Tasks:**
    - Write a clear and concise introductory paragraph for the homepage.
    - Design the layout of the homepage introduction section.
    - Choose appropriate visuals (images, icons) to accompany the introduction.

#### Feature 7: Eligibility Assessment Referral via Help Page Form

- **As a user who is unsure about my eligibility and seeking assistance,** I want to be able to submit a request for an eligibility assessment via a form on the help page so I can get personalised advice and understand my funding options.

  - **Acceptance Criteria:**

    - A dedicated form for eligibility assessment requests is present on the help page.
    - The form is clearly labelled and easy to find on the help page.
    - The form collects the necessary information from the user (e.g., contact details, course interests, employment status, specific questions).
    - The user receives confirmation (e.g., a thank you message or email) that their request has been submitted successfully.
    - Information is provided about the typical timeframe for response.
    - The form is accessible and usable on all devices (desktop, tablet, mobile).

  - **Tasks:**
    - Design and develop the eligibility assessment request form, including appropriate input fields (text, dropdowns, checkboxes).
    - Determine the specific information required from users for the eligibility assessment.
    - Implement client-side form validation to ensure data accuracy and completeness before submission.
    - Create a confirmation message to acknowledge successful submission and provide further information to the user.
    - Ensure the form and help page content are accessible according to WCAG guidelines (e.g., proper labelling, keyboard navigation, screen reader compatibility).
    - Thoroughly test the form submission process, including validation and confirmation.

### Design

- **Colour Scheme**

  When people hear the word funding, the most common association is simply money, as funding is the provision of financial resources. As such, the colour palette for this project has been sampled from a £20 note as sourced from the [Bank of England Specimen Image](https://www.bankofengland.co.uk/banknotes/polymer-20-pound-note). The below colour palette was generated from the Front of the Queen Elizabeth II note using [IMAGECOLORPICKER.com](https://imagecolorpicker.com/)

  ![Colour palette for this project](https://github.com/jdpclarke/Milestone-Project-1/blob/a2c8f37c5d7a062c29b87db03c4eda8f13876bf4/Assets/README/Colour%20Palette.png)

- **Typography**

  The ["Rubrik"](https://fonts.google.com/specimen/Rubik) font family has been selected as the main font used throughout the whole project with Sans Serif as the fallback font in any case that the font isn't being imported into the project correctly. Rubrik is a classified as a variable font which allow one font file to contain multiple variations. You can change the weight, width, style, optical size, and more. The variables within variable fonts are controlled by axes.

  The ["Righteous"](https://fonts.google.com/specimen/Righteous) font family has been selected as the heading element font. Righteous is classified as a static font and is not as versitile as a variable font, hence why this is used for heading elements only.

### Imagery

This website utilises a variety of images to enhance the user experience and convey information effectively. The images serve several purposes:

- **Branding:** The logo (`Assets/Images/logo.png`) is used in the navigation bar to reinforce brand identity and provide a consistent visual element throughout the site.

- **Homepage Carousel:** The carousel on the homepage (`Assets/Images/index-carousel-1.svg`, `Assets/Images/index-carousel-2.svg`, `Assets/Images/index-carousel-3.svg`, `Assets/Images/guide-carousel-2.svg`, `Assets/Images/guide-carousel-3.svg`, `Assets/Images/guide-carousel-4.svg`, `Assets/Images/guide-carousel-5.svg`) features rotating images with accompanying text to highlight key information, promotions, or calls to action. These images are designed to be visually appealing and informative.

- **Informational Images:** Images are incorporated within the accordion sections (`Assets/Images/esfa-2.jpg`, `Assets/Images/asf.jpg`) and card components (`Assets/Images/esfa.jpg`, `Assets/Images/career-search.jpg`, `Assets/Images/ncs.webp`, `Assets/Images/funding-grants.jpg`) to illustrate concepts, break up text, and make the content more engaging. These images are carefully selected to be relevant to the surrounding information.

- **Favicon:** A favicon (`Assets/favicon/apple-touch-icon.png`, `Assets/favicon/favicon-32x32.png`, `Assets/favicon/favicon-16x16.png`) is included to provide a visual cue for the website in browser tabs and bookmarks. This also provides a first look in to the brand of the website.

All images used on the website are optimised for web performance to ensure fast loading times and a smooth user experience. Alternative text (alt text) is provided for all images to ensure accessibility for users with visual impairments and to improve SEO. The alt text descriptions are concise and descriptive, accurately conveying the content and purpose of each image. For example, the carousel images have descriptive alt text explaining the message conveyed in each image. Similarly, the images in the accordion and card sections have alt text that describes the subject of the image.

### Wireframes

## 3. Features

- **Homepage with Clear Introduction:**
  - A concise and informative introduction explaining the purpose of the website and the benefits of using it.
  - A visually appealing design with a clear call to action, encouraging users to explore funding options.
  - A carousel showcasing key funding information and highlighting different opportunities available through the ESFA.  Each carousel item includes descriptive alt text for accessibility.

- **Detailed Explanations of Funding Models:**
  - Dedicated sections explaining each funding model:
    - **Fully Funded:**  Describes courses where the ESFA covers 100% of the cost, outlining eligibility criteria and examples of relevant courses (e.g., English and Maths, Free Courses for Jobs, Skills Bootcamps).
    - **Co-Funded:** Explains situations where the ESFA covers a portion of the cost, with the learner contributing the remainder.  Provides clarity on how co-funding works and where it might apply.
    - **Advanced Learner Loan:**  Details this loan option for higher-level qualifications (Level 3 and above), explaining the borrowing process and repayment terms.  Clarifies that while not strictly part of the Adult Skills Fund (ASF), it's a key funding avenue for adult learners.
  - Use of accordion elements to present detailed information in a collapsible and user-friendly format, improving readability and navigation.

- **Links to Relevant Government Websites and Resources:**
  - Clearly labelled links to:
    - **ESFA Website:**  Direct link to the official ESFA website for comprehensive information on funding rules and policies.
    - **National Careers Service:** Link to the NCS website for career exploration, course searching, and skills development resources.
    - **Find a Learning Aim:** Link to the government service for finding course funding information.
  - Links open in new tabs to ensure users remain on the FF4U website while accessing external resources.
  - Concise descriptions provided for each link, explaining the type of information users can find on the linked website.

- **Responsive Design:**
  - Website layout adapts seamlessly to various screen sizes and orientations (desktops, laptops, tablets, and mobile phones).
  - Navigation menu is accessible and functional on all devices, ensuring ease of use.
  - Images resize appropriately to maintain visual quality and optimize loading times on different devices.

- **Accessible Design:**
  - Semantic HTML structure used to improve website structure and accessibility.
  - Descriptive alt text provided for all images to convey their meaning to screen reader users.
  - Full keyboard navigation support, allowing users to navigate the website without a mouse.
  - Sufficient colour contrast maintained to meet accessibility requirements.

- **Footer with Contact Information and Social Media Links:**
  - Contact information provided, including phone number, email address, and physical address.
  - Links to social media profiles (Instagram, Facebook, Twitter/X) to connect with the FF4U community.
  - Disclaimer and copyright information clearly stated to protect intellectual property and inform users about the limitations of the information provided.
  - Embedded Google Maps location to help users find the physical address.

## 4. Technology Used

This project, FE Funding 4 U (FF4U), was built using a combination of front-end web development technologies to ensure a responsive, accessible, and user-friendly experience.

- **HTML5:** HTML5 was used as the foundation for the website's structure and content. Semantic HTML5 elements were employed to create a logical and accessible document outline, improving both search engine optimization (SEO) and screen reader compatibility. The use of semantic elements like `<nav>`, `<header>`, `<main>`, `<section>`, and `<footer>` clarifies the purpose of different parts of the page, making the content more understandable for both users and machines.

- **CSS3:** CSS3 was used for styling the website and controlling its visual presentation. Custom CSS rules were written in the `style.css` file to enhance and tailor the website's appearance beyond the default styles provided by Bootstrap. CSS classes were strategically applied to elements to manage layout, typography, colours, and spacing. This included the creation of custom classes for styling elements like bullet point lists and video wrappers.

- **JavaScript:** JavaScript was used to implement interactive features. While the provided code primarily relies on Bootstrap's JavaScript for interactive components, future enhancements will incorporate more custom JavaScript. The inclusion of Bootstrap's JavaScript via CDN enables functionalities such as the collapsible navigation menu and accordion elements.

- **Bootstrap 5:** Bootstrap 5, a popular front-end framework, was utilized to create a responsive and mobile-first design. Bootstrap's grid system facilitated the creation of a flexible layout that adapts seamlessly to different screen sizes. Pre-built components, such as navigation bars, cards, and accordions, were used to accelerate development and ensure consistency in the user interface. The framework's built-in responsive utilities and CSS classes were used extensively to manage the website's responsiveness. The dark theme functionality was also utilized.

- **Font Awesome:** Font Awesome icons were integrated into the website to enhance visual appeal and improve user experience. Icons were used to represent different sections and concepts, making the content more engaging and easier to understand. The use of icons also contributes to a more intuitive navigation experience.

- **Google Maps API (Embedded):** The Google Maps API was used to embed a map of the organization's location within the footer. This enhances user experience by providing a visual and interactive way to locate the organization's physical address.

- **YouTube Embed (iFrame):** Although the included source is a placeholder, the website is designed to embed youtube videos using iFrames. This allows for the integration of video content to further explain and enhance the website's information.

- **CDN (Content Delivery Network):** Bootstrap's CSS and JavaScript were loaded from a CDN. This allows for faster loading times as it uses servers geographically closer to the user.

## 5. Installation

## 6. Usage

## 7. Testing

## 8. Deployment

## 9. Credits

## 10. Future Improvements
