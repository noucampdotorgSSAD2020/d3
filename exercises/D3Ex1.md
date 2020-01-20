# D3 Exercise 1 – SVG

> Complete ALL the exercises in this section. Ask thomas.devine@lyit.ie for help or post an *Issue* on your GitHub repository.


## Clone the Remote Repository

1.	Accept the GitHub Classroom invitation to this exercise @ the module moodle page.

1.	Copy the clone URL from your new repository ``d3-<YOURACCOUNT>``

1.	Type these commands into your *Git Bash* client:

	```
	$ cd /<DRIVE>/xampp/htdocs   
	$ git clone <URL> d3
	$ cd d3
	$ ls
	$ git status

	```

	Check your ``htdocs`` folder.  You should have a new folder called ``d3`` with some files in it.

		

## Part 1

> It is important you know how to render SVG graphics BEFORE using D3.  Its similar to having to know HTML before using JavaScript

1.	Examine and open the file [http://localhost/d3/svgBarChart.html](http://localhost/d3/svgBarChart.html)

	It uses *SVG* to render a simple bar chart.  

	Using your code editor experiment/change some of the values, colours, etc. to see the outcome

1.	Modify the code in ``svgBarChart.html`` so that bar chart looks like this:

	![img](../images/barChart2.png)

	Set the ``<svg>`` width to 300.


1.	Add the code to ``svgCircles.html`` to render this:

	![img](../images/svgCircles.png)

	The diameter of the circles are shown in the text values inside the circle.  Set the ``<svg>`` height to 300.

1.	Add the code to ``svgColumnChart.html`` for a new SVG rendered *column chart* like this:

	![img](../images/columnChart1.png)

	Set the ``<svg>`` height to 300.

1.	Add the code to ``svgLineChart.html`` to create a new SVG rendered *line chart* to look like this:

	![img](../images/lineChart1.png)

1.	Push your code to **your private** repository on GitHub.  Type these commands into your *Git Bash* client:

	```
	$ git status
	$ git add .
	$ git commit -m "Exercise 1 Part 1 - DONE|PARTIAL|HELP"
	$ git push origin master
	$ git status

	```

## Part 2

1.	Examine and open the code in [http://localhost/d3/svgBarChart2.html](http://localhost/d3/svgBarChart2.html) that uses SVG to render a simple bar chart dynamically using JavaScript.  
	
	Add another value to the ``data`` array and rerun the code.

1.	Modify the code so the output includes the text like this:

	![img](../images/barChart3.png)

	Add the text dynamically using JavaScript.

1.	Push your code to **your private** repository on GitHub.  Type these commands into your *Git Bash* client:

	```
	$ git status
	$ git add .
	$ git commit -m "Exercise 1 Part 2 - DONE|PARTIAL|HELP"
	$ git push origin master
	$ git status

	```
