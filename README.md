Download Link: https://assignmentchef.com/product/solved-web322-assignment-1-2
<br>
<h1>Introduction</h1>

Good<em>food</em> (https://www.makegoodfood.ca/) is a popular Canadian meal delivery company that creates recipes and delivers the ingredients straight to your door. You have been contracted as a full-stack programmer to develop your version, a competing product, of the Good<em>food</em> website.

You must not name your website Good<em>food</em> but instead come up with your own name and brand.  Also, your website <u>cannot</u> look the same as the Good<em>food</em> website however you can use the website (or similar meal delivery websites) to inspire the look and feel for your implementation.

The implementation of the website will be spanned over six assignments.  In this assignment, you will focus on building an Express server and the home page for your web application.  There is no database connectivity required at this time.

This assignment is worth 5% of your final grade.




<h1>Reminder about academic integrity</h1>




You must comply with <a href="https://www.senecacollege.ca/about/policies/academic-integrity-policy.html">Seneca College’s Academic Integrity Policy</a><a href="https://www.senecacollege.ca/about/policies/academic-integrity-policy.html">.</a>  Although you may interact and collaborate with others, this assignment must be worked on individually and you must submit your own work.

You are responsible to ensure that your solution, or any part of it, is not duplicated by another student.  If you choose to push your source code to a source control repository, such as GIT, ensure that you have made that repository private.

A suspected violation will be filed with the Academic Integrity Committee and may result in a grade of zero on this assignment or a failing grade in this course.




<h1>Technical Requirements</h1>




<ul>

 <li>All <strong><u>back-end</u></strong> functionality <strong><u>must</u></strong> be implemented using only <strong>js</strong> and <strong>Express</strong>, other frameworks/packages are not allowed for this assignment.</li>

 <li>You are <strong><u>not allowed to use</u></strong> any front-end CSS frameworks or JavaScript frameworks.</li>

</ul>







<h1>Objectives</h1>




<h2>Express web server set-up</h2>




Create an Express web server that listens to incoming HTTP requests <u>on port 8080</u>.  The logic for your web server must be placed in a file called “server.js”.  The top of the file must include the following header.




/************************************************************************************

<ul>

 <li>WEB322 – Project (Fall 2021)</li>

 <li>I declare that this assignment is my own work in accordance with Seneca Academic</li>

 <li>No part of this assignment has been copied manually or electronically from * any other source (including web sites) or distributed to other students.</li>

 <li>* Name:</li>

 <li>Student ID:</li>

 <li>Course/Section:</li>

</ul>

*

************************************************************************************/




Remember to fill in your name, student ID, and the course code (including the section code) in the header.  For example:




/************************************************************************************

<ul>

 <li>WEB322 – Project (Fall 2021)</li>

 <li>I declare that this assignment is my own work in accordance with Seneca Academic</li>

 <li>No part of this assignment has been copied manually or electronically from * any other source (including web sites) or distributed to other students.</li>

</ul>

*

<ul>

 <li>Name: Nick Romanidis</li>

 <li>Student ID: 990123456</li>

 <li>Course/Section: WEB322 ZAA</li>

</ul>

*

************************************************************************************/




<h2>Implement Route Handlers</h2>




Create <u>route handlers</u> that will direct users to specific pages when they navigate to the following routes:

<ul>

 <li>The “home” page</li>

 <li>An “on the menu” page, this page will list the current week’s meals.</li>

 <li>A registration page used to sign up to the service.</li>

 <li>A login page used to log in after a user has signed up.</li>

</ul>

<h2>The “Home” Page</h2>




You are required to build a well-designed home page that consists of the following sections:

<ul>

 <li><strong>Header: </strong>The header <strong><u>must</u></strong> contain a logo for your website.  The logo must be an image file and cannot be html markup.  Feel free to add links or other content.</li>

</ul>




<ul>

 <li><strong>Navigation Bar:</strong> The navigation bar can be placed within the header or defined as an entirely new area.  It <strong><u>must</u></strong> contain links that navigate visitors to the “on the menu” page, a sign-up page, the login page, and the home page (default route).</li>

</ul>







<ul>

 <li><strong>A Hero:</strong> This section <strong><u>must</u></strong> have a prominent image or video element that is placed at the top of your page, below the header and navigation section.  Here is an example:</li>

</ul>










<strong>                 </strong>

<ul>

 <li><strong>Content Section(s):</strong> These sections <strong><u>must</u></strong> use a combination of grids, words, headings, and images with the sole purpose of highlighting some selling features of the website, how it will work, and/or the services that it will provide.  Here is an example:</li>

 <li><strong>Top Meals:</strong> This section must display at least three (3) top meals.  In this assignment, the data for this section will not be pulled from a database, instead it will be hardcoded in the HTML file.  Each meal package must display an image, title, what is included, and a price.  Here is an example:</li>

</ul>










<strong>                 </strong>

<ul>

 <li><strong>Footer:</strong> This section must include footer menu items, social media links, and any other information you deem necessary.</li>

</ul>










<strong>Required:</strong> Your footer must contain a copyright statement that reads exactly as follows:




<h3>Copyright © Fall 2021, &lt;FirstName&gt; &lt;LastName&gt;, WEB322 &lt;SectionCode&gt;</h3>




Be sure to include your first and last name.  For example, your professor would show the following copyright statement:




<em>Copyright © Fall 2021, Nick Romanidis, WEB322 ZAA</em>




<h2>“On the Menu”, Registration, and Login Pages</h2>




You do not need to implement these pages for this assignment, but you must create and configure the appropriate routes.  Simply, <u>return a string with the page name</u> for the “On the Menu”, registration, and login pages.  Do not leave any “dead” routes.




<h2>Reminder</h2>




All back-end functionality <strong><u>must</u></strong> be implemented using <strong>Node.js</strong> and <strong>Express</strong> and your pages <strong><u>must</u></strong> be created with using only vanilla HTML, CSS and JavaScript.




<h1>Rubric</h1>




<table width="622">

 <tbody>

  <tr>

   <td width="231"><strong>Criteria</strong></td>

   <td width="131"><strong>Not  </strong><strong>Implemented (0) </strong>Little or no work done. Unacceptable attempt.</td>

   <td width="131"><strong>Partially  </strong><strong>Implemented (1) </strong>Work is minimally acceptable but is incomplete or needs significant modification.</td>

   <td width="131"><strong>Fully  </strong><strong>Implemented (2) </strong>Work is complete and done perfectly. </td>

  </tr>

  <tr>

   <td width="231">Home page.•       Header•       Navigation•       Hero Section•       Content Section•       Top Meals Section•       Footer</td>

   <td width="131"> </td>

   <td width="131"> </td>

   <td width="131"> </td>

  </tr>

  <tr>

   <td width="231">Express web server.•       A web server was created in a file named “server.js”. The file has the appropriate header at the top. •       The web server listens on port 8080.</td>

   <td width="131"><strong> </strong></td>

   <td width="131"><strong> </strong></td>

   <td width="131"><strong> </strong></td>

  </tr>

  <tr>

   <td width="231">Additional routes.•     Routes have been configured for the “On the Menu”, registration, and login pages.</td>

   <td width="131"> </td>

   <td width="131"> </td>

   <td width="131"> </td>

  </tr>

 </tbody>

</table>




<table width="623">

 <tbody>

  <tr>

   <td width="231">Home page look and feel.•       Page is polished.•       Used pleasing typography, color palettes, and imagery.•       Appropriate use of grids.</td>

   <td width="131"><strong>Poor (1)</strong></td>

   <td width="131"><strong>Average (3)</strong></td>

   <td width="131"><strong>Exceeds (6)</strong></td>

  </tr>

 </tbody>

</table>




<strong>Total:</strong> 24 Marks

<strong>Note:</strong> Half marks may be awarded.




<h1>Submitting your work</h1>




Make sure you submit your assignment <u>before the due date and time</u>.  It will take a few minutes to package up your project so make sure you give yourself a bit of time to submit the assignment.

<ol>

 <li>Locate the folder that holds your solution files.</li>

</ol>




<ol start="2">

 <li>Compress the copied folder into a zip file. <strong>You must use ZIP compression, <u>do not use 7z or</u> <u>other compression algorithms or your assignment will not be marked</u>.</strong></li>

</ol>




<ol start="3">

 <li>Login to My.Seneca.</li>

</ol>




<ol start="4">

 <li>Open the <strong>Web Programming Tools and Frameworks</strong> course area and click the <strong>Project</strong> link on the left-side navigator. Follow the link for this assignment.</li>

</ol>




<ol start="5">

 <li>Submit/upload your zip file. The page will accept <u>three</u> submissions so you may re-upload the project if you need to make changes.  Make sure you make all your changes before the due date.  Only the latest submission will be marked.</li>

</ol>


