---
layout: post
title: How do we form past tense forms in English?
---

How do we form past tense forms? Do we memorize them or is there a rule based processing involved? Can we model this aspect of language processing?

## Introduction
For fifteen years, the English past tense has been the subject of a debate on the nature of language processing. The debate began with the report of a connectionist model by Rumelhart and McClelland [1] and a critique by Pinker and Prince [2], and has since been the subject of many papers, conferences and simulation models.
Regular inflection, as in walk-walked and play-played, applies predictably to thousands of verbs and is productively generalized to neologisms such as spam-spammed and mosh-moshed, even by preschool children. Irregular inflection, as in come-came and feel-felt, applies in unpredictable ways to some 180 verbs, and is seldom generalized; rather, the regular suffix is often overgeneralized by children to these irregular forms, as in holded  and breaked.
There are two competing hypotheses regarding the generation of these past-tense forms : Words-and-Rules by Pinker et al. and Connectionist Model by McClelland and Patterson.
Words-and-Rules theory posits that in the context of english past tense we have a hypothesis that it works on two different kinds of routes which are interconnected.
The lexicon is a subdivision of memory containing (among other things) the thousands of arbitrary sounds–meaning pairings that underlie the morphemes and simple words of a language.
The grammar is a system of productive, combinatorial operations that assemble morphemes and simple words into complex words, phrases and sentences.

In the Connectionist Model by McCleland, Paterson, the authors posit a single all encompassing hypothesis for the formation of past tense forms by using a connectionist approach, in which individual forms are broken down into sounds, and a representation of the sound and its position is formed in the form of wickel features. Inflection happens by association with wickel features.

### Modular vs Probabilistic

- Modular (as per WR model)

Modularity refers to the idea that there are self-contained areas in the brain that store mental processes such as the "lower level" reflexes. Refers to a specialized sub-unit to resolve cognitive tasks. Linked with the idea of some innate neural correlates for specific functions.

Ullman and colleagues have recently extended the WR theory to a hypothesis about the neurocognitive substrate of lexicon and grammar.

According to the Declarative/Procedural (DP) hypothesis, lexical memory is a subdivision of declarative memory, which stores facts, events and arbitrary relations .
The consolidation of new declarative memories requires medial-temporal lobe structures, in particular the hippocampus.

Long-term retention depends largely on neocortex, especially temporal and temporo-parietal regions; other structures are important for actively retrieving and searching for these memories.

Grammatical processing, by contrast, depends on the procedural system, which underlies the learning and control of motor and cognitive skills, particularly those involving sequences . It is subserved by the basal ganglia, and by the frontal cortex to which they project – in the case of language, particularly Broca’s area and neighboring anterior cortical regions.

Irregular forms must be stored in the lexical portion of declarative memory; regular past-tense forms can be computed in the grammatical portion of the procedural system.

The brain processes regular forms like syntactic combinations and irregular forms like words - indicating specificity in the processing modules.

Examples: Anomia: swimmed from swim, (swam) - retrieval errors
Agrammatism: regularization errors, lack of errors in retrieval

(Pinker and Ullman, 2002)

![Past Tense1]({{ site.baseurl }}/posts/images/pt1.png?raw=true "Past Tense 1")




- Probabilistic (as per connectionist model):

Pinker's theory rejected the role of meaning in selection of past tense forms. However, the authors have argued that, the influence of meaning in selection of past tense forms (be it regular or irregular) must be taken into account. In a recent study by Ramscar, he placed nonce verbs like ‘frink’ into semantic contexts that encouraged an interpretation resembling either ‘drink’ or ‘blink’ & “wink”. "frink" is a nonce word. In a neutral condition, with no semantic context, participants preferred irregular past tenses, and this trend persisted when context provided a meaning for the nonce verb similar to that of drink. When the context suggested a meaning similar to regular ’wink’ or ’blink’, or even to the regular word ’mediate’, participants shifted to the regular past tense, suggesting that use of the regular past tense can be influenced by semantics. So, participants acquired the past tense of ‘frink’ as either ‘frank’ or ‘frinked’ depending on the context in which the stem ‘frink’ was being used.
So, given that meaning carries a weight in past tense formation, the model should be more probabilistic than modular.
Brown mentions that learning of the inflections is probabilistic as and when required. The analysis of whether the overregularization is sudden leads them to conclude that it's actually gradual and the acquisition is more suited to a probabilistic model(Bayesian).

### Symbolic vs Distributed

- Symbolic (as per WR Model)

The dual route is considered symbolic in approach, as the symbols and representations  are distinct as compared to the single route connectionist approach wherein the matrix of weights represents the information in a distributed way, which is similar for all the inputs.

Eg. The symbolic route is insensitive to the phonological structure of the word and applies the general rule ("ed") in case of regulars.
“The regular route is symbolic because it is impervious to the phonological content of the particular word stem: It simply adds an /ed/ to whatever word it encounters. The irregular route, in contrast, needs to pay attention to the phonological content of the word stem in order to identify whether the current word is a candidate for irregular inflection. Rather than applying a rule, it associates that particular word stem with its irregular past tense form.”

Analogy can be derived from symbolic systems in AI as they are rules and logic based as well. In the WR model, the words are the symbols.


Sources:
https://msu.edu/course/lin/463/ss04/dr.html
https://www.sltinfo.com/modularity-of-cognitive-processes/


- Distributive Viewpoint (as per Connectionist viewpoint)

As opposed to Pinker's theory (which emphasised on word / symbol manipulations at large), connectionist models propose that not whole words / symbols undergo manipulations, rather a select constituent phonemes within those words undergo manipulations based on weights assigned to them. Thus, past tense formation is more of a distributive process rather than symbolic, as distributively weighted constituent phonemes undergo change to form a past tense, and not whole words or symbols.

The learning process is influenced by associations in the Wickelfeature properties e.g. a combination like /eep/ is associated with /ept/ getting us crept, slept, kept for creep, sleep and keep.

### Innate vs Gradually Acquired

- Innate (as per WR Model)

Innatism is a philosophical and epistemological doctrine that holds that the mind is born with ideas/knowledge, and that therefore the mind is not a "blank slate" at birth.

The Words and Rules (WR) theory claims that the regular–irregular distinction is an epiphenomenon of the design of the human language faculty, in particular, the distinction between lexicon and grammar made in most traditional theories of language. (Pinker and Ullman, 2002)
Examples: run and runn-ed, hold and hold-ed; where the irregular forms are ran and held.
(Connectionists claimed that robust generalization depends on regular forms constituting the majority of forms in the child’s input) However,the onset and rate of overregularization errors in children do not correlate with changes in the number or proportion of regular verbs used by parents.

- Gradual acquisition (as per Connectionist model)

Marcus et al. suggested that the first over-regularisation in each child’s corpus signals the moment of acquisition of the past tense rule, and state that this over-regularisation error is followed by “rapid increases in inflecting regulars to high levels shortly afterward. Adam’s first over-regularization occurred during a 3-month period in which regular marking increased from 0 to 100%
Considering the data presented by Marcus et al. , Hoeffner noted that one could just easily say that “Adam’s first over-regularization occurred during a six-month period in which the probability of using the regular ... rose gradually from 24 to 44%”. Either statement seems fairly arbitrary; the data are noisy, and spikes occur when relatively few observations were available (Adam’s 100% marking at 37 months is based on 8 observations). Given the noise, the graphs from all three children suggest a process that proceeds from very little marking in obligatory contexts to fairly reliable marking over the course of about one year. A good fit to the data was achieved with a logistic regression in which the use of the regular past increases monotonically with age. Use of first over-regularization as a predictor did not reliably improve the account for regularization rates in any of the children.
Moreover, the notion for past tense forms and grammar in general being “gradually acquired” rather than innate, finds support from Bayesian line of thought. "Gradually acquired" and "Probabilistic" can be related together since in Bayesian models, the beliefs are updated in light of new evidence which is a gradual process. Also, in ANN the networks are trained with the incoming data which is also a gradual process.

### Domain Specific vs Domain General

- Domain specific (as per WR Model)

Certain cognitive functions are responsible for specific functions, related to modularity. Different types of information are learned differently.

An intriguing aspect of inflection is that irregular forms can sometimes turn up in regular form. Some of these regularizations are unsystematic –
For example, doublets such as dived/dove and dreamt/dreamed, in which the regular form is used sporadically because the irregular form is low in frequency and hence poorly remembered.
But many are systematic: in particular contexts, the regular form is consistently used, such as ringed the city and low-lifes.


The Words-and-Rules theory explains this phenomenon using an independently motivated theory of compositionality in word-formation [a,b] (see also Fig. 2 in main article).

Irregular-sounding words are regularized if they lack a root in the head position that can be marked for the inflectional feature (tense or number). The regular suffix applies as the default, as it does in other cases where memory access is disabled. This neatly explains a diverse set of systematic regularizations found in actual usages, laboratory experiments with adults and children, and many languages [c–f]:

![Past Tense2]({{ site.baseurl }}/posts/images/pt2.png?raw=true "Past Tense 2")

(Pinker and Ullman, 2002)

- Domain General (as per Connectionist Model)

As the authors have described in the paper, connectionist models inherently capture the regularity in the exceptions because the exceptions are processed by the same network that processes the regulars, which is in stark contrast to the rule-based hypothesis put forth by Pinker & Ullman.
All nine of the types noted in the paper, encompassing 177/181 forms, exploit to some degree the connection weights that produce regular items. Even the irregularities have some regularities in them, (quasi-regular) which a connectionist model identifies and outputs the valid result.  

## Conclusion :

The Past Tense debate continues to rage on, with new research coming up in support of each viewpoint, quite a distance from being resolved. Future direction of debate might be shaped by new evidence in the light of factors such as efficiency, biological plausibility, and cross-lingual studies.
