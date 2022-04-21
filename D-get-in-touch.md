---
layout: page
title: I would like to get in touch
description: or contribute to this project
image: assets/images/X.jpg
nav-menu: true
permalink: /contact/
---

<section id="one">
	<div class="inner">
		<header class="major">
			<h1>Get in touch!</h1>
			<h2>Either fill out the contact form below or submit an issue in our new <strong>GitLab repository</strong></h2>
		</header>
		
<section id="contact">
	<div class="inner">
		<section>
			<form action="https://formspree.io/{{ site.email }}" method="POST">
				<div class="field half first">
					<label for="name">Name</label>
					<input type="text" name="name" id="name" />
				</div>
				<div class="field half">
					<label for="email">Email</label>
					<input type="text" name="_replyto" id="email" />
				</div>
				<div class="field">
					<label for="message">Message</label>
					<textarea name="message" id="message" rows="6"></textarea>
				</div>
				<ul class="actions">
					<li><input type="submit" value="Send Message" class="special" /></li>
					<li><input type="reset" value="Clear" /></li>
				</ul>
			</form>
		</section>
	</div>
</section>
