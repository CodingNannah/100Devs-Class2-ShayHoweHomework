Homework for #100Devs
Lesson 1 Building First Web Page:
	Create file called index.html
 	Save it in folder (recommended "styles-conference")
  	In file, add <!DOCTYPE html> structure (html, head, and body elements)
	In <head> add appropriate <meta> and <title> with text elements
 	In <body> add <h1> and <p> elements with text
  	Open the file in a browser
   	Add CSS:
	In folder, create folder called "assets"
  	In this folder, create folder called "stylesheets"
   	In this folder, create file called main.css
	Use Eric Meyer's reset to remove auto styling:
 		Navigate to https://meyerweb.com/eric/tools/css/reset/
   		Copy reset
	 	Paste at top of main.css file
   	Connect main.css to index.html:
		Open index.html
  		Add <link> element to <head> after title
		Within <link> add rel attribute with value stylesheet 
  		Include href attribute with path to main.css
	Save and Refresh or reopen browser to test html & css connection

Lesson 2 Getting to Know HTML (structure & content)
	In index.html file, add <header> element to include current <h1> & <p>
 	Add <h3> element as tagline for <h1> element
  	Add <section> element after <header> element with an <h2> and a <p>
   	Add new <section> below 
	For each of following, within separate <section>s:
		Create Speakers, Schedule, Venue (future pages)
  		Include <h5> (titles), <h3> (description), and <p> (blurb) elements
	Add <footer> element 
 	Add copyright within <footer> using <small> and &copy;
	Create Multiple Pages:
 	Link <h1> to index.html page
  	Add navigation menu:
   		Within <header>, create <nav>
	 	Create links for each of the following:
   			index.html as Home
	  		speakers.html as Speakers
	 		schedule.html as Schedule
			venue.html as Venue
   			register.html as Register
	Copy & paste the same navigation menu to <footer>
   	Copy & paste the register link below <p> within introductory <section>
	Add links to all labels in links <section>s:
 		Wrap <h3> & <h5> elements in anchor
   		Use proper href for each link
	 Within folder with the file index.html add the following:
  		speakers.html, schedule.html, venue.html, register.html
		On each html page, copy and paste <header> and <footer> elements from index.html
     
Lesson 3 Getting to Know CSS
	learning session only - no html nor css tasks

Added README.md and info for Lessons up through Lesson 4:
Lesson 4 Opening the Box Model
	NOTE: Developer Tools for browsers introduced here
 	Adjust box size to use border-box:
  		In main.css below reset, add comment Grid for the layout
		Using universal selector & universal before & after pseudo-elements, change box-sizing to border-box
  	Below universal selector rule set, create a container class:
   		Set width to 960 pixels
	 	Set left & right padding to 30 pixels
   		Set top and bottom margins to 0 pixels
	 	Set left & right margins to auto
   In html, apply the container class throughout <header> & <footer> on each page
   In index.html, add container class to each <section>
   Wrap all <h1> elements on each page with <section> element with container class
   Save & Open browser to verify that all content on each page is centered
   Create vertical spacing between elements:
   		In css, give h1, h3, h4, h5 & p bottom margin of 22 pixels
   In the top <section> of the homepage, place a button below the header
   Add the classes of btn and btn-alt to the anchor in this section
   In css, add btn class w 5 pixel border-radius, inline-block display, & margin of 0
   In css, add btn-alt class w1-pizel, solid, gray border 
   Add padding to the btn-alt class: 10 pixels on top & bottom and 30 pixels on left & right
   Add padding to the <section> that hs the <a>:
   		Add classes "hero container" to <section>
	 	In css, use hero to apply following padding in pixels: t=22, r=80, b=66, l=80   
  	
	
     
