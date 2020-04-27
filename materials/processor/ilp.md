# Instruction-Level Parallelism

![An ancient XKCD](https://imgs.xkcd.com/comics/paths.jpg)

## Static ILP

**READING:** *Computer Organization and Design* Section 4.10

### Instruction scheduling **VIDEO**

{% include video.html id="0_h627dgvo" %}

This is a video on how to get parallelism by statically finding independent instructions and how to improve performance with static instruction scheduling.

### A new ISA type: VLIW **VIDEO**

{% include video.html id="0_cuql5qo6" %}

This video introduces VLIW ISAs and a little about how they work.

{% include video.html id="0_wk3y9639" %}

This video talks about their pros and cons.

#### A bit about Intel Itanium (a *real* VLIW design) **VIDEO**

Rather than listen to me talk about the history of the Itanium, let's go back to the Turing Lecture and have Dave Patterson explain why it failed!

<iframe width="608" height="402" src="https://www.youtube.com/embed/3LVeEjsn8Ts?start=1456&end=1643" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### **QUIZ** Static scheduling

[Use gradescope to take the quiz.](https://www.gradescope.com/courses/105214/assignments/474132)

## Dynamic ILP

**READING:** *Computer Organization and Design* Section 4.10

Now, can we do the same thing as we discussed above, but do it automatically in hardware?

### Dynamic instruction scheduling

#### A cool historical perspective

Optional **READING:** [*Dynamic Instruction Scheduling* Conway et al.](https://ai.eecs.umich.edu/people/conway/ACS/DIS/DIS.pdf)

DIS is one possible implementation of dynamic ILP.
It's one of the first descriptions of a hardware mechanism for ILP.
Interestingly, this idea was lost for decades.
Computer historians overwrote this history, and if you read your book or most other references it will say that the first algorithm for dynamically issuing instructions is Tomasulo's algorithm.

Norm Hardy said of DIS: "It was superscalar, and the instructions were rather simple -- it was the first design that I had heard of with the idea of issuing more than one instruction per clock cycle -- I can recall thinking that that was barely credible at the beginning. It turns out, in retrospect, to be the right way to build a machine. But I can remember being quite in awe of the very idea--in fact, I thought that executing one instruction per clock cycle was quite remarkable"

I strongly encourage you to read about [Lynn Conway's story](https://ai.eecs.umich.edu/people/conway/Retrospective2.html#anchor100470).
Her [website](https://ai.eecs.umich.edu/people/conway/) is a treasure trove of fascinating computer architecture history.
Not only did she likely invent the first method for out of order execution, but she essentially [started the VLSI revolution](https://ai.eecs.umich.edu/people/conway/Retrospective3.html#anchor42852) that was a major driver of Moore's Law!

She has some great talks that she's given as well.
If you have time, *please* check these out.
It's a great way to see some insight into the human aspects of computer science history.
[This video](https://youtu.be/7ncuhRYmfJw) is long, but similar to the talk she gave at Davis a couple of years ago.
At around the 20 minute mark is where she starts talking about computer architecture.

#### DIS details **VIDEO**

{% include video.html id="0_4z25jj2k" %}

This is a video introduces how to get parallelism by dynamically finding independent instructions.

{% include video.html id="0_f6gvn5wi" %}

This video describes an algorithm called DIS which can be implemented in hardware to decide which instructions are allowed to execute at any time.

## Register renaming **VIDEO**

{% include video.html id="0_9nplzxmb" %}

Finally, this video discusses how to overcome WAW and WAR hazards by using register renaming.

### **QUIZ** Dynamic ILP

[Use gradescope to take the quiz.](https://www.gradescope.com/courses/105214/assignments/474764)

[Next up: A summary of processor design.](./summary.md)
