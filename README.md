Alarm Clock Application
This project is a simple web-based alarm clock. It displays the current time and allows users to set an alarm. When the set time is reached, an alarm sound plays. The application is built using HTML, CSS, and JavaScript.


Files

index.html: The HTML structure of the alarm clock.
style.css: The CSS styling for the alarm clock.
script.js: The JavaScript functionality for the alarm clock.
clock.svg: The image of the clock displayed on the webpage.
ringtone.mp3: The sound file that plays when the alarm goes off.

HTML Structure (index.html)

The HTML file includes a div with the class wrapper that contains an image of a clock, the current time, dropdown menus for setting the alarm, and a button to set the alarm.
The dropdown menus allow the user to select the hour, minute, and AM/PM for the alarm.
The h1 element displays the current time.
The button element allows the user to set or clear the alarm.

CSS Styling (style.css)

The CSS file includes styles for the overall layout, the wrapper, the dropdown menus, and the button.
The page uses the 'Poppins' font from Google Fonts.
The background color of the body is set to #4A98F7.
The wrapper has a white background, padding, rounded corners, and a shadow effect.

JavaScript Functionality (script.js)

The JavaScript file selects the required HTML elements using querySelector.
The script initializes the variables for the alarm time and the alarm state.
It populates the dropdown menus for hours, minutes, and AM/PM.
A setInterval function updates the current time every second.
If the current time matches the set alarm time, the alarm sound plays.
The setAlarm function sets or clears the alarm based on the user's interaction with the button.
Event listeners are added to handle the alarm setting and clearing.

Setup and Usage

HTML Setup: The HTML file includes a reference to style.css for styling and script.js for functionality.
CSS Styling: The style.css file contains styles for the layout and appearance of the alarm clock.
JavaScript Logic: The script.js file contains the logic for displaying the current time, setting the alarm, and playing the alarm sound.
Alarm Sound: The alarm sound is stored in the ringtone.mp3 file and is played using the Audio API in JavaScript.
