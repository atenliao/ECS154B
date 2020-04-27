# Welcome to Computer Architecture (ECS 154B)

![SMBC comic](https://www.smbc-comics.com/comics/20110217.gif)

First of all, welcome!

Welcome to the online-only version of UC Davis ECS 154B Computer Architecture in Spring Quarter 2020!
This is going to be a *unique* experience as we all try to figure out how to best interact in an online-only format.

My goal with this class is to encourage as much participation and interaction as possible.
I learn best from interacting with others.
So, I'm going to provide you with as many ways to interact with me, with our TA (Julian), and each other as possible.

## What is this class? **VIDEO**

Here, we find our first video.
Throughout these materials, there will be embedded videos for you to watch.
These will be taking the place of in-person lecture.

{% include video.html id="0_7u0bggal" %}

This video welcomes you to the class!

Usually, these videos will be 5-15 minutes long so that you won't be overwhelmed.
After each video, there will be a short Canvas-based quiz to check your understanding.
There is more information about quizzes [below](#quizzes).

## Class organization **VIDEO**

{% include video.html id="0_mz0h7c8r" %}

Video describing the class organization.

{% include video.html id="0_ui4epr3t" %}

Oops, I forgot somethings.
Another video describing how to use videos.

As previously mentioned, this class will be all online.
For details of the class policies, see the [syllabus](../../syllabus/syllabus.md).
Below, I'll briefly discuss some of the changes from a normal "in-person" class.

### **Quiz** Just testing you

[Use gradescope to complete the quiz.](https://www.gradescope.com/courses/105214/assignments/414482/)

### Lectures

Instead of in-person lectures, all of the content that I will be delivering will be through this website and videos.
You can find all of the videos on [this playlist](https://video.ucdavis.edu/playlist/dedicated/0_8bwr1nkj/) on [Aggie Video](https://video.ucdavis.edu/).

Most of the content will be via the video lectures since this is a high bandwidth way for me to deliver content.
However, there will also be links and further explanation written to go along with the videos.

### Quizzes

There will be a short quiz after each video to help promote learning through this asynchronous medium.
You can take these quizzes as many times as you like.
The quizzes are due every couple of days, kind of like a normal lecture.
There is no late penalty for quizzes, so if something comes up, you can take the quiz after you have found time to watch the video.

I think you'll learn best if you complete the quiz, then come back later and fix any errors you may have made.
Therefore, when you submit your quiz, you will not immediately see what you got right and wrong.
*When the quiz is due,* you will see all of the correct and incorrect answers.
At that time you can go back and update any questions you got wrong for full credit.

Note: quizzes are due when we would have been covering those topics in "real" lecture.
By doing the quizzes before the due date (or on the day it's due) you will make sure that you're keeping  up with the course.

Quizzes will close even to late submission 1 week after they are due (except for the first week's quizzes).

More information about the quizzes can be found [on the syllabus](../../syllabus/syllabus.md#quizzes).

### Discussion

Not only will I be presenting lectures asynchronously through video, but discussions will also be online.
We will be using [Zoom](https://zoom.us/) for discussion groups.

I'm going to try something different for lecture/discussion.
Since this is all remote, I don't believe that synchronous lectures make sense.
Instead, all lecture material will be available asynchronously as video/text on the [website](https://jlpteaching.github.io/ECS154B/).

However, I do think that some synchronous communication is important!
Thus, I'm going to convert all lectures/discussion into small group discussion sections.
There will be 6 sections each week and each section will be 40 minutes.
Most of the discussion section times are during our scheduled lecture/discussion times, but I've also included one evening time for those of you that have to work or take care of family members during the day.

Attending discussion is *required* (see [participation on the syllabus](../../syllabus/syllabus.md#participation) for more details).
However, you're only required to attend one discussion time each week.
I would prefer you to attend the same one each week, but it's not required.

The details about the discussion sections can be found [on the syllabus](../../syllabus/syllabus.md#discussion).

As always, let me know if there are any questions/comments!
This is something new to all of us, and if it doesn't work out, we'll try something new :).

### Project

Throughout this class you will be designing the *Davis In-Order* CPU or [DINO CPU](https://github.com/jlpteaching/dinocpu-sq20).
The DINO CPU assignments will roughly follow lectures.
You can find more information, and all of the assignments, on the [DINO CPU repository for Spring Quarter 2020](https://github.com/jlpteaching/dinocpu-sq20).

The [first assignment](https://github.com/jlpteaching/dinocpu/blob/master/assignments/assignment-1.md) is an introduction to [Chisel](https://www.chisel-lang.org/) which is a *language* for *constructing hardware*.
Chisel is essentially a programmatic version of [Logisim](http://www.cburch.com/logisim/).

The [second assignment](https://github.com/jlpteaching/dinocpu/blob/master/assignments/assignment-2.md) has you construct a full CPU which can execute almost any RISC-V program.

The [third assignment](https://github.com/jlpteaching/dinocpu/blob/master/assignments/assignment-3.md) extends this design with pipeling to improve the performance of applications.

In the [fourth assignment](https://github.com/jlpteaching/dinocpu/blob/master/assignments/assignment-4.md) you will further extend the pipelined DINO CPU design to handle a realistic memory and perform some experiments to evaluate the performance of different designs.

The [fifth assignment](https://github.com/jlpteaching/dinocpu/blob/master/assignments/assignment-5.md) has not been decided, yet.

### Tests

There will be three tests this quarter.
The tests will be after each of the three main modules, [processor architecture](../processor/index.md), [memory architecture](../memory/index.md), and [parallel architecture](../parallel/index.md).

More information on the tests can be found [on the syllabus](../../syllabus/syllabus.md#tests).

### Books

There are two books for this class.
The lectures and reading will be from *Computer Organization and Design RISC-V Edition: The Hardware/Software Interface* by D. A. Patterson and J. L. Hennessy.
This book is available on Canvas (for a price).
You may also have luck using Google to find the book.

**IMPORTANT:** The textbook on Canvas/vitalsource is *opt out*.
Thus, if you don't want to be charged for the textbook you must *opt out* by 4/16/2020!

I have also suggested that you get *The RISC-V Reader: An Open Architecture Atlas* by David Patterson and Andrew Waterman.
I find this book to be a very useful reference while developing the DINO CPU.
However, all of the information in this book can be found for free in the [RISC-V specification](https://riscv.org/specifications/isa-spec-pdf/) although the specification isn't as easy to read.

[Next up: Computer Architecture and Security.](./security.md)
