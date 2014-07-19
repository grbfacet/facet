---
layout: default
title: The Plain English explanation of the Beam Energy Doubling research paper
pagetype: explanation
---

### How to read the material:

Here is our suggestion for how to achieve an understanding the energy doubling paper research paper. It is based on the fact that this Plain English explanation and the supporting physics tutorials, like the research paper itself, contain a lot of interconnected information. You will need to go over all the information more than once to make all those connections:

1. If you don’t like reading from a computer screen, you can print the material before you begin:
   1. [The research paper](/slac-pub-12363.pdf). (We reccommend that you, at least, print a color copy of the research paper.)
   1. This document you are reading now – [the Plain English explanation of the beam energy doubling research paper](/energy-doubling-exposition.html).
   1. The physics tutorials that provide background knowledge for this Plain English explanation.
      1. [Principles of physics](/principles-of-physics-tutorial.html)
      1. [Acceleration of beams](/beam-acceleration-tutorial.html)
      1. [Relativity](/relativity-tutorial.html)
      1. [Control of beam trajectories](/beam-control-tutorial.html)
2. First, read this Plain English explanation and follow the suggestions that are made along the way to stop perioically and look at the research paper and rate your level of understanding each time you look at the research paper. On this first reading skip over the hyperlinks to the relevant tutorial sections. Also skip the sections that are indicated to be details. .
3. Then, read all the physics tutorials but skip over the calculations. Read them in this order:
   1. [Principles of physics](/principles-of-physics-tutorial.html)
   1. [Acceleration of beams](/beam-acceleration-tutorial.html)
   1. [Relativity](/relativity-tutorial.html)
   1. [Control of beam trajectories](/beam-control-tutorial.html)
4. If you followed steps 2 and 3, you have gone over almost all the Plain English material once (the paper explanation and the tutorials). You have also looked at the research paper a few times. In order to deepen your understanding repeat steps 2 and 3 but this time:
   1. Follow the hyperlinks to the tutorials you skipped on first reading and read those linked tutorial sections. 
   1. Read through the details sections you skipped on the first reading of the Plain English explanation. 
   1. Read the calculations in the tutorials that you skipped over on the first reading of the tutorials. 
   1. Continue to rate your understanding each time you look at the research paper.
5. Finally, to experience what it is like to actually understand physics equations you can repeat all the tutorial calculations yourself with paper and pencil. If you do this exercise you will find that you can just look at the Einstein mass formula and understand what it says the way a physicist sees it.   
6. It is also an option to just skip around all the material according to your own instincts and look at selected topics.

### Introduction

We begin with an explanation of an important research paper from the plasma acceleration research done at the SLAC research lab’s FFTB facility, FACET’s predecessor research facility. To give you a sense of how much you can understand what may seem like an arcane research paper, let’s do some before and after measurements. Before you go any further, take a look at the research paper we are going to explain. If you haven't aready printed a copy, either open the [paper](/slac-pub-12363.pdf) in a new browser tab or color print it. Printing may be the easiest way to go back and forth between the journal paper and the interpretative information given here. Also you will be able to mark on the printed copy to make notes for yourself. Look it over, try to read parts of it and notice how much or little you can understand and notice if you tend to think something like, “I could never understand this.” Then come back here and we will explain the paper and have you look at it again a few times during this process and you can watch how your understanding increases and see that it is indeed within your capability to understand without needing a PhD in physics. Now look at the research paper and then come back here. Here’s a [link to the paper](/slac-pub-12363.pdf) if you didn't print it. 

Welcome back. On a scale from 0-10 how much did you understand? Make a note of this number. As you continue reading the Plain English explanation we will periodically have you look again at the research paper and ask for more 0-10 ratings so you can see if your understanding is progressing. Now let’s begin the explanation of the paper. 

### Background

To make your journey into this story smoother, we will give you a brief introduction to the cast of characters, inanimate entities mostly identified by acronyms like “SLAC”. To the people that work with these entities they have personalities and history and are almost thought of as living beings that evolve over time. 

We begin with SLAC, formerly known as the Stanford Linear Accelerator Center, today officially known as SLAC National Accelerator Laboratory. This is a large research laboratory with up to 2000 people working on site and many more visiting to do research. SLAC has a five decade history of research projects. It is a complex entity with many buildings, research facilities, and departments to handle things like payroll and personal issues. SLAC is operated by Stanford University for the U.S. Department of Energy (DOE), and is located in Menlo Park, California next to Stanford University. 

Built in the 1960s, SLAC’s work for decades was and still is based on the electron beams produced in its dead straight 2 mile long electron linear accelerator known as the Linac. The Linac was built at a cost of something like a billion dollars measured in today’s dollars. The electron beams from the Linac have served many different research projects. Some of the facilities the Linac provided beams for, which are mentioned here in the story of plasma acceleration research, are the SLC (Stanford Linear Collider), the FFTB (Final Focus Test Beam), FACET (Facility for Advanced Accelerator Experimental Tests) and the LCLS (Linac Coherent Light Source). 

We also mention LEP, the Large Electron Positron Collider that was located at the CERN particle physics laboratory in Geneva, Switzerland. Finally there is LHC, the Large Hadron Collider that replaced the LEP collider in its underground ring tunnel and which collides beams of protons. LHC is where the first direct discovery measurement was made of the Higgs boson, the long sought final particle to round out the Standard Model theory of particle physics. Finally, we mention the ILC, the hoped for but as yet unfunded International Linear Collider, a next generation SLC. 

### A little history behind the energy doubling research paper

Racing against the clock at SLAC’s FFTB facility, physicists, engineers and technicians achieved a major breakthrough. Using [plasma acceleration](/beam-acceleration-tutorial.html#plasma-acceleration), they doubled the energy of part of an electron particle beam. The electron particle beam was [first created and accelerated](/beam-acceleration-tutorial.html#charged-particles-are-accelerated-by-electric-fields)
 in the conventional particle accelerator, the Linac, at SLAC, and all the electrons left the Linac with 42 GeV of energy per electron. [A GeV is a unit of energy](/relativity-tutorial.html#the-electron-volt-ev-an-atomic-sized-unit-of-energy) used to measure the energy of a single particle like an electron. The beam then entered and exited a plasma accelerator and some of the electrons' energy was doubled to 84 GeV. Electrons with GeV level energies have velocities almost the speed of light and their behavior is described by [Einstein's Theory of Relativity](/relativity-tutorial.html#relativity-theory). 

Why is merely doubling something such an accomplishment?  For example, we are used to technological advances like Moore’s law that says computer chip processor speeds will double every two years - and they have done so for a few decades. And what was the hurry? Why were the experimenters racing to get their doubling result?

Plasma acceleration is a new and novel method of accelerating an electron to higher energy. In this experiment the Linac created a beam consisting of tiny bunches of about 1.8 x 10<sup>10</sup> electrons created at a rate of 60 bunches per second at the beginning of the Linac. Each bunch was accelerated in the Linac by very strong electric fields. To get a feeling for [how much energy is in the beam](/beam-acceleration-tutorial.html#the-beam-bunch-energy) imagine being pummeled by 60 major league pitchers each hitting you with a fastball every second.[link]

Think of each electron bunch as a cloud of particles. Because the electrons repel each other and because the electrons in the bunch have random thermal motion, [beam control technology](/beam-control-tutorial.html) was required to keep each bunch intact as it moved along the accelerator. The bunches in the Linac were long narrow needle shaped cylinders with a length of 6 millimeters (about 1/4"). The diameter of the cylinder varied as the bunch traveled down the Linac passing through focusing and defocusing beam control magnetic fields. Just before it entered the plasma accelerator, each bunch was “compressed” in length by a factor of 500 down to about 12 µm (1 µm = 1 micron = 10<sup>-6</sup> meters) and it’s diameter was focused to a “spot size” of 10 µm diameter.  

For the energy doubling experiment, the input beam bunches of 42 GeV electrons were created in the Linac and sent into the FFTB where the experimental plasma accelerator was located. The plasma accelerator that increased the energy of some electrons in the beam bunches to 84 GeV cost perhaps about ten thousand times less than the Linac to build AND was only 3 feet long, about three thousand times shorter than the Linac!! One way of looking at this  energy doubling accomplishment is in an order of magnitude approximation. In order of magnitude, the result represented a thirty million fold jump in capability (roughly one ten thousandth of the cost times roughly one three thousandth the length.) By comparison it would have been easy, in principle, to just build an essentially identical second two mile long linac after the first one and also achieve a doubling of energy. But doing it thirty million times better is the kind of thing physicists pop a cork of bubbly to celebrate. 

Why were they racing the clock? The FFTB was a research facility built about three decades earlier ~1980 to learn how to precisely focus the electron beams from the Linac for SLAC’s premiere project of the 1990s, the linear collider (SLC), a novel particle research facility that collided a beam of electrons at 45 GeV with a beam of positrons at 45 GeV. The research at SLC along with work done at the same time at a circular electron/positron collider facility, LEP, at CERN, helped establish the Standard Model theory of particle physics. The Standard Model was articulated in the early 1970s based partially on Nobel prize winning research done in the late 1960s and early 1970s using the SLAC Linac. 

To collide the two beams at the SLC required not only focusing the beams to tiny micron sized spots but also knowing exactly where they were located and controlling their location accurately and precisely to make them collide with each other in the center of the particle detector as they came together from opposite directions at essentially the speed of light. The research to develop that level of beam control technology was successfully undertaken in the FFTB. 

After the beam control research was finished at the FFTB and while the linear collider physics research program was running at the SLC, the FFTB was available for other research projects, and plasma acceleration was studied there for a decade. In ~2000 the SLC linear collider’s research was complete and the FFTB was going to be dismantled to make way for an amazing new facility to use the Linac to create a free electron X-ray laser (FEL) beam ten millions times better than any previous X-ray laser, and indeed, the FEL project was a success and corks were popped for this new facility, the LCLS, in 2011. The last beam run at FFTB was scheduled in order to give the plasma acceleration project a chance to achieve energy doubling. The run had a hard and fast end date and the doubling was achieved. 

From a scientific research point of view the energy doubling experiment at that time was partially a public relations effort. There were other important matters of plasma acceleration to continue to be studied. But where would they be studied once the FFTB was gone? To build a new research facility somewhere else at the lab would cost several million dollars. With a lot of competition for research funds and government deficits eating into research money, getting another facility would be a challenge. 

The plasma research group decided one thing to do was to demonstrate in a powerful way the ultimate goal of studying plasma acceleration, namely, to learn how to create plasma accelerators for many possible uses. And doing the energy doubling experiment would certainly create an easy to understand, easy to explain and easy to remember “sound bite” about the potential value of plasma accelerators.  They did indeed beat the clock and, eventually got the funds for a new facility, FACET, and today they are at work on further research on plasma acceleration and plasma accelerators. 

Normally experiments and research are not under the gun quite so dramatically as this project was, but funding concerns are a part of most scientific research today. The excitement of achieving important goals is not always as dramatic but it, too, is always a part of research. Scientific research is after all a human activity carried out by people who are no different than anyone else when it comes to having a successful career. 
 
### Research papers

The purpose of scientific papers is to enable other scientists who are interested in what you are doing to understand exactly what you did. There are at least two reasons for this. First, to evaluate what you did and see if it all makes sense, to look for any possible mistakes and to look for alternate possible interpretations of the data. In most experiments, data is collected and analyzed for its meaning. Before you write your paper you undertake an excruciating evaluation to be sure you haven’t overlooked anything that might shed a doubt on what you’ve concluded. The second purpose of a research paper is to describe what you did in enough detail so that someone else could reproduce your results. 

These two aspects: questioning of methodology/interpretation of data and reproducing results elsewhere, are the cornerstone of how science creates consensus. Comparing with politics, for example, detailed and carefully thought out explanations for a policy goal can be given by politicians but there is no standard methodology that can lead to a consensus of what policy is best.
 
Writing the research paper can be an important part of the research since it requires thinking through and clarifying exactly what you did and what you found. The paper focuses on a specific identifiable result worth publishing. The research itself typically uncovers a great deal of information that does not appear in the paper. Often these other discoveries point the way to new questions to answer and but generally go unmentioned in the paper currently being written.

### Energy doubling research paper overview

Let’s return our focus to the research paper. In a moment we will send you back to look again at the paper and, based on what you’ve read since that first look, see if you can at least understand that the paper is about energy doubling of beam electrons. Notice all the jargon that means nothing to you but try to see that it is mainly describing the details of how the experiment was conducted.  

First notice the structure of the paper: There is a title and a list of authors. The paper is in a common format for research papers, double column. The text begins with the abstract, the long paragraph in bold face type, a kind of executive summary. Based on what you know now you should be able to understand much of this opening paragraph. Notice there are three sets of figures in the paper. Notice beginning on page three in the second part of the paper there is a section called Methods and that section has four sub-sections: 

1. Electron pulse, 
2. Plasma generation, 
3. Energy Measurement and 
4. Simulation. 

At the end of the paper are the references to other research cited in the paper. 

Read the opening paragraph and peruse the rest of the paper again. See what you can understand based on what you know so far, get a feel for it then come back and we will explain the experiment in more detail and then you will be able to go back again and actually read the paper with a deeper level of comprehension. So have another look and come back here again. Here’s the [link] again to the energy doubling paper.  

Welcome back. Now that you’ve looked at the paper a second time rate your current sense of understanding on the 0-10 scale once again and write it down with your previous number. Have you made any progress?

You’ve had a more focused and assisted look at the paper now. Some questions that might have occurred to you (it always helps when studying something to have questions in your mind as you read):

1.	Why did the plasma accelerator double the beam energy? Why not triple? Why not only a half-fold increase? 
2.	Where does the additional energy come from to increase the energy of some of the electrons? 

Conservation of energy says the additional energy doesn’t come out of nothing. The Linac is driven by a megawatt power system, but the plasma accelerator has no power input at all except the heater to keep the Lithium vaporized. The second law of thermodynamics says you can’t directly convert heat to organized energy of motion in this type of situation, so the extra beam energy cannot come from the heat of the plasma. Think about these questions and try to come up with an answer. Actually the answers are implicit but right on the surface of the first paragraph of the paper. As we go on from here you will learn if your answers were correct. 


### The Methods section of the paper

The paper has two major sections. After the bold face first paragraph, the abstract, there are two plus pages of discussion of the results of the experiment and that discussion is followed by a Methods section which actually explains the experimental setup so we will focus on the Methods section now. 

We can get an overview of this experiment by considering the four topics of the Methods section, each one describing an element of the experiment. The first element is the electron beam from the Linac and it is described in the first topic, Electron Pulse. The second element is the plasma accelerator described in the second topic, Plasma generation. The third element of how the final beam energy coming out of the plasma accelerator was measured is described in the third topic, Energy measurement. These three elements of the experiment are displayed in the Figure 1 schematic of the experiment. So far so good, but what is the fourth topic on simulation about? 

You know the scientific method usually involves testing a theory: we make a prediction using theory and then we make a measurement and see if it agrees with the theory. If they agree, the theory is supported; if not, then some serious thinking is required to find out whether something went wrong in the experiment or whether the theory is wrong or, perhaps, the theory is correct but was incorrectly applied in some way. For physics we tend to think of theory prediction as a matter of solving equations. Sometimes when complex phenomena are involved a computer program is written that “simulates” how theory applies to the situation. In this case a program that incorporates some of the known relevant physics of plasma acceleration was used to predict approximately what would happen. 

Figure 1 is a very simple schematic of the apparatus involved. It shows the beam, the plasma accelerator and the energy measurement apparatus consisting a magnet that bends the beam and two screens that record the direction of the beam. The second figure set displays the measurement, what was seen on the screen and also shows what the simulation predicted, by displaying them together it compares theory and experiment. The third figure set displays information about the simulation. Go back to the paper again and briefly scan it. Look at the first figure and read its caption. Read each of the four methods sections and come back here. 

Make your third 0-10 rating on your understanding. 

Are you starting to think the paper actually might be within your ability to understand with some more explanation? By now you should be feeling a little more familiar with this paper. And if you have delved into more than the bare minimum we have suggested to look at, you might be feeling that although you are starting to get the big picture, the details are still pure Greek. Journals are expensive to produce because they have limited circulation. For that reason and others, brevity and concise writing are required. Many journals have a word limit and authors will spend a lot of time figuring out how to present as much information as they can in as few words as possible. If the energy doubling paper seems dense, that’s because it is dense. 

Let’s take a moment and boil this all down to the experimental method of science. The basic pattern is

1.	A theory (expressed in the simulation shown in Figure 3) makes predictions (shown in Figure 2b)
2.	The predictions are tested in an experiment (by the apparatus summarized in the Figure 1 schematic). 
3.	The results of the experiment are a measurement (Figure 2a shows data that was projected on the screen shown in Figure 1). 
4.	The actual measurement is compared with the theory (Figure 2b). 

The figures mentioned with each of the cardinal four steps described above are, of course, supplemented in the text with much more explanation. It is useful to orient yourself with these basic four parts of a scientific experiment and see that their presence in the paper provides the paper with its ultimate meaning and purpose. 

We have reviewed the purpose, organization and meaning of the paper. Now take some time and study the material: Read the tutorials skipping the calculations. Then read through the research paper again, this time following the links to the tutorial information. Finally, reread this explanation page up to this point and try to get an overall understanding of the research paper. 

When you've finished make another 0-10 rating of your understanding. See how far you have come since your first look at the paper. Have you confirmed our contention yet that research is understandable? 

You should have a pretty good idea of what the paper is saying but many details will still be unclear. To go deeper in your understanding continue reading further in this explanation.

### More details on some important issues covered in the paper (skip this section on first reading)


Figure 2 shows the energy spread of the electrons in the bunch after they have passed through the plasma accelerator. Notice the horizontal scale is electron energy in GeV and the scale goes from 35 GeV on the left to 100 GeV on the right. There are electrons with energy below 35 GeV but they are simply not shown. The spread of energies in Figure 2a should not be misinterpreted as the faster electrons somehow being ahead of the lower ones. It is a plot of spread in energy, not a plot of spread in space. It is understandable to expect a spread in space based on ordinary everyday experience. When a car accelerates and goes faster, it gains energy and speed and moves away from slower cars. Not so for electrons with relativistic speeds. See why here– [link].

The vertical scale of Figure 2b, the bottom plot, shows the number of electrons with each energy. Looking at Figure 2b, we see the blue line for the measured values and the red line for the simulation predicted values. Both lines show a peak around 42 GeV, the incoming beam energy, and they show that some electrons have lost energy (left of the peak) and some electrons have gained energy (right of the peak). The simulation data does not exactly match the measured data but it is generally the same pattern and the differences mostly have to do with the simulation not taking into account all the relevant factors. This experiment was not intended to be a precision measurement, instead it was intended as a kind of proof of principle demonstration where just reasonably accurate predictions and measurements were sufficient (link). 

The red and blue lines in Figure 2b are the electrons’ energy after leaving the plasma accelerator. If you imagine the sharp triangular spike of the red line at 42 GeV extended all the way down to the bottom of the plot that would be a representation of the beam energy distribution just before its entry into the plasma accelerator when its energy distribution was spread only 1.5 GeV wide around 42 GeV.  

Now we understand that the paper title does not mean that a beam at 42 GeV is all doubled to exactly 84 GeV but that a portion of the beam is raised to energies from just above 42 GeV all the way up to over 84 GeV. One of the experimental enhancements available at the new FACET facility is the ability to create two separate bunches of electrons very close together by basically splitting the original bunch in the Linac into two pieces. The expectation, if this works is that the energy profile seen in Figure 2b will look more like a peak at 84 GeV for the trailing bunch.

With a very dense bunch of very high energy electrons passing through the Lithium vapor essentially all the Lithium atoms along the beam path have at least one electron ionized. The beam is moving at nearly light speed and leaves an unmoved trail of positive ions in place but the ionized electrons, being far lighter, are pushed away by the negative charge of the beam bunch, that’s the blue cloud in Figure 3.


### Some Details on the Figures. (skip this section on first reading)


##### The Figure 2 - The energy measurement: 

Figure 1 indicates that a beam energy measurement is made after an electron bunch leaves the plasma accelerator and Figure 2a shows this measurement data in the form it is obtained on a CCD screen [hover] for a single bunch of electrons. The research paper as a whole is reporting on data obtained by making the same measurement on 800 bunches. When a charged particle passes through a magnetic field the particle’s direction of movement is changed because the magnetic field applies a force on the particle at a right angle to the particle’s direction of motion [link]. The force is proportional to the particle’s momentum, the greater the momentum the stronger the sideways push. When all the particles have the same momentum their directions will all be changed the same amount, but if they have different momenta their directions will be changed different amounts and the bunch will be spread out in space. That is what we see in Figure 2a. Since momentum has a fixed relation to energy, the locations where the electrons pass through the CCD indicate their energy. 

 
The Figure 2a CCD picture uses different colors to indicate the number of electrons hitting the CCD at each location. The color scale for Figure 2a is tucked in the upper right hand corner of Figure 2b (just below Figure 2a) and shows the numerical meaning of each color. If we were to create a series of vertical slices or bands across Figure 2a and add up the hits in each slice and plot it, we would have the blue line of Figure 2b. The blue line peaks in the area where there is the most red above it in Figurer 2a. The scale in millimeters along the top of Figure 2a shows the amount the electrons direction was changed by the magnet. Given the magnet strength, the geometry of the apparatus on the physics of particle energy and amount of bending these millimeter distances translate into an energy value for electrons, and that is what is given in the horizontal scale along the bottom of Figure 2b. Notice it is a logarithmic scale where the distance of bending scale is linear. This is because the relation between energy and bending is a power law relationship.  

##### The Figures 3a and 3b - The simulation: 

It is important to note the details in Figure 3. First note that the top Figure, 3a, is a simulation of what is happening when the bunch is 12.3 cm into the heated Lithium vapor. The bottom Figure, 3b, is a similar simulation further along the plasma accelerator near the end of the Lithium vapor at 81 cm. It is especially important to note the horizontal scale is not the distance into the plasma accelerator, which would be measured in centimeters. Rather, the scale is in microns and shows bunch scale details around the bunch at the two locations along the plasma accelerator. Notice also, the vertical axis is shown in microns, again showing things on the tiny scale of a bunch and not on the scale of the plasma accelerator diameter which is measured in centimeters. 

##### The Figure 3c - Measured data and simulated data compared: 

As noted in the research paper, two actual physical plasma accelerators were studied, one with a Lithium vapor length of 85 cm and a second longer one of 113 cm. The longer accelerator was to measure what happens when the effective acceleration ends and the bunch continues through more Lithium vapor. The orange circles in Figure 3c plot the simulated amount of maximum energy the electrons acquired at various distances into a simulated Lithium column 120 cm long. The simulation shows the energy increases as the bunch progresses through the plasma to a maximum just above 80 GeV and then drops off past this point just beyond 80 cm into the plasma indicating that the most accelerated electrons begin to lose energy after 80 cm. The blue squares are the actual values measured in the two different length real accelerators and they are pretty close to the simulated expectation. The simulation is known to be imperfect in that it does not account for all known effects, so exact agreement is not to be expected between simulation and experimentally measured data. Remember, this was a proof of principle experiment, not a precision measurement. The vertical scale on the left hand side of the plot refers to the plotted energy of the electrons. The vertical scale on the right hand side refers to the dashed line at the bottom of the plot which represents the profile of the density of the Lithium vapor assumed in the simulation.

### Where to next?

There is more about this plasma acceleration energy doubling experiment to be explained but we will do that in our explanations of some of the earlier experimental papers that led up to this result. The same basic issues and technologies were involved in those earlier papers, so by studying a few of the papers you should be able to get a pretty good grounding in the plasma research project at FACET. 

We have begun the story of plasma acceleration _en medias res_, in the middle, with the energy doubling experiment. It is natural to ask questions about how the research has reached this point. But we emphasize "in the middle" because the research is on going and it is natural to ask where the research is going. For example, it is typically very desirable to have an accelerated beam of particles all have the same energy for most applications and in this experiment we have seen that although enormous gains have been made in creating accelerating gradients the result is a wide spread of beam particle energies. 

One focus of research after this is to create final beams of particles all with the same energy. We have seen that the front of the beam bunch creates the field that accelerates the back of the bunch. Some of the energy required to do this goes to creating the plasma, that is to ionize the Lithium gas. The heater only vaporizes the Lithium, it does not ionize it. 

An alternate way to ionize a path through the gas is with a very powerful laser beam precisely timed to go through the gas just before the beam bunch enters the plasma accelerator. Then the job of the front of the bunch is only to push the ionized electrons away from the beam path to create the wakefield that accelerates the rear of the bunch. And even that arrangement can perhaps be improved by separating the bunch into two parts: a lead bunch that is discarded after creating the wakefield and a trailing bunch that is more uniformly accelerated. This idea and many others are part of the ongoing plasma acceleration research at FACET.








