---
layout: main
title: Home
order: 1
collection: pages_2019
---

## Overview

<p style="margin-bottom:1cm;"> Knowledge graphs (KGs) have demonstrated remarkable effectiveness for addressing various knowledge-intensive computational tasks in a range of domains, including journalism and the sciences.  Most work on the automatic construction of KGs has focused narrowly on extracting factual assertions from source material, ignoring an important dimension--argumentation.  Many domains communicating factual knowledge also have an argumentative dimension.  Arguments are an essential means for forming stances on controversial topics, arriving at successful decisions in the face of uncertainty, and establishing consensus on problems that require interpretation.  This inaugural workshop on Argumentation Knowledge Graphs (ArgKG) will explore the automatic construction of KGs that encode argumentative structure and the incorporation of argumentation into factual knowledge graphs, drawing together researchers focusing on automatic KG construction and computational treatments of argumentation.</p>

## Topics of Interest

We encourage submissions (but not limited) related to:

- Argumentation knowledge graph construction and evaluation
- Argumentation knowledge graph schema design in various domains
- Application of argumentation knowledge graphs in different tasks, such as legal case analysis, student essay assessment, argument relation classification, counter-argument generation
- Systems and toolkits, demonstration of the existing argumentation knowledge graphs
- Argumentation knowledge graph and common sense reasoning
- .....
- .....


## Article Contributions

We invite the submission of papers and abstracts describing previously unpublished research, including new methodology, datasets, evaluations, surveys, reproduced results, negative results, and visionary positions.

<b>Full Papers:</b>

Papers should be restricted to 10 single-column pages, excluding references. Appendices should be put after references and submitted in one PDF document.  We also encourage authors to upload their code and data (<=100 Mb) as part of their supplementary material in order to help reviewers assess the quality of the work. Like submissions, supplementary material must be anonymized. 

Archival/Non-archival papers:  Authors of accepted papers will have the option for their paper to be archival (with full text in ArgKG Proceedings to be indexed in XXXX) or non-archival (listed in AKBC Conference schedule, with full text in OpenReview, and the flexibility to also submit elsewhere).  For more on non-archival proceedings, this <a href="https://academia.stackexchange.com/questions/138797/what-exactly-is-a-non-Archival-venue-and-workshop-with-proceedings">post</a> might be helpful.

<b>Extended Abstracts:</b>

We welcome submissions of short abstracts (2 page max) related to the above research areas.  Submissions may include previously published results, late-breaking results, and work in progress. Extended abstracts can summarize existing work or work in progress or summarize a collection of works under a unified theme (e.g., a series of closely-related papers that build on each other or tackle a common problem). Abstracts will be lightly reviewed to ensure that the topic is within the scope of the workshop. These abstracts are non-archival, so participants are free to also submit their work for publication elsewhere. Figures and tables will count toward the length limit. References will not count toward the length limit. All accepted abstracts (and their videos) will be made available online prior to the workshop and remain accessible afterwards.

## Important Dates

- Call for Papers: July 6, 2021
- Paper/Abstract Submission Deadline: August 31, 2021
- Notification of workshop paper/abstract acceptance: September 22, 2021
- Camera-ready Submission Deadline: September 30, 2021
- Workshop: October 7, 2021  

## Submission Information

- All submissions must be formatted with LaTeX using the following LaTeX source: <a href="https://github.com/akbc-conference/style-files/blob/master/akbc-latex.zip?raw=true">akbc-latex.zip</a>. 
- Further details on submission TBA shortly.


## Registration

Workshop registration is included in [AKBC 2021 registration](https://akbc.ws/2021/registration/), along with access to the main conference (October 4-7).

## Invited Speakers

TBA

## Panel Discussion

TBA

## Tentative Schedule

The First ArgKG workshop will be held virtually on October 7, 2021 from XXXX - XXXX in Pacific Time (UTC-7).

<!--
<div id="schedule">
    <ul>
        <li>
            8:25-8:30 - Opening remarks
        </li>
        <li>
            8:30-9:00 - Invited talk: <a href="https://users.cs.northwestern.edu/~forbus/">Kenneth Forbus</a> -- <b>Analogy and the Construction of more Human-like Knowledge Bases</b> <button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#ken-card" aria-expanded="false" aria-controls="ken-card">Abstract</button><a href="https://www.youtube.com/watch?v=V4nbWiPdnTE" class="btn btn-outline-info btn-xs">Video</a>
            <div class="collapse" id="ken-card"><div class="card card-body">
            Humans remain the most capable learners and reasoners on the planet today.  This talk argues that lessons from cognitive science can be used to create AI systems that reason and learn more like people do.  I start by summarizing the Companion cognitive architecture, our structure-mapping models of analogical matching, retrieval, and generalization, and the language and visual processing Companions use to construct structured, relational representations from natural inputs.  I then describe the continuum of knowledge hypothesis, that argues one source of abstract knowledge is distillation via analogical generalization from experience, and illustrate via examples from a model of human conceptual change and work on learning by reading and on commonsense reasoning.  Analogical training for question-answering provides another illustration of the data-efficiency of analogical learning.  Finally, I close with some suggestions for the community.</div></div>
        </li>
        <li>
            9:00-9:30 - Invited talk: <a href="http://www.sc.cit-ec.uni-bielefeld.de/team/philipp-cimiano/">Philipp Cimiano</a> -- <b>Knowledge graphs for information extraction</b> <button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#philipp-card" aria-expanded="false" aria-controls="philipp-card">Abstract</button><a href="https://www.youtube.com/watch?v=V4nbWiPdnTE&t=30m16s" class="btn btn-outline-info btn-xs">Video</a>
            <div class="collapse" id="philipp-card"><div class="card card-body">
            In template-based information extraction, a template is described by a predefined set of slots that need to be filled with entities mentioned in a text. Compared to traditional relation extraction that aims at classifying binary relations involving a pair of entities only, template-based slot-filling is of higher complexity as interdependencies between slot-filler values need to be taken into account. To model these dependencies, we tackle the slot-filling task as a joint inference problem and build on factorized distributions as used in conditional random fields. These dependencies are often described by textual features only, but in some cases dependencies are of semantic nature and not directly expressed in text. To exploit this potential, we propose the incorporation of semantic dependencies extracted from knowledge graphs into an information extraction model. Dependencies are extracted from the variable bindings of queries executed over a knowledge graph and capture semantic soft constraints that are weighted as part of model training. We evaluate our approach on five distantly supervised labeled datasets extracted from Wikipedia/DBpedia and compare our approach to a most frequent entity baseline as well as a purely textual model. We show that there is an overall positive impact of integrating factual background knowledge in all datasets, yielding an improvement of up to 10 points in F1-score.</div></div>
        </li>
        <li>
            9:30-10:00 - Invited talk: <a href="https://williamleif.github.io/">Will Hamilton</a> -- <b>Meta Learning and Logical Induction on Knowledge Graphs</b> <button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#will-card" aria-expanded="false" aria-controls="will-card">Abstract</button><a href="https://www.youtube.com/watch?v=V4nbWiPdnTE&t=58m40s" class="btn btn-outline-info btn-xs">Video</a>
            <div class="collapse" id="will-card"><div class="card card-body">
            Traditional knowledge graph completion (KBC) methods focus on the setting where one has access to a single, static knowledge graph. For example, it is generally assumed that one has access to the full set of entities in the knowledge graph during training, and KBC research has predominantly focused on entity-centric, embedding-based methods (e.g., TransE). In this talk, I will discuss more challenging forms of knowledge graph completion, which involve generalizing to unseen entities, inducing logical rules, and meta-learning from multiple disjoint graphs. I will highlight new methodological directions that extend and complement traditional embedding-based techniques to handle these more complicated learning regimes.</div></div>
        </li>
        <li>
            10:00-10:15 - Break 1
        </li>
        <li>
            10:15-10:45 - Invited talk: <a href="https://researcher.watson.ibm.com/researcher/view.php?person=us-yunyaoli">Yunyao Li</a> -- <b>Building Domain-Specific Knowledge with Human in the Loop</b> <button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#yunyao-card" aria-expanded="false" aria-controls="yunyao-card">Abstract</button><a href="https://www.youtube.com/watch?v=V4nbWiPdnTE&t=90m39s" class="btn btn-outline-info btn-xs">Video</a>
            <div class="collapse" id="yunyao-card"><div class="card card-body">
            We describe the development of human-in-the-loop tools to capture the implicit knowledge in the mind of human experts to build domain-specific knowledge bases as the foundation for many AI systems. The ability to build large-scale domain-specific knowledge bases that capture and extend the implicit knowledge of human experts is the foundation for many AI systems. We use an ontology-driven approach for the creation, representation and consumption of such domain-specific knowledge bases. This approach relies on several well-known building blocks: natural language processing, entity resolution, data transformation and fusion. We will present several human-in-the-loop work  that target domain experts (rather than programmers) to extract the domain knowledge from the human expert and map it into the "right" models or algorithms. We will also share successful use cases in several domains, including Compliance, Finance, and Healthcare: by using these tools we can match the level of accuracy achieved by manual effort, but at a significantly lower cost and much higher scale and automation. If time permits, we will demonstrate a knowledge base built for the Finance domain.</div></div>
        </li>
        <li>
            10:45-11:15 - Invited talk: <a href="https://www.fabiopetroni.com/">Fabio Petroni</a> -- <b>How can we compare unstructured, structured and self-structured knowledge representation?</b> <button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#fabio-card" aria-expanded="false" aria-controls="fabio-card">Abstract</button><a href="https://www.youtube.com/watch?v=V4nbWiPdnTE&t=121m21s" class="btn btn-outline-info btn-xs">Video</a>
            <div class="collapse" id="fabio-card"><div class="card card-body">Several approaches have been proposed to represent world knowledge. It can be unstructured in text corpora, organised in structured collections (e.g, KBs, key-value memories), or self-structured in the parameters of a neural model. However, it is still unclear how to compare these different solutions. Most of the existing NLP benchmarks focus on tasks that humans can solve by just examining local information. In this talk I will review some knowledge-intensive tasks, that require to seek knowledge in a large body of documents even for humans in order to be solved. I will present some of the latest models proposed to solve those and which representation they use for knowledge. Moreover, I will present some ideas to investigate models' explainability in this setting.</div></div>
        </li>
        <li>
            11:15-11:45 - Invited talk: <a href="https://craffel.github.io/">Colin Raffel</a> -- <b>Answering Questions by Querying the Implicit Knowledge Base Inside T5</b> <button class="btn btn-outline-info btn-xs" type="button" data-toggle="collapse" data-target="#colin-card" aria-expanded="false" aria-controls="colin-card">Abstract</button><a href="https://www.youtube.com/watch?v=V4nbWiPdnTE&t=152m43s" class="btn btn-outline-info btn-xs">Video</a>
            <div class="collapse" id="colin-card"><div class="card card-body">
            It has recently been observed that language models trained on unlabeled, unstructured text corpora form a sort of implicit knowledge base. In this talk, I connect this ability to the important NLP task of question answering by introducing "closed-book question answering" (CBQA): In CBQA, a model is only provided with a natural language query and must "look up knowledge" in its parameters in order to produce the correct answer. To attack this problem, we leverage the recent T5 models that cast every text problem into a unified text-to-text format. We find that model performance scales with model size and show that T5-11B attains surprisingly strong performance on the open-domain variants of WebQuestions and TriviaQA, outperforming models that explicitly retrieve a document and extract the answer from it. We also find that existing evaluation procedures for open-domain question-answering often treat correct answers produced by our model as incorrect, suggesting that they are a poor fit for CBQA. I will conclude by outlining some strengths and weaknesses of our approach.</div></div>
        </li>
        <li>
            11:45-12:00 - Break 2
        </li>
        <li>
            12:00-12:45 - <b>Panel discussion</b><a href="https://www.youtube.com/watch?v=V4nbWiPdnTE&t=188m54s" class="btn btn-outline-info btn-xs">Video</a>
        </li>
    </ul>
    <p>Each talk is 25 min + 5 min Q&A.</p>
</div>
-->

## Program Committee

TBA

## Organizing Committee
- [Khalid Al-Khatib](https://www.uni-weimar.de/en/media/chairs/computer-science-department/webis/people/alkhatib/), Leipzig University, Germany
- [Tirthankar Ghosal](https://elitr.eu/tirthankar-ghosal/), Charles University, Czech Republic
- [Yufang Hou](https://researcher.watson.ibm.com/researcher/view.php?person=ie-YHou), IBM Research, Ireland
- [Dayne Freitag](https://www.sri.com/bios/dayne-freitag/), SRI International, US
- [Anita de Waard](https://www.linkedin.com/in/anitadewaard/), Elsevier, US

<b>Website Credits:</b> https://uskb-workshop.github.io
