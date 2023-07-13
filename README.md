# Framework (Working Version)
The working version of SAOFAI (Secure Adoption and Operation Framework for Artificial Intelligence).

## Overview

### Summary
SAOFAI is a community-driven standard that provides [guidelines](#guidelines) and [controls](#controls) for [entities](#entity) (i.e., individuals and organizations) to minimize [risks](#risk) and maximize the [value](#value) of using [Artificial Intelligence (AI)](#artificial-intelligence-ai) in their [operations](#operations). It is open-source, developed by an international, interdisciplinary community of experts through a democratic process. All changes are transparent, discussed, and voted on by the community to mitigate the effects of subjective biases and incentives.

### Audience
The target audience of SAOFAI includes individuals and organizations aiming to automate their [operations](#operations) with [AI](#artificial-intelligence-ai). These [entities](#entity) thus face the dual challenges of, firstly, [adopting](#adoption) and, secondly, [operating](#operation) their processes supported by [AI](#artificial-intelligence-ai).

### Objective
The primary objective of SAOFAI is to minimize the operational, strategic, compliance, reputational, and cybersecurity [risks](#risk) associated with the [adoption](#adoption) and [operation](#operation) of [AI](#artificial-intelligence-ai). The secondary objective is to maximize [value](#value) by reducing costs and increasing benefits derived from [AI](#artificial-intelligence-ai).

### Structure
First, the document [defines](#definitions) all notions used in the [main part](#integration-models). The main part presents blueprints for different integration models resulting in [processes](#process) integrated with [AI](#artificial-intelligence-ai), designed to serve as flexible baselines that can be adapted to a specific [entity’s](#entity) needs. Each integration model is divided into three parts - Adoption, Operation, and Case Study.

### Contributions
Contributions to the projects are done via the [Pull Requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request). After a new PR is created, the community (contributors listed in the [Contributors](https://github.com/SAOFAI/Framework#contributors) chapter) vote on it. Once at least have of them [approves the change](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/reviewing-proposed-changes-in-a-pull-request), the change is merged to the `main` branch.

## Definitions

*[WIP]*

### Guidelines

SAOFAI establishes *guidelines* for various approaches to adopting and operating AI within a focal entity.

### Control

A *control* is a quantifiable metric, or a KPI (key performance indicator), of a specific area of interest. SAOFAI defines controls along with every guideline, to help measuring its implementation in the focal entity.

### Entity

An *entity* is an individual or an organization that operates using [processes](#process) and interacts with the [environment](#environment). To differentiate from other entities operating in the environment, the entity implementing SAOFAI is referred to as the *focal entity*.

![Figure](Figures/EntityDefinition.png)

### Risk

*[WIP]*

### Value

*[WIP]*

### Artificial Intelligence (AI)

![Figure](Figures/AIDefinition.png)

Drawing upon the definition by Russel (Russel 2010), SAOFAI defines AI as an [IT system](#it-system) that contains an [AI model](#ai-model) which solves a [domain problem](#domain-problem). Application provides an interface to a user ([human agent](#human-agent)), via which the user can formulate the formulate the problem. Then, the [application](#application) translates it to the input understandable by the [AI model](#ai-model), and translates an inference produced by the model back to the user via the interface.

Since [AI models](#ai-model) can only learn how to solve [domain problems](#domain-problem), [training data](#training-data) is an integral part of the AI system. In order to teach the model, an [operator](#operator) provides [training data](#training-data) and performs training activities.

### Domain Problem

*[WIP]*

### (Human) Agent

*[WIP]*

### Operator

*[WIP]*

### IT System

*[WIP]*

### Application

*[WIP]*

### AI Model

Drawing upon the definition by Russel (Russel 2010), SAOFAI defines an AI model as a [subsystem](#it-system) of an [AI system](#artificial-intelligence-ai) that transforms inputs ([real data](#real-data)) into outputs ([inference](#inference)) by extrapolating patterns found in [training data](#training-data). In this view, the behavior of the model is a derivative of its configuration and the training data, and can only be changed by retraining with different variations of those.

![Figure](Figures/AIModelDefinition.png)

As suggested by Arrieta (Arrieta 2020), there are two categories of AI models which represent opposite polars of the spectrum:

- **black-box models** whose inference logic is hardly understandable to an external observer (i.e., a [human agent](#human-agent)),
- **explainable models** which "enable humans to understand, appropriately trust, and effectively manage the emerging generation of artificially intelligent partners" (Arrieta 2020).

### Training Data

*[WIP]*

### Real Data

*[WIP]*

### Inference

*[WIP]*

### Operations

*[WIP]*

### Process

A process is a set of related activities that are performed by an agent (human or non-human) who has specific [capabilities] to change states of the activities (Howard 2003). See the [baseline integration model](#baseline) as an example.

### Capability

*[WIP]*

### Environment

An environment consists of a variety of [entities](#entity) that interact with the *focal entity* and each other, and in result have direct impact on [risks](#risk) and [values](#value) in the ecosystem.

## Integration models

*[WIP]*

### Baseline

#### Operation

As a baseline, the focal entity is expected to operate with processes that consist of non-AI agents who have certain capabilities to work on activities.

![Figure](Figures/OperationsBaseline.png)

Following sections describe strategies of operating the baseline process with AI, identified by SAOFAI.

#### Adoption

*[WIP]*

#### Case study

*[WIP]*

### AI-supported Activity

#### Operation

*[WIP]*

#### Adoption

*[WIP]*

#### Case study

*[WIP]*

### AI-supported Agent

#### Operation

*[WIP]*

#### Adoption

*[WIP]*

#### Case study

*[WIP]*

### AI Agent

#### Operation

*[WIP]*

#### Adoption

*[WIP]*

#### Case study

*[WIP]*

## Contributors

*[WIP]*

## References

- Arrieta, Alejandro Barredo, Natalia Díaz-Rodríguez, Javier Del Ser, Adrien Bennetot, Siham Tabik, Alberto Barbado, Salvador García et al. "Explainable Artificial Intelligence (XAI): Concepts, taxonomies, opportunities and challenges toward responsible AI." Information fusion 58 (2020): 82-115.
- Russell, Stuart J. Artificial intelligence a modern approach. Pearson Education, Inc., 2010.
- Smith, Howard. "Business process management—the third wave: business process modelling language (bpml) and its pi-calculus foundations." Information and Software Technology 45, no. 15 (2003): 1065-1069.
