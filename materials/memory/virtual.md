# Virtual Memory

Virtualization and virtual memory enable multiple processes to *share* a single set of hardware.
Without hardware support for these software mechanisms, we wouldn't have wide-spread computing today!

![xkcd on virtualization](https://imgs.xkcd.com/comics/xkcde.png)

## Reading for this section

*Computer Organization and Design* Sections 5.6,5.7

## Virtualization

**READING:** *Computer Organization and Design* Section 5.6

Before diving into the hardware and software mechanisms behind virtualization, I want to give a bit of motivation for virtualization generally.

{% include video.html id="0_x6tdfp5g" %}

This video talks about why we want virtualization and how processors are virtualized.

## Virtual memory

**READING:** *Computer Organization and Design* Section 5.7

{% include video.html id="0_sajt6ufo" %}

This video introduces virtual memory and discusses segmentation as a mechanism to implement virtual memory.

### Page-based virtual memory

{% include video.html id="0_zruofsyl" %}

This video goes back and talks about more motivation for virtual memory and introduces page-based virtual memory.

{% include video.html id="0_b1n20i91" %}

This video shows an example simple page table implementation: A flat page table.

### **QUIZ** Introduction to virtual memory

[Use gradescope to take the quiz.](https://www.gradescope.com/courses/105214/assignments/510207)

### Multi-level page tables

{% include video.html id="0_7tgkv2oo" %}

This video talks about the downsides of a flat page table and motivates a multi-level page table design.

{% include video.html id="0_omnfnp31" %}

This video discusses how the actual RISC-V and x86 page tables are implemented.

{% include video.html id="0_pfhi6wm6" %}

This videos extends the two-level page table for rv32 to 3 and 4 levels for rv64 and x86.

## Performance and virtual memory

{% include video.html id="0_0knma2rd" %}

This video discusses how to access memory now that we're using virtual address translation and the main performance overhead: walking the page table.

{% include video.html id="0_4s9hkfr8" %}

This video discusses a cache structure for virtual address translation: the TLB.

{% include video.html id="0_juu68l8l" %}

This video covers other virtual memory optimizations such as huge pages.

### **QUIZ** Multi-level page tables and TLBs

![under construction]({{ "/under-construction.png" | relative_url }})
[Use gradescope to take the quiz.](https://www.gradescope.com/courses/105214/assignments/)

## Virtual virtual memory

This section is *optional* and will not be on any quizzes or the exam.
However, I think it's important to talk about virtual machines and hypervisors as many of you will use these systems.
Understanding how they work and how the hardware handles virtualization is key to getting good performance on the cloud or on VMs on your desktop.

![yo dawg meme](xzibit.jpg)

{% include video.html %}

This video discusses virtualization and its impacts on virtual memory and performance.

[Next up: Memory system summary](./summary.md)
