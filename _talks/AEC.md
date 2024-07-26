---
title: "<span style=\"color: blue; text-decoration: none;\"> Acoustic echo cancellation </span>"
collection: talks
type: "Talk"
permalink: /talks/AEC
---
 
---
- <font size=3> Acoustic Echo Cancellation (AEC) uses the far-end signal as a reference to eliminate echoes in the near-end signal, ensuring clear communication.</font>  


---
###  <font size=4> Single channel AEC </font>
-- <font size=3> By utilizing time-frequency domain information, we designed a real-time full-network model for echo cancellation and noise suppression, distinct from the commonly used traditional methods followed by post-filtering solutions.</font>  
  
-- <font size=3> Before AEC </font>  
![AEC before](/images/neaecmic.JPG){: .align-center width="700px"}
​<audio id="audio" controls="" preload="none">
      <source id="wav" src="../files/neaecmic.wav">


-- <font size=3> After AEC</font>  
![AEC before](/images/neaecout.JPG){: .align-center width="700px"}
 ​<audio id="audio" controls="" preload="none">
      <source id="wav" src="../files/neaecout.wav">

---
### <font size=4> Stereo AEC</font>
-- <font size=3> In stereo acoustic echo cancellation (SAEC), a microphone receives echoes from multiple loudspeakers, making it difficult to identify the echo paths and significantly complicating the echo cancellation task.</font>  

-- <font size=3> Before SAEC</font>  
![SAEC before](/images/saecbefore.png){: .align-center  width="700px"}
​<audio id="audio" controls="" preload="none">
      <source id="wav" src="../files/saecbefore.wav">
 

-- <font size=3> After SAEC</font>  
![SAEC before](/images/saecafter.png){: .align-center width="700px"}
​<audio id="audio" controls="" preload="none">
      <source id="wav" src="../files/saecafter.wav">
 
 

