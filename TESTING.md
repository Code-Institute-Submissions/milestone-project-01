# Testing 'The Studes' website

## Testing client stories from the UX section of README.md

1. "I'm a sculptor and need to create some pieces next week.
The Studes has a dirty area that's perfect for artists with all the equipment.
**I need to check if I can use it on a certain day next week**.” 
- This user will be an existing member of The Studes.
- The user takes 3 steps: _Home > Members > Enquiry form_ 
- The user can either go to the Members page through the navigation bar or the button within the homepage content
- The user is then able to fill in the form to match their requirements

2. "I’m a student at the craft school and live in a small shared flat so aren’t able to do much work at home.
I’d love a studio of my own but that would be quite expensive and I don’t want to spend that much just for a few evenings a week. 
**I’ve heard about The Studes so want to see if membership is affordable and if it's not too much, I want to join!**"
- This user is not currently a member of The Studes so may be unfamiliar with the site.
- The user takes 3 steps to the application form: _Home > Join Us > Apply_
- The user will be able to access the membership packages on the 'Join Us' page through 2 routes: through the navigation bar or the button positioned after the first paragraph
- The user can review the different membreship packages on the 'Join Us' page and easily make their way to the application page by clicking 1 of the 3 buttons on this page
- The application form can only be reached through the 'Join Us' page to ensure they review the membership types
- The application form requests only essential information (name, email, link to portfolio) with options for the specialist area

3. “I’ve heard about The Studes and just want to check it out.
I used to screen print when I was younger and am considering taking it up again but don’t have the facilities.
**I want to see how much it costs to be a member as I'm considering picking it up again?**”
- The user is not currently a member of The Studes and wants to review membership packages
- For this mission, the user takes 2 steps to the join us section to review membership packages
- The join us page is easily reached either through the navigation bar or the button underneath the first paragraph of text on the home page

4. “I’m a womenswear designer that uses The Studes for their big tables, sewing machines and to generally make a mess!
I’m working for a client who wants bespoke prints designed but I can’t do it myself.
**I need to see if there is anyone at The Studes who does print and would be interested in working with me on this collection**”
- The user is an existing member and needs to reach the collaboration / commission form
- The user will navigate through the following journey: _- Home > Members > Collaboration form_
- The Members page can be reached through the navigation bar or the button underneath the second paragraph on the homepage
- On the Members page, the user scrolls down to the 2nd form where they can fill in a brief for their commission
- When the user submits their brief a modal pops up confirming their brief has been received and outlining next steps

5. "Someone left their ‘The Studes’ bag with some materials in it at my coffee shop.
**I just need a phone number** so they can pick it up."
- The user needs to take 2 steps to get a phone number: _- Home > Contact_
- On the Contact page, the user can see the phone number
- The number can be pressed and automatically dialled from the users phone if they are viewing on mobile

## Manual (logical) testing of all elements and functionality on every page.

### Home page
1. Navigation bar:
- Check that the logo functions and takes the user back to the Home page when clicked on
- Check that the logo is responsive and changes size in different screen sizes
- Check that the navigation menu items condense into a 'hamburger' drop down menu when the screen reduces in size
- Check that the 'home' menu item in the navigation is bold while on the home page
- Check that the navigation bar stays at the top of the viewport while the user scrolls down to the bottom of the page

2. Footer bar:
- Check that when the email button is clicked that it opens a new page to send an email
- Check that the Instagram icon opens The Studes Instagram stories in a new window
- Check that the LinkedIn icon opens the LinkedIn home page in a new window
- Check that the elements don't distort in smaller screen sizes
- Check that the footer bar stays at the bottom of the page

3. Header panel:
- Check that the image doesn't repeat in smaller screen sizes
- Scroll down the page to check the background image is fixed
- Reduce screen size and scroll to check the background image doesn't repeat
- Check that the text is responsive and reduces in size in smaller screen sizes, but that the heading is always bigger than the sub-heading

4. Intro copy section:
- Check that the padding in the opening copy disappears in any screen smaller than a laptop
- Check that the 'Review Memberships' button takes the user to the 'join us' page
- Check that the first image sits below the introduction paragraph in a screen size smaller than a tablet
- Check that the second image is not visible on a screen size smaller than a tablet
- Check that the second block of copy sits beneath the image in a screen size smaller than a tablet
- Check that the button 'Go to members page' takes the user to the members page

5. Testimonials:
- Check that the row of images and text stretch to the edges of the screen when smaller than a laptop
- Check that the names are overlaid on the images when the screen is a tablet and larger, but disappear on mobile
- Check that the names appear underneath the captions on a mobile screen
- Check that the captions overlay the images on a mobile screen
- Check that the images stretch to the edges on a mobile screen

### Join Us page
1. Navigation bar:
- Repeat checks as above
- Check that 'join us' is bold while on this page

2. Footer bar:
- Repeat checks as above

3. Header panel:
- Repeat checks as above

4. Intro copy:
- Check that the image sits on the left in a laptop size screen but sits below the text in a screen tablet size or smaller
- Check that the text takes up half the row on a laptop sized screen but sits above the image when the screen reduces to tablet

5. Membership Options
- Check that the membership options in a large screen sit two per row along with one image per row on a large screen
- Check that the images disappear on a tablet and smaller sized screen
- Check that the membership backgrounds become coloured on a tablet and smaller sized screen
- Check that the membership options sit two per row on a tablet, but become stacked on mobile size 
- Check that the membership options have a white bar between them on mobile size
- Click the apply buttons to go to the application form page when clicked 

### Application form
1. Navigation bar:
- Repeat checks as above
- Check that 'join us' is bold while on this page

2. Footer bar:
- Repeat checks as above

3. Header panel:
- Repeat checks as above

4. MeMbership type selection:
- Select a membership type
- Check text doesn't distort in smaller screen sizes
- Click the 'Back to memberships' button to go back to the join us page
- Fill in information in each of the required areas
- Try to select more than one specialist area from the options and should only be able to select one
- Press 'Send application' button to see a modal show up confirming the application has been sent 
- The modal only shows up when the required information has been input by the user
**NOTE: The modal shows up even without the correct information being input. I have not been able to fix this yet.**
- Click the modal button 'close' to close the modal
- Click the modal button 'Back to homepage' to go back to the home page

### Members Page 
1. Navigation bar:
- Repeat checks as above
- Check that 'members' is bold while on this page

2. Footer bar:
- Repeat checks as above

3. Header panel:
- Repeat checks as above

4. Need to book something form:
- Check that the text sits above the form in a tablet size and smaller screen 
- Click the word 'here' to go back to the 'join us' page
- Input an email address
- Select one of the facilities in the drop down menu 
- Input a date into the form or select from the calendar
- Select from 1 of 4 time slots in the drop down menu
- Type text into the 'need it for longer?' box
- Click the 'Send booking request' button to check if a modal shows up
- The modal only shows up when the required information has been input by the user
**NOTE: The modal shows up even without the correct information being input. I have not been able to fix this yet.**
- Click the 'Close' button 
- Click the 'Back to homepage' button to go back to the home page

5. Collaboration / commission form:
- Check that the text sits above the form in a tablet size and smaller screen 
- Click the word 'here' to go back to the 'join us' page
- Input an email address
- Select a type of enquiry 
- Select a skill needed
- Type text into the 'Your brief' box
- Click the 'Submit your brief' button to check if a modal shows up
- The modal only shows up when the required information has been input by the user
**NOTE: The modal shows up even without the correct information being input. I have not been able to fix this yet.**
- Click the 'Close' button 
- Click the 'Back to homepage' button to go back to the home page

### Contact Page

1. Navigation bar:
- Repeat checks as above
- Check that 'contact' is bold while on this page

2. Footer bar:
- Repeat checks as above

3. Header panel:
- Repeat checks as above

4. Google map:
- Check that the map sits above the box containing contact information in a mobile screen
- Click the 'view larger map' to see the map in full screen

5. Contact information:
- Click the email address to open a new window to send an email
- Click on the featured phone number in a mobile screen to call through to the number
- Click on the word 'Instagram' to open a new window with The Studes Instagram stories
- Check that the background image turns into a solid pink background in a mobile screen