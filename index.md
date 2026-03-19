---
marp: true
theme: my_theme
math: katex
paginate: true
---

<!-- footer: <small><i>Kıvanç Tatar, Associate Professor in Interactive AI</small></i> <p> ![width:350](chalmers-gu.png)</p> -->

# Machine Learning and Artificial Intelligence Applied to Computational Arts, Music, and Games



<small> These slides are live at: 
https://ktatar.github.io/2026-03-docent-lecture/ </small>

![width:150](img/qrcode.png)


---

## Research Themes

- Deep Learning and Audio
- Multimodal Deep Learning for Movement and Audio
- AI in Computational Creativity and Game Design
- Societal Impact of AI in Culture, Arts, and Music

---

---

### Deep Learning and Audio

Focuses on technical innovations in sound synthesis and modeling using deep learning:

- Latent Timbre Synthesis
- Coding the Latent Artwork and RawAudio Variational Autoencoder
- Neuralacoustics
- Music Notation and Composition with Latent Spaces

---

### Deep Learning and Audio

- **Latent Timbre Synthesis**
- Coding the Latent Artwork and RawAudio Variational Autoencoder
- Neuralacoustics
- Music Notation and Composition with Latent Spaces

---

#### Latent Timbre Synthesis

<iframe width="560" height="315" src="https://www.youtube.com/embed/ZJm-N_-ySe0?si=WDxjA7frj4Jj3COq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<small> K. Tatar, D. Bisig, and P. Pasquier, “Latent Timbre Synthesis,” Neural Computing & Applications, Oct. 2020, doi: 10.1007/s00521-020-05424-2.
</small>

---

#### Latent Timbre Synthesis

![align-center width:700](https://camo.githubusercontent.com/3fd7f5186b4aab037b57b340eddde353badf52b196389622f70db93117438264/68747470733a2f2f6769746c61622e636f6d2f6b74617461722f6c6174656e742d74696d6272652d73796e7468657369732f2d2f7261772f737461626c652f696d616765732f696e746572706f6c6174655f74776f5f75692e6a7067)

---

#### Latent Timbre Synthesis

![bg right width:400](img/timbre_vae.png)

---

#### Latent Timbre Synthesis

Notes on Reproducibility

![bg right width:600](img/run_logs.png)

---

#### Latent Timbre Synthesis

Notes on Reproducibility

![align-left width:1200](img/interpolations_small.png)

---

#### Latent Timbre Synthesis

Interpolations in the latent space of the VAE

![align-left width:550](img/inter_latent_space_scatter.png)

![align-right width:550](img/full_latent_space_scatter.png)

---

### Deep Learning and Audio

- Latent Timbre Synthesis
- **Coding the Latent Artwork and RawAudio Variational Autoencoder**
- Neuralacoustics
- Music Notation and Composition with Latent Spaces

---

#### Coding the Latent Artwork and RawAudio Variational Autoencoder 

<iframe width="560" height="315" src="https://www.youtube.com/embed/rfq82eKE-34?si=1yz17QB_0yfCKHvS&amp;start=2160" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<small> K. Tatar, K. Cotton, and D. Bisig, “Sound Design Strategies for Latent Audio Space Explorations Using Deep Learning Architectures,” presented at the Proceedings of Sound and Music Computing 2023, 2023.</small>

---

#### RawAudio Variational Autoencoder

![align-center width:900](img/smc-poster-3-strategies.jpg)

---

#### RawAudio Variational Autoencoder

![align-center width:900](img/coding-the-latent-arc.jpg)

---

#### Coding the Latent

![align-center width:800](img/coding-the-latent-setup.png)
    
---

### Deep Learning and Audio

- Latent Timbre Synthesis
- Coding the Latent Artwork and RawAudio Variational Autoencoder
- **Neuralacoustics**
- Music Notation and Composition with Latent Spaces

---

#### Neuralacoustics

![align-left width:450](img/neuralacoustics-1.png)

![align-right width:700](img/neuralacoustics-4.png)

<small>Chen, J., Tatar, K., & Zappi, V.. (2024). A Deep Learning Framework for Musical Acoustics Simulations. In Proceedings of the AI Music Creativity Conference. Oxford, London, September 2024. https://aimc2024.pubpub.org/pub/5cl1cvmy/release/1</small>

---

#### Neuralacoustics

![align-center width:750](img/neuralacoustics-3.png)

---

#### Neuralacoustics

![align-center width:500](img/neuralacoustics-2.png)

---

### Deep Learning and Audio

- Latent Timbre Synthesis
- Coding the Latent Artwork and RawAudio Variational Autoencoder
- Neuralacoustics
- **Music Notation and Composition with Latent Spaces**

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

![align-center width:1200](img/meta-ben-6.png)

<small>The space distribution of these two compositions gives information about how the sound evolves in time. While composer D3 created a gradual and constant evolution by navigating the whole point cloud using the meander transition, B3 was interested in exploring local variations and nuances. This difference can be seen by the fact that the viewpoint is zoomed far out in (a), while it is much closer to the cloud in (b).</small>

---

## Research Themes

- Deep Learning and Audio
- **Multimodal Deep Learning for Movement and Audio**
- AI in Computational Creativity and Game Design
- Societal Impact of AI in Culture, Arts, and Music

---

### Multimodal Deep Learning for Movement and Audio

- **Reinforcement Learning for Musical Performances with Moving Machines**
- Raw Music from Free Movements
- Neural Audio Instruments

---

#### Reinforcement Learning for Musical Performances with Moving Machines

![bg left width:500](img/ergo.webp)

![align-center width:250](img/ergo-1.png)

<small>Caravati, Matteo, Tatar, Kıvanç. (2024). Interfacing ErgoJr with Creative Coding Platforms. In Proceedings of the 9th International Conference on Movement and Computing. Utrecht, Netherlands, May 2024. https://dl.acm.org/doi/10.1145/3658852.3659082</small>

---

![align-left width:500](img/ergo-2.png)

![align-center width:400](img/ergo-3.png)

---

### Multimodal Deep Learning for Movement and Audio

- Reinforcement Learning for Musical Performances with Moving Machines
- **Raw Music from Free Movements**
- Neural Audio Instruments

---

#### Raw Music from Free Movements

![align-center width:1300](https://ktatar.github.io/rawmusicfromfreemovements/content/movement_audio.png)

<small>Tatar, K., Cotton, K., Bisig, D. (2023). Sound Design Strategies for Latent Audio Space Explorations Using Deep Learning Architectures. In Proceedings of Sound and Music Computing 2023. https://arxiv.org/pdf/2305.15571 </small>

---

#### Raw Music from Free Movements

![align-center width:900](img/ramfem-architecture.png)

---

### Multimodal Deep Learning for Movement and Audio

- Reinforcement Learning for Musical Performances with Moving Machines
- Raw Music from Free Movements
- **Neural Audio Instruments**

---

#### Neural Audio Instruments

<br>

The six takeaways from our conceptualization of neural audio instruments:

- Stand on the shoulders of giants
- Search for new modes of interaction
- Challenge dualities
- Embrace inexplicability (with a grain of salt)
- Make AI inconspicuous

<br>
<br>
<br>

<small>Neural audio instruments: Epistemological and phenomenological perspectives on musical embodiment of deep learning. Frontiers in Computer Science, 7. https://doi.org/10.3389/fcomp.2025.1575168</small>

---

**0.Stand on the shoulders of giants**

- All the core insights from the DMI literature remain relevant 
- Challenges like the control bottleneck and the symbolic nature of action-to-sound can become more pronounced under AI/ML conditions 
- Established guidance on fostering embodiment in DMIs still applies here as a vital starting point!

---

**1.Search for new modes of interaction.** 
   
- The behaviors and “materials” of any instrument strongly condition how musicians interact with it 
- Neural networks, however, may exhibit properties not easily paralleled in earlier instruments. 
- Novel paradigms, such as directly “traversing” multi-dimensional latent spaces, might offer fresh avenues for mapping movement and cognition to sonic outcomes

---

**2.Challenge dualities**

- A pressing and practical concern for DMIs lies in the traditional control–synthesis divide and the predicate of mapping. 
- We do not suggest abandoning mapping altogether; exploration of how gesture connects to sound is a valuable design tool. 
- We advocate a holistic design perspective where sound and gesture are conceived as a unified entity from the outset, rather than as two separate “containers” later bound by mapping 

---

**3.Embrace inexplicability (with a grain of salt).**
   
- While research on explainable AI is undoubtedly worthwhile, non-explainability can play a significant role in the use and design of neural audio instruments.
- Performers and even designers of neural audio systems may choose to focus on musical outcomes rather than dissecting every underlying process. 
- Indeed, not all instrument designs are “predicated on the application of scientific knowledge” (Green, 2011) and a certain measure of “unknowing” can inspire extraordinary results. 
- This notion also resonates with broader human-computer interaction discourse on the creative power of ignorance (Grammenos, 2014) (ranging from lack of preconceptions, to true ignorance), where “if you already know where you are going, you are not going someplace new.”

---

**4. Make AI inconspicuous.**

- When the AI is not intended to act as a distinct musical agent, making its presence explicit may be unnecessary or even counterproductive.
- Designers might treat neural audio models as just another invisible part of the instrument's anatomy, like the string of a piano or the integrated circuit of an analog synthesizer. 
- By letting the model manifest itself only through the embodiment of the musician's actions and intentions, the performer can experience a unified instrument rather than a model endowed with conspicuous (artificial) intelligence
- By rendering the model seamlessly integral, designers promote an experience of playing an instrument rather than interfacing with an AI model.

---

## Research Themes

- Deep Learning and Audio
- Multimodal Deep Learning for Movement and Audio
- **AI in Computational Creativity and Game Design**
- Societal Impact of AI in Culture, Arts, and Music

---

### AI in Computational Creativity and Game Design

- Towards Computationally Creative Game Design
- Understanding Co-Storytelling with Large Language Models (LLMs)
- AEGIS: Authentic Edge Growth In Sparsity for Link Prediction
- Grounding Machine Creativity in Game Design Knowledge Representations

---

### AI in Computational Creativity and Game Design

- Towards Computationally Creative Game Design
- Understanding Co-Storytelling with Large Language Models (LLMs)
- AEGIS: Authentic Edge Growth In Sparsity for Link Prediction
- Grounding Machine Creativity in Game Design Knowledge Representations

---

#### Towards Computationally Creative Game Design

![bg right width:650](img/co-occurrence-network.jpg)

Reviewed 236 studies on learning-based AI in game design

While AI technologies are widely applied for functional and procedural tasks, **creativity remains underexplored**

We investigated the correlation between the appearance of creativity-related terms and their co-occurrence with other keywords. 

The co-occurrence network here visualizes the relationships and connections between frequently co-occurring keywords within the same article. 

---

#### Understanding Co-Storytelling with Large Language Models (LLMs)

<small> AI Dungeon (<https://play.aidungeon.com/>)  is a text-based adventure game that uses a large language model to generate dynamic and interactive storytelling experiences. Players can input any action or dialogue, and the AI responds with narrative developments, creating a unique story each time. This game exemplifies how LLMs can be used for co-storytelling, allowing players to collaboratively create narratives with the AI in real-time. </small>

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
    src="https://play.aidungeon.com/"
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

---

#### Understanding Co-Storytelling with Large Language Models (LLMs)

![align-center width:800](img/llm-research-design.png)

---

#### Understanding Co-Storytelling with Large Language Models (LLMs)

- Users treat LLM co-storytelling as interactive play
- AI imperfections (repetition, incoherence, abrupt shifts, incompleteness) came forward as creative affordances rather than failures.
- Players perceive the AI as a semi-autonomous collaborator in a story that is written together
- User experience revolves around shifting agency between the machine and the player
- Users develop strategies for controlling or guiding the LLM via narrative perspective, prompts, and system features (Story Cards, World Info, Author’s Notes).
- Multimodal storytelling is emerging, with image generation expanding narrative expression.
- Highlights: Wabi-sabi (imperfection appreciation), anthropomorphism/power dynamics, and the game–tool duality of LLM storytelling systems.

---

Previous work: Game Design Patterns (Bjork and Holopainen, 2005) includes 200 patterns.

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
    src="http://virt10.itu.chalmers.se/index.php/Category:Patterns"
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

<small> <http://virt10.itu.chalmers.se/index.php/Category:Patterns> 
Bjork, S., and Holopainen, J. 2005. Patterns in game design, volume 11. Charles River Media Hingham. </small>

---

**Classification** -> Embedding -> Generative Game Synthesis

AEGIS: Authentic Edge Growth In Sparsity for Link Prediction approached the classification problem as a link prediction task.

---

#### AEGIS: Authentic Edge Growth In Sparsity for Link Prediction

**Game Design Patterns** (Bjork and Holopainen, 2005)

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
    src="https://gdpv.is"
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


---

#### Grounding Machine Creativity in Game Design Knowledge Representations
*Empirical Probing of LLM-Based Executable Synthesis of Goal Playable Patterns under Structural Constraints*

We investigated whether large language models can translate structured game‑design knowledge—specifically goal‑pattern  abstractions—into executable Unity game scenes

**Game Development Framing:** Digital game development as a computational creativity activity, in which design‑pattern abstractions and game engine constraints guide the creation of an executable, playable game
**Execution‑grounded evaluation pipeline:** An end‑to‑end workflow (LLM generation → Unity batch compilation → log‑based failure analysis) for assessing executable viability at scale.
**Insights on human–machine knowledge boundaries:** Game design pattern knowledge injection increases structural complexity requirement at generation, revealing a tension in how domain knowledge should be injected into generative systems.

<small>H. X. Liu and K. Tatar, “Grounding Machine Creativity in Game Design Knowledge Representations: Empirical Probing of LLM-Based Executable Synthesis of Goal Playable Patterns under Structural Constraints,” Mar. 16, 2026, arXiv: arXiv:2603.07101. doi: 10.48550/arXiv.2603.07101. </small>

---

### Societal Impact of AI in Culture, Arts, and Music

---

#### A Shift in Artistic Practices through Artificial Intelligence 

![align-center width:900](img/a-shift-1.jpg)

<small>K. Tatar et al., “A Shift in Artistic Practices through Artificial Intelligence,” Leonardo, pp. 293–297, Apr. 2024, doi: 10.1162/leon_a_02523.</small>

---

#### Caring Trouble and Musical AI

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
    src="https://holly.plus"
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

<small>K. Cotton and K. Tatar, “Caring Trouble and Musical AI: Considerations towards a Feminist Musical AI,” in AIMC 2023, Aug. 2023. Accessed: Feb. 22, 2024. [Online]. Available: https://aimc2023.pubpub.org/pub/zwjy371l/release/1
</small>

---

#### Caring Trouble and Musical AI

![align-center width:1000](img/caring-trouble-1.jpg)

<small>Haraway, D. (2013). A cyborg manifesto: Science, technology, and socialist-feminism in the late twentieth century. In The transgender studies reader (pp. 103–118). Routledge.</small>


---

#### Caring Trouble and Musical AI

![align-center width:1100](img/caring-trouble-2.jpg)

---

#### Caring Trouble and Musical AI

![align-center width:550](img/caring-trouble-3.png)

---

### Artworks

---

#### Expert Procrastinator's Tool: Artificial Intelligence (2023)

<iframe width="560" height="315" src="https://www.youtube.com/embed/xdf1uKzGYfs?si=2ffM-WlVKZgfJasB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

---

#### Conceptual Pillars of Artistic Creativity

![align-center width:1000](img/artwork-1.jpg)

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
# Thank you! 

Feel free to reach out -> tatar@chalmers.se
