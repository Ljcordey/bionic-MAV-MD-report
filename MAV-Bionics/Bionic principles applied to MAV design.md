# Bionic principles applied to MAV design





## Introduction

//TODO: entscheiden zwischen den zwei texten

In recent years, the micro air vehicle (MAV) industry has flourished, making them accessible to a wide range of individuals and purposes, including surveillance, delivery of commodities, and mapping, among others.
Utilizing bionic principles, our company intends to develop a multirole surveillance drone that can shift seamlessly between air and water.

In recent years, the market for micro air vehicles (MAVs) has exploded, making them available for a variety of persons and purposes, including surveillance, delivery of goods, photography, and many more.
Our organization has identified the potential of MAVs and is revolutionizing them by converting a micro air vehicle into a mini autonomous amphibious air vehicle.
Therefore, it has three times as many functions as the previous system.  //TODO: (Aufgabenstellung als Quellenangabe)

## Problem

Bionic engineering principles are difficult to integrate in the construction of a MAV. In order to enhance the performance of technological systems, bionic engineering incorporates biological principles and materials. This can be a complex and subtle procedure, requiring an in-depth knowledge of both the biological systems being replicated and the technological requirements of the MAV.

Multiple variables contribute to the difficulties of incorporating bionic engineering principles into the design of an MAV. The necessity to balance the opposing demands of performance, functionality, and durability is one of the key obstacles. Due of the fragility and environmental sensitivity of bionic materials and systems, it might be challenging to fit them into an MAV's tough and high-performance design. In addition, the integration of bionic systems into an MAV necessitates a high level of technical skill and complex production procedures, which can be time-consuming and costly.

Implementing bionic engineering principles in the design of an MAV necessitates a cautious and nuanced approach, and it is a substantial task that calls for a combination of technical expertise, ingenuity, and resourcefulness.

## Scoping

For the project's Scope Definition, we referred to the biomimicry modeling wheel (Fig.1). It enabled us to divide our scoping efforts into three main categories:

- Context definition
- Function identification
- Life's principle integration

<img src="C:\Users\Loup\Desktop\MAV-Bionics\Picture1.png" alt="Picture1" style="zoom:50%;" />


### Context definition

For the sake of our study, we determined two primary contextual domains, as well as various sub-contexts, and we also took into consideration a transitional context. 

The table below highlights our efforts in this area. 



| **AIR**                                                      | **TRANSITION**      | **WATER**                                                    |
| ------------------------------------------------------------ | ------------------- | ------------------------------------------------------------ |
| **WEATHER**<br /> SUNLIGHT<br /> TEMPERATURE<br /> HUMIDITY <br />RAIN<br /> WIND<br /> ICE&SNOW | **DENSITY**         | **CONDITIONS**<br/>water<br/> current<br/> waves             |
| **HAZARDS**<br/> animals/insects<br/> moving objects<br/> abrasives<br/> people | **SURFACE TENSION** | **HAZARDS**<br/> animals<br/> moving objects                 |
| **TOPOLOGY**<br/> mountains<br/> forests<br/> glaciers<br/> buildings |                     | **TOPOLOGY**<br/> lake/river<br/> depth<br/> stones/rocks<br/> plants |
|                                                              |                     |                                                              |



### Function's identification

To have a better understanding of what the MAV will need to be able to do, its functions required to be contextualized (Fig.2). 



![Picture2](C:\Users\Loup\Desktop\MAV-Bionics\Picture2.png)



### Life's principle integration

When looking at how to integrate/use natural engineering solution, we identified the following Life's principle that we wanted to integrate into the project:

1. adapt to changing conditions

2. Change between air and water

3. Temperature change

4. Altitude change

5. be resource efficient

6. Navigation for over and underwater

<img src="C:\Users\Loup\Documents\GitHub\bionic-MAV-MD-report\MAV-Bionics\env-factors.png" alt="env-factors" style="zoom:33%;" />

## Discovering

Understanding the technical answers that the natural world has to give after millions of years of natural evolution is the focus of the discovering phase.

The goal was to identify relevant biological models or solutions for the challenges and functions that the MAV would have to overcome/perform. Therefore, using the terms of our scoping section, we began to seek inspiration in nature. We conducted a keyword search on [Asknature.org](https://asknature.org/) for some of the tasks identified during scoping. Other elements were derived from experience. In the section that follows, only the few mechanisms that made it into the final prototype are listed.

### Function Lense
In this method, we searched multiple sources for the functionalities our challenge must satisfy.
Consequently, the questions/functions were required to be **Biologized**. [^1]

[^1]: https://moodle.zhaw.ch/pluginfile.php/477890/mod_resource/content/2/04%20Biomimicry%20-%20Discovering_11102022.pdf


https://asknature.org/strategy/body-protected-from-diving-impact/
#### How would nature transition from air to water?
The transition between air/flight and water/diving is one of the most vital and crucial capabilities that the MAV must master to perfection.

The issue is surface tension, which increases with speed and causes the water to become solid like concrete. Various bird species have already developed this trait over many years. One of these species is the Kingfisher. They fly approximately 30 meters above the ocean and dive into it at a speed of 97 kilometers per hour. Not only can they dive to depths of up to 25 meters, but they can also hunt fish as deep as 90 meters. To break the water tension optimally, they fold their wings right before impact, and the anatomy of their beaks aids in this process. (Figure 1).

![Kingfisher](https://www.earthtouchnews.com/media/1515869/kingfisher1_2015_10_23.jpg)

https://www.pnas.org/doi/10.1073/pnas.1608628113
https://www.10000birds.com/well-adapted-for-a-plunge-diving-lifestyle.htm
https://eartheclipse.com/animals/birds/water-diving-birds.html


#### How would nature navigate under water? (sonar)
//TODO: eine zweite navigation "Discovern"
https://asknature.org/strategy/spiders-surf-on-electric-fields/

Without navigation, the MAV is ineffective. The issue lies in finding an underwater navigation system and having a backup plan.

Various creatures, such as the tenrec, bats, and whales, utilize a well-known variant of this called the echosounder. This method involves releasing extremely high-pitched noises that reflect off of things and return to the animal. You may determine the distance, direction, speed, density, and size of an object based on the duration of bounce and the incoming waves. [^4]

[^4]: https://www.discoverwildlife.com/animal-facts/what-is-echolocation/

![Bat Echolocation](https://www.peec.org/PEEC_Bats/Start_files/droppedImage.png)![img](https://www.nwtexhibits.ca/beluga/images/sketch-echolocation.jpg)
https://www.zmescience.com/mrf4u/statics/i/ps/cdn.zmescience.com/wp-content/uploads/2013/09/echolocation-sonar-.jpg?width=1200&enable=upscale

#### How would nature tackle underwater and airborn communication ?
Fortunately, or thanks to intelligent evolution, animals also use ultrasound to communicate. The same approach applies here as mentioned previously.
https://blog.scienceandmediamuseum.org.uk/the-sophisticated-use-of-sound-in-the-animal-kingdom/


#### How does nature solve airborn and underwater motility?
MAVs have long been experts at flying, which is why we looked to nature  and how it moves through the air to find more efficient and suitable  approaches.

 For example, certain spider species can be found flying several kilometers  in the air and traveling over a thousand kilometers out to sea.

 They can even detect electrically charged atmospheres and use their senses and  environment to their advantage. 

To accomplish these feats, they crawl along a negatively charged edge and then shoot out strands of silk, which pick up the negative  charges of the surface and repel away from it, allowing them to fly  through the air. [^6]

[^6]: https://asknature.org/strategy/spiders-surf-on-electric-fields/

Due to the rapid entry of our UAV into the water, the underwater movement strategy emphasized direction changes and short distances. As such, we looked for underwater motility strategies in nature, and Flagella from certain bacteria and microorganisms came to our mind.

##### Flagella 

Numerous microorganisms utilize flagella, which are long, whip-like appendages, to travel through water. They are made of proteins known as flagellins, which are spirally organized around a central core. At the base of the flagellum lies a molecular motor called the basal body that powers the flagellum. The rotation of the basal body causes the flagellum to oscillate, propelling the bacterium through the water. The microbe can control the movement's direction and velocity by regulating the rotation of its basal body. Flagella are an integral aspect of the biology and behavior of numerous aquatic bacteria, as they are particularly effective at propelling microbes through water. [^7]

[^7]:https://en.wikipedia.org/wiki/Flagellum


### Operating Conditions
The MAV must give careful consideration to the operating conditions at all times.
It is necessary to take into account a wide variety of application domains, which is especially important when thinking about the varied topography of Switzerland. 

#### Resilience to big temperature variation 
Variations in temperature can pose a serious threat to electronics. Large temperature swings can pose a number of issues for electronic components, including thermal expansion, which can put physical stress on the components, and changes in the electrical properties of materials, which can compromise the performance and dependability of the electronics. In addition, elevated temperatures can hasten the deterioration of materials and the aging of components, leading to their early failure. Extremely low temperatures, on the other hand, can lead to issues such as brittle failure, higher resistance, and decreased performance. In order to maintain the dependability and performance of electronic devices, it is necessary to safeguard them against significant temperature fluctuations.

Therefore, proper thermal insulation is necessary for the normal operation of the MAV.  To address this issue, we can assess the tactics utilized by various animals and plants to withstand extreme temperatures. 

A nice model is a furry animal, such as a beaver.

 Animal fur always consists of two unique types of hair strand.
The longer ones are called **guard hairs** and act as a protective covering for the **underhairs**, which are denser (one guard hair protects on average 3 underhairs).

Beavers and other aquatic mammals have scales on the outermost layer of their underhair. This causes the hairs to intertwine, preventing cold water from penetrating and trapping air bubbles.
Air bubbles effectively insulate a surface.  [^8]

[^8]: https://asknature.org/strategy/fur-keeps-heat-in-and-cold-water-out/

Extremophile multicellular creatures, such as the Pompeii worm (Alvinella pompejana), are similarly well adapted to great temperature changes.
The measurements revealed that they can survive despite a 60°C differential between two bodily sections.
It accomplishes this by constructing protective tubes that generate a mosaic of microenvironments from which the researcher may determine the thermal and chemical gradients.  [^9][^10]

[^9]: https://www.cambridge.org/core/journals/international-journal-of-astrobiology/article/adaptations-to-environmental-extremes-by-multicellular-organisms/788142428590F0D32F24F139CA20B9B4
[^10]: https://asknature.org/strategy/worm-tolerates-temperature-gradient-of-140-deg-f/

#### Structural integrity
Good structural integrity has always been proven to bring with it a certain degree of isolation. Nevertheless, it is important that durability is considered as a specific criterion, as the MAV should be able to withstand water pressure, water impact and possible collision. Nature is once again a wonderful source of inspiration for structural integrity with many completely different techniques to meet the criteria.

By hammering the tree, the woodpecker must stop forces to prevent brain injury. This is achieved by the unique structure of its skull. The skull bone has a layered, plate-like structure that resembles a sponge. They function as shock absorbers, deflecting the forces of impact in different directions.  [^11]
[^11]: https://asknature.org/strategy/spongey-cranium-absorbs-impact/

Diatoms have another unique strategy to ensure stability. They create a shell of silicona. Through a characteristic structure such as circular or star-shaped and a pore pattern, they manage to create a particularly good structural integrity. Not only diatoms. Not only diatoms but also the Venus' flower basket sea sponge uses a unique structure for itself. Like the diatoms, the sea sponge is also made of silica ( in fact, glass). 
A layering of 50 to 200nm small silica spheres and organic compounds can prevent the propagation of cracks. The relatively stiff inorganic spheres and the energy-absorbing organic compounds are arranged in a square lattice that is rolled up into a tube. This is the main form of the glass sponge and is so tough that even the shrimp living in its woven glass basket cannot break out. [^12][^13]

[^12]: https://asknature.org/strategy/diatoms-build-glass-houses-that-are-stable-and-strong/
[^13]: https://asknature.org/strategy/glass-skeleton-is-tough-yet-flexible/

![img](https://asknature.wpenginepowered.com/wp-content/uploads/2016/04/Euplectella_aspergillum_Okeanos-720x405.jpg)

### Naturalist Lens
After a functional analysis and the elaboration of operating conditions, the tables should be turned and nature should be used as an inspiration. For this purpose, sites such as asknature can be used to look for exciting ideas.[^14]
[^14]: https://moodle.zhaw.ch/pluginfile.php/477890/mod_resource/content/2/04%20Biomimicry%20-%20Discovering_11102022.pdf

#### Buoyancy
To create neutral or positive buoyancy, fish use a simple but very solid strategy. They have a swim bladder, which is located in the body cavity. This bubble is filled with gas, which can give good buoyancy due to its low density. [^15][^16][^17]
[^15]: https://asknature.org/strategy/swim-bladder-helps-maintain-buoyancy/
[^16]: https://www.scientificamerican.com/article/floating-with-a-swim-bladder/
[^17]: https://www.britannica.com/science/swim-bladder

#### Swarm behaviour
In order for several MA[^3]V to work together on a mission, they must be able to act in a "swarm".

One feature that would be beneficial in a swarm is collision detection. Locusts migrate in a huge swarm without colliding. Like humans, their movements are converted into electrical signals by the eye and finally read by the brain. the exciting thing is that locusts only detect those movements that interfere with their flight path. this happens because the electrical signal increases when an object moves directly towards them. this signal is then filtered according to strength so that only those objects which are on a direct flight path are detected. [^18]<img src="https://media.nature.com/lw767/magazine-assets/nindia.2020.129/nindia.2020.129_19310606.jpg" alt="Locust vision could help self-driving cars, drones avoid collisions" style="zoom:33%;" />

[^18]: https://asknature.org/strategy/collision-detection-in-a-swarm/

Another useful feature would be the collaboration between the different individuals of the swarm. Honey bees can share their knowledge through two different channels. On the one hand, they communicate through movement by performing a so-called "waggle dance", which indicates to other bees where, for example, the food source is. On the other hand, they can communicate through pheromones. When a worker bee stings, it produces pheromones that alerts the other bees of danger. [^19][^20]![Swarming (honey bee) - Wikipedia](https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Bee_Swarm.JPG/220px-Bee_Swarm.JPG)]
[^19]: https://www.thoughtco.com/how-honey-bees-communicate-1968098
[^20]: https://asknature.org/strategy/collaborating-for-group-decisions/

#### Defense
//TODO: defense schreiben
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6646469/#:~:text=For%20self%2Ddefense%2C%20electric%20eels,nociceptors%20to%20deter%20their%20target.
https://asknature.org/strategy/deployable-web-distracts-predators/
https://www.birdwatchingdaily.com/news/science/secrets-of-the-worlds-poisonous-birds/

#### Hydrophobicity
//TODO fertig stellen
https://asknature.org/strategy/surface-allows-self-cleaning/

## Idea Creation
After the discovering phase, we were able to move on to the next phase with a lot of interesting strategies of nature. This chapter explains which ideas are combined into a prototype, how they interact and which biomimicry approaches could not be used.

//TODO: Image of Prototype handdrawn


1. To make transitoining from air to water as easy as possible, two different traits inspired by kingfisher will be adopted. On the one hand, attention will be paid to a slender hydrodinamic design, which helps to break into the water at high speed, and on the other hand, the wings and propellers will be collapsible to further optimise the hydrodynamics.
2. For vision, we are integrating the bee's functions by incorporating compound vision cameras that can perceive as many aspects of the environment as possible. Not only the vision but also the swarm behaviour should work as well as the bees. This will be made possible with emergent behaviour AI, which mimics the behaviour of bees so that several MAVs can collaborate with each other.
3. As a defense mechanism, the prototype is to be coated with a non-lethal toxin so that enemies in the environment as well as human opponents can be kept at a distance.
4. To navigate underwater and in poor conditions, echolocation technology is used for maximum performance in all conditions.
Inspired by whales and bats, ultrasound is also used to communicate and transfer research data underwater.
5. To create a hydrophobic effect, the surface of the fabric is coated with a water-repellent coating, which also increases bacterial resistance.
6. The drone's frame is modeled like marine organisms like Sponges and Diatomea. Topological optimization, a novel technique, guarantees a lightweight but sturdy construction with insulation capabilities that shield delicate gear from impacts.
7. Similar to the Anacondas in the Amazonian Basin or certain microorganisms with their flagellum, while underwater the drone should be propelled by its tail.
Thus it can push itself and travel in 3D underwater space when agitated.
8. To control the buoyancy, a bladder similar to the fish should be used. This bladder should be filled with gas and be controllable to stabilize the drone in the water.

Of course, many exciting technologies did not qualify for the final prototype. 
* Surfing on electric fields" was not feasible as a means of transport because the weight of the MAV is too great.
* Although the Pompeii worm is insanely resistant to temperature differences, its protective tube building strategy did not translate well into a micro air vehicle.
* Fur as insulation has long been discussed as it can also be water repellent and hydrophobic. However, it was decided against, as a coating and a smooth surface is more practical and easier to produce.

In the discussion, the possibility of moving forward under water for short distances was also often discussed, as the anwnendugsfall was only intended for a fast, deep dive. It was decided to incorporate a biomimic aspect for a controlled forward movement under water. Therefore, the discovery process had to be gone through again and the flagella was found.


## Evaluation
//TODO: Kapitel beschreibung fertig machen
//TODO: insert image icons per life principle



In this chapter, the selected functions are evaluated on the basis of the life's principle, which we set out to achieve in chapter XY. 

### Evolve to Survive
**Continually incorporate and embody information to ensure enduring performance.** //TODO: quoting style

#### Replicate Strategies that work
functioning micro air vehicles have already implemented many strategies. therefore, some components such as the propeller structure and RF communication will be adopted in the new design. In addition, various strategies from nature mentioned in the Idea Creation chapter are reused and adapted to the MAV context.

### Be Resource (Material and Engergy) Efficient
**Skillfully and conservatively take advantage of resources and opportunities** //TODO: quoting style

#### Use Multi-functional Design
Some multifunctional designs have been integrated. One of these is the flagella, which serves as a means of transport in water and as an antenna for RF signals in the air. Another such design is the echo sounder, which can be used not only for navigation but also for communication. A final and most exciting multifunctional design is the topologically optimized surface that combines maximum lightness, insulation and resistance.

#### Recycle all Materials
This topic is discussed in more detail in the chapter on Cradle to Cradle. From the beginning, however, care was taken to make all materials as recyclable as possible. As an example, a biodegradable plastic called BiomeHTX is used. To give the non-recyclable components a new life in other applications was another very important aim.

#### Fit form to function
The shape of the prototype was worked out as minimalistic as possible and as efficient as possible, so that the MAV can fulfill all functional criteria as lean as possible.

### Adapt to changing conditions
**Appropriately respond to dynamic contexts.** //TODO: quoting style

#### Incorporate Diversity
For some key components, such as navigation and communication, a strong focus was placed on diversification. For navigation, cameras and echolot were used to take into account failures, changing visibility qualities and partly unpredictable environments. Communication does not work in the same way in the water as it does on the surface, so two different technologies (RF and echolot) are used.

### Use Life-friendly Chemistry
**Use chemistry that supports life processes.** //TODO: quoting style

> use an ">" before a phrase you want to quote, to make it work like a quotation.

This life principle was the most difficult to fulfill, as the hydrophobic and non lethal toxic coating is a chemical product that needs to be inspected more closely. There are already several solutions, but whether they are safe in all the designated areas of application must be tested in more detail in a study to be absolutely sure.


## Prototype
### Concept
### Extension Possibilities
## Cradle to Cradle
Innovation through biomimicry, applied lifes principles, and all other techniques are incomplete without attempting zero waste production and developing a cradle-to-cradle product.
- The hull, propeller, and topologically optimized structure will be made from a 3D-printable biodegradable material, BiomeHTX.
- The components will be modular so that they can be replaced in the event of problems and fed into a new lifecycle.
- The electronics will be supplied protected so that they can be recycled back into the technical cycle.
## Discussion
Thanks to a cradle to cradle and biomimicry approach, the problem was approached in a completely different way and viewed from a completely new angle. this led to the functionalities being rethought from scratch and not only the question of what? but repeatedly also the question of why? was in focus.
Starting with scoping, it was not yet clear how exactly the end product could look, and everything that could be relevant was simply questioned and described. In the process, for example, it emerged that the transition from the surface into the water plays a central role. In the discovering part, many exciting and new techniques appeared, which could (not always) be used, but even if they were not used, they have remained in the back of the mind for the next project (e.g. sending data like water strides).
When it finally came to the prototype, a lot of preliminary work had been done and only the compatibility and technological requirements had to be checked. This was not always easy, but thanks to the good groundwork, a lot of time could be saved.
## Conclusion

## References



















The following links are relevant:

| https://asknature.org/strategy/beak-protects-during-dives/   |
| ------------------------------------------------------------ |
| https://asknature.org/strategy/deep-divers-manage-temperature/ |
| https://asknature.org/strategy/leg-position-initiates-dive/  |
| https://asknature.org/strategy/spinning-makes-safe-dive/     |
| https://asknature.org/strategy/beak-provides-streamlining/   |
| https://asknature.org/strategy/body-protected-from-diving-impact/ |
| https://asknature.org/strategy/legs-reversibly-stick-to-surfaces-underwater/ |
| https://asknature.org/strategy/olfactory-cues-aid-in-prey-detection/ |
| https://asknature.org/strategy/moths-alter-flight-to-deal-with-winds/ |
| https://asknature.org/strategy/sonar-adjusts-to-surroundings/ |
| https://asknature.org/strategy/navigation-underwater/        |
| https://asknature.org/strategy/eyes-see-magnetic-fields/     |
| https://asknature.org/strategy/spiders-surf-on-electric-fields/ |
| https://asknature.org/strategy/how-flies-survive-freezing/   |
| https://asknature.org/strategy/legs-detect-small-vibrations-for-communication/ |
| https://asknature.org/strategy/body-designed-for-fast-efficient-swimming/ |
