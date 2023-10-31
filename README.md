# openmush

A project to develop a FOSS alternative for dogsledding race timing. 

## author

This project is run by estlin. I am happy to accept contributions from others who are interested, but my experience so far has been that there's not much overlap between computer people and dogsports people. 

## history

I am beginning this project after seeing how haphazard the timing systems are at many of the races I've been to, running old, messy code and with obsolete systems. Much of it also depends on interfacing with Microsoft Excel, which leaves it liable to breaking whenever that updates, and also requires timers pay for expensive software that has its own perfectly reliable FOSS alternatives out there. 

## goals

My long term goals include: 

1. A race timing software that generates start sheets with either randomized or specified (or some combination of the two) start order at custom intervals (including mass starts and staggered mass starts), allows for the input of times from an outside source or does the timing itself (with the use of a lap button in the program or interfacing with an external stopwatch (such as the Seiko 300/S149)), and outputs race standing sheets, sortable by overall time and by various groups, with the ability to include multiple race stages (or multi-day races).
   * Should run independently of any other software, ie not on Microsoft Excel, and be compatible across operating systems (MacOS, Windows, Linux, and various phone operating systems).
   * Should be able to function without access to internet or cell service.
3. A web interface for people to upload race standings (and individual users to upload their own personal times from other runs) so mushers anywhere can compare speeds with each other.
  * Including the ability to "verify" standings as official race times, so they can be easily distinguished from user-uploaded race times.
  * A long term, searchable archive of past race standings
  * Ability to integrate searching by known dog genetic trees, so it's feasible to track how an entire bloodline has historically performed. 
