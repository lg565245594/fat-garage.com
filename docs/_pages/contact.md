---
title: Contact
permalink: /contact.html
---


<!-- Mailchimp Subscribe Form -->
 {% if site.mailchimp-list %}
<div class="border p-5 bg-lightblue">
				<div class="row justify-content-between">
					<div class="col-md-6 mb-2 mb-md-0">
						<h5 class="font-weight-bold">Join Newsletter</h5>
						 Get the latest update of Fat Garage !
                         <p>
						 “The void I saw in the future was no longer a liability, but the greatest opportunity.”
						 </p>
					</div>
					<div class="col-md-6">
						<div class="row">
              <form action="{{site.mailchimp-list}}" method="post" name="mc-embedded-subscribe-form" class="wj-contact-form validate w-100" target="_blank" novalidate>
                <input type="email" placeholder="Enter e-mail address" name="EMAIL" class="required email form-control w-100" id="mce-EMAIL" autocomplete="on" required>
                <input type="text"  placeholder="Name"                 name="FNAME" class="required form-control w-100"       id="mce-FNAME" autocomplete="on" required>
                <button type="submit" value="Subscribe" name="subscribe" class="heart btn btn-success btn-block w-100 mt-2">Subscribe</button>
              </form>
						</div>
					</div>
				</div>
			</div>
            {% endif %}


