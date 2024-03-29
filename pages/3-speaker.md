---
layout: page
title: Keynote Speakers
permalink: /speakers/
feature-img: "assets/img/pexels/computer.jpeg"
---


# Keynote Speakers
+ [Julia Hockenmaier](#julia_hockenmaier) (UIUC)
+ [Mirella Lapata](#mirella_lapata) (University of Edinburgh)
+ [Percy Liang](#percy_liang) (Stanford; Microsoft Semantic Machines)
+ [Eran Yahav](#eran_yahav) (Technion, Israel)
+ [Charles Sutton](#charles_sutton) (University of Edinburgh)
+ [Stefanie Tellex](#stefanie_tellex) (Brown University)
+ [Lin Tan](#lin_tan) (Purdue University)
+ [Brad Myers](#brad_myers) (Carnegie Mellon University)

<br>

# Speaker Details

<a name="julia_hockenmaier"></a>
<img align="left" src="../assets/img/speakers/Julia_Hockenmaier.jpg" width="400px"> [Julia Hockenmaier](http://juliahmr.cs.illinois.edu/) (UIUC)

**Talk**: _Collaborative Construction and Communication with Minecraft_<br>
Virtual gaming platforms such as Minecraft allow us to study situated natural language generation and understanding tasks for agents that operate in complex 3D environments. In this talk, I will present a collaborative Blocks World construction task, where one player (the Architect) needs to instruct another (the Builder) via a chat interface to construct a given target structure that only the Architect is shown. Although humans easily complete this task (often after lengthy back-and-forth dialogue), creating agents for each of these roles poses a number of challenges for current NLP technologies. Probably of most relevance to the topic of this workshop is the role of the Builder, which requires the ability to generate sequences of executable code that are appropriate in the current game and dialogue context, and I will describe and demonstrate a neural model for this task. This talk is based on joint work with Anjali Narayan-Chen, Prashant Jayannavar, Harsha Kokel, Mayukh Das, Rakib Islam, Julia Bonn, Jon Cai, Susan Brown, Soham Dan, Jana Doppa, Sriraam Natarajan, Martha Palmer, and Dan Roth. 

**Bio**: Julia Hockenmaier is an associate professor in Computer Science at the University of Illinois at Urbana-Champaign. She has received a CAREER award for her work on CCG-based grammar induction and an IJCAI-JAIR Best Paper Prize for her work on image description. She has served as member and chair of the NAACL board, president of SIGNLL, and as program chair of CoNLL 2013 and EMNLP 2018.

<br />
<br />
<br />
<br />


<a name="mirella_lapata"></a>
<img align="left" src="../assets/img/speakers/mirella_lapata.jpeg" width="400px"> [Mirella Lapata](https://homepages.inf.ed.ac.uk/mlap/) (University of Edinburgh)

**Talk**: _The Democratization of Semantic Parsing via Zero-Shot Cross-lingual Learning_<br>
Semantic parsing is the task of mapping natural language utterances to machine-interpretable expressions such as SQL or a logical meaning representation. It has emerged as a key technology for developing natural language interfaces, especially in the context of question answering where a semantically complex question is mapped to an executable query to retrieve an answer, or denotation.

Datasets for semantic parsing scarcely consider languages other than English and professional translation can be prohibitively expensive. Recent work has successfully applied machine translation to localize parsers to new languages. However, high-quality machine translation is less viable for lower resource languages, and can introduce performance limiting artifacts, struggling to accurately model native speakers.

In this talk we view cross-lingual semantic parsing as a zero-shot learning problem.  We propose a multi-task encoder-decoder model to transfer parsing knowledge to additional languages using only English-Logical form paired data and unlabeled, mono-lingual utterances in each target language. Our encoder learns
language-agnostic representations and is jointly optimized for generating logical forms or utterance reconstruction and against language discriminability.  We frame zero-shot parsing as a latent-space alignment problem and find that pre-trained models can be improved to generate logical forms with minimal cross-lingual transfer penalty.  Our parser performs above back-translation baselines and, in some cases, approaches the supervised upper bound.

**Bio**: Mirella Lapata is professor of natural language processing in the  School of Informatics at the University of Edinburgh. Her research
 focuses on getting computers to understand, reason with, and generate natural language. She is the first recipient (2009) of the British
 Computer Society and Information Retrieval Specialist Group (BCS/IRSG)  Karen Sparck Jones award and a Fellow of the Royal Society of
 Edinburgh. She has also received best paper awards in leading NLP  conferences and has served on the editorial boards of the Journal of
 Artificial Intelligence Research, the Transactions of the ACL, and Computational Linguistics. She was president of SIGDAT (the group that
 organizes EMNLP) in 2018.

<br />
<br />



<a name="percy_liang"></a>
<img align="left" src="../assets/img/speakers/percy_liang.jpeg" width="400px" style="vertical-align:middle;margin:0px 0px"> [Percy Liang](https://cs.stanford.edu/~pliang/) (Stanford; Microsoft Semantic Machines)

**Talk**: _Learning to Fix Programs_<br>
A huge amount of time is spent by programmers fixing broken code.  Our goal is to train neural models that can do this automatically.  I will first present DrRepair, a system that learns to edit programs based on error messages.  We leverage a large number of valid programs by artificially perturbing (and thus breaking) them.  DrRepair obtains strong results on two tasks: fixing errors made by students and pseudocode-to-code translation.  We then present a new framework, Break-It-Fix-It (BIFI), which additionally leverages unlabeled broken code to learn a model that perturbs code to generate more realistic broken code.  We show that this results in further improvements over DrRepair.  Taken together, our work suggests that one can learn a lot just from unlabeled programs and a compiler and no further manual annotations.

**Bio**:
Percy Liang is an Associate Professor of Computer Science at Stanford University (B.S. from MIT, 2004; Ph.D. from UC Berkeley, 2011).  His research spans many topics in machine learning and natural language processing, including robustness, interpretability, semantics, and reasoning.  He is also a strong proponent of reproducibility through the creation of CodaLab Worksheets.  His awards include the Presidential Early Career Award for Scientists and Engineers (2019), IJCAI Computers and Thought Award (2016), an NSF CAREER Award (2016), a Sloan Research Fellowship (2015), a Microsoft Research Faculty Fellowship (2014), and multiple paper awards at ACL, EMNLP, ICML, and COLT.


<br />
<br />



<a name="eran_yahav"></a>
<img align="left" src="../assets/img/speakers/eran_yahav.jpg" width="400px"> [Eran Yahav](http://www.cs.technion.ac.il/~yahave/) (Technion, Israel)

**Talk**: _Pair Programming with Structural Language Models_<br>
We describe two tasks that are central to "pair programming" with language models: code completion and edit completion. The goal in code completion is to generate a missing piece of code in a given program. The goal in edit completion is to predict remaining edit operations given a code snippet that has been partially edited.

We show that both of these tasks benefit from structural language models---models that leverage the syntax of programming languages to model a code snippet as a tree. Structural language models estimate the probability of the program's abstract syntax tree (AST) by decomposing it into a product of conditional probabilities over its nodes. We present a neural model that computes the conditional probability of each node by considering every AST path leading to that node. 

**Bio**: Eran Yahav is a professor at the Computer Science Department in the Technion, Israel, and the CTO of Tabnine. Prior to that, he was a research staff member at the IBM T.J. Watson Research Center (2004-2010). He received his Ph.D. from Tel Aviv University (2005) and his B.Sc. from the Technion in 1996. His research interests include program synthesis, machine learning for code, program analysis, and program verification. Eran is a recipient of the prestigious Alon Fellowship for Outstanding Young Researchers, the Andre Deloro Career Advancement Chair in Engineering, the Robin Milner Young Researcher Award, and multiple distinguished paper awards at various conferences. Eran loves long-distance running, and while he has not won any medals yet, he has suffered at least one heatstroke trying.

<br />
<br />


<a name="charles_sutton"></a>
<img align="left" src="../assets/img/speakers/charles_sutton.jpg" width="400px"> [Charles Sutton](https://homepages.inf.ed.ac.uk/csutton/) (University of Edinburgh; Google AI)

**Talk**: _Learning, Search, and Program Synthesis_<br>
Deep learning has potential to change the way that people write code, including both end users and professional software developers. One challenge in this area is program synthesis, the task of automatically writing a program from a specification of its desired behavior. Program synthesis can be considered one of the historical grand challenges of artificial intelligence, with work dating back to the 70s. I will discuss our recent work on using machine learning to guide program synthesis. This includes how to represent the specification for program synthesis tasks via the output of a set of property functions, and how to use execution information and latent variables to guide the search.

**Bio**:
Charles Sutton is a Research Scientist at Google Brain and a Reader (equivalent to Associate Professor: http://bit.ly/1W9UhqT) in Machine Learning at the University of Edinburgh. He has published over 50 papers in probabilistic machine learning and deep learning, motivated by the demands of a broad range of applications, including natural language processing (NLP), analysis of computer systems, sustainable energy, data analysis, and software engineering. His work in software engineering has won an ACM Distinguished Paper Award. His PhD is from the University of Massachusetts Amherst, and he has done postdoctoral work at the University of California Berkeley. He has served as Director of the EPSRC Centre for Doctoral Training in Data Science at the University of Edinburgh. He is a Fellow of the Alan Turing Institute, the UK’s national research institute for artificial intelligence and data science.

<br />
<br />


<a name="stefanie_tellex"></a>
<img align="left" src="../assets/img/speakers/stefanie_tellex.jpg" width="400px"> [Stefanie Tellex](https://cs.brown.edu/people/stellex/) (Brown University)

**Talk**: _Towards Complex Language in Partially Observed Environments_<br>
Robots can act as a force multiplier for people, whether a robot assisting an astronaut with a repair on the International Space
station, a UAV taking flight over our cities, or an autonomous vehicle driving through our streets. Existing approaches use action-based
representations that do not capture the goal-based meaning of a language expression and do not generalize to partially observed
environments.  The aim of my research program is to create autonomous robots that can understand complex goal-based commands and execute
those commands in partially observed, dynamic environments.  I will describe demonstrations of object-search in a POMDP setting with
information about object locations provided by language, and mapping between English and Linear Temporal Logic, enabling a robot to
understand complex natural language commands in city-scale environments.  These advances represent steps towards robots that
interpret complex natural language commands in partially observed environments using a decision theoretic framework.

**Bio**: 
Stefanie Tellex is an Associate Professor of Computer Science at Brown University.  Her group, the Humans To Robots Lab, creates robots
that seamlessly collaborate with people to meet their needs using language, gesture, and probabilistic inference, aiming to empower
every person with a collaborative robot.  She completed her Ph.D. at the MIT Media Lab in 2010, where she developed models for the meanings
of spatial prepositions and motion verbs.  Her postdoctoral work at MIT CSAIL focused on creating robots that understand natural language.
She has published at SIGIR, HRI, RSS, AAAI, IROS, ICAPs and ICMI, winning Best Student Paper at SIGIR and ICMI, Best Paper at RSS, and
an award from the CCC Blue Sky Ideas Initiative.  Her awards include being named one of IEEE Spectrum's AI's 10 to Watch in 2013, the
Richard B. Salomon Faculty Research Award at Brown University, a DARPA Young Faculty Award in 2015, a NASA Early Career Award in 2016, a 2016
Sloan Research Fellowship, and an NSF Career Award in 2017.  Her work has been featured in the press on National Public Radio, BBC, MIT
Technology Review, Wired and Wired UK, as well as the New Yorker.  She was named one of Wired UK's Women Who Changed Science In 2015 and
listed as one of MIT Technology Review's Ten Breakthrough Technologies in 2016.<br>
Website:  [http://h2r.cs.brown.edu/](http://h2r.cs.brown.edu/)

<br />
<br />



<a name="lin_tan"></a>
<img align="left" src="../assets/img/speakers/lin_tan.jpg" width="400px"> [Lin Tan](https://www.cs.purdue.edu/homes/lintan/) (Purdue University)

**Talk**: _Software Text Analytics for Finding and Fixing Software Bugs_<br>
Software contains a large amount of text, such as code comments, API documentation, identifier names, processor specifications, and user interface text. Such software text contains a rich amount of information that can be leveraged to improve and automate important software development tasks including specification mining, bug detection, and program repair. 

In this talk, I will present the history as well as our work that analyzes software text in addition to source code to detect and fix software bugs automatically. These techniques extract input constraints from software text to guide symbolic execution and other program analysis techniques to test more code and find more real-world bugs given the same time budget. In addition, we cross-check source code and the specifications extracted from software text to find inconsistency bugs in source code and software text. 

I will also describe our techniques that build neural machine translation models to learn how to fix bugs automatically. Existing models do not have software knowledge such as code context or syntaxes. I will present our code-aware deep learning techniques to fix software bugs more effectively.  These bug detection and fixing techniques combine machine learning, natural language processing, and program analysis techniques to improve software dependability. 


**Bio**:
Lin Tan is a Mary J. Elmore New Frontiers Associate Professor in the Department of Computer Science at Purdue University. Her research interests include software dependability, software text analytics, and software and AI synergy. 

Dr. Tan was a recipient of Early Career Academic Achievement Alumni Award (from the University of Illinois, Urbana-Champaign), Canada Research Chair (one of Canada's highest research honors), an Ontario Early Researcher Award, two J.P.Morgan AI Research Faculty Awards, two Facebook Research Awards, two Google Faculty Research Awards, and an IBM CAS Research Project of the Year Award.  Dr. Tan's co-authored papers have received ACM SIGSOFT Distinguished Paper Awards at ASE 2020, MSR 2018, and FSE 2016; and IEEE Micro's Top Picks in 2006. 

She served as program (co-)chair of FSE 2020 Visions & Reflections, ICSE-SMeW 2019, SOSP 2019 Scholarship, MSR 2017, ICSE-NIER 2017, and ICSME-ERA 2015. She is an associate editor of IEEE Transactions on Software Engineering (2017-present).
<br />
<br />



<a name="brad_myers"></a>
<img align="left" src="../assets/img/speakers/brad_myers.jpg" width="500px"> [Brad Myers](https://www.cs.cmu.edu/~bam/) (Carnegie Mellon University)

**Talk**: _Programming by Natural Language and Demonstration_ <br>
We have been working for the last 6 years on the Sugilite system, which combines Natural Language Programming (NLP) with Programming by Example (PBE) to enable non-programmers to create automations on their Android smartphones. Sugilite allows users to teach the phone agent new skills. For example, the user could say: "Buy me a cappuccino," and the agent might say, "I don't know how to buy a cappuccino, do you want to teach me?", and then the user can demonstrate how to use the Starbucks app to do this task. From the demonstration, Sugilite generalizes to learn how to buy all the other items on the Starbucks menu. When there are errors or ambiguities in what the user means, the user can again use a mix of Natural Language and PBE for repair. From commands to the agent like "When it is hot, buy a iced latte", Sugilite can learn new concepts, like what "hot" means to this user and which app to use to determine whether it is hot. Concepts can be generalized for monitoring and controlling IoT devices, such as "When the oven is hot...", which requires using the oven's app and a different value for the temperature of what counts as "hot". This talk will summarize the NLP aspects of what we learned from developing Sugilite, which was the basis for Tobi Li's PhD dissertation.

**Bio**:
Brad A. Myers is a Professor in the Human-Computer Interaction Institute in the School of Computer Science at Carnegie Mellon University. He was chosen to receive the ACM SIGCHI Lifetime Achievement Award in Research in 2017, for outstanding fundamental and influential research contributions to the study of human-computer interaction. He is an IEEE Fellow, ACM Fellow, member of the CHI Academy, and winner of 17 Best Paper type awards and 5 Most Influential Paper Awards. He is the author or editor of over 525 publications, including the books "Creating User Interfaces by Demonstration" and "Languages for Developing User Interfaces," and he has been on the editorial board of six journals. He has been a consultant on user interface design and implementation to over 90 companies, and regularly teaches courses on user interface design and software. Myers received a PhD in computer science at the University of Toronto where he developed the Peridot user interface tool. He received the MS and BSc degrees from the Massachusetts Institute of Technology during which time he was a research intern at Xerox PARC. From 1980 until 1983, he worked at PERQ Systems Corporation. His research interests include user interfaces, programming environments, programming language design, end-user software engineering (EUSE), API usability, developer experience (DevX or DX), interaction techniques, programming by example, mobile computing, and visual programming. He belongs to ACM, SIGCHI, IEEE, and the IEEE Computer Society.

<br />
<br />

