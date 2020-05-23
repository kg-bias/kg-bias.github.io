---
layout: default
title: KG-BIAS 2020 – Bias in Automatic Knowledge Graph Construction
---

### Overview
Knowledge Graphs (KGs) store human knowledge about the world in structured format, e.g., triples of facts or graphs of entities and relations, to be processed by AI systems. In the past decade, extensive research efforts have gone into constructing and utilizing knowledge graphs for tasks in natural language processing, information retrieval, recommender systems, and more. Once constructed, knowledge graphs are often considered as “gold standard” data sources that safeguard the correctness of other systems. Because the biases inherent to KGs may become magnified and spread through such systems, it is crucial that we acknowledge and address various types of bias in knowledge graph construction. 

Such biases may originate in the very design of the KG, in the source data from which it is created (semi-)automatically, and in the algorithms used to sample, aggregate, and process that data.
Causes of bias include systematic errors due to selecting non-random items (selection bias), misremembering certain events (recall bias), and interpreting facts in a way that affirms individuals' preconceptions (confirmation bias). Biases typically appear subliminally in expressions, utterances, and text in general and can carry over into downstream representations such as embeddings and knowledge graphs. 

This workshop – to be held for the first time at AKBC 2020 – addresses the questions: “how do such biases originate?”, “How do we identify them?”, and “What is the appropriate way to handle them, if at all?”.  This topic is as-yet unexplored and the goal of our workshop is to start a meaningful, long-lasting dialogue spanning researchers across a wide variety of backgrounds and communities. 

### Keynote Speakers

#### Jahna Otterbacher, Open University of Cyprus

Mitigating bias in algorithmic processes and systems is a critical issue drawing increasing
attention across research communities within the information and computer sciences. Given
the complexity of the problem and the involvement of multiple stakeholders – not only
developers, but also end-users and third parties – there is a need to understand the landscape
of the sources of bias, as well as the solutions being proposed to address them. In this talk, I
present insights from a recent survey of 250+ articles across four domains (machine learning,
information retrieval, HCI, and RecSys), providing a “fish-eye view” of the field. I will also
discuss the particular challenges of data biases, given the heterogeneity of data sources
available for learning about our world, drawing on examples of my previous work on image
data.

_Jahna Otterbacher received her doctorate from the University of Michigan (Ann Arbor, USA),
School of Information. She is currently Assistant Professor at the Open University of Cyprus
(OUC), Faculty of Pure and Applied Sciences. Jahna coordinates the [Cyprus Center for
Algorithmic Transparency (CyCAT)](http://www.cycat.io/) at the OUC, funded by the H2020 Widespread Twinning
program. The CyCAT seeks to promote transparency and accountability in algorithmic systems
that people routinely use, but that are rather opaque to them (e.g., search engines), through
three types of interventions – data-, developer- and user-focused. In addition to her post at the
OUC, Jahna holds a concurrent appointment as team leader of the Transparency in Algorithms
Group at [RISE (Research centre on Interactive media, Smart systems and Emerging
technologies)](https://www.rise.org.cy/en-gb/research/research-groups/), a new center of excellence and innovation in Nicosia, Cyprus, in collaboration
with two international Advanced Partners, UCL and MPI._

#### Jieyu Zhao, University of California - Los Angeles

Natural Language Processing (NLP) plays an important role in many applications, including resume filtering, text analysis, and information retrieval. Despite the remarkable accuracy enabled by the advances in machine learning used in many applications, the technique may discover and generalize the societal biases implicit in the data. For example, an automatic resume filtering system may unconsciously select candidates based on their gender and race due to implicit associations between applicant names and job titles, causing the societal disparity discovered by researchers. Various laws and policies have been designed to ensure social equality and diversity. However, there is no such mechanism for a machine learning model for sensitive applications. My research analyzes the potential stereotypes in various machine learning models and develops computational approaches to enhance fairness in a wide range of NLP applications. The broader impact of my research aligns with one the concerns of machine learning community: how can we do AI for (social) good.

_Jieyu is a PhD candidate in the department of Computer Science at UCLA advised by Prof. Kai-Wei Chang. Her research interest lies in fairness of ML/NLP models. Their previous paper was awarded the EMNLP Best Long Paper Award (2017). More detail can be found at [her personal website](https://jyzhao.net/)._

### Topics
Topics of interest include, but are not limited to:
* Ethics, bias, and fairness
* Qualitatively and quantitatively defining types of bias
  * Implicit or explicit human bias reflected in data people generate
  * Algorithmic bias represented in learned models or rules
  * Taxonomies and categorizations of different biases
* Empirically observing biases
  * Measuring diversity of opinions
  * Language, gender, geography, or interest bias
  * Implications of existing bias to human end-users
  * Benchmarks and datasets for bias in KGs
* Measuring or remediating bias
  * De-biased KG completion methods
  * Algorithms for making inferences interpretable and explainable
  * De-biasing or post-processing algorithms 
  * Creating user awareness on cognitive biases
  * Ethics of data collection for bias management
  * Diversification of information sources
  * Provenance and traceability

### Submission Instructions
Submission files should not exceed 8 pages with additional pages allowed for references. Reviews are double-blind; author names and affiliations must be removed. All submissions must be written in English and submitted as PDF files formatted using the sigconf template: https://www.acm.org/publications/proceedings-template.

Submissions should be made electronically through <a href="https://easychair.org/conferences/?conf=kgbias2020">Easychair</a>.

### Workshop format
We accept position papers, short papers, and full papers. Both ongoing and already published work is welcomed, and we will offer authors the option of having their paper included in the workshop proceedings. More details regarding the actual format and schedule of the workshop will be announced closer to the workshop date.

### Important Dates

If you want your contribution to appear in proceedings:
* Submission deadline: ~~May 4~~ **May 11**
* Notification: May 18

If you **do not** want your contribution to appear in proceedings:
* Submission deadline: June 1
* Author feedback: June 8

AKBC Conference: June 22-23

KG-BIAS 2020 workshop: June 24 or 25

All deadlines are 11:59 PM, in the AoE (Anywhere on Earth) timezone 

### Organizing committee
* Edgar Meij, Bloomberg
* Tara Safavi, University of Michigan
* Chenyan Xiong, Microsoft Research AI
* Miriam Redi, Wikimedia Foundation
* Gianluca Demartini, University of Queensland
* Fatma Özcan, IBM Research

### Program Committee
* Guillaume Bouchard (Facebook AI)
* Soumen Chakrabarti (IIIT Bombay)
* David Corney (Full Fact)
* Jeff Dalton (University of Glasgow) 
* Maarten de Rijke (University of Amsterdam) 
* Laura Dietz (University of New Hampshire)
* Djellel Difallah (Wikimedia Foundation) 
* Ying Ding (University of Texas at Austin)
* Ujwal Gadiraju (L3S Research Center)  
* Jacopo Grazzini (Eurostat)
* Faegheh Hasibi (Radboud University)
* Lucie-Aimée Kaffee (University of Southampton and Wikidata)
* Jeff Pan (University of Aberdeen)
* Fabrizio Silvestri (Facebook AI)
* Emine Yilmaz (University College London)

### Code of Conduct
Our workshop adheres to all principles and guidelines specified in the <a href="https://www.acm.org/code-of-ethics" target="_blank">ACM Code of Ethics and Professional Conduct</a>.

### Contact information 
You can find us at <a href="https://kg-bias.github.io/">https://kg-bias.github.io</a> and contact us at <a href="mailto:kg-bias@googlegroups.com">kg-bias@googlegroups.com</a>.
