<br>
<p align="center">
<a href="https://www.insidesherpa.com/virtual-internships/prototype/R5iK7HMxJGBgaSbvk/Technology%20Virtual%20Experience" target="_blank">
<img src="https://insidesherpa-assets.s3-ap-southeast-2.amazonaws.com/icons/jpmorgan/github+repo+images/jpm+gitub+.png"></a>
</p>

<p align="center"> 
	<b><a href="#task">Task Overview</a></b>
	|
	<b><a href="#installation">Installation Instructions</a></b>
	| 
	<b><a href="https://www.insidesherpa.com/modules/R5iK7HMxJGBgaSbvk/gtAhtcvke9AFCzqME" target="_blank">Link to Module 1</a></b>		
	| 
	<b><a href="https://www.insidesherpa.com/virtual-internships/prototype/R5iK7HMxJGBgaSbvk/Technology%20Virtual%20Experience">JP Morgan Chase & Co Software Engineering Virtual Experience</a></b>
</p>

<h1> Introduction</h1> 
<b> Experience Technology at JP Morgan Chase & Co</b>
<p>Try out what real work is like in the technology team at JP Morgan Chase & Co. Fast track to the tech team with your work.</p>

<h2 id="task"> Module 1 Task Overview </h2>
<p>Interface with a stock price data feed and set up your system for analysis of the data</p>
<p> <b>Aim:</b> We want to process the data feed of stock A and stock B’s price to enable us to analyse when trading for the stock should occur.</p>

<ol>
	<li>Please clone this repository to start the task</li>
	<li>Adjust the getRatio, getDataPoint and main functions</li>
	<li>Bonus: Pass all unit tests and add more to cover edge cases</li>
	<li>Upload a git patch file as the submission to this task</li>
	
</ol>

<h2 id="installation" >Set up / Installation</h2>

<p>In order to get the server and client application code working on your machine</p>
<ul>
	<li>Install python 3 to your system - any recent version of<strong> python 3</strong> will work fine, though the most up-to-date version is advisable. If you need help with this step, check out this excellent guide from real python<span>:&nbsp;</span><a href="https://realpython.com/installing-python/" target="_blank"><span><u>https://realpython.com/installing-python/</u></span></a><br>&nbsp;</li>
	<li>Fork and clone the starter repo here:<span>&nbsp;</span><a href="https://github.com/theforage/forage-jpmc-swe-task-1" target="_blank"><span><u>https://github.com/theforage/forage-jpmc-swe-task-1</u></span></a>
		<ul><li>IMPORTANT! Uncheck the “Copy the main branch only” box in the fork dialog on GitHub. A model answer has been provided in a separate branch from main.</li>
		<li>if you are unfamiliar with forking, cloning, or git in general, take a look at the first two chapters of the git book here<span>:&nbsp;</span><a href="https://git-scm.com/book/en/v2" target="_blank"><span><u>https://git-scm.com/book/en/v2</u></span></a><br>&nbsp;</li></ul></li>
	<li>Open the project in your IDE of choice - if you don’t have a favourite python IDE yet, take a look at Pycharm Community Edition. It’s a well-designed IDE by Jetbrains packed with features and plugins, powerful enough to work on the most complex projects, and entirely free.<br>&nbsp;</li>
	<li>Create a new virtual environment in the project root. Pycharm can do this automatically for you using the “<a href="https://www.jetbrains.com/help/pycharm/configuring-python-interpreter.html" target="_blank"><span><u>configure python interpreter</u></span></a>” option in settings.<br>&nbsp;</li>
	<li>Install all project dependencies. These are listed in the requirements.txt file.<br>&nbsp;</l</ul>

<h2>How to Run</h2>
	<p>To start the server, run</p>

	<p>python server3.py</p>

	<p>this will create random market called 'test.csv' in your working directory if one does not already exist.</p>

	<p>When you’re in a work environment, you’ll usually receive tasks in the form of engineering tickets. Here is an example of what this task looks like in the form of an engineering ticket</p>
	
	<p><u>Purpose</u>
	<br>
		We want to process the data feed of stock A and stock B’s price to enable us to analyse when trading for the stock should occur.
	</p>
		
	<p><u>Acceptance Criteria</u></p>
	<ul>
		<li><i>getDataPoint</i>&nbsp;function should return correct tuple of stock name, bid_price, ask_price and price. Note: price of a stock = average of bid and ask</li>
		
		<li><i>getRatio</i>&nbsp;function should return the ratio of the two stock prices</li><li>main function should output correct stock info, prices and ratio</li>
	</ul>
