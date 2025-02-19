---
layout: page
title: Resources
nav_order: 6
description: Relevant material to aid you in the course.

---

# Resources
{:.no_toc}

Here is a collection of resources that will help you learn more about various concepts and skills covered in the class. Reading and studying beyond the course material provides a 3 dimensional perspective while only seeing the course perspective is closer to 1 dimensional. It's important to be exposed to different perspectives and ways of understanding familiar concepts. 

Jump to:
* TOC
{:toc}



<a name = 'course_website'></a>
## Course Website

All lecture materials and notes will be posted on the course website.

## Textbook 

This course has two official texts. Both texts are available for free online (legally) at the provided links.

- [Learning Data Science](https://learningds.org/intro.html) by Sam Lau, Joey Gonzalez, and Deb Nolan
- [Introduction to Statistical Learning with Python](https://www.statlearning.com) by James, Witten, Hastie, Tibshirani


## Coding and Mathematics Resources


#### Pandas

  - [Pandas API Reference](https://pandas.pydata.org/pandas-docs/stable/reference/index.html)
  - [The Pandas Cookbook](http://nbviewer.jupyter.org/github/jvns/pandas-cookbook/tree/master/cookbook/): Overview of some of the basic Pandas functions. 
  - [Python for Data Science](http://wavedatalab.github.io/datawithpython/index.html) Notebooks demonstrating Pandas functionality.

#### Jupyter Notebooks

Jupyter notebooks can be executed and edited in a number of IDEs. I prefer to work with jupyter notebooks in [google collaboratory](https://colab.research.google.com) and this will be the official platform which students are encouraged to use. Others may prefer to use a local IDE like [visual studio](https://code.visualstudio.com). Students are free to choose their preferred platform. However, course staff may be unable to help resolve IDE specific issues.

- [Tutorial](https://saturncloud.io/blog/how-to-run-a-downloaded-jupyter-notebook-on-google-colaboratory/) for uploading .ipynb file to google colab 


#### LaTeX
+ [Guide to Overleaf and LaTeX](https://www.overleaf.com/learn)

#### Other Web References

- **Python:**
  - [Python Tutorial](https://docs.python.org/3.5/tutorial/): If you have issues with python syntax or commands, start here!
  - [Python + Numpy Tutorial](http://cs231n.github.io/python-numpy-tutorial/) Numpy provides functionality for arrays and mathematical essentials. You may not have used it directly. This provides helpful experience with numpy basics.

- **Data Visualization:**
  - [matplotlib.pyplot tutorial](http://matplotlib.org/users/pyplot_tutorial.html#pyplot-tutorial): This short tutorial provides an overview of the basic plotting utilities we will be using.
  - [Pandas Tutor](https://pandastutor.com).
  - [Kernel Density Visualization](https://mathisonian.github.io/kde/).
  - [Altair Documentation](https://altair-viz.github.io/): Altair(Vega-Lite) is a new and powerful visualization library. 

  

#### Calculus and Linear Algebra

**Calculus**:
In terms of calculus, you will need to know a few things, most of which are covered within the space of the first homework and lab. Specifically, you will need to know univariate calculus rules like: Taking derivatives of a univariate function (i.e. f(x), where x is the only variable); Derivative power rule; Knowing derivatives of mathematical functions like: sinx,cosx,logx,ex; Chain rule; Product rule (rarely); Derivatives of sums. We will expect some multivariate fluency like: Taking partial derivatives of a multivariate function (i.e. f(x,y,z), where x,y,z are all variables); Gradients (the concept).

- Khan Academy: 
[Derivatives, Definitions, and Basic Rules](https://www.khanacademy.org/math/calculus-1/cs1-derivatives-definition-and-basic-rules);
[Multivariable Derivatives](https://www.khanacademy.org/math/multivariable-calculus/multivariable-derivatives)


**Linear Algebra**:

Concepts roughly in order of importance:
vectors, matrices; rank/nullity;
inner products, orthogonality, norms;
linear independence;
orthonormal matrices;
vector spaces;
projections;
invertibility.


- Data 100 textbook: Geometric Perspective of Linear Projection ([Chapter 15](https://www.textbook.ds100.org/ch/15/linear_multi_fit.html)); Vector Spaces ([Appendix 2](https://www.textbook.ds100.org/ch/a02/vector_space_review.html))
- 3blue1brown: [Essence of Linear Algebra](https://www.3blue1brown.com/essence-of-linear-algebra-page)
- Khan Academy: [Linear Algebra](https://www.khanacademy.org/math/linear-algebra)
- MIT OpenCourseware: [Linear Algebra Video Lectures](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/video_galleries/video-lectures/)


#### Probability
+ [Probability and statistics textbook](http://stat88.org/textbook/content/intro.html) that provides introductory probability coverage geared towards data science.


## Homework Issues

### Homework 1

- cannot convert numpy.ndarray to numpy.ndarray (solved) - this is due to a wayward numpy version and is fixed. Solution: Reload the homework from the link.

- If you changed pip3 to pip (solved) - info about why that may not work is [here](https://www.perplexity.ai/search/install-works-with-pip3-but-wh-i19KtrHVS7OUEdGOMCko1w) TLDR; using pip instead of pip3 may not work depending on how your local python installation and pip are setup. Solution: Use pip3.

- urllib related error on **local** execution (solved) - The homework code was developed for python 3.11.9, some python packages in 3.12 and 3.13 are not compatible. Solution: Install and use python 3.11.9 - this does not affect colab

- A test case failed that should have passed on qEx7 and qEx5 (solved) - Solution: reload the homework or (if you have already started) copy lines 9 & 10 in the first cell from the homework on the website and replace line 9 in your copy

- There was a small issue with the example output on Question 2d. The output was listed as `np.array([0., 2., 4., 6.])` but it should have beeen `np.array([1., 3., 5., 7.])`. This didn't effect the grading and has been corrected. Thanks for reporting the error!


### Homework 2

- Question 1c 

Do not use the new_position variable in any of the code that you write. You do not need it and accessing it breaks the game. 

As discussed in class, the game was created by Thomas Bayes himself. In the game, he is able to identify the location of the mark on the wall knowing only if each new position struck by a thrown ball is to the right of the mark or not. If he was allowed to know where the ball struck (the content of new_position) then the game would not be interesting!

The reason new_position is exposed is so that the positions can be logged for visualization (which is taken care of for you in the code). I apologize for any confusion!

- Question 2a

The successes variable should contain an array of booleans. 

There is a problem with the test case. If your answer is within 0.03 of pi, then it is correct. 

- Question 3b

This question can be answered by referring to the material from lecture 4 and 5 and the in class exercise. 

There is one nuance that differs from what we have seen. The actual pdf for a binomial distribution is discrete. When we use KDE to estimate it, the function is smoothed. So, if you intend to integrate from 0 to 4, you should integrate from -0.5 to 4.5 to capture the smooth roll off. This will make sense when you plot the KDE estimated PDF.

- Question 5a

The deflategate.csv file only contains the 15 datapoints visible in the first table. You can either copy and paste them into a dataframe, create a csv from those values, or download the csv [here](https://drive.google.com/file/d/1OCLP17_RaK0BphLxUNpO9Os-MULasn58/view?usp=sharing).


## Wellness Resources

Your well-being matters, and we hope that Data 100 is *never* a barrier to taking care of your mental and physical health. Below are some campus resources that may be helpful.


### For mental well-being
{:.no_toc}
The Counseling Center offers brief, short-term, solution-focused therapeutic interventions for Tennessee Tech University students. The staff of the Counseling Center is available to assist students with their personal and social concerns in hopes of helping them achieve satisfying educational and life experiences. To learn more or schedule an appointment, visit the Counseling Center [website](https://www.tntech.edu/counsel/index.php). 



### Health Services 
{:.no_toc}
Health Services offers high-quality, affordable care that is accessible and promotes the health and wellness of our Tennessee Tech community. Visit the Health Services [website](https://www.tntech.edu/healthservices/) to learn more. 


### For basic needs (food, shelter, etc.)
{:.no_toc}
Tennessee Tech has a food pantry which can be a great point of contact for the food insecure. This was started out of a passion to make sure that the Tennessee Tech community had their needs met. Please do not go without!



## Disability Accommodation 
{:.no_toc}
Students with a disability requiring accommodations should contact the accessible education center (AEC). An accommodation request (AR) should be completed as soon as possible, preferably by the end of the first week of the course. The AEC is located in the Roaden University Center, room 112; phone 931-372-6119. For details, view Tennessee Tech's policy 340 – services for students with disabilities at [policy central](https://tntech.policytech.com/docview/?docid=1131&public=true).


### Technical Help 
{:.no_toc}
If you are experiencing technical problems, visit the myTech IT [Helpdesk](https://its.tntech.edu/display/MON/Help+Desk) for assistance. 

If you are having trouble with one of the instructional technologies (i.e. Zoom, Teams, Qualtrics, Respondus, or any technology listed [here](https://www.tntech.edu/citl/tech-services/index.php)) visit the Center for Innovation in Teaching and Learning (CITL) [website](https://www.tntech.edu/citl/index.php) or call 931-372-3675 for assistance. 

For accessibility information and statements for our instructional technologies, visit the CITL's Learner Success Resource [webpage](https://www.tntech.edu/citl/learner-success-resources.php). 


### Tutoring 
{:.no_toc}
The university provides free tutoring to all Tennessee Tech students. Tutoring is available for any class or subject, as well as writing, test prep, study skills, and resume support. Appointments are scheduled, so contact the Learning Center [website](https://www.tntech.edu/library/learning-center.php) for more information. 




### Pandemic Protocols
{:.no_toc}
Each student must take personal responsibility for knowing and following any University protocol related to pandemics and other public health events. Students are expected to follow all directives published by Tennessee Tech on its official webpage. As conditions related to the COVID-19 pandemic change, the University's COVID-19 protocols are also likely to change. Students are expected to monitor the University's official webpage to stay up to date on public health protocols.
