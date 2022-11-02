<h1>Live Project (C#)</h1>

<h2>Introduction</h2>

<p>During my two week internship at Prosper IT Consulting, I was part of a team that worked on an ongoing project, which was a C# MVC Web Application. The purpose of the web app was to create an app, for a theatre company, which made it easier to save and show various areas of it for public viewing and be easy to maintain as shows would change.</p>

<h2>Main Index</h2>

<p>For my first story, I was asked to create the main index that had certain requirements for the layout. A UX designer had provided a template of how it should look too and so this task tested my CSS and Bootstrap knowledge.
  
  <li><a href="./Media/Code/Home-Index-cshtml/">Home Index Code</li>
  <li><a href="./Media/Code/Home-Index-css/">Home Index CSS Code</li><br>
    
![Home-Index](https://user-images.githubusercontent.com/108291876/199376147-47689325-13dc-4f01-b296-744542e40a18.gif)

    
<h2>Production Model</h2>

<p>The app has 3 areas and our team was given the Production area to work on. On my second story I was tasked to build the database for where the production show details would go. The project used a Code-First approach therefore I was easily able to enter the required properties into a model, who's class was derived from DbContext, and then scaffold a MVC controller with using Entity Framework.</p>

  <li><a href="./Media/Code/Model-Production.png">Model Code</li>
    
<h2>Production Index</h2>
    
<p>Within the Production area, a sub-section also call Production was set up. It was felt as more plays would be added, the list may grow fairly long. To help the user a search bar was added so they could query the db entries against the Title property and get a list back accordingly. Also another Pagination Function added was to sort the list by Title. By clicking on the given button, the list of entries was be alphabetised in a decending order.</p>

  <li><a href="./Media/Code/Controller-Production/">Production Controller Index Code</li>
  <li><a href="./Media/Code/Production-Index-View/">Production Index Code</li>
  <li><a href="./Media/Website/Production-Index/">Production Website View</li>
  
<h2>CRUD Functions</h2>
  
<p>The next part was styling the CRUD pages so they would look similar to the website. This was aided by given certain colours to work with and being able to work off the style of existing items also. This is where a team member and I came up with the idea to even keep the sub-sections styling the same for where each of us were working on. After agreeing on layout in a team meeting I changed our given area CSS page so classes that could be used across all our pages were given a certain naming convention and rid of classes doing the same styling. This would help in needing to create less classes through-out the Production section.</p>

  <li><a href="./Media/Code/Production-Create-View">Production Create Code</li>
  <li><a href="./Media/Code/Production-Edit-View.png">Production Edit Code</li>
  <li><a href="./Media/Code/Production-All-css">Production CSS Code</li>
  <li><a href="./Media/Code/Production-Create-css.png">Production Create CSS Section</li><br>
    
  ![Production-IndexEditDelete-View](https://user-images.githubusercontent.com/108291876/199390097-49480af9-1274-40df-b90a-a014a991f350.gif)  
    
<h2>Details Modal</h2>
    
<p>A pop-up modal was wanted to show the details of the entry upon clicking on its card in the index page, rather than redirection onto a whole new page.This was achieved placing a section in the index cshtml page that would target the details placed in the contents of the modal within the details page. JavaScript was using to help achieve this.</p>

  <li><a href="./Media/Code/Production-Details-View">Production Details Code</li><br>

  ![Production-DetailsModal-View](https://user-images.githubusercontent.com/108291876/199390025-600bb8c2-3ecc-40d7-9689-bd37f84eb56a.gif)

<h2>Users</h2>

<p>In order to limit further down the line which users could create, edit and delete entries the need to create a user name/role, which would then be given admin usage facilities. I was tasked to create the model from this and populate the database with a single user, whom had been given a specific role/title. This would be a one-to-many relationship therefore the model was derived from another class rather than dbcontext as previous. In its Seed method it would query the required databases, via context class, and if that query wasn't met then the rest of the method would execute to populate the db with one user. </p>

  <li><a href="./Media/Code/Model-ProductionManager">Production Manager Model Code</li>
    
<h2>Other Skills Learnt</h2>
  
<p>This project has giving me the chance to learn some value skills such as:

  <li>Working within a team and communicating better to simplify areas for all</li>
  <li>Learn how to resolve merge conflicts</li>
  <li>Fixing front-end and back-end bugs through research or help from peers/supervisor</li>
  <li>Familiarising myself more with the .NET Framework</li>
