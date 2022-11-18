# Embodied AI (具身智能) ![](https://visitor-badge.glitch.me/badge?page_id=putao537.Awesome-Embodied-AI)

<h4 align="center">Everything about Embodied AI.</h4>

<p align="center">
  <strong><a href="#0">Papers</a></strong> •
  <strong><a href="#1">Tutorials</a></strong> •
  <strong><a href="#2">Workshops</a></strong> •
  <strong><a href="#3">Talks</a></strong> •
  <strong><a href="#4">Companies & Labs</a></strong>
</p>

<p align="center">
  <strong><a href="#5">Technical Reports</a></strong> •
  <strong><a href="#6">Tasks</a></strong> •
  <strong><a href="#7">Simulation Environments</a></strong> •
  <strong><a href="#8">Datasets & Benchmarks</a></strong>
</p>


<h2 id="0">0. Papers</h2>

**By Tasks:** [[Locomotion]](Papers/locomotion.md) [[Visual Navigation]](Papers/visual_navigation.md) [[Object Manipulation]](Papers/object_manipulation.md) [[Others]](Papers/others.md)  

#### Survey
- A Survey of Embodied AI: From Simulators to Research Tasks, T-ETC 2022, [[PDF]](https://arxiv.org/abs/2103.04918)
- A Survey of Visual Navigation: From Geometry to Embodied AI, Eng. Appl. Artif 2022, [[PDF]](https://www.sciencedirect.com/science/article/pii/S095219762200207X)
- Deep learning for embodied vision navigation: A survey, arxiv 2021, [[PDF]](https://arxiv.org/abs/2108.04097)


<h2 id="1">1. Tutorials</h2>

|  **Pub.**  | **Title**                                                    |                          **Links**                           |
| :--------: | :----------------------------------------------------------- | :----------------------------------------------------------: |
| **CVPR'22** | Building and Working in Environments for Embodied AI | [HomePage](https://ai-workshops.github.io/building-and-working-in-environments-for-embodied-ai-cvpr-2022/) |


<h2 id="2">2. Workshops</h2>

|  **Pub.**  | **Title**                                                    |                          **Links**                           |
| :--------: | :----------------------------------------------------------- | :----------------------------------------------------------: |
| **CVPR'22** | Embodied AI Workshop | [HomePage](https://embodied-ai.org/) |
| **CVPR'21** | Embodied AI Workshop | [HomePage](https://embodied-ai.org/cvpr2021) |
| **ICCV'21** | SEAI: Simulation Technology for Embodied AI | [HomePage](https://iccv21-seai.github.io/) |
| **CVPR'20** | Embodied AI Workshop | [HomePage](https://embodied-ai.org/cvpr2020) |


<h2 id="3">3. Talks</h2>

<details>
  <summary> xxx </summary>
  
  ### 2022
|  **Pub.**  | **Title**                                                    |                          **Links**                           |
| :--------: | :----------------------------------------------------------- | :----------------------------------------------------------: |
| **TPAMI** | **[xxx]** xxxx | [PDF](xxx) |

</details>


<h2 id="4">4. Companies & Labs</h2>

### Companies

### Labs
- [Robotic Systems Lab](https://rsl.ethz.ch/), ETH Zurich
- [Stanford Vision And Learning Lab](https://svl.stanford.edu/), Standford
- [Robotics and Embodied AI Lab](https://montrealrobotics.ca/), Université de Montréal


<h2 id="5">5. Technical Reports</h2>

- A Path Towards Autonomous Machine Intelligence, Yann LeCun, [[PDF]](https://openreview.net/pdf?id=BZ5a1r-kVsf)
- Toward Next-Generation Artificial Intelligence:Catalyzing the NeuroAI Revolution, Zador et al., [[PDF]](https://arxiv.org/abs/2210.08340)

<h2 id="6">6. Tasks</h2>

<details>
  <summary> Locomotion </summary>  

</details>

<details>
  <summary> Visual Navigation </summary>  

  - **PointGoal Navigation** (arxiv 2018, [[PDF]](https://arxiv.org/abs/1609.05143)) requires an embodied agent to navigate form a starting location to a specific location. Some works propose to merely provide the tuple of (angle of goal, distance to goal) at the starting goal while other works propose to constantly update this tuple with the movement of agent.
  
  - **RoomGoal Navigation** (ICLR workshop 2018, [[PDF]](https://arxiv.org/abs/1801.02209)) requires an embodied agent that is initialized at a random position to navigateto a spicific room (e.g. bedroom or kitchen). 

  - **ObjectGoal Navigation** (ICRA 2017, [[PDF]](https://arxiv.org/abs/1609.05143)) requires an embodied agent that is initialized at a random starting position to find the target object. The target object is specified by an RGB image or semantic label. Moreover, some works propose to find novel objects by utilizing scene priors.
  
  - **Audio-Visual Navigation** (ECCV 2020, [[PDF]](https://arxiv.org/abs/1912.11474)) requires the embodied agent to navigate to a sound object by seeing and hearing.
  
  - **Vision-Language Navigation** (CVPR 2018, [[PDF]](https://arxiv.org/abs/1711.07280)) requires an embodied agent to follow natural language instructions to navigate from a starting pose to a goal location.  Besides, some works propose to provide language-based assistance when the agent is lost.

</details>


<details>
  <summary> Object Manipulation </summary>  


</details>


<details>
  <summary> Others </summary>  
  
  - **Embodied Question Answering** (CVPR 2018, [[PDF]](https://arxiv.org/abs/1711.11543)) puts an intelligent agent at random location in a 3D environment and asked a question. The agent must first intelligently navigate to explore the environment, gather necessary visual information through first-person (egocentric) vision, and then answer the question.
  
  - **IQA** (CVPR 2018, [[PDF]](https://arxiv.org/abs/1712.03316)) puts an intelligent agent at random location in a 3D environment and asked a question. This task requires an agent to navigate around the scene, acquire visual understanding of scene elements, interact with objects (e.g. open refrigerators) and plan for a series of actions conditioned on the question.
   
  
  - **Rearrangement** (arxiv 2020, [[PDF]](https://arxiv.org/pdf/2011.01975.pdf)) requires an agent moves objects in a room, such that they are restored to a given initial configuration.

  - **REVERIE** (CVPR 2020, [[PDF]](https://arxiv.org/abs/1904.10151)) requires an intelligent agent to correctly localize a remote target object (can not be observed at starting location) specified by a concise high-level natural language instruction.
  
  - **TOUCHDOWN** (CVPR 2019, [[PDF]](https://arxiv.org/abs/1811.12354)) requires an agent to first follow navigation instructions in a real-life visual urban environment, and then identify a location described in natural language to find a hidden object at the goal position.
  
  
</details>

<h2 id="7">7. Simulation Environments</h2>

- [AI2-THOR](https://ai2thor.allenai.org/) (arxiv'17, [[PDF]](https://arxiv.org/pdf/1712.05474.pdf))    

- [AI Habitat](https://aihabitat.org/) (ICCV'19, [[PDF]](https://arxiv.org/pdf/1904.01201.pdf))  
  
- [VirtualHome](http://virtual-home.org/) (CVPR'18, [[PDF]](https://arxiv.org/pdf/1806.07011.pdf))     
  
- [House3D](https://github.com/facebookresearch/House3D) (arxiv'18, [[PDF]](https://arxiv.org/pdf/1801.02209.pdf))   
  
- [Gibson](http://gibsonenv.stanford.edu/) (arxiv'18, [[PDF]](https://arxiv.org/pdf/1808.10654.pdf))  
  
- [Matterport3D](https://niessner.github.io/Matterport/) (3DV'17, [[PDF]](https://arxiv.org/pdf/1709.06158.pdf))   
  
- [UnrealCV](https://unrealcv.org/) (ACM MM'17, [[PDF]](https://arxiv.org/pdf/1709.06158.pdf))      
  
- [CHALET](https://github.com/lil-lab/chalet) (arxiv'18, [[PDF]](https://arxiv.org/pdf/1801.07357.pdf))      

- [ALFWorld](https://alfworld.github.io/) (ICLR'21, [[PDF]]([https://arxiv.org/pdf/1709.06158.pdf](https://arxiv.org/pdf/2010.03768.pdf)))    

- [RCareWorld](https://emprise.cs.cornell.edu/rcareworld/) (IROS 2022, [[PDF]](https://arxiv.org/abs/2210.10821))
  
<h2 id="8">8. Datasets & Benchmarks</h2>

### Physical Robotic Caregiving Tasks
    - Based on RCareWorld
    - Including **Feeding**, **Bathing**, **Dressing**, **Limb Repositioning**, **Ambulating**, **Toileting**.

</details>
