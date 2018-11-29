# DEEPWAVE: Deep Learning based Real-time Water Wave Simulation

Source code for course project in CS230 Virtual Reality.

### Abstract
Water surface simulation is an important task in computer animation. Today’s simulation techniques are highly realistic. However, these techniques usually `require extensive offline computation`. It is difficult to compute the details of water wave in large phenomena. Effective `real-time simulating techniques` of water wave are necessary for many interactive applications such as virtual reality and games.

We present `DEEPWAVE, a novel water wave simulation technique based on deep learning and wave packet theory`. Instead of solving the physics equations, we use data-driven learning-based methods to do the simulation for wave packets. There are two models available in DEEPWAVE, namely `packet-wise method` and area-wise method. Packet-wise method runs inference for every packet while `area-wise method` runs inference for every sub area patch.

Experiment results show that both of them `can effectively learn the motion of water wave`. In addition, by training our models on better data, we can fix the artifacts produced by existing methods. Our models run very fast on modern GPU through highly optimized deep learning frameworks, so it also shows the potential to accelerate the existing CPU-based physical engine.

### Example water wave simulated by DeepWave:
![](example.gif)

### See My Paper and PDF of Presentation for more details
![](presentation.pdf)

### Requirements:
```
Visual Studio
Tensorflow == 1.3.0
```

### Reference
```
Water Wave Packet
https://github.com/jeschke/water-wave-packets
```
