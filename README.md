## Members
Dom Meoli III, Computer Engineering Student
djmeoli3@vt.edu

## Mentor
MENTOR NAME HERE

## Current Status
IN PROGRESS

## Project Overview

The end goal of this project is to produce a large scale scoreboard using **only mechanical displays** that will update with states and gamestates in real time. The displays will be similar in nature to MLB.com's 'Gameday' feature, showing live statistics regarding many facets of the game, such as a dynamic strikezone, batting averages, pitch counts, and a plethora of other key statistics that cannot be gathered at all points of a television broadcast. The user would be able to iterate through each live game at a time, updating the scoreboard in turn. 

## Educational Value Added

1. For obtaining the statistics for the display, I plan to either develop a script that will scrape the necessary data from the web, or I will find a way to implement the MLB API, if applicable. Either approach is completely new to me and will teach me a viable method of obtaining and repurposing real time data. This is a worthwhile skill to learn as a Computer Engineer with a desire to continue into Machine Learning, which has implications for both API usage and webscraping.
2. I have a general idea on how I want to operate my two types of mechanical displays, a Split-Flap display and a Flip-Disc (Flip-Dot) display. Some similar products are documented on maker websites, but they will not meet my specific usecases. I will have to modify these pre-existing designs to create functional PCBs link together modular displays that will contribute to the overall size and aesthetic of the scoreboard. This will teach me about driving multiple modules with a singular driver via daisy chain. Additionally, I will have to consider the overall power requirements and find a way to effectively power all of the modules in a safe manner. These are general concepts that will be essential to future hardware applications as my academia and career begin to work with larger, more complex systems.
3. In order to meet my personal goals, I will need to innovate beyond current documentation of Flip-Disc (Flip-Dot) displays. These displays inherently only have two states depending on the polarity of the solenoid being powered in each individual disc/dot. These discs/dots will make up the strikezone component of the scoreboard. Using two states, I would be able to display a lot of strikezone information accurately, but, in order to cover all possible scenarios, I will need to find a way to implement a third state. For example,
         Let's say the strikezone has a neutral color (gray). When a pitch is thrown, the discs in the area where the pitch crossed the plate relative to the strikezone will flip. If it is a strike, these discs will turn red, and if it
         is a ball, the discs will turn green. In an ideal world, I could just make the discs in the strikezone gray/red, and the discs outside of the zone gray/green. However, due to the nature of baseball, some pitches are incorrectly
         called balls and strikes. If a pitch outside of the zone is called a strike, I would have no way to display this information accurately.
My solution is to implement a third possible state, so each disc could be gray, green, or red at any give time. In order to accomplish this, I have a few ideas, including finding a way to implement a spring mechnism to 'return to a home position', or powering a second solenoid to hold the disc perpendicular to the viewing angle, revealing the background color (gray/neutral). More information regarding this process can be explaiend in person. I tried to provide context in order to justify the learning objectives that I hope to achieve from this design. Ultimately, this will force me to think outside the box and innovate due to the lack of documentation for a three-state flip-disc display. This skill is something that is difficult to learn, let alone master, but it is a great skill to have as an aspiring engineer.
4. This project will also force me to consider other engineering disciplines in my build. Due to the use of mechanical displays, I will have to consider properties of rotation, torque, and magnetism, which can be more common to disciplines outside of ECE. I would be eager for an opportunity to broaden my horizons and bolster my knowledge of what future coworkers and peers might be working toward.
5. My displays will be modular. Due to the desired statistics, the scoreboard will be large. To save on materials and attempt to streamline the module production process, my plan is to build the modules mostly out of 3D printed parts. This will require a development in CAD knowledge and prototyping design. I will also have an opportunity to practice creating a 'proof of concept' for my designs before attempting them on a large scale. The combination of 3D printed parts, electronic components (motors, solenoids), physical components (magnets, outer casing - probable laser cut application), will contribute to a wholistic project design that requires thorough design and careful implementation. This complex project will be a great platform to practice working in the engineering industry, beginning with small steps across multiple key tasks and eventually combining all of the designs, planning, and objectives under one large final product.

6. Along the way, I am sure that there will be many opportunities to jump down rabbit hole after rabbit hole, learning new skills and concepts along the way. My intial design will inevitably change, bringing in new skills that might not have been needed previously. Despite all of this, there is no doubt that these skills will be essential to my future. In review of my educational takeaways, I can think of real applications for each conecpt. At my current summer internship, real employees are using webscraping tactics and API implementations to innovate a tool that currently does not exist. My starting job is to research everything under the sun about reverse engineering hardware, which includes how power is distributed throughout the system and how multiple components are connected to a central hub. My current team at work has multiple people working on individual assignments and tasks, but they are always considering how their component will fit into the larger tool and be compatible with the rest of the system. On top of this, I am already slightly exposed to working cross-discipline. The undergraduate research lab I volunteered at in Spring '24 was the Assistive Robotics Lab in the Mechanical Engineering department. Learning more about some mechanical engineering concepts and applications will allow me to further my understanding and ability to communicate with peers and coworkers. I will enable myself to contribute more to a team objective in research and later in industry. Overall, I truly believe I would gain a wealth of knowledge from undertaking this project. My passion for both baseball and electronics makes this a special design, and that same passion would contribute to my determination to achieve what I set out to accomplish regardless of setbacks and difficulties.

## Tasks

<!-- Your Text Here. You may work with your mentor on this later when they are assigned -->

## Design Decisions

<!-- Your Text Here. You may work with your mentor on this later when they are assigned -->

## Design Misc

<!-- Your Text Here. You may work with your mentor on this later when they are assigned -->

## Steps for Documenting Your Design Process

<!-- Your Text Here. You may work with your mentor on this later when they are assigned -->

## BOM + Component Cost

<!-- Your Text Here. You may work with your mentor on this later when they are assigned -->

## Timeline

<!-- Your Text Here. You may work with your mentor on this later when they are assigned -->

## Useful Links

<!-- Your Text Here. You may work with your mentor on this later when they are assigned -->

## Log

<!-- Your Text Here. You may work with your mentor on this later when they are assigned -->
