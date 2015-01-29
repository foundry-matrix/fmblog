---
layout: page
title: Contact
permalink: /contact/
---

<script type="text/javascript">

var center;
function calculateCenter() {
  center = map.getCenter();
}
google.maps.event.addDomListener(map, 'idle', function() {
  calculateCenter();
});
google.maps.event.addDomListener(window, 'resize', function() {
  map.setCenter(center);
});

</script>


<div class ="col-lg-12 col-sm-12">
	<div class="container-fluid">
		<div class="google-maps">
		<iframe		  
		  width="600"
		  height="450"
		  frameborder="0" style="border:0"
		  src="https://www.google.com/maps/embed/v1/place?key=AIzaSyDmOyKpQ4tgIemHFTepmzEFSsgDGP1Rwxs
		    &zoom=16&q=14+Palmers+Rd,+London+E2+0SY,+Storbritannia">

		</iframe>
		</div>
	</div>
</div>

<div class="contact-form col-xs-12 col-md-12">
	<div class="container-fluid">
		<form action="https://formspree.io/gaj.aubert@gmail.com">
			<div class="form-group">
				<label for="form-name-input">Name</label>
				<input type="text" class="form-control" id="form-name-input" placeholder="Your Name">
			</div>
			<div class="form-group">
				<label for="form-email-input">Email</label>
				<input type="email" class="form-control" id="form-email-input" placeholder=" Your Email Address">
			</div>
			<div class="form-group">
				<label for="form-text-input">Please write your message here </label>
				<textarea id="textarea" class="form-control" name="textarea" rows="3"></textarea>
			</div>
			<button type="submit" class="btn btn-default">Send</button>

		</form>
	</div>
</div>



