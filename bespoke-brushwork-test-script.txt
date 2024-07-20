Bespoke Brushwork Test Script

Header:

Action | Expectation | Pass/Fail

Click Logo from any page | User is brought back to home page | Pass
Hover over the three nav titles, Home, Gallery, Enquire, on large screen size | Nav item background should go white and font should turn black | Pass
Click Home Button from any page | User should be brought to the home page and Home should have a white underline in the nav | Pass
Click Gallery Button from any page | User should be brought to the Gallery page and Gallery should have a white underline in the nav | Pass
Click Enquire Button from any page | User should be brought to the Enquire page and Enquire should have a white underline in the nav | Pass
Use Dev Tools to make the screen smaller (mobile phone size) | The three Nav items should disappear into a burger-menu icon which can be clicked to open and drop down the three nav options on the phone screen, including the underline to show which screen the user is currently on | Pass


Footer:

Action | Expectation | Pass/Fail

Click Facebook logo from any page | User should be taken to the Facebook homepage via a new tab | Pass
Click X logo from any page | User should be taken to the X homepage via a new tab | Pass
Click Instagram logo from any page | User should be taken to the Instagram homepage via a new tab | Pass
Using Dev Tools alter the size of the viewport from largest screen to smallest screen | The social media icons should move closer to each other as the viewport shrinks but should always be evenly spaced | Pass


Index:

Action | Expectation | Pass/Fail

Observe Hero Image - Laptop Size or larger | Images should move in a slideshow, two images should be visible at a time and each image should scroll to the left by the width of one image and repeat until the reset when the cycle will restart again | Pass
Observe Hero Image - Tablet Size or smaller | Images should move in a slideshow, one image should be visible at a time and each image should scroll to the left by the width of the whole image and repeat without end | Pass
In dev tools observe the About Us section starting at the smallest viewport and gradually expand | When tablet size is reached, the two blocks of text should start to move in opposing directions, the top one to the left and the bottom one to the right | Pass
Click the in-text link 'gallery' in the About Us section | User should be directed to the gallery | Pass
Click the in-text link 'here' in the About Us section | User should be directed to the Enquire page | Pass
In dev tools observe the Some of our Services section starting at the smallest viewport and gradually expand | The writing in each square should always be visible and each block should align neatly by filling up the width of its container, else wrapping next to the other blocks of equal size to fill the respective row | Pass


Gallery:

Action | Expectation | Pass/Fail

In dev tools observe the Gallery section, starting at the smallest viewport and gradually expand | The images should, in masonry fashion, go from one column of images, to two, then two three, as the size of the viewport expands. They should always slot neatly together horizontally with no gaps where the images come into contact with each other | Pass


Form:

Action | Expectation | Pass/Fail

In dev tools observe the Enquire section, starting at the smallest viewport and gradually expand | The form should stay symmetrical, take up most of the width and height of the viewport, and remain evenly laid out regardless of the size of the viewport | Pass
Attempt to submit the form without inputting a First Name | A notification should appear saying 'Please fill out this field' and be pointed at the First Name box | Pass
Attempt to submit the form without inputting a Last Name but with everything else correctly filled in | A notification should appear saying 'Please fill out this field' and be pointed at the Last Name box | Pass
Attempt to submit the form without inputting an Email Address but with everything else correctly filled in | A notification should appear saying 'Please fill out this field' and be pointed at the Email Address box | Pass
Attempt to submit the form without inputting a Description but with everything else correctly filled in | A notification should appear saying 'Please fill out this field' and be pointed at the Description box | Pass
Attempt to submit the form without inputting an @ in the Email Address you have entered | A notification should appear saying 'Please include an @ in the email address' and be pointed at the Email Address box | Pass
Attempt to submit the form without putting anything before/after the @ symbol in the Email Address field | A notification should appear saying 'Please enter a part followed by '@''/'Please enter a part following '@'' and be pointed at the Email Address box
Fill out the form correctly and hit submit | The user should be directed to the confirmation page | Pass


Confirmation:

Action | Expectation | Pass/Fail

In dev tools observe the Confirmation section starting at the smallest viewport and gradually expand | The div containing the text should stay symmetrical, take up most of the width of the viewport, and remain evenly laid out regardless of the size of the viewport | Pass


Browsers: 

Action | Expectation | Pass/Fail

Action all of the above tests in Google Chrome | All tests should pass | Pass
Action all of the above tests in Microsoft Edge | All tests should pass | Pass
Action all of the above tests in Safari | All tests should pass | Pass

