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
 (e.g. `<!-- LOGO ROW --> `)
 - Within each row there are extra comments with instructions where to change colour, fonts etc. 
 (e.g. `<!-- row's background colour 2x -->`)

There are parts to an email that should always be copied in: 
- Everything above the comment  ROWS START HERE.
- Make sure the email starts with [EMV TEXTPART] and [EMV HTMLPART] tags (needed for SmartFocus).
- The FOOTER row and everything below.

Between the ROWS START HERE comment and the ROWS END HERE comment rows can be added in different order.
However, you'd always have the FOOTER row as last row and you'd normally begin with the PRE-HEADER, LOGO and NAVIGATION rows.
