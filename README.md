win8-notify
===========

A windows 8.x style notification system using CSS3 and JQuery.

Live Demo at [Win8-Notify Demonstration Page](http:.//code.ashrith.in/win8-notify)



<h2>Getting Started</h2>
<ol>
	<li>Get the source code from <a href="https://github.com/ashriths/win8-notify/archive/master.zip">here</a></li>
				<li>Include the CSS File in your page.
					<blockquote><pre>&lt;link rel="stylesheet" type="text/css" href="css/win8-notify.css"&gt;</pre></blockquote>
				</li>
				<li>Add the Shortcode with the required color to get the Notification. For Example to get a black Notification.
					<blockquote>
						<pre>&lt;div id="notification" class="notification black"&gt;
	&lt;div class="dark-back"&gt;&lt;/div&gt;
	&lt;div class="win8-notif-body"&gt;
		&lt;div class="mid"&gt;
			&lt;h3&gt;THis is the Notification heading&lt;/h3&gt;
			&lt;p&gt;This is the demo notifification descrption that can be long enough, Like your account has been succesfully hacked....&lt;/p&gt;
			&lt;button class="win8-notif-button"&gt;OK&lt;/button&gt;
			&lt;button class="win8-notif-button"&gt;CANCEL&lt;/button&gt;
		&lt;/div&gt;
	&lt;/div&gt;
&lt;/div&gt;</pre>
					</blockquote>
				</li>
				<li>You can also use Jquery or Natice Js to add this shortcode to the body when the Notifications is to be displayed.
						For example to show a green Notification.
						<blockquote>
							<pre>$('body').append(
	&lt;div id="notification" class="notification green"&gt;
		&lt;div class="dark-back"&gt;&lt;/div&gt;
		&lt;div class="win8-notif-body"&gt;
			&lt;div class="mid"&gt;
				&lt;h3&gt;THis is the Notification heading&lt;/h3&gt;
				&lt;p&gt;This is the demo notifification descrption that can be long enough, Like your account has been succesfully hacked....&lt;/p&gt;
				&lt;button class="win8-notif-button"&gt;OK&lt;/button&gt;
				&lt;button class="win8-notif-button"&gt;CANCEL&lt;/button&gt;
			&lt;/div&gt;
		&lt;/div&gt;
	&lt;/div&gt;
);</pre>
						</blockquote>
				</li>
			</ol>
