README - Portfolio HTML
This README file provides an explanation of the structure and components of the given HTML code. The HTML code represents a portfolio webpage with sections for an introduction, about me, work samples, and contact information. Let's dive into the details of each section:

HTML Structure
The HTML document is enclosed within the <html> tags. It consists of two main sections: <head> and <body>. The <head> section contains meta information, title, and links to external CSS stylesheets. The <body> section holds the content visible on the webpage.

External Resources
The HTML file includes two external CSS files:

reset.css located in ./Assets/css/reset.css: This file is responsible for resetting or overriding default CSS styles to ensure consistent rendering across different browsers.
styles.css located in ./Assets/css/styles.css: This file likely contains custom CSS styles specific to this portfolio webpage.
Introduction Section
The top section contains a name banner with navigation links. The name banner is enclosed within a <div> element with the class "container555".
The navigation links include "About Me," "Work," "Contact Me," and "Resume."
The name "Alan Paccor" is displayed within a <div> element with the class "Name".
Header Image
This section displays a header image with a caption.
The image is enclosed within a <div> element with the class "image-container".
The image source is specified using the <img> tag, with the source file located at "./Images/02-hero-bg.jpg".
The caption is displayed as a <figure> element with the class "image-text".
About Me Section
This section provides information about the portfolio owner.
The section is enclosed within a <div> element with the class "About-Container".
The heading "About Me" is displayed as an anchor link with the ID "About-Me" for navigation purposes.
The content is displayed as an article enclosed within a <div> element with the class "Article".
The article provides a personal narrative about Alan Paccor, his background, interests, and experiences.
Work Section
This section showcases the portfolio owner's work samples.
The section is enclosed within a <div> element with the class "work-container1".
The heading "Work" is displayed as an anchor link with the ID "work" for navigation purposes.
The work sample is displayed as an image and a corresponding project description.
The image is enclosed within a <div> element with the class "big-image".
The image source is specified using the <img> tag, with the source file located at "./Images/02-portfolio-4.jpg".
The project description is displayed within a <div> element with the class "Surf".
Additional Work Samples
This section displays multiple additional work samples in a grid layout.
The section is enclosed within a <div> element with the class "work-container2".
The work samples are displayed as smaller images with descriptions.
Each image is enclosed within an individual <div> element with the class "image-container".
The image source is specified using the <img> tag with the respective class ("small-1" to "small-4") and source file paths.
Each image has an overlay with a project description displayed within a nested <div> element.
Footer Section
This section provides contact information for the portfolio owner.
The section is enclosed within a <footer> element with the class "footer".
The heading "Contact Me" is displayed as an anchor link with the ID "contact-me" for navigation purposes.
The contact information is displayed within