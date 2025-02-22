---
title: "<span style=\"color: blue; text-decoration: none;\"> Speech enhancement </span>"    
collection: talks
type: "Talk"
permalink: /talks/SE
---

---
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

---
###  Speech quality enhancemnet 
  
-- <font size=3> Interspeech2025 URGENT Challenge (Universal, Robust, and Generalizable speech EnhancemeNT systems) aims to bring more attention to constructing Universal, Robust and Generalizable speech EnhancemeNT models. To improve the universality of SE systems, the following distortions are considered: additive noise, reverberation, clipping, bandwidth extension, codec artifacts, packet loss, and wind noise. </font>  
![goal](/images/interspeechgoal.PNG){: .align-center width="700px"}
​ 
 

-- <font size=3> 4th place globally！</font>  
![results](/images/interspeechre.PNG){: .align-center width="700px"}
​ 

