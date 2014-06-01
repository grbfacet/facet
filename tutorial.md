---
layout: default
title: tutorial
---



Background physics tutorial for the energy doubling paper

Overview: 

This is a review of some of the physics behind the research paper. You can read it in order as a tutorial. When you read the paper exposition there are links into the relevant sections in this tutorial. 

We discuss several physics topics in this tutorial. The end goal is to explain how the electron particle bunch retains its compact form and why electrons of different energy do not change relative position as the rear part of the bunch is accelerated and the front part is decelerated. From our experience of human level phenomena that makes no sense and an understanding of relativity theory is required and is provided here. 

To lead up to this final result we present information on the Newtonian theory of accelerated moving bodies as well as the Einsteinian relativistic theory and we discuss some general issues about how one theory can replace another over time as science progresses. This approach of focusing on a very specific result, the bunch integrity, is in harmony with the idea of looking at a journal paper as focused on one very specific result. Thus, we aim to have a very narrow focus and to drill down deep rather than describing a broad array of topics as is typical of textbooks and most scientific expositions written for a lay audience.  

We have indicated extended calculations by noting when a calculation begins and ends. The idea is that you may skip over the details, especially on a first reading of the tutorial. But to get a real feeling for what it is like to actually do physics calculations we encourage you to eventually take pencil/pen, paper and calculator and work through each step in a calculation. Take your time and enjoy the experience of understanding how it is done. 

Aside on the terms “classical”, “quantum” and “modern” as used by physicists:
The term “classical” as in “classical physics” or “classical mechanics” or “classical electrodynamics” or “classical statistical mechanics” or many other uses is contrasted with the term “quantum” as in “quantum physics” or “quantum mechanics” or “quantum electrodynamics” or “quantum statistical mechanics”. This usage has a precisely understood meaning among physicists. Classical physics is all of physics that does not require consideration of quantum effects. The term “classical” does not refer to a historical era although its etymological origin is related to a historical reference. Even today, there are new discoveries in many areas of classical physics. The revolutionary Einstein theories of relativity and gravitation are part of classical physics since quantum effects are not part of these theories. 

In western culture at large, “classical” as a historical term refers to the Greco-Roman era two millennia ago. In western culture at large the term “modern” has a multitude of historical period references. Perhaps a good example of the confusion possible about this adjective is when we consider that the modernist period in English literature ended sometime before World War II, followed by the post-modernist period which also has had its zenith and is essentially over today. In other uses in western culture, the term “modern” often refers generally to a time that began with the Renaissance, creating the three western periods classical, medieval and modern. In physics the term “modern” is also used in contradictory ways but one important usage is when it is said that modern physics began with Newton. 

Aside: Calculus and modern physics

Although we will not do any calculus in this physics tutorial it will be helpful to understand what calculus, invented by Newton, did for physics. Newton’s calculus is the mathematics of change and accumulation. Modern physics began with Newton’s invention of calculus. From, at least, the ancient Greeks, people had tried to understand change but until there was a mathematical tool available to describe change quantitatively, the study of change was essentially limited. 

One could concoct any manner of explanation for change, or a more specific form of change, motion, but without the ability to make numeric predictions one was left with only trying to demonstrate the logic and consistency of a theory in a qualitative way. Newton changed all that with his invention of differential and integral calculus. Differential calculus is the mathematics of change, more specifically, rate of change and integral calculus is the mathematics of accumulation, or again, accumulation relative to some amount of change. 

Some important points are implied in these two paragraphs. Let’s fill those out now. Suppose someone said something changed by 5 feet or 5 dollars or 5 seconds or 5 gallons. Implicit in change is a starting point and an end point, i.e., change is always relative to two events, a beginning event or place and an ending event or place. It is 5 miles from town A to town B. The stock price increased 5 dollars from Feb 1 to March 1. It took 5 years to transform the grapes from ripe on the vine to the wine in our glass. It took 5 gallons of gas to make the trip from Los Angeles to San Diego. 

When the two points of reference differ by some kind of quantitative measure we can talk about a rate of change. If it took 10 minutes to drive the 5 miles from A to B we had an average rate of location change (speed) of 5 miles per 10 minutes or 30 mile per hour. If the stock started at 100 dollars per share, then it increased 5% in one month or 60% a year. In the case of the grapes to wine there is no quantitative measure of the difference between grapes on the vine and wine in the glass so there is no quantitative rate of change involved. The distance covered with the 5 gallons of gas depends on exactly where in LA you leave and where in San Diego you arrive. Let’s just say the trip was 100 miles. Then the rate of gas usage was .05 gallons per mile or more commonly we invert the ratio and say 20 miles per gallon. 

Now let’s look at the idea of accumulation. If something has a rate of change, 30 mph, 60% per year, or 20 miles per gallon we can apply that over a specific amount of the denominator quantity. If we drive at 30 miles per hour and we do that for six hours we accumulate 180 miles traveled. If we hold the stock for three years at a rate of increase of 60% per year the stock will accumulate an increase of 180% (we ignore compounding here). If we want to travel (accumulate) 400 miles at a gas usage rate of 20 mpg it will take 20 gallons of gas. If gas sells at the rate of $3.00 per gallon we will accumulate a gas cost of $60 for our 400 mile trip. 

Change and accumulation 

Rate of change and accumulation are two sides of the same coin, if you have one, you have the other. This is what’s known as the fundamental theorem of calculus, that differential calculus is the inverse of integral calculus. Let’s now talk about calculus. In the examples we have given, we might call them difference calculations, calculations based on a constant rate of change over a fixed amount of change. For example 30 mph was a rate of change and if we applied it over 3 hours we would cover 90 miles. But in real life a car’s speed is constantly changing, a stock price is moving up and down at a changing rate and even our gas mileage varies somewhat with driving conditions which is exemplified in the citation of city and highway gas usage rates provided on all new car stickers. 

In fact, new cars now have a gauge that tells you the “instantaneous” mpg. If we tromp on the accelerator leaving a stop sign, our gas mileage rate might be quite low, say 10 mpg in a car that normally averages 35 mpg. On the other hand if we are speeding down the freeway or going down a long hill and take our foot off the accelerator we will typically see 99.9 mpg, usually the biggest number the gauge can show. In fact, if we put the car in neutral and turn off the engine and coast, our rate is actually infinite since we are covering distance without using any gas at all.  

These are examples of change and accumulation taken from familiar daily life. What are some examples taken from the world of physics, the study of change in the world of matter? The motions of objects like planets, gyroscopes, vibrating guitar strings, sound waves, the flow of air over a plane wing or the flow of fluid in a pipe are examples that are all explained by Newton’s laws of force and motion. The amount of heat it takes to boil water, i.e., the amount of heat to raise the temperature a certain number of degrees, the amount of disorder (entropy) increase in a chemical reaction, the atmospheric temperature change of a parcel of moist air rising after being heated by the hot ground on a sunny day, and many other examples are explained by the theory of thermodynamics. The rate of battery discharge in a laptop is explained in electromagnetic theory. 

Notice all these examples from modern physics involve quantitative rates of change and accumulation and hence require the use of differential and integral calculus. None of this is possible without Newton’s invention. Leibniz is also credited with inventing the calculus and we won’t go into that controversial bit of history. Here we simply side with Newton because the scientific tradition of applying the calculus to problems of science indisputably begins with Newton. If we were primarily interested in the mathematics and philosophy of infinitesimals instead of physics we would put emphasis on Leibniz’s contributions to understanding the mathematical theory of the calculus. For Newton calculus was simply a tool to get on with physics. For Leibniz, calculus was a philosophical and mathematical idea.

Instantaneous rate of change 

What Newton did was work out the mathematics of instantaneous rate of change, differential calculus, and the mathematics of accumulation of a quantity whose rate of change varies from instant to instant, integral calculus. What is an instantaneous rate of change? It is thought of as the limit of a smaller and smaller amount of change. We can measure the average change of a stock price over each year, over each month, over each day, over each hour, minute or second. In fact some computer trading programs work on price changes measured in thousandths of a second. We can imagine a similar limiting process for the speed of a car or anything else that has change that can be measured with numbers. 

Let’s look at what Newton is perhaps most famous for, the combination of his laws of motion with his theory of gravity which he successfully applied to predicting the motion of planets. His theory of motion is that forces cause changes of motion. This idea contrasts with Aristotle’s idea that forces cause motion. According to Aristotle the shot arrow moves through the air because the air somehow keeps pushing it along. There is a long and fascinating history from Aristotle to Newton with Galileo playing a crucial role in recognizing that a body in motion has inertia and simply keeps moving in a straight line at the same speed, now known as Newton’s first law of motion. 

Without going into the history we should be careful not to disparage the ideas of the ancients. For example, consider a horse pulling a cart, something very familiar to Aristotle. The horse pulls with a constant force and the cart moves at a constant speed. If the horse pulls harder, the cart moves at faster speed, so obviously speed is proportional to force. But Newton says change of speed is proportional to force. In our modern point of view the cart does indeed move with a speed proportional to the pull of the horse, but it also is affected by other forces, in particular the force of friction in its wheel bearings and all the small bumps in the road. Newton would say those forces resisting the motion exactly balance the pull of the horse and the cart moves at a constant speed because the total of all forces on it balance out to zero. 

However, the ancients accepted steady motion without force in the heavens where the sun, moon, planets and stars moved across the sky at a steady speed with nothing pushing them. But this was another of Newton’s great accomplishments to assert that the laws of motion on the earth were the same as those in the heavens whereas it is obvious to common sense that the sky is an entirely different kind of place than around the surface of the earth. So Newton unified many different phenomena under one set of laws. 

Newton gave a quantitative law of gravity. Not just that the gravity of the earth pulled objects to it but he said quantitatively how strong the pull was. The further you go from the earth into space the weaker the force. In particular the force gets weaker as the square of the distance. If the force is a certain amount at 100,000 miles then it will be four times as weak at twice the distance, 200,000 miles and nine times as weak at three times the distance, 300,000 miles. 

From a mathematical point of view the force could have had any kind of relation to the separation distance. You could write a mathematical formula for the force being stronger with distance. For example the force, F, goes as d, the distance. With this formula, launching objects into space would be impossible because as they get further from the earth the rockets have to push even harder to keep going and eventually, they run out of fuel and fall back. (There actually is a force that gets stronger as the attracting objects get further apart, the strong force, the force between quarks in protons and neutrons. That is the reason we can never isolate a single quark.) Or the force could go as the inverse of the distance, if the force is a certain amount at 100,000 miles, it would half that at 200,000 miles and a third at 300,000miles. Compare this to the inverse square force formula mentioned above where at 300,000 miles the force is one ninth what it was at 100,000 miles. 


As you can see all the different possible gravity force laws predict different forces at different distances and we can simply watch how objects move around the earth and the sun to see which force law gives a prediction that agrees with what we see in nature and then we say, that is the true force law for gravity. This is exactly what Newton did but to do it he needed his calculus. Aristotle could not have tested these different force laws very easily since he didn’t have calculus.

Let’s look at Newton’s monumental motion law, the second law that says a force produces a change of speed and the change in speed is proportional to the force. It could be that the change of speed is proportional to the force squared or that force squares the speed or cubes it or anything else. An infinite number of force laws are mathematically possible but the aim is to find the law that matches reality. Let’s consider gravity force acting on an object near the earth’s surface. We won’t show why but when you calculate the force of gravity using the inverse square of the distance law, the distance to be used is the distance of the object from the center of the earth, not from the surface. 

For an object just a few feet above the surface we calculate the force based on the fact that the object is about 4000 miles from the center of the earth not based on a few feet. Now suppose we are interested in the motion of an object dropped out of a helicopter hovering two miles in the air. As it falls two miles the force of gravity on it will be a tiny bit stronger when it reaches the last, say, one foot from the ground. It would be the difference between the inverse square of 4002 and 4000. This is a tiny difference so we usually just say the force of gravity near the earth’s surface is the same at any point above the surface but within a few miles. If we were doing a very precise measurement we would need to calculate with a changing strength of the force as we got closer to the earth and notice the words, “change of force”, and that should tell us to do the problem right will require the mathematics of change, differential calculus! 

It turns out that Earth’s gravity near the surface changes the speed of an object by about 10 meters per second every second the object is falling. If we drop the object out of the hovering chopper, in the first second it is falling it will go from a speed of zero to a speed of 10 meters per second. In the next second it is falling it will speed up another 10 meters per second. It ends its first second of fall moving 10 m/s and by the end of the next second it has gained another 10 m/s so it is moving at 20 m/s. Another second of fall with add another 10 m/s to its speed and after three seconds it will be moving at 30 m/s. After ten seconds of falling it will be moving 100 m/s. 

Suppose we want to know how far the object falls in one or two or ten seconds? If it was falling at a steady speed we can easily do the math, but its speed is constantly changing, constantly increasing. How do we calculate the distance it falls? This is a question of accumulation, integral calculus: accumulation of distance over a period of time with a non-constant speed (steadily increasing in this case). We want to integrate, add together, the amount of distance traveled over the whole time. We could imagine approximating an answer by saying in the first second it averaged 5 m/s so it fell 5 meters. In the next second it fell at an average of 15 m/s so it fell 15 meters. Add that to the 5 for the first second and it has now fallen 20 meters. In the third second it averages 25 m/s so it falls another 25 meters for a total of 45 meters after three seconds. If we keep doing the math we get the sequence 

1-5, 
2-20, 
3-45, 
4-80, 
5-125, 
6-180, 
7-245, 
8-320,
… 

Now if you’re Newton and if you are playing around with numbers like this you might notice if you take the first number in the pair, the seconds falling number and square it and divide by two and multiply by the acceleration of gravity (10 m/s per second) you get the second number! That is you would have discovered 

d = 1/2gt2, where g = 10 m/sec per second. 

We started with s, speed, 

s = gt and we “integrated” that formula over time. 

If we were Newton, we might have wondered about integrating the new formula involving t2 over time and we would find we get the result 

1/3 x 1/2gt3 and if we integrated that we would get 
1/4 x 1/3 x 1/2gt4. 

We would have found that the integral of gtn over t is 

1/(n+1)gtn+1. 

Differentiation is going the opposite direction. Just from a mathematical point of view, if you have a formula for the accumulation of distance and you want to know how fast you are accumulating you go the opposite way. If you accumulate kxn after x units of total accumulation then at that moment you are accumulating at the rate of 

nkxn-1. 

Newton’s achievements in physics were staggering but without his achievement of the calculus none of what we know as physics today would have been possible because physics, the laws governing the material world, almost always involve relations between changing and accumulating variables. And that is calculus. It is interesting to note that Archimedes actually developed the beginnings of integral calculus. Two events buried Archimedes great discovery, his killing by a Roman soldier and the predominance that was given over time to Aristotle’s ideas. Aristotle had theories about everything but Archimedes only focused on basic inanimate natural phenomena and was seen as a narrow specialist and posterity mistakenly accepted Aristotle’s judgment over Archimedes. The reason for this was probably that Aristotle was a generalist and tried to come up with a consistent logical theory of everything. Today we tend the other way and compartmentalize knowledge. 


Aside: Units of measure prefixes indicate powers of ten:

The reader is probably familiar with the use of prefixes on units of measure in the metric system to indicate multiples or fractions of the unit in powers of ten. The meter, a unit of length (about 3 ft), is abbreviated with the letter “m”. Just like we say 7 ft, we also say 13.2 m. Unlike the English system of measure we indicate 1000 meters as 1 km (one kilometer) and we indicate 1/1000th of a meter as 1 mm (one millimeter).  

Going up in multiples, 

k for kilo indicates 103 = 1000 (thousand), 
M for mega indicates 106 = 1,000,000 (million), 
G for giga indicates 109 = 1,000,000,000 (billion) and 
T for tera indicates 1012 = 1,000,000,000,000 (trillion). 

Sometimes in particle physics literature a few decades ago B was also used for a billion. 
The scale of energy reached by particles in current particle accelerators is in the 100 GeV to 10 TeV range.  We explain the eV energy unit below.

There is a corresponding series of notations for fractions of a unit. 

1 m = 1 meter. 
1 mm (one millimeter) = 10-3m = one thousandth of a meter. 
1 µm (one micrometer, where µ is the Greek letter mu) =10-6m = 1 millionth of a meter.
1 nm (one nanometer) = 10-9m = 1 billionth meter. 

And further steps of one thousandth are pico (10-12) , femto (10-15) , atta (10-18).


Force, energy, work, potential energy, energy of motion (kinetic energy), electric potential and all that… 

One of the challenges of understanding physics is keeping in mind several interrelated concepts simultaneously. This problem is not restricted to physics. To understand such things as economic and biological systems the interplay of many concepts occurs. The ability to think in abstract ideas is widely believed to be a skill possessed only by humans. Perhaps other animals can form abstract ideas but what does seem to be unique to us is the ability to think not only about abstract ideas but to go a level further and think in terms of abstract relations between abstract ideas. For example, force, mass and acceleration are abstract ideas. Newton’s famous 2nd law, F = ma, is an abstract relation between three abstract concepts. To understand his law we first have to understand each of the three component ideas and then we have to understand the relationship the law expresses. And we will see that some of Einstein’s relativistic concepts and relations are even more complex. So we want to spend a little time emphasizing the differences and relations between several basic concepts involved with understanding objects in motion. 

In the most general point of view physics is often about how things change, where motion is one of many kinds of change, change of position in space. And it is important to keep in mind that change always involves both a before and after state. These basic ideas about change are usually implicit in physics discussions but lack of awareness of them can sometimes cause confusion. For example, that fact that a force exists does not mean it is doing work. To do work there must be a beginning and an end condition where something has been moved by the force. 

We will discuss a variety of related concepts from what is called dynamics of motion and we will discuss both Newtonian and the Einsteinian (Relativistic) dynamics. It is important to keep track of which specific dynamic concept is being referred to in a particular situation. You are probably familiar with the Newtonian theory of motion that a force causes a mass to accelerate. The same is true in relativistic theory but the details are different. In Newtonian theory the object being accelerated has an unchanging inertial mass in relativistic theory the inertia of an object increases with its speed. The amount of material in the object is unchanged in the sense that it still contains the same number of atoms but the atoms each get “heavier” or more resistant to being accelerated the faster they move in the relativistic version. 

Thus, in Newtonian theory with enough force applied an object can be accelerated to any desired speed, in particular it can be accelerated beyond the speed of light. Relativity says its speed is limited to only approach the speed of light. Both theories would see the same force being applied but the result would be different. The relativistic increase of inertial mass is such that the closer its speed gets to the speed of light, the heavier it gets and its inertial mass approaches infinitely heavy as its speed approaches the speed of light. 

A body in motion has energy of motion, called kinetic energy in both theories. Energy can take various forms besides energy of motion. A stretched slingshot has potential energy that can be converted to kinetic energy of the stone when the sling is released. The stone, shot straight up in the air, will slow down (“decelerate”) because the force of gravity is pulling it down and that slows it until it stops at some height. Now all its energy has been reconverted to potential energy of height in a gravitational field. As it begins to fall it picks up speed and thus kinetic energy as it goes lower and it loses its gravitational potential energy of height. According to the law of conservation of energy the total of both kinetic and potential energy is constant and energy swings from one form to the other. 

Of course, we are disregarding loss of motion energy to friction with the atmosphere which is converting motion energy into heat energy of the air. Once the increased temperature of the friction heated air is accounted for the law of conservation of energy is maintained. Thus the energy swings from the potential energy in a stretched rubber band to the kinetic energy of motion to the potential energy of an object in a gravitational field back to kinetic energy of motion and when the stone hits the ground and stops, the energy is transferred into shock waves in the stone and the ground and the shock waves dissipate into heating the stone and the ground. Think of the extreme case of a meteor hitting the earth.

The force of gravity is something we experience all the time as a force every time we pick something up. But we just mentioned that an object raised in the air has potential energy. There are a cluster of related ideas lurking here. When we lift the object we are applying our own force to counteract the force of gravity. We apply the force over a distance, the distance we lift the object, and the technical term for that is “work” and it is simply the amount of force times the distance the force is applied. When released the slingshot applies a force to the stone to give it motion. Work creates either potential energy (raising an object or stretching a slingshot) or kinetic energy (a falling object or a stone from a slingshot). Since work, the product of a force and a distance, is energy we might turn things around mathematically from E = F x d and note that F = E/d. When E is potential energy, E/d is sometimes thought of as a potential energy gradient. 

A clarification may be in order here about the concepts of force and work. Work is a transfer of energy of one form into another form and work occurs when a force acts over a distance, which is when it moves something. A stone pillar that holds a marble statue in the air motionless for centuries is not doing any work even though the force is always there balancing the also ever present force of gravity pulling down on the statue. Gravity is not doing any work either. 

This seems counter-intuitive because when we lift something heavy and hold it motionless in the air we certainly feel like we are expending energy and doing work. And in fact we are but the work is not done on moving the object we are holding. The work is being done in our muscle tissues consisting of millions of tiny rubber bands that repeatedly tighten and relax. Each tiny rubber band contraction does indeed do work and we use up the energy stored chemically in ATP molecules and it is converted eventually to heat energy. A force only does work when it moves something.  



The electron volt, eV, an atomic sized unit of energy:

One eV is a unit of energy. One e is a unit of charge; it is the amount of charge of an electron, a proton and many other elementary particles. Electric charge comes in two kinds, positive and negative, and the charge of an electron is actually –e where e is a positive number. One V (volt) is a unit of electric potential, the capacity to create energy, i.e., to do work, with an electric force. A electric potential is closely related to a force in that a charged particle, like an electron, will be pushed to move when it experiences an electric potential, V. And one eV is the energy of motion acquired by one particle that has the amount of charge e that is accelerated through a one volt electrical potential. 

An AA battery creates a 1.5 volt potential between it’s + and - ends. A single electron accelerated freely (“freely” is an important qualification explained later) would acquire an energy of motion of 1.5 eV. Energy of motion is called kinetic energy and is given in low velocity situations, far from the speed of light, by the Newtonian formula 

ENewton = ½ m0v2, 

which is an approximation to the very famous and correct relativistic formula EEinstein = mc2.
ENewton is the Newtonian kinetic energy of motion, m0 is the particle’s mass and v is the particle’s velocity.

Let’s compute how fast a freely accelerated 1.5 eV electron would move. To do this we will need a conversion factor between the atomic level unit of energy, the eV, and the macroscopic level of energy, the Joule: 

1 eV = 1.6 x 10-19 J (Joules) where the units of a Joule are kg-m2/sec2. 

The mass of the electron is 

me = 9.1 x 10-31 kg. 

Calculation: Solving the Newtonian kinetic energy formula for velocity squared and taking the square root:

v = (2E/m0)1/2.  

Plug in the values for E and me of the 1.5 eV electron,

v = ( 2 x 1.5 eV x 1.6 x 10-19 J/eV / 9.1 x 10-31 kg)1/2 ,
v = ( 0.525 x 1012 J/kg )1/2,  

since 1 J = 1 kg-m2/sec2, J/kg = m2/sec2

v = ( 0.525 x 1012  m2/sec2)1/2,
v = 0.72 x 106 m/sec = 720km/sec ≈ 450 miles/second. End calculation.

An electron accelerated freely by a 1.5 volt AA battery would reach a speed of 450 miles per second which is about 4000 times the speed of a passenger jet plane.  But this is still only about one quarter of a percent of the speed of light so the use of the Newtonian approximation 

ENewton = ½ m0v2 

is OK as we will prove later. 

Relativity effects only begin to become important when particles reach, say 10 percent, at least, of the speed of light. As is explained elsewhere, the Newtonian formula, ENewton = ½ m0v2, begins to make a significant error only when we approach these “relativistic” speeds. 

4000 times jet speed is pretty fast, a bullet or a baseball with that speed could do a lot of damage but they are very heavy compared to an electron so how can we get a sense of the 42 GeV electron energy? Remember our 4000 times jet speed was an electron accelerated only by one 1.5 volt AA battery. To get to 42 GeV we need 

42 x 109/1.5 ≈ 3,000,000,000 

AA batteries connected in series. 

42GeV takes our electron very close to the speed of light as we will show later. 

There is something we should clarify here. When you put an AA battery in, say, a little radio, the electrons flow through the circuit but they don’t flow at the speed, 4000 times jet speed, we calculated above. They would only move that fast in a vacuum. In a circuit the electrons are constantly bumping into atoms in the wires. The electric potential starts to accelerate them and before they can go more than a few atomic sizes they hit an atom and are deflected only to start accelerating again and then to hit another atom. These collisions happens at very high rate and the net overall flow of the electrons, called their “drift” speed along the wire, is very slow, in the range of a meter per hour. 

The electrons are actually banging around at speeds vastly greater than their drift speed but most of that motion is sidewise and backwards and forwards. When the electrons hit atoms in the wire they cause the atoms to move slightly, that is they transfer some of their energy of motion to the wire’s atoms. The warmth of an object is actually the amount random atomic motion and this is why wires heat up when we run a current through them. With an old fashioned incandescent wire light bulb the wire gets so hot it begins to radiate energy in the visible light range of the spectrum. 

An electron with 42 GeV of energy actually has a very small amount of energy.

42 GeV = 42x109 eV x 1.6 x10-19 J/eV = 67 x 10-10 J. 

But in the plasma acceleration experiment tiny bunches of 1.8 x 1010 electrons at a time are used, so one entire bunch would have 

1.8 x 1010 electrons/bunch x 67 x 10-10 J/electron =  121 J of energy per bunch. 

How much energy is that? Going back to 

v = (2ENewton/ m0)1/2 ,

let’s think of a baseball which weighs 5 oz. At 28 grams/oz, that’s 

5 x 28 = 140 grams/baseball = 0.14 kg/baseball.

A baseball with 121 joules of energy will have a velocity of

v = ( 2 x 121 J/0.14 kg )1/2 = ( 1729 m2/sec2)1/2 = 42 m/s. 

What is that in mph? 

42 m/s x 3600 s/hr = 150 km/hr = 93 mph.

If you imagine being hit by a fastball thrown by a major league baseball pitcher that gives some sense of the punch packed by a 42 GeV bunch of electrons in our experiment. The SLAC Linac can produce 60 bunches per second so imagine being pelted by 60 pitchers simultaneously with each pitcher throwing a baseball at you every second. Ouch. 

Relativity theory: 

(This discussion of relativity focuses only on the aspects that are essential to understand for the purposes of understanding accelerated high energy particle beams. We will not go into many famous aspects of relativity theory such as time dilation, length contraction, the twin paradox and others.) We begin with a mostly English exposition but we gradually add some math to get actual numbers to give a better feeling for the sizes of the effects involved. On a first reading you can skip over the calculations without a problem but if you desire to know how a physicist understands relativity come back to the calculations and not only step through them in your mind but reproduce them yourself on a piece of paper using a calculator to do some of the arithmetic. It may take a little time and sometimes require figuring out exactly how a calculation was done but that is when you will really get your ideas right. The education of a physicist through course work always involves an extensive amount of mathematical problem solving both in homework and tests, not to mention in the classroom lectures. 

To get a feeling for the way relativity affects our measurement we explain how relativity applies and we will calculate some facts about 42 GeV electrons to try to give you a sense of how things work for sub-atomic sized particles moving at essentially the speed of light. 

The Newtonian theory of the energy of motion: 

Before the discovery of the theory of relativity in 1905, the Newtonian theory was always used and it said the energy, E, of a body with mass, m0, moving with the speed v, was 

ENewton = 1/2 m0v2, 

This was believed to be accurate for all speeds. This demonstrates an important feature of physics. Theories supersede older theories not by discovering that they were wrong in all cases but rather by discovering that the older theory is actually an approximation to the newer theory where the newer theory covers a wider range of situations than was available for experimentation during the reign of the older theory. This general rule only applies for theories which make numerical predictions. There must be numbers involved to give meaning to the idea of an approximation. For example the theory that the earth was the center of the universe is not a numerical theory and it is not an approximation to our current view. The difference between, “the earth is the center of the universe” and “the universe has no center” are clearly not different by a mere approximation error.  

Aside: Theories and measurement errors: 

This brings up the crucial role of measurement error in experimental science. A quantitative theory is used to make a numerical prediction about what will happen in a particular situation. The prediction is normally a number that can be measured. Let’s say the theory predicts 2.7 inches and a series of measurements are made and the result is a series of numbers like 

2.73, 2.65, 2.79, 2.69 … 

The numbers are all close to the predicted 2.7 and they have an average near to 2.7. Now, we ask the big question. Did the experiment confirm or disprove the theory? 

The answer, “confirms” or “disproves”, depends on how we account for the discrepancy between the measured values and the predicted value. We always expect errors when the variable is a real number, as opposed say to an integer, because measurement is never exact. But the more exacting question is “how big do we expect the errors to be?” Using our eyes and a standard school 12 inch ruler we might expect to measure to a precision (link to precision, accuracy, random errors, systematic errors, ) of something like a tenth of an inch. Suppose the theory predicted 2.7 inches but the theory is actually only an approximation to a better theory and the better theory predicts 2.69 inches. We will never disprove the first theory when our measurement precision is only a tenth of an inch and the difference between the two theories’ predictions is only one hundredth of an inch. To disprove the first theory we must perform measurements with precision below hundredths of an inch. Thus, in our example 2.7 inch test, the measurements did not and could not, for lack of adequate precision, disconfirm the old theory but we would say they are consistent with the old theory.

On the other hand, there is a strong sense in which the old theory is completely wrong and the new theory is “right” until the newer one is displaced by some even newer theory yet to be discovered. Perhaps we should more accurately describe this series of theories with the word “better”. Each succeeding theory is better than the last one. It is better because it correctly describes a wider range of situations than the previous theory. So what are we talking about here? A theory of physics is typically a set of principles or laws. These are general statements, energy is conserved or the speed of light will always be measured to be the same in any frame of reference moving with constant velocity relative to any other frame of reference where it is measured. In two theories one better than the last, the general statements clearly contradict each other and it is logically impossible that both are true. But what does true mean? 

For example, in the discussion of relativity below we will compare the earlier Newton theory with Einstein’s and we will see that at speeds well below the speed of light the formula for the particle energy for both theories are the same within the measurement error of the 19th century and there were no cases of relativistic speed phenomena available to measure so there was no direct indication of anything wrong with Newton. However, there was indirect evidence accumulating after the 1860s, but it was not understood until Einstein’s theory. In fact, his theory was not motivated by measurements of high speed particles. So with the range of physical phenomena available to study until the late 1890s, one could not distinguish the two theories. The predictions would have been the same within measurement error if someone had proposed relativity that early. But the principles behind the two theories flat out contradicted each other. Einstein said the inertial mass of an object changed with its speed and Newton said it stayed the same. Yet at low speeds these principles lead to the same quantitative formula as we will see below. 

We apply theories to specific situations when we make a measurement. Newton’s theory of gravity says all bodies with mass attract each other with a certain mathematically defined amount of force. But when we test that theory we apply it to individual situations: an apple falling to the ground, the moon revolving around the earth, the earth revolving around the sun, a rocket capsule sent to Mars. In each specific situation Newton’s theory can be used to calculate the motions and we can then actually measure the motions and compare the theory based prediction with the actual observed (measured) motions. Once we take into account the limits of our measurements’ precision we reach the conclusion that the measurements do or don’t agree with the theory to within those measurement precision limits.  

A related consideration applies when two theories differ significantly only in more extreme conditions. Newtonian and relativity physics only show significant differences in their predictions when we are dealing with objects with speeds near the speed of light. Cars, planes, rockets, bullets, even meteors, planets and stars move at much less than a thousandth the speed of light and the relativistic effects for those are only noticeable with very precise measurements. 

Aside on precision, accuracy, random errors and systematic errors

Although the development of plasma acceleration technology does not require careful attention to exacting measurement standards, it is helpful to understand the relevant concepts because quantitative numerical measurements are crucial to the progress of physics and are crucial to the progress of any study that involves numerical measurements. 

Precision and accuracy have different meanings. The accuracy of a measurement concerns how close the result is to the true value. The precision of a measurement concerns the amount of error in the measurement itself regardless of how close it is to the true value. Suppose we are measuring how long to cut some 2x4s for horizontal bracing between vertical 2x4s in a wall where for some reason the space between the vertical pieces varies from place to place. We measure the gap at one location and carefully mark out that length on a board and cut it. And, “rats”, it is too long to fit between the vertical boards. It is off by more than an inch, yet we made the mark of where to saw with a precision of 1/16”. We were very careful about that. Unfortunately we realize that when we measured the gap between the two verticals we measured from the left edge of one board to the left edge of the next rather than measuring the space in between the right edge of one and the left edge of the other. We made a precise but inaccurate measurement of the gap. 

These considerations lead to the concept of errors of measurement. We generally distinguish two kinds of errors called systematic and random. A systematic error is one that recurs in every measurement and is the same amount. In our board sawing example, if we had measured all the gaps first and then sawed all the braces before trying to put any of them in place we would have made the same systematic error every time when we measured each gap from left edge to left edge. Every gap would have had the same extra length in it, namely, the thickness of one vertical board, nominally 2 inches for a nominal 2x4 board. 

Suppose we have a different task, to cut many braces all the same length. We measure and mark and cut over and over. Then we lay all our braces side by side and discover they are not all exactly the same length. They vary “randomly” in length by small amounts due to the imprecision of our marking and sawing. In this case if we made very accurate measurements of each cut brace piece and plotted them in a histogram graph we would find they followed the famous Gaussian Bell curve where many are close in length to a central average but fewer and fewer have increasing errors “in the tails of the distribution”. There are other patterns of random distributions depending on the type of situation such as the Poisson which models things like number of calls per minute to some place like the IRS. The Poisson is skewed, steeper on the side close to zero frequency and with a long tail out beyond the point of maximum frequency. 


E=mc2: Einstein’s formula for the energy of motion

What formula superseded 

ENewton = ½ m0v2 ? 

The famous 

EEinstein = mc2. 

Let’s unwrap what these formulas are telling us. First we need to be clear what m, the mass, means in both formulas. In pre-relativistic, Newtonian ideas of mass, a body had a fixed amount of matter that was independent of its motion. In a way this is still true in relativity but in a way it is no longer true. We need to be more precise about what aspect of mass we are talking about. A lead ball might consist of a zillion atoms of lead and that would be true no matter how the ball is moving even according to Einstein. And each lead atom would consist of a certain number of electrons, protons and neutrons and those numbers would also be unchanged by motion, Einstein would also agree. 

Another aspect of mass however does change with motion according to Einstein. In both Newtonian and Einsteinian theory of force and motion, mass is a measure of a body’s resistance to having its state of motion changed (i.e., accelerated) by a force. We also refer to this as the body’s inertia. We all know that you have push a heavy body harder (with more force) than a lighter body to get equal motion. A normal adult can push a small auto and get it to roll. A dozen normal adults probably can’t budge a railway car on the tracks. That’s the amount of resistance to changing the motion of a body. We need to distinguish the amount of matter in a body which is unchanged by the state of motion and the inertia of a body which does change in relativity theory but does not change in Newtonian theory when a body moves faster. 

Newton’s F = ma tells us if we keep pushing a body with a constant force it will accelerate at constant rate to any speed we shoot for, even beyond the speed of light. But that assumes that m, the inertia does not change with increasing speed. If we solve the Newtonian energy formula for v we get

 v = (2ENewton/m0)1/2.

If this were true at any speed, that is, if m0 was a constant independent of speed, what speed would a 42 GeV electron have? We have put the subscript 0 on m to indicate it is an unchanging constant. 

Calculation: Let’s calculate the speed of a 42 GeV electron just leaving the Linac accelerator and let’s do it “wrong”, let’s do it according to Newton’s formula. We need a couple numbers, the conversion between eV and joules, 

1 eV = 1.6x10-19 J 

and the rest mass of an electron, 

me = 9.1x10-31 kg. 

These numbers show the vast difference between the scale of ordinary human level phenomena and sub-atomic particles and it will just get stranger as we continue. Plugging in these two factors and doing some arithmetic we get

	v = ( 2 x 42 GeV / 9.1 x 10-31 kg )1/2 ,
v = ( 2 x 4.2x1010 eV x 1.6 x 10-19 J/eV / 9.1x10-31 kg )1/2,
	v ≈ ( 1.5 x 1022 m/sec )1/2 ≈ 1.2 x 1011m/sec.

Since the speed of light, c = 3x108 m/sec 

	v ≈ 1.2 x 1011 / 3x108 = 400 times the speed of light.
End calculation.

If Newton’s formula still was accurate at 42 GeV the electron coming out of the Linac would be going 400 times the speed of light! Since relativity tells us nothing can go faster than c we can see that the m term must be increasing a very great deal to thwart surpassing c. In fact, it will have to approach infinity as the speed approaches c, as we will see shortly.

The relativistic inertial mass formula

In relativity theory we denote the mass of an object at rest (not moving) as m0 and call it the object’s rest mass. We denote the mass of the object as it moves simply by m and relativity tells us m gets bigger as the speed of the body increases. The formula is 

m = m0/( 1 – (v/c)2 )1/2, 

where c is the speed of light, 300,000 km/sec (186,000 mi/sec). 

This is a complicated unintuitive looking formula but we can tease out a feeling for it by considering different cases. 

First, it says the mass of a moving body depends on only two things: its rest mass, m0, and the ratio of its speed to the speed of light, v/c. If v can never exceed c as relativity says, then the ratio v/c will always be smaller than 1. (Actually relativity only says you cannot accelerate an object from a speed less than c to a speed greater than c. It does not rule out the creation of a particle “born” with a speed greater than c. At present, such particles called “tachyons” have never been observed.) Further, no matter what situation we might be considering for the object, its rest mass, m0, and c will always be unchanged, those are what we call physical constants. All electrons have exactly the same rest mass no matter what their motion. In all situations, the speed of light is the same (this is the basis of relativity theory). What determines the inertial mass of a moving object is simply its speed, v. 

Now let’s look at some values for v. If the body is standing still, v = 0 and if you plug v = 0 into the mass formula and do the math you will see that m = m0; m standing still is the rest mass exactly as we wanted (more on this below). Now let’s go to another extreme value, what happens when v = c? We plug that in and we get infinity for the mass. Normal particles can’t exceed c by pushing because no matter how hard and how long you push to make it go faster as you get closer and closer to c all you are doing is adding to its mass energy (inertia) and less and less to its speed. Between the extremes of v = 0 and v = c we can see the mass formula predicts a positive number for the mass. 

You may wonder how light itself can travel at the speed, c? It can because for photons, light particles, 

mphoton = 0, they are massless! 

Suppose, however, that v is larger than c, say v = 2c. We find the mass is given by an imaginary number, a normal number multiplied by the square root of -1. Such postulated particles are called tachyons and nobody has ever seen one and if they did they would behave strangely since other physics tells us they are particles traveling backwards in time. And we know we can’t get a normal particle to tachyon speeds by accelerating it because it has to acquire infinite mass first so we can only say we don’t know anything that makes tachyons impossible but we can say that we can’t create one in the obvious manner by accelerating an ordinary particle. So they are not ruled out but since we don’t know how to make one and one has never been seen, they are not ruled in either.

Now let’s have a look at what happens between v = 0 and v = c. What about v = 18.6 miles/sec (30 km/sec)?(That may seem like an odd example speed to choose but sometimes in this exposition we will make choices like that because it makes the arithmetic easier to follow later.)That’s a typical speed for objects in our solar system. A meteor or comet might hit the earth at that very high speed. The speed of light, c, is 186,000 mi/sec (300,000 km/sec) so you see why we choose 18.6 miles/sec, it’s one thousandth of c. Let’s plug v/c = 0.001 in the mass formula and we see that the mass, the inertia of the motion is 

m = m0/(1-(0.001)2)1/2 ,
m = m0/(1–0.000001)1/2 ,
m = m0/(0.999999)1/2 ,
m = m0/0.9999995 ,
m = 1.0000005m0.  

The inertia is only increased by one half of a millionth even at a speed of 18.6 mi/sec ( 30 km/sec), hardly a large amount. It’s no wonder no one noticed in Newton’s time. 

Calculation: Now let’s work backwards to find out how fast m0 must be going to double its inertia. We want 

m = m0/(1- (v/c)2)1/2 = 2 m0. 

The two m0 factors cancel and we want to solve for v starting with 

1/(1 – (v/c)2)1/2 = 2. Let’s move things around a little to get 
(1-(v/c)2)1/2 = ½. Let’s square both sides to get 
1 – ( v/c )2 = ¼. Let’s rearrange to get 
( v/c )2 = ¾. Now let’s take the square root of both sides to get 
v/c = (3/4)1/2 ≈ .87 or 
v ≈ 0.87c. End of calculation.


Thus,v is about 87% of the speed of light or v is about 160,000 miles/sec when the inertial mass reaches double the rest mass. 
So the inertia of an object only doubles by the time it reaches 87% of the speed of light. We can try a few more values for m, say m = 10m0 and will find for that amount of inertia, v is about 99.5 % of the speed of light. So the inertia really starts to pile up very close to the speed of light. And we saw from the famous Einstein formula for relativistic energy the energy goes up in proportion to the mass. From this we can work out that there is very little difference in velocity if we double the energy of an electron from 42 to 84 GeV. 

By comparison, if the Newtonian formula were correct any time you double the energy of motion of an object you have increased its speed from v to √2v or about a 40% increase for each doubling of the energy. Thus our normal sense that things really speed up as you push them harder is not true near the speed of light, instead they just get harder to push. It’s a little bit like eating. We eat for energy and up to a point a meal gives us some energy to move around. But if we eat a lot, our body just stores it as weight and a lot of weight makes it harder for us to move. 

Thus our initial little electron bunch 12µm long with all the electrons at same energy now has particles with energy as high as 84 GeV, some at the original 42 GeV, and many that have lost energy to well below 42. But because they are already nearly the speed of light the speed difference between them is so small that the bunch stays pretty much the same size (more on this later). This is, of course, not at all how we think about objects that are accelerated. The Porsche leaves the Prius in the dust with its more powerful engine. This is a great example of how what we know under conditions that our body size and our senses are familiar with may not at all be normal at more extreme conditions of speed where relativity replaces Newtonian laws or small size where quantum mechanics replaces Newtonian laws. And most subatomic physics processes require the simultaneous use of both new theories, relativity and quantum mechanics, to correctly explain what happens. 

Where Newton approximates Einstein

We stated above that Newtonian theory is an approximation to relativity theory. But when we look at the two formulas for energy, 

ENewton = 1/2 m0v2 and 
EEinstein = m0c2/(1-(v/c)2)1/2. 

It’s not at all obvious that the first is an approximation to the second. The way to make this more precise is that we want to see that the second one looks more and more like the first one when v/c gets smaller and smaller. We already noted that at v =0 EEinstein does not equal 0 but ENewton does equal 0. So what is that about? We can use a Taylor series expansion of EEinstein to explore this issue. 

The Taylor series expansion of a function
A function of a variable x can be expressed as an infinite sum of terms:

	f(x) = f(0) + f’(0)x + (1/2)f’’(0)x2 + (1/2x3)f’’’(0)x3 + (1/2x3x4)f(4)(0)x4 + …

The nice thing for us about Mr. Taylor’s series can be seen if you consider a case where x is much smaller than 1 and close to 0. When you take a number smaller than 1 and near zero and calculate it’s powers (multiples of itself), those powers rapidly get much smaller. If 

x = 0.1, then 
x2 = 0.01, 
x3 = 0.001, 
… 
x8 = 0.00000001, 
…. 

And this means as you go further out in the sum of the series those terms are getting small very fast whenever the f(n)(0) terms stay relatively small because they are multiplied by two rapidly shrinking numbers, the 1/n! and the xn factors. This in turn means that f(x) is given by good approximation by just the first few terms of the series when x is small. If we know the limits of our measurement precision we can actually specify where to meaningfully cut off the series sum. 

Calculation: Let’s apply the series to something fairly simple. Consider a formula like 

	f(x) = (1 + x)1/2.

The first term in the series, f(0) means to replace x with 0 in the formula giving

	f(0) = (1 + 0)1/2 = 11/2  = 1.

From calculus f’(x) the first derivative of f(x) is given by

	f’(x) = d/dx(1 + x)1/2 = ½(1 + x)-1/2 and thus
	f’(0) = 1/2(1 + 0)-1/2 = ½(1)-1/2 = ½.

Going one more term

	f’’(x) = d/dx(1/2(1+x)-1/2) = (1/2)(-1/2)(1+x)-3/2 and thus
	f’’(0) = (1/2)(-1/2)(1) = -1/4.

Then the first three terms of the Taylor series for (1 + x)1/2 are

	f(x) ≈ 1 + ½ x – ¼ x2 .

For x = 0.1 according to Mr. Taylor,

	f(0.1) ≈  1 + ½ x 0.1 – ¼ x (0.1)2 = 1 + 0.05 - 0.0025 = 1.0475.

But plugging in the original formula, f(x) = (1 + x)1/2 and using a calculator good to several decimal places

f(0.1) =  (1 + 0.1)1/2 = √(1.1) = 1.0488.

The error between the approximation by three terms of the Taylor series and the calculator (“true”) value is

1.0488 – 1.0475 = 0.0013 

or about one part in a thousand and we only took the first three terms of the Taylor expansion. If we added more terms the error would rapidly get smaller. End calculation. 


What happens when we apply the Taylor expansion to 

EEinstein = m0c2/(1-(v/c)2)1/2 ? 

Calculation: Let’s rewrite this as

	EEinstein = m0c2γ(β) where γ(β) = 1/(1 – β2)1/2 and β= v/c 

and let’s expand γ(β) using Mr. Taylor’s expansion. If you know some calculus check the math, we will just give the result

	γ(β) = (1 – β2)-1/2 = 1 + 1/2β2 + 1/4β4 + …

Now let’s plug in 

β = 0.01, i.e., 
v = 0.01c = 3000km/sec = 1860mi/sec.

	γ(0.01) = 1 + 0.5x0.0001. + 0.25x0.00000001 + …
	γ(0.01) ≈ 1.0000500025. End of calculation.

This tells us that the first two terms (1 and 0.00005) dominate all the rest (actually, the first term dominates the second but we include the second term for a reason soon to be seen.) To good approximation for v a small fraction of c, we get

	γ(β) ≈ 1 + 1/2β2.

 Let’s put this back in EEinstein:

	EEinstein = m0c2γ ≈ m0c2 (1 + 1/2β2 ) =  m0c2 + 1/2 m0v2.

We can rewrite that as

	EEinstein ≈ m0c2 + ENewton ! 

This tells us when a body is standing still, i.e. when v = 0, i.e. when ENewton = 0 that EEinstein = m0c2. This is the best way to understand the idea that mass and energy are inter-convertible. Given that c2 is a very big number it tells us that a small amount of mass might be convertible into a large amount of energy and that is the basis of the nuclear reactions of fission (atomic bomb, nuclear reactors) and fusion ( hydrogen bomb and the energy released by a star’s “burning” of hydrogen and other elements). When a uranium atom fissions into parts the sum of the weights of the parts is less than the weight of the original atom and that tiny missing weight is converted to very rapid motion of the results of the break up (fission) of the uranium atom. 

For most processes we study, rocket ships, accelerated electrons, etc the first term, the rest energy term is unchanged in the process as we are not changing the particle composition of, say the electron, we are only accelerating it so that term is the same before and after acceleration and we are left with the difference is only in the terms that involve a power of the velocity so we can rewrite 

	EEinstein of motion = ENewton + 1/4 m0c2β4
			= 1/2 m0v2 + 1/4 m0v4/c2 + even smaller terms when v/c is small.

Since the second term (the v4/c2 term) is very small for ordinary velocities observable in, say, Newton’s time, all measurements would have agreed with Newton’s theory within the measurement precision of his time. Thus, his theory passed every test and was believed to be “true”. It was only with advances in technology in the 19th century that measurements begin to indicate something was not right but it took about half a century for Einstein to figure out what was wrong and come up with his theory of relativity which agreed with Newton at low velocities but differed at high velocities and explained the anomalies that had been noticed. 

Actually, Einstein’s theory was there for anyone to see as far back as the 1860s hidden in the new Maxwell’s unified theory of Electricity and Magnetism but to see it one had to throw off some very natural assumptions made by Newton and see the world in a way that disagrees with ordinary human experience. That was the genius of Einstein to make that leap. (Actually, at the time the anomaly was considered a flaw in Maxwell’s theory, not Newton’s. It was Einstein that turned the picture around and said Maxwell was right and Newton had it wrong.)

When some crazy people first claimed the earth actually rotated about its axis and if you were on the equator you were actually moving at a speed of about 1000 miles/hour this was obviously not true. We should be thrown violently around. They deduced the rotation of the earth from observing the motion of the sun and stars across the sky and said it was a lot simpler to conclude the earth rotated. But that didn’t agree with ordinary experience and to explain that discrepancy ultimately required Newton’s theories of motion and gravity. New and better theories often require rethinking ideas that seem unshakably true. 

We have developed some examples and described various ways of thinking about relativity in the context of accelerated electrons. Their behavior is very unintuitive for non-physicists. Through constant use a physicist begins to feel they have an intuitive grasp of what’s going on. That comes with training and experience over years of practice often doing calculations just like the examples here. To learn more, there have been many good expositions of relativity theory for the lay person. Einstein himself wrote a lucid layman’s guide that is still in print after nearly a century. 

Physicists commonly help their thinking by considering extreme cases. We did that when we looked at the mass formula for the extreme cases of v equal 0, c and 2c. George Gamow wrote a nice little book for lay people about a mythical Mr. Tompkins. Gamow’s approach was to wonder what ordinary daily experience would be like if the speed of light was slower, 10 miles per hour! Mr. Tompkins needs to go shopping and hops on his bike and starts to peddle. At first his speed picks up rapidly but as he gets to around 7 mph it begins to be a little harder to peddle faster. We noted at v = 0.87c the mass of an object doubles. If c is 10 mph then Mr. Tompkins is peddling a system (bike + himself) that weighs twice as much when he reaches 8.7 mph (87% of his c). And it quickly gets worse as he peddles harder and harder barely increasing his speed with more and more effort but he continues to feel heavier and heavier.

Relativity and plasma acceleration of electron bunches

Particle accelerators get particles very near the speed of light and behavior is very different there than at speeds we are used to in daily life. We showed above that even for speeds many miles per second the difference between the Newtonian and the relativistic behavior is almost indistinguishable. Now we want to have a look at near the speed of light where the particles in our accelerators operate. We have explained elsewhere that the plasma acceleration experiment involved bunch of electrons 12 µm long. The electrons at the front of the bunch gave up energy to create the ionized plasma and the plasma created the electric field which in turn accelerated electrons at the back of the bunch. 

If Newtonian physics described these electrons we would have the lead electrons slowing down because they lost energy and the trailing electrons speeding up because they are accelerated and the net result would be for the electrons to switch places and the newly accelerated leading electrons would now lose energy to accelerate the electrons that previously were decelerated. Sometimes a team of runners or bicyclists train in a single file column. The lead person breaks the wind for the rest and thus, they are expending more energy than the rest. When they tire, they drop back to the tail end of the column and the next person in line breaks the wind. So why doesn’t this happen for the relativistic case as well since it involves lead electrons losing energy to accelerate trailing electrons in the 12 µm long bunch? 

To give an idea of the difference between ordinary and relativistic experience we will make up some examples with numbers that are easy to work with just to get a feel for what is happening. Let’s compare a 1 GeV and a 100 GeV electron. According to Newton’s E = 1/2 m0v2 if we take the ratio of the two energies we get

	100 GeV/1 GeV = (v100/v1)2 and solving
	v100 = 10v1.

At ten times the velocity the 100 GeV electrons would cover any given distance 10 times as fast as the 1 GeV. So in the time it takes a 1 GeV electron to move the length of a bunch, the 100 GeV electron would have moved ten bunch lengths. Clearly, for a bunch to stay together the length of the plasma accelerator, 1 meter, they have to be pretty close in energy if Newton were correct. 

Calculation: Let’s now look at the situation from Mr. Einstein’s point of view.

EEinstein = m0c2/(1 – β2 )1/2, where β = v/c.

Let’s rewrite that as

	EEinstein/m0c2 = 1/(1 – β2 )1/2 .

If we plug in the mass of an electron and multiple it by c2 and convert units we find 

	mec2 ≈ 0.5 MeV, (where me = m0 of the electron).  

This is a number every particle physicist knows better than they know their own birthdate. Let’s consider a 7 GeV electron just to make the math simple later

	EEinstein/m0c2 = 7 x 109 eV/ 0.5 x 106 eV = 1.4 x104 = 1/(1 – β2)1/2 .

Square both sides and do a little arithmetic

	1 – β2 = 2 x 10-8,
	β2 = 1 - 2 x 10-8,
	β = (1 – 2 x10-8)1/2 = (1 - 0.00000002)1/2 = (0.99999998)1/2 = 0.99999999 = 1 – 10-8,
β = v/c = 1 – 10-8,
v = (1 – 10-8 ) c,
	v = c – 10-8c = 300,000,000 m/sec – 3 m/sec. End of calculation

The 7 GeV electron is only 3 m/sec slower than the speed of light! Even if the fastest electron were going at the speed of light (not possible) the “slow” 7 GeV electron would only be falling behind at the rate of 1 part in 108. Over the one meter length of the plasma accelerator it would fall behind any faster electron by, at most, about 10-8 meters ( 10-2 µm)  which is about one thousandth of a bunch length ( 12 µm). Therefore, all the electrons stay pretty much in their same location in the bunch, those at the head stay at the head and continue to give up energy and those at the tail stay there and keep gaining energy. Thus assuming the model of how plasma acceleration works is correct this experiment demonstrates convincingly that Einstein’s improvement of Newton’s idea is correct. 


The electron bunch stays together in the plasma accelerator. 

Before entering the plasma accelerator, all the electrons experienced the same accelerating force in the Linac to get them all to 42GeV. Once they enter the plasma accelerator thing change drastically. The electrons at the head of the bunch experience a force against their motion as they give up energy to create the ionized plasma surrounding the bunch and the electrons at the tail of the bunch are accelerated forward by the field of the ionized plasma cloud of electrons. Unlike in the Linac where all the electrons get the same push forward and thus have the same energy and same speed, in the plasma accelerator they start getting different pushes and we asked why the bunch stayed together?

We have seen that the Einstein theory of relativity reduces to the Newtonian theory at speeds low relative to the speed of light, speeds we are familiar with in our normal lives but at speeds nearing the speed of light the Newtonian theory is completely wrong. The Newtonian theory says a force applied over a distance does work on an object thus increasing the energy of the object. But as we approach the speed of light and relativity comes into play, more and more of that energy goes into increasing the inertial mass of the object and less and less goes into increasing its speed. 

This explains how the electron bunch stays together despite some electrons losing energy while others gain energy. We make an analogy with a pack of marathon runners nearing the finish line after all running at the same speed for most of the race (in the Linac). (After entering the plasma accelerator) Some start to run out of energy reserves and have less energy to put into running while others stage a finishing kick by drawing on remaining energy reserves. In our world where they are running about 12 miles an hour the pack spreads out. But in a Gamowian Mr. Tompkins world where the speed of light is just barely above the speed of the pack, let’s say, 12.01 miles per hour we would find that the tiring runners (at the front of the pack) having less ability to push themselves don’t actually slow down very much, instead they lose weight allowing them to maintain the speed of the pack with less effort!!! And the ones (at the back of the pack) with the finishing kick that push themselves harder don’t speed up much and thus don’t gain much on the runners at the front of the pack. Instead they just become heavier requiring more effort to maintain their pace!!! Such is the world of near light speed phenomena. And plasma acceleration would not work without this peculiar effect of nature keeping the electron bunch intact and in the same order! 

Expressed mathematically this is the difference between

	ENewton = ½ m0v2 and

	EEinstein = m0c2/( 1- (v/c)2)1/2.

If you have followed the math in the tutorial you should have a sense of how this strange formula creates this marvelous relativistic effect. 


To summarize:

We noted that the Linac produced bunches of 1.8 x 1010 electrons with 42GeV of energy per electron. This is the equivalent of the energy of a baseball thrown at 93 mph. Since the Linac was producing 60 bunches per second one might imagine what it would be like to have 60 major league baseball pitchers each one hitting us with a fastball every second.

According to Newtonian theory the energy of motion of an object is 

	ENewton = 1/2 m0v2.

Solving for velocity of a 42 GeV electron according to Newton we found that

	v = 400c, where c is the speed of light,

which violates what we have all heard that nothing can be pushed to travel faster than c. 

According to Einstein the energy of an object is 

	EEinstein = mc2.

Where

	m = m0γ and
	γ = 1/(1-β2)1/2 and 
	β = v/c. 

Writing it all out without the gamma and beta

	EEinstein = m0c2/(1-(v/c)2)1/2 and we solving for the inertial mass, m, 
	m = m0/(1 – (v/c)2)1/2.

When v = 0, when the particle is not moving, m = m0, the rest mass.

When v approaches c, m and hence E become infinitely large.

When v is greater than c the formula tells us the number for the energy and the mass become an imaginary number, a number with a √(-1) which is hard to understand what that might mean. And we can see that you can’t get a particle to v greater than c by starting with v less than c and pushing it because it has to pass through a stage of infinite mass which takes an infinite amount of energy.

Then we went on to look at what happens between v = 0 and v = c, the realm of objects we deal with in life and science. We found that for an object traveling at speeds in the range of a comet hitting the earth, v ~ 18.6 miles/sec that even at this very high speed m is little changed

	m ≈ 1.0000005m0, a one half millionth increase.

To make a noticeable difference in the mass, say to double the mas, we found we needed

	v ≈ 0.87c, the particle is moving at 87% of the speed of light.

For a tenfold increase of mass 

v = 99.5 % of the speed of light.

Since the rest mass of an electron is 0.5 MeV the velocity of a 7 GeV electron is

	 v ≈ (1 – 10-8)c, about one millionth percent shy of the speed of light.

Finally, we noted that according to Newton any time you double the energy of motion you increase speed by about 40%. In the energy doubling experiment the particle bunch is tiny and all the electrons are at essentially the same energy when they enter the plasma accelerator. After traveling one meter in the plasma accelerator the electrons’ energies ranged from around 84 GeV down to 5 GeV. Intuitively this should cause the bunch to spread out a great deal, yet we found that the velocity difference between the electrons was about one part in 108 and over the distance of one meter this hardly affects the particle’s location in the bunch. 

