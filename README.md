# Syllabus for "Fundamentals of Digital Archeology"

## News

* Assignment1 due Monday Sep 8 before 2:30PM
* Be ready to present your findings from Assignment1 on Monday
* Project 1 teams are formed! You should see Team? where ? is 1-5 in your github page (on the right)
* Lecture slides are at [Data Discovery](https://github.com/fdac/presentations/dd.pdf)
* Sep 5 lecture recording failed as 323Link (host for the recording) went down

==========

* Aloc Hota is a TA for this course: office hours are on Monday 10AM-Noon and on Wednesday 4-6PM in MK314.
* Please =watch= and check [https://github.com/fdac/syllabus](https://github.com/fdac/syllabus) periodically for news
* [Sep 3 lecture recording](http://utk-eecs.podcast.323link.com/episodes/a/au/audris/123/Audris_Mockus_Videos__123.h264.flash.mp4)

==========

* If you have missed the lecture on Aug 29 please take a look at the recording: [Aug 29, 2014 recording](http://utk-eecs.podcast.323link.com/episodes/a/au/audris/120/Audris_Mockus_Videos__120.h264.flash.mp4)
* [Assignment 1](https://github.com/fdac/Assignment1) due before class on Sep 8
	* A good [place](http://regexppal.com) to practice regular expressions
	* [python documentation for regular expressions](https://docs.python.org/2/library/re.html)
	* A nice [coursera tutorial on basic re](https://class.coursera.org/nlp/lecture/125)
	* A hint for extra credit: 
	 	* assume that the word frequency follows binomial distribution: k - the number of coccurences of a specific word in the text with n words.
	 	* calculate confidence intervals for fractions p=k/n in different documents
* Only 14 pull requests are submitted so far for Homework0 (on Sep 30), if you don't see yourself in the 
[list](https://github.com/fdac/Homework0/pulls?q=+is%3Apr+), please submit a pull request. 
* Have a great Labor Day

===========

### ~~MK623~~ moved to _MK419_
* Please watch [fdac/syllabus](https://github.com/fdac/syllabus) and other repositories to get
   email with any changes (click on Watch icon: if the icon is Un
   Watch, then you are already "watching") 
* Please try to use issues and wikis: as you resolve problems it
   is important to document the problem and the resolution. It helps
   others (and yourself) if you encounter a similar issue later.
   1. title is very important for an issue: provide a one-line
      summary
   1. describe the issue and the relevant context, attach
      screenshots if needed
   1. as more information is gathered, document that in the comments
      section
   1. once the issue is resolved, please close it and explain briefly
      how it was resolved. Perhaps even add a wiki entry.
* For VM problems related to VT-x/AMD-v, I have added [a possible suggestion](https://github.com/fdac/syllabus/wiki)


* **Course:** [COSCS-495/COSCS-595][class-site]
* ** ~~MK623~~ moved to MK419  2:30-3:20 MWF**
* **Instructor:** Audris Mockus, [audris@utk.edu](mailto:audris@utk.edu)
* **Need help?**

Simple rules for questions: 

1. There are no stupid questions. 
1. Think of what the right answer may be.
1. Search online: stack overflow, etc.
  * code snippets: [gist.github.com](https://gist.github.com/)
  * answers to questions: [Stack Overflow](http://stackoverflow.com/)
1. Look through [issues](https://github.com/fdac/syllabus/issues)
1. Post the question as an issue
1. Ask instructor: [email](mailto:audris@utk.edu) for 1-on-1 help, or
   to set up a time to meet 

## Objectives
The course will combine theoretical underpinning of big data with
intense practice. In particular, approaches to ethical concerns,
reproducibility of the results, absence of context, missing data,
and incorrect data will be both discussed and practiced by writing
programs to discover the data in the cloud, to retrieve it by
scraping the deep web, and by structuring, storing, and sampling it
in a way suitable for subsequent decision making.  At the end of the
course students will be able to discover, collect, and
clean digital traces, to use such traces to construct meaningful
measures, and to create tools that help with decision making.

## Expected Outcomes
Upon completion, students will be able to discover, gather, and analyze
digital traces, will learn how to avoid mistakes common in
the analysis of low-quality data, and will have produced a working
analytics application.

In particular, in addition to practicing critical thinking,
students will acquire the following skills:
*  Use Python and other tools to discover, retrieve, and process data.
  
*  Use data management techniques to store data locally and in the cloud.
  
*  Use data analysis methods to explore data and to make predictions.

## Course Description

A great volume of complex data is generated as a result of human
activities, including both work and play. To exploit that data for
decision making it is necessary to create software that discovers,
collects, and integrates the data.

Digital archeology relies on traces that are left over in the course
of ordinary activities, for example the logs generated by sensors in
mobile phones, the commits in version control systems, or the email
sent and the documents edited by a knowledge worker. Understanding
such traces is complicated in contrast to data collected using
traditional measurement approaches.

Traditional approaches rely on a highly controlled and well-designed
measurement system. In meteorology, for example, the temperature is
taken in specially designed and carefully selected locations to
avoid direct sunlight and to be at a fixed distance from the ground.
Such measurement can then be trusted to represent these controlled
conditions and the analysis of such data is, consequently, fairly
straightforward.

The measurements from geolocation or other sensors in mobile phones
are affected by numerous (yet not recorded) factors: was the phone
kept in the pocket, was it indoors or outside?  The devices are not
calibrated or may not work properly, so the corresponding
measurements would be inaccurate.  Locations (without mobile phones)
may not have any measurement, yet may be of the greatest interest.
This lack of context and inaccurate or missing data necessitates
fundamentally new approaches that rely on patterns of behavior to
correct the data, to fill in missing observations, and to elucidate
unrecorded context factors. These steps are needed to obtain
meaningful results from a subsequent analysis.

The course will cover basic principles and effective practices to
increase the integrity of the results obtained from voluminous but
highly unreliable sources.

*   Ethics: legal aspects, privacy, confidentiality, governance
   
*   Reproducibility: version control, ipython notebook
   
*   Fundamentals of big data analysis:
    extreme distributions, transformations, quantiles,
    sampling strategies, and
    logistic regression

*   The nature of digital traces:
    lack of context,
    missing values, and
    incorrect data

## Prerequisites

Students are expected to have basic programming skills, in
particular, be able to use regular expressions, programming concepts
such as variables, functions, loops, and data structures like lists
and dictionaries (for example, COSC 365)

Being familiar with version control systems (e.g., COSC 340), Python
(e.g., COSC 370), and introductory level probability (e.g., ECE 313)
and statistics, such as, random variables, distributions and
regression would be beneficial but is not expected. Everyone is
expected, however, to be willing and highly motivated to catch up in
the areas where they have gaps in the relevant skills.

All the assignments and projects for this class will use github and
Python. Knowledge of Python is not a prerequisite for this course,
provided you are comfortable learning on your own as needed. While
we have strived to make the programming component of this course
straightforward, we will not devote much time to teaching
prorgramming, Python syntax, or any of the libraries and APIs.  You
should feel comfortable with:

1. How to look up Python syntax on Google and StackOverflow.
1. Basic programming concepts like functions, loops, arrays, dictionaries, strings, and if statements.
1. How to learn new libraries by reading documentation and resusing examples
1. Asking questions on StackOverflow or as a GitHub issue.


### Requirements

These apply to real life, as well.

* Must apply "good programming style" learned in class
    * Optimize for readability
* Bonus points for:
    * Creativity (as long as requirements are fulfilled)

## Teaming Tips

* Agree on an editor and environment that you're comfortable with
* The person who's less experienced/comfortable should have more keyboard time
* Switch who's "driving" regularly
* Make sure to save the code and send it to others on the team

## Evaluation

* Class Participation – 15%: students are expected to read all
   material covered in a week and come to class prepared to take
   part in the classroom discussions. Responding to other student
   questions (issues) counts as classroom participation.

* Assignments - 40%: Each assignment will involve writing (or modifying a template of)
   a small Python program.

* Project - 45%: one original project done alone or in a group of 2 or 3
   students. The project will explore one or more of the themes covered
   in the course that students find particularly compelling.  The
   group needs to submit a project proposal (2 pages IEEE format)
   approximately 1.5 months before the end of term.  The proposal
   should provide a brief motivation of the project, detailed
   discussion of the data that will be obtained or used in the project,
   along with a time-line of milestones, and expected outcome.

## Other considerations

As a programmer you will never write anything from scratch, but will
reuse code, frameworks, or ideas.  You are encouraged to
learn from the work of your peers. However, if you don't try to do
it yourself, you will not learn. [Deliberate practice][deliberate-practice]
(activities designed for the sole purpose of effectively improving
specific aspects of an individual's performance) is the only way to
reach perfection.

Please respect the terms of use and/or license of any code you find,
and if you re-implement or duplicate an algorithm or code from
elsewhere, credit the original source with an inline comment.

## Homework 0 (Due Aug 22)

1. GitHub
   * Sign up for [GitHub](https://github.com/) if not already signed
     up. Pick default (free plan).	 
   * Create a pull request on
      [students repository](https://github.com/fdac/students) so I
      can add you to the to the GitHub group for the course.
	  1. Start by [**forking** the students repository](https://github.com/fdac/students)
	  1. Add your GitHub username as USERNAME.md (click on propose
         new file)
	  1. Click on Create Pull Request
   * Install [virtual machine][vminstall] (kindly provided by Markus Iturriaga Woelfel)
1. Familiarize yourself with GitHub workflow
   * Walk through [workflow](#workflow) using
	[Homework0](https://github.com/fdac/Homework0) notebook
    
## Workflow
1. To start, [**fork** the repository][forking] for the exercise/project (found under [github.com/fdac](https://github.com/fdac))
1. [**Clone**][ref-clone] the repository to your computer.
1. View, create, and edit your ipython notebooks or other files
1. [**commit**][ref-commit] changes to complete your solution.
1. [**Push**][ref-push]/sync the changes up to GitHub.
1. [Create a **pull request**][pull-request] on the original
   repository by the due time (generally within a week)
1. You can continue to push fixes and improvements until the close
date – just add a comment in the pull request to let me know it's been updated.

Feedback will be given in the pull request, so please respond with
your thoughts and questions!  You are welcome to open the pull
request as the work is still in-progress if you are stuck and want
to ask a question – just mention `@audris` with the question to make
sure I know to look at it sooner.

## Resources
### Materials

This class assumes you are confident with this material, but in case you need a brush-up...

* Codecademy – [Python](http://www.codecademy.com/courses/python)
  and [Python Dictionaries](http://www.codecademy.com/courses/python-beginner-en-pwmb1/2/1?curriculum_id=4f89dab3d788890003000096)
* See also – [Other](#other)

#### Other

* [Mining the Social Web, 2nd Edition](http://shop.oreilly.com/product/0636920030195.do)

##### R and data analysis
* Modern Applied Statistics with S (4th Edition) by William
  N. Venables, Brian D. Ripley. ISBN0387954570
* [R](https://www.coursera.org/course/compdata) 
* [Code School](http://www.codeschool.com/courses/try-r)
* [Quick-R](http://www.statmethods.net)

##### Tutorials written as ipython-notebooks
* [python-data-cleaning](http://nbviewer.ipython.org/github/ResearchComputing/Meetup-Fall-2013/blob/master/python/lecture_21_pandas_processing.ipynb)
* [python tutorial for engineers](http://nbviewer.ipython.org/gist/rpmuller/5920182)

#### GitHub

* Git and GitHub
    * [Official GitHub Help](https://help.github.com/)
	* [GitHub Issues](https://guides.github.com/features/issues/)
    * [Recommended resources](https://help.github.com/articles/what-are-other-good-resources-for-learning-git-and-github)
* GitHub Pages
    * [Official site](http://pages.github.com/)
    * [Thinkful guide](http://www.thinkful.com/learn/a-guide-to-using-github-pages/)


<!-- Links -->
[vminstall]:http://www.eecs.utk.edu/resources/it/kb/cosc-594fda
[class-site]:http://web.eecs.utk.edu/~audris/fdac
[deliberate-practice]:http://www.psy.fsu.edu/faculty/ericsson/ericsson.exp.perf.html
[pull-request]:https://help.github.com/articles/creating-a-pull-request
[create-repo]: https://help.github.com/articles/create-a-repo
[forking]: https://guides.github.com/activities/forking/
[ref-clone]: http://gitref.org/creating/#clone
[ref-commit]: http://gitref.org/basic/#commit
[ref-push]: http://gitref.org/remotes/#push
[pull-request]: https://help.github.com/articles/creating-a-pull-request
[raw]: https://raw.githubusercontent.com/education/guide/master/docs/forks.md
