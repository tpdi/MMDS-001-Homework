**This is an iPython Notebook for the homework assignments in the Coursera class *Mining Massive Datasets*
offered in conjunction with Stanford University and taught by *Jure Leskovec, Anand Rajaraman, and Jeff Ullman.***

The course can be found at: https://class.coursera.org/mmds-001

It's principally of use to students of that course. The text and images are from the course and are copyrighted by their creators.
I've merely re-packaged them in a format that makes completing the homework more convenient, and allows it to be later used as a
study guide. Permission to distribute it was granted by Derek Farren, a Teaching Assistant for the first iteration of the course. 
Because of this there is no license attached to this repository.

The homework is a copy of the homework in the first iteration of the class, mmds-001.

Using the iPython server, the notebook creates a web page with markup and images, which can also include (and run) embedded python scripts.

I have the questions, and placeholders for answers in one git branch (master) and a version with my answers in another git branch.

iPython Notebooks work almost like a wiki, in that each part of the page (each cell, in a vertical array) can be edited in an editable mode, or run. Running a cell puts it into a display mode. Each cell can be one of several types:

* Markdown with MathJax support. When run, it displays the markdown as HTML.

* One of several headers, which correspond to HTML H1, H2, etc. tags.

* Or python. Python cells, when run, run the python script in them and display that script's output.

All the data to create the page is held in a JSON document, which the iPython server transforms into the HTML page. 

It's that JSON document, plus the image files, that you'll find here.

iPython's JSON files make good use of newlines, and so git diffs and mergetools (I use kdiff) seem (so far, in my very limited experience) to work with the JSON pretty well.


**Here's what you'll need if you want to use this.**

Clone this repository with git.

Then, install Anaconda python (or some other python distribution), if you haven't yet.

Then update iPython, from a cmd or bash prompt. 

If you're using Anaconda, the "conda" program will do this:
($ is just the terminal prompt, don't type that, and this assumes conda is on your PATH):

    $ conda update conda
    $ conda update ipython

The update of ipython may throw an error if you already have an MS Windows shortcut to ipython, but you can ignore that.

Then you can run the iPython server, in the cloned git directory. For me, that's:
   $ ipython.exe notebook

Note that this will serve up whatever directory it's in, so do this in a leaf directory that doesn't contain any sensitive files.

Your browser should open, and display the "files" directory, which contains the images, and the "MMDS-001 Homework.ipynb", which is the notebook. Click on the notebook to open it.

When you open it, all cells will be in display mode, double click any cell to put that cell into edit mode.

You can also "File|Download As..." to download the notebook as pure (uneditable) HTML. Download it to that files directory (so it finds relative path to the images), and then open the downloaded file in your browser, to see the uneditable version.

I recommend creating a second branch to fill in the answers. Please don't distribute your answers on github or elsewhere, that's
a disservice to other students or potential future students.


Thanks,
TP Diffenbach