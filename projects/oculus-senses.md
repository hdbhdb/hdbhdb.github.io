---
title: Using VR to Study the Senses in Context
layout: no-sidebar-page
---
The past few decades of brain research in _multisensory integration_ has demonstrated that many of our taken-for-granted ideas about how the senses work are misguided. Among other things, we have learned that auditory or visual or touch perception very rarely happens without being affected by other senses. Sensory perception always occurs _in the context of other senses_: the way your brain processes the sounds you hear, for example, is fundamentally changed by what you are seeing. Still, most of this and other perception research has relied on simple computer interfaces using flashes of white light and bursts of white noise to understand how the human sensory system works. In recent conversations in the field, this body of research has been complicated by mounting evidence that there are other contextual factors at play that can affect how sensory information interacts. Pushing this idea of _contextual sensory research_ further, they say that these relatively simplistic studies tell us little about how the brain make sense of information coming from eyes, ears and elsewhere in the noisier and more distracting contexts of the real world. So how is it possible to reconcile the knowledge about what the brain does out of context in a laboratory setting with the difficulty of studying what the brain does elsewhere in the unpredictable settings where it actually matters how the sensory environment comes together?

<br>
![...](/assets/ms-detection.gif){:width="100%"}

>Example of a classic minimal psychophysics experiment. The research participant presses a button when they see the white circle or a noise that might accompany it.

<br>

In our neuroscience study, we were interested in how the human brain integrates audio and visual sensory information in complex environments like the ones we experience in real life. In order to study what the brain does in a setting that is both controlled and relatively realistic, we made use of immersive technologies like "virtual reality" to fabricate more complex environments and scenarios. Because the development of immersive technologies continues to outpace that of mobile "_in situ_ brain imaging", VR and other technologies remain very valuable tools for neuroscientists and psychologists to use to understand brain activity outside the lab.


<br>
![...](/assets/vr-room.jpg){:width="100%"}
>Sound-proofed VR room with Oculus Rift and mounted surround-sound speakers which we used to study audio-visual integration in the brain

<br>

For this project I used the Oculus Rift HMD, a surround sound speaker system, and VR environments I built using Vizard, Python and 3DS Max to create an immersive version of classic multisensory psychophysics experiments. Our initial sketches of these environments emphasized different kinds of contextual features we could exploit in order to get a range of complex and simple virtual worlds. By making some of the environments minimal and more like the classic psychophysics experiments, we could identify patterns in how the brain extracts multisensory information from environments that are more complex versus less complex. This ability of VR to produce either highly realistic or simple worlds lets us investigate the 'ecological validity' of experimental paradigms: how the results of past brain experiments might scale to the real world. With data collection features I had built into a prototype version of the study, I was also able to use motion and response data to narrow-down our environments to ones which represented an ideal range of sparse and more information-dense contexts.

On one end, my responsibilities in this project included coding VR environments using the _Vizard_ Python library and development platform,[^1] reformulating research questions in order to meet technically-achievable goals, creating a data system for organizing and analyzing the vast amounts of information accessible via VR, and performing extensive hardware troubleshooting and modification to retool entertainment devices to fit the needs and standards of a scientific experiment. On the other end, I was responsible for recruitment, scheduling, study moderation, debriefing, and moreover introducing people to VR without setting their expectations to high.

<br>

| [![...](/assets/task-sketches.jpg)](/assets/task-sketches.jpg){:width="100%"} <small>Sketches of trial structure schematic and room dimension testing</small>| [![...](/assets/task-flow.jpg)](/assets/task-flow.jpg){:width="100%"} <small>Low-fi wireframe demonstrating final experiment run-through</small>|
|[![...](/assets/vr-exp.png)](/assets/vr-exp.png){:width="100%"} <small>One of the virtual environments used in the study was made to look like the experiment room</small> | [![...](/assets/vr-exp-2.png)](/assets/vr-exp-2.png){:width="100%"} <small>An environment I designed for our second round of VR multisensory studies</small> |

<br>

I also laid the groundwork in research planning and VR environment design for the lab's follow-up VR study on "cross-modal attentional cuing" in complex environments, completed after I had graduated from the lab.

Our two-part _multisensory detection_ study led to interesting and unexpected findings about how the brain integrates sensory information in more complex environments, which we published in Multisensory Research.[^2] Our research also served as a proof of concept for using VR technologies to replicate past research and verify principle findings in neuroscience. I presented our results at [the annual Society for Neuroscience conference](http://www.abstractsonline.com/Plan/ViewAbstract.aspx?mID=3744&sKey=8ffdb9bb-e46a-4d5d-8eba-d2ab4dd08884&cKey=b23bba56-576a-48aa-a886-c95fb61bb543&mKey=d0ff4555-8574-4fbb-b9d4-04eec8ba0c84) and gave a related discussion-panel [talk](https://www.dropbox.com/s/wio5f70xiyqvpx7/synesthesia-symposium-april-15-updated-figures.pdf?dl=0) at an interdisciplinary symposium on synesthesia and the intersection of humanities and sciences.

<br>

[Back to projects](../)

[^1]: [Vizard](https://www.worldviz.com/vizard-virtual-reality-software) is an alternative to the more popular Unity platform that (as of 2015) offers better control for over extremely precise timing of events--essential for any studies working with temporal data on the scale of milliseconds or nanoseconds.

[^2]: Bailey, H. D., Mullaney, A. B., Gibney, K. D., & Kwakye, L. D. (2018). [Audiovisual integration varies with target and environment richness in immersive virtual reality](http://booksandjournals.brillonline.com/content/journals/10.1163/22134808-20181301). *Multisensory Research*, 31(7), 689 – 713. doi:10.1163/22134808-20181301
