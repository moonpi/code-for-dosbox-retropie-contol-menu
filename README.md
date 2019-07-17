# code-for-dosbox-retropie-contol-menu
Code for the DOSBOX Retropie Controls menu for dosbox-retropie-launch-control

I was able to compile control2.c into a MS DOS com file using bcc on a Raspberry Pi.
To install bcc on a Raspberry Pi or a Debian distribution of Linux: 
<code>sudo apt-get install bcc</code>
To compile: 
Go to the directory using the terminal:
<code>bcc -Md -o controls.com controls2.c</code>

You may be able to compile the other codes into MSDOS on DOS or Windows using anoher method. However, I have not tried that yet.
