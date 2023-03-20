<h1> User Stories </h1>

<ol>

  <li>When I start up the application, I am given a choice between the following options:</li>
  	<ul>
  		<li>Begin a study session</li>
  		<li>Add a new question to the list</li>
	</ul>

  <li>If I choose to add a new question, I am asked to provide:</li>
  	<ul>
  		<li>The question text</li>
  		<li>A list of possible responses separated by semicolon</li>
  		<li>Designation of which response is correct</li>
		<li>A list of topic tags separated by semicolon</li>
	</ul>

  <li>If I choose to start a review session:</li>
  	<ul>
  		<li>The program presents a random question from the question list</li>
  		<li>I am provided the question text and all response options with labels</li>
  		<li>I am prompted to provide my response using the labels presented</li>
		<li>The program informs me of the correct answer</li>
		<li>I am prompted to choose whether to continue the session or quit</li>
	</ul>
	
</ol>

<h3>Technical requirements</h3>
<ul>
	<li>Store the list of created questions in a .csv file</li>
	<li>Load the previously created questions when the user initializes the application</li>
</ul>

<h3>Stretch goals</h3>
<ul>
	<li>The program allows you to limit the session to questions from a specific topic</li>
	<li>The program keeps track of your right and wrong answers to each question</li>
	<li>The program uses some logical system for giving you questions you've answered wrong</li>
	<li>The program allows you to load questions from different tests, tracked in different files</li>
	<li>The program tracks the average time you've taken to answer each specific question</li>
</ul>
