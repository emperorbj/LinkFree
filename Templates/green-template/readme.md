# Green-template

Made by [Bolaji](https://github.com/emperorbj)

<img src="screenshot.png" alt="alt text" width="auto">

## How to Use
### index.html
 1. **Title**
    This is the name that is given to the page.
	   ```
	   <title>Your Title Here</title>
	   ```
 2. **(Optional) Favicon** 
	To change the favicon, just replace the "favicon.ico" file. You can generate the .ico file in a website like [favicon.io](https://favicon.io/).
 3. **Image**
	 This is the user image that is shown. Make sure it is square and substitute the "src" property with its url. You can generate the url in a website like [imgur](https://imgur.com/).
	```
	<img  id="userPhoto"  src="https://i.imgur.com/t8ZX9um.jpg"  alt="User Photo">
	```
 4. **Username**
	Your Instagram username. Change the "href" property with its url and add substitute the text with your @.
	```
	<a  href="https://www.instagram.com/thesimpsons"  id="userName"></h3>@thesimpsons</a>
	```
 5. **Links**
 To add your clickable links just substitute, delete or copy the "a" tags inside the "links" div with your desired hyperlinks.
	```
	<div  id="links">

		<a  href="https://pt.wikipedia.org/wiki/Homer_Simpson"  target="_blank">Wikipedia</a>

		<a  href="https://foxplay.com/br/forme"  target="_blank">IMDB</a>

	</div>
	```