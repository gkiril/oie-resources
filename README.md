# Open Information Extraction (OIE) Resources

A curated list of Open Information Extraction (OIE) resources: research papers, code, data, applications, etc. The list is not limited to Open Information Extraction systems exclusively. It also includes work highly related to the field of OIE, such as taxonomizing open relations and using OIE in downstream applications. 

* [Introduction to OIE](#introduction-to-oie)
* [Papers](#papers)
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
* [Slides](#slides)
* [Talks](#talks)
* [OIE for downstream applications](#oie-for-downstream-applications)
  * [Question Answering](#question-answering)
  * [Slot Filling](#slot-filling)
  * [Event Schema Induction](#event-schema-induction)
  * [Fact Salience](#fact-salience)
  * [Knowledge Base Population](#knowledge-base-population)
  * [Relating Entities](#relating-entities)
* [OIE in Different Languages](#oie-in-different-languages)
  * [OIE Systems for German Language](#oie-systems-for-german-language)
  * [OIE Systems for Portugese Language](#oie-systems-for-portugese-language)
  * [OIE Systems for Chinese Language](#oie-systems-for-chinese-language)
  * [OIE Systems for Persian Language](#oie-systems-for-persian-language)
* [Code](#code)
* [Data](#data)
  * [OIE corpora](#oie-corpora)
  * [Resources derived from OIE output](#resources-derived-from-oie-output)
* [PhD theses](#phd-theses)

## Introduction to OIE

Open Information Extraction (OIE) systems aim to extract unseen relations and their arguments from unstructured text in unsupervised manner. In its simplest form, given a natural language sentence, they extract information in the form of a triple, consisted of subject (S), relation (R) and object (O).

Suppose we have the following input sentence:

    AMD, which is based in U.S., is a technology company.

An OIE system aims to make the following extractions:

    ("AMD"; "is based in"; "U.S.")
    ("AMD"; "is"; "technology company")

## Papers

### 2007
* *["Open information extraction from the web"](https://www.aaai.org/Papers/IJCAI/2007/IJCAI07-429.pdf)* - IJCAI 2007
  
  Michele Banko,  Michael J. Cafarella, Stephen Soderland, Matthew Broadhead, Oren Etzioni
* *["Autonomously semantifying wikipedia"](http://turing.cs.washington.edu/papers/cikm07.pdf)* - CIKM 2007

  Fei Wu, Daniel S. Weld
  
* *["Unsupervised resolution of objects and relations on the web"](http://turing.cs.washington.edu/papers/object_identification_camera_ready_4.pdf)* - NAACL 2007

  Alexander Yates, Oren Etzioni
  
* *["TextRunner: Open Information Extraction on the Web"](https://tianjun.me/static/essay_resources/RelationExtraction/Paper/p25-yates.pdf)* -  HLT-NAACL 2007

  Alexander Yates, Michele Banko, Matthew Broadhead, Michael J. Cafarella, Oren Etzioni, Stephen Soderland
  
### 2008
* *["The tradeoffs between open and traditional relation extraction"](http://turing.cs.washington.edu/papers/acl08.pdf)* - ACL 2008

  Michele Banko, Oren Etzioni

* *["Open Knowledge Extraction through Compositional Language Processing"](https://www.cs.rochester.edu/~schubert/papers/open-knowledge-step08.pdf)* - STEP 2008

  Benjamin Van Durme, Lenhart K. Schubert

* *["Open information extraction from the web"](https://dl.acm.org/citation.cfm?id=1409378)* - Commun. ACM 2008

  Oren Etzioni, Michele Banko, Stephen Soderland, Daniel S. Weld
  
### 2009

* *["Using Wikipedia to bootstrap open information extraction"](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.143.4369&rep=rep1&type=pdf)* - SIGMOD 2009
  	
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
  
* *["Filtering and clustering relations for unsupervised information extraction in open domain"](https://perso.limsi.fr/bg/fichiers/2011/cikm0874-wang.pdf)* - CIKM 2011

  Wei Wang, Romaric Besançon, Olivier Ferret, Brigitte Grau

* *["An analysis of open information extraction based on semantic role labeling"](https://homes.cs.washington.edu/~mausam/papers/kcap11.pdf)* - K-CAP 2011

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
  
* *["Porting an Open Information Extraction System from English to German"](https://aclweb.org/anthology/D16-1086)* - EMNLP 2016

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

* *["MinIE: Minimizing Facts in Open Information Extraction"](http://aclweb.org/anthology/D17-1278)* - EMNLP 2017 ([code](https://github.com/gkiril/minie), [poster](https://dws.informatik.uni-mannheim.de/fileadmin/lehrstuehle/pi1/people/rgemulla/publications/gashteovski17minie-poster.pdf), [all resources](https://dws.informatik.uni-mannheim.de/en/resources/software/minie/))

  Kiril Gashteovski, Rainer Gemulla, Luciano Del Corro
  
* *["Answering Complex Questions Using Open Information Extraction"](http://ai2-website.s3.amazonaws.com/publications/TupleInf_ACL17.pdf)* - ACL 2017

  Tushar Khot, Ashish Sabharwal, Peter Clark
  
* *["Pocket Knowledge Base Population"](https://www.cs.jhu.edu/~mdredze/publications/2017_acl_pocket_kb.pdf)* - ACL 2017
  
  Travis Wolfe, Mark Dredze, Benjamin Van Durme
  
* *["Bootstrapping for Numerical Open IE"](https://homes.cs.washington.edu/~mausam/papers/acl17.pdf)* - ACL 2017

  Swarnadeep Saha, Harinder Pal, Mausam

* *["MT/IE: Cross-lingual Open Information Extraction with Neural Sequence-to-Sequence Models"](http://www.aclweb.org/anthology/E17-2011)* - EACL 2017 ([code](https://github.com/sheng-z/cross-lingual-open-ie))
  	
  Kevin Duh, Benjamin Van Durme, Sheng Zhang
    
* *["Syntactic Representation Learning for Open Information Extraction on Web"](https://dl.acm.org/citation.cfm?id=3041021.3054266)* - WWW 2017

  Chengsen Ru, Jintao Tang, Shasha Li, Ting Wang
    
* *["MetaPAD: Meta Pattern Discovery from Massive Text Corpora"](http://www.meng-jiang.com/pubs/metapad-kdd17/metapad-kdd17-paper.pdf)* ([code](https://github.com/mjiang89/MetaPAD))- KDD 2017

  Meng Jiang, Jingbo Shang, Taylor Cassidy, Xiang Ren, Lance M. Kaplan, Timothy P. Hanratty, Jiawei Han

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
  
### 2018

* *["Logician: A Unified End-to-End Neural Approach for Open-Domain Information Extraction"](https://tianjun.me/static/essay_resources/RelationExtraction/Paper/2018_Logician_A_Unified_End-to-End_Neural_Approach_for_open_domain_IE(1).pdf)* - WSDM 2018

  Mingming Sun, Xu Li, Xin Wang, Miao Fan, Yue Feng, Ping Li

* *["Assertion-Based QA With Question-Aware Open Information Extraction"](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/download/16705/16170)* - AAAI 2018
  	
  Zhao Yan, Duyu Tang, Nan Duan, Shujie Liu, Wendi Wang, Daxin Jiang, Ming Zhou, Zhoujun Li
  
* *["Neural Open Information Extraction"](http://aclweb.org/anthology/P18-2065)* - ACL 2018

  Lei Cui, Furu Wei, Ming Zhou
  
* *["Supervised Open Information Extraction"](http://www.aclweb.org/anthology/N18-1081)* - NAACL-HLT 2018
  	
  Gabriel Stanovsky, Julian Michael, Luke Zettlemoyer, Ido Dagan
  
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
  
* *["WiRe57 : A Fine-Grained Benchmark for Open Information Extraction"](https://arxiv.org/pdf/1809.08962.pdf)* - CoRR 2018

  William Léchelle, Fabrizio Gotti, Philippe Langlais
  
### 2019

* *["OPIEC: An Open Information Extraction Corpus"](https://openreview.net/pdf?id=HJxeGb5pTm)* - AKBC 2019 (to appear) 

  Kiril Gashteovski, Sebastian Wanner, Sven Hertling, Samuel Broscheit, Rainer Gemulla

* *["Integrating Local Context and Global Cohesiveness for Open Information Extraction"](https://arxiv.org/pdf/1804.09931.pdf)* - WSDM 2019 ([code](https://github.com/GentleZhu/ReMine))

  Qi Zhu, Xiang Ren, Jingbo Shang, Yu Zhang, Ahmed El-Kishky, Jiawei Han

* *"Open Information Extraction from Question-Answer Pairs"* - NAACL 2019 (to appear)

  Nikita Bhutani, Yoshihiko Suhara, Wang-Chiew Tan, Alon Halevy and H V Jagadish
  
* *"OpenKI: Integrating Open Information Extraction and Knowledge Bases with Relation Inference"* - NAACL 2019

  Dongxu Zhang, Subhabrata Mukherjee, Colin Lockard, Xin Luna Dong, Andrew McCallum
  
* *"When Open Information Extraction Meets the Semi-Structured Web"* - NAACL 2019

  Colin Lockard, Prashant Shiralkar and Xin Luna Dong (to appear)

* *["Span Based Open Information Extraction"](https://arxiv.org/pdf/1901.10879.pdf)* CoRR 2019
   
   Junlang Zhan, Hai Zhao

## Slides

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

## OIE for downstream applications

OIE's output has been shown to be a useful input for many downstream tasks. In this section, several downstream tasks that benefited from OIE output are listed. 

### Question Answering
* [*"Assertion-based QA with Question-Aware Open Information Extraction"*](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/download/16705/16170) AAAI 2018

  Zhao Yan, Duyu Tang, Nan Duan, Shujie Liu, Wendi Wang, Daxin Jiang, Ming Zhou, Zhoujun Li

* *["Answering Complex Questions Using Open Information Extraction"](http://ai2-website.s3.amazonaws.com/publications/TupleInf_ACL17.pdf)* - ACL 2017

  Tushar Khot, Ashish Sabharwal, Peter Clark

* [*"Paraphrase-Driven Learning for Open Question Answering"*](http://www.aclweb.org/anthology/P13-1158) ACL 2013 

  Anthony Fader, Luke S. Zettlemoyer, Oren Etzioni
  
### Slot Filling

* [*"Open Information Extraction to KBP Relations in 3 Hours"*](https://pdfs.semanticscholar.org/d431/81fa9af5440360d4055e1ce7ddaaa6e82d77.pdf) - TAC 2013

  Stephen Soderland, John Gilmer, Robert Bart, Oren Etzioni, Daniel S. Weld

### Event Schema Induction

* [*"Generating Coherent Event Schemas at Scale"*](http://turing.cs.washington.edu/papers/emnlp-2013-niranjan.pdf) - EMNLP 2013

  Niranjan Balasubramanian, Stephen Soderland, Mausam, Oren Etzioni

### Fact Salience

* [*"Facts That Matter"*](http://aclweb.org/anthology/D18-1129) - EMNLP 2018

  Marco Ponza, Luciano Del Corro, Gerhard Weikum
  
### Knowledge Base Population

* [*"Pocket Knowledge Base Population"*](https://www.cs.jhu.edu/~mdredze/publications/2017_acl_pocket_kb.pdf) - ACL 2017

  Travis Wolfe, Mark Dredze, Benjamin Van Durme

### Relating Entities

* [*"Relating Legal Entities via Open Information Extraction"*](https://link.springer.com/chapter/10.1007/978-3-030-14401-2_17) - MTSR 2018
  
  Giovanni Siragusa, Rohan Nanda, Valeria De Paiva, Luigi Di Caro
  
## OIE in Different Languages

Most of the OIE systems are focused on extractions made from text written on English. However, some OIE systems either are focused on a language other than English, or are multilingual. In this section, OIE systems on languages other than English or multilingual OIE systems are listed. 

### Multilingual OIE Systems

* [*"Multilingual Open Relation Extraction Using Cross-lingual Projection"*](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/43449.pdf) - HLT-NAACL 2015

  Manaal Faruqui, Shankar Kumar

* [*"Multilingual Open Information Extraction"*](https://gramatica.usc.es/~gamallo/artigos-web/EPIA2015.pdf) - EPIA 2015

  Pablo Gamallo, Marcos García

### OIE Systems for German Language

* [*"GerIE - An Open Information Extraction System for the German Language"*](http://www.jucs.org/jucs_24_1/gerie_an_open_information/jucs_24_01_0002_0024_bassa.pdf) - J. UCS 2018

  Akim Bassa, Mark Kröll, Roman Kern
  
* [*"Porting an Open Information Extraction System from English to German"*](https://aclweb.org/anthology/D16-1086) - EMNLP 2016

  Tobias Falke, Gabriel Stanovsky, Iryna Gurevych, Ido Dagan

### OIE Systems for Portugese Language

* [*"Challenges of an Annotation Task for Open Information Extraction in Portuguese"*](https://link.springer.com/chapter/10.1007/978-3-319-99722-3_7) - PROPOR 2018

  Rafael Glauber, Leandro Souza de Oliveira, Cleiton Fernando Lima Sena, Daniela Barreiro Claro, Marlo Souza

* [*"Inference Approach to Enhance a Portuguese Open Information Extraction"*](http://www.scitepress.org/Papers/2017/63382/63382.pdf) - ICEIS 2017
  
  Cleiton Fernando Lima Sena, Rafael Glauber, Daniela Barreiro Claro
  
* [*"DependentIE: An Open Information Extraction system on Portuguese by a Dependence Analysis"*](https://www.researchgate.net/profile/Rafael_Glauber/publication/324759625_DependentIE_An_Open_Information_Extraction_system_on_Portuguese_by_a_Dependence_Analysis/links/5ae0e48faca272fdaf8d8979/DependentIE-An-Open-Information-Extraction-system-on-Portuguese-by-a-Dependence-Analysis.pdf) - ENIAC 2017

  Leandro Souza de Oliveira, Rafael Glauber, Daniela Barreiro Claro
  
### OIE Systems for Chinese Language

* *["ZORE: A Syntax-based System for Chinese Open Relation Extraction"](http://aclweb.org/anthology/D14-1201)* - EMNLP 2014

  Likun Qiu, Yue Zhang
  
* *["Chinese Open Relation Extraction and Knowledge Base Establishment"](https://ai2-website.s3.amazonaws.com/publications/10094_Paper.pdf)* - ACM Trans. Asian & Low-Resource Lang. Inf. Process. 2018 ([slides](https://hong.xmu.edu.cn/__local/B/68/C0/92B8F8DC6AC06A3F256E1FE1A6F_9556CC90_4CCA5D.pdf?e=.pdf), [code](https://github.com/lemonhu/open-entity-relation-extraction))

  Shengbin Jia, Shijia E, Maozhen Li, Yang Xiang
  
### OIE Systems for Persian Language

* [*"A recursive algorithm for open information extraction from Persian texts"*](https://www.researchgate.net/publication/325977333_A_recursive_algorithm_for_open_information_extraction_from_Persian_texts) IJCAT 2018

  Mahmoud Rahat, Alireza Talebpour, Seyedamin Monemian
  
* [*"Open information extraction as an intermediate semantic structure for Persian text summarization"*](https://link.springer.com/article/10.1007/s00799-018-0244-z) - Int. J. on Digital Libraries (2018)

  Mahmoud Rahat, Alireza Talebpour
  
* [*"Parsa: An open information extraction system for Persian"*](https://academic.oup.com/dsh/article/33/4/874/4951677) - DSH 2018

  Mahmoud Rahat, Alireza Talebpour  

## Code

* MinIE: Open Information Extraction System
  * [MinIE](https://github.com/gkiril/minie): originally written in Java
  * [Python wrapper for MinIE](https://github.com/mmxgn/miniepy)
* ClausIE: Clause-based OIE
  * [ClausIE](https://www.mpi-inf.mpg.de/departments/databases-and-information-systems/software/clausie/): originally written in Java
  * [ClausIEpy](https://github.com/drwiner/ClausIEpy): Python wrapper for ClausIE
* [OpenIE 5.0](https://github.com/dair-iitd/OpenIE-standalone): the latest version of OpenIE at A2I.
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
* [CORE:](https://github.com/fabiopetroni/CORE) Context-Aware Open Relation Extraction with Factorization Machines
* [CESI:](https://github.com/malllabiisc/cesi) Canonicalizing Open Knowledge Bases using Embeddings and Side Information

## Data

OIE output is used as a useful input in many other downstream tasks, such as question answering, event schema induction or generating inference rules. Moreover, OIE output can be used as a "fuel" to derive further resources. Here, the data is organized into two major categories: 1) OIE corpora; 2) Resources derived from OIE output.

### OIE corpora

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

* [*"Methods for open information extraction and sense disambiguation on natural language text"*](https://people.mpi-inf.mpg.de/~corrogg/publications/delcorro-thesis.pdf) by Luciano Del Corro, University of Saarland, Germany, 2016

* [*"Automated Knowledge Base Extension Using Open Information"*](https://ub-madoc.bib.uni-mannheim.de/40469/1/dutta.dissertation.pdf) by Arnab Kumar Dutta, University of Mannheim, Germany, 2015

* [*"Open Information Extraction for the Web"*](http://turing.cs.washington.edu/papers/banko-thesis.pdf) by Michele Banko, University of Washington, USA, 2009
