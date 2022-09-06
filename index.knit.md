---
title: "Intro to Urban Analytics"
author: "Bon Woo Koo & Subhrajit Guhathakurta"
date: '2022-08-20'
output:
  rmdformats::downcute:
    downcute_theme: "chaos"
    code_folding: show
---


<br>
**Office hours**  
* **Bon Woo Koo**: Wed 10AM - 12PM  
* **Subhrajit Guhathakurta**: Tue 11AM-12PM  
* **Location**: The Center for Spatial Planning Analytics and Visualization (760 Spring St NW, suite 217).
<br>
<br>

This course introduces students to the field of urban analytics. The main objective of this course is for students to master important theories and concepts emerging in the field of urban analytics. Students will complete this course with a working knowledge of how data and advanced analytical techniques can enhance the planning and operation of cities.

# Prerequisites
There are no prerequisites to this course, but the followings are encouraged.
* Basic understanding of geographic information systems (GIS) and applied statistics
* Working knowledge of any programming language, preferably the R (or Python)

# Course Goals and Learning Outcomes 
After successfully completing this course, students will: 

* List sources of data from urban areas and why each of them would be used
* Explain what is on the cutting edge of urban analytics research
* Describe a few types of measurements for spatial data
* Explain characteristics of data types
* Learn how to clean and manipulate spatial data using technical analysis skills 
* Create a basic data visualization
* Be critical about who is creating and using data


# Course schedules





<table class="table table-condensed" style="margin-left: auto; margin-right: auto;">
 <thead>
  <tr>
   <th style="text-align:left;"> Module </th>
   <th style="text-align:left;"> Week </th>
   <th style="text-align:left;"> Topic </th>
   <th style="text-align:left;"> Reading </th>
   <th style="text-align:left;"> To do </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;width: 12em; vertical-align: top !important;" rowspan="2"> Preparation </td>
   <td style="text-align:left;"> 1 </td>
   <td style="text-align:left;"> Intro to Urban Analytics in R [(Slide)](https://github.gatech.edu/pages/sguhathakurta3/UA-Lecture1/Untitled/LectureONE.html), <br> Data ethics [(Slide)](https://github.gatech.edu/pages/sguhathakurta3/UA-Lecture1/Lecture-2/LectureTWO.html) </td>
   <td style="text-align:left;"> [Tu](https://journals.sagepub.com/doi/full/10.1177/2399808319839494) <br> [Th-1](https://scholarship.law.gwu.edu/cgi/viewcontent.cgi?article=1159&amp;context=faculty_publications), [Th-2](https://openyls.law.yale.edu/handle/20.500.13051/7808), [Th-3](https://web.stanford.edu/dept/HPS/Design%20AI%20so%20that%20it%27s%20fair.pdf), [Th-4](https://www.nature.com/articles/541458a) </td>
   <td style="text-align:left;"> [Survey](https://forms.gle/4BBtMfrvr5yJLebK9),<br>[Group](https://forms.gle/sGVfDgLR6yLLmb4S8) </td>
  </tr>
  <tr>
   
   <td style="text-align:left;"> 2 </td>
   <td style="text-align:left;"> Data for Urban Analytics [(Slide)](./Lab/module_0/w2_d2_modern_data.html), <br> Intro to R - 1 [(Slide)](./Lab/module_0/w2_d1_Intro_to_R_1.html), 2 [(Slide)](./Lab/module_0/w2_d2_Intro_to_R_2.html) </td>
   <td style="text-align:left;"> [Tu-1](https://r4ds.had.co.nz/workflow-basics.html), [Tu-2](https://r4ds.had.co.nz/transform.html) <br>
   [Th-1](https://geocompr.robinlovelace.net/spatial-class.html), [Th-2](https://geocompr.robinlovelace.net/attr.html), [Th-3](https://geocompr.robinlovelace.net/spatial-operations.html), [Th-4](https://rmarkdown.rstudio.com/lesson-1.html) </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 12em; vertical-align: top !important;" rowspan="4"> Module 1: <br> A walk-through of your first UA project - <br> POI &amp; Census </td>
   <td style="text-align:left;"> 3 </td>
   <td style="text-align:left;"> Accessing data (Slide), <br> Census &amp; Yelp API (RMD) </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;"> Mini </td>
  </tr>
  <tr>
   
   <td style="text-align:left;"> 4 </td>
   <td style="text-align:left;"> <b>Mini-presentation 1 (Slide)</b>, <br> Tidy data (Slide), <br> Data wrangling (RMD) </td>
   <td style="text-align:left;"> [1](https://www.researchgate.net/publication/215990669_Tidy_data), [2](https://r4ds.had.co.nz/tidy-data.html) </td>
   <td style="text-align:left;"> Mini </td>
  </tr>
  <tr>
   
   <td style="text-align:left;"> 5 </td>
   <td style="text-align:left;"> First statistical insights from your data (Slide), <br> Hands-on (RMD) </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;"> Mini </td>
  </tr>
  <tr>
   
   <td style="text-align:left;"> 6 </td>
   <td style="text-align:left;"> Interactive visualization (Slide), <br> Hands-on (RMD) </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;"> Mini </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 12em; vertical-align: top !important;" rowspan="2"> Module 2: <br> Transportation </td>
   <td style="text-align:left;"> 7 </td>
   <td style="text-align:left;"> <b>Mini-presentation 2 (Slide)</b>, <br> General Transit Feed Specification (Slide), <br> GTFS and equity (RMD) </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   
   <td style="text-align:left;"> 8 </td>
   <td style="text-align:left;"> Open Street Map (Slide), <br> OSM as a graph (RMD) </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;"> Major </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 12em; vertical-align: top !important;" rowspan="2"> Module 3: <br> Image &amp; computer vision </td>
   <td style="text-align:left;"> 9 </td>
   <td style="text-align:left;"> <b>Mini-presentation 3 (Slide)</b>, Urban images and computer vision (Slide), <br> Yolo in R (RMD) </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   
   <td style="text-align:left;"> 10 </td>
   <td style="text-align:left;"> Many ways of viewing your city (Slide), <br> Sampling images and using Vision API (RMD) </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;"> Major </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 12em; vertical-align: top !important;" rowspan="2"> Module 4: <br> Social media </td>
   <td style="text-align:left;"> 11 </td>
   <td style="text-align:left;"> <b>Mini-presentation 4 (Slide)</b>, <br> User-generated text data - Twitter (Slide), <br> Getting live feeds from Twitter (RMD) </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   
   <td style="text-align:left;"> 12 </td>
   <td style="text-align:left;"> Preprocessing texts (Slide), <br> Sentiment analysis (RMD) </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;"> Major </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 12em; vertical-align: top !important;" rowspan="2"> Module 5: <br> Storytelling </td>
   <td style="text-align:left;"> 13 </td>
   <td style="text-align:left;"> <b>Mini-presentation 5 (Slide)</b>, <br> Storytelling with data - 1 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   
   <td style="text-align:left;"> 14 </td>
   <td style="text-align:left;"> Storytelling with data - 2 </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;"> Major </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 12em; "> Student Presentations </td>
   <td style="text-align:left;"> 15 </td>
   <td style="text-align:left;"> <b>Student presentations</b> </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 12em; vertical-align: top !important;" rowspan="2"> Reading weeks </td>
   <td style="text-align:left;"> 16 </td>
   <td style="text-align:left;"> <b>Student presentations - continued</b> </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   
   <td style="text-align:left;"> 17 </td>
   <td style="text-align:left;"> Wrap up </td>
   <td style="text-align:left;">  </td>
   <td style="text-align:left;">  </td>
  </tr>
</tbody>
</table>
*NOTE 1: Slide = lecture slide & RMD = R Markdown document*

*NOTE 2: The links to the class material will be updated each week.*

*NOTE 3: For readings, TU = readings for Tuesday & TH = readings for Thursday*

<font size="3px" color="grey">Modification history</font><br>
<font size="3px" color="grey"> &bull; 8/25/2022: Moved Mini-presentation 1 from week 3 to 4</font>


# How to succeed in this class
1. Be prepared for occasional frustration. It’s part of learning process. However, don’t spin the wheel. You are responsible for actively searching for help. Don’t wait until the last minute (e.g., homework).
2. Read assigned book chapters/materials, review their examples and snippets, replicate their results, and repeat until you understand.
3. Work with peers. Form a group early in the semester, and have their sharp eyes on your code. Still, you need to submit your HW individually.
4. If you have a trouble with your code outside of class (and get frustrated), Google it. It will not only be faster and more efficient than contacting us, but trouble-shooting on your own is essential skill, particularly after you graduate. Luckily, most of the problems you may encounter in this class have been already encountered by others. You can search how they solved them in **StackOverFlow.** 
5. Of course, you can ask questions to us anytime, inside or outside classroom. I strongly encourage you to utilize our office hours as another learning opportunity.

# Grading breakdown
There are four major assignments, four mini assignments, and one final team project.
Only three out of the four major assignments will be counted towards the final grade. 
Same applies to the mini assignments.

<table class="table table-condensed table-responsive" style="margin-left: auto; margin-right: auto;">
 <thead>
  <tr>
   <th style="text-align:left;"> Assignment.Type </th>
   <th style="text-align:left;"> Percent </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> Final Project Presentation </td>
   <td style="text-align:left;"> 20% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Major Assignment </td>
   <td style="text-align:left;"> 45% (15% each x 3) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Mini Assignment </td>
   <td style="text-align:left;"> 30% (10% each x 3) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Participation (Mini Presentation) </td>
   <td style="text-align:left;"> 5% </td>
  </tr>
</tbody>
</table>

The final grade will be assigned as a letter grade according to the following scale:

* **A $~~~$ 100%-90%** $~~~$ Excellent (4 quality points per credit hour)
* **B $~~~$ 89% - 80%** $~~~$ Good (3 quality points per credit hour)
* **C $~~~$ 79% - 70%** $~~~$ Satisfactory (2 quality points per credit hour)
* **D $~~~$ 69% - 60%** $~~~$ Passing (1 quality points per credit hour)
* **F $~~~$ 59% $~$-$~$ 0%** $~~~$ Failure (0 quality points per credit hour)

# Textbooks/resources
There is no textbook associated with this course. I highly recommend Data Action by Sarah Williams, and Urban Analytics by Alex Singleton, Seth Spielman and David Folch is another popular textbook on the topic.

Here are some other free resources:

* [R for Data Science](https://r4ds.had.co.nz/)
* [Geocomputation with R](https://rpubs.com/spring19cp6521/Syllabus)
* [Urban Analytics - supporting materials](https://github.com/alexsingleton/urban_analytics)

# Technology
Cell phone use is prohibited at all times during class, except if you are using cell phones to answer quizzes/ surveys. Laptops, tablets, e-readers, and other digital devices may be used to take notes or refer to relevant information, take quizzes, and complete in-class assignments. If you are using a digital device for non-course purposes at any time during the semester, you will be asked to refrain from using it for the remainder of the course. No exceptions.

There will be times in class when the instructor reserves the right to enact the “No Device Rule.” During these times, all digital devices will be required to be stored off desks so that students may concentrate on tasks or presentations. Expect that this rule will be used when your peers are presenting and during guest lectures.

# Student-Faculty expectations
At Georgia Tech, we believe that it is important to continually strive for an atmosphere of mutual respect, acknowledgement, and responsibility between faculty members and the student body. See http://www.catalog.gatech.edu/rules/22.php for an articulation of some basic expectations—that you can have of me, and that I have of you. Respect for knowledge, hard work, and cordial interactions will help build the environment we seek. Therefore, I encourage you to remain committed to the ideals of Georgia Tech while in this class.

# Academic integrity
Georgia Tech aims to cultivate a community based on trust, academic integrity, and honor. Students are expected to act according to the highest ethical standards. For more information on Georgia Tech’s Academic Honor Code, please visit http://www.catalog.gatech.edu/rules/18b.php and http://www.catalog.gatech.edu/genregulations/honorcode.php.

# ADA accommodations
If you are a student with learning needs that require special accommodation, contact the Office of Disability Services at (404)894-2563 or http://disabilityservices.gatech.edu/, as soon as possible, to make an appointment to discuss your special needs and to obtain an accommodations letter.  Please also e-mail me as soon as possible in order to set up a time to discuss your learning needs.
