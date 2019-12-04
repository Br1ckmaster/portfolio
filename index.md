<style>
.topnav
{
	overflow: hidden;
	background-color: #333;
}

.topnav a
{
	float: left;
	color: #f2f2f2;
	text-align: center;
	padding: 14px 16px;
	text-decoration: none;
	font-size: 17px;
}

.topnav a:hover 
{
  background-color: #ddd;
  color: black;
}

.topnav a.active 
{
  background-color: #bbbfbc;
  color: white;
}
</style>

<div class="topnav">
<a class="active" href="https://stevencoombe.github.io/Portfolio/">Home</a>
<a href="pages/catburglar.html">Projects/Games</a>
</div>

<body>
<div class="About Me">
<h2>About Me!</h2>
<p>Hello! I am a games programmer who has been programming for over 4 years now. It all started off learning HTML/CSS & JavaScript on Codecademy. From there on I have been constantly learning & improving my programming skills.</p>
</div>

<div class="Social Media">
<h2>Social Media!</h2>
<p>Here are links to my social media accounts:</p>
<ul>
	<li>View my <a href ="https://www.linkedin.com/in/steven-coombe/" title="Linkedin Profile">Linkedin profile</a>.</li>
	<li>View my <a href ="https://github.com/stevencoombe" title="GitHub Profile">GitHub profile</a>.</li>
</ul>
</div>

<div class="Contact Me">
<h2>Contact Me!</h2>
<p> Fill out the email form below, and I will get back to you as soon as possible. </p>
<form action="https://formspree.io/myyzpnvq" method="POST">
<label>Your Name:</label><br>
<input type="text" name="name" required><br>
<label>Your Email Address:</label><br>
<input type="email" name="_replyto" required><br>
<label>Your Message:</label><br>
<textarea name="message" rows="10" cols="50"></textarea><br>
<button>Submit</button><br>

</form>
</div>
</body>