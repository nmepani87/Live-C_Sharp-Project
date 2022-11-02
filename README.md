<h1>Live Project (C#)</h1>

<h3>Introduction</h3>

<p>During the last two weeks of my bootcamp with <a href="https://www.learncodinganywhere.com/">The Tech Academy</a>, I was part of a team that worked on an ongoing project, which was a C# MVC Web Application. The purpose of the web app was to create an app, for a theatre company, which made it easier to save and show various areas of it for public viewing and be easy to maintain as shows would change.</p>

<h3>Main Index</h3>

<p>For my first story, I was asked to create the main index that had certain requirements for the layout. A UX designer had provided a template of how it should look too and so this task tested my CSS and Bootstrap knowledge.
  
  <li><a href="./Media/Code/Home-Index-cshtml/">Home Index Code</li>
  <li><a href="./Media/Code/Home-Index-css/">Home Index CSS Code</li><br>
    
![Home-Index](https://user-images.githubusercontent.com/108291876/199376147-47689325-13dc-4f01-b296-744542e40a18.gif)

<h3>Production Model</h3>

<p>The app has 3 areas and our team was given the Production area to work on. On my second story I was tasked to build the database for where the production show details would go. The project used a Code-First approach therefore I was easily able to enter the required properties into a model, who's class was derived from DbContext, and then scaffold a MVC controller with using Entity Framework.</p>

  <li><a href="./Media/Code/Model-Production.png">Model Code</li>

<h3>Production Index</h3>

<p>Within the Production area, a sub-section also call Production was set up. It was felt as more plays would be added, the list may grow fairly long. To help the user a search bar was added so they could query the db entries against the Title property and get a list back accordingly. Also another Paging Function added was the sort by Title. By clicking on the given button, the list of entries was be alphabetised in a decending order.</p>

  <li><a href="./Media/Code/Controller-Production/">Production Controller Index Page</li>
  <li><a href="./Media/Code/Production-Index-View/">Production Index View Page</li>
  
    
    
<h3>CRUD Functions/h3>
  
<h3>Create/h3>

<p>Once the views had been scaffolded. The next part was styling the CRUD pages so they would look similar to the website. This was aided by given certain colours to work with and being able to work off the style of existing items also. This is where a team member and I came up with the idea to even keep the sub-sections styling the same for where each of us were working on. After agreeing on layout in a team meeting I changed our given area CSS page so classes that could be used across all our pages were given a certain naming convention and rid of classes doing the same styling.</p>

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
