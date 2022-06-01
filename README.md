Activity 5 - Data Summarization
================

It is assumed that you have read Sections 5.5 - 5.6 from R4DS and
completed the Derive Information with dplyr Primer.

In this activity, you will:

-   Produce numerical summaries of variables using `{dplyr}`.
-   Produce numerical summaries of variables by a grouping variable
    using `{dplyr}`.
-   Compute new variables in a dataset using `{dplyr}`.

## ☑️ Task 1: The Workflow

**You may need your PAT that you created in Activity 1**. If you
misplaced this token, you will need to create a new one prior to
beginning the steps below. You can do this by going back to your
Activity 1 repo and look at Task 4 or go to my repo’s [Task
4](https://github.com/gvsu-sta518/activity01-rmarkdown#%EF%B8%8F-tasks-4-connect-rstudio-and-github).

Remember to take these steps slowly, help each other out, and get a hold
of your instructor when you have questions or issues.

1.  In this GitHub repo, click on the ![fork](README-img/fork-icon.png)
    **Fork** icon near the upper-right-hand corner. You should be taken
    a copy of this repo that is in your GitHub account - your page title
    should be `username/activity05-data-summarization`, where `username`
    is replaced with your GitHub username.
2.  Click on the green **Code** button.

-   Verify that the drop-down identifies that you are using the
    **HTTPS** method (this is *probably* the default view; otherwise,
    select “HTTPS”).
-   Click on the ![clipboard](README-img/clipboard-icon.png) icon to
    copy the repo HTTPS information.

3.  Log in to the [RStudio Workbench](https://rstudio.gvsu.edu/).

-   Verify that you are in an RStudio session (it doesn’t matter if it
    is a previous Project session or a “vanilla” RStudio session).

4.  Create a new Project. You can do this by clicking on the
    <img src="README-img/new-project-icon.png" alt="new project" width = "20"/>
    icon or through the menus (File > New Project…).

-   In the *New Project Wizard* pop-up, select **Version Control** on
    the *Create Project* screen, then select **Git** on the *Create
    Project from Version Control* screen.
-   On the *Clone Git Repository* screen, paste the HTTPS information
    from (2) into the *Repository URL* dialog box. It should look like:
    `https://github.com/username/activity05-data-summarization.git`
-   The *Project directory name* dialog box should automatically
    populate with your repository name, but sometimes Macs have an issue
    with this (if so, click into this box and press the ![command
    key](README-img/command-key-icon.png) command key on your keyboard).
    It should look something like: `activity05-data-summarization`
-   In the *Create project as subdirectory of* dialog box, click on
    **Browse**.
-   In the *Choose Directory* pop-up, navigate to your class-level
    folder (i.e., you were encouraged to create a folder named either
    `STA418` or `STA518`) You were also encouraged to create
    an`activities` folder within your class-level folder to help
    organize our materials. Once you have navigated to the folder you
    wish this repo to be located, click **Choose**.
-   Verify that the *Create project as a directory of* dialog box
    contains the folder location that you previously specified, then
    click on **Create Project**.
-   You may be asked to login with your GitHub credentials on a *Clone
    Repository* pop-up window. Provide your GitHub username and PAT (not
    your GitHub password) if prompted.

6.  After a few seconds, your RStudio session will refresh and you
    should be in your newly created RStudio Project!

Note that beginning in Activity 7, I will be no longer provide these
full steps and will instead be saying:

> ![fork](README-img/fork-icon.png) **Fork** this repo and clone it to a
> new [RStudio Project](https://rstudio.gvsu.edu/).

Remember that more detailed directions are provided in this Activity - I
will note/link this in activities after this switch.

<img src="README-img/noun_pause.png" alt="pause" width = "20"/>
<b>Planned Pause Point</b>: If you have any questions, contact your
instructor or another group.

## ☑️ Task 2: Complete the RMarkdown File

The `activity05-data-summarization.Rmd` file contains the directions for
this activity. For the rest of this class period, you will complete the
RMarkdown document with your neighbor(s). Your instructor will be
circling and be available to help when needed.

Note that each person is working in their own repo. We are not worrying
about collaborating for the time being and instead will be working on
being more comfortable with the workflow for working between RStudio and
GitHub.

However, do not continue in this README document until you and your
neighbor(s) have completed your `.Rmd` files.

![Work Work
Work](https://media.giphy.com/media/SATgMmr1Sdawhp1CkN/giphy.gif)

## ☑️ Task 3: Reflection

We now have a number of skills to help us explore datasets. Before we
add too many more tools/skills, we should verify what we have currently
learned. Look at the [Course
Objectives](https://docs.google.com/document/d/17CTL6DJYZfn2aqE1PQqJ84yiaY6XBbb_Sz7momwuL_8/edit?usp=sharing)
that we came up with at the beginning of this semester. Take 5 minutes
to identify which of these you feel comfortable with. How could you
demonstrate what you have learned?

Now, think back through the 5 Activities that we have completed. What is
still not clear? What will you do to better understand these tricky
items?

**Next**: Activity 6 will focus on restructuring data to be easier for
humans to read or easier for computers to handle.
