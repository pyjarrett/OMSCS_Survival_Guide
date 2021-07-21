# How OMSCS Works

Georgia Tech's OMSCS might be online, but these are campus level of difficulty
Master's courses.  Georgia Tech does a good job reinforcing its reputation while
offering these distance courses.

# Prepping for the Semester

Classes typically have a list of recommended skills and background listed on the
appropriate OMSCS page.  Read this and get an overview on the main stuff.

Do not avoid classes or specializations because you don't know a particular
programming language.  It baffles me that people do this and it physically pains
me whenever I see a Reddit post of someone trying to do this.  If you stop
learning new languages and tools, you will make yourself obsolete.  Play around
on [HackerRank](https://www.hackerrank.com/domains) or set up a test environment
and learn about the language your class uses before class starts.  OMSCS is an
engineering program, and engineering is applied program solving.  In computer
science, the most direct way of doing this is by writing computer programs.

# Time Considerations

Since this is a Master's level program, expect to put in a Master's level of
work.  I know a guy in a different program at a different school who describe
his program as, "I did almost nothing and got a 4.0".  This is not that program. 

I plan my class schedule around major life events.  When I was getting out of
the Navy, I still took a course, but I picked one which had been reviewed to be
easier on the commitment side of the spectrum.

It turns out that changing jobs and trying to find a place to live while working
full time and taking only 3 credits is incredibly difficult.
During my 9 credit semester and also when I was taking High Performing Computing
Architecture, I did pretty much nothing else on nights and weekends during that
semester other than schoolwork.  However, because I planned the semester when I
would have that much time to invest, I managed to get everything done.

If you have a major life event (wedding, baby due, job change, etc.) I would
recommend taking 1 class less than you would otherwise think you could handle.
I would also examine the level of difficulty of course I would be picking  with
a lot more scrutiny.

Some courses are known to be "take only this course in a semester", such as:
computer vision, CCA (when it existed.), machine learning, and HPCA.  There are others.  If you
search for, or ask about your desired scheduled on the OMSCS Reddit, you
will get a lot of helpful suggestions about if you are taking too much.

# Lectures

As expected, there are lectures for each class.  Accompanying this is typically
some sort of "recommended schedule" so you stay up to date with the knowledge
required for your assignments and projects.  Some classes require you to
actually complete all of the online quizzes and others don't.  If your class
doesn't, I like to download all the lectures from the Udacity page so I can
watch them repeatedly without interfering with my Comcast data cap and dealing
with internet buffering.  While working on projects, I typically listen to the
lectures in the background.  Over, and over again.  I've also found that a
downloaded lecture on VLC is quicker to search than the online lectures.

Typically the "recommended schedule" has a list of the number of hours of video
each week, which will help you in your pacing.  If not, a student will typically
create one.  Keep in mind that assignments will only add onto this time for
lectures.

I take notes during the lecture and treat it no differently than if I were in
the classroom.  While I listen to the lectures while doing projects, I first
actually watch the lectures and take notes and do the quizzes.  It takes more
time, but since I am a super strong visual and auditory learner, so I retain it
better.  In the end, I believe that it saves me time.

## Class forums


Students post really useful things like IDE recommendations, useful 3rd party
libraries, documentation links, and (when allowed) unit/integration tests.
Professors/TAs will post assignment updates and clarifying information.
Typically, asking a question at least one day before an assignment is due will
get you an answer.  Also, it seems like TAs and Professors respond better if you
are asking questions early and being active.  The earlier the better, and you
can definitely tell if you are ahead or behind on an assignment based on the
number of posts and the amount of general activity.

When you get stuck or tired of an assignment, just check the class forum posts.
There's probably a missing requirement or clarification you need that someone
else has asked about that has already been answered.  Or, you might need to be
the person who asks for clarification.

Foster the community, since your fellow students will be awesome.  I
would call out names here of awesome folks I've gotten to work with, but there's
too many names and not enough space to list them here.

## Submitting Assignments

After you submit, you can go onto and download the
documents/files you submitted.  I download what I submitted, create a clear
environment and make sure my code works (my own unit tests pass) and that it's
the right version of the appropriate documents.

# Getting Stuff Done

## Virtual Box and VMs

Most classes provide a completely packaged virtual machine (VM) which will run
on [VirtualBox](https://www.virtualbox.org/) or a similar platform.  This saves
you the headache of trying to set up your own environment to work on assignments
for class.  However, these will to be significantly slower than working on your
computer normally.

If you are willing to spend the time to create your own environment, doing that
will speed up your ability to work on projects.  This is typically what I have
done. However, I also maintain a VM ready and test my code on my native machine
and the VM.  git (see below) integrates very well with this workflow, as it only
requires a `git pull` on the VM from the repository to bring everything there
back up to date.

## Linux and Command Lines

If you are scared of a command line, during the semester for some courses is not
the time to try to "figure it out."  You don't need to be a bash expert, but if
you're not at least familiar on the surface with basic Linux tools
(git, grep, less, find, etc.) for most classes, you are in for a hurtful
awakening.

If you have never programmed on Linux and your class requires it, you should
also at least attempt it before the semester.  Windows users can conveniently do
this by downloading an appropriate Linux image and running it with VirtualBox.
Mac users can just do a spotlight search for "Terminal" and they are good to go.
Technically Mac provides BSD-style commands/programs, but most of it is the same
or very similar to Linux/GNU style commands/programs.

_Just go to [HackerRank](https://www.hackerrank.com/domains), and do the "Linux Shell" challenges._

Windows users can now take advantage of a partial Linux experience using the
Windows Subsystem for Linux (WSL).  [Cmder](https://cmder.net/) is a good
alternative which comes with a lot of things bundled.

## IDEs/Editors

Know the basics in at least one command line text editor.  I use Vim, but it
takes a while to get familiar with.  Once you do, it can be quite powerful.
There are Vim reference cards you can print, in addition to there being a lot of
in-depth help built directly into the program.  If you don't have this
experience, often a group of students figures out how to get an IDE to perform
well enough to be useful on the VM.

I'd highly recommend trying out JetBrain's IDEs, and seeing if they offer the
student version for OMSCS.  I keep a full subscription because I do a variety of
hobby and professional work and find it well worth the price.  These IDEs work
well on Linux and Windows.

Visual Studio Code is a free alternative which is very popular and available for
all platforms.  This is what I'd recommend on Windows if you're not using a
JetBrains IDE or need a general purpose editor.

I'm not out to create a laundry list of editors--these are the three I'd
recommend.

## Source Control

If you post a public source control
repository for a class, you can, and probably will, be prosecuted for honor code
violations.  Additionally, it prevents you from losing your work when your
computer hard drive inexplicably dies days before an assignment is due.
[Bitbucket](https://bitbucket.org/), [GitLab](https://about.gitlab.com/)
and [Visual Studio Team Services](https://beta.visualstudio.com/visual-studio-team-services-vs/)
(recommended by Bill M.) are
also alternative options.

If you have no idea what git or source control are, I highly recommend learning
git for [free online](https://git-scm.com/).  It will make you more productive and also more attractive
for a job as nearly every company uses some form of source control.  There's
nothing more frustrating than not working under source control, and not being
able to track down a bug because you don't remember all the places you've change
since the last time something worked.  As you get more advanced with git, there
are [really good tools to learn](http://ndpsoftware.com/git-cheatsheet.html#loc=workspace;).

Every project I've started begins with creating a private repository.
After this, everything that I do for that
project goes into source control.  Everything.  EVERYTHING. I really hope my
point is clear.  PUT EVERYTHING IN SOURCE CONTROL.  Bookmarks of websites or
other resources get put into a resources.md (md is for markdown).  The unit (and
sometimes integration) tests that I write.  The assignment specification and
other documents and resources provided for the assignment.  My code goes in
source control, as do my report's LaTeX files (see below section on LaTeX).  The
only thing you shouldn't put in source control is any file that you can generate
from another file (e.g. JavaDocs, Sphinx Docs, .pyc files, C++ \*.o files, things
created by CMake, etc.) and you should have these on your [.gitignore](https://git-scm.com/docs/gitignore)
anyways.

If you are on a group project, you will almost undoubtable use git.

**If you are working by yourself, you should just use git anyways.**

## LaTeX (Mac and Linux)

If you are really crafty, you can merge the "source control" and the "command
line" recommendations above by doing your reports in [LaTeX](https://www.latex-project.org/).
Think of LaTeX as HTML or Markdown for documents, but it can create PDFs.  It's
not trivial to do so, but it helps when you add things to a report to be able to
have a history of your document and be able to verify the changes.  `git diff`
is built into my workflow, even that around documents, so I always check my work
to see that I'm putting in my source control repository only the things that I
expect should have changed.

I have a template LaTeX document with specific customized commands and  reuse
that document as a starter for all my reports.

Tad M. recommends trying Markdown for simple things viewed on Github.  [Pandoc](http://pandoc.org/)
is
an option to convert [Markdown to PDF](http://www.mscharhag.com/software-development/pandoc-markdown-to-pdf).
I've never looked into this before, but
since Markdown has more natural syntax, I might be trying that in future
semesters.  Abhishek T. and Adam A. recommend [Knitr](http://yihui.name/knitr/) 
which supports [Python](https://github.com/janschulz/knitpy).
[Jupyter Notebooks](https://jupyter.org/) are another alternative that I've used which lets you put
executable Python inline with your report and generate images generated by
Python inline, while exporting to PDF.

## Makefiles (Mac and Linux)

[Makefiles](https://www.gnu.org/software/make/manual/make.html#Introduction) are
a really easy way to manage file dependencies and set up commands
that you run over and over again ([bash scripts](http://tldp.org/HOWTO/Bash-Prog-Intro-HOWTO.html)
and [aliases](http://tldp.org/LDP/abs/html/aliases.html) 
are the other option
for routine complex commands).

I set up Makefiles to do lots of things listed above.  Building pdfs and don't
want to retype that command to build it again?  Add it to the Makefile.  Want to
rerun your code and rebuild your pdf from LaTeX with the new images when you
update your project.  Make your PDF make rule depend on your source files!
LaTeX really takes the cake away from MicrosoftWord or MicrosoftPowerPoint, or
OpenOffice, or Apple's Pages here.  Since LaTeX only consists of text and hence
doesn't embed the resources in the document, you can have your code generate new
output and then rerunning LaTeX will cause those new resources (i.e. images) to
be updated in the newly created PDF.

## Unit Test

Unit testing is pretty ubiquitous for development these days.  It is nice to
have unit tests set up so that I can run a quick make command (or run the "test"
button in an IDE) to get a good picture of where I stand and that I don't have a
test which has discovered I have broken anything.  When you have tests a button
press or a make command away, there's no excuse not to use them, especially when
you have the time.

One of the first things I do in any new programming environment is to figure out
how to get unit testing working.  In Java you have [JUnit](http://junit.org/junit4/)
and in Python you have
[unittest](https://docs.python.org/2/library/unittest.html) (yes, that's 2.7
documentation because that's the Python version I've
used in every class) or [nose](http://nose.readthedocs.io/en/latest/testing.html).

I do a lot of unit and integration testing as anyone can do very silly mistakes
in code sometimes, especially late at night on pressure to hit a deadline.  I
had a ridiculous time in Pandas dealing with similar functions that return
different types depending on how they're called.  Unit tests help you think
through the problem and design your code to be modular.

## Assignments

Start early!  Since I am a tortoise, I typically start the day the assignment
comes out, and I slowly plod along through assignments and finish them through
sheer force of will.

Read the specification at least three times from beginning to end before you do
anything.  I forget which class posted a link to [this paper](http://ccr.sigcomm.org/online/files/p83-keshavA.pdf),
and it's not a directly translation for specifications, but the idea of reading
at incrementally lowering  levels of abstraction has validity.  While in a rush
due to personal schedule constraints, I lost about 10% on a recent assignment
because I "didn't have time" failed to read the specification completely and
sufficiently.

"If I had an hour to solve a problem I'd spend 55 minutes thinking about the problem and 5 minutes think about solutions." - Albert Einstein

Develop a schedule and milestones from the specification, noting that you should
expect to spend about 80% of your time, on the last 20% of the project.

## Schedule

Keep a bedtime.  Eat dinner with your family.  These things are important and
can be integrated into your life if you make time for them.  You do need to set
aside a schedule of when you are planning to work.  I find that my most
productive times are when the rest of my family is asleep.  The general
quietness helps me concentrate.  Additionally, I also tend to get very little
done during the afternoons on the weekend, so use them for family activities.  

Sometimes the best bridge between hope and despair is a good night's sleep. - a really smart fortune cookie

Consistence of doing things over time is worth 1000 times more than trying to do
everything at once.  There is simply too much to do it all at the end.  The work
you get during the semester is like butter on bread, it's just asking to be
spread out.  Work a little bit every night and keep an eye on where you are on
an assignment versus the due date.

## Proctored Exams

I really like to build things, and I've already taken many, many exams for
certifications/qualifications in the Navy so I try to avoid them by taking
project-based class.  Sometimes, they are unavoidable, so you need to take
proctored exams.

All of the proctored exams systems are terrible by definition: You are going to
be very stressed when taking each exam, so expect to be frustrated with the exam
system.  Check your hardware and software and do any "setups checks" with the
exam software that are offered as soon as it is available and ask for help if
your system doesn't work early on Piazza.

Block out at least 2 (I use 3) times as much time as you expect the exam to
take, and read the instructions about the proctoring thoroughly.  Exam set up
tends to be time consuming with identity verification, and waiting for a proctor
often taking quite a bit of time.  Before exams for Mac users: Disable Mac
notifications by holding Option and clicking on the notification button in the
top right of the full screen menu (the little outline button will turn gray when
disabled).  Also, ensure that you close all other programs and follow the
proctoring directions to the letter.

Take the exam from a place with good internet.  I don't know why some proctor
software thinks I want to see the proctor in 1080p, but some of them use very
high resolution video of the proctor (in addition to you, but that part makes
sense).  This eats your connectivity, so you often need pretty good connectivity
to take exams (in my experience).  From Romeo C.: "[Georgia Tech] ha[s] moved
away from ProctorU which works with a live proctor; ProctorTrack just saves a
video while you take an exam, and its algorithms automatically flag your session
for revision if something seems odd."  I've gotten to use both: ProctorU took a
while to set up but was nice to have someone to answer questions or concerns
about the proctoring process; ProctorTrack never replied to any of my concerns
before, during or after my exams when I had issues with them.

Know what materials, notes, and calculator, you are allowed and not allowed to
use.  One Proctoring service prevented some students from using allowed notes!

If they complain about materials that you are allowed to use, ensure that you
voice your opinion and have them try to contact the professor.  In extreme
scenarios where the Professor and TAs could not be contacted, proctors have let
students take exams with the allowed notes anyways and took a record of what
materials they used and sent it to the Professor.

## Have a good time

You are trying to make yourself better by going to a graduate school.  It's
going to be hard, but that doesn't mean it can't be fun.  If you approach your
graduate life like drudgery, it will be happy to oblige and become that
drudgery.  If you view it as a fun and creative time and keep a relaxed pressure
on your work, you will find yourself having a fun and creative time.

Build rewards into your process.  I've always thought this was silly until I
actually started doing it.

# The "A"/"B" method.

Let's say you just want to get done with graduate school in the minimum amount of time.
You want to take the summers off so you get a break, but still want to get done quickly
in 5 semesters.  Enter: the "A" "B" method.  The idea of this is to take 2 classes per
semester and go for an "A" in one class and a "B" in the other.  The idea is to not stress
yourself out too much trying to get an "A" in both classes, while still finishing the program
as quickly as possible.  Keep in mind that to safely pursue this methodology, you should probably
go for the "A" in your specialization because you need to get at least a "B" in that course,
and go for the "B" in the class which you see as being easier or not in your specialization.
This way, if you get a "C" the class will still count.

WARNING: Note that if you try to pursue this method, you will likely lose much of your competitiveness
to get into PhD programs because you are sacrificing your GPA.  Also, you will probably get less out
of your courses by taking multiple at a time.

# I hope that covers it

If you have any other questions you want added onto this, just post below or
send me a message and I'll answer what I can.

Also, send in material if you have things I didn't think of that helped you and
I'll add them with appropriate attribution.
