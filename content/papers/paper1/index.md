---
title: "Cooperative bus holding and stop-skipping: A deep reinforcement learning framework" 
date: 2024-01-01
tags: ["reinforcement learning","public transit","bus control","multi-agent systems","simulation"]
author: ["Joseph Rodriguez","Haris N. Koutsopoulos","Shenhao Wang","Jinhua Zhao"]
description: "A multi-agent deep reinforcement learning framework for cooperative bus holding and stop-skipping control. Published 2024." 
summary: "A multi-agent deep reinforcement learning framework that combines holding and stop-skipping strategies for bus control, evaluated on a complex route from the Chicago transit network."
cover:
    image: "paper1.png"
    alt: "[Placeholder image — final figure to be added]"
    relative: true
editPost:
    URL: "https://github.com/josephrodvar/josephrodvar.github.io"
    Text: "[Journal placeholder]"

---

---

##### Download

+ [Paper (placeholder)](paper1.pdf)
+ [Online appendix (placeholder)](appendix1.pdf)
+ [Code and data (placeholder)](https://github.com/josephrodvar/josephrodvar.github.io)

---

##### Abstract

The bus control problem that combines holding and stop-skipping strategies is formulated as a multi-agent reinforcement learning (MARL) problem. Traditional MARL methods, designed for settings with joint action-taking, are incompatible with the asynchronous nature of at-stop control tasks. On the other hand, using a fully decentralized approach leads to environment non-stationarity, since the state transition of an individual agent may be distorted by the actions of other agents. To address it, we propose a design of the state and reward function that increases the observability of the impact of agents' actions during training. An event-based mesoscopic simulation model is built to train the agents. We evaluate the proposed approach in a case study with a complex route from the Chicago transit network. The proposed method is compared to a standard headway-based control and a policy trained with MARL but with no cooperative learning. The results show that the proposed method not only improves level of service but it is also more robust towards uncertainties in operations such as travel times and operator compliance with the recommended action.

---

##### Figure 1: [Placeholder — final figure to be added]

![](paper1.png)

---

##### Citation

Rodriguez, Joseph, Haris N. Koutsopoulos, Shenhao Wang, and Jinhua Zhao. 2024. "Cooperative bus holding and stop-skipping: A deep reinforcement learning framework." *[Journal placeholder]*.

```latex
@article{placeholder,
author = {Joseph Rodriguez and Haris N. Koutsopoulos and Shenhao Wang and Jinhua Zhao},
year = {2024},
title = {Cooperative bus holding and stop-skipping: A deep reinforcement learning framework},
journal = {[Journal placeholder]},
url = {[URL placeholder]}}
```

---

##### Related material

+ [Presentation slides (placeholder)](presentation1.pdf)

