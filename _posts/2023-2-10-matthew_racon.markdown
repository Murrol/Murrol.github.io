---
layout: post
title:  "RACon: Retrieval-Augmented Simulated Character Locomotion Control with Diverse Skills"
date:   2023-02-10 22:21:59 +00:00
image: /images/racon23.pdf
categories: research
author: "Yuxuan Mu"
authors: "<strong>Yuxuan Mu</strong>, Shihao Zou, Kangning Yin, Zheng Tian, Li Cheng, Weinan Zhang, Jun Wang"
venue: "Under Review"
---
We introduce an end-to-end hierarchical reinforcement learning method utilizes a task-oriented learnable retriever and a motion controller. The retriever searches motion experts from a user-specified database in a task-oriented fashion, improving the effectiveness of manipulation. The selected motion experts and the manipulation signal are then transferred to the motion controller for simulated motion generation. This hierarchical cooperative system further boosts the responsiveness to the user’s control of locomotion. In addition, a retrieval-augmented discriminator leverages the retrieval module to provide a more robust motion prior reward for both policies, enhancing the realism of the animation. 