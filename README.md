# High-Energy-Physics
One of the ways to develop theories nowadays is to develop an experimental device that probes the universe. The collected information might give hints to theoreticians about the better version of a current model. For example, how to include newly absorbed phenomena into it and improve the accuracy of model predictions for further experiments. CERN is a French abbreviation for Center of European Nuclear Research. Essentially, it is a vast laboratory. There are several distinct experiments that take place. And everyone is operated by an international collaboration that unites physicists or scientists from different countries. People from 100 different countries work together despite political difficulties and misunderstanding on governmental levels.
They focused their intellectual efforts on the development of better understanding of our universe on the development of new technologies. So it is a fascinating place. And there are, of course, some by-products that you're most likely aware of. For example, CERN is the birth place of the World Wide Web. So you are using this to watch this lecture. Also, one of the great things built there is called Large Hadron Collider. It has been used for discovery of Higgs boson, and it is one of the finest and the biggest data generation machine ever created.
By design, it is a machine for smashing protons and examining outcomes. By effect, it is a massive arena for examining different models striving for better explanation of the universe. Let us take a closer look at LHC. It is a 27 km-long tunnel, 50 to 175 meters deep, and the protons are accelerated to the speed almost comparable to the speed of light. And the energy collision on those protons is up to 14 teraelectronvolts. There are four big detectors located around the ring. Those are called ALICE, ATLAS, CMS and LHCb. So there are 40 million bunches of proton that collide every second. Every detector generates enormous amounts of data, for example, since the beginning, hundred of petabytes has been stored for later data analysis. Let's take a look at the cycle that starts from the very beginning till the discovery or publication has been created. So we start with creation of protons out of hydrogen atoms, and then we accelerate those to the speed almost equal to the speed of light. Then those protons are grouped into bunches. And those bunches are smashed into each other. And during this collision, set of particles appear out of the energy of this collision, and those are called events.
Then the detector that sits around place of this collision records information of the energy that is deposited by every particle flying out of the event. And can convert this information of the energy into the hits that you can record and store.
Left after after this, the algorithm that tries to reconstruct trajectories of different particles, and identify types of those particles comes to action.
After we get the picture of individual trajectories, we combine them into vertices and form a structural of the whole event. Then we build the map of the event and filter for the further analysis only those that have some meaning from the physical point of view.
And only after this, we analyze statistical properties of those events that has been stored and make conclusion about validity of models that predict existence of certain events of certain part of the events.
So at the place of collision there is a detector which is essentially a sub-atomic digital camera. Sits and in records outcome of the collision that happens during the data taking. On the upper part of this image, you see the mechanical design of LHCb detector. And at the bottom part of this image, you will see reconstructed trajectories of elementary particles that have been detected by this detector.
Their collection of lines that has been reconstructed for the whole event. And the data is used for this analysis, for this reconstruction, come from various parts of the directories, not only the backside or downstream side. It also comes from, there is a middle part that is called tracker. And there is a very precise part of the detector that sits around the place of the collision. It is called vertex locator. That gives most of the information about the particle trajectory. And then we have to identify what kind of particle every track represents.
We can use various sources of information. The first one is that every particle leaves different traces in different subdetectors of the experiment. For example, Electrons leave tracks at tracking system and electromagnetic calorimeter. Photons leave no traces in tracking system but leave traces electromagnetic calorimeter. Hard ones such as protons, Kaons, and pions, leave tracks in inner most tracking system and electromagnetic calorimeter and hadronic calorimeter. And there is a special kind of particles that are called muons, they're heavier brothers of electrons that fly through the whole detector and leave traces everywhere.
So collection of the information that those sub-detectors provide allows us to deduce the type of the particle. And this actually is one of the machine learning problems that is being solved at every experiment. After you got the picture of individual tracks, it is important to reconstruct the whole image, the whole event that consists of tracks and vertices that happen during the particle decays. There are so-called secondary vertices that correspond to a very short flight of a particle that is then decayed into something else. After this trajectory's particle identification and vertex identification has been happened, we still have to understand whether or not inside this event, something interesting has actually happened. And for this purpose, we have special selection procedures that are called triggers. There are two stages of triggers. The first one is hardware trigger that reduces the rate of the event from 40 MHz to 1 MHz. And there is a software trigger that reduces this rate even further, and output of this trigger is being use for offline analysis and eventually for discovery.
Design of the triggers is actually a quite interesting problem from machine learning perspective. My group has been taking part and design of the triggers for LHCb experiment, and it works in data taking since 2015. 
So precise and fast particle tracking, single tracks, showers and jets kind of objects that detector operate with. Particle identification, how can you discriminate between different kinds of particles? Fast and accurate online data processing and filtering. How you make sure that data collected can be trusted. If there is anomaly happening during the data taking, you should disregard the model data taken during the period.
You should take certain measures to fix the infrastructure to improve quality of the data. And, of course, there are very interesting topic of design optimization of the detector, where various techniques like Bayesian optimization and surrogate modelling can be used. And here's example of a tracking problem that we'll cover during the next lecture. Given the set of hits represented by points here, you should be able to reconstruct the tracks and estimate parameters of those tracks as precisely as possible.
