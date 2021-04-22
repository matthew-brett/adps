**The exercise links in this page will not work correctly until 8am on Friday
23 April**

Like your exercises, this exam uses the R notebook.

Please fill in the notebook and submit it.

You have 24 hours to work on the notebook, but we estimate that it should take
you about 90 minutes if you have done all the exercises and tutorials from the
course.

Feel free to look for solutions online, but of course, do not share answers with any other student, or ask anyone else what the answers are.  This must be your own work.

There are various points in the notebook where a wrong answer in one chunk will
lead to wrong answers in later chunks.  For this case, please do your best to
work out what the later chunks should be.  We will give you due credit for
later answers that are correct, even if the earlier variables etc are wrong in
your notebook.

We highly recommend you start this notebook early in the day so you can test
the initial load of some libraries.  You will see what we mean when you get to
the notebook.  These libraries should be installed from your work on the
exercises during the sessions, or your catch-up after the sessions.  If they
are not installed, install them with the instructions given, or switch to the
cloud.

## Doing the exercise

You can do the exercise on your own computer, or on the [R in the
cloud](../pages/R in the cloud) system.

## On your own computer

Next go to [this
link](https://github.com/uob-cfd/delhi_air/archive/master.zip) to
download a Zip file with the exercise files.

*Unpack the Zip file* to some sensible place on your computer, such as your
Desktop.  *Please don't forget to unpack the zip file*.  This is especially
easy to forget on Windows.  On Windows, make sure, when you open the Zip file,
that you run "Extract All" on the Zip file to extract its contents, and you
then use the extracted files.

Open RStudio, and then use the File - Open File ... option to open the
`delhi_air.Rmd` file.  This is an R notebook.

Fill in the notebook, following the instructions.

Use File - Save to save the notebook when you have finished.

Submit the saved `delhi_air.Rmd` file here on Canvas.

## On the R in the cloud system

Click on the link below to go to the exercise in the [R in the
cloud](../pages/R in the cloud) system.

[Exam notebook
link](https://uobhub.org/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fuob-cfd%2Fdelhi_air&urlpath=/rstudio)

You will be working on the file `delhi_air.Rmd` in the `delhi_air` directory.
See [Work on exercise in R cloud](../pages/work-on-exercise-in-r-cloud) for the
steps to open this file.

Read the instructions in the `delhi_air.Rmd` notebook and follow them, to fill
in the notebook.

When you have finished, don't forget to [save your
notebook.](../pages/work-on-exercise-in-r-cloud).

Then, [download your saved notebook \".Rmd\" file from the R
cloud](../pages/download-from-r-cloud), and submit the notebook here.

## Problems with the exercise when working on your own computer

Some of you are getting the following error message, when you try to load the data file in the notebook:

```
cannot open file 'new_delhi_air.csv': No such file or directoryError in file(file, "rt") : cannot open the connection
```

This happens when, for whatever reason, the file `new_delhi_air.csv` is not in
the same folder as the notebook `.Rmd` file.  There are two common ways this
happens:

### You did not extract the files from the Zip archive on Windows

The exam is in a Zip archive (`.zip` file).  By default, if you open this
file on Windows, Windows Explorer will show you the Zip file interface.  This
shows you the files in the Zip archive, and allows you to open the files
*within the Zip archive*, but it does not *extract the files*.   You need to
*extract* the files from the Zip archive in their own directory, using the
Extract option in the interface.   Then you should open the *extracted* version
of the notebook.  If you do not do this, and you are working on the notebook
file inside the Zip archive, then you will not have the data file
`new_delhi_air.csv` in the same folder, and you will get the error above.  To
fix, close the notebook file you are using, make sure you have extracted the
Zip archive, and make sure you are using the extracted version of the notebook
`.Rmd` file.

### You tried downloading your notebook again from Canvas

Another common reason for this error, is the situation where you filled in the notebook, and everything was working, then you saved the notebook, and submitted via Canvas.  Just to check your submitted file is OK, you download it again from Canvas, but then you run it and get the error above.

The error is because your newly downloaded copy is in a different folder from
your original copy. For example, your new copy might be in your `Downloads`
folder. This folder probably does not contain the `new_delhi_air.csv`
file.   You don't need to fix this - as long as the file that you submitted
works, when you run in its original location, you will be fine, because, when
we mark these files, we make sure the data file is available in the same
folder.  But, if you want to be super-sure, then copy the
`new_delhi_air.csv` file from its original location to the folder containing
your newly downloaded copy of the notebook (such as `Downloads`), and try
running the notebook again.

## Any other problems, on your computer, or on the cloud

Any problems, please email <m.brett@bham.ac.uk>.
