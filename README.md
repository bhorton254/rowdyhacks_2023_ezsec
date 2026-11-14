# rowdyhacks_2023_ezsec
Awarded "Best Cyber Hack" during the RowdyHacks Hackathon in 2023, created by Brandon Horton and Gabriel Ferrer. EZSec (EZSecurity) is a Chrome extension designed to simplify browser security settings for non-technical users by altering certain Chrome Privacy APIs to promote a more secure browser.

----------------------------------------------------------

**Original README.md:**

Purpose: Assisting the elderly and individuals who are not tech-savvy. Provides an extra layer of security to their Chrome browser by enabling a few security features, that are otherwise turned off (by default), all conveniently at the click of one button.

FOR TESTING AND PERSONAL USE: Be sure to install ALL of the files, including images, and place them in one folder. For testing, upload the folder to chrome://extensions and be sure to enable developer console!

----------------------------------------------------------

**More Information:** 

(**Overview**)

EZSec is a Chrome extension developed during RowdyHacks 2023 to simplify browser security and privacy configuration for users with limited technical experience/knowledge. The extension provides a one-click interface that adjusts several browser privacy preferences through Chrome's Privacy API.

(**Features**)

- Enables Chrome Safe Browsing (subject to browser API support).
- Enables 'Do Not Track' requests.
- Disables address autofill.
- Disables credit card autofill.
- Displays status updates after successful configuration requests.

(**Technologies**)

- JavaScript
- HTML5
- CSS3
- Chrome Extensions Manifest V3
- Chrome Privacy API

(**How It Works**)

The extension uses a popup interface containing a single "Secure Browser" button. When clicked, JavaScript invokes Chrome Privacy API methods to request changes to supported browser settings. The popup updates its status indicators after successful API calls.

(**Project Background**)

EZSec (AKA "EZSecurity") was developed collaboratively during RowdyHacks 2023, with the goal of making browser security controls more accessible to elderly individuals and users unfamiliar with browser configuration. The project was developed in a single night. Me and my co-developer, Gabriel Ferrer, got little to no sleep and had to learn HTML, CSS, and JS in a single night. Admittedly, we had some help along the way with some senior Computer Science students at UTSA, but me and Gabriel completed the bulk of what was created in this repo. The project received the Best Cyber Hack Award.

(**Limitations**)

EZSec is a hackathon prototype originally developed in 2023. It is most likely not compatible with modern Chrome versions, though this may need verifiability. The extension does not automatically manage cookie-consent banners, block all tracking, or provide comprehensive browser security protection (i.e., against social engineering attempts or SQL injection attacks).

(**Future Improvements**)

- Synchronize status indicators with actual browser settings 
- Update compatibility to utilize Chrome's current Privacy API.
- Improve API error handling.
- Add individual controls for each privacy preference.
- Improve accessibility and user feedback.
