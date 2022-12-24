# Bionic principles applied to MAV design





## Introduction

The micro air vehicle (MAV) business has boomed in recent years, making them available to a wide range of persons and purposes such as surveillance, delivery of goods, mapping, and many more. Our business realized the potential of MAVs and intends to provide a multirole surveillance drone capable of effortlessly transitioning between air and water by exploiting bionic principles. 

Over the last few years there has been a huge boom in the micro air vehicle (MAV) market, making them accessible for a wide range of people and purposes like surveillance, delivery of goods, photographing and many more. Our company has recognized the potential of MAVs and revolutionizes it by transforming a micro air vehicle to a micro autonomous amphibious air vehicle. Which means it has three times as many functions in a single system. //TODO: (Aufgabenstellung als Quellenangabe)

## Problem

## Scoping

For the Scoping of the project we referred to the biomimicry modeling wheel (Fig.1). It allowed us to structure our scoping into three distinctive categories:

- Context definition
- Function identification
- Life's principle integration

<img src="C:\Users\Loup\Desktop\MAV-Bionics\Picture1.png" alt="Picture1" style="zoom:50%;" />

### Context definition

We identified two main contextual areas for our project, and several sub-context, while also considering a transitional context.



The following table summarizes our work in this regard.



| **AIR**                                                      | **TRANSITION**      | **WATER**                                                    |
| ------------------------------------------------------------ | ------------------- | ------------------------------------------------------------ |
| **WEATHER**<br /> SUNLIGHT<br /> TEMPERATURE<br /> HUMIDITY <br />RAIN<br /> WIND<br /> ICE&SNOW | **DENSITY**         | **CONDITIONS**<br/>water<br/> current<br/> waves             |
| **HAZARDS**<br/> animals/insects<br/> moving objects<br/> abrasives<br/> people | **SURFACE TENSION** | **HAZARDS**<br/> animals<br/> moving objects                 |
| **TOPOLOGY**<br/> mountains<br/> forests<br/> glaciers<br/> buildings |                     | **TOPOLOGY**<br/> lake/river<br/> depth<br/> stones/rocks<br/> plants |
|                                                              |                     |                                                              |



### Function's identification

To have a better grasp on what the MAV will have to be able to perform, it's functions had to be placed within their contexts (Fig.2).



![Picture2](C:\Users\Loup\Desktop\MAV-Bionics\Picture2.png)



### Life's principle integration

When looking at how to integrate/use natural engineering solution, we identified the following Life's principle that we wanted to integrate into the project:

1. adapt to changing conditions
2. Change between air and water
3. Temperature change
4. Altitude change
5. be resource efficient
6. Navigation for over and underwater

## Discovering

The discovering phase is all about understanding the technical solutions that the natural world has to offer after millions of years of natural evolution.
The objective was to find applicable biological models or answers to the issues and functions that the MAV would have to overcome/perform. Therefore we took the terms of our scoping part and started searching for inspirations in nature. For some of the tasks found in scoping, we did a keyword search on asknature. Other parts we were able to take from experience. In the following section only the few choosen mechanisms which made it to the final prototype are listed.

### Function Lense
In this approach we were searching different sources for functionallities our problem has to fullfill. Therefore the questions/functions had to be **Biologized**.
https://moodle.zhaw.ch/pluginfile.php/477890/mod_resource/content/2/04%20Biomimicry%20-%20Discovering_11102022.pdf


https://asknature.org/strategy/body-protected-from-diving-impact/
#### How would nature transition from air to water?
One of the most important and critical functionalities that the MAV must master to perfection is the transition between air/flight and water/diving. 
The difficulty here is surface tension, which increases at higher speeds, causing the water to feel like concrete. This has already been evolved over many years by various bird species. One of them are the **Peruvian boobies**. They fly ~30 meters above the water and dive into the water at a speed of about 97km/h. Not only can they go up to depths of 25 meters with diving, they are also able to pursue fish as deep as 90 meters. In order to break the water tension optimally, they fold their wings just before the impact and the structure of the beak helps them to do so(Figure 1).
https://www.pnas.org/doi/10.1073/pnas.1608628113
https://www.10000birds.com/well-adapted-for-a-plunge-diving-lifestyle.htm
https://eartheclipse.com/animals/birds/water-diving-birds.html


#### How would nature navigate under water? (sonar)
//TODO: eine zweite navigation "Discovern"
https://asknature.org/strategy/spiders-surf-on-electric-fields/


Without navigation, the MAV would be useless. the difficulty is to find a navigation underwater and have a fallback scenario.
A well-known variation of this is the echosounder, which is used by various animals such as tenrec, bats or wales. This works by emitting very high-pitched sounds that bounce off objects and return to the animal. From the time of bounce and the incoming waves, you can tell the distance, direction, speed, density and even the size of an object.
https://www.zmescience.com/mrf4u/statics/i/ps/cdn.zmescience.com/wp-content/uploads/2013/09/echolocation-sonar-.jpg?width=1200&enable=upscale
https://www.discoverwildlife.com/animal-facts/what-is-echolocation/
#### How would nature communicate under water and in the air?
Fortunately, or thanks to clever evolution, the echosounder is also used by animals to communicate. This works with the same principle as described above.
https://blog.scienceandmediamuseum.org.uk/the-sophisticated-use-of-sound-in-the-animal-kingdom/


#### How does nature move underwater and in the air?
MAV's have long mastered the concept of flying. That's why we asked how nature **moves** in the air to find more efficient or suitable approaches.

Spiders can be found multiple kilometers in the air and over a thousand kilometers out to sea. Spiders can detect electronically charged atmospheres. Taking their senses and environment for advantage they crawl on a negatively charged edge from where they shoot out a couple strands of silk. The strands pick up the negative charges of the edge surface and repel from the like charged surface, which let's them travel through air.
https://asknature.org/strategy/spiders-surf-on-electric-fields/

Because our mav is breaking into the water at speed, the focus on moving underwater was to change directions and move short distances.

//TODO flagella


### Operating Conditions
Operating Conditions are very important for the MAV to consider. Lots of different areas of applications have to be considered, especially with the diverse topology of switzerland in mind.
#### Resistance to high temperature changes
A good insulator is very important so that the MAV can be used at all temperatures. Many animals but also plants have tricks that we can analyze to protect themselves from the temperature.


A role model are animals with fur like the beaver. Fur always consists of two different types of hair. The longer ones are called guard hairs and form a protective cover for the underhairs, which are denser (1 guard hair protects on average 3 underhairs). The beaver and other aquatic mammals have scales on the outer layer of their underhair. This makes the hairs interlock with each other and prevents the penetration of cold water and traps air bubbles. Air bubbles form a good insulating layer.
https://asknature.org/strategy/fur-keeps-heat-in-and-cold-water-out/


Multicellular organisms such as the Pompeii worm (Alvinella pompejana) are also specialized in adapting to extreme temperature fluctuations. Measurements showed that they can survive despite a difference of 60°C in two parts of the body. It achieves this by building protective tubes that create a mosaic of microenvironments with which he can determine the thermal and chemical gradients.
https://www.cambridge.org/core/journals/international-journal-of-astrobiology/article/adaptations-to-environmental-extremes-by-multicellular-organisms/788142428590F0D32F24F139CA20B9B4
https://asknature.org/strategy/worm-tolerates-temperature-gradient-of-140-deg-f/

#### Structural integrity
Good structural integrity has always been proven to bring with it a certain degree of isolation. Nevertheless, it is important that durability is considered as a specific criterion, as the MAV should be able to withstand water pressure, water impact and possible collision. Nature is once again a wonderful source of inspiration for structural integrity with many completely different techniques to meet the criteria.

By hammering the tree, the woodpecker must stop forces to prevent brain injury. This is achieved by the unique structure of its skull. The skull bone has a layered, plate-like structure that resembles a sponge. They function as shock absorbers, deflecting the forces of impact in different directions. 
https://asknature.org/strategy/spongey-cranium-absorbs-impact/


Diatoms have another unique strategy to ensure stability. They create a shell of silicona. Through a characteristic structure such as circular or star-shaped and a pore pattern, they manage to create a particularly good structural integrity. Not only diatoms. Not only diatoms but also the Venus' flower basket sea sponge uses a unique structure for itself. Like the diatoms, the sea sponge is also made of silica ( in fact, glass). 
A layering of 50 to 200nm small silica spheres and organic compounds can prevent the propagation of cracks. The relatively stiff inorganic spheres and the energy-absorbing organic compounds are arranged in a square lattice that is rolled up into a tube. This is the main form of the glass sponge and is so tough that even the shrimp living in its woven glass basket cannot break out.
https://asknature.org/strategy/diatoms-build-glass-houses-that-are-stable-and-strong/
https://asknature.org/strategy/diatoms-build-glass-houses-that-are-stable-and-strong/

### Naturalist Lens
After a functional analysis and the elaboration of operating conditions, the tables should be turned and nature should be used as an inspiration. For this purpose, sites such as asknature can be used to look for exciting ideas.
https://moodle.zhaw.ch/pluginfile.php/477890/mod_resource/content/2/04%20Biomimicry%20-%20Discovering_11102022.pdf
#### Buoyancy
To create neutral or positive buoyancy, fish use a simple but very solid strategy. They have a swim bladder, which is located in the body cavity. This bubble is filled with gas, which can give good buoyancy due to its low density.
https://asknature.org/strategy/swim-bladder-helps-maintain-buoyancy/
https://www.scientificamerican.com/article/floating-with-a-swim-bladder/
https://www.britannica.com/science/swim-bladder
#### Swarm behaviour
In order for several MA[^3]V to work together on a mission, they must be able to act in a "swarm".


One feature that would be beneficial in a swarm is collision detection. Locusts migrate in a huge swarm without colliding. Like humans, their movements are converted into electrical signals by the eye and finally read by the brain. the exciting thing is that locusts only detect those movements that interfere with their flight path. this happens because the electrical signal increases when an object moves directly towards them. this signal is then filtered according to strength so that only those objects which are on a direct flight path are detected.


Another useful feature would be the collaboration between the different individuals of the swarm. Honey bees can share their knowledge through two different channels. On the one hand, they communicate through movement by performing a so-called "waggle dance", which indicates to other bees where, for example, the food source is. On the other hand, they can communicate through pheromones. When a worker bee stings, it produces pheromones that alerts the other bees of danger.
https://www.thoughtco.com/how-honey-bees-communicate-1968098
https://asknature.org/strategy/collaborating-for-group-decisions/
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
3. As a denfense mechanism, the prototype is to be coated with a non-lethal toxin so that enemies in the environment as well as human opponents can be kept at a distance.
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

## Prototype
### Concept
## Extension Possibilities
## Cradle to Cradle
Innovation through biomimicry, applied lifes principles, and all other techniques are incomplete without attempting zero waste production and developing a cradle-to-cradle product.
- The hull, propeller, and topologically optimized structure will be made from a 3D-printable biodegradable material, BiomeHTX.
- The components will be modular so that they can be replaced in the event of problems and fed into a new lifecycle.
- The electronics will be supplied protected so that they can be recycled back into the technical cycle.
## Discussion
## Conclusion
## References




















### Abstracted Biological Strategies

Looking for interesting biological solutions to our problems, we identified the following:

- *Water Strides* – Communication by vibration
- *Brown Pelican* – Beak slices into surface at high speed
- *Big Brown Bats* – Navigating via sonar
- *Garden warbler* – Navigation via magnetic fields
- *Spiders* – Flying with silk in negativly charged surface
- *Goldenrod Gall Fly* – Internal antifreeze protein

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
