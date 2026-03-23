---
marp: true
theme: my_theme
math: katex
paginate: true
---

<!-- footer: <small><i>Kıvanç Tatar, Associate Professor in Interactive AI</small></i> <p> ![width:350](chalmers-gu.png)</p> -->

# Computational Arts and Music informed Machine Learning and Artificial Intelligence

<small> These slides are live at: 
https://ktatar.github.io/2026-03-uniarts/ </small>

![width:150](img/qrcode.png)

---

## Overview

---

What does Artificial Intelligence technology encapsulate?

- Good-old fashioned AI (Symbolic AI, Expert Systems, Rule-based Systems, etc.)
- Evolutionary Algorithms (Genetic Algorithms, Genetic Programming, etc.)
- Artificial Life
- Multi-agent Systems
- Machine Learning (Supervised, Unsupervised, Semi-supervised learning; such as SVMs, Decision Trees, Random Forests, KNN, etc.)
- Deep Learning (Artificial Neural Networks, Convolutional Neural Networks, Recurrent Neural Networks, Transformers, etc.)
- Deep Generative Models (Variational Autoencoders, Generative Adversarial Networks, Flow-based Models, etc.)
- Reinforcement Learning (Q-Learning, Deep Q-Networks, Policy Gradient Methods, etc.)
- Large Language Models (GPT, DeepSeek etc.)
- Multimodal Foundation Models

---

## Calculating Empires (Crawford and Joler 2023)

<small>https://calculatingempires.net/?pos=64626.91%2C13950.71%2C14.3640</small>
<div
  style="
    width: 100%;
    height: 70vh;
    max-height: 400px;
    border: 1px solid #ddd;
    border-radius: 12px;
    overflow: hidden;
    position: relative;
  "
>
  <iframe
    src="https://calculatingempires.net/?pos=64626.91%2C13950.71%2C14.3640"
    title="Calculating Empires"
    style="
      position: absolute;
      inset: 0;
      width: 100%;
      height: 100%;
      border: 0;
    "
    loading="lazy"
    referrerpolicy="no-referrer-when-downgrade"
    allowfullscreen
  ></iframe>
</div>

---

## Organizing Sound with Artificial Intelligence

![align-center width:1200](img/organised-sound.png)

---

### A Conversation with Artificial Intelligence

<iframe width="560" height="315" src="https://www.youtube.com/embed/VLtilZ2lcIA?si=BxKv39bkl7GiU9v8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

---

#### Musical Agents based on Self-Organizing Maps (MASOM)

K. Tatar, “Musical agents based on self-organizing maps for audio applications,” Thesis, Communication, Art & Technology: School of Interactive Arts and Technology, 2019. Available: http://summit.sfu.ca/item/19665

---

#### Co-Performance with MASOM

![align-center width:10000](img/masom-live.jpg)

---

## Deep Generative Modelling and Latent Spaces for Audio

What is a latent space? 

<iframe width="560" height="315" src="https://www.youtube.com/embed/vZgO2DEtfbY?si=JNQyDg6NISNX0LxW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

---

### Latent Timbre Synthesis

![align-center width:650](https://camo.githubusercontent.com/3fd7f5186b4aab037b57b340eddde353badf52b196389622f70db93117438264/68747470733a2f2f6769746c61622e636f6d2f6b74617461722f6c6174656e742d74696d6272652d73796e7468657369732f2d2f7261772f737461626c652f696d616765732f696e746572706f6c6174655f74776f5f75692e6a7067)

<small> K. Tatar, D. Bisig, and P. Pasquier, “Latent Timbre Synthesis,” Neural Computing & Applications, Oct. 2020, doi: 10.1007/s00521-020-05424-2.
</small>

---

#### Latent Timbre Synthesis

<iframe width="560" height="315" src="https://www.youtube.com/embed/ZJm-N_-ySe0?si=WDxjA7frj4Jj3COq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

---

#### Latent Timbre Synthesis
Architecture

![bg right width:400](img/timbre_vae.png)

---

#### Latent Timbre Synthesis

Interpolations in the latent space of the VAE

![align-left width:550](img/inter_latent_space_scatter.png)

![align-right width:550](img/full_latent_space_scatter.png)

---

#### Coding the Latent

<iframe width="560" height="315" src="https://www.youtube.com/embed/rfq82eKE-34?si=b3xsvPWKXwDRp12e&amp;start=2810" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

---

#### Coding the Latent

![align-center width:800](img/coding-the-latent-setup.png)

---

#### Sound Design Strategies for Latent Audio Space Explorations

![align-center width:900](img/smc-poster-3-strategies.jpg)

<small> K. Tatar, K. Cotton, and D. Bisig, “Sound Design Strategies for Latent Audio Space Explorations Using Deep Learning Architectures,” presented at the Proceedings of Sound and Music Computing 2023, 2023.</small>

---

#### Coding the Latent

![align-center width:900](img/coding-the-latent-arc.jpg)

---

#### Music Notation and Composition with Latent Spaces

**Meta-Benjolin**

![align-left width:500](img/meta-ben-1.png)

![align-right width:600](img/meta-ben-2.png)

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

<small>Madaghiele V., Lund L., Holzer D., Kelkar T., Tatar, K., and Holzapfel A. (2026). Expanding the machine: notating generative synthesis with a state-based representation and an interactive timbre space. Organised Sound, Cambridge Press.</small>

---

#### Music Notation and Composition with Latent Spaces

![align-center width:900](img/meta-ben-3.png)

---

#### Music Notation and Composition with Latent Spaces

![align-center width:800](img/meta-ben-4.png)

---

#### Music Notation and Composition with Latent Spaces

![align-center width:1200](img/meta-ben-5.png)

<small>Examples of the use of transitions to navigate long distances. D2 used a meander transition in the middle of the piece to connect two sections; within a section, neighbouring states are connected using crossfades. A5 used a crossfade and a meander transition to navigate between two neighbourhoods in the cloud, each corresponding to a section in their piece. (a) Composition by D2 (detail), Sound_example_4.m4a in the sound material. (b) Composition by A5 (detail), Sound_example_5.m4a in the sound material.
</small>

---

#### Music Notation and Composition with Latent Spaces
<small><https://meta-benjolin.com/></small>
<div
  style="
    width: 100%;
    height: 70vh;
    max-height: 400px;
    border: 1px solid #ddd;
    border-radius: 12px;
    overflow: hidden;
    position: relative;
  "
>
  <iframe
    src="https://meta-benjolin.com/"
    title="AI Dungeon"
    style="
      position: absolute;
      inset: 0;
      width: 100%;
      height: 100%;
      border: 0;
    "
    loading="lazy"
    referrerpolicy="no-referrer-when-downgrade"
    allowfullscreen
  ></iframe>
</div>

<small>Madaghiele V., Lund L., Holzer D., Kelkar T., Tatar, K., and Holzapfel A. (2026). Expanding the machine: notating generative synthesis with a state-based representation and an interactive timbre space. Organised Sound, Cambridge Press.</small>

---

#### Expert Procrastinator's Tool: Artificial Intelligence (2023)

<iframe width="560" height="315" src="https://www.youtube.com/embed/xdf1uKzGYfs?si=2ffM-WlVKZgfJasB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

---

---

#### Digital Ripples (2020)

<div
  style="
    width: 100%;
    height: 70vh;
    max-height: 400px;
    border: 1px solid #ddd;
    border-radius: 12px;
    overflow: hidden;
    position: relative;
  "
>
  <iframe
    src="https://objkt.com/tokens/hicetnunc/726715"
    title="Digital Ripples"
    style="
      position: absolute;
      inset: 0;
      width: 100%;
      height: 100%;
      border: 0;
    "
    loading="lazy"
    referrerpolicy="no-referrer-when-downgrade"
    allowfullscreen
  ></iframe>
</div>

---

#### Experiments with VQGAN Text-to-Image Synthesis

<video controls src="best-to-worst.mp4" width="450"></video>

---

#### Exposing the Bias in Artificial Intelligence: The Cyber Future

<iframe width="560" height="315" src="https://www.youtube.com/embed/79gJtoeOhHE?si=dHgWsZPMWFxTO_kt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

---

#### Exposing the Bias in Artificial Intelligence: The Machine Lexicon

<iframe width="560" height="315" src="https://www.youtube.com/embed/RhOfPQJSrok?si=oXLhS4DY-nMmvASS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

---

- Start from the theoretical foundations of your artistic practice
  - **From theoretical foundations of artistic practice -> Computational or Algorithmic approaches:**

- Ideate what would be interesting to automate

- Explore AI/ML approaches that are suitable to that



---

In parallel, 

Try new AI/ML tools and techniques that are relevant to your domain and practice continuously

Transform them with your wishes ie (expansion, conceptual shifting, cross-modal approaches, add, subtract etc.)

---

## Acknowledgements

| Country  | Funding Body  | Timeline |
|:---|:---|:---|
| Sweden | The Wallenberg AI, Autonomous Systems, and Software Program – Humanities and Society |2025-2030 |
| Sweden | VR - Vetenskapsrådet | 2025-2031 |
| Sweden | The Wallenberg AI, Autonomous Systems, and Software Program – Humanities and Society |2021-2026 |
| Canada | Canada Council for the Arts | 2018-2021 |
| Canada |BC Arts Council | 2020 |
| Switzerland | Swiss National Science Foundation | 2020-2021|
| Canada |Social Sciences and Humanities Research Council| 2014-2020 |
| Canada |Natural Sciences and Engineering Research Council| 2014- 2019 |

---
## Thank you! 

Feel free to reach out -> tatar@chalmers.se or info@kivanctatar.com

---

Downloading videos for offline backup:

https://github.com/yt-dlp/yt-dlp?tab=readme-ov-file#format-selection-examples

run on command line
make sure ffmpeg is installed

yt-dlp.exe [links goes here] -f "bv+ba/b" -t mp4