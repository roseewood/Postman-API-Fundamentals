<div align="center">
<h1>What are APIs?<h1>
</div>

<h1 align="center">Application Programming Interfaces</h1>

<p>An <b>Application Programming Interface (API)</b> is a <u>contract that allows code to talk to other code</u>. APIs are the building blocks of modern software because they allow for sharing of resources and services across applications, organizations, and devices.</p>

<br>

<p>Have you ever made a payment on a website? Checked the weather on a mobile app? Listened to Spotify on both your desktop and your phone? Used Google Maps inside another app? Whether you know it or not, you are using APIs every day. Even this lesson you are reading is brought to you by an API!</p>

<br>

<h2>Why are APIs important?</h2>
<ol>
<li>APIs help developers <b>integrate exciting features</b> and <b>build automation</b> without reinventing the wheel
<p><i>ex: using a Weather API instead of launching your weather balloons</i></p></li>
<li>APIs allow enterprises to <b>open up their product for faster innovation</b>
<p><i>ex: apps that interact with Twitter or Meta APIs by posting on your behalf or reading tweets</i></p></li>
<li>APIs can <b>be products themselves</b>
<p><i>ex: Software as a Service (SaaS) products like Stripe's payment APIs or Twilio's text messaging and email APIs</i></p></li>
</ol>

<br>

<h2>Who works with APIs?</h2>
<p><b>APIs are not just for developers.</b> According to Postman's latest State of the API Report, almost half of the survey respondents identified as holding non-developer roles, such as management, solutions architects, business and data analysts, educators and researchers. All these roles benefit from the standardized data access provided by APIs.</p>

<div align="center">
<img src="Images/worksurvey.png" alt="" width="" height="">
</div>

<p><b>API use is not limited to the tech and IT industries.</b> Survey responses in the same report show that while tech, business, IT, and banking sectors represent the bulk of API use, any industry can benefit from the convenience provided by APIs. </p>

<div align="center">
<img src="Images/nolimitationsurvery.png" alt="" width="" height="">
</div>

<br>

<h2>Who benefits from APIs?</h2>
<p>Ultimately, <b>everyone benefits from APIs</b> either directly or indirectly because APIs make processes more efficient and connect the services we love and rely on.</p>

<br><br>

<h1 align="center">APIs - A Digital Restaurant</h1>
<p>You can think of APIs as being like a waiter at a restaurant, serving as a go-between for the customer and the kitchen. </p>

<div align="center">
<img src="Images/digital restaurant.png" width="500px" height="350px">
</div>

<p>A customer who wants soup doesn't go into the kitchen to cook. They don't even have to know how to make soup! They only have to know <i>how to ask the waiter for soup, expecting the waiter to bring back soup</i>.</p>
<br>
<p>APIs work the same way, but there are different names for the players involved. Instead of soup, the requester might ask for data or execution of a service.  </p>

<table>
<tr>
<th>Networking term</th>
<th>Description</th>
<th>Restaurant analogy</th>
</tr>
<tr>
<td>Client</td>
<td><i>The requester. Ex: browser, web app, mobile app</i></td>
<td>Customer</td>
<tr>
<tr>
<td>API</td>
<td><i>Simplified interface for interacting with the backend</i></td>
<td>Waiter</td>
</tr>
<tr>
<td>Server</td>
<td><i>The backend where the processing happens</i></td>
<td>Kitchen</td>
<tr>
</table>

<br><br>

<h1 align="center">Types of APIs</h1>

<h2>Medium</h2>
<p>While this course will focus on Web APIs, it is important to know that "API" can apply to a broad range of interfaces.</p>

<ul>
<li><b>Hardware APIs</b></li>
<p>Interface for software to talk to hardware.<br><i>Example: How your phone's camera talks to the operating system. </i></p>

<br>

<li><b>Software Library APIs</b></li>
<p>Interface for directly consuming code from another code base.<br><i>Example: Using methods from a library you import into your application.</i></p>

<br>
<li><b>Web APIs</b></li>
<p>Interface for communicating across code bases over a network.<br><i>Example: Fetching current stock prices from a finance API over the internet.</i></p>
</ul>


<p>Multiple API types may be used to achieve a task. For example, uploading a photo to Instagram makes use of various APIs:</p>

<br>

<ol>
<li><u>Hardware API</u> for the app to talk to your camera</li><br>
<li><u>Software library API</u> for the image to be processed with filters</li><br>
<li><u>Web API</u> for sending your image to Instagram's servers so your friends can like it!</li>
</ol><br>

<h2>Architectures</h2>

<div align="center">
<img src="Images/architectures.png" width="500px" height="">
<p>There is more than one way to build and consume APIs. Some architecture types you may come across are:</p>
</div>

<ul>
<li>REST (Representational State Transfer)</li>
<li>GraphQL</li>
<li>WebSockets</li>
<li>webhooks</li>
<li>SOAP (Simple Object Access Protocol)</li>
<li>gRPC (Google Remote Procedure Call)</li>
<li>MQTT (MQ Telemetry Transport)</li>
</ul>

<h4>Rest APIs</h4>
<p>Some traits of REST APIs include not storing session state between requests, the ability to cache, and the ability to send and receive various data types. Still confused? Don't worry; we will learn hands-on very soon in this course!</p>

<h2>Access</h2>
<p>APIs also vary in the scope of who can access them.</p>

<ol>
<li><b>Public APIs (aka Open APIs)</b><br>Consumed by anyone who discovers the API
</li>
<li><b>Private APIs</b><br>Consumed only within an organization and not made public</li>
<li><b>Partner APIs</b><br>Consumed between one or more organizations that have an established relationship</li>
</ol>


