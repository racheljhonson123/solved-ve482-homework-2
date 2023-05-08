Download Link: https://assignmentchef.com/product/solved-ve482-homework-2
<br>
<strong>Ex. 1 — </strong><em>Multiprogramming</em>

A few years ago when computers featured less RAM it is was common to increase it in order to enhance CPU performance. In order to better understand the link between the two we now create a simple model for multiprogramming. We assume all the processes to be similar and spending the same fraction <em>p </em>of their time waiting for Input/Output (I/O) to complete.

<ol>

 <li>What is the probability for <em>n </em>processes to be waiting at the same time, then express the CPU utilisation as a function of <em>n</em>?</li>

 <li>Sketch the curve representing the CPU utilisation as a function of the number of processes for the following values of <em>p</em>: 25%, 60% and 90%.</li>

 <li>A certain old computer has 256 MB of RAM, once loaded a light operating system uses 96 MB of RAM. Several programs are launched each of them using 48 MB.

  <ol>

   <li>How many processes can be store simultaneously in memory?</li>

   <li>Assuming an average of 90% I/O waiting time what is the CPU utilisation?</li>

   <li>What is the effect of adding 256 MB, 512 MB and 1024 MB of RAM. Argue on which amount would be the most beneficial and would be worth the investment.</li>

  </ol></li>

</ol>

<strong>Ex. 2 — </strong><em>Keymap in Minix 3</em>

Map the Shit+F7 key to displaying how many processes are currently running.

This can be achieved following the steps:

<ol>

 <li>Find all the files that need to be modified;</li>

 <li>Locate the part of the code that should be updated;</li>

 <li>Check how to process table is stored;</li>

 <li>Count the number of running processes;</li>

 <li>Map the newly written function to the Shift-F7 key;</li>

 <li>Recompile the kernel and test.</li>

</ol>

Refer to <a href="https://wiki.minix3.org/doku.php?id=usersguide:commandlineinterface">Minix user’s guide</a> for some basic help.