# Open Information Extraction (OIE) Resources

A curated list of Open Information Extraction (OIE) resources: research papers, code, data, applications, etc. The list is not limited to Open Information Extraction systems exclusively. It also includes work highly related to OIE, such as taxonomizing open relations and using OIE in downstream applications. 

## Table of contents

* [Introduction to OIE](#introduction-to-oie)
* [Papers sorted in chronological order](#papers-sorted-in-chronological-order)
  * [2006](#2006)
  * [2007](#2007)
  * [2008](#2008)
  * [2009](#2009)
  * [2010](#2010)
  * [2011](#2011)
  * [2012](#2012)
  * [2013](#2013)
  * [2014](#2014)
  * [2015](#2015)
  * [2016](#2016)
  * [2017](#2017)
  * [2018](#2018)
  * [2019](#2019)
  * [2020](#2020)
  * [2021](#2021)
  * [2022](#2022)
* [Papers grouped by category](#papers-grouped-by-category)
  * [Surveys](#surveys)
  * [Evaluation](#evaluation)
  * [OIE for downstream applications](#oie-for-downstream-applications)
    * [Question Answering](#question-answering)
    * [Slot Filling](#slot-filling)
    * [Event Extraction](#event-extraction)
    * [Text Summarization](#text-summarization)
    * [Knowledge Base Population](#knowledge-base-population)
    * [Knowledge Base Construction](#knowledge-base-construction)
    * [Entity Linking](#entity-linking)
    * [Relation Linking](#relation-linking)
    * [Open Link Prediction](#open-link-prediction)
    * [Relating Entities](#relating-entities)
    * [Video Grounding](#video-grounding)
  * [OIE in Different Languages](#oie-in-different-languages)
    * [OIE Systems for German Language](#oie-systems-for-german-language)
    * [OIE Systems for Portugese Language](#oie-systems-for-portugese-language)
    * [OIE Systems for Spanish Language](#oie-systems-for-spanish-language)
    * [OIE Systems for Chinese Language](#oie-systems-for-chinese-language)
    * [OIE Systems for Persian Language](#oie-systems-for-persian-language)
    * [OIE Systems for Italian Language](#oie-systems-for-italian-language)
    * [OIE Systems for Indonesian Language](#oie-systems-for-indonesian-language)
    * [OIE Systems for Greek Language](#oie-systems-for-greek-language)
  * [Supervised OIE](#supervised-oie)
  * [Canonicalization of OIE](#canonicalization-of-oie)
* [Slides](#slides)
* [Talks](#talks)
* [Code](#code)
* [Data](#data)
  * [OIE corpora](#oie-corpora)
  * [Resources derived from OIE output](#resources-derived-from-oie-output)
* [PhD theses](#phd-theses)
* [Demos](#demos)

## Introduction to OIE

Open Information Extraction (OIE) systems aim to extract unseen relations and their arguments from unstructured text in unsupervised manner. In its simplest form, given a natural language sentence, they extract information in the form of a triple, consisted of subject (S), relation (R) and object (O).

Suppose we have the following input sentence:

    AMD, which is based in U.S., is a technology company.

An OIE system aims to make the following extractions:

    ("AMD"; "is based in"; "U.S.")
    ("AMD"; "is"; "technology company")

## Papers sorted in chronological order

### 2006

* *["Machine Reading"](https://www.aaai.org/Papers/Symposia/Spring/2007/SS-07-06/SS07-06-001.pdf)* - AAAI 2006

  Oren Etzioni, Michele Banko, Michael J. Cafarella

### 2007
* *["Open Information Extraction from the Web"](https://www.aaai.org/Papers/IJCAI/2007/IJCAI07-429.pdf)* - IJCAI 2007
  
  Michele Banko,  Michael J. Cafarella, Stephen Soderland, Matthew Broadhead, Oren Etzioni
  
* *["Unsupervised Resolution of Objects and Relations on the Web"](http://turing.cs.washington.edu/papers/object_identification_camera_ready_4.pdf)* - NAACL 2007

  Alexander Yates, Oren Etzioni
  
* *["TextRunner: Open Information Extraction on the Web"](https://tianjun.me/static/essay_resources/RelationExtraction/Paper/p25-yates.pdf)* -  HLT-NAACL 2007

  Alexander Yates, Michele Banko, Matthew Broadhead, Michael J. Cafarella, Oren Etzioni, Stephen Soderland
  
### 2008
* *["The Tradeoffs between Open and Traditional Relation Extraction"](http://turing.cs.washington.edu/papers/acl08.pdf)* - ACL 2008

  Michele Banko, Oren Etzioni

* *["Open Knowledge Extraction through Compositional Language Processing"](https://www.cs.rochester.edu/~schubert/papers/open-knowledge-step08.pdf)* - STEP 2008

  Benjamin Van Durme, Lenhart K. Schubert

* *["Open Information Extraction from the Web"](https://dl.acm.org/citation.cfm?id=1409378)* - Commun. ACM 2008

  Oren Etzioni, Michele Banko, Stephen Soderland, Daniel S. Weld
  
### 2009

* *["Using Wikipedia to Bootstrap Open Information Extraction"](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.143.4369&rep=rep1&type=pdf)* - SIGMOD 2009
  	
    Daniel S. Weld, Raphael Hoffmann, Fei Wu
    
### 2010

* *["Open Information Extraction Using Wikipedia"](http://www.aclweb.org/anthology/P10-1013)* - ACL 2010

  Fei Wu, Daniel S. Weld
  
* *["Identifying Functional Relations in Web Text"](https://homes.cs.washington.edu/~mausam/papers/emnlp10.pdf)* - EMNLP 2010
  
  Thomas Lin, Mausam, Oren Etzioni

* *["Adapting Open Information Extraction to Domain-Specific Relations"](https://www.aaai.org/ojs/index.php/aimagazine/article/view/2305)* -  AI Magazine (31), 2010

  Stephen Soderland, Brendan Roof, Bo Qin, Shi Xu, Mausam, Oren Etzioni 
  
### 2011

* *["Open Information Extraction: The Second Generation"](http://turing.cs.washington.edu/papers/etzioni-ijcai2011.pdf)* -  IJCAI 2011 ([slides](http://www.cse.iitd.ac.in/~mausam/courses/col864/spring2017/slides/03-openie.pdf))
  
  Oren Etzioni, Anthony Fader, Janara Christensen, Stephen Soderland, Mausam
  
* *["Identifying Relations for Open Information Extraction"](http://www.aclweb.org/anthology/D11-1142)* - EMNLP 2011 [(resources (code, data)](http://reverb.cs.washington.edu/))

  Anthony Fader, Stephen Soderland, Oren Etzioni
  
* *["Filtering and Clustering Relations for Unsupervised Information Extraction in Open Domain"](https://perso.limsi.fr/bg/fichiers/2011/cikm0874-wang.pdf)* - CIKM 2011

  Wei Wang, Romaric Besançon, Olivier Ferret, Brigitte Grau

* *["An Analysis of Open Information Extraction based on Semantic Role Labeling"](https://homes.cs.washington.edu/~mausam/papers/kcap11.pdf)* - K-CAP 2011

  Janara Christensen, Mausam, Stephen Soderland, Oren Etzioni

### 2012

* *["Open Language Learning for Information Extraction"](https://www.aclweb.org/anthology/D12-1048)* - EMNLP-CoNLL 2012 ([resources (code, data, binaries)](http://knowitall.github.io/ollie/))

  Mausam, Michael Schmitz, Stephen Soderland, Robert Bart, Oren Etzioni
  
* *["PATTY: A Taxonomy of Relational Patterns with Semantic Types"](http://www.aclweb.org/anthology/D12-1104)* - EMNLP-CoNLL 2012

  Ndapandula Nakashole, Gerhard Weikum, Fabian M. Suchanek
  
* *["Ensemble Semantics for Large-scale Unsupervised Relation Extraction"](https://www.aclweb.org/anthology/D12-1094)* - EMNLP-CoNLL 2012

  Bonan Min, Shuming Shi, Ralph Grishman, Chin-Yew Lin
  
* *["WiSeNet: building a wikipedia-based semantic network with ontologized relations"](http://wwwusers.di.uniroma1.it/~moro/MoroNavigli_CIKM12.pdf)* - CIKM 2012 ([resources](http://lcl.uniroma1.it/wisenet/))

  Andrea Moro, Roberto Navigli
  
* *["Open Information Extraction for SOV Language Based on Entity-Predicate Pair Detection"](http://aclweb.org/anthology/C12-3038)* -  COLING 2012

  Woong-Ki Lee, Yeon-Su Lee, Hyoung-Gyu Lee, Won-Ho Ryu, Hae-Chang Rim
  
* *["A Weighting Scheme for Open Information Extraction"](http://www.aclweb.org/anthology/N12-2011)* - HLT-NAACL 2012

  Yuval Merhav

* *["Dependency-based open information extraction"](http://www.anthology.aclweb.org/W/W12/W12-0702.pdf)* - Joint Workshop on Unsupervised and Semi-Supervised Learning in NLP @ ACL 2012

  Pablo Gamallo, Marcos Garcia
  
* *["KrakeN: N-ary Facts in Open Information Extraction"](http://wing.comp.nus.edu.sg/~antho/W/W12/W12-3010.pdf)* - AKBC-WEKEX@NAACL-HLT 2012

  Alan Akbik, Alexander Löser
  
* *["Improving Open Information Extraction for Informal Web Documents with Ripple-Down Rules"](https://link.springer.com/chapter/10.1007/978-3-642-32541-0_14)* - PKAW 2012

  Myung Hee Kim, Paul Compton
  
### 2013

* *["ClausIE: clause-based open information extraction"](http://resources.mpi-inf.mpg.de/d5/clausie/clausie-www13.pdf)* - WWW 2013 ([slides](https://people.mpi-inf.mpg.de/~corrogg/publications/delcorro13clausie-slides.pdf), [code](http://resources.mpi-inf.mpg.de/d5/clausie/clausie-0-0-1.zip), [all resources](https://www.mpi-inf.mpg.de/departments/databases-and-information-systems/software/clausie/))

  Luciano Del Corro, Rainer Gemulla
  
* *["Integrating Syntactic and Semantic Analysis into the Open Information Extraction Paradigm"](http://wwwusers.di.uniroma1.it/~moro/MoroNavigli_IJCAI13.pdf)* - IJCAI 2013 ([resources](http://lcl.uniroma1.it/wisenet/))

  Andrea Moro, Roberto Navigli

* *["Effectiveness and Efficiency of Open Relation Extraction"](http://www.aclweb.org/anthology/D13-1043)* - EMNLP 2013 ([code](https://github.com/U-Alberta/exemplar))

  Filipe de Sá Mesquita, Jordan Schmidek, Denilson Barbosa
  
* *["Open Information Extraction with Tree Kernels"](http://www.aclweb.org/anthology/N13-1107)* - HLT-NAACL 2013
 
  Ying Xu, Mi-Young Kim, Kevin Quinn, Randy Goebel, Denilson Barbosa
  
* *["Relation Extraction with Matrix Factorization and Universal Schemas"](http://www.aclweb.org/anthology/N13-1008)* -  HLT-NAACL 2013 

  Sebastian Riedel, Limin Yao, Andrew McCallum, Benjamin M. Marlin
  
* *["Open Information Extraction via Contextual Sentence Decomposition"](http://ad-publications.cs.uni-freiburg.de/ICSC_csdie_BH_2013.pdf)* - ICSC 2013
  
  Hannah Bast, Elmar Haussmann
  
* *["Integrating Open and Closed Information Extraction: Challenges and First Steps"](http://ceur-ws.org/Vol-1064/Dutta_Integrating.pdf)* - NLP-DBPEDIA@ISWC 2013

  Arnab Dutta, Christian Meilicke, Mathias Niepert, Simone Paolo Ponzetto
  
* *["Open Information Extraction to KBP Relations in 3 Hours"](https://pdfs.semanticscholar.org/d431/81fa9af5440360d4055e1ce7ddaaa6e82d77.pdf)* - TAC 2013

  Stephen Soderland, John Gilmer, Robert Bart, Oren Etzioni, Daniel S. Weld
  
### 2014

* *["ReNoun: Fact Extraction for Nominal Attributes"](http://emnlp2014.org/papers/pdf/EMNLP2014038.pdf)* - EMNLP 2014
  	
  Mohamed Yahya, Steven Whang, Rahul Gupta, Alon Y. Halevy
    
* *["ZORE: A Syntax-based System for Chinese Open Relation Extraction"](http://aclweb.org/anthology/D14-1201)* - EMNLP 2014

  Likun Qiu, Yue Zhang
  
* *["Canonicalizing Open Knowledge Bases"](https://suchanek.name/work/publications/cikm2014.pdf)* - CIKM 2014

  Luis Galárraga, Geremy Heitz, Kevin Murphy, Fabian M. Suchanek
  
* *["Focused Entailment Graphs for Open IE Propositions"](https://www.aclweb.org/anthology/W14-1610)* - CoNLL 2014

  Omer Levy, Ido Dagan, Jacob Goldberger

* *["Boosting Open Information Extraction with Noun-Based Relations"](https://pdfs.semanticscholar.org/570c/ce7b24c51f75da091b515baddce567128680.pdf)* - LREC 2014

  Clarissa Castellã Xavier, Vera Lúcia Strube de Lima

* *["Improving Open Relation Extraction via Sentence Re-Structuring"](http://www.lrec-conf.org/proceedings/lrec2014/pdf/1038_Paper.pdf)* - LREC 2014

  Jordan Schmidek, Denilson Barbosa

* *["More Informative Open Information Extraction via Simple Inference"](http://ad-publications.informatik.uni-freiburg.de/ECIR_csdie-inf_BH_2014.pdf)* - ECIR 2014

  Hannah Bast, Elmar Haussmann
  
* *["Semantifying Triples from Open Information Extraction Systems"](https://ub-madoc.bib.uni-mannheim.de/36881/1/FAIA264-0111.pdf)* - STAIRS 2014

  Arnab Dutta, Christian Meilicke, Heiner Stuckenschmidt

* *["Entity-Centric Coreference Resolution of Person Entities for Open Information Extraction"](http://www.taln.upf.edu/pages/sepln2014/full_papers/edited_paper_30.pdf)* - Procesamiento del Lenguaje Natural (2014)

  Marcos García, Pablo Gamallo
  
* *["Open Information Extraction for Spanish Language based on Syntactic Constraints"](https://www.aclweb.org/anthology/P14-3011.pdf)* - ACL (Student Research Workshop) (2014)

  Alisa Zhila, Alexander Gelbukh
  
### 2015

* *["Leveraging Linguistic Structure For Open Domain Information Extraction"](https://nlp.stanford.edu/pubs/2015angeli-openie.pdf)* - ACL 2015 ([code (Java)](https://stanfordnlp.github.io/CoreNLP/openie.html), [code (Python)](https://github.com/philipperemy/Stanford-OpenIE-Python))

  Gabor Angeli, Melvin Jose Johnson Premkumar, Christopher D. Manning

* *["Open IE as an Intermediate Structure for Semantic Tasks"](http://www.aclweb.org/anthology/P15-2050)* - ACL 2015

  Gabriel Stanovsky, Ido Dagan, Mausam
  
* *["Large-Scale Information Extraction from Textual Definitions through Deep Syntactic and Semantic Analysis"](https://transacl.org/ojs/index.php/tacl/article/view/660)* - TACL 2015 ([resources](http://lcl.uniroma1.it/defie/))

  Claudio Delli Bovi, Luca Telesca, Roberto Navigli
  
* *["Inferring Binary Relation Schemas for Open Information Extraction"](http://www.aclweb.org/anthology/D15-1065)* - EMNLP 2015

  Kangqi Luo, Xusheng Luo, Kenny Qili Zhu
  
* *["Knowledge Base Unification via Sense Embeddings and Disambiguation"](http://aclweb.org/anthology/D15-1084)* - EMNLP 2015 ([resources](http://lcl.uniroma1.it/kb-unify/))

  Claudio Delli Bovi, Luis Espinosa Anke, Roberto Navigli
  
* *["CORE: Context-Aware Open Relation Extraction with Factorization Machines"](https://www.aclweb.org/anthology/D15-1204)* - EMNLP 2015 ([code](https://github.com/fabiopetroni/CORE))

  Fabio Petroni, Luciano Del Corro, Rainer Gemulla
  
* [*"Multilingual Open Relation Extraction Using Cross-lingual Projection"*](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/43449.pdf) - HLT-NAACL 2015

  Manaal Faruqui, Shankar Kumar
  
* [*"Enriching Structured Knowledge with Open Information"*](https://ub-madoc.bib.uni-mannheim.de/38861/1/p267.pdf) - WWW 2015

  Arnab Dutta, Christian Meilicke, Heiner Stuckenschmidt
  
* *["SRDF: Korean Open Information Extraction using Singleton Property"](http://ceur-ws.org/Vol-1486/paper_55.pdf)* - ISWC 2015

  Sangha Nam, YoungGyun Hahm, Sejin Nam, Key-Sun Choi

* *["Multilingual Open Information Extraction"](https://gramatica.usc.es/~gamallo/artigos-web/EPIA2015.pdf)* - EPIA 2015

  Pablo Gamallo, Marcos García
  
* *["Open information extraction based on lexical semantics"](https://link.springer.com/article/10.1186/s13173-015-0023-2)* - J. Braz. Comp. Soc. 21 2015

  Clarissa Castellã Xavier, Vera Lúcia Strube de Lima, Marlo Souza
  
### 2016

* *["Nested Propositions in Open Information Extraction"](https://aclweb.org/anthology/D16-1006)* - EMNLP 2016 ([talk](https://vimeo.com/239245885))

  Nikita Bhutani, H. V. Jagadish, Dragomir R. Radev

* *["Creating a Large Benchmark for Open Information Extraction"](https://aclweb.org/anthology/D16-1252)* - EMNLP 2016 ([code](https://github.com/gabrielStanovsky/oie-benchmark), [talk](https://vimeo.com/239251034))

  Gabriel Stanovsky, Ido Dagan
  
* *["Porting an Open Information Extraction System from English to German"](https://aclweb.org/anthology/D16-1086)* - EMNLP 2016 ([code](https://github.com/UKPLab/props-de))

  Tobias Falke, Gabriel Stanovsky, Iryna Gurevych, Ido Dagan
  
* *["Relation Schema Induction using Tensor Factorization with Side Information"](https://www.aclweb.org/anthology/D16-1040)* - EMNLP 2016 

  Madhav Nimishakavi, Uday Singh Saini, Partha P. Talukdar
  
* *["Open Information Extraction Systems and Downstream Applications"](https://www.ijcai.org/Proceedings/16/Papers/604.pdf)* - IJCAI 2016

  Mausam
  
* *["Demonyms and Compound Relational Nouns in Nominal Open IE"](https://homes.cs.washington.edu/~mausam/papers/akbc16.pdf)* - AKBC@NAACL-HLT 2016

  Harinder Pal, Mausam
  
* *["A Rule Based Open Information Extraction Method Using Cascaded Finite-State Transducer"](https://link.springer.com/chapter/10.1007/978-3-319-31750-2_26)* - PAKDD 2016

  Hailun Lin, Yuanzhuo Wang, Peng Zhang, Weiping Wang, Yinliang Yue, Zheng Lin

* *["Getting More Out Of Syntax with PropS"](https://arxiv.org/pdf/1603.01648.pdf)* - CoRR (2016)

  Gabriel Stanovsky, Jessica Ficler, Ido Dagan, Yoav Goldberg

* *["Improving Open Information Extraction for Semantic Web Tasks"](https://link.springer.com/chapter/10.1007/978-3-662-49521-6_6)* -  Trans. Computational Collective Intelligence 21, 2016

  Cheikh Kacfah Emani, Catarina Ferreira Da Silva, Bruno Fiés, Parisa Ghodous
  
* *["An Informativeness Approach to Open IE Evaluation"](http://rali.iro.umontreal.ca/rali/sites/default/files/publis/An_informativeness_approach_to_Open_IE_evaluation%5B1%5D.pdf)* - CICLing 2016 ([slides](http://www-etud.iro.umontreal.ca/~lechellw/papers/2016-CICLING.pdf), [code + data](http://www-etud.iro.umontreal.ca/~lechellw/data/CICLing_092.zip))

  William Léchelle, Philippe Langlais
  
### 2017

* *["MinIE: Minimizing Facts in Open Information Extraction"](http://aclweb.org/anthology/D17-1278)* - EMNLP 2017 ([code](https://github.com/uma-pi1/minie), [poster](https://dws.informatik.uni-mannheim.de/fileadmin/lehrstuehle/pi1/people/rgemulla/publications/gashteovski17minie-poster.pdf), [all resources](https://dws.informatik.uni-mannheim.de/en/resources/software/minie/))

  Kiril Gashteovski, Rainer Gemulla, Luciano Del Corro
  
* *["Answering Complex Questions Using Open Information Extraction"](http://ai2-website.s3.amazonaws.com/publications/TupleInf_ACL17.pdf)* - ACL 2017

  Tushar Khot, Ashish Sabharwal, Peter Clark
  
* *["Pocket Knowledge Base Population"](https://www.cs.jhu.edu/~mdredze/publications/2017_acl_pocket_kb.pdf)* - ACL 2017
  
  Travis Wolfe, Mark Dredze, Benjamin Van Durme
  
* *["Bootstrapping for Numerical Open IE"](https://homes.cs.washington.edu/~mausam/papers/acl17.pdf)* - ACL 2017

  Swarnadeep Saha, Harinder Pal, Mausam

* *["MT/IE: Cross-lingual Open Information Extraction with Neural Sequence-to-Sequence Models"](http://www.aclweb.org/anthology/E17-2011)* - EACL 2017 ([code](https://github.com/sheng-z/cross-lingual-open-ie))
  	
  Kevin Duh, Benjamin Van Durme, Sheng Zhang
  
* *[Open Relation Extraction for Support Passage Retrieval: Merit and Open Issues"](https://www.cs.unh.edu/~dietz/appendix/openie4ir/kadry-dietz-sigir2017-open-relation-extraction-for-support-passage-retrieval.pdf)* - SIGIR 2017

  Amina Kadry, Laura Dietz
    
* *["Syntactic Representation Learning for Open Information Extraction on Web"](https://dl.acm.org/citation.cfm?id=3041021.3054266)* - WWW 2017

  Chengsen Ru, Jintao Tang, Shasha Li, Ting Wang
    
* *["MetaPAD: Meta Pattern Discovery from Massive Text Corpora"](http://www.meng-jiang.com/pubs/metapad-kdd17/metapad-kdd17-paper.pdf)* ([code](https://github.com/mjiang89/MetaPAD))- KDD 2017

  Meng Jiang, Jingbo Shang, Taylor Cassidy, Xiang Ren, Lance M. Kaplan, Timothy P. Hanratty, Jiawei Han
  
* *["RelVis: Benchmarking OpenIE Systems"](http://ceur-ws.org/Vol-1963/paper527.pdf)* - ISWC 2017

  Rudolf Schneider, Tom Oberhauser, Tobias Klatt, Felix A. Gers, Alexander Löser

* *["Open Relation Extraction and Grounding"](http://aclweb.org/anthology/I17-1086)* - IJCNLP 2017

  Dian Yu, Lifu Huang, Heng Ji
  
* *["Selective Decoding for Cross-lingual Open Information Extraction"](http://www.aclweb.org/anthology/I17-1084)* - IJCNLP(1) 2017

  Sheng Zhang, Kevin Duh, Benjamin Van Durme

* *["An assessment of open relation extraction systems for the semantic web"](https://www.sciencedirect.com/science/article/pii/S0306437916304999)* - Inf. Syst. 71, 2017

  Amal Zouaq, Michel Gagnon, Ludovic Jean-Louis
  
* *["An Evaluation of PredPatt and Open IE via Stage 1 Semantic Role Labeling"](https://aclweb.org/anthology/W17-6944)* - IWCS 2017

  Sheng Zhang, Rachel Rudinger, Benjamin Van Durme
  
* *["Discovering Relational Phrases for Qualia Roles Through Open Information Extraction"](https://link.springer.com/chapter/10.1007/978-3-319-69548-8_6)* - KESW 2017

  Giovanni Siragusa, Valentina Leone, Luigi Di Caro, Claudio Schifanella
  
* *["Open Relation Extraction Based on Core Dependency Phrase Clustering"](https://ieeexplore.ieee.org/document/8005507)* - DSC 2017

  Chengsen Ru, Shasha Li, Jintao Tang, Yi Gao, Ting Wang  
  
* *["Analysing Errors of Open Information Extraction Systems"](https://aclweb.org/anthology/W17-5402)* - Workshop on Building Linguistically Generalizable NLP Systems @ EMNLP 2017

  Rudolf Schneider, Tom Oberhauser, Tobias Klatt, Felix A. Gers, Alexander Löser
  
### 2018

* *["Logician: A Unified End-to-End Neural Approach for Open-Domain Information Extraction"](https://tianjun.me/static/essay_resources/RelationExtraction/Paper/2018_Logician_A_Unified_End-to-End_Neural_Approach_for_open_domain_IE(1).pdf)* - WSDM 2018

  Mingming Sun, Xu Li, Xin Wang, Miao Fan, Yue Feng, Ping Li

* *["Assertion-Based QA With Question-Aware Open Information Extraction"](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/download/16705/16170)* - AAAI 2018
  	
  Zhao Yan, Duyu Tang, Nan Duan, Shujie Liu, Wendi Wang, Daxin Jiang, Ming Zhou, Zhoujun Li
  
* *["Neural Open Information Extraction"](http://aclweb.org/anthology/P18-2065)* - ACL 2018

  Lei Cui, Furu Wei, Ming Zhou
  
* *["Supervised Open Information Extraction"](http://www.aclweb.org/anthology/N18-1081)* - NAACL-HLT 2018
  	
  Gabriel Stanovsky, Julian Michael, Luke Zettlemoyer, Ido Dagan
  
* [*"Logician and Orator: Learning from the Duality between Language and Knowledge in Open Domain"*](https://www.aclweb.org/anthology/D18-1236) - EMNLP 2018

   Mingming Sun, Xu Li, Ping Li
  
* *["Open Information Extraction from Conjunctive Sentences"](http://aclweb.org/anthology/C18-1194)* - COLING 2018

  Swarnadeep Saha, Mausam
  
* *["Graphene: Semantically-Linked Propositions in Open Information Extraction"](http://aclweb.org/anthology/C18-1195)* - COLING 2018 ([code](https://github.com/Lambda-3/Graphene), [documentation](http://lambda3.org/Graphene/))

  Matthias Cetto, Christina Niklaus, André Freitas, Siegfried Handschuh
  
* *["Open Information Extraction on Scientific Text: An Evaluation"](http://aclweb.org/anthology/C18-1289)* - COLING 2018
  
  Paul T. Groth, Michael Lauruhn, Antony Scerri, Ron Daniel
  
* *["A Survey on Open Information Extraction"](http://aclweb.org/anthology/C18-1326)* - COLING 2018

  Christina Niklaus, Matthias Cetto, André Freitas, Siegfried Handschuh
  
* *["StuffIE: Semantic Tagging of Unlabeled Facets Using Fine-Grained Information Extraction"](https://dl.acm.org/citation.cfm?id=3271812)* - CIKM 2018

  Radityo Eko Prasojo, Mouna Kacimi, Werner Nutt
  
* *["Towards Practical Open Knowledge Base Canonicalization"](https://dl.acm.org/citation.cfm?id=3271707)* - CIKM 2018

   Tien-Hsuan Wu, Zhiyong Wu, Ben Kao, Pengcheng Yin
  
* *["Open Information Extraction with Global Structure Constraints"](http://www-bcf.usc.edu/~xiangren/www18_poster.pdf)* - WWW 2018

  Qi Zhu, Xiang Ren, Jingbo Shang, Yu Zhang, Frank F. Xu, Jiawei Han

* *["CESI: Canonicalizing Open Knowledge Bases using Embeddings and Side Information"](https://dl.acm.org/citation.cfm?id=3186030)* - WWW 2018 ([code](https://github.com/malllabiisc/cesi))
  
  Shikhar Vashishth, Prince Jain, Partha Talukdar

* *["Revisiting the Task of Scoring Open IE Relations"](http://www-etud.iro.umontreal.ca/~lechellw/papers/submitted_to_LREC18.pdf)* ([poster](http://www-etud.iro.umontreal.ca/~lechellw/papers/2018-LREC-poster.pdf)) - LREC 2018

  William Léchelle, Philippe Langlais
  
* *["Employing Semantic Context for Sparse Information Extraction Assessment"](https://dl.acm.org/citation.cfm?id=3201407)* - TKDD 2018 ([resources](https://github.com/peipeilihfut/AssessSparseIE))

  Pei-Pei Li, Haixun Wang, Hongsong Li, Xindong Wu
  
* *["Open Information Extraction with Meta-pattern Discovery in Biomedical Literature"](https://yuzhimanhua.github.io/papers/bcb18.pdf)* - BCB 2018

  Xuan Wang, Yu Zhang, Qi Li, Yinyin Chen, Jiawei Han
  
* *["Modeling and Summarizing News Events Using Semantic Triples"](https://link.springer.com/chapter/10.1007/978-3-319-93417-4_33)* - ESWC 2018

  Radityo Eko Prasojo, Mouna Kacimi, Werner Nutt
  
* *["Disambiguating Open IE: Identifying Semantic Similarity in Relation Extraction by Word Embeddings"](https://www.springerprofessional.de/en/disambiguating-open-ie-identifying-semantic-similarity-in-relati/16122888)* - PROPOR 2018

  Leandro M. P. Sanches, Victor S. Cardel, Larissa S. Machado, Marlo Souza, Laís do Nascimento Salvador
  
* *["Task-Oriented Evaluation of Dependency Parsing with Open Information Extraction"](https://link.springer.com/chapter/10.1007%2F978-3-319-99722-3_8)* - PROPOR 2018

  Pablo Gamallo, Marcos Garcia
  
* *["Challenges of an Annotation Task for Open Information Extraction in Portuguese"](https://link.springer.com/chapter/10.1007/978-3-319-99722-3_7)* - PROPOR 2018

  Rafael Glauber, Leandro Souza de Oliveira, Cleiton Fernando Lima Sena, Daniela Barreiro Claro, Marlo Souza
  
* *["A systematic mapping study on open information extraction"](https://www.sciencedirect.com/science/article/pii/S0957417418303932)* -  Expert Syst. Appl. 2018

  Rafael Glauber, Daniela Barreiro Claro
  
* *["Self-training on refined clause patterns for relation extraction"](https://www.sciencedirect.com/science/article/abs/pii/S0306457316303259?dgcid=raven_sd_recommender_email)* - Inf. Process. Manage. 54(4): 686-706 (2018)

  Duc-Thuan Vo, Ebrahim Bagheri
  
* *["Supervised Neural Models Revitalize the Open Relation Extraction"](https://arxiv.org/pdf/1809.09408.pdf)* - CoRR 2018

  Shengbin Jia, Yang Xiang, Xiaojun Chen
  
* *["Chinese Open Relation Extraction and Knowledge Base Establishment"](https://ai2-website.s3.amazonaws.com/publications/10094_Paper.pdf)* - ACM Trans. Asian & Low-Resource Lang. Inf. Process. 2018 ([slides](https://hong.xmu.edu.cn/__local/B/68/C0/92B8F8DC6AC06A3F256E1FE1A6F_9556CC90_4CCA5D.pdf?e=.pdf), [code](https://github.com/lemonhu/open-entity-relation-extraction))

  Shengbin Jia, Shijia E, Maozhen Li, Yang Xiang
  
* *[Rule-based Indonesian Open Information Extraction"](https://ieeexplore.ieee.org/document/8541293)* - ICAICTA 2018 

  Ade Romadhony, Ayu Purwarianti, Dwi H. Widyantoro
  
* *["WiRe57 : A Fine-Grained Benchmark for Open Information Extraction"](https://arxiv.org/pdf/1809.08962.pdf)* - CoRR 2018

  William Léchelle, Fabrizio Gotti, Philippe Langlais
  
### 2019

* *["OPIEC: An Open Information Extraction Corpus"](https://openreview.net/pdf?id=HJxeGb5pTm)* - AKBC 2019 ([data + resources](https://www.uni-mannheim.de/dws/research/resources/opiec/), [code (data reading)](https://github.com/uma-pi1/OPIEC), [code (pipeline)](https://github.com/uma-pi1/OPIEC-pipeline))

  Kiril Gashteovski, Sebastian Wanner, Sven Hertling, Samuel Broscheit, Rainer Gemulla
  
* *["MinScIE: Citation-centered Open Information Extraction"](https://ub-madoc.bib.uni-mannheim.de/49216/1/_JCDL19Demo__MinScIE%20%284%29.pdf)* - JCDL 2019 ([code](https://github.com/gkiril/MinSCIE))

  Anne Lauscher, Yide Song, Kiril Gashteovski
  
* *["EAL: A Toolkit and Dataset for Entity-Aspect Linking"](https://ub-madoc.bib.uni-mannheim.de/49596/1/EAL.pdf)* - JCDL 2019 ([data](https://federiconanni.com/eal-d/), [code](https://github.com/jinggz/Master-Thesis-EAL/tree/service), [demo](http://tools.dws.informatik.uni-mannheim.de/eal))

  Federico Nanni, Jingyi Zhang, Ferdinand Betz, Kiril Gashteovski

* *["Integrating Local Context and Global Cohesiveness for Open Information Extraction"](https://arxiv.org/pdf/1804.09931.pdf)* - WSDM 2019 ([code](https://github.com/GentleZhu/ReMine))

  Qi Zhu, Xiang Ren, Jingbo Shang, Yu Zhang, Ahmed El-Kishky, Jiawei Han

* *["Open Information Extraction from Question-Answer Pairs"](https://arxiv.org/pdf/1903.00172.pdf)* - NAACL 2019

  Nikita Bhutani, Yoshihiko Suhara, Wang-Chiew Tan, Alon Halevy and H V Jagadish
  
* *["OpenKI: Integrating Open Information Extraction and Knowledge Bases with Relation Inference"](https://www.aclweb.org/anthology/N19-1083/)* - NAACL 2019 ([data](https://github.com/zhangdongxu/relation-inference-naacl19)) 

  Dongxu Zhang, Subhabrata Mukherjee, Colin Lockard, Xin Luna Dong, Andrew McCallum
  
* *["OpenCeres: When Open Information Extraction Meets the Semi-Structured Web"](http://lunadong.com/publication/openCeres_naacl.pdf)* - NAACL 2019 ([video](https://vimeo.com/355837778), [slides](https://homes.cs.washington.edu/~lockardc/OpenCeres_NAACL_talk.pdf), [data](https://archive.codeplex.com/?p=swde))

  Colin Lockard, Prashant Shiralkar and Xin Luna Dong 
  
* *["Improving Open Information Extraction via Iterative Rank-Aware Learning"](https://www.aclweb.org/anthology/P19-1523)* - ACL 2019 ([code](https://github.com/jzbjyb/oie_rank))

   Zhengbao Jiang, Pengcheng Yin and Graham Neubig
   
* *["Open Relation Extraction: Relational Knowledge Transfer from Supervised Data to Unsupervised Data"](https://www.aclweb.org/anthology/D19-1021.pdf)* - EMNLP 2019

   Ruidong Wu, Yuan Yao, Xu Han, Ruobing Xie, Zhiyuan Liu, Fen Lin, Leyu Lin and Maosong Sun
   
* *["Supervising Unsupervised Open Information Extraction Models"](https://www.aclweb.org/anthology/D19-1067.pdf)* - EMNLP 2019

   Arpita Roy, Youngja Park, Taesung Lee and Shimei Pan
   
* *["CaRB: A Crowdsourced Benchmark for Open IE"](http://www.cse.iitd.ac.in/~mausam//papers/emnlp19.pdf)* - EMNLP 2019 ([code and data](https://github.com/dair-iitd/CaRB))

   Sangnie Bhardwaj, Samarth Aggarwal and Mausam
   
* *["CaRe: Open Knowledge Graph Embeddings"](http://talukdar.net/papers/CaRe_EMNLP2019.pdf)* - EMNLP 2019 ([code](https://github.com/malllabiisc/CaRE))

   Swapnil Gupta, Sreyash Kenkre, Partha Talukdar
   
* *["Collaborative Policy Learning for Open Knowledge Graph Reasoning"](https://www.aclweb.org/anthology/D19-1269.pdf)* - EMNLP 2019 ([code](https://github.com/INK-USC/CPL))
 
   Cong Fu, Tong Chen, Meng Qu, Woojeong Jin, Xiang Ren
   
* *["Multi-Input Multi-Output Sequence Labeling for Joint Extraction of Fact and Condition Tuples from Scientific Text"](https://www.aclweb.org/anthology/D19-1029/)* - EMNLP 2019

   Tianwen Jiang, Tong Zhao, Bing Qin, Ting Liu, Nitesh Chawla, Meng Jiang
   
* *["The Role of "Condition": A Novel Scientific Knowledge Graph Representation and Construction Model"](https://dl.acm.org/doi/10.1145/3292500.3330942)* - KDD 2019

   Tianwen Jiang, Tong Zhao, Bing Qin, Ting Liu, Nitesh V. Chawla, Meng Jiang

* *["Canonicalization of Open Knowledge Bases with Side Information from the Source Text"](https://ieeexplore.ieee.org/abstract/document/8731346)* - ICDE 2019

   Xueling Lin, Lei Chen
   
* *["Open Relation Extraction for Chinese Noun Phrases"](https://ieeexplore.ieee.org/abstract/document/8903488)* - TKDE 2019

   Chengyu Wang, Xiaofeng He, Aoying Zhou
   
* *["Divide and Extract – Disentangling Clause Splitting and Proposition Extraction"](https://acl-bg.org/proceedings/2019/RANLP%202019/pdf/RANLP047.pdf)* - RANLP 2019

   Darina Gold, Torsten Zesch
   
* *["Exploiting Open IE for Deriving Multiple Premises Entailment Corpus"](https://acl-bg.org/proceedings/2019/RANLP%202019/pdf/RANLP144.pdf)* - RANLP 2019

   Martin Víta, Jakub Klímek
   
* *["Lexicon-Grammar based Open Information Extraction from Natural Language Sentences in Italian"](https://www.sciencedirect.com/science/article/pii/S0957417419306724)* - Expert Systems and Applications 2019

   Raffaele Guarasci, Emanuele Damiano, Aniello Minutolo, Massimo Esposito, Giuseppe De Pietro
   
* *["Weakly Supervised, Data-Driven Acquisition of Rules for Open Information Extraction"](https://link.springer.com/chapter/10.1007/978-3-030-18305-9_2)* - CAIAC 2019

   Fabrizio GottiEmail, Philippe Langlais

* *["Aligning Open IE Relations and KB Relations using a Siamese Network Based on Word Embedding"](https://www.aclweb.org/anthology/papers/W/W19/W19-0412/)* - ICCS 2019

   Rifki Afina Putri, Giwon Hong, Sung-Hyon Myaeng
   
* [*"Contextualized Word Embeddings in a Neural Open Information Extraction Model"*](https://link.springer.com/chapter/10.1007/978-3-030-23281-8_31) - NLDB 2019

   Injy Sarhan, Marco R. Spruit
   
* [*"Multilingual Open Information Extraction: Challenges and Opportunities"*](https://www.preprints.org/manuscript/201905.0029/download/final_file) -  Information 10(7): 228, 2019

   Daniela Barreiro Claro, Marlo Souza, Clarissa Castellã Xavier, Leandro Souza de Oliveira
   
* [*"CTGA: Graph-based Biomedical Literature Search"*](https://ieeexplore.ieee.org/abstract/document/8983173) - IEEE International Conference on Bioinformatics and Biomedicine (BIBM)

   Tianwen Jiang, Zhihan Zhang, Tong Zhao, Bing Qin, Ting Liu, Nitesh V. Chawla, Meng Jiang
   
* [*"When Lexicon-Grammar Meets Open Information Extraction: a Computational Experiment for Italian Sentences"*](http://ceur-ws.org/Vol-2481/paper36.pdf) -  CLiC-it 2019

   Raffaele Guarasci, Emanuele Damiano, Aniello Minutolo, Massimo Esposito
   
* [*"Towards a gold standard dataset for Open Information Extraction in Italian"*](https://ieeexplore.ieee.org/abstract/document/8931822) - SNAMS 2019

   Raffaele Guarasci, Emanuele Damiano, Aniello Minutolo, Massimo Esposito
   
* [*"Co-Clustering Triples from Open Information Extraction"*](https://people.mpi-inf.mpg.de/~kpal/paper/COMAD_2020_kpal.pdf) - COMAD 2019

   Koninika Pal, Vinh Thinh Ho, Gerhard Weikum
   
* [*Coherence and Salience-Based Multi-Document Relationship Mining*](https://www.researchgate.net/publication/332735453_Coherence_and_Salience-Based_Multi-Document_Relationship_Mining) - APWeb-WAIM 2019

   Yongpan Sheng, Zenglin Xu

* *["Learning Open Information Extraction of Implicit Relations from Reading Comprehension Datasets"](https://arxiv.org/abs/1905.07471)* - CoRR 2019

   Jacob Beckerman, Theodore Christakis
   
### 2020

* [*Systematic Comparison of Neural Architectures and Training Approaches for Open Information Extraction*](https://www.aclweb.org/anthology/2020.emnlp-main.690) - EMNLP 2020

   Patrick Hohenecker, Frank Mtumbuka, Vid Kocijan, Thomas Lukasiewicz

* [*A Predicate-Function-Argument Annotation of Natural Language for Open-Domain Information eXpression*](https://www.aclweb.org/anthology/2020.emnlp-main.167/) - EMNLP 2020 ([resources](https://sunbelbd.github.io/Open-Information-eXpression/))

   Mingming Sun, Wenyue Hua, Zoey Liu, Xin Wang, Kangjie Zheng, Ping Li


* [*Systematic Comparison of Neural Architectures and Training Approaches for Open Information Extraction*](http://www.cs.ox.ac.uk/publications/publication14256-abstract.html) - EMNLP 2020

   Patrick Hohenecker, Frank Mtumbuka, Vid Kocijan, Thomas Lukasiewicz


* [*SelfORE: Self-supervised Relational Feature Learning for Open Relation Extraction*](https://arxiv.org/pdf/2004.02438.pdf) - EMNLP 2020

   Xuming Hu, Chenwei Zhang, Yusong Xu, Lijie Wen, Philip S. Yu

* [*"OpenIE6: Iterative Grid Labeling and Coordination Analysis for Open Information Extraction"*](https://arxiv.org/abs/2010.03147) ([code](https://github.com/dair-iitd/openie6)) - EMNLP 2020

  Keshav Kolluru, Vaibhav Adlakha, Samarth Aggarwal, Mausam, Soumen Chakrabarti

* [*"Multi2OIE: Multilingual Open Information Extraction based on Multi-Head Attention with BERT"*](https://arxiv.org/pdf/2009.08128.pdf) ([code](https://github.com/youngbin-ro/Multi2OIE)) - EMNLP 2020

  Youngbin Ro, Yukyung Lee, Pilsung Kang
  
* [*"On Aligning OpenIE Extractions with Knowledge Bases: A Case Study"*](https://www.aclweb.org/anthology/2020.eval4nlp-1.14/) ([video](https://slideslive.com/38939720/on-aligning-openie-extractions-with-knowledge-bases-a-case-study), [slides](https://www.uni-mannheim.de/media/Einrichtungen/dws/pi1/opiec/dsa-ota-talk-final.pdf), [resources](https://www.uni-mannheim.de/dws/research/resources/opiec/)) - Eval4NLP@EMNLP 2020

   Kiril Gashteovski, Rainer Gemulla, Bhushan Kotnis, Sven Hertling, Christian Meilicke

* [*"IMoJIE: Iterative Memory-Based Joint Open Information Extraction"*](https://www.aclweb.org/anthology/2020.acl-main.521/) ([code](https://github.com/dair-iitd/imojie), [video](https://slideslive.com/38929035/imojie-iterative-memorybased-joint-open-information-extraction)) - ACL 2020

   Keshav Kolluru, Samarth Aggarwal, Vipul Rathore, Mausam, Soumen Chakrabarti
   
* [*"Can We Predict New Facts with Open Knowledge Graph Embeddings? A Benchmark for Open Link Prediction"*](https://www.aclweb.org/anthology/2020.acl-main.209/) ([resources](https://www.uni-mannheim.de/dws/research/resources/olpbench/), [video](https://slideslive.com/38929433/can-we-predict-new-facts-with-open-knowledge-graph-embeddings-a-benchmark-for-open-link-prediction)) - ACL 2020

   Samuel Broscheit, Kiril Gashteovski, Yanjie Wang, Rainer Gemulla

* [*"Learning Interpretable Relationships between Entities, Relations and Concepts via Bayesian Structure Learning on Open Domain Facts"*](https://www.aclweb.org/anthology/2020.acl-main.717/) ([video](https://slideslive.com/38928762/learning-interpretable-relationships-between-entities-relations-and-concepts-via-bayesian-structure-learning-on-open-domain-facts)) - ACL 2020

   Jingyuan Zhang, Mingming Sun, Yue Feng, Ping Li

* [*"In Layman’s Terms: Semi-Open Relation Extraction from Scientific Texts"*](https://www.aclweb.org/anthology/2020.acl-main.137.pdf) ([code](https://github.com/rubenkruiper/FOBIE), [video](https://slideslive.com/38928870/in-laymans-terms-semiopen-relation-extraction-from-scientific-texts)) - ACL 2020

   Ruben Kruiper, Julian Vincent, Jessica Chen-Burger, Marc Desmulliez, Ioannis Konstas

* *["Span Model for Open Information Extraction on Accurate Corpus"](https://arxiv.org/pdf/1901.10879.pdf)* ([code](https://github.com/zhanjunlang/Span_OIE))- AAAI 2020
   
   Junlang Zhan, Hai Zhao
   
* *["LOREM: Language-consistent Open Relation Extraction from Unstructured Text"](https://repository.tudelft.nl/islandora/object/uuid%3A3d9cfa08-4a7f-41cc-afdd-a8902094228c)* ([code](https://github.com/tomharting/LOREM)) - WWW 2020

   Tom Harting, Sepideh Mesbah, Christoph Lofi
   
* *["Extracting Knowledge from Web Text with Monte Carlo Tree Search"](https://dl.acm.org/doi/abs/10.1145/3366423.3380010)* - WWW 2020

   Guiliang Liu, Xu Li, Jiakang Wang, Mingming Sun, Ping Li
   
* *["MULCE: Multi-level Canonicalization with Embeddings of Open Knowledge Bases"](https://link.springer.com/chapter/10.1007/978-3-030-62005-9_23)* - WISE 2020

   Tien-Hsuan Wu, Ben Kao, Zhiyong Wu, Xiyang Feng, Qianli Song, Cheng Chen

   
* [*An Advantage Actor-Critic Algorithm with Confidence Exploration for Open Information Extraction"*](https://epubs.siam.org/doi/abs/10.1137/1.9781611976236.25) - SDM 2020

   Guiliang Liu, Xu Li, Miningming Sun, Ping Li

   
* *["Chinese Open Relation Extraction with Pointer-Generator Networks"](https://ieeexplore.ieee.org/abstract/document/9172882/references#references)* - DSC 2020

   Ziheng Cheng, Xu Wu, Xiaqing Xie, Jingchen Wu
   
* *[Explainable OpenIE Classifier with Morpho-syntactic Rules"](http://ceur-ws.org/Vol-2693/paper1.pdf)* - HI4NLP@ECAI 2020 

   Bruno Cabral, Marlo Souza, Daniela Barreiro Claro
   
* [*Language Models are Open Knowledge Graphs*](https://arxiv.org/abs/2010.11967) - CoRR 2020

   Chenguang Wang, Xiao Liu, Dawn Song
   
* [*"Hybrid Neural Tagging Model for Open Relation Extraction"*](https://arxiv.org/pdf/1908.01761.pdf) - CoRR 2020 ([data](https://github.com/TJUNLP/NSL4OIE))

   Shengbin Jia, Yang Xiang
   
* [*"Canonicalizing Open Knowledge Bases with Multi-Layered Meta-Graph Neural Network"*](https://arxiv.org/pdf/2006.09610.pdf) - CoRR 2020

   Tianwen Jiang, Tong Zhao, Bing Qin, Ting Liu, Nitesh V. Chawla, Meng Jiang
   
* [*"Tag and Correct: Question Aware Open Information Extraction with Two-Stage Decoding"*](https://arxiv.org/pdf/2009.07406.pdf) - CoRR 2020

   Martin Kuo, Yaobo Liang, Lei Ji, Nan Duan, Linjun Shou, Ming Gong, Peng Chen
   
* [*"Abstractive Query Focused Summarization with Query-Free Resources"*](https://arxiv.org/abs/2012.14774) - CoRR 2020

   Yumo Xu, Mirella Lapata

### 2021

* [*"CoRI: Collective Relation Integration with Data Augmentation for Open Information Extraction"*](https://arxiv.org/pdf/2106.00793.pdf) - ACL 2021

   Zhengbao Jiang, Jialong Han, Bunyamin Sisman, Xin Luna Dong
   
* [*"DocOIE: A Document-level Context-Aware Dataset for OpenIE"*](https://aclanthology.org/2021.findings-acl.210/) - ACL 2021

   Kuicai Dong, Zhao Yilin, Aixin Sun, Jung-Jae Kim, Xiaoli Li
   
* [*"OKGIT: Open Knowledge Graph Link Prediction with Implicit Types"*](https://aclanthology.org/2021.findings-acl.225/) - ACL 2021

   	Chandrahas, Partha Pratim Talukdar
    
* [*"Maximal Clique Based Non-Autoregressive Open Information Extraction"*](https://aclanthology.org/2021.emnlp-main.764/) - EMNLP 2021

    Bowen Yu, Yucheng Wang, Tingwen Liu, Hongsong Zhu, Limin Sun, Bin Wang
   
* [*"LSOIE: A Large-Scale Dataset for Supervised Open Information Extraction"*](https://aclanthology.org/2021.eacl-main.222/) - EACL 2021 ([code and data](https://github.com/Jacobsolawetz/large-scale-oie)) 

   Jacob Solawetz, Stefan Larson

* [*"Open Hierarchical Relation Extraction"*](https://www.aclweb.org/anthology/2021.naacl-main.452.pdf) - NAACL 2021 ([code](https://github.com/thunlp/OHRE))

   Kai Zhang, Yuan Yao, Ruobing Xie, Xu Han, Zhiyuan Liu, Fen Lin, Leyu Lin, Maosong Sun

* [*"Semi-Open Information Extraction"*](https://dl.acm.org/doi/abs/10.1145/3442381.3450029) - WWW 2021

   Bowen Yu, Zhenyu Zhang, Jiawei Sheng, Tingwen Liu, Yubin Wang, Yucheng Wang, Bin Wang
   
* [*"Joint Open Knowledge Base Canonicalization and Linking"*](https://dl.acm.org/doi/abs/10.1145/3448016.3452776) - SIGMOD 2021

   	Yinan Liu, Wei Shen, Yuanfei Wang, Jianyong Wang, Zhenglu Yang, Xiaojie Yuan
    
* [*"TENET: Joint Entity and Relation Linking with Coherence Relaxation"*](https://dl.acm.org/doi/abs/10.1145/3448016.3457280) - SIGMOD 2021

    Xueling Lin, Lei Chen, Chaorui Zhang

* [*"Multi-Grained Dependency Graph Neural Network for Chinese Open Information Extraction"*](https://link.springer.com/content/pdf/10.1007/978-3-030-75768-7_13.pdf) - PAKDD 2021

   Zhiheng Lyu, Kaijie Shi, Xin Li, Lei Hou, Juanzi Li, Binheng Song
   
* *[PENELOPIE: Enabling Open Information Extraction for the Greek Language through Machine Translation"](https://aclanthology.org/2021.eacl-srw.4/)* - Student Research Workshop @ EACL

   Dimitris Papadopoulos, Nikolaos Papadakis, Nikolaos Matsatsinis
   
### 2022

* [*"BenchIE: A Framework for Multi-Faceted Fact-Based Open Information Extraction Evaluation"*](https://aclanthology.org/2022.acl-long.307/) - ACL 2022 ([code](https://github.com/gkiril/benchie))

   Kiril Gashteovski, Mingying Yu, Bhushan Kotnis, Carolin Lawrence, Mathias Niepert, Goran Glavaš
   
* [*"MILIE: Modular & Iterative Multilingual Open Information Extraction"*](https://aclanthology.org/2022.acl-long.478/) - ACL 2022 

   Bhushan Kotnis, Kiril Gashteovski, Daniel Rubio, Ammar Shaker, Vanesa Rodriguez-Tembras, Makoto Takamoto, Mathias Niepert, Carolin Lawrence

* [*Alignment-Augmented Consistent Translation for Multilingual Open Information Extraction"*](https://aclanthology.org/2022.acl-long.179/) - ACL 2022 ([code](https://github.com/dair-iitd/moie))

   Keshav Kolluru, Muqeeth Mohammed, Shubham Mittal, Soumen Chakrabarti, Mausam

* [*"OIE@OIA: an Adaptable and Efficient Open Information Extraction Framework"*](https://aclanthology.org/2022.acl-long.430/) - ACL 2022 

   Xin Wang, Minlong Peng, Mingming Sun, Ping Li
   
* [*"Open Relation Modeling: Learning to Define Relations between Entities"*](https://aclanthology.org/2022.findings-acl.26/) - ACL 2022 ([code](https://github.com/jeffhj/open-relation-modeling))

   Jie Huang, Kevin Chang, Jinjun Xiong, Wen-mei Hwu
   
* [*"DeepStruct: Pretraining of Language Models for Structure Prediction"*](https://aclanthology.org/2022.findings-acl.67/) - ACL 2022 ([code](https://github.com/cgraywang/deepstruct))

   Chenguang Wang, Xiao Liu, Zui Chen, Haoyun Hong, Jie Tang, Dawn Song
      
* [*"AnnIE: An Annotation Platform for Constructing Complete Open Information Extraction Benchmark"*](https://aclanthology.org/2022.acl-demo.5/) - ACL 2022 ([code](https://github.com/nfriedri/annie-annotation-platform))

   Niklas Friedrich, Kiril Gashteovski, Mingying Yu, Bhushan Kotnis, Carolin Lawrence, Mathias Niepert, Goran Glavaš
   
* [*"CompactIE: Compact Facts in Open Information Extraction"*](https://aclanthology.org/2022.naacl-main.65/) - NAACL 2022 ([code](https://github.com/FarimaFatahi/CompactIE))

   Farima Fatahi Bayat, Nikita Bhutani, H. V. Jagadish

* [*"DetIE: Multilingual Open Information Extraction Inspired by Object Detection"*](https://www.aaai.org/AAAI22Papers/AAAI-8073.VasilkovskyM.pdf) - AAAI 2022 ([code](https://github.com/sberbank-ai/DetIE))

   Michael Vasilkovsky, Anton Alekseev, Valentin Malykh, Ilya Shenbin, Elena Tutubalina, Dmitriy Salikhov, Mikhail Stepnov, Andrey Chertok, Sergey I. Nikolenko

* [*"A Survey on Neural Open Information Extraction: Current Status and Future Directions"*](https://arxiv.org/pdf/2205.11725.pdf) - IJCAI 2022

   Shaowen Zhou, Bowen Yu, Aixin Sun, Cheng Long, Jingyang Li, Jian Sun
   
* [*"Open Information Extraction from 2007 to 2022 – A Survey"*](https://arxiv.org/pdf/2208.08690.pdf) - CoRR 2022

   Pai Liu, Wenyang Gao, Wenjie Dong, Songfang Huang, Yue Zhang


## Papers grouped by category

### Surveys

* *["Open Information Extraction Systems and Downstream Applications"](https://www.ijcai.org/Proceedings/16/Papers/604.pdf)* - IJCAI 2016

  Mausam
  
* *["A Survey on Open Information Extraction"](http://aclweb.org/anthology/C18-1326)* - COLING 2018

  Christina Niklaus, Matthias Cetto, André Freitas, Siegfried Handschuh

* *["A systematic mapping study on open information extraction"](https://www.sciencedirect.com/science/article/pii/S0957417418303932)* -  Expert Syst. Appl. 2018

  Rafael Glauber, Daniela Barreiro Claro
  
* [*"Multilingual Open Information Extraction: Challenges and Opportunities"*](https://www.preprints.org/manuscript/201905.0029/download/final_file) -  Information 10(7): 228, 2019

   Daniela Barreiro Claro, Marlo Souza, Clarissa Castellã Xavier, Leandro Souza de Oliveira
   
* [*"A Survey on Neural Open Information Extraction: Current Status and Future Directions"*](https://arxiv.org/pdf/2205.11725.pdf) - IJCAI 2022

   Shaowen Zhou, Bowen Yu, Aixin Sun, Cheng Long, Jingyang Li, Jian Sun

* [*"Open Information Extraction from 2007 to 2022 – A Survey"*](https://arxiv.org/pdf/2208.08690.pdf) - CoRR 2022

   Pai Liu, Wenyang Gao, Wenjie Dong, Songfang Huang, Yue Zhang

### Evaluation

* *["Creating a Large Benchmark for Open Information Extraction"](https://aclweb.org/anthology/D16-1252)* - EMNLP 2016 ([code](https://github.com/gabrielStanovsky/oie-benchmark), [talk](https://vimeo.com/239251034))

  Gabriel Stanovsky, Ido Dagan

* *["An Informativeness Approach to Open IE Evaluation"](http://rali.iro.umontreal.ca/rali/sites/default/files/publis/An_informativeness_approach_to_Open_IE_evaluation%5B1%5D.pdf)* - CICLing 2016 ([slides](http://www-etud.iro.umontreal.ca/~lechellw/papers/2016-CICLING.pdf), [code + data](http://www-etud.iro.umontreal.ca/~lechellw/data/CICLing_092.zip))

  William Léchelle, Philippe Langlais

* *["An Evaluation of PredPatt and Open IE via Stage 1 Semantic Role Labeling"](https://aclweb.org/anthology/W17-6944)* - IWCS 2017

  Sheng Zhang, Rachel Rudinger, Benjamin Van Durme

* *["An assessment of open relation extraction systems for the semantic web"](https://www.sciencedirect.com/science/article/pii/S0306437916304999)* - Inf. Syst. 71, 2017

  Amal Zouaq, Michel Gagnon, Ludovic Jean-Louis
  
* *["RelVis: Benchmarking OpenIE Systems"](http://ceur-ws.org/Vol-1963/paper527.pdf)* - ISWC 2017

  Rudolf Schneider, Tom Oberhauser, Tobias Klatt, Felix A. Gers, Alexander Löser
  
* *["Analysing Errors of Open Information Extraction Systems"](https://aclweb.org/anthology/W17-5402)* - Workshop on Building Linguistically Generalizable NLP Systems @ EMNLP 2017

  Rudolf Schneider, Tom Oberhauser, Tobias Klatt, Felix A. Gers, Alexander Löser

* *["Open Information Extraction on Scientific Text: An Evaluation"](http://aclweb.org/anthology/C18-1289)* - COLING 2018
  
  Paul T. Groth, Michael Lauruhn, Antony Scerri, Ron Daniel
  
* *["WiRe57 : A Fine-Grained Benchmark for Open Information Extraction"](https://arxiv.org/pdf/1809.08962.pdf)* - CoRR 2018

  William Léchelle, Fabrizio Gotti, Philippe Langlais
  
* *["CaRB: A Crowdsourced Benchmark for Open IE"](http://www.cse.iitd.ac.in/~mausam//papers/emnlp19.pdf)* - EMNLP 2019 ([code and data](https://github.com/dair-iitd/CaRB))

   Sangnie Bhardwaj, Samarth Aggarwal and Mausam
   
* [*"Towards a gold standard dataset for Open Information Extraction in Italian"*](https://ieeexplore.ieee.org/abstract/document/8931822) - SNAMS 2019

   Raffaele Guarasci, Emanuele Damiano, Aniello Minutolo, Massimo Esposito
   
* [*Systematic Comparison of Neural Architectures and Training Approaches for Open Information Extraction*](https://www.aclweb.org/anthology/2020.emnlp-main.690) - EMNLP 2020

   Patrick Hohenecker, Frank Mtumbuka, Vid Kocijan, Thomas Lukasiewicz
   
* [*"On Aligning OpenIE Extractions with Knowledge Bases: A Case Study"*](https://www.aclweb.org/anthology/2020.eval4nlp-1.14/) ([video](https://slideslive.com/38939720/on-aligning-openie-extractions-with-knowledge-bases-a-case-study), [slides](https://www.uni-mannheim.de/media/Einrichtungen/dws/pi1/opiec/dsa-ota-talk-final.pdf), [resources](https://www.uni-mannheim.de/dws/research/resources/opiec/)) - Eval4NLP@EMNLP 2020

   Kiril Gashteovski, Rainer Gemulla, Bhushan Kotnis, Sven Hertling, Christian Meilicke
   
* [*"BenchIE: A Framework for Multi-Faceted Fact-Based Open Information Extraction Evaluation"*](https://aclanthology.org/2022.acl-long.307/) - ACL 2022 ([code](https://github.com/gkiril/benchie))

   Kiril Gashteovski, Mingying Yu, Bhushan Kotnis, Carolin Lawrence, Mathias Niepert, Goran Glavaš
   
  
### OIE for downstream applications

OIE's output has been shown to be a useful input for many downstream tasks. In this section, several downstream tasks that benefited from OIE output are listed. 

#### Question Answering

* [*"Guiding the Growth: Difficulty-Controllable Question Generation through Step-by-Step Rewriting"*](https://aclanthology.org/2021.acl-long.465/) - ACL 2021

   Yi Cheng, Siyao Li, Bang Liu, Ruihui Zhao, Sujian Li, Chenghua Lin, Yefeng Zheng

* [*"Assertion-based QA with Question-Aware Open Information Extraction"*](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/download/16705/16170) AAAI 2018

  Zhao Yan, Duyu Tang, Nan Duan, Shujie Liu, Wendi Wang, Daxin Jiang, Ming Zhou, Zhoujun Li

* *["Answering Complex Questions Using Open Information Extraction"](http://ai2-website.s3.amazonaws.com/publications/TupleInf_ACL17.pdf)* - ACL 2017

  Tushar Khot, Ashish Sabharwal, Peter Clark

* [*"Paraphrase-Driven Learning for Open Question Answering"*](http://www.aclweb.org/anthology/P13-1158) ACL 2013 

  Anthony Fader, Luke S. Zettlemoyer, Oren Etzioni
  
#### Slot Filling

* [*"Open Information Extraction to KBP Relations in 3 Hours"*](https://pdfs.semanticscholar.org/d431/81fa9af5440360d4055e1ce7ddaaa6e82d77.pdf) - TAC 2013

  Stephen Soderland, John Gilmer, Robert Bart, Oren Etzioni, Daniel S. Weld
  
* *["Leveraging Linguistic Structure For Open Domain Information Extraction"](https://nlp.stanford.edu/pubs/2015angeli-openie.pdf)* - ACL 2015 ([code (Java)](https://stanfordnlp.github.io/CoreNLP/openie.html), [code (Python)](https://github.com/philipperemy/Stanford-OpenIE-Python))

  Gabor Angeli, Melvin Jose Johnson Premkumar, Christopher D. Manning
  
* *["University of Washington System for 2015 KBP Cold Start Slot Filling"](https://www.cs.rochester.edu/u/gkim21/papers/UWashington-KBP2015.pdf)* - TAC 2015

   Stephen Soderland, Natalie Hawkins, Gene L. Kim, Daniel S. Weld
   
* *["Combining Open IE and Distant Supervision for KBP Slot Filling"](https://tac.nist.gov/publications/2015/participant.papers/TAC2015.UWashington.proceedings.pdf)* - TAC 2015

   	Stephen Soderland, Natalie Hawkins, John Gilmer, Daniel S. Weld
   
* *["Open Relation Extraction and Grounding"](https://www.aclweb.org/anthology/I17-1086/)* -  IJCNLP 2017

   Dian Yu, Lifu Huang, Heng Ji


#### Event Extraction

* [*"Generating Coherent Event Schemas at Scale"*](http://turing.cs.washington.edu/papers/emnlp-2013-niranjan.pdf) - EMNLP 2013

  Niranjan Balasubramanian, Stephen Soderland, Mausam, Oren Etzioni

* [*"Cross-document Event Identity via Dense Annotation"*](https://aclanthology.org/2021.conll-1.39/) - CoNLL 2021

   Adithya Pratapa, Zhengzhong Liu, Kimihiro Hasegawa, Linwei Li, Yukari Yamakawa, Shikun Zhang, Teruko Mitamura

#### Text Summarization

* [*"Facts That Matter"*](http://aclweb.org/anthology/D18-1129) - EMNLP 2018

  Marco Ponza, Luciano Del Corro, Gerhard Weikum
  
* [*"Coherence and Salience-Based Multi-Document Relationship Mining"*](https://www.researchgate.net/publication/332735453_Coherence_and_Salience-Based_Multi-Document_Relationship_Mining) - APWeb-WAIM 2019

   Yongpan Sheng, Zenglin Xu
   
* [*"FAR-ASS: Fact-aware reinforced abstractive sentence summarization"*](https://www.sciencedirect.com/science/article/abs/pii/S0306457320309675) - Information Processing & Management 2021

   Mengli Zhanga, Gang Zhoua, Wanting Yua, Wenfen Liu
   
* [*"Summary Explorer: Visualizing the State of the Art in Text Summarization"*](https://aclanthology.org/2021.emnlp-demo.22/) - EMNLP 2021

   Shahbaz Syed, Tariq Yousef, Khalid Al Khatib, Stefan Jänicke, Martin Potthast

   
* [*"Generating Query Focused Summaries from Query-Free Resources"*](https://aclanthology.org/2021.acl-long.475/) - ACL 2021

   Yumo Xu, Mirella Lapata
   
* [*"Focus on the Action: Learning to Highlight and Summarize Jointly for Email To-Do Items Summarization"*](https://aclanthology.org/2022.findings-acl.323/) - ACL 2022

   Kexun Zhang, Jiaao Chen, Diyi Yang

   
#### Knowledge Base Population

* [*"Pocket Knowledge Base Population"*](https://www.cs.jhu.edu/~mdredze/publications/2017_acl_pocket_kb.pdf) - ACL 2017

  Travis Wolfe, Mark Dredze, Benjamin Van Durme
  
* [*KBPearl: A Knowledge Base Population System Supported by Joint Entity and Relation Linking"*](http://www.vldb.org/pvldb/vol13/p1035-lin.pdf) - PVLDB 2020

  Xueling Lin, Haoyang Li, Hao Xin, Zijian Li, Lei Chen
  
#### Knowledge Base Construction

* *["The Role of "Condition": A Novel Scientific Knowledge Graph Representation and Construction Model"](https://dl.acm.org/doi/10.1145/3292500.3330942)* - KDD 2019

   Tianwen Jiang, Tong Zhao, Bing Qin, Ting Liu, Nitesh V. Chawla, Meng Jiang
   
#### Entity Linking

* [*"TENET: Joint Entity and Relation Linking with Coherence Relaxation"*](https://dl.acm.org/doi/abs/10.1145/3448016.3457280) - SIGMOD 2021

    Xueling Lin, Lei Chen, Chaorui Zhang
    
#### Relation Linking

* [*"TENET: Joint Entity and Relation Linking with Coherence Relaxation"*](https://dl.acm.org/doi/abs/10.1145/3448016.3457280) - SIGMOD 2021

    Xueling Lin, Lei Chen, Chaorui Zhang
   
#### Open Link Prediction

* [*"OKGIT: Open Knowledge Graph Link Prediction with Implicit Types"*](https://aclanthology.org/2021.findings-acl.225/) - ACL 2021

   	Chandrahas, Partha Pratim Talukdar
    
* [*"Can We Predict New Facts with Open Knowledge Graph Embeddings? A Benchmark for Open Link Prediction"*](https://www.aclweb.org/anthology/2020.acl-main.209/) ([resources](https://www.uni-mannheim.de/dws/research/resources/olpbench/), [video](https://slideslive.com/38929433/can-we-predict-new-facts-with-open-knowledge-graph-embeddings-a-benchmark-for-open-link-prediction)) - ACL 2020

   Samuel Broscheit, Kiril Gashteovski, Yanjie Wang, Rainer Gemulla

#### Relating Entities

* [*"Relating Legal Entities via Open Information Extraction"*](https://link.springer.com/chapter/10.1007/978-3-030-14401-2_17) - MTSR 2018
  
  Giovanni Siragusa, Rohan Nanda, Valeria De Paiva, Luigi Di Caro
  
#### Video Grounding

* *["Interventional Video Grounding With Dual Contrastive Learning"](https://openaccess.thecvf.com/content/CVPR2021/papers/Nan_Interventional_Video_Grounding_With_Dual_Contrastive_Learning_CVPR_2021_paper.pdf)* - CVPR 2021

  Guoshun Nan, Rui Qiao, Yao Xiao, Jun Liu, Sicong Leng, Hao Zhang, Wei Lu
  
### OIE in Different Languages

Most of the OIE systems are focused on extractions made from text written on English. However, some OIE systems either are focused on a language other than English, or are multilingual. In this section, OIE systems on languages other than English or multilingual OIE systems are listed. 

#### Multilingual OIE Systems

* [*"MILIE: Modular & Iterative Multilingual Open Information Extraction"*](https://aclanthology.org/2022.acl-long.478/) - ACL 2022 

   Bhushan Kotnis, Kiril Gashteovski, Daniel Rubio, Ammar Shaker, Vanesa Rodriguez-Tembras, Makoto Takamoto, Mathias Niepert, Carolin Lawrence
   
* [*Alignment-Augmented Consistent Translation for Multilingual Open Information Extraction"*](https://aclanthology.org/2022.acl-long.179/) - ACL 2022 ([code](https://github.com/dair-iitd/moie))

   Keshav Kolluru, Muqeeth Mohammed, Shubham Mittal, Soumen Chakrabarti, Mausam

* [*"DetIE: Multilingual Open Information Extraction Inspired by Object Detection"*](https://www.aaai.org/AAAI22Papers/AAAI-8073.VasilkovskyM.pdf) - AAAI 2022 ([code](https://github.com/sberbank-ai/DetIE)

   Michael Vasilkovsky, Anton Alekseev, Valentin Malykh, Ilya Shenbin, Elena Tutubalina, Dmitriy Salikhov, Mikhail Stepnov, Andrey Chertok, Sergey I. Nikolenko


* [*"Multi2OIE: Multilingual Open Information Extraction based on Multi-Head Attention with BERT"*](https://arxiv.org/pdf/2009.08128.pdf) ([code](https://github.com/youngbin-ro/Multi2OIE)) - EMNLP 2020

  Youngbin Ro, Yukyung Lee, Pilsung Kang

* *["LOREM: Language-consistent Open Relation Extraction from Unstructured Text"](https://repository.tudelft.nl/islandora/object/uuid%3A3d9cfa08-4a7f-41cc-afdd-a8902094228c)* ([code](https://github.com/tomharting/LOREM)) - WWW 2020

   Tom Harting, Sepideh Mesbah, Christoph Lofi
   
* *[Explainable OpenIE Classifier with Morpho-syntactic Rules"](http://ceur-ws.org/Vol-2693/paper1.pdf)* - HI4NLP@ECAI 2020 

   Bruno Cabral, Marlo Souza, Daniela Barreiro Claro

* [*"Multilingual Open Information Extraction: Challenges and Opportunities"*](https://www.preprints.org/manuscript/201905.0029/download/final_file) -  Information 10(7): 228, 2019

   Daniela Barreiro Claro, Marlo Souza, Clarissa Castellã Xavier, Leandro Souza de Oliveira

* [*"Multilingual Open Relation Extraction Using Cross-lingual Projection"*](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/43449.pdf) - HLT-NAACL 2015

  Manaal Faruqui, Shankar Kumar
  
* *["MT/IE: Cross-lingual Open Information Extraction with Neural Sequence-to-Sequence Models"](http://www.aclweb.org/anthology/E17-2011)* - EACL 2017 ([code](https://github.com/sheng-z/cross-lingual-open-ie))
  	
  Kevin Duh, Benjamin Van Durme, Sheng Zhang

* [*"Multilingual Open Information Extraction"*](https://gramatica.usc.es/~gamallo/artigos-web/EPIA2015.pdf) - EPIA 2015

  Pablo Gamallo, Marcos García

#### OIE Systems for German Language

* [*"GerIE - An Open Information Extraction System for the German Language"*](http://www.jucs.org/jucs_24_1/gerie_an_open_information/jucs_24_01_0002_0024_bassa.pdf) - J. UCS 2018

  Akim Bassa, Mark Kröll, Roman Kern
  
* [*"Porting an Open Information Extraction System from English to German"*](https://aclweb.org/anthology/D16-1086) - EMNLP 2016 ([code](https://github.com/UKPLab/props-de))

  Tobias Falke, Gabriel Stanovsky, Iryna Gurevych, Ido Dagan

#### OIE Systems for Portugese Language

* [*"Challenges of an Annotation Task for Open Information Extraction in Portuguese"*](https://link.springer.com/chapter/10.1007/978-3-319-99722-3_7) - PROPOR 2018

  Rafael Glauber, Leandro Souza de Oliveira, Cleiton Fernando Lima Sena, Daniela Barreiro Claro, Marlo Souza

* [*"Inference Approach to Enhance a Portuguese Open Information Extraction"*](http://www.scitepress.org/Papers/2017/63382/63382.pdf) - ICEIS 2017
  
  Cleiton Fernando Lima Sena, Rafael Glauber, Daniela Barreiro Claro
  
* [*"DependentIE: An Open Information Extraction system on Portuguese by a Dependence Analysis"*](https://www.researchgate.net/profile/Rafael_Glauber/publication/324759625_DependentIE_An_Open_Information_Extraction_system_on_Portuguese_by_a_Dependence_Analysis/links/5ae0e48faca272fdaf8d8979/DependentIE-An-Open-Information-Extraction-system-on-Portuguese-by-a-Dependence-Analysis.pdf) - ENIAC 2017

  Leandro Souza de Oliveira, Rafael Glauber, Daniela Barreiro Claro
  
#### OIE Systems for Spanish Language

* *["Open Information Extraction for Spanish Language based on Syntactic Constraints"](https://www.aclweb.org/anthology/P14-3011.pdf)* - ACL (Student Research Workshop) (2014)

  Alisa Zhila, Alexander Gelbukh
  
#### OIE Systems for Chinese Language

* *["ZORE: A Syntax-based System for Chinese Open Relation Extraction"](http://aclweb.org/anthology/D14-1201)* - EMNLP 2014

  Likun Qiu, Yue Zhang
  
* *["Chinese Open Relation Extraction and Knowledge Base Establishment"](https://ai2-website.s3.amazonaws.com/publications/10094_Paper.pdf)* - ACM Trans. Asian & Low-Resource Lang. Inf. Process. 2018 ([slides](https://hong.xmu.edu.cn/__local/B/68/C0/92B8F8DC6AC06A3F256E1FE1A6F_9556CC90_4CCA5D.pdf?e=.pdf), [code](https://github.com/lemonhu/open-entity-relation-extraction))

  Shengbin Jia, Shijia E, Maozhen Li, Yang Xiang
  
* *["Open Relation Extraction for Chinese Noun Phrases"](https://ieeexplore.ieee.org/abstract/document/8903488)* - TKDE 2019

   Chengyu Wang, Xiaofeng He, Aoying Zhou
   
* *["Chinese Open Relation Extraction with Pointer-Generator Networks"](https://ieeexplore.ieee.org/abstract/document/9172882/references#references)* - DSC 2020

   Ziheng Cheng, Xu Wu, Xiaqing Xie, Jingchen Wu
   
* [*"Multi-Grained Dependency Graph Neural Network for Chinese Open Information Extraction"*](https://link.springer.com/content/pdf/10.1007/978-3-030-75768-7_13.pdf) - PAKDD 2021

   Zhiheng Lyu, Kaijie Shi, Xin Li, Lei Hou, Juanzi Li, Binheng Song
  
#### OIE Systems for Persian Language

* [*"RePersian:An Efficient Open Information Extraction Tool in Persian"*](https://ieeexplore.ieee.org/abstract/document/9122301/authors#authors) - ICWR 2020

  Raana Saheb-Nassagh, Majid Asgari, Behrouz Minaei-Bidgoli

* [*"A recursive algorithm for open information extraction from Persian texts"*](https://www.researchgate.net/publication/325977333_A_recursive_algorithm_for_open_information_extraction_from_Persian_texts) - IJCAT 2018

  Mahmoud Rahat, Alireza Talebpour, Seyedamin Monemian
  
* [*"Open information extraction as an intermediate semantic structure for Persian text summarization"*](https://link.springer.com/article/10.1007/s00799-018-0244-z) - Int. J. on Digital Libraries (2018)

  Mahmoud Rahat, Alireza Talebpour
  
* [*"Parsa: An open information extraction system for Persian"*](https://academic.oup.com/dsh/article/33/4/874/4951677) - DSH 2018

  Mahmoud Rahat, Alireza Talebpour
  
#### OIE Systems for Italian Language

* *["Lexicon-Grammar based Open Information Extraction from Natural Language Sentences in Italian"](https://www.sciencedirect.com/science/article/pii/S0957417419306724)* - Expert Systems and Applications 2019

   Raffaele Guarasci, Emanuele Damiano, Aniello Minutolo, Massimo Esposito, Giuseppe De Pietro
   
* [*"Towards a gold standard dataset for Open Information Extraction in Italian"*](https://ieeexplore.ieee.org/abstract/document/8931822) - SNAMS 2019

   Raffaele Guarasci, Emanuele Damiano, Aniello Minutolo, Massimo Esposito
   
#### OIE Systems for Indonesian Language

* *[Rule-based Indonesian Open Information Extraction"](https://ieeexplore.ieee.org/document/8541293)* - ICAICTA 2018 

  Ade Romadhony, Ayu Purwarianti, Dwi H. Widyantoro
  
#### OIE Systems for Greek Language

* *[PENELOPIE: Enabling Open Information Extraction for the Greek Language through Machine Translation"](https://aclanthology.org/2021.eacl-srw.4/)* - Student Research Workshop @ EACL

   Dimitris Papadopoulos, Nikolaos Papadakis, Nikolaos Matsatsinis

### Supervised OIE

* [*"Supervised Open Information Extraction"*](https://aclweb.org/anthology/N18-1081) - NAACL-HLT 2018

  Gabriel Stanovsky, Julian Michael, Luke Zettlemoyer, Ido Dagan

* [*"Neural Open Information Extraction"*](https://arxiv.org/pdf/1805.04270.pdf) - ACL 2018

  Lei Cui, Furu Wei, Ming Zhou
  
* *["Logician: A Unified End-to-End Neural Approach for Open-Domain Information Extraction"](https://tianjun.me/static/essay_resources/RelationExtraction/Paper/2018_Logician_A_Unified_End-to-End_Neural_Approach_for_open_domain_IE(1).pdf)* - WSDM 2018

  Mingming Sun, Xu Li, Xin Wang, Miao Fan, Yue Feng, Ping Li
  
* [*"Logician and Orator: Learning from the Duality between Language and Knowledge in Open Domain"*](https://www.aclweb.org/anthology/D18-1236) - EMNLP 2018

   Mingming Sun, Xu Li, Ping Li
   
* *["Supervising Unsupervised Open Information Extraction Models"](https://www.aclweb.org/anthology/D19-1067.pdf)* - EMNLP 2019

   Arpita Roy, Youngja Park, Taesung Lee and Shimei Pan
   
* [*"Contextualized Word Embeddings in a Neural Open Information Extraction Model"*](https://link.springer.com/chapter/10.1007/978-3-030-23281-8_31) - NLDB 2019

   Injy Sarhan, Marco R. Spruit

* [*"Weakly Supervised, Data-Driven Acquisition of Rules for Open Information Extraction"*](https://link.springer.com/chapter/10.1007/978-3-030-18305-9_2) - CAIAC 2019

   Fabrizio GottiEmail, Philippe Langlais
   
* [*"Learning Open Information Extraction of Implicit Relations from Reading Comprehension Datasets"*](https://arxiv.org/abs/1905.07471) - CoRR 2019

   Jacob Beckerman, Theodore Christakis
   
* *["Span Model for Open Information Extraction on Accurate Corpus"](https://arxiv.org/pdf/1901.10879.pdf)* ([code](https://github.com/zhanjunlang/Span_OIE))- AAAI 2020
   
   Junlang Zhan, Hai Zhao
   
* *["Extracting Knowledge from Web Text with Monte Carlo Tree Search"](https://dl.acm.org/doi/abs/10.1145/3366423.3380010)* - WWW 2020

   Guiliang Liu, Xu Li, Jiakang Wang, Mingming Sun, Ping Li
   
* [*An Advantage Actor-Critic Algorithm with Confidence Exploration for Open Information Extraction"*](https://epubs.siam.org/doi/abs/10.1137/1.9781611976236.25) - SDM 2020

   Guiliang Liu, Xu Li, Miningming Sun, Ping Li
   
* [*"Hybrid Neural Tagging Model for Open Relation Extraction"*](https://arxiv.org/pdf/1908.01761.pdf) - CoRR 2020 ([data](https://github.com/TJUNLP/NSL4OIE))

   Shengbin Jia, Yang Xiang   
   
* [*"IMoJIE: Iterative Memory-Based Joint Open Information Extraction"*](https://www.aclweb.org/anthology/2020.acl-main.521/) ([code](https://github.com/dair-iitd/imojie)) - ACL 2020

   Keshav Kolluru, Samarth Aggarwal, Vipul Rathore, Mausam, Soumen Chakrabarti
   
* [*"OpenIE6: Iterative Grid Labeling and Coordination Analysis for Open Information Extraction"*](https://arxiv.org/abs/2010.03147) ([code](https://github.com/dair-iitd/openie6)) - EMNLP 2020

  Keshav Kolluru, Vaibhav Adlakha, Samarth Aggarwal, Mausam, Soumen Chakrabarti
   
* [*Systematic Comparison of Neural Architectures and Training Approaches for Open Information Extraction*](https://www.aclweb.org/anthology/2020.emnlp-main.690) - EMNLP 2020

   Patrick Hohenecker, Frank Mtumbuka, Vid Kocijan, Thomas Lukasiewicz
   
* [*"Multi-Grained Dependency Graph Neural Network for Chinese Open Information Extraction"*](https://link.springer.com/content/pdf/10.1007/978-3-030-75768-7_13.pdf) - PAKDD 2021

   Zhiheng Lyu, Kaijie Shi, Xin Li, Lei Hou, Juanzi Li, Binheng Song

### Canonicalization of OIE

* *["Canonicalizing Open Knowledge Bases"](https://suchanek.name/work/publications/cikm2014.pdf)* - CIKM 2014

  Luis Galárraga, Geremy Heitz, Kevin Murphy, Fabian M. Suchanek
  
* *["CESI: Canonicalizing Open Knowledge Bases using Embeddings and Side Information"](https://dl.acm.org/citation.cfm?id=3186030)* - WWW 2018 ([code](https://github.com/malllabiisc/cesi))
  
  Shikhar Vashishth, Prince Jain, Partha Talukdar
  
* *["Towards Practical Open Knowledge Base Canonicalization"](https://dl.acm.org/citation.cfm?id=3271707)* - CIKM 2018

   Tien-Hsuan Wu, Zhiyong Wu, Ben Kao, Pengcheng Yin
  
* *["CaRe: Open Knowledge Graph Embeddings"](http://talukdar.net/papers/CaRe_EMNLP2019.pdf)* - EMNLP 2019 ([code](https://github.com/malllabiisc/CaRE))

   Swapnil Gupta, Sreyash Kenkre, Partha Talukdar
   
* *["Canonicalization of Open Knowledge Bases with Side Information from the Source Text"](https://ieeexplore.ieee.org/abstract/document/8731346)* - ICDE 2019

   Xueling Lin, Lei Chen
   
* *["MULCE: Multi-level Canonicalization with Embeddings of Open Knowledge Bases"](https://link.springer.com/chapter/10.1007/978-3-030-62005-9_23)* - WISE 2020

   Tien-Hsuan Wu, Ben Kao, Zhiyong Wu, Xiyang Feng, Qianli Song, Cheng Chen
   
* [*"Joint Open Knowledge Base Canonicalization and Linking"*](https://dl.acm.org/doi/abs/10.1145/3448016.3452776) - SIGMOD 2021

   	Yinan Liu, Wei Shen, Yuanfei Wang, Jianyong Wang, Zhenglu Yang, Xiaojie Yuan
   
* [*"Canonicalizing Open Knowledge Bases with Multi-Layered Meta-Graph Neural Network"*](https://arxiv.org/pdf/2006.09610.pdf) - CoRR 2020

   Tianwen Jiang, Tong Zhao, Bing Qin, Ting Liu, Nitesh V. Chawla, Meng Jiang


## Slides
* [\[pdf\] *"Compact Open Information Extraction on Large Corpora"*](https://www.uni-mannheim.de/media/Einrichtungen/dws/Files_People/Researchers/gashteovski/oie_nec_labs_gashteovski.pdf). Talk by Kiril Gashteovski given at NEC Labs Europe GmbH, 2019.
* [\[pdf\] *"(Information Extraction) Lecture 10 – Ontological and Open IE"*](http://www.cis.uni-muenchen.de/~fraser/information_extraction_2015_lecture/10_ontological_and_open_IE.pdf): A lecture on Open IE, which is part of the course ["Information Extraction"](http://www.cis.uni-muenchen.de/~fraser/information_extraction_2018_lecture/), by [Prof. Dr. Alexander Fraser](http://www.cis.uni-muenchen.de/~fraser/), from LMU München
* Open IE Tutorial: [Open Information Extraction for QA](https://www.slideshare.net/andrenfreitas/open-ie-tutorial-2018) by [André Freitas](http://andrefreitas.org/). Tutorial was presented on OKBQA 2018
* [\[pdf\] "Chinese Open Relation Extraction and Knowledge Base Establishment"](https://hong.xmu.edu.cn/__local/B/68/C0/92B8F8DC6AC06A3F256E1FE1A6F_9556CC90_4CCA5D.pdf?e=.pdf), 2018
* [\[pdf\] *"Brief Introduction and Review of Open Information Extraction (Open-IE) Systems"*](https://ece.umd.edu/~smiran/OpenIE.pdf). Project Presentation by Sina Miran.
* [\[pdf\] *"Open Information Extraction Systems and Downstream Applications"*](https://homes.cs.washington.edu/~mausam/papers/ijcai16-earlycareer.pdf) by [Prof. Mausam](http://www.cse.iitd.ernet.in/~mausam/). The talk was presented at [IJCAI 2016](http://ijcai-16.org/)
* [\[pptx\] *"Open Information Extraction from the Web"*](https://akbcwekex2012.files.wordpress.com/2012/06/slides-oren.pptx), presented by [Prof. Oren Etzioni](https://allenai.org/team/orene/). The tutorial was presented at [AKBC-WEKEX 2012](https://akbcwekex2012.wordpress.com/)
* [\[pdf\] *"ClausIE: Clause-Based Open Information Extraction"*](https://people.mpi-inf.mpg.de/~corrogg/publications/delcorro13clausie-slides.pdf) by [Luciano del Corro](https://people.mpi-inf.mpg.de/~corrogg/). 
* [\[pdf\] *"Open Information Extraction: the Second Generation"*](http://www.cse.iitd.ac.in/~mausam/courses/col864/spring2017/slides/03-openie.pdf)
* [\[pdf\] *"Open Information Extraction: Where Are We Going?"*](http://wwwusers.di.uniroma1.it/~dellibovi/talks/talk_OIE.pdf) by [Claudio Delli Bovi](http://wwwusers.di.uniroma1.it/~dellibovi/), 2016
* [\[pdf\] *"An Informativeness Approach to Open Information Extraction Evaluation"*](http://www-etud.iro.umontreal.ca/~lechellw/papers/2016-CICLING.pdf) by [William Léchelle](http://www-etud.iro.umontreal.ca/~lechellw/), 2016 


## Talks

* [*\[video\] "Open Information Extraction from the Web"*](https://www.youtube.com/watch?v=lMiLiPjGays&feature=youtu.be), by [Prof. Oren Etzioni](https://allenai.org/team/orene/), presented at [AKBC-WEKEX 2012](https://akbcwekex2012.wordpress.com/).
Slides: [\[pptx\]](https://akbcwekex2012.files.wordpress.com/2012/06/slides-oren.pptx)
* [*\[video\] "Open Information Extraction: Where Are We Going?"*](https://www.youtube.com/watch?v=EhOF_AbDwcE), by [Claudio Delli Bovi](http://wwwusers.di.uniroma1.it/~dellibovi/). The talk was given at AI2 in 2016. [Slides \[pdf\]](http://wwwusers.di.uniroma1.it/~dellibovi/talks/talk_OIE.pdf)
* [*\[video\] "Nested Propositions in Open Information Extraction"*](https://vimeo.com/239245885) by Nikita Bhutani at EMNLP 2016
* [*\[video\] "Creating a Large Benchmark for Open Information Extraction"*](https://vimeo.com/239251034) by Gabriel Stanovsky at EMNLP 2016  
* [*\[video\] "OpenCeres: When Open Information Extraction Meets the Semi-Structured Web"*](https://vimeo.com/355837778) by Colin Lockard at NAACL 2019 [slides \[pdf\]](https://homes.cs.washington.edu/~lockardc/OpenCeres_NAACL_talk.pdf)

## Code

* MinIE: Open Information Extraction System
  * [MinIE](https://github.com/uma-pi1/minie): originally written in Java
  * [Python wrapper for MinIE](https://github.com/mmxgn/miniepy)
  * [MinScIE](https://github.com/gkiril/MinSCIE) - an Open Information Extraction system which provides structured knowledge enriched with semantic information about citations (based on MinIE).
  * [SalIE](https://github.com/mponza/SalIE) - Salient Open Information Extraction (based on MinIE)
* ClausIE: Clause-based OIE
  * [ClausIE](https://www.mpi-inf.mpg.de/departments/databases-and-information-systems/software/clausie/): originally written in Java
  * [ClausIE (mavenized version)](https://github.com/IsaacChanghau/ClausIE)
  * [ClausIEpy](https://github.com/drwiner/ClausIEpy): Python wrapper for ClausIE
* OpenIE at IIT Delhi:
  * [OpenIE6](https://github.com/dair-iitd/openie6)
  * [IMoJIE](https://github.com/dair-iitd/imojie): a BERT-based OpenIE system
  * [OpenIE5](https://github.com/dair-iitd/OpenIE-standalone)
* OpenIE at UW:
  * [OLLIE](http://knowitall.github.io/ollie/)
  * [ReVerb](http://reverb.cs.washington.edu/)
* Stanford's OpenIE:
  * [Stanford OpenIE](https://nlp.stanford.edu/software/openie.html): Stanford's OpenIE system.
  * [Stanford OpenIE Spider](https://github.com/liaoziyang/OpenIE-Spider): Extract Information from WebCorpus using Stanford Open Information Extraction.
  * [Python wrapper for Stanford OpenIE](https://github.com/philipperemy/Stanford-OpenIE-Python): The unofficial cross-platform Python wrapper for the state-of-art information extraction library from Stanford University.
* [Graphene:](https://github.com/Lambda-3/Graphene) OpenIE system containing coreference resolution, simplification and open relation extraction pipeline
* [EXEMPLAR](https://github.com/U-Alberta/exemplar)
* [DefIE:](https://github.com/claudio-db/defIE) Open information extraction from textual definitions
* [ReMine:](https://github.com/GentleZhu/ReMine) Integrating Local and Global Cohesiveness for Open Information Extraction 
* OIE systems for languages other than English or cross-lingual systems:
   * [Zhopenie - Chinese OIE](https://github.com/tim5go/zhopenie): OIE system for **Chinese** language written in Python.
   * [Open Relation Extraction for Chinese](https://github.com/lemonhu/open-entity-relation-extraction): Knowledge triples extraction (entities and relations extraction) and knowledge base construction based on dependency syntax for open domain text (for **Chinese**)
   * [Baaz](https://github.com/sobhe/openie): Open information extraction from **Persian** web (Python)
   * [MT/IE](https://github.com/sheng-z/cross-lingual-open-ie): Cross-lingual Open IE. Attention-based sequence-to-sequence model for cross-lingual open IE. Written in Python
   * [Relation Extraction on German Websites](https://github.com/tabergma/relation-extraction): This repository holds a collection of three Open Information Extraction approaches for the **German** language
   * [DptOIE:](https://github.com/FORMAS/DptOIE) A **Portuguese** Open Information Extraction system based on Dependency Analysis
   * [PragmaticOIE:](https://github.com/FORMAS/PragmaticOIE) a rule-based approach to extract facts in **Portuguese** in a first pragmatic level
* [CORE:](https://github.com/fabiopetroni/CORE) Context-Aware Open Relation Extraction with Factorization Machines
* [CESI:](https://github.com/malllabiisc/cesi) Canonicalizing Open Knowledge Bases using Embeddings and Side Information
* [IMPLIE:](https://github.com/knowitall/implie) IMPLIE (IMPLicit relation Information Extraction) is a program that extracts binary relations from English sentences where the relationship between the two entities is not explicitly stated in the text.
* [Ranking:](https://github.com/jzbjyb/oie_rank) Iterative Rank-Aware Open IE (confidence score).


## Data

OIE output is used as a useful input in many other downstream tasks, such as question answering, event schema induction or generating inference rules. Moreover, OIE output can be used as a "fuel" to derive further resources. Here, the data is organized into two major categories: 1) OIE corpora; 2) Resources derived from OIE output.

### OIE corpora

* [OPIEC: An Open Information Extraction Corpus:](https://www.uni-mannheim.de/dws/research/resources/opiec/) the largest OIE corpus to date, containing more than 341M triples extracted from the entire English Wikipedia. Each triple from the corpus is composed of rich meta-data: each token from the subj / obj / rel along with NLP annotations (POS tag, NER tag, ...), provenance sentence along with the dependency parse, original (golden) left from Wikipedia, sentence order, space / time, etc.
* [\[.gz\] ReVerb extractions](http://reverb.cs.washington.edu/reverb_clueweb_tuples-1.1.txt.gz): 15 million high-precision  OIE extractions (826MB compressed) from the OIE system ReVerb. The extractions were made from the [ClueWeb09 corpus](https://lemurproject.org/clueweb09/). The data contains *(subject, relation, object)* triples, accompanied by a confidence score (estimating the likelihood of whether the triple was correctly  extracted) and provenance information (the link of the web-page where the triple was extracted from).
* [ReVerb extractions (linked)](http://knowitall.cs.washington.edu/linked_extractions/): 3 million triples with linked argument (a subset of the 15 M high-precision ReVerb extractions). The links (to Freebase) are provided by an entity linker. The data fields are: *argument 1, relation phrase, argument 2, freebase ID for argument 1 link, corresponding freebase entity name, link score, link ambiguity score*
* [PATTY](https://www.mpi-inf.mpg.de/departments/databases-and-information-systems/research/yago-naga/patty/): PATTY is a system that takes open relations between two arguments, structures them into relational synsets and then organizes the synsets into a taxonomy. This resource contains over 15M triples with disambiguated arguments (links to WikiPedia articles) and relation synset ID between them. Additionaly, the resource contains: 1) relation pattern synsets with type signatures; 2) relation pattern subsumptions; 3) relation paraphrases; 4) evaluation data;
* [WiseNet (1.0 and 2.0)](http://lcl.uniroma1.it/wisenet/): similarly as PATTY, WiseNet 1.0/2.0 is a source containing of OIE triples, where the arguments are disambiguated and the open relations are organized into relation synsets and then taxonomized. One of the main differences between PATTY and WiseNet is that WiseNet contains "golden links" for the arguments (annotated by humans) by keeping the original links from the WikiPedia articles.
* [KB-Unify](http://lcl.uniroma1.it/kb-unify/): KB-Unify takes as an input several OIE corpora and unifies them into a single disambiguated OIE repository. The open relations are organized into relational synsets and the arguments are disambiguated with BabelFy. 

### Resources derived from OIE output

* [Functional relations](http://knowitall.cs.washington.edu/leibniz/): 10K Functional relations. This resource comes from the paper [*"Identifying Functional Relations in Web Text"*](http://knowitall.cs.washington.edu/leibniz/paper.pdf), published on EMNLP 2010.
* [Entailment rules](http://u.cs.biu.ac.il/~nlp/resources/downloads/predicative-entailment-rules-learned-using-local-and-global-algorithms/): 10M predicative entailment rules learned using local and global algorithms. From the documentation: 
  "This resource of predicative entailment rules contains three resources in two formats – shallow and syntactic. Resources are learned over the REVERB data set and using the local and algorithms described in Chapter 5 of Jonathan Berant’s thesis (which is part of the package)."
* [Entailment rules](https://github.com/dair-iitd/kglr): 36K high precision entailment rules (data and code). The resource is the result of the work of Prachi Jain and Mausam [*"Knowledge-Guided Linguistic Rewrites for Inference Rule Verification"*](http://www.cse.iitd.ac.in/~mausam/papers/naacl16b.pdf) published on NAACL-HLT, 2016.

### PhD theses

* [*"Compact Open Information Extraction: Methods, Corpora, Analysis"*](https://madoc.bib.uni-mannheim.de/59813/1/thesis-kiril-gashteovski-final.pdf) by Kiril Gashteovski, University of Mannheim, Germany, 2020

* [*"Constructing Lexicons of Relational Phrases"*](https://publikationen.sulb.uni-saarland.de/bitstream/20.500.11880/26789/1/adam_grycner.pdf) by Adam Grycner, University of Saarland, Germany, 2017

* [*"Methods for open information extraction and sense disambiguation on natural language text"*](https://people.mpi-inf.mpg.de/~corrogg/publications/delcorro-thesis.pdf) by Luciano Del Corro, University of Saarland, Germany, 2016

* [*"Automated Knowledge Base Extension Using Open Information"*](https://ub-madoc.bib.uni-mannheim.de/40469/1/dutta.dissertation.pdf) by Arnab Kumar Dutta, University of Mannheim, Germany, 2015

* [*"Exploiting Knowledge in Unsupervised Open Information Extraction"*](https://search.proquest.com/docview/1372164047?pq-origsite=gscholar) by Yuval Merhav, Illinois Institute of Technology, USA, 2012

* [*"Open Information Extraction for the Web"*](http://turing.cs.washington.edu/papers/banko-thesis.pdf) by Michele Banko, University of Washington, USA, 2009

### Demos
* [ClausIE:](https://gate.d5.mpi-inf.mpg.de/ClausIEGate/ClausIEGate/) Demo for ClausIE, an OIE system.
* [Fact retrieval:](https://openie.allenai.org/) Fact retrieval with OpenIE on large corpora.
