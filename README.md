Objectives
==========

This lab serves as the starting point for the hands-on portion of
IS6481. In this lab, we will set up each of the technologies used in the
class. All of the technologies used will be cloud-based, however, some
downloads will be helpful in working with some of these. It will be
noted below when a download will be helpful.

I have attempted to do exercises in the same order presented in the
text. Unfortunately, this is not possible for all of the labs. The text
starts at the strategic level and works backward to technology. This is
the corret thing to do in real life, but is not optimized for doing labs
in the class. You’ll see what I mean when you get there. This lab will
outline each of the systems we’re going to use and will provide
resources for further reading. Information from labs will be included in
quizzes, so please pay close attention to the material in this (and
other) labs.

### Git/GitHub

Git is a version control system. If you haven’t heard of this it
probably means you haven’t done any software development in the last two
or three years (which is totally fine, BTW). Version control systems
track changes to a file or set of files over time. This allows for
experimentation with those files as changes can be rolled back to any
prior version. It is incredibly useful when developing software and, as
we’re finding, doing analytics work.

Git will not be used a ton in this course, except to be a place I can
manage and share the materials for the course. I’m mentioning it here
because it is a terribly important technology that is used in analytics
(and software development) today. Also note that some of you may want to
work locally for a few of the labs and that can be done easily by
checking out the code from GitHub (here: <https://github.com/is6481>).

Please watch this [video](https://www.youtube.com/watch?v=BCQHnlnPusY)
as an introduction to Git and GitHub.

It can be easier to interact with GitHub by downloading [GitHub
Desktop](https://desktop.github.com/) This is optional.

### Domo

Domo is a cloud-based data warehouse and data visualization platform
(disclosure: I work for Domo in my real life). We will be using Domo for
a handful of exercises as we can model how data moves from a database or
data warehouse, through ETL processes and ends up in a front-end system.
Domo also highlights some of the advancements discussed in the text
especially around the ability to search for data, the ability to create
alerts, and the ability to have reports sent at specified intervals
(this will make sense as we go through the course).

You can sign up for a student version of Domo
[here](http://www.domo.com/start/student). You will have access to a
current version of Domo for one year. Please be responsible regarding
what data you upload to Domo.

### R/Rstudio Cloud

We will use RStudio this semester for two predictive projects/labs. R
Studio Cloud is a great product that allows me visibility into your
work. I’ll have the two assignments there and will be able to see your
work w/o the need to transfer files back and forth.

Sign up for your account and access to our workspace
[here](https://rstudio.cloud/spaces/20344/join?access_code=2HCnR%2B%2BP8WRCAJOTqOqRrGGEYh4FUi0oWGhIt%2FNb).
There will be a longer introduction to R Studio when we get there later
this semester.

### AWS

Amazon Web Services is the best/most popular cloud service provider. AWS
provides everything from simple servers to more complicated machine
learning capabilities. It is possible to run all of your IT operations
on the AWS platform and many of your favorite products run on AWS
(Netflix and Uber come to mind).

You should have recieved an email from AWS and a note via Canvas from me
regarding signing up for our AWS classroom. Follow the prompts to sign
up for the student version of AWS.

Please watch this [video](https://www.youtube.com/watch?v=qcY-uiEHhn0).
This video is quite basic, but does a great job introducing cloud
computing concepts.

We will be using MySQL databases hosted on AWS this semester. Later in
the semester it might be helpful to use a SQL development environment.
More details to follow later in the semester when needed.

Summary Instructions
====================

For Lab 1 do the following.

-   Git/GitHub
    -   Watch this video: <https://www.youtube.com/watch?v=BCQHnlnPusY>
    -   Be prepared to answer questions in Quiz 1.
-   Domo
    -   Go to <http://www.domo.com/start/student> and sign up for an
        account
    -   Watch the “Getting started with Domo” video
    -   Go to the following Google Form and fill in the fields:
        <https://forms.gle/dY2kph4bg9meAXNn8>
        -   To get the Access Token, do the following.
            -   Click the waffle menu in the top right (to the left of
                your profile image).
            -   Click Admin
            -   Click Security
            -   In the top right of the screen, click “Generate access
                token”
            -   Description = Instructor creds, User = your user
                account, Expire after = 90 days
            -   Paste the access token into the Google Form above
        -   To get the developer tokens, do the following.
            -   While you’re logged in to Domo, go to
                <https://developer.domo.com>
            -   In the top right, click My Account
            -   Click New Client
            -   Name it “IS6481 Grading”
            -   Click all options under scope
            -   Click “Create”
            -   Enter the information in the Google Form
-   R Studio Cloud
    -   Go to the following link: [link much too
        long](https://rstudio.cloud/spaces/20344/join?access_code=2HCnR%2B%2BP8WRCAJOTqOqRrGGEYh4FUi0oWGhIt%2FNb)
    -   Watch the video I will create for an introduction to R Studio
-   AWS
    -   Follow the instructions in the email you recieved to setup your
        account with AWS Educate.
    -   Note that you will be allocated enough credits to complete
        projects for this course. In fact, there will likely be more
        credits in your account that we need for the course. If you
        would like to play around with other technologies not covered in
        the course, feel free, just be careful you don’t use up all the
        credits before you’ve finished the assignments.
-   To get credit for the assignment, copy the URL from your Overview
    page in Domo and submit it as proof you have completed all steps.

After you have completed these exercises, refer to lecture notes for
what topics will be covered in quiz 1.
