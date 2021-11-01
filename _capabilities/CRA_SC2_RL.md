---
title: "Causal Models to Explain Machine Learning Systems in StarCraft2"
excerpt: "A framework for distributed RL Training and human-machine-teaming in StarCraf2"
tags: # Select from this set
  - Autonomy
  - Reinforcement Learning
  - Human-Machine Teaming
  - Distruted Systems
   
submission_details:
  resources: # List any resources associated with the contribution. Not all sections are required
    papers:
      - title: Paper link text
        url: Paper link url
    software:
      - title: Software link text
        url: Software link url
      - title: Another software link text
        url: Another software link url
    demos:
      - title: Demo link text
        url: Demo link url
    data:
      - title: Data link text
        url: Data link url
   
  # Optional information describing artifact. Leave blank if unused
  version: Version Number
  size: Size
  license: Link to license
   
  authors:
    - Jeff Druce
    # Optional for multiple authors and organizations
    - Joseph Campolongo <sup>1</sup>
    - Michael Harredon <sup>1</sup>
    - Vanessa Moody <sup>1</sup>
  organizations:
    - Charles River Analytics
    # Optional for multiple authors and organizations
    - 1. Organization
  point_of_contact:
    name: PoC Name
    email: email
---
   
## Overview
[comment]: <> (What is the main purpose of the contribution?)
The main purpose of this contribution is to provide a framework for: 1) distributed RL training in StarCraf2; and 2) playing alongside an RL agent. Concerning 
1), Distributed RL training paradigms (e.g., IMPALA) are important as the allow for simulatneously gathering experience in multiple episode. E.g., in our framework we support 
spinning up multiple StarCraft2 instances which can concurrently gather experience used to update control policied in a central learner. In 2), in critical 
scenarios, it is often important to have humans in-the-loop to assist AIs, and possibly interven if necessary. To offer a human machine teaming (HMT) scenario
to support testing of humans working alongside an advanced deep reinforment learning-based agent. 
   
## Intended Use
[comment]: <> (What is the intended use case for this contribution?)
The intended use case of this contribution is the training and testing of RL agents in our provided custom StarCraft2 maps. The framework supports other
enviornments, but is currently configured for StarCraft2. Many of the well-known Google Deep Mind "mini games" are built in as well for testing. 

[comment]: <> (What domains/applications has this contribution been applied to?)
This contribution has been applied to a variety of StarCraft 2 games, and Open AI gym Atari games. 
   
## Model/Data
[comment]: <> (If a model is involved, what are its inputs and outputs?)

[comment]: <> (If the model was learned/trained, what data was used for training/testing?)
   
## Limitations
[comment]: <> (Are there any additional limitations/ethical considerations for use of this contribution?)
   
[comment]: <> (Are there known failure modes?)
   
## References
[comment]: <> (Any additional information, e.g. papers \(cited with bibtex\) related to this contribution.)
