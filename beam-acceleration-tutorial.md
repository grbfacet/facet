---
layout: default
title: The acceleration of particle beams
pagetype: tutorial
---

## Overview

This tutorial is about the energy of particle beams and how they are accelerated. It begins with some basic information  on units of measure, particularly the eV used to measure energy of particles. Then it discusses how charged particles are accelerated by electric fields and how an accelerating electric field is created in a plasma accelerator.

## The prefixes on units of measure indicate powers of ten

The reader is probably familiar with the use of prefixes on units of measure in the metric system to indicate multiples or fractions of the unit of measure in powers of ten. The meter, a unit of length (about 3 ft), is abbreviated with the letter “m”. Just like we say 7 ft, we also say 13.2 m. Unlike the English system of measure we indicate 1000 meters as 1 km (one kilometer) and we indicate 1/1000th of a meter as 1 mm (one millimeter).  

Going up in multiples, 

<span class="eq">k for kilo indicates 10<sup>3</sup> = 1000 (thousand),</span> 

<span class="eq">M for mega indicates 10<sup>6</sup> = 1,000,000 (million),</span> 

<span class="eq">G for giga indicates 10<sup>9</sup> = 1,000,000,000 (billion) and</span> 

<span class="eq">T for tera indicates 10<sup>12</sup> = 1,000,000,000,000 (trillion).</span> 

Sometimes in particle physics literature written a few decades ago, B was also used for a billion. 
The scale of energy reached by particles in current particle accelerators is in the 100 GeV to 10 TeV range.  We explain the eV energy unit below.

There is a corresponding series of notations for fractions of a unit. 

<span class="eq">1 m = 1 meter.</span> 

<span class="eq">1 mm (one millimeter) = 10<sup>-3</sup> m = one thousandth of a meter.</span> 

<span class="eq">1 µm (one micrometer/micron, where µ is the Greek letter mu) =10<sup>-6</sup> m = 1 millionth of a meter.</span>

<span class="eq">1 nm (one nanometer) = 10<sup>-9</sup> m = 1 billionth meter.</span> 

And further steps of one thousandth are pico (10<sup>-12</sup>) , femto (10<sup>-15</sup>) , atta (10<sup>-18</sup>).



## The electron volt, eV, an atomic sized unit of energy

The eV is a unit of energy. [See the tutorial explanations of the key related concepts of energy, force and work](/relativity-tutorial.html#force-energy-work-potential-energy-energy-of-motion-kinetic-energy-electric-potential-and-all-that)
 One e is a unit of charge; it is the amount of charge of an electron, a proton and many other elementary particles. Electric charge comes in two kinds, positive and negative, and the charge of an electron is actually –e, where e is a positive number. One V (volt) is a unit of electric potential, the capacity to create energy, i.e., to do work, with an electric force. An electric potential is closely related to an electric force in that a charged particle, like an electron, will be pushed to move when it experiences an electric potential, V. And one eV is the energy of motion acquired by one particle that has the amount of charge e that is accelerated through a one volt electrical potential. 

An AA battery creates a 1.5 volt potential between it’s + and - ends. A single electron accelerated freely (“freely” is an important qualification explained later) would acquire an energy of motion of 1.5 eV. Energy of motion is called kinetic energy and is given in low velocity situations, far from the speed of light, by the Newtonian formula 

<span class="eq">E<sub>Newton</sub> = ½ m<sub>0</sub>v<sup>2</sup>,</span> 

which is an approximation to the very famous and correct (as far as we know today!) relativistic formula E<sub>Einstein</sub> = mc<sup>2</sup>. (This is presented in detail in the [relativity tutorial.](/relativity-tutorial.html#relativity-theory)
)
E<sub>Newton</sub> is the Newtonian kinetic energy of motion, m<sub>0</sub> is the particle’s mass and v is the particle’s velocity.

Let’s compute how fast a freely accelerated 1.5 eV electron would move. To do this we will need a conversion factor between the atomic level unit of energy, the eV, and the macroscopic level energy unit, the Joule: 

<span class="eq">1 eV = 1.6 x 10<sup>-19</sup> J (Joules) where the units of a Joule are kg-m<sup>2</sup>/sec<sup>2</sup>.</span> 

The mass of the electron is 

<span class="eq">m<sub>e</sub> = 9.1 x 10<sup>-31</sup> kg.</span> 

Calculation: Solve the Newtonian kinetic energy formula for velocity squared and then take the square root;

<span class="eq">v = (2E/m<sub>0</sub>)<sup>1/2</sup>.</span>  

Plug in the values for E and m<sub>e</sub> of the 1.5 eV electron and the energy units conversion factor;

<span class="eq">v = (2 x 1.5 eV x 1.6 x 10<sup>-19</sup> J/eV / 9.1 x 10<sup>-31</sup> kg)<sup>1/2</sup> .</span>

<span class="eq">v = (0.525 x 10<sup>12</sup> J/kg)<sup>1/2</sup> .</span>  

Since 1 J = 1 kg-m<sup>2</sup>/sec<sup>2</sup>, J/kg = m<sup>2</sup>/sec<sup>2</sup> .

<span class="eq">v = (0.525 x 10<sup>12</sup>  m<sup>2</sup>/sec<sup>2</sup>)<sup>1/2</sup>,</span>

<span class="eq">v = 0.72 x 10<sup>6</sup> m/sec = 720km/sec ≈ 450 miles/second. End calculation.</span>

An electron accelerated freely by a 1.5 volt AA battery would reach a speed of 450 miles per second which is about 4000 times the speed of a passenger jet plane.  But this is still only about one quarter of a percent of the speed of light, 300,000 km/sec (186,000 mi/sec) so the use of the Newtonian approximation 

<span class="eq">E<sub>Newton</sub> = ½ m<sub>0</sub>v<sup>2</sup>.</span> 

Relativity effects only begin to become important when particles reach, say 10 percent, at least, of the speed of light. As is explained in the relativity tutorial, the Newtonian formula, 

<span class="eq">E<sub>Newton</sub> = ½ m<sub>0</sub>v<sup>2</sup>,</span> 

[begins to make a significant error](/relativity-tutorial.html#where-newton-approximates-einstein) only when we approach these “relativistic” speeds. 

4000 times jet speed is pretty fast, a bullet or a baseball with that speed could do a lot of damage but they are very heavy compared to an electron. What about electrons accelerated by the Linac, not just a battery. Remember our 4000 times jet speed was an electron accelerated only by one 1.5 volt AA battery. Can we get a sense of the energy of the 42 GeV electrons in the energy doubling experiment? 


#### The beam bunch energy

An electron with 42 GeV of energy actually has a very small amount of energy.

<span class="eq">42 GeV = 42x10<sup>9</sup> eV x 1.6 x10<sup>-19</sup> J/eV = 67 x 10<sup>-10</sup> J.</span> 

But in the plasma acceleration experiment tiny bunches of 1.8 x 10<sup>10</sup> electrons at a time are used, so one entire bunch would have 

<span class="eq">1.8 x 10<sup>10</sup> electrons/bunch x 67 x 10<sup>-10</sup> J/electron =  121 J of energy per bunch.</span> 

How much energy is 121 Joules? Let's make a comparison to a baseball which weighs 5 oz.  At 28 grams/oz, that’s 

<span class="eq">5 x 28 = 140 grams/baseball = 0.14 kg/baseball.</span>

Go back to Newton's formula:

<span class="eq">v = (2E<sub>Newton</sub>/ m<sub>0</sub>)<sup>1/2</sup>.</span>


A baseball with 121 joules of energy will have a velocity of

<span class="eq">v = ( 2 x 121 J / 0.14 kg )<sup>1/2</sup> = ( 1729 m<sup>2</sup>/sec<sup>2</sup>)<sup>1/2</sup> = 42 m/s.</span> 

What is that in mph? 

<span class="eq">42 m/s x 3600 s/hr = 150 km/hr = 93 mph.</span>

If you imagine being hit by a fastball thrown by a major league baseball pitcher that gives some sense of the punch packed by a 42 GeV bunch of electrons in our experiment. The SLAC Linac can produce 60 bunches per second so imagine being pelted by 60 pitchers simultaneously with each pitcher throwing a fastball at you every second. Ouch. 

## Charged particles are accelerated by electric fields

How does plasma acceleration work? First, how does particle acceleration work in general? Any time you flick an ON switch to something electrical you complete a circuit for a current to flow from a high voltage side, one terminal of the battery or one prong of the wall plug, to the other low voltage side. (Actually, since the electrons are negative, they flow the other direction.) That voltage difference between the two power source terminals pushes the electrons along the circuit. In a normal circuit like a flashlight or a lamp, the electrons are accelerated by the voltage difference but they collide with atoms in the wire and are slowed down momentarily or bounce in a different direction only to speed up again along the wire until the next collision. This results in an average “drift” speed for the flow of the electrons at a rate of less than a millimeter per second in a device powered by a 1.5 volt AA battery. 

When the electrons hit atoms in the wire they cause the atoms to move slightly, that is, the electrons transfer some of their energy of motion to the wire’s atoms. The warmth of an object is actually the amount of random atomic motion, and this is why wires heat up when we run a current through them. With an old fashioned incandescent wire light bulb the wire gets so hot it begins to radiate energy in the visible light range of the spectrum.

However, at the atomic level the voltage accelerates the electrons rapidly to high speeds. In the absence of obstructions they just continue to gain energy of motion as they keep accelerating to higher speeds. We calculated above that same standard 1.5 volt AA battery can accelerate an electron to a final velocity approaching a million meters per second "freely", in the absence of the obstruction of atoms in a wire. Without the wire’s resistance the electron reaches a speed nearly a billion times faster than the drift speed in the wire. In the Linac the electrons move in a vacuumized beam pipe, so they don’t hit anything to slow them down. In each section of the Linac there is an accelerating electric field, a voltage that gives additional speed and energy of motion to the electrons. Since the Linac gives the electrons 42 GeV of energy, that means the Linac is the equivalent of

<span class="eq">42 x 10<sup>9</sup>/1.5 ≈ 30,000,000,000 (thirty billion!) AA batteries connected in series.</span> 

And 42 GeV takes our electron very [close to the speed of light](/relativity-tutorial.html#relativity-and-the-acceleration-of-electron-bunches) as we show in the relativity tutorial.


#### Plasma acceleration

In the plasma, it is the same principle. An electric field is created in the plasma by the beam itself and, in a sense, the beam accelerates itself. But conservation of energy says that’s not possible so what is actually happening is that electrons at the front of the beam bunch are using some of their energy to ionize the Lithium vapor and push the ionized electrons away from positive Lithium ions which creates a very strong local electric field in the plasma between the separated positive Lithium ions and the negative Lithium electrons ; and that plasma electric "wakefield" (where the Lithium electron cloud is closing behind the end of the beam bunch) accelerates electrons at the back of the beam bunch. The bunch enters the plasma accelerator from the Linac with all the electrons having approximately the same energy, 42 GeV, but the bunch exits the plasma with a wide range of electron energies. You may wonder how this works since it might seem the bunch should quickly spread out in length as some electrons gain energy and others lose energy but [relativity](/relativity-tutorial.html#the-electron-bunch-stays-together-in-the-plasma-accelerator)
 comes to the rescue making the seemingly impossible possible.

Since we know the Linac takes two miles of acceleration to produce the first 42 GeV and the plasma accelerator produces another 42 GeV in about one meter, we know the total voltage between the beginning and end of each device is 42 GV (1 GV = 1 gigavolt = 10<sup>9</sup> volts). In accelerator talk it’s more useful to talk about the volts per meter (V/m), also known as the potential gradient or simply the gradient. The Linac gradient is 42 GV / 3000 m or 14 MV/m and the plasma gradient is about 42 GV / 1 m or 42 GV/m. The plasma gradient is 42 GV / 14 MV = 3000 times as strong as the Linac’s gradient. 

Why can’t the Linac create an equally high gradient? The Linac accelerating components are made of ordinary solid matter such as various metals and ceramic insulators, all the things that go into ordinary electrical components. When those components are exposed to strong electric field gradients, the materials begin to break down electrically. When you scuff your shoes on a rug in dry weather and then get a shock when you touch something, there is an electrical potential between you and the object you are about to touch. Before you actually touch it, the air in between ionizes, that is, electrons actually are pulled off of gas molecules of the air creating an electrical path for the charge to jump between you and the object. Gradients in the range of 10 MV/m are about the highest possible with structures made of ordinary solid materials. (This limit can be increased by perhaps a factor of five by operating at temperatures near absolute zero.) The gradient in the plasma is entirely different in origin and can go much higher because material breakdown is not a problem. In fact, material breakdown (gas ionization) is actually an essential part of creating the potential in the plasma accelerator.

When a charged particle like an electron is shot through anything (solid, liquid or gas) made up of atoms, the electron may interact with an atom and have an effect on it. This effect is limited by how much energy the electron has, that is, how much energy it can give up to make something happen to the atom. The atomic theory of matter says atoms are made of nuclei of protons and neutrons surrounded by electrons. The positive charges of the protons repel each other and the negative charges of the electrons repel each other but the positive charges of the protons attract the negatively charged electrons and the whole package is in balance and stays together (the neutrons help keep the peace between the protons packed so close together in the nucleus.)

The simplest atom is hydrogen with a lone proton holding on to a lone electron. The plasma material is Lithium with three protons (plus 4 neutron peace keepers) holding on to three electrons. If a charged particle comes flying at an atom, in our case, the flying charged particles are the beam electrons, the moving electron can have various kinds of interactions with the Lithium atom depending on how much energy the electron has and how much it gives up to the atom it hits. A very low energy electron may only have enough energy to jostle the Lithium and give it a bump that moves the whole atom in one piece. A little more energy and it can “excite” one of the Lithium electrons. The electron remains attached to its atom but it jumps to a higher energy state and then in a while jumps back down emitting a small burst of light. This is what happens in florescent lights. This level of “jostling” involves the transfer of a few eV of energy. Remember the 1.5 volt AA battery can at most give an electron 1.5 eV of energy which is enough energy to light up an LED or warm a wire but not enough to cause fluorescence. 

With even more energy transferred to a Lithium atom, an electron may be completely knocked free and the remaining atom, less one electron, is said to be ionized creating a net positive atom (a Lithium ion) and a negatively charged electron moving around separately from each other. Since protons and neutron are nearly 2000 times heavier than electrons when an ionization event takes place the ion has a great deal of inertia and doesn’t move nearly as far or easily as the electron. And this is the key to what happens in the ionized plasma. (The ion has seven nucleons so it is 7x2000 = 14000 times as heavy as the electron.)

With a very dense bunch of very high energy electrons passing through the Lithium vapor, essentially all the Lithium atoms along the beam path have at least one electron ionized. The beam is moving at nearly light speed and leaves an unmoved trail of positive ions in place but the ionized electrons, being far lighter, are pushed away by the negative charge of the beam bunch. The ionized electrons are the blue cloud in the simulation shown in Figure 3 of the energy doubling research paper. Then the plasma ionized electron cloud is pulled back towards the Lithium ions and closes behind the bunch after it passes, creating an electric field that accelerates the electrons in the tail of the bunch.


## Linear colliders versus ring (circular) colliders

Conceptually both types of colliders involve colliding bunches of particles coming at each other from opposite directions. But the technological differences are considerable. In a ring the two opposing particle bunches go around the ring in opposite directions millions of times per second and thus collide at one point on the ring millions of times per second. In both types of colliders, only a tiny fraction of the beam particles hit a particle in the opposing bunch. The vast majority of particles simply pass through the opposing bunch unaffected. In a linear collider each bunch passes through the opposing bunch only once and is discarded. These essential differences create very different demands and opportunities for the two types of colliders. 

The ring collider bunches can be much larger, much less dense because the bunches have many more opportunities to create a collision of two opposing particles. On the other hand the physics of ring colliders makes it much more difficult to create short focused bunches. Also, to get to higher particle energies requires much larger ring accelerators than linear accelerators. And plasma accelerator boosters are not an option at a ring accelerator. 
