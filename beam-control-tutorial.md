---
layout: default
title: Tutorial - Controlling beam particle trajectories with magnets
pagetype: tutorial
---

### Overview


Accelerator particle beams are accelerated to higher energies (higher speeds) by the [force of electric fields](/beam-acceleration-tutorial.html#charged-particles-are-accelerated-by-electric-fields)
 that they are guided to pass through. However, the path the beam follows, the direction the beam moves is controlled by magnetic fields. In both techniques the underlying physics is the theory of Electromagnetism given its final formulation by James Clerk Maxwell in the 1860s. Charged particles experience a force pushing them when they pass through electric and magnet fields although the direction and amount of the two kinds of pushes are quite different. We imagine electric and magnetic fields represented by arrows where the direction the arrow points is the direction of the field and the strength of the field is represented by the length of the arrow, the longer the arrow, the stronger the field. 

#### The magnetic and electric force laws

A positively charged particle is pushed in the direction of the electric field arrow. That’s pretty straightforward to imagine. And if the particle is negatively charged it is pushed in the direction opposite to the arrow of the electric field. The way a magnetic field pushes a charged particle is more complicated. The first thing that is different between the way the two kinds of fields affect the motion of charged particles is the electric force is the same no matter what the speed of the particle. The same amount of force is applied whether the particle is standing still when it first experiences the electric field, it is the same amount of force if it is moving slowly and it is the same amount of force if it is moving very fast. 

We want to contrast the electric field force with the idea the magnetic field no matter how strong applies no force to a particle that is standing still, that’s one thing that may seem unusual about the magnetic force. The second strange thing about the magnetic force is that a particle is only pushed sidewise to the direction it is already moving and does not add any energy (or speed) to its motion, the magnetic field just changes the particle's direction. 

The exact rule for magnetic force can be imagined as follows: make your right hand flat with fingers out straight and your thumb pointing perpendicular to the side so your hand is making a backwards L shape. Now imagine your fingers pointing in the direction the beam of charged particles is moving. Now rotate your hand so you can imagine that the magnetic field is piercing the back of your hand and pointing out from your palm. (By convention the arrow goes from north pole to south pole. By convention the electric field arrow goes from positive to negative electric poles.) In this orientation of your hand the magnetic field force on the particle will be in the direction of your thumb. That is, sidewise to the direction of the particle's motion and also sidewise to the direction of the magnetic field. ( Caveat: When the magnetic field is only at an angle to the beam direction you will need to bend your fingers at the knuckles so they point along the beam and the magnetic field still goes through your palm perpedicular to the palm.)

Now imagine this force turns the direction of the particle beam so rotate your hand (still making the L shape) around the arrow piercing your palm so the beam has a new direction. If the beam is still in the presence of the magnetic field it will continue to curve in the direction your thumb points (your hand remains rigid so the thumb keeps turning too) and that will require you keep rotating your fingers to keep pointing in the changing direction of the beam's motion. 

![text](/beam-control-1.jpg)

To express the two force laws mathematically we symbolize the two kinds of forces due to an electric field, **E**, and a magnetic field, **B**, where **bold face** means the variable has both a magnitude and a direction (in math jargon, it is a vector quantity.)

<span class="eq">**F**<sub>E</sub> = q**E**,</span>

where q is the particle charge and **F**<sub>E</sub>, the electric force, and **E**, the electric field, point in the same direction.

<span class="eq">**F**<sub>B</sub> = q(**v x B**),</span>

where q is the particle charge, **v** is the particle velocity, **F**<sub>B</sub>, the magnetic force, is perpendicular to both **v** and **B**, and **v x B** is a vector whose magnitude is vB and whose direction is perpendicuar to both the direction of **v** and the direction of **B**.

#### Magnets and the beam path

If the magnetic field covers enough area, the beam passing through the field will eventually go in a circle all the way back to where it started and the beam will continue to go in that circle always at the same speed since the force is always sidewise so it never causes the beam to speed up or slow down. If the beam only pass through a small area with a magnetic field the net effect will be to change the direction of the beam by some angle, maybe a degree maybe much more, maybe much less. How much the beam turns and how tightly it turns depends on the strength of the magnetic field and how long the beam is passing through the field and also, one more factor we need to emphasize. The force on the beam depends not only on the strength of the magnetic field and the charge of the particles, but it also depends of the speed of the particle, the faster the beam is going, the stronger the force on it. The magnetic force on a beam is much more complicated than the electric field force. 

What is useful about the magnetic field force is that it can be used to control the direction of the beam as a whole and also control the direction of the individual particles in the beam. The simplest kind of magnet is the kind everyone is familiar with, a dipole magnet, where "dipole" means two poles, traditionally called North and South although they could just as easily be called positive and negative or zero and one or blue and red or whatever you want. If a beam passes through a dipole magnet the direction of the beam will be changed, which is very useful for guiding beams where you want them to go with a series of magnets turning the beam this way and that way. This much is pretty easy to imagine. But there are other very useful things that can be accomplished with more complicated magnetic field shapes than just the simple dipole field. 

#### Focusing the beam bunch

Consider the problem that the beam consists of negatively charged electrons that repel each other. How do you keep the beam bunch together? Imagine you have a desired path you want the beam to follow. Imagine a simple straight line path. Now imagine the beam is spreading out as it travels along the path, some electrons are right on the path but some are some various distances away from the path and are diverging. We would like to bend the direction of electrons that are off the path back towards the path. (Yes, once they get back to the path they will overshoot and get further away on the other side of the path but we will deal with that soon.) It turns out we can make a complicated magnetic field that will do exactly what we want. It will bend off path electrons back towards the path and even better yet, the further off the path it is, the more it gets bent. We can imagine that what we need is a magnetic field that is perpendicular to the direction of the beam and the strength of the field is zero on the path and the field gets stronger the further we get from the path. That way, particles right on the path are not bent at all and the further a particle is off the path, the more it will be bent back towards the path. 

A kind of magnet system that can do this is a quadrupole magnet; that’s a magnet with four poles. So far we have considered simple dipoles with the same field strength across the magnet. What is a quadrupole? In a dipole there is a north pole opposite to a south pole. In a quadrupole there are two north poles opposite each other and perpendicular to them are two south poles opposite to each other. Thinking of a clock face, the two north poles are at 12 o’clock and 6 o’clock and the two south poles are at 3 o’clock and 9 o’clock. Or you could turn the whole thing 90 degrees and the south poles would be at 6 and 12 and the north poles would be at 3 and 9. Or you could turn it 45 degrees and the north poles would be at 1:30 and 7:30 and so forth. 

If you look at the diagram of the field direction in a quadrupole you see that the arrows follow a curved path from both north poles to both south poles in a completely symmetric path. First thing to notice is that the field strength gets weaker the closer you get to the center of the magnet. So that’s where we want the beam path to go, put the quadrupole so its center is on the desired beam path. Particles on the path will not feel any magnetic pushes. The direction and strength of the field at various locations are indicated with black arrows. Now imagine an electron beam is going into the page indicated by the circle with a cross in it symbolizing the feathered tail end of a real arrow. To use the right hand rule remember electrons are negatively charged so the force direction is now opposite the way the thumb points in the right hand rule. 

Red arrows in the diagram indicate the direction the electrons will be pushed as they pass through the quadrupole. The picture is quite complicated. But notice what happens along the 45 degree line marked C for convergence. If you imagine each red arrow marks an electron you can see that every electron is being pushed towards the C line and the further the electron is away from the C line the strong component of the push towards the C line.That's exactly what we wanted. 

But wait, have you noticed something is wrong here? If instead of the C line you look at the D (for divergence) line 90 degrees to the C line all the red arrows have a net compenent pushing away from the D line and the further from the D line the stronger the push away from it. So we have half sovled the problem and half made it worse. 

It seemed like a good start on shepparding the flock. But what if after the beam passes through the quadrupole it passes through another quadrupole turned 90 degrees to the first one? Now those particles bent outwards will be bent inwards. That’s good, but those originally bent inwards now get bent outwards. That’s not so good. It turns out that the overall effect of having a pair of quadrupoles (called a quadrupole doublet) overall keeps the beam from blowing up and the beam goes through an expanding and contracting motion as it goes through a series of doublets all along the beam path. The net result is that at any point along the Linac accelerator the beam’s bunch diameter varies although its bunch length remains the same. These "focusing-defocusing" magnet tricks are used to bring the beam to a very small diameter (call “the spot size”) just as it enters the plasma accelerator. 

#### Accelerator physics

Accelerator physics is the fascinating field of creating, accelerating and guiding particle beams. We have barely scratched the surface of the subject here. Another interesting topic important to the plasma acceleration research is to ask if there is some way to address another cause of beam blowup, namely, when the electron bunch is created in the first place the electron have thermal motion like any gas. One might wonder if it is possible to “cool” the bunch before accelerating it so there is less tendency for blow up? Indeed, it can be done. A Nobel prize was won for the discovery of a way to cool the protons in a proton beam in the 1980s. The accelerator at SLAC added damping rings as part of the SLC project. We have mentioned elsewhere that the FFTB, where the initial plasma acceleration research was done, was built to learn how to create and control very small spot sized beams and part of accomplishing that goal was the development of the damping rings for the Linac to "cool" the electron bunches to make smaller spot sizes.


![text](/beam-control-2.jpg)

![text](/beam-control-3.jpg)
