## Notes for people designing service and interfaces

This is a work in progress - a structured brain dump!

### Best practices by type of design
#### Graphic design
* Design page text with sufficient contrast - colour contrast between foreground and background is sufficiently strong (text and form borders). 
* Text is never aligned justified
* Line spacing between lines of text should be at least a space-and-a-half depending on text size
* Spaces between paragraphs should be at least 1.5x larger than line height
* Default text size should not be too small
* Watch the use of CAPS and italic text
* Don't present text as an image (except in logos, graphs, screenshots, and diagrams)
* Include image and media alternatives in your design
* Logical chunks of content should be grouped together visually.
* Headings should visually reflect their level (h1, h2 etc.).
* Links should be easily detectable when visually scanning the page.
* Link text provides its own context
* Avoid duplication of links
* Ensure that interactive elements are easy to identify
* Ensure clickable items have adequate target areas
* Current keyboard focus is easily visible
* Colour or shape should not be used as the only means of conveying information. Colour conveying meaning is reinforced using other methods.
* Content does not flash more than 3 times in a second.
* Create designs for different viewport sizes

#### Interaction design
* Users can skip straight to the main page content using a keyboard
* Text should be able to dynamically resize without requiring the user to scroll horizontally. Page content is not obscured if the page is magnified to 200%.
* It should be possible to zoom content without loss of display or function.
* Interactive components should look and feel the same wherever they're used.
* The placement of components that appear on multiple pages should be consistent - this is especially important for screen magnification user who cannot only see part of the viewport 
* All functionality that is available when using a mouse is also available when using a keyboard - and is just as usable. (eg Don’t make people hover to find things)
* When a component gets focus it doesn’t automatically change context
* Where there is a time limit on an activity, users can disable or extend the time limit
* Moving or auto-updating content on a page can be paused, stopped or hidden
* Consider how people who can't see will interact with dynamic content. If new content appears on the screen - this either needs to be made available to a user that can't see the screen by being notified of it (using WAI-ARIA) or by focus being moved to the new content.
* Ensure that form elements include clearly associated labels and easily identifiable feedback
* Forms should be submitted by activating a button.
* Audio/video should be controlled on demand. If background audio starts automatically, users need to be able to pause, stop, or mute it.
* We follow the principles of progressive enhancement - how does the non-js version look/work?
* There are multiple ways for users to navigate around the site
* If an experience cannot be made accessible, create another route for users to get that information

#### Service Design
* Users are able to communicate (receive and send) using their preferred channel (web form, web chat, video, phone, face to face, print (standard and large print) and language (easy read, BSL)
* Disabled people are not forced to provide the same information many times to different services (e.g Personal Indepenance Payments and Access to Work)
* Disabled people with a permanent condition are not forced to provide the same information multiple time to the same service (e.g regular PIP review)

## [Strategies for Accessible Design](https://github.com/alphagov/accessibility-guidance/wiki/strategies-for-accessible-design)
There are four main strategies for Accessible Design:

####  Design for most users without modifications
* design with good colour contrast
* write content that is easy to read
* use typography that is easy to see
* structure your content clearly
* make things work consistently
* keep designs clutter and distraction free
* provide captions
* prove scannable links
* provide large hit areas

####  Design for easy adaptation to different users
* ensure your site still works when default styles are overridden
  * change colours
  * increase font size
  * change font
* consider providing a mechanism for users to listen to web content (e.g [ReadSpeaker](http://www.readspeaker.com/))
 
####  Complementary design providing alternative approaches for contradictory accessibility requirements of users,
* For interactive maps also provide the ability to search for a location using a search box and getting text based results rather than relying purely on a visual interface
* For interactive data visualisations also provide access to the raw data
* for services that utilise a phone / call centre ensure that there are alternative ways to communicate such as email/SMS and BSL video relay
* for services that send out printed material ensure users can request an alternative format (large print, audio, braille, BSL) and that staff understand these will be sent out free of charge, and that a process is in place so that this happens quickly

#### Design with a view to connect seamlessly to assistive technology.
* markup content with semantic HTML
* allow easy navigation with good headings and landmark roles
* provide skips links
* ensure all features work with a keyboard
* ensure there are no keyboard traps
* provide visible keyboard focus
* manage keyboard focus when required
* write helpful text descriptions for images

http://mandate376.standards.eu/planning-procurement/key-principles-accessible-procurement

### An Accessible Design Maturity Continuum

#### 1. No Conscious Design
Accessibility isn’t recognized in the design process. Any accessibility happens by chance.

#### 2. Style
Efforts are limited to addition of a few cosmetic accessibility features, with little positive impact on users.

#### 3. Function and Form
Focus is on following accessibility guidelines in order to achieve technical compliance. Improvements are made, but users are not directly part of the accessible design process.

#### 4. Problem Solving
A more strategic process of researching and designing solutions to support accessible task completion, but still within a pre-defined design concept.

#### 5. Framing
Accessibility and diversity are integrated into the design process, driving creative thought and sparking innovation.

https://www.paciellogroup.com/blog/2014/06/accessibility-maturity-continuum/

### Principles of Universal design

#### Principle 1: Equitable Use
The design is useful and marketable to people with diverse abilities.

#### Principle 2: Flexibility in Use
The design accommodates a wide range of individual preferences and abilities.

#### Principle 3: Simple and Intuitive Use
Use of the design is easy to understand, regardless of the user's experience, knowledge, language skills, or current concentration level.

#### Principle 4: Perceptible Information
The design communicates necessary information effectively to the user, regardless of ambient conditions or the user's sensory abilities.

#### Principle 5: Tolerance for Error
The design minimizes hazards and the adverse consequences of accidental or unintended actions.

#### Principle 6: Low Physical Effort
The design can be used efficiently and comfortably and with a minimum of fatigue.

#### Principle 7: Size and Space for Approach and Use
Appropriate size and space is provided for approach, reach, manipulation, and use regardless of user's body size, posture, or mobility.

http://universaldesign.ie/What-is-Universal-Design/The-7-Principles/

### Accessible UX Principle and Guidelines

#### People First: Designing for differences
People are the first consideration, and sites are designed with the needs of everyone in the audience in mind.

* Know your audience. (Familiarise yourself with accessibility personas and the full range of human capability)

#### Clear Purpose: Well-defined goals
People enjoy products that are designed for the audience and guided by a defined purpose and goals.

* Start with purpose and goals. 
* Design for clarity and simplicity. 
* Think “accessibility first.”
* Make templates accessible. 
* Choose an accessibility strategy.

#### Solid Structure: Built to standards
People feel confident using the design because it is stable, robust, and secure.

* Code content to be machine-readable.
* Code to standards.
* Use standard web technologies.
* Organize code for clarity and flow.
* Use stylesheets to separate content and presentation.
* Use semantic markup for content.

#### Easy Interaction: Everything works
People can use the product across all modes of interaction and operating with a broad range of devices.

* Identify and describe interactive elements. Use basic HTML codes correctly.
* Use WAI-ARIA for complex elements.
* Use features of the technology platform. 
* Provide accessible instructions and feedback. 
* Support keyboard interaction.
* Make controls large enough to operate easily. 
* Let users control the operation of the interface. 
* Design for contingencies.
* Allow users to request more time.

#### Helpful Wayfinding: Guides users
People can navigate a site, feature, or page following self-explanatory signposts.

* Create consistent cues for orientation and navigation. 
* Present things that are the same in the same way. 
* Differentiate things that are different.
* Provide orientation cues.
* Provide clear landmarks within the page. 
* Provide alternative ways to navigate.

#### Clean Presentation: Visual design supports meaning
People can perceive and understand elements in the design.

* Design simply.
* Minimize distracting clutter.
* Design for customization of the display.
* Support customization through the browser.
* Design content for easy comprehension.
* Use color contrast to separate foreground from background.
* Use visual and semantic white space. 
* Provide enough space between lines of text. 
* Use clean typography.

#### Plain Language: Creates a conversation
People can read, understand, and use the information.

* Write for your audience.
* Follow plain language guidelines for writing content.
* Support users through their tasks.
* Structure the whole page for scanning and understanding.
* Write sentences and paragraphs for easy scanning.
* Write helpful links.
* Use language your audience is familiar with, or provide definitions.
* Provide plain language summaries of complex content. 
* Don’t rely on readability formulas.
* Usability test your content.

#### Accessible Media: Supports all senses
People can understand and use information contained in media, such as images, audio, video, animation, and presentations.

* Don’t use only color to communicate meaning.
* Provide instructions without relying on visual cues. 
* Describe the content or meaning of images.
* Provide captions and descriptions for video.
* Format captions to enhance meaning.
* Provide alternatives to time-based media.
* Use dynamic elements carefully.
* Make presentations accessible.

http://rosenfeldmedia.com/books/a-web-for-everyone/

### Inclusive Design Principles (TPG)
#### Provide comparable experience
* Content for alternatives
* Ergonomic features
* Notifications

#### Consider situation
* Colour contrast
* Context sensitive help
* Captions on the go

#### Be consistent
* Consistent design patterns
* Consistent editorial
* Consistent page architecture

#### Give control
* Scrolling control
* Make it stop
* Allow zoom

#### Offer choice
* Multiple ways to complete an action
* Layout
* Accessible alternatives

#### Prioritise content
* Keep task focused
* Prioritising tasks
* Prioritising content
* Prioritising editorial

#### Add value
* Integration with connected devices or second screen
* Integration with platform APIs
* Make task completion easier

[Inclusive Design Principles](http://inclusivedesignprinciples.org/)

### BBC Accessible Design Guidelines
#### Getting started
* Put people first
* Use familiarity
* Give control
* Offer choice
* Add value

#### Key considerations
* Think about headings, labels and link text
* Think about focus
* Think about colour

[BBC: How to design for accessibility](http://www.bbc.co.uk/gel/guidelines/how-to-design-for-accessibility)

### Tools and techniques to aid accessible design

* Personas with a range of disabilities and modes of interactions
* Cognitive walk through with personas
* Expert review (hueristic evaluation) by an accessibility specialist
* Automated accessibility testing tools / Manual inspection / WCAG Audit
* Usability testing with people with disabilities

### GOV.UK design challenges
* Data visualisation
* Maps
* Admin interfaces and dashboards
* Non-web channels 

### GOV.UK design  issues
* Allowing users to change the appearance of GOV.UK - browsers settings vs widget (most people don't know how to change appearance in browsers)
* Providing text alternatives for video 
	* Video player has not interface control for closed captions
	* No design patterns for transcripts (disclosure vs inpage vs link content)
* Inaccesible PDFs and requesting alternavtives formats
* Provision of BSL and Easy Read content

### Ideas for [Accessibility Training](https://github.com/alphagov/accessibility-guidance/wiki/accessibility-training)

* General accessibility topics (relevant to all disciplines)
* Design topics

## WCAG success criteria most relevant to design
### Level A

#### [1.3.3 Sensory characteristics](https://www.w3.org/TR/UNDERSTANDING-WCAG20/content-structure-separation-understanding.html)
Instructions must not depend on sensory characteristics like shape, size, colour, or location. This ensures that instructions can be understood by users who are unable to see or recognise information communicated using sensory characteristics.
##### Requirements
* Do not use shape, size, colour, or location to communicate instructions.
##### Common issues
* An instruction tells users to "activate the green button";
* An instruction tells users to "use the menu on the left of the page";
* An instruction tells users they can "find more information in the square box";
* An instruction tells users to "follow the biggest link in the tag cloud".
##### Useful resources
* TBC

#### [1.4.1 Use of Colour](https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-without-color.html)
Colour must not be the only thing that identifies or differentiates a piece of informative content. This ensures that people who are unable to see colours, and people who have difficulty distinguishing different colours, can still tell different pieces of content apart.
##### Requirements
* When rendered in monochrome, information does not disappear.
* Text identified by colour as having special meaning has another indicator - a visible border and label, underline or other visual effect.
* Information graphics and charts that use colour as a key also provide distinctive non-colour differences - hatching patterns or directly applied labels.
##### Common issues
* Graphics and charts use colours without redundant patterns or size differences.
* Colour-coding text or backgrounds to indicate essential content, pass/fail categorisation, etc.
* Links are only distinguished from plain text by colour
##### Useful resources
* TBC

#### [1.4.2 Audio control](https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-dis-audio.html)
When audio or video plays automatically on a page, it should last for less than three seconds or there must be a way to pause/stop it. This ensures that people who listen to content with a screen reader can do so without it being drowned out by the audio/video.
##### Requirements
* Audio or video content that plays automatically lasts for three seconds or less;
* Audio or video that plays automatically and lasts for more than three seconds, can be paused and/or stopped.
##### Common issues
* Audio or video plays automatically for more than three seconds, but cannot be paused or stopped by the user.
##### Useful resources
* TBC

#### [2.1.1 Keyboard](https://www.w3.org/TR/UNDERSTANDING-WCAG20/keyboard-operation-keyboard-operable.html)
It must be possible for someone using a keyboard or touch device to complete all tasks in a service. This ensures that people with mobility impairments who do not use a mouse can successfully complete their goals.
##### Requirements
* All interaction and functionality is usable with a keyboard;
* All interaction and functionality is usable on a touch-screen device.
##### Common issues
* A custom widget has been created, but the necessary keyboard support has not been provided;
* An ```<a>``` element has been used as the basis for a button, but the additional keyboard interaction (activation with the space key) has not been provided;
* A dialogue opens but cannot be dismissed by touch, because it does not have a close button;
* The tabindex attribute has been used with a value of "-1" to mistakenly remove it from the tab order.
##### Useful resources
* [Keyboard accessibility](http://webaim.org/techniques/keyboard/)
* [Using the tabindex attribute](https://www.paciellogroup.com/blog/2014/08/using-the-tabindex-attribute/)
* [Ridiculously easy trick for keyboard accessibility](http://www.karlgroves.com/2014/11/24/ridiculously-easy-trick-for-keyboard-accessibility/)

#### [2.1.2 No keyboard trap](https://www.w3.org/TR/UNDERSTANDING-WCAG20/keyboard-operation-trapping.html)
When someone using a keyboard to navigate content moves to an element, they must be able to move away from it again. This ensures that people who use a keyboard do not get stuck on any part of the page.
##### Requirements
* Keyboard focus can move to an element and away again.
##### Common issues
* A dialogue opens but cannot be closed with the keyboard, preventing the user from accessing the original content underneath;
* Content is presented in an infinite scroll, so a keyboard user is forced to tab through everything before they can exit the scroll area.
##### Useful resources
* TBC

#### [2.2.2 Pause, stop, hide](https://www.w3.org/TR/UNDERSTANDING-WCAG20/time-limits-pause.html)
When content moves (is animated, blinks or scrolls) automatically for more than five seconds, or when content automatically updates on the page, it must be possible for users to Pause, stop or hide it. This ensures that people with cognitive disabilities that affect focus and concentration, are not distracted by movement.
##### Requirements
* A mechanism is available that lets users pause, stop or hide the moving or updating content;
* Content does not move (animate, blink or scroll) for more than five seconds;
* Content does not update automatically.
##### Common issues
* Content moves for more than five seconds but there is no mechanism for a user to pause, stop or hide it.
##### Useful resources
* TBC

#### [2.3.1 Three flashes or below](https://www.w3.org/TR/UNDERSTANDING-WCAG20/seizure-does-not-violate.html)
A page must not contain content that flashes more than three times a second. This ensures that people with conditions like photosensitive Epilepsy are protected from harmful seizures.
##### Requirements
* Content does not flash more than three times a second.
##### Common issues
* Content flashes at more than three times a second.
##### Useful resources
* TBC

#### [2.4.1 Bypass blocks](https://www.w3.org/TR/UNDERSTANDING-WCAG20/navigation-mechanisms-skip.html)
When there is repeated content (like a header) at the top of the page, there must be a way for keyboard users to move focus directly to the start of the main content area of the page. This ensures that people who do not use a mouse can quickly and easily reach the primary content of the page.
##### Requirements
* A "Skip to main content" link is provided, and the link is located close to the start of the page;
* The ```<main>``` element is used to represent the main content area of the page.
##### Common issues
* The ```<main>``` element has been used, but there is no skip link that points to it;
* A skip link has been provided, but it does not work in all supported browsers;
* A skip link is provided, but it is only available to screen reader users.
##### Useful resources
* TBC

#### [3.2.1  On Focus](http://www.w3.org/TR/UNDERSTANDING-WCAG20/consistent-behavior-receive-focus.html)
When a keyboard user focuses on a control it must not cause a change of context, such as loading a new page/tab. This stops unexpected things happening without screen reader and screen magnifer users being aware of it.
##### Requirements
* `focus` events do not cause navigation, nor form submission
* components that respond to `focus` do not initiate a "focus trap", where it is impossible or unclear how to navigate out of the component using the keyboard.
##### Common issues
* Dropdown menus trigger navigation as the user tabs between options
* Javascript triggers navigation when a user is merely leaving a form control
* focus is moved by script in ways that surprise the user
##### Useful resources
* TBC

#### [3.2.2  On Input](https://www.w3.org/TR/UNDERSTANDING-WCAG20/consistent-behavior-unpredictable-change.html)
Changing the setting of any user interface component does not automatically cause a change of context unless the user has been advised of the behaviour before using the component.
##### Requirements
* Users can predict what a control such as a button or drop-down menu will do
* User interface components built with javascript have adequate and accurate ARIA labelling.
##### Common issues
* Controls built with javascript lack appropriate ARIA information
* Form controls are used to trigger navigation without an explicit submit step, and without warning
##### Useful resources
[Using ARIA](https://w3c.github.io/using-aria/)

#### [3.3.1 Error identification](https://www.w3.org/TR/UNDERSTANDING-WCAG20/minimize-error-identified.html)
When an error occurs the user is informed what caused the error, and the error is described in text. This ensures that the error is available to people who cannot see, distinguish colours, or understand icons and other visual cues.
##### Requirements
* Each error is described in text;
* Each error is associated with the field it relates to;
* Multiple errors are summarised at the top of the form.
##### Common issues
* An error is only indicated by a red border around the field;
* An error is only indicated by an icon near to the field;
* An error is described in text, but it is not associated with the field it relates to;
* Multiple errors occur, but no summary is provided;
* An error summary is provided, but keyboard focus is not taken to it.
##### Useful resources
* TBC

#### [3.3.2 Labels or instructions](https://www.w3.org/TR/UNDERSTANDING-WCAG20/minimize-error-cues.html)
When data must be entered in a specific format or in a particular way, clear instructions must be associated with the form field. This ensures that everyone understands any requirements for entering data, and does so in a way that ensures that people unable to see the information are made aware of it by their screen readers.
##### Requirements
* Instructions are provided for fields that require data to be entered in a specific format;
* Instructions are properly associated with the relevant form field.
##### Common issues
* Data is expected in a specific format, but no iinstructions have been provided;
* Instructions have been provided, but they are not associated with the relevant field.
##### Useful resources
* [Using aria-describedby to provide form hints](https://www.paciellogroup.com/blog/2014/12/using-aria-describedby-to-provide-helpful-form-hints/)
* [Basic form hints](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/forms/Basic_form_hints)

### Level AA
#### [1.4.3 Contrast minimum](https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-contrast.html)
Text must have a contrast ratio of at least 4.5:1 against its background colour. This makes content easier for everyone to read, but especially partially sighted people.
##### Requirements
* Text (whether plain text or in an image) has a contrast ratio of at least 4.5:1 against its background colour.
##### Common issues
* Text does not have a contrast ratio of at least 4.5:1 against its background colour.
##### Useful resources
* TBC

#### [1.4.4 Resize text](https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-scale.html)
It must be possible for people to increase the size of text by up to 200%. This ensures that partially sighted people can comfortably read content.
##### Requirements
* We need to decide whether we want to use text resize or zoom as the preferred mechanism.

#### [1.4.5 Images of text](https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-text-presentation.html)
Text must not be presented as part of an image because it cannot be resized, and it deteriorates in quality when magnified. This means that everyone is able to read and access information presented in text.
##### Requirements
* Text is not presented as part of an image;
* Text is presented using plain text and styled with CSS.
##### Common issues
* Images contain text.
##### Useful resources
* TBC.

#### [2.4.5 Multiple ways](https://www.w3.org/TR/UNDERSTANDING-WCAG20/navigation-mechanisms-mult-loc.html)
Unless the service is a series of steps, there must be different ways for people to locate and navigate content. Different people will have different preferences, for example someone with a cognitive disability may prefer to browse a sitemap to locate content, whereas someone using magnification may prefer to use search instead of scroll through a lengthy navigation block.
##### Requirements
* Hmm. Difficult to phrase this in a way that's relevant for GDS.

#### [2.4.6 Headings and labels](https://www.w3.org/TR/UNDERSTANDING-WCAG20/navigation-mechanisms-descriptive.html)
Headings must indicate the topic or purpose of the content in that section of the page, and labels must indicate the purpose of the field they relate to. This ensures people with reading difficulties can understand the purpose of content, and that screen reader users can easily navigate to relevant sections of content on the page.
##### Requirements
* Headings describe the purpose or topic of the content that follows;
* Labels indicate the purpose of the fields they relate to.
##### Common issues
* A heading does not indicate the purpose or topic of the content that follows;
* A label does not indicate the purpose of the field it relates to.
##### Useful resources
* TBC

#### [2.4.7 Focus visible](https://www.w3.org/TR/UNDERSTANDING-WCAG20/navigation-mechanisms-focus-visible.html)
It must be easy to tell which element has keyboard focus. This helps sighted keyboard users orient themselves within the page, and confidently interact with it.
##### Requirements
* Interactive elements like links, buttons, and form fields, have a visible focus indicator.
##### Common issues
* The browser default focus indicator has not been replaced with something that is easier to see;
* An indicator has been provided for mouse hover, but not duplicated for keyboard focus.
##### Useful resources
* TBC.

#### [3.2.3 Consistent navigation](https://www.w3.org/TR/UNDERSTANDING-WCAG20/consistent-behavior-consistent-locations.html)
When ways to navigate content are repeated on multiple pages, they must be presented in a consistent manner. This makes it easier for people to learn how to navigate the service, and it enables people to develop strategies (like using screen reader shortcuts) for more efficient navigation.
##### Requirements
* Navigation mechanisms are presented consistently wherever they are used.
##### Common issues
* A main navigation block is used on multiple pages, but is located in a different place on each page;
* A breadcrumb navigation is used on multiple pages, but is presented in a different format on each page.
##### Useful resources
* TBC.

#### [3.2.4 Consistent identification](https://www.w3.org/TR/UNDERSTANDING-WCAG20/consistent-behavior-consistent-functionality.html)
When features with the same functionality are used in multiple places, they must be identified in a consistent way. This helps screen reader users correctly identify the type and purpose of the functionality.
##### Requirements
* An icon has the same alternative text wherever it is used;
* Buttons for "Next", "Previous", and "Continue", are labelled consistently wherever they are used;
* Form fields with the same purpose are consistently labelled wherever they are used.
##### Common issues
* An icon is used to denote a file download, but has a different alternate text whenever it is used;
* A search facility is provided on every page, but the text field and button have different labels on each page.
##### Useful resources
* TBC.

#### [3.3.3 Error suggestion](https://www.w3.org/TR/UNDERSTANDING-WCAG20/minimize-error-suggestions.html)
When an error is detected, suggestions for correcting the issue must be provided unless the suggestion comprimises security. This helps everyone resolve issues more easily, but especially people with cognitive disabilities who find processing information difficult.
##### Requirements
* When an error is detected, a suggestion is provided to help the user correct the issue.
##### Common issues
* An error is detected and the user is notified, but no suggestion is given to help them resolve it;
A login error is detected and a suggestion is provided, but it comprimises security by revelaing that a particular username exists.
##### Useful resources
* TBC.


## Related Resources

### Books
* [A Web for Everyone: Designing Accessible User Experiences](http://rosenfeldmedia.com/books/a-web-for-everyone/)
* [Colour Accessibility Workflows](https://abookapart.com/products/color-accessibility-workflows)

### Web Content
* [How to design for accessibility](http://www.bbc.co.uk/gel/guidelines/how-to-design-for-accessibility)
* [BBC: Accessibility, News and Designers](https://bbc-news.github.io/accessibility-news-and-you/accessibility-news-and-designers)
* [NZGOVT: Web accessibility for designers](http://govtnz.github.io/web-standards/guidance/quick-reference/a11y-designers.html)
* [WAI: Tips on Designing for Web Accessibility](https://www.w3.org/WAI/gettingstarted/tips/designing.html)
* [WebAIM: Web Accessibility for Designers](http://webaim.org/resources/designers/)
* [7 Things Every Designer Needs to Know about Accessibility](https://medium.com/salesforce-ux/7-things-every-designer-needs-to-know-about-accessibility-64f105f0881b#.7slpobstz)
* [Designing accessible products](https://uxdesign.cc/designing-accessible-products-e8aa79b55ebc)
* [Design Before Code: Thinking About Accessibility from the Ground Up – Part 1](https://www.deque.com/blog/design-code-thinking-accessibility-ground/)
* [Design Before Code: Thinking About Accessibility from the Ground Up – Part 2](https://www.deque.com/blog/design-before-code-part-2/)
* [5 Things UX and Visual Designers Can Do to Get Started with Accessibility](https://www.deque.com/blog/5-ux-visual-designers-started-accessibility/)
* [Voxmedia Accessibility Guidelines: Designers](http://accessibility.voxmedia.com/#designers)
* [NDA: Designer's introduction and index](http://universaldesign.ie/Technology-ICT/Web-accessibility-techniques/Designer-s-introduction-and-index/)
* [Access Iq: Design](http://www.accessiq.org/create/design)
* [Google: Material Design - Accessibility](https://material.io/guidelines/usability/accessibility.html)
* [WCAG 2.0 filtered by design role](http://code.viget.com/interactive-wcag/#responsibility=design&level=aaa)
* [WCAG 2.0 filtered by UX role](http://code.viget.com/interactive-wcag/#responsibility=ux&level=aaa)

#### Font size / Typography
* [The 100% easy-2-read standard](https://ia.net/topics/100e2r/)
* [Your Body Text Is Too Small](https://blog.marvelapp.com/body-text-small/)
