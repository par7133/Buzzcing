<p align="center">
    <a href="https://buzzcing.5mode-foss.eu">
        <img src="./Public/static/res/AFlogo.png" width="188" title="Buzzcing" alt="Buzzcing">
    </a>
</p>

# Buzzcing

Hello and welcome to Buzzcing!<br>
	  
Buzzcing is a light, simple, software on premise to build and own your music blog.<br>
	   
Buzzcing is released under GPLv3 license, it is supplied AS-IS and we do not take any responsibility for its misusage.<br>
	   
First step, use the password box and salt fields to create the hash to insert in the config file. Remember to manually set there also the salt value.<br>
	   
As you are going to run Buzzcing in the PHP process context, using a limited web server or phpfpm user, you must follow some simple directives for an optimal first setup:<br>

<ol>
<li>Check the write permissions of your "data" folder in your web app Private path; and set its path in the config file.</li>
<li>Set the default Locale.</li>
<li>Set FILE_MAX_SIZE (remember that some PHP settings could limit the upload behaviour of Buzzcing too)</li>
<li>Set BLOG_MAX_POSTS to limit the number of visible posts in the blog.</li>
<li>Set PAGINATION true or false to give more public access to your data.</li>
</ol> 

Song file nomenclature: "Company_Name~Listing Title.mp3"

You can access your avatar by http://yourdomain.com/<your_avatar>. Login with the password for the admin view. Drag-n-drop all your resources in the browser window.<br>

For any need of software additions, plugins and improvements please write to <a href="mailto:info@5mode.com">info@5mode.com</a>  

To help please donate by clicking <a href="https://gaox.io/l/dona1">https://gaox.io/l/dona1</a> and filling the form.  

### Public view:

![Buzzcing in action #1](/Public/static/res/screenshot1.png)<br>

### Admin view:

![Buzzcing in action #2](/Public/static/res/screenshot2.png)<br>

Feedback: <a href="mailto:code@gaox.io" style="color:#e6d236;">code@gaox.io</a>

