# programming-for-data-analysis-project
Programming for Data Analysis Project @ GMIT 2021

Overview:
For this project, you must create a data set by simulating a real-world phenomenon of
your choosing. You may pick any phenomenon you wish – you might pick one that is
of interest to you in your personal or professional life. Then, rather than collect data
related to the phenomenon, you should model and synthesise such data using Python.
We suggest you use the numpy.random package for this purpose.

Specifically, in this project you should:
• Choose a real-world phenomenon that can be measured and for which you could
collect at least one-hundred data points across at least four different variables.
• Investigate the types of variables involved, their likely distributions, and their
relationships with each other.
• Synthesise/simulate a data set as closely matching their properties as possible.
• Detail your research and implement the simulation in a Jupyter notebook – the
data set itself can simply be displayed in an output cell within the notebook.

Note that this project is about simulation – you must synthesise a data set. Some
students may already have some real-world data sets in their own files. It is okay to
base your synthesised data set on these should you wish (please reference it if you do),
but the main task in this project is to create a synthesised data set.

Introduction:
As a gamer in my spare time, I will choose the real-world phenomenon of gamer preferences, in terms of the number of hours gamers put in, their preferred console, the number of games they own and their spending habits.

The gaming dataset will analyse 1,000 gamers, and the variables are:
    Hours Played
    Console Owned
    Games Owned
    Digital Games Owned
    Physical Games Owned

The variables are expanded upon below:
    Hours Played:
    This variable is linked to the variable above, Games Owned, where it would be feasible that the more games owned, the more hours would naturally be played.
    Console Owned:
    This variable will display whether a gamer's console preference would be either PlayStation, XBOX or Nintendo, as these consoles would be the top 3 in the world.
    Games Owned:
    This variable will display the quantity of games a gamer would own, which would have an impact on the hours a gamer would put in.
    Digital Games Owned:
    This variable references Games Owned above, where the gamer can download their games from the applicable console's online store.
    Physical Games Owned:
    This variable references both Games & Digital Games Owned above, where the gamer purchases their games from their local games retailer as opposed to a console's online store.

As a gamer, I might pick the real-world phenomenon of the performance of gamers and their playing time. After some research, I decide that the most interesting variable related to this is the hours a gamer puts in - this is going to be one of my variables (hours played).
Upon investigation of the problem, I find that the number of hours on average a gamer plays per week (hours), the number of times they log onto Moodle in the
first three weeks of term (logins), and their previous level of degree qualification (qual) are closely related to grade.
The hours and grade variables will be non-negative real
numbers with two decimal places,
logins will be a non-zero integer,
qual will be a categorical variable with four possible values: none, bachelors, masters, or phd.
After some online research, I find that full-time post-graduate students study on average four hours per week with a standard deviation of a quarter of an hour and that a normal distribution is an acceptable model of such a variable.
Likewise, I investigate the other four variables, and I also look at the relationships between the variables. I devise an algorithm (or method) to generate such a data set, simulating values of the four variables for 1,000 gamers.
I detail all this work in my notebook, and then I add some code in to generate a data set with those properties.