---
date: '2026-01-14T18:42:53-08:00'
draft: false
title: 'Cutscene Design and Implementation for Behavioral Study'
weight: 4
---
_"Animated 16 cutscenes using Unity Timeline to simulate different scenarios from the perspective of a user in a VR social space."_

{{< cards cols="2" >}}
  {{< card title="Role: Main Programmer" subtitle="Used Unity, Unity EditorTools and Timeline to record videos" >}}
  {{< card image="images/unity_timeline.png" subtitle="Unity timeline">}}
{{< /cards >}}

For this project, I used Unity Timeline to create cutscenes that would then be recorded into videos and used for social research. The cutscenes were each 2-8 minutes long and involved several characters moving in and out of frame, camera panning, voice lines with spatial audio, and particle effects. I moved the models to record keyframes and inserted audio or effects as the scripts dictated.

The project required certain scenarios to share significant portions of animation so I explored the EditorTools API in Unity and built some functionality to cut and paste keyframes, which was extremely useful and enabled me to distribute animation work to the other members of the research group.  

---

This work was part of a research group of 4 undergrad students led by Vivek Rao under the UC Berkeley Design for Cybersecurity group. Each cutscene scenario would present the situation that you were in a VR social space (like VRChat) and you would watch other people’s digital avatars commit social fallacies and then be subjected to moderation. 

For example, in some scenarios a moderator player might explain the rule violation and mute the violator, and in other scenarios the rule violator would just disappear. Sometimes there would be no moderator and the scenario would indicate that other players were choosing to mute the violator individually. The research study intended to show these scenarios to people and discover people’s preferences of moderation on these scales (opaque vs transparent rules, centralized vs decentralized moderation, etc). 

We completed making cutscenes and were in the process of designing the trial. I don’t know if this study was ever conducted as it was interrupted by several factors, namely the COVID-19 pandemic. 
