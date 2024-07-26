---
title: "<span style=\"color: blue;\">Speech Enhancement</span>"
collection: talks
type: "Talk"
permalink: /talks/SE
---

---
## Speech Enhancement
- <font size=3> Sound quality restoration includes various aspects such as noise reduction, Howling suppression, and speech super-resolution, aiming to enhance overall audio quality.</font>  


---
###  Noise reduction
-- <font size=3> Based on neural network solutions, non-stationary noise can be effectively removed, achieving superior results compared to traditional algorithms. The model is lightweight, making it suitable for real-time implementation.</font>  
  
-- <font size=3> Before</font>  
![SE before](/images/nesebefore.png){: .align-center width="700px"}
​<audio id="audio" controls="" preload="none">
      <source id="wav" src="../files/nesebefore.wav">{: .align-center}
 

-- <font size=3> After</font>  
![SE after](/images/neseafter.png){: .align-center width="700px"}
​<audio id="audio" controls="" preload="none">
      <source id="wav" src="../files/neseafter.wav">{: .align-center}

-- Noise reduction *[DEMOPAGE](https://wanliangdaxia.github.io/){:target="_blank"}*.

---
###  Howling suppression

-- <font size=3> In sound amplification scenarios, the sound emitted by the speaker is picked up again by the microphone, forming a closed loop and causing a piercing feedback noise. This not only easily damages equipment but also affects the auditory experience.</font>  

-- <font size=3> Before</font>  
![Howling before](/images/howlbefore.JPG){: .align-center width="700px"}
​<audio id="audio" controls="" preload="none">
      <source id="wav" src="../files/howl-noisy.wav">{: .align-center}
 

-- <font size=3> After</font>  
![Howling after](/images/howlafter.JPG){: .align-center width="700px"}
​<audio id="audio" controls="" preload="none">
      <source id="wav" src="../files/howl-enhance.wav">{: .align-center}

--- 
###  Speech super-resolution 

-- <font size=3> The main purpose of SSR it to convert low-sample-rate speech into high-sample-rate speech to enhance the listening experience. </font>  

-- <font size=3> Before</font>  
![super before](/images/superbefore.png){: .align-center width="700px"}
​<audio id="audio" controls="" preload="none">
      <source id="wav" src="../files/superbefore.wav">{: .align-center}
 

-- <font size=3> After</font>  
![super after](/images/superafter.png){: .align-center width="700px"}
​<audio id="audio" controls="" preload="none">
      <source id="wav" src="../files/superafter.wav">{: .align-center}

-- SSR *[DEMOPAGE](https://sdnetdemo.github.io/){:target="_blank"}*.
