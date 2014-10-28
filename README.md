**this awesome app gets your news feed in very plane retro optic!**

<h1>How to install the project</h1>

<ol>
<li>Install gradle if not already done: Eclipse -> Help -> Install new Software...</li>
<li>(Eclipse 3.7 - 4.2) Work with: Gradle - http://dist.springsource.com/release/TOOLS/update/e3.7/</li>
<li>Choose: Core - Eclipse Integration for Gradle</li>
<li>Click Finish</li>
<li>Import: Eclipse -> File -> Import...</li>
<li>Choose: Gradle -> Gradle Project</li>
<li>Click Browse... (to Project directory)</li>
<li>Click Build Model</li>
<li>Choose: FacebookWrapper</li>
<li>Click Finish</li>
</ol>

Eventually you should clean and refresh the imported project.

<h1>How to get the appId and appSecret</h1>
<ol>
<li>Get a facebook account</li>
<li>Get a facebook developer account</li>
<li>Create new app</li>
<li>Insert app domains: localhost</li> 
<li>Add new platform: website</li>
<li>Site-url: http://localhost:8080/connect/facebook</li>
<li>Mobile-site-url: http://localhost:8080/connect/facebook</li>
<li>Save</li>
</ol>

<h1>How to setup the project</h1>
<ol>
<li>Place your appId and appSecret in /src/main/ressources/application.properties</li>
<li>Start the application main function in /src/main/java/hello/Application.java</li>
<li>Open your browser and visit: http://localhost:8080/connect/facebook</li>
<li>Connect to facebook</li>
<li>Get your fabulous news feed!</li>
</ol>
