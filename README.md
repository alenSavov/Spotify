<h1>Spotify<h1/>

<h3>Using libraries like <strong>jQuery</strong>, <strong>Handlebars</strong> and <strong>Sammy</strong> . Implement a <strong>Web application</strong> (SPA) using HTML5, JavaScript, AJAX, REST and JSON with cloud-based backend (Kinvey). The app keeps <strong>users</strong> and <strong>songs</strong>. Users can <strong>register</strong>, <strong>login</strong>, <strong>logout</strong> , view all songs with all the <strong>songs</strong>. They will also be able to <strong>like</strong> the songs added <strong>by other users</strong> and should be able to <strong>listen and remove their own songs</strong>. There should also be a <strong>section </strong>where users can <strong>see only the songs they created</strong>.</h3>

![Webp net-gifmaker](https://user-images.githubusercontent.com/28908397/55901737-9dc98400-5bd2-11e9-95c2-1587ba00efbb.gif)


<h3>Getting started:</h3>
<p>In order to run the project you just need to add APP_KEY and APP_SECRET which is located in kinvey.json and after that run npm install.</p>

<h2>Set up Kinvey:</h2>
<p>Register at <strong>Kinvey.com</strong> and create an application to keep your data in the cloud.</p>
<p>Create a collection called <strong>songs</strong>. Each <strong>song</strong> has a <strong>title, artist, imageURL, likes (starting from 0) </strong>and <strong>listened (starting from 0)</strong>.</p>
<p>&nbsp;</p>
<p>&nbsp;</p>

![Kenvey1](https://user-images.githubusercontent.com/28908397/55902270-d158de00-5bd3-11e9-8607-26488582a385.JPG)

![Ca5pture](https://user-images.githubusercontent.com/28908397/55902490-44625480-5bd4-11e9-89fc-dcc456a61941.JPG)



<p>In order to be able to keep track of the <strong>likes and listened </strong>of each song, you need to <strong>allow all users to edit this collection</strong>. So go to the <strong>properties</strong> of the collection:</p>
<p>&nbsp;</p>
<p>&nbsp;</p>


![k2](https://user-images.githubusercontent.com/28908397/55902359-fe0cf580-5bd3-11e9-984e-8931635014e5.JPG)

<p>Then go to <strong>permissions</strong> and edit them to look like this:</p>
<p>&nbsp;</p>
<p>&nbsp;</p>


![Capture4](https://user-images.githubusercontent.com/28908397/55902429-1e3cb480-5bd4-11e9-98f8-ab1ae4a73bb4.JPG)
