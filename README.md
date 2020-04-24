# volume-em-pubs
Interactive graph of publications of large electron microscopy (EM) volumes over time. Some publications are image volumes only, some have segmentations associated with them. This is by no means an exhaustive list. As datasets are published, they will be added to the list.

This started as a personal toy project to learn interactive graphing in Python and Bokeh.

Initial idea and data from Timothy Lee, Georgia Institute of Technology. 
http://www.bioengineering.gatech.edu/people/timothy-lee

Files in /example are derived from Tim's data. Tim's graph was meant to show the general trend toward larger EM datasets.


Roadmap:
- add logic to determine if point is graphed (conditional on is_plotted)
- add year and author as separate tags in hover box
