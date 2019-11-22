## Peter McIntyre
Public web site home

I anticipate that home page content, shown in the white area, goes here.

<br>

### Possible changes

The main background looks a little grey. Change to white?  
Title "home" - change, and also the tagline.  

<br>

### default.html

The `_layouts/default.html` file has these content areas:

`<!-- HEADER -->`  
Top area, grey background, too tall by default. 

`<!-- MAIN CONTENT -->`  
Middle area, white background. 

`<!-- FOOTER -->`  
Bottom area, grey background. 

<br>

### assets / css / styles.scss

Comment out the import theme.  
Add in the import for the site theme.  

Use the Chrome dev tools inspector.  
Use its select tool, then select the UI.  
Look at the Styles list, and look for the rule.  
Test it by changing it in the Chrome inspector.  
Then add a new rule to the `styles.scss` file.  

<br>
