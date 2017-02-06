---
layout: page
title: About  
---

<p class="message">
  Hi. I'm Alex!  I'm a web developer that has a knack for front-end technologies. This is my home for all my projects, opinions, and insights into working in the world of the web. While you're here take a look at my <a href="projects/projects/"> Projects </a> and send me a message via the form below if you're interested in working with me! :) Thanks for stopping by. 
</p>

## Contact me! 

<div class="contact-form">
	<form action="https://formspree.io/alex.m.beaulieu@gmail.com" method="POST">
		<div class="row"> 
			<div class="column"> 
				<div class="contact-item">
					<p class="contact-label"> Name </p> 
					<input class="contact-field" type="text" onfocus="this.placeholder = ''" onblur="this.placeholder = 'John/Jane Doe'" name="name" placeholder="John/Jane Doe">
				</div>
				<div class="contact-item"> 
					<p class="contact-label"> Email </p> 
					<input class="contact-field" onfocus="this.placeholder = ''" onblur="this.placeholder = 'email@example.com'" type="email" name="email" placeholder="email@example.com">
				</div>
			</div> 
			<div class="column">
				<div class="contact-item"> 
					<p class="contact-label"> Message </p> 
					<textarea class="contact-message" type="textarea" name="message" onfocus="this.placeholder = ''" onblur="this.placeholder = 'What's on your mind?'" placeholder="What's on your mind?"></textarea> 
				</div>

				<div class="contact-item">
					<input id="submit-button" type="submit" value="Send"> 	 
				</div>
			</div>
	</form>
</div> 
