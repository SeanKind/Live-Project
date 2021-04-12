<h3> Introduction</h3>

<h5>For the last stretch of my time as a student at the tech academy, I worked on a live project that simulated a real world development scenario. The live projects are 2 week sprints working with various technologies, both front end and back end. The following is a step by step example of my thought process through one of my more intricate contributions. 
</h5>

<h3> Background context </h3>

  <h5> The project was an ASP.NET MVC website for a theatre company who wanted to update the look and functionality of their site. Users were able to view the productions and actors for each production, and admins were able to edit content on the site through an administrator login. My task was to create a method for checking if photos within the database were in use anywhere on the site, and display that information. Additionally, I was to add a way to update the photos with a final verification if the photos were used on the site. 
</h5>

<h3> I began by creating a ViewModel </h3>

<h5> I needed a way to store the information from my database query and to pass the information to the View. To do this, I created a ViewModel as shown below. <br/> 
<img alt="ViewModel" src="Screenshots/photodependenciesviewmodel.png"/> <br/>
  
</h5>








<img alt="test" src="/Screenshots/FindDependencies() Method code.png">
