# D.A.R.X.A | Track.Locate.Secure
<b>D</b>eep <b>A</b>utonomous <b>R</b>econnaissance and e<b>X</b>ploration <b>A</b>ssistance</b>

<p align="justify">The rate of cross border trespassing/poaching and other illegal activities has increased excessively in recent years. We have learnt our lessons from past sad-and-deadly incidents like Pathankot terror attack which shook the whole world, and was a result of lack of security across the border areas. Our scalable and state of the art end-to-end solution helps secure a region. We take it as a game, where the AI assistant constantly tracks, locates anomalies and secures a region.</p>

Our mission and project synopsis can be read at [DARXA-Mission](http://www.darxa.in/mission.html).

### Status and Achievement of the work until December 2019

> ✔️ Smart India Hackathon 2018 : KPIT Innovation Award Winner

> 🔄 Discussions with Government of Assam with possibility to implement in Kaziranga National Park.

<p align=justify>This project includes Hardware as well as Software stack for end-to-end implementation. The work done at Smart India Hackathon had some limitations and not every feature was implemented. Research on Computer Vision and other Deep Learning areas have given us new cutting edge algorithms and possibilities to work upon.  </p>

### Google AI Explore ML Mentorship Bootcamp

<p align=justify>This project is selected for Google AI Explore ML Mentorship Bootcamp and further developments of the AI and ML algorithms will be done under <a href="https://www.linkedin.com/in/akshaybahadur21/">Akshay Bahadur</a> and <a href="https://www.linkedin.com/in/nikita-gandhi01/">Nikita Gandhi</a>. Expert suggestions and advices on the growth of the project for securing national parks, military installments and other confidential area as per the synopsis is of prime importance. The project is of large scale and needs time for it's growth and real world implementation.</p>

<p align=justify>Primary Focus of the project's growth in the bootcamp is with the development of AI Algorithms and making a robust software stack. The Hardware needs of the project will be worked upon over time.</p>

<b>SOFTWARE NEED</b> Analysis:

- ML & DL Algorithms [TensorFlow 2.0] (Applied Machine Learning and Deep Learning)

<img src="https://github.com/darxa/darxa-google-ai/blob/master/img/TF.png" height=90px><a> </a><img src="https://github.com/darxa/darxa-google-ai/blob/master/img/linux.png" height=90px>

- Android application for the handheld device [Flutter]

As most of the Machine Learning Algorithms will be in PHOENIX-T and TRACKODS with onboard neural compute stick, we don't need much processing capabilities in the android application. Development in the TF Lite World and Flutter will make all possibilities come true with time. For now our basic planned tech stack would be: 

<img src="https://github.com/darxa/darxa-google-ai/blob/master/img/tech_stack.png" height=220px>

- Distributed system architecture of the network of TRACKODS
- Operating System of PHOENIX-T [linux with opensource ROS]
- DARXA control center system architecture [Full Stack Development]


<hr />

## HIGHLIGHT - AI FEATURES:

## 🌌
> 🎄 STATE OF THE ART OBJECT DETECTION AND LOCALIZATION

<img src="https://github.com/darxa/darxa-google-ai/blob/master/img/obj/attention.png" height=150px><a> </a><img src="https://github.com/darxa/darxa-google-ai/blob/master/img/obj/dark.jpg" height=150px><a> </a><img src="https://github.com/darxa/darxa-google-ai/blob/master/img/obj/superres.jpg" height=150px><a> </a><img src="https://github.com/darxa/darxa-google-ai/blob/master/img/obj/thermal2.jpg" height=150px><a> </a><img src="https://github.com/darxa/darxa-google-ai/blob/master/img/obj/detect.png" height=150px>

<b>Tasks achieved</b>:
- [Image] Object Detection and Localization [Animals] [README](https://github.com/darxa/darxa-google-ai/blob/master/README/obj/IMGDETECT.MD)
- [Video] Object Detection and Localization [Animals] [README](https://github.com/darxa/darxa-google-ai/blob/master/README/obj/VIDDETECT.MD) - [Demo](https://youtu.be/sCrg1bD2Lno)
- [Realtime] Object Detection and Localization [Animals] [README](https://github.com/darxa/darxa-google-ai/blob/master/README/obj/VIDDETECT.MD) -[Demo](https://youtu.be/qkzmv4ny7VM)

<p align="justify">We need to work on detecting every other object that might be a threat - firearms, military vehicles, drones etc by training a better dataset and using Transfer Learning. Also more emphasis on collecting good datasets and indepth research on detecting  objects in IR vs NightVision vs Thermal imaging is mandatory.</p>

<b>Tasks todo</b>:
- SuperResolution using Deep Learning in TRACKODS [README]()
- Tracking using attention in Deep Learning [README]()
- See in the Dark (NightSight) [README]()

## 🌌
> 🎄 AUDIO FREQUENCY CLASSIFICATION WITH CNN AND RNN

<img src="https://github.com/darxa/darxa-google-ai/blob/master/img/voice/spectr.png" height=150px><a> </a><img src="https://github.com/darxa/darxa-google-ai/blob/master/img/voice/lstm.png" height=150px><a> </a><img src="https://github.com/darxa/darxa-google-ai/blob/master/img/voice/wav.png" height=150px>

<b>Tasks achieved</b>:
- Audio Classification with CNN [README](https://github.com/darxa/darxa-google-ai/blob/master/README/voice/AUDRECCNN.MD)

<b>Tasks todo</b>:
- Use of LSTM and attention for precise Audio classification [README]()
- Voice Assistance for PHOENIX-T from the control centre [README]()

## 🌌
> 🎄 PREDICTIVE ANALYSIS WITH VIZUALIZATIONS

<img src="https://github.com/darxa/darxa-google-ai/blob/master/img/pred/pgm.jpg" height=130px><a> </a><img src="https://github.com/darxa/darxa-google-ai/blob/master/img/pred/heat.jpg" height=130px><a> </a><img src="https://github.com/darxa/darxa-google-ai/blob/master/img/pred/data.png" height=130px><a> </a><img src="https://github.com/darxa/darxa-google-ai/blob/master/img/pred/event.gif" height=130px>

<b>Tasks achieved</b>:
- Poaching prediction [Dummy Dataset] [README](https://github.com/darxa/darxa-google-ai/blob/master/README/pred/PREDANALYSIS.MD)

<b>Tasks todo</b>:
- Classical Machine Learning approach on real world dataset (Use of past data) [README]()
- Probabilistic Graphical Models for Inference (Intelligence source) [README]()

## 🌌
> 🎄 SENSOR FUSION WITH REAL TIME TRACKING IN HANDHELD

<img src="https://github.com/darxa/darxa-google-ai/blob/master/img/sensor_fuse/pc.jpg" height=130px><a> </a><img src="https://github.com/darxa/darxa-google-ai/blob/master/img/sensor_fuse/satellite.jpg" height=130px><a> </a><img src="https://github.com/darxa/darxa-google-ai/blob/master/img/sensor_fuse/wifi.jpg" height=130px><a> </a><img src="https://github.com/darxa/darxa-google-ai/blob/master/img/sensor_fuse/auto.PNG" height=130px>

<b>Tasks achieved</b>:
- N/A

<b>Tasks todo</b>:
- 3D Mapping of an area with Point Cloud (Need suggestion on the best way to 3D Map an area) [README]()
- Realtime GPS location of rangers on the 3D-MAP (Application to Visualize) [README]()
- Shortest path between 2 GPS locations in the 3D-MAP (as used in Uber/Lyft/Ola) [README]()
- See through walls using - Wi-Vi [README]()
- Satellite Imagery analysis of a region [README]()
- Autonomous flight via coordinates path planning (Using sensor data - wind speed, weather etc) [README]()
- Simulation of Phoenix-T in the 3D-MAP using Reinforcement Learning [README]()

<img src="https://github.com/darxa/darxa-google-ai/blob/master/img/sih.jpg" height=70px><a> </a><img src="https://github.com/darxa/darxa-google-ai/blob/master/img/kpit.jpg" height=70px><a> </a><img src="https://github.com/darxa/darxa-google-ai/blob/master/img/glogo.png" height=70px>
