### Workshop at [Robotics: Science and Systems 2022](https://roboticsconference.org/)
### July 1st, 2022

![](composite.png)

## Description
Handling contact is a fundamental challenge in robotics. We want robots to interact with the world to do
something useful, which often requires physical interaction with the environment. Whether it is a warehouse
arm picking an object from a box, a search and rescue robot walking over broken terrain, or a home assistance
robot clearing the dishes, robots need to be able to enable, plan for, control through, sense, withstand, and
learn about contact events. However, contact necessarily involves a sudden change in dynamics – the effects
of motion while touching and almost touching can differ dramatically. Because of this, many robots seek to
avoid or minimize the effects of contact, for example by slowing down before touching an object. Furthermore,
robots go through great lengths to avoid unexpected contacts, by operating in controlled environments or
taking excessively conservative paths around obstacles.

This workshop seeks to push the field toward a future where robots aren’t afraid of contact. Where
accidentally bumping into something isn’t catastrophic, and where the robot doesn’t treat everything in the
environment as if it were made of egg shells. To get there, we need to reason about contact while considering
all aspects of the system design: the mechanism, sensing, control, planning, and learning must all account for
the challenges of real-world contact. This is also an issue that cuts across different application domains such
as manipulation or locomotion. Thus this workshop is designed to bring together researchers from across
the robotics field to explore new approaches to tackling this fundamental challenge.

To get the conversation started, here is a list of topics and questions for participants to think about (but other topics within the spirit of the above description will also be considered):
* Reactive or online planning and control to initiate and leverage contacts.
* Robustness to expected or unexpected contact events.
* Is a model-based structure necessary, or can unstructured learning methods succeed? What types of
problems might require or benefit from structure?
* Making sense of touch: leveraging spatially rich tactile sensing.
* The role of design and novel shapes to control interactions.
* Interacting with soft and deformable surfaces, and leveraging softness for robustness.
* How does the manner (fast/slow, accidental/intentional/adversarial) or physics (soft/hard, point/surface,
slippery/sticky) affect which solution(s) might be appropriate?




## Invited Speakers
We are excited to have an incredible group of invited speakers from a range of research backgrounds who are all excited to share their thoughts on this theme:

* [Pulkit Agrawal](https://people.csail.mit.edu/pulkitag/), Assistant Professor, Massachusetts Institute of Technology
* [Maria Bauza](https://web.mit.edu/bauza/www/), Ph.D. Candidate, Massachusetts Institute of Technology
* [Ken Goldberg](https://goldberg.berkeley.edu/), Professor, University of California, Berkeley
* [Yan Gu](https://www.uml.edu/engineering/mechanical/faculty/gu-yan.aspx), Assistant Professor, University of Massachusetts, Lowell
* [Kevin Lynch](https://robotics.northwestern.edu/people/profiles/faculty/lynch-kevin.html), Professor, Northwestern University
* [Zachary Manchester](https://www.ri.cmu.edu/ri-faculty/zachary-manchester/), Assistant Professor, Carnegie Mellon University
* [Carolyn Matl](https://carolyncmatl.github.io/), Research Scientist, Toyota Research Institute
* [Francesca Negrello](https://scholar.google.com/citations?user=pRTUzT4AAAAJ&hl=en), Postdoc, Istituto Italiano di Tecnologia
* [Alessandro Saccon](https://www.tue.nl/en/research/researchers/alessandro-saccon/), Assistant Professor, Eindhoven University of Technology

## Call for Contributions

We would like to invite contributed abstracts from the community that fit the themes of this workshop. Accepted abstracts will be presented as either posters or spotlight talks. Submissions may be on recently published work, upcoming papers, position papers, or work in progress. All accepted abstracts will be posted on this page. Submissions should follow the [RSS paper format](https://roboticsconference.org/information/authorinfo/) and should be one to two pages in length (including citations). Submissions should include a brief abstract at the start summarizing the work. 

**Submission deadline has past**

**Submission Deadline** For full consideration for speaking slots: **May 9th, 2022**, with decisions by May 20th, 2022.    
**Late Deadline** For poster-only consideration: **June 6th, 2022**, with decisions returned within two weeks of submission.    
**Workshop Date** The workshop will be held on: **July 1st, 2022**

## Schedule

Subject to change. Location: 451 CSB, Posters: CS Lounge

|Introduction & Welcome | 9:00-9:15 |
|[Maria Bauza](https://web.mit.edu/bauza/www/) | 9:15-9:35 |
|[Ken Goldberg](https://goldberg.berkeley.edu/) | 9:35-9:55 |
|[Carolyn Matl](https://carolyncmatl.github.io/) | 9:55-10:15 |
|Huanbo Sun | 10:15-10:30 |
|**Posters and coffee break** | 10:30-11:30 |
|[Kevin Lynch](https://robotics.northwestern.edu/people/profiles/faculty/lynch-kevin.html) | 11:30-11:50 |
|Panel Discussion 1 | 11:50-12:20 |
|**Lunch** | 12:20-1:50 |
|Taylor Howell | 1:50-2:05 |
|Yuki Shirai | 2:05-2:20 |
|[Francesca Negrello](https://scholar.google.com/citations?user=pRTUzT4AAAAJ&hl=en) | 2:20-2:40 |
|[Yan Gu](https://www.uml.edu/engineering/mechanical/faculty/gu-yan.aspx) | 2:40-3:00 |
|**Coffee break** | 3:00-3:30 |
|[Alessandro Saccon](https://www.tue.nl/en/research/researchers/alessandro-saccon/) | 3:30-3:50 |
|[Zachary Manchester](https://www.ri.cmu.edu/ri-faculty/zachary-manchester/) | 3:50-4:10 |
|[Pulkit Agrawal](https://people.csail.mit.edu/pulkitag/) | 4:10-4:30 |
|Panel Discussion 2 | 4:30-5:00 |

## Contributed Papers

The accepted abstracts for this workshop are:  \
[	Fast Contact-Implicit Model-Predictive Control](	cimpc_bumping_rss2022.pdf	), by 	Howell, Taylor; Le Cleac'h, Simon; Schwager, Mac; and Manchester, Zachary	  \
[	Insight: A Vision-based Haptic Sensor That Provides Rich Force Information about Contacts](	Insight_RSS_2022_Workshop_Paper.pdf	), by 	Sun, Huanbo; Kuchenbecker, Katherine J; and Martius, Georg	  \
[	Safe Supervisory Control of Soft Robot Actuators](	Safe_Supervisor_RSS_Workshop_2022-05-09.pdf	), by 	Sabelhaus, Andrew P; Patterson, Zach; Wertz, Anthony; and Majidi, Carmel	  \
[	Framework and Software for Real-Time Multi-Contact Model Predictive Control](	Aydinoglu_RSSWS_2022.pdf	), by 	Aydinoglu, Alp; and Posa, Michael	  \
[	Robust Pivoting Manipulation Using Bilevel Contact-Implicit Optimization](	RSS22_WS_Pivoting.pdf	), by 	Shirai, Yuki; Jha, Devesh K; Raghunathan, Arvind U; and Romeres, Diego	  \
[	Efficient Object Manipulation Planning with Monte Carlo Tree Search](	zhu22efficient_rssws.pdf	), by 	Zhu, Huaijiang; and Righetti, Ludovic	  \
[	Using Contacts During Robot Manipulation to Map and Reconstruct a Scene](	Joao_Bimbo_RSSWS_2022.pdf	), by 	Bimbo, Joao; Morgan, Andrew S; and Dollar, Aaron M.	  \
[	Python-based Open Source Package for Optimization of Contact-rich Systems](	RSS22_pyrobocop-3.pdf	), by 	Raghunathan, Arvind U; Jha, Devesh K; and Romeres, Diego  \
[	Developing Data-driven Methods for Mixed-integer Nonlinear Programs](	Lin_RSSWS_2022.pdf	), by 	Lin, Xuan; and Hong, Dennis W	  \
[	Dynamic Inference on Graphs using Structured Transition Models](	Saxena_RSSWS_2022.pdf	), by 	Saxena, Saumya; and Kroemer, Oliver	  \
[	Torque-Limited Manipulation Planning with Contact](	insat_ptc_extd_abs.pdf	), by 	Natarajan, Ramkumar; Likhachev, Maxim; and Choset, Howie	  \
[	Emergent Mechanism Design via Robot Swarms](	Taylor_RSSWS_2022.pdf	), by 	Taylor, Annalisa; Berrueta, Thomas A; and Murphey, Todd	  \
[	High-Speed Scooping Manipulation Using Controlled Compliance](	RSS2022WS_High_Speed_Scooping.pdf	), by 	Mak, Ka Hei; and Seo, Jungwon	  \
[	Hybrid Event Shaping to Stabilize Periodic Hybrid Orbits](	RSS_Workshop___Hybrid_Event_Shaping.pdf	), by 	Zhu, James; Kong, Nathan J; Council, George; and Johnson, Aaron	M  \
[	Solving the "Last Centimeter" Problem with Autonomous Grasping Reflexes](	SaLoutos_RSSWS_2022.pdf	), by 	SaLoutos, Andrew; Guo, Menglong; Stanger-Jones, Elijah; Kim, Hongmin; and Kim, Sangbae	  \
[	Automatic Tool Design for Robotic Caging Using Flexible Wires](	Ketchum_RSSWS_2022.pdf	), by 	Ketchum, Jake B; Meyer, Joel; and Murphey, Todd	  \
[	Designing Whisker Sensors for Noisy Environments](	Kent_RSSWS_2022.pdf	), by Kent, Teresa  A; Kim, Suhan; Babaei, Mahnoush; Emnett, Hannah; Hartmann, Mitra J. Z.; and Bergbreiter, Sarah


 
## Organizers

* [Aaron M. Johnson](https://www.andrew.cmu.edu/user/amj1/), Carnegie Mellon University
* [Michael Posa](https://www.grasp.upenn.edu/people/michael-posa/), University of Pennsylvania
* [Hannah Stuart](https://edg.berkeley.edu/people/hannah-stuart/), University of California, Berkeley
