# Debugging Assignment Files


1. **index.html**
   - 
  1.1 <!-- <html> Added lang attribute to specify the language of the document -->
  <html lang="en">
   ##Warning: This document appears to be written in English. Consider adding lang="en" (or variant) to the html start tag.

# 1.2 <!-- <meta> Added charset attribute to specify character encoding -->
    <meta charset="UTF-8">

   1.3 <!-- <meta name="viewport" content="width=device-width, initial-scale=1.0" /> 
    Trailing slash on void elements has no effect and interacts badly with unquoted attribute values. -->
<meta name="viewport" content="width=device-width, initial-scale=1.0">

   1.4 <!-- <img src="easter-bunny-150-profile.png">  An img element must have an alt attribute, except under certain conditions-->
    <img src="easter-bunny-150-profile.png" alt="Profile picture of the Easter Bunny">
  
   1.5  <!-- <h3>Enough Content
            <p>You need enough content to thoroghly populate your page. The content should cause the page to be long
              enough to need to scroll. Keep copy/pasting content from Wikipedia until you have enough content to
              scroll. You will use this page later to embellish it with styles, color, formatting and layouts.</p> -->
        <h3>Enough Content</h3>
        <p>You need enough content to thoroughly populate your page. The content should cause the page to be long
          enough to need to scroll. Keep copy/pasting content from Wikipedia until you have enough content to
          scroll. You will use this page later to embellish it with styles, color, formatting, and layouts.</p>

2. **style.css**
   - Includes intentional errors related to CSS syntax, selectors, and properties.

  2.1  color: #B2;/* Invalid color value. Hex codes must have 3 or 6 characters. */

    /* Corrected color value below */
    color: #B2B2B2;

   2.2 /* font-size: 5 vw; Fixed: Removed the space between 5 and vw */
	font-size: 5vw; 

   2.3/* line-height: 1.35me; Fixed: Removed the invalid 'me' unit */
	 line-height: 1.35;

   2.4 /* color: #FE27122; Fixed: Removed the extra digit 2 */
	 color: #FE2712;
  
   2.5  /* 	text-decoration: all; Fixed: Changed 'all' to 'none' */
	text-decoration: none;


3. Layout CSS 

  /* Incorrectly nested rules for dt and dd */
  /* dt {
       font-weight: bold;
     }

     dd {
       padding: 0 10px;
     } */
}

/* Corrected dt and dd rules moved outside of aside */
dt {
  font-weight: bold;
}

dd {
  padding: 0 10px;
}

footer {
  padding: 1vw;
}
