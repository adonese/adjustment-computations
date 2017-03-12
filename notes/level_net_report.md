# Adjustment of a level net

## A few remarks about writing your report

When you write a scientific paper there are a few considerations you should pay attention for. This note will not be about the *writing techniques* aspects, for that please consider this great (resource)[https://cgi.duke.edu/web/sciwriting/index.php?action=lesson1]. In this notes we rather consider discussing the structure of a scientific paper.

## Introduction
In your introduction section you are basically need to introduce the reader to your topic. It should be very short and precise. Again, you should only write about your topic, anything more than that would confuse the reader. In your work, write a very short--yet precise--introduction about the errors in surveying works (e.g., random error theory). You should also write about how can we reduce those errors. Some writers also describe the structure of their paper in the first section i.e., Section 2 describes `something`, etc.


## Reducing the errors
In this section you should be more formal about the mathematical formals. You should write the equation of least squares, define its parameters and also show how it works--and do that for the other method too. 

## Methodology
This section describes your work. You should write about two topics
* Describe your field work. Again be as much precise as possible.
* Describe how you solved the problem, using e.g., least squares solution, or other solutions.
* In more details describe your software program. You are asked to write a software package that solves this problem, you should describe how
    * How your program works
    * Any bottlenecks, corner cases? You should describe *if any* when your program does not give the expected answers. Remember, that is a plus not a disadvantage.
    * Be creative! Help the readers understand and appreciate what you have done.
    * You also need to describe how your code works. A good way to do that is to write only a small snippest of your code, and discus them. The rest of the code might be provided at an external host (GitHub?).
## Results

In this section you should write about your software application result. These results are typically shown in tables or figures. Visualization is a very important task in scientific writing. It captures your whole work.

## Discussions

After you have shown your results, you need to give reasons about these results. In our case, you have two methods to reduce the errors, each one of them gives a different corrections. Describe the source of the difference, also show *if any* why one of these methods is better than the other. Giving reasons about your results is very important to help readers understand your work.

## Abstract

You need to summarize your work on a few lines (should not exceed a page). You should describe your work, the problem you want to solve, your results, and if possible, compare your work with other similar works. While the abstract appears on the first page, you should write it after you have completed your whole writing.

---
# LaTeX
You are highly encouraged to use LaTeX. The templates are only provided for LaTeX. You may also use LyX. LaTeX is installed on the department lab, you can use it however you want. If the lab is closed, please contact me to arrange some hours. You can also copy our installation to your own machine. If that does not work for you, try to use `sharelatex` or `overleaf`. You can use them to write your own LaTeX document online.
# Templates

All these templates are provided for LaTeX. You are not encouraged to use LyX, however you can find similar templates. There are a lot of templates for scientific writing e.g., for books, conference poster, etc. In our case, we want an article template. Almost all of the scientific fields have their own templates, and the journals have their own ones too. In our case, we want to use APS, `American Physical Standard`, as the name implies, it is for physics fields. Download APS template from (here)[https://www.sharelatex.com/templates/52fb899a34a287a85245b477/v/3/zip?name=APS]. Try to compile this package at your own, or in the next section we will go through that.

You can view more templates from (sharelatex)[https://www.sharelatex.com/templates/journals] for more journals templates.
