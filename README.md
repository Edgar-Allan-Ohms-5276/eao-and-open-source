# The Edgar Allan Ohms and Open Source

Open-source software is computer software that is released under a license in which the copyright holder grants users the rights to use, study, change, and distribute the software and its source code to anyone and for any purpose. Open Source software has become a core aspect of both software development, and education around computer science and programming.

One of the reasons for the explosion of open source software is it's tendency to promote collaboration - something which most FRC teams are intimately famaliar with. When developing and engineering parts for a robot, teams can gather inspiration from other creations, reverse engineer their systems, and create their own new versions. In this process, team members learn about how to better design and create parts and mechanisms. Open source software allows for this same behavior - people can find inspiration from other software, reverse engineer how they work, create new programs for their own uses.

Within the FRC community, we see lots of teams sharing their projects as open source. Some notable examples are [Team 997 Spartan Robotics](https://github.com/Team997Coders), who shares their robot code every year, [Team 4915 Spartronics](https://github.com/Spartronics4915), who share [SpartronicsLib](https://github.com/Spartronics4915/SpartronicsLib) as a library containing many handy functions, and [Team 2052 KnightKrawler](https://github.com/frc2052), who creates a public [app for scouting](https://github.com/frc2052/FRC-Krawler). [GradleRIO](https://github.com/wpilibsuite/GradleRIO), the official Gradle Plugin that allows teams to build and upload their robot code, was originally an [open source project](https://github.com/Open-RIO/GradleRIO-C)

Open source software promotes a free exchange of ideas within a community to drive creative, scientific and technological advancement. With that said, it is deeply alarming that many of the software which is integral to FRC is closed source. The main examples are the [NI DriverStation](https://docs.wpilib.org/en/stable/docs/software/driverstation/driver-station.html), the [Field Management System (FMS)](https://wpilib.screenstepslive.com/s/fms/m/whitepaper/l/608744-fms-whitepaper), [The Radio Programmer](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-3/radio-programming.html), the radio firmware, and the [Schedule MatchMaker](https://idleloop.com/matchmaker/). Each of these components are used by each and every FRC team, and yet they will never get the opportunity to dive into how these systems work. 

In concept, these softwares could provide great learning expirences - The DriverStation can be used to explore control systems, hardware input, and safety protocols, the FMS can be used to show networking technologies and protocols, the Radio Programmer/Firmware can be used to show OS creation and demonstrate the inner-workings of WIFI and IP, and the MatchMaker can be used to demonstrate algorithms. However, all of these softwares are closed source and cannot be used for these purposes.

There are many cases where closed source software makes sense, and we also understand the oblication to partner companies such as NI to keep certain softwares closed source. However, as one of the larges STEAM programs in the United States, that gets many thousands of high-schoolers exposed to programming every year, we feel it does not make sense to have the core softwares be closed source.

The Edgar Allan Ohms is not one of the biggest FRC teams, nor one that has won many seasons, nor one that has created the best robots. We are a small (12 members at the time of writing) team started out of a public library. It is safe to say that the majority of people reading this piece have not heard about us. However, we are a group of ambitious individuals who take great pride in who we are and what we create. 

One of the goals of the Edgar Allan Ohms is to lower the friction caused by FRC's closed source libraries. We are pleased to see the many parts of FRC which are open source, such as [wpilib](https://github.com/wpilibsuite/allwpilib). However, there are still many parts which are locked behind the barrier of closed source. 

Many of our projects aim to re-create or re-implement the softwares used by FIRST in an open source way. Although the list of softwares we've recreated is small, we hope that in time it will continue to grow, with support from both ourselves and the community, so that every component of FRC has an open source version available. Long-term, we hope that this influences FIRST to follow the same path in future iterations of the FRC technology stack.



Sincerely,

The Edgar Allan Ohms

2021



List of Software Components created by EAO (updated July 2021):
- [EAO Radio Programmer](https://github.com/Edgar-Allan-Ohms-5276/radio-programmer)
- [Nevermore FMS](https://github.com/Nevermore-FMS/nevermore-fms)
