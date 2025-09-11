## CineSplat Release History

* v1.1 - May 5 2025
    * (May 24 2025) Feature - Normalized star icon sizes.
    * (May 24 2025) Feature - Doubleclick on the image opens the image in fullscreen on captures.
    * (May 24 2025) Feature - Changed favourites icon to a red circle with a white star.
    * (May 10 2025) Feature - Clicking on Cinesplat logo redirects to root URL. 
    * (May 10 2025) Feature - Added 0.4 transparent black overlay for landing page. 
    * (May 8 2025) Feature - Changed password field to text field on landing page. 
    * (May 8 2025) Feature - Changed password field placeholder to Location and Sign In button title to Start.
    * (May 8 2025) Feature - Modified Location field to be case insensitive.
    * (May 8, 2025) Feature - Mapped provided Locations to Model IDs.
    * (May 8 2025) Feature - Captures *.zip name mapped to Location Name or ModelID if name not available.
    * (May 8 2025) Bugfix - Issue when settings are not properly maintained while switching between viewer and captures.
    * (May 8 2025) Bugfix - On mobile devices, the Landing page is not vertically centred and allows scrolling even if the whole content fits the screen.
    * Feature - Tool selections, camera, and target positions maintained when switching between the viewer and captures.
    * Feature - 'Enter' triggers clicking the Login button on the Password page.
    * Feature - Display loading animation when clicking on the Login button.
    * Feature - Show the 'No captures available' message and icon if no captures are found for the given modelId on the captures page.
    * Feature - URL parameter (defaultPosition=true) to set the default camera and target positions for the model.
    * Feature - Doublclick on captures scrollbar resets zoom to default setting. 
    * Feature - Captures download images in a zip archive.
    * Feature - Captures Select all functionality.
    * Feature - Captures Deselect all functionality.
    * Feature - Show pop-up modals confirming deletion and providing notifications when no captures are selected.
    * Feature - Capture star functionality by storing the state in DynamoDB.
    * Feature - Captures delete by deleting captures from S3.
    * Feature - Configure app.cinesplat.com to point to the CloudFront distribution.
    * Bugfix -  Issue with values not being updated when switching between tools.
    * Bugfix - In/Out control with keypad (Shift + Up/Shift + Down ) not working.
    * Bugfix - Translate/Roll sometimes loses settings.
    * Bugfix - Maintain the image size irrespective of the number of images shown on the captures page.
    * Bugfix - Reset translation and roll on focal point change to avoid target position misalignment.

* v1.0.2 - Mar 2 2025
    * Changed tool sequence.
    * New page - captures.
    * Highlighted lens, sensor size and aspect values.
    * Hover on fullcreen and captures icons changes color.
    * Camera far plane increased to 10000.
    * Adjusted camera controls sensitivity and animation.
    * Swapped Roll with Dolly.
    * Camera and target position maintained returning to scene from captures section.
    * Fixed multiple Safari speciffic bugs.
    * Fixed issue with Orbit controls when mouving out of the canvas
    * Capture button - store images to S3
    * Dynamic Links from and to captures section
    * Maintain camera and target positions when navigate to captures section and back
    * Dynamically load captures from S3 based on modelId
    * Login router page
    * Moved upload section from root to /upload
    * New DynamoDB integration for login router page
    * Changed trsanslate labels to up/down, left/right, in/out

* v1.0.1 - Jan 16 2025
    * Users can now use scroll for changing the values.
    * Doubleclick on scrollbar resets the value.
    * Added Fullscreen button (f).
    * Added 75% shading for aspect ratio.
    * Maintain the same camera position on viewport resize.
    * Fixed X and Y rotation - Pan and Tilt.
    * Fixed Dolly on IOS fullscreen. Now it works with holding Shift + Arrow Up and Arrow Down.
    * Resolved canvas overscroll with arrows for IOS.
