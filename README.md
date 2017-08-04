# SmartFocus email template

This is the main email template for our campaign and 365 emails that are sent out via SmartFocus.
Preview: https://smartfocus-email-template.netlify.com/


## How to use the template:

- Go to: https://smartfocus-email-template.netlify.com/
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
However, you'd always have the FOOTER row as last row and you'd normally begin with the PRE-HEADER, LOGO and NAVIGATION rows.

#### Where to copy and previewing:
- open up your favourite text editor (just open up notepad if you're on a Windows machine)
- copy the template as described above
- save the file as an html file (`nameofmyemail.html`)
- open this file in your browser to preview what it looks like.
- copy the markup from your html file into the message in Smartfocus. 

Note that SmartFocus' placeholders for Links ([EMV LINK]13[/ EMV LINK]) won't work when previewing in the browser, but they can be tested by sending yourself a test email through SmartFocus.

#### Images:
Images should be uploaded to the `email-assets.comicrelief.com` S3 bucket inside the `2017` folder.
(towards the end of 2018 the email assets outside the 2017 folder will be deleted in order to clean up the bucket). 
Inside the 2017 folder the images can be placed inside any of the folders the image belongs to. By right clicking on the image file the source link for the image can be retrieved.
