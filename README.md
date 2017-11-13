# SmartFocus email template

This is the main email template for our campaign and 365 emails that are sent out via SmartFocus.

Preview: https://smartfocus-email-template.netlify.com/

Sport Relief template:
https://smartfocus-email-template.netlify.com/sr18.html

Sport Relief template with frequently used rows already there:
https://smartfocus-email-template.netlify.com/sr18-start.html


## How to use the template:

- Go to: https://smartfocus-email-template.netlify.com/sr18.html
- Right-click with your mouse and select something along the lines of "view page source"
- A new tab / window /pop-up will be opened with the template's markup.

### Copying the markup:

The email template consists of rows that can be used in our emails. 

 - Each row is surrounded by comments in capitals denoting the start and the end of the row. 
  (`<!-- LOGO ROW --> `)
 - Within each row there are extra comments with instructions where to change colour, fonts etc. 
  (`<!-- row's background colour 2x -->`)


There are parts to an email that should always be copied in: 
- Everything above the comment  ROWS START HERE.
- Make sure the email starts with [EMV TEXTPART] and [EMV HTMLPART] tags (needed for SmartFocus).
- The FOOTER row and everything below.

Between the ROWS START HERE comment and the ROWS END HERE comment rows can be added in different order.
However, you'd always have the FOOTER row as last row and you'd normally begin with the PRE-HEADER and LOGO rows.

#### Where to copy and previewing:
- open up your favourite text editor (just open up notepad if you're on a Windows machine)
- copy the template as described above
- save the file as an html file (`nameofmyemail.html`)
- open this file in your browser to preview what it looks like.
- copy the markup from your html file into the message in Smartfocus. 

Note that SmartFocus' placeholders for Links ([EMV LINK]13[/ EMV LINK]) won't work when previewing in the browser, but they can be tested by sending yourself a test email through SmartFocus.

#### Images:
Sizes for sr18:
- Feature row: 570px wide and should have the bar cut out at the bottom. If the image is a gif the bar at the bottom should be made the colour of the row it's used in. If it's not a gif then make it a png and make the bar transparent.
The height of the bar is 25px and it should be 520px wide, leaving 25px on each side of the bar (based on an image width of 570px).
The height of the image is automatically calculated according to the images' aspect ratio.
- Small rows : should be square and be 275px by 275px.
- Quicklinks row: 129px wide. All images should have the same height.
- Resources 2 column rows: 275px wide. All images should have the same height.
- Resources 3 column row: 176px wide. All images should have the same height.
- Questionnaire row: 176px wide. All images should have the same height.
- Icon row:  176px wide. All images should have the same height.
- 2x2 Resources row: Square images. 275px by 275px.

Resrouces 3 column row, icon row and questionnaire rows ideally have square images.

Images should be uploaded to the `email-assets.comicrelief.com` S3 bucket inside the `2017` folder.
(towards the end of 2018 the email assets outside the 2017 folder will be deleted in order to clean up the bucket). 
Inside the 2017 folder the images can be placed inside any of the folders the image belongs to. By right clicking on the image file the source link for the image can be retrieved.
