<h1>Live Project (C#)</h1>

<h3>Introduction</h3>

<p>During the last two weeks of my bootcamp with <a href="https://www.learncodinganywhere.com/">The Tech Academy</a>, I was part of a team that worked on an ongoing project, which was a C# MVC Web Application. The purpose of the web app was to create an app, for a theatre company, which made it easier to save and show various areas of it for public viewing and be easy to maintain as shows would change.</p>

<h3>Main Index</h3>

<p>For my first story, I was asked to create the main index that had certain requirements for the layout. A UX designer had provided a template of how it should look too and so this task tested my CSS and Bootstrap knowledge.
  
  <li><a href="./Media/Code/Home-Index-cshtml/">Home Index Code</li>
  <li><a href="./Media/Code/Home-Index-css/">Home Index CSS Code</li>
    
    

<h3>Model</h3>

<p>The app has 3 areas and our team was given the Production area to work on. On my second story I was tasked to build the database for where the production show details would go. The project used a Code-First approach therefore I was easily able to enter the required properties into a model, who's class was derived from DbContext, and then scaffold a MVC controller with using Entity Framework.</p>

  <li><a href="./Media/Code/Model-Production.png">Production Model Code</li>

 
<p>The above image shows the code that I created that allows a user to be able to input an entry into the database and saves it. The model sections shows the fields, the types they are given and limitations as to what is allow to be entered. Through the forms I was able to use widgets for certain fields, the placeholder being an important one to show the user how to enter the time and date the correct way to allow the form to be valid. I've also shown the use the ModelForm and through the meta class how I renamed a field as needed.</p>
  
![Create](https://user-images.githubusercontent.com/108291876/195746518-3a7f188a-1a71-4a7b-bdd8-62592aa34fff.gif)

<h3>Read</h3>

<li><a href="./Media/Model_views2.png">Read Code</li><br>

<p>Through the creation of the two functions shown, the user it able to view a page that contain a list of all the entries added to the SQLite database and, if wanted, by clicking on an individual entry, via the use of a primary key, they can view all the details of that specific entry.</p>

<h3>Update/Delete</h3>

<li><a href="./Media/Model_update_delete.png">Update/Delete Code</li><br>

<p>Shown in the code is how a user, once on a specific entry, can choose to either delete or update that entry. Embedded into it, with the use of JavaScript, is a pop up message that shows to the user the requested action was successful.</p>

![DeleteFunction](https://user-images.githubusercontent.com/108291876/195746873-a04eeeae-99ae-4983-a5d4-69a2a0e67fae.gif)

<h3>Web Scrapping/API</h3>
  
<li><a href="./Media/API_BS_01.png">API Code</li>
<li><a href="./Media/API_Page.png">API Page Template Code</li>
<li><a href="./Media/API_BS_02.png">Web Scrapping Code</li><br>

<p>Through the use of an API I was able to provide a fast way for the user to know the latest currency exchange rates for the GBP. This was done by parsing the API information through JSON and retrieved only certain information as wanted. Each currency in the html page was easily seperated by using block tags to show each individual from the dictionary.
By using web scrapping, I was easily able to render a page from another by only targetting a specific tag in its html code. Then due to the originally page not wrapping certain information within certain div tags, I took the ones needed by using their index point and putting that into a dictionary. The dictionary is then show in a page another with some other text I put in.</p>

<a href="./Media/API.png">API View</a>
<a href="./Media/BS.gif">Web Scrapping View</a>
  
<h3>Other Skills Learnt</h3>
  
<p>This project has giving me the chance to learn some value skills such as:

<li>Working within a team a complete tasks given efficiently
<li>Utilizing Azure DevOps for:</li>
  <ul><li>Organizing active and completed user stories</li>
  <li>Creating push and pull requests to merge with the master branch</li>
  <li>Creating working branches for version control</li></ul>
<li>Fixing bugs through research or help from peers</li>
<li>Familiarising myself more with the Django Framework</li>
