# DATASCI W266: Natural Language Processing with Deep Learning

[Course Overview](#course-overview)  
[Grading](#grading)  
[Final Project](#final-project)  
[Course Resources](#course-resources)  
[Schedule and Readings](#schedule-and-readings)  

* [Piazza](https://piazza.com/berkeley/spring2020/datasciw266) - we'll use this for Q&A, and this will be the fastest way to reach the course staff. Note that you can post anonymously, and/or make posts visible only to instructors for private questions.

## Course Overview
Understanding language is fundamental to human interaction. Our brains have evolved language-specific circuitry that helps us learn it very quickly; however, this also means that we have great difficulty explaining how exactly meaning arises from sounds and symbols. This course is a broad introduction to linguistic phenomena and our attempts to analyze them with machine learning. We will cover a wide range of concepts with a focus on practical applications such as information extraction, machine translation, sentiment analysis, and summarization.

**Prerequisites:**
* Language: All assignments will be in Python using Jupyter notebooks, NumPy, and TensorFlow.
* Time:  There are 6-7 substantial assignments in this course as well as a term project.  Make sure you give yourself enough time to be successful! In particular, you may be in for a rough semester if you have other significant commitments at work or home, or take both this and any of 210 (Capstone), 261, or 271 :)
* [MIDS 207 (Machine Learning)](https://www.ischool.berkeley.edu/courses/datasci/207): We assume you know what gradient descent is.  We'll review simple linear classifiers and softmax at a high level, but make sure you've at least heard of these! You should also be comfortable with linear algebra, which we'll use for vector representations and when we discuss deep learning.

**Contacts and resources:**
* Course website: [GitHub datasci-w266/2020-spring-main](../../../)
* [Piazza](https://piazza.com/berkeley/spring2020/datasciw266) - we'll use this for Q&A, and this will be the fastest way to reach the course staff. Note that you can post anonymously, and/or make posts visible only to instructors for private questions.
* Email list for course staff (expect a somewhat slower response here): [mids-nlp-instructors@googlegroups.com](mailto:mids-nlp-instructors@googlegroups.com)

**Live Sessions:**
* (Section 1) Tuesday 4 - 5:30p Pacific (Daniel Cer)
* (Section 2) Wednesday 6:30 - 8p Pacific (Mike Tamir)
* (Section 3) Thursday 4 - 5:30p Pacific (Mark Butler, Matthew Sims)
* (Section 98) Friday 2 - 3:30p Pacific (Matthew Sims)
* (Section 99) Friday 4 - 5:30p Pacific (Matthew Sims)
* (Section 4) Friday 4 - 5:30p Pacific (Mark Butler)
* (Section 5) Saturday 10a - 11:30a Pacific (Sid J Reddy)

**Teaching Staff Office Hours:**

* **Daniel Cer**: Wednesday at noon Pacific.
* **Mark Butler**: Thursday and Friday immediately after his live session
* **Sid J Reddy**: Saturday immediately after his live session
* **Matthew Sims**: Thursday 1pm - 2pm PST 
* **Mike Tamir**: Wednesday immediately after his live session
* **Drew Plant**: Monday 6pm - 7 PST

Office hours are for the whole class; students from any section are welcome to attend any of the times above.

**Async Instructors:**
* Dan Gillick
* James Kunz
* Kuzman Ganchev


## Grading

### Breakdown

Your grade report can be found at [https://w266grades.appspot.com](https://w266grades.appspot.com).

Your grade will be determined as follows:
* **Weekly Assignments**: 40%
* **Final Project**: 60%
* **Participation**: Up to 10% bonus

There will be a number of smaller [assignments](../assignment/) throughout the term for you to
exercise what you learned in async and live sessions. Some assignments may be more difficult than others, and may be weighted accordingly.

Participation will be graded holistically, based on live session participation as well as participation on Piazza (or other activities that improve the course this semester or into the future). Do not stress about this part.


### Letter Grades

We curve the numerical grade to a letter grade.  While we don't release the curve, it usually results in about a quarter of the class each receiving A, A-, B+, and B.  Exceptional cases receive A+, C, or F, as appropriate.

A word of warning:  Given that we (effectively) release solutions to assignments in the form of unit tests, it shouldn't be surprising that most students earn near perfect scores.  Since the variance is so low, assignment scores aren't the primary driver of the final letter grade for most students.  A good assignment score is necessary, but not sufficient, for a strong grade in the class.  A well structured, novel project with good analysis is what makes the difference between a high B/B+ and an A-/A.

As mentioned above:  this course is a lot of work.  Give it the time it deserves and you'll be rewarded intellectually and on your transcript.


### Late Day Policy

We recognize that sometimes things happen in life outside the course, especially in MIDS where we all have full time jobs and family responsibilities to attend to. To help with these situations, we are giving you **5 "late days"** to use throughout the term as you see fit.  Each late day gives you a 24 hour (or any part thereof) extension to any deliverable in the course **except** the final project presentation or report. (UC Berkeley needs grades submitted very shortly after the end of classes.)

Once you run out of late days, each 24 hour period (or any part thereof) results in a **10 percentage point deduction** on that deliverable's grade.

You can use a **maximum of 2 late days** on any single deliverable.  We will **not be accepting any submissions more than 48 hours past the original due-date**, even if you have late days. (We want to be more flexible here, but your fellow students also want their graded assignments back promptly!)

We don't anticipate granting extensions beyond these policies.  Plan your time accordingly!

### More serious issues

If you run into a more serious issue that will affect your ability to complete the course, please email the instructors mailing list and cc MIDS student services.  A word of warning though: in previous sections, we have had students ask for INC grades because their lives were otherwise busy.  Mostly we have declined, opting instead for the student to complete the course to the best of their ability and have a grade assigned based on that work.  (MIDS prefers to avoid giving INCs, as they have been abused in the past.)  The sooner you start this process, the more options we (and the department) have to help.  Don't wait until you're suffering from the consequences to tell us what's going on!


## Final Project
*See the [Final Project Guidelines](../project/)*


## Course Resources
We are not using any particular textbook for this course. We’ll list some relevant readings each week. Here are some general resources:
* [Speech and Language Processing (2nd edition)](http://www.cs.colorado.edu/~martin/slp.html) (Jurafsky and Martin)
* [Speech and Language Processing (3rd edition draft)](https://web.stanford.edu/~jurafsky/slp3/) (Jurafsky and Martin) - _free online!_
* [NLTK Book](http://www.nltk.org/book/) - Accompanies NLTK (Natural Language ToolKit) and includes useful, practical descriptions (with python code) of basic concepts.
* [Deep Learning](http://www.deeplearningbook.org/) (Goodfellow, Bengio, and Courville)

We’ll be posting materials to the course [GitHub repo](../../../).

*Note:* the syllabus below might be subject to change. We'll be sure to announce anything major on Piazza.

### Code References

The course will be taught in Python, and we'll be making heavy use of NumPy, TensorFlow, and Jupyter (IPython) notebooks. We'll also be using Git for distributing and submitting materials. If you want to brush up on any of these, we recommend:
* **Git tutorials:** [Introduction / Cheat Sheet](https://git-scm.com/docs/gittutorial), or [interactive tutorial](https://try.github.io/)
* **Python / NumPy:** Stanford's CS231n has [an excellent tutorial](http://cs231n.github.io/python-numpy-tutorial/).
* **TensorFlow:** We'll go over the basics of TensorFlow in [Assignment 2](../../../tree/master/assignment/a2/).  
  [Effective TensorFlow](https://github.com/vahidk/EffectiveTensorflow) is a great reference, ranging from the absolute basics through advanced topics like multi-GPU training, `tf.learn`, and debugging.  
  You can also check out the [tutorials](https://www.tensorflow.org/get_started/) on the TensorFlow website, but these can be somewhat confusing if you're not familiar with the underlying models.


### Misc. Deep Learning and NLP References
A few useful papers that don’t fit under a particular week. All optional, but interesting!
* (optional) [Chris Olah’s blog](http://colah.github.io/) and [Distill](https://distill.pub/)
* (optional) [GloVe: Global Vectors for Word Representation (Pennington, Socher, and Manning, 2014)](http://nlp.stanford.edu/pubs/glove.pdf)

---

## Tentative Schedule and Readings

We'll update the table below with assignments as they become available, as well as additional materials throughout the semester. Keep an eye on GitHub for updates!

*Dates are tentative:* assignments in particular may change topics and dates.  (Updated slides for each week will be posted during the live session week.)

### Live Session Slides: [[available here](https://drive.google.com/drive/folders/17yQSEhmC8JObODOxBOXu6bLG8C_i6K_S?usp=sharing)]

### Deliverables

Note:  we will update this table as we release (approximately weekly) assignments.  Each assignment
will be released around the last live session of the week and due approximately one week later.

<table>
<tr>
<th></th><th>Topic</th><th>Release</th><th>Deadline</th>
</tr>
<tr>
  <td><strong><a href="../assignment/a0" target="_blank">Assignment&nbsp;0</a></strong>
  <td><strong>Course Set-up</strong>
  <ul>
    <li>GitHub
    <li>Piazza
    <li>Google Cloud
  </ul></td>
  <td></td>
  <td>January&nbsp;12</td>
</tr>
<tr> <!-- a1 -->
  <td><strong><a href="../assignment/a1" target="_blank">Assignment&nbsp;1</a></strong>
  <td><strong>Assignment 1</strong>
  <ul>
    <li>Information Theory
  </ul></td>
  <td></td>
  <td>January&nbsp;19</td>
</tr>
<tr>  <!-- a2 -->
  <td><strong><a href="../assignment/a2" target="_blank">Assignment&nbsp;2</a></strong>
  <td><strong>Assignment 2</strong>
  <ul>
    <li>Neural Networks
  </ul></td>
  <td></td>
  <td>January&nbsp;26</td>
</tr>
<tr> <!-- a3 -->
  <td><strong><a href="../assignment/a3" target="_blank">Assignment&nbsp;3</a></strong>
  <td><strong>Assignment 3</strong>
  <ul>
    <li>Embeddings
	<li>ML Fairness
  </ul></td>
  <td>January&nbsp;25</td>
  <td>February&nbsp;2</td>
</tr>
<tr> <!-- project proposal -->
  <td><strong><a href="../project/#project-proposal" target="_blank">Project&nbsp;Proposal</a></strong>
  <td>
  <strong><a href="../project" target="_blank">Final Project Guidelines</a></strong>
  </td>
  <td></td>
  <td>February&nbsp;9</td>
</tr>
<tr> <!-- a4 -->
  <td><strong><a href="../assignment/a4" target="_blank">Assignment&nbsp;4</a></strong>
  <td><strong>Assignment 4</strong>
  <ul>
    <li>Classification
    <li>Convolutional Neural Nets
  </ul></td>
  <td>February&nbsp;8</td>
  <td>February&nbsp;16</td>
</tr>
<tr> <!-- a5 -->
  <td><strong><a href="../assignment/a5" target="_blank">Assignment&nbsp;5</a></strong>
  <td><strong>Assignment 5</strong>
  <ul>
    <li>Language Models
  </ul></td>
  <td>February&nbsp;15</td>
  <td>February&nbsp;23</td>
</tr>
<tr> <!-- a6 -->
  <td><strong><a href="../assignment/a6" target="_blank">Assignment&nbsp;6</a></strong>
  <td><strong>Assignment 6</strong>
  <ul>
    <li>Machine Translation
  </ul></td>
  <td>February&nbsp;22</td>
  <td>March&nbsp;1</td>
</tr>
<tr> <!-- a7 -->
  <td><strong><a href="../assignment/a7" target="_blank">Assignment&nbsp;7</a></strong>
  <td><strong>Assignment 7</strong>
  <ul>
    <li>Various Topics
  </ul></td>
  <td>March&nbsp;7</td>
  <td>March&nbsp;15</td>
</tr>
<tr><!--- Project Reports -->
  <td><strong><a href="../project/#final-submission" target="_blank">Project&nbsp;Reports</a></strong>
  </td>
  <td></td>
  <td></td>
  <td><strong>CHANGED</strong><br>now due April&nbsp;20<br><strong>(hard deadline)</strong></td>
</tr>
<tr><!--- Project Presentations -->
  <td><strong><a href="../project/#presentations" target="_blank">Project&nbsp;Presentations</a></strong></td>
  <td></td>
  <td></td>
  <td><br>in-class April&nbsp;13-18</td>
</tr>
</table>


### Course Schedule

<table>
<tr>
<th></th>
<th>Async to Watch</th>
<th>Topics</th>
<th>Materials</th>
</tr>
<tr><!--- Introductions -->
  <td><strong>Week&nbsp;1-2</strong><br>(January&nbsp;6)</td>
  <td>Introduction
  <br>5.2 Softmax Classification
  <br>5.4 Neural network recap
  <br>5.5 Neural network training loss
  </td>
  <td><ul>
    <li>Overview of NLP applications
    <li>Ambiguity and grounding in language
    <li>Information theory and linear algebra review
    <li>ML models: Logistic regression and feed forward networks
  </ul></td>
  <td><ul>
  <li>Skim: <a href="http://www.nltk.org/book/ch01.html" target="_blank">NLTK book chapter 1 (python and basics)</a>
  <li>Skim: <a href="http://www.nltk.org/book/ch02.html" target="_blank">NLTK book chapter 2 (data resources)</a>
  <li>Read: <a href="https://www.technologyreview.com/s/602094/ais-language-problem/" target="_blank">AI’s Language Problem (Technology Review)</a>
  <li>Read: <a href="http://nautil.us/issue/54/the-unspoken/the-rise-and-fall-of-the-english-sentence" target="_blank">The Rise and Fall of the English Sentence</a>
  <li>Read: <a href="https://www.cs.toronto.edu/~hinton/absps/pdp8.pdf">Original backprop paper</a>
  <li><em>Optional:</em> <a href="http://www.newyorker.com/magazine/2007/04/16/the-interpreter-2" target="_blank">The Interpreter (New Yorker)</a>
  <li><em>Optional:</em> <a href="https://www.uio.no/studier/emner/hf/ikos/EXFAC03-AAS/h05/larestoff/linguistics/Chapter%204.(H05).pdf" target="_blank">Introduction to Linguistic Typology</a>
  </ul>
  <!-- <p>                                                                                                                -->
  <!-- <a href="../materials/week1/TensorFlow%20Tutorial.ipynb" target="_blank">[TensorFlow&nbsp;Intro&nbsp;notebook]</a> -->
  </td>
</tr>
<tr><!--- Sentiment/Classification -->
  <td><strong>Week&nbsp;3</strong><br>(January&nbsp;20)</td>
  <td>Classification and Sentiment (up to 2.6)
  </td>
  <td><ul>
  <li>Sentiment lexicons
  <li>Aggregated sentiment applications
  <li>Bag-of-word models
  <li>Introduction to Word embeddings
  </ul></td>
  <td><ul>
  <li>Skim: <a href="http://www.cs.cornell.edu/home/llee/omsa/omsa.pdf" target="_blank">Opinion Mining and Sentiment Analysis</a> (Pang and Lee 2008) - focus on Chapters 1-4
  <li>Read: <a href="http://www.wildml.com/2015/11/understanding-convolutional-neural-networks-for-nlp/" target="_blank">Understanding Convolutional Neural Networks for NLP</a>
  <li>Read: <a href="https://arxiv.org/abs/1408.5882" target="_blank">Convolutional Neural Networks for Sentence Classification</a> (Yoon Kim, 2014)
  <li><em>Optional:</em> <a href="https://arxiv.org/pdf/1103.0398v1.pdf" target="_blank">Natural Language Processing (almost) from Scratch</a> (Collobert et al., 2011)
</tr>
<tr><!--- Sentiment/Classification -->
  <td><strong>Week&nbsp;4</strong><br>(January&nbsp;27)</td>
  <td>Classification and Sentiment (2.7 onwards)
  <p><p>
  <em>Note: you may want to review Async 5.3, 5.4, and 5.5.</em>
  </td>
  <td><ul>
  <li>Convolutional neural networks for NLP
  </ul></td>
  <td></td>
</tr>
<tr><!--- n-grams -->
  <td><strong>Week&nbsp;5</strong><br>(February&nbsp;3)</td>
  <td>Language Modeling I,
  <br>4.1-4.4, 4.8 - 4.11</td>
  <td><ul>
    <li>LM applications
    <li>N-gram models
    <li>Smoothing methods
    <li>Representations of meaning
    <li>Distributed representations
    <li>Neural Net LMs
    <li>Word embeddings
    <li>Hierarchical softmax
  </ul></td>
  <td>Language model introduction:<ul>
  <li>Skim: <a href="http://www.cs.berkeley.edu/~klein/cs294-5/chen_goodman.pdf" target="_blank">Chen and Goodman Survey</a>
  <li>Skim: <a href="http://arxiv.org/pdf/1312.3005.pdf" target="_blank">1 Billion Word Benchmark</a>
  <li><em>Optional:</em> <a href="http://norvig.com/ngrams/ch14.pdf" target="_blank">Natural Language Corpus Data (Peter Norvig)</a>
  </ul>
  <p>
  <a href="../materials/simple_lm/lm1.ipynb" target="_blank">[Language&nbsp;Modeling&nbsp;Notebook]</a>
  Distributed representations:<ul>
  <li>Read: <a href="https://www.aclweb.org/anthology/J92-4003" target="_blank">Brown Clustering</a> (Brown et al. 1992)
  <li>Read: <a href="http://arxiv.org/pdf/1301.3781.pdf" target="_blank">CBOW and SkipGram</a> (Mikolov et al. 2013)
  <li><em>Optional:</em> <a href="http://colah.github.io/posts/2014-07-NLP-RNNs-Representations/" target="_blank">Deep Learning, NLP, and Representations</a> (Chris Olah's blog)
  <li><em>Optional:</em> <a href="https://www.tensorflow.org/versions/master/tutorials/word2vec/index.html" target="_blank">Tensorflow Word2Vec Tutorial</a> (just the parts on <a href="https://github.com/tensorflow/tensorflow/blob/r0.10/tensorflow/examples/tutorials/word2vec/word2vec_basic.py" target="_blank">word2vec_basic.py</a> - don’t bother with the “Optimizing the Implementation” part or anything in C++)
  <li><em>Optional:</em> <a href="https://www.technologyreview.com/s/602025/how-vector-space-mathematics-reveals-the-hidden-sexism-in-language/" target="_blank">How Vector Space Mathematics Reveals the Hidden Sexism in Language</a> (and the <a href="http://arxiv.org/abs/1607.06520" target="_blank">original paper</a>)
  </ul>
  <p>
  <a href="../materials/embeddings/embeddings.ipynb" target="_blank">[Word&nbsp;Embeddings&nbsp;Notebook]</a>
  <a href="http://projector.tensorflow.org/" target="_blank">[TensorFlow&nbsp;Embedding&nbsp;Projector]</a>
  </td>
</tr>
<tr><!--- Neural language models -->
  <td><strong>Week&nbsp;6</strong><br>(February&nbsp;10)</td>
  <td>Language Modeling II</td>
  <td><ul>
  <li>Recurrent Neural Nets
  <li>State of the art: Advanced Embeddings and Transfer Learning
  </ul></td>
  <td><ul>
  <li>Read: <a href="http://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf" target="_blank">A Neural Probabilistic Language Model</a> (Bengio et al. 2003)
  <li>Read or skim: <a href="http://neuralnetworksanddeeplearning.com/chap2.html" target="_blank">How the backpropagation algorithm works</a>
  <li><em>Optional:</em> <a href="http://colah.github.io/posts/2015-08-Understanding-LSTMs/" target="_blank">Understanding LSTM Networks</a> (Chris Olah's blog)
  <li><em>Optional (skim):</em> <a href="https://www.tensorflow.org/versions/master/tutorials/recurrent/index.html#recurrent-neural-networks" target="_blank">Tensorflow LSTM Language Model Tutorial</a>
  <li><em>Optional / fun:</em> <a href="http://playground.tensorflow.org/" target="_blank">Tensorflow Playground</a>
  </ul>
  <p>
  <p>
  <a href="../materials/nplm/nplm.ipynb" target="_blank">[NPLM Notebook]</a>
  </td>
</tr>
<tr><!--- Extra Material -->
  <td><strong>Interlude (Extra Material)</strong></td>
  <td>Units of Meaning: Words, Morphology, Sentences</td>
  <td><ul>
  <li>Edit distance for strings
  <li>Tokenization
  <li>Sentence splitting
  </ul></td>
  <td><ul>
  <li>Skim: <a href="http://www.nltk.org/book/ch03.html" target="_blank">NLTK book chapter 3</a> (processing raw text)
  <li>Skim: <a href="http://norvig.com/ngrams/ch14.pdf" target="_blank">Natural Language Corpus Data</a> (Peter Norvig) <em>(if you didn't read in Week 2)</em>
  <li>Read: <a href="http://u.cs.biu.ac.il/~89-680/gillick2009.pdf" target="_blank">Sentence Boundary Detection and the Problem with the U.S.</a>
  <p>
  </ul></td>
</tr>
<tr><!--- Week 7 and 8 -->
  <td><strong>Week&nbsp;7</strong><br>(February&nbsp;17)</td>
  <td>Machine Translation I</td>
  <td><ul>
  <li>Word- and phrase-based MT
  <li>IBM alignment models
  <li>Evaluation
  <li>Neural MT with sequence-to-sequence models and attention
  </ul></td>
  <td><ul>
  <li>Read: <a href="http://papers.nips.cc/paper/5346-sequence-to-sequence-learning-with-neural-networks.pdf" target="_blank">Sequence to Sequence Learning with Neural Networks</a>
  <li>Read: <a href="https://arxiv.org/pdf/1409.0473.pdf" target="_blank">Neural Machine Translation by Jointly Learning to Align and Translate</a>
  <li><em>Optional:</em> <a href="https://arxiv.org/abs/1609.08144" target="_blank">Google’s Neural Machine Translation System</a>
  <li><em>Optional:</em> <a href="http://distill.pub/2016/augmented-rnns/#attentional-interfaces" target="_blank">Attention and Augmented Recurrent Neural Networks</a> (section on “Attentional Interfaces” has an awesome visualization of an MT example, showing alignments)
  </ul></td>
    <tr><!--- Practical Machine Learning  week 8-->
  <td><strong>Week&nbsp;8</strong><br>(February&nbsp;24)</td>
  <td>Machine Translation II</td>
  <td><ul>
  <li>Self-Attention
  <li>Transformers
  <li>Transfer Learning
  </ul></td>
  <td><ul>
  </ul>
  <p>
  </td>
</tr>
  <tr><!--- Practical Machine Learning  week 9-->
  <td><strong>Week&nbsp;9</strong><br>(March&nbsp;2)</td>
  <td>No Async</td>
  <td><ul>
  <li>Practical Deep Learning Tips
  <li>Xavier Initialization
  <li>Batch Normalization
  <li>Optimizers
  </ul></td>
  <td><ul>
  </ul>
  <p>
  </td>
</tr>
<tr><!--- Week 10 -->
  <td><strong>Week&nbsp;10</strong><br>(March&nbsp;9)</td>
  <td>Summarization</td>
  <td><ul>
  <li>Single- vs. multi-document summarization
  <li>Extractive and abstractive summarization
  <li>Classical summarization algorithms
  <li>Evaluating generated summaries
  </ul></td>
  <td><ul>
  <li>Skim: <a href="https://www.cs.cmu.edu/~afm/Home_files/Das_Martins_survey_summarization.pdf" target="_blank">A Survey on Automatic Text Summarization</a> (Das and Martins, 2007)
  <li>Read: <a href="https://arxiv.org/pdf/1509.00685v2.pdf" target="_blank">A Neural Attention Model for Abstractive Sentence Summarization</a> (Rush et al. 2015)
  <li><em>Optional:</em> <a href="https://arxiv.org/pdf/1704.04368.pdf" target="_blank">Get To The Point: Summarization with Pointer-Generator Networks</a> (See et al. 2017)
  </ul>
  <p>
  </td>
</tr>
<tr><!--- Entities -->
  <td><strong>Week&nbsp;11</strong><br>(March&nbsp;16)</td>
  <td>Entities</td>
  <td><ul>
  <li>From syntax to semantics
  <li>Named Entity Recognition
  <li>Coreference Resolution
  </ul></td>
  <td><ul>
  <li>Read: <a href="http://www.nltk.org/book/ch07.html" target="_blank">NLTK Book Chapter 7 (Extracting Information from Text)</a>
  <li><em>Optional:</em> <a href="http://www.aclweb.org/anthology/D09-1120" target="_blank">Simple Coreference Resolution with Rich Syntactic and Semantic Features</a> (Haghighi and Klein 2009, rule-based coreference)
  <li><em>Optional:</em> <a href="http://www.aclweb.org/anthology/P16-1061" target="_blank">Improving Coreference Resolution by Learning Entity-Level Distributed
  Representations</a> (Clark and Manning 2016, neural coreference)
  </ul>
  <p>
  </td>
</tr>
<tr><!--- Information Retrieval -->
  <td><strong>Week&nbsp;12</strong><br>(March&nbsp;30)</td>
  <td>Information Retrieval</td>
  <td><ul>
  <li>Building a Search Index
  <li>Ranking
  <li>TF-IDF
  <li>Click signals
  <li>Neural IR models
  </ul></td>
  <td><ul>
  <li>Read: <a href="http://static.googleusercontent.com/media/research.google.com/en//archive/googlecluster-ieee.pdf" target="_blank">Web Search for a Planet</a> (Google)
  <li>Read: <a href="http://infolab.stanford.edu/~backrub/google.html" target="_blank">The Anatomy of a Large-Scale Hypertextual Web Search Engine</a>
  <li>Skim: <a href="http://nlp.stanford.edu/IR-book/pdf/irbookprint.pdf" target="_blank">"An Introduction to Information Retrieval", sections 6.2 and 6.3</a>
  <li><em>Optional:</em> <a href="http://ilpubs.stanford.edu:8090/422/1/1999-66.pdf" target="_blank">PageRank</a> (Page, et al. 1999)
  </ul>
  <p>
  </td>
</tr>

<tr><!--- Parsing and POS Tagging -->
  <td><strong>Week&nbsp;13</strong><br>(April&nbsp;6)</td>

  <td><a href="https://www.youtube.com/playlist?list=PLh1VT8Lm3apRPGB1uKZsMyMt1DmUf_ItE">Part of Speech Supplementary Videos</a>
<p><p>
9.1, 9.2, 9.3
<p>
10.1, 10.2, 10.3
</td>


  <td><ul>
  <li>HMM/CRF models
  <li>Transition-based dependency parsing
  <li>CKY-based constituency parsing
  </ul>
  </td>


  <td><ul>
  <li><em>Optional:</em> <a href="http://www.nltk.org/book/ch05.html" target="_blank">NLTK book chapter 5: Categorizing and Tagging Words</a>
  </ul>
  <p>
  <br>
  <a href="https://hmm-dot-nlp-visualizations.appspot.com/hmm?sentence=James+ate+the+food&vizMode=viterbi&numFormat=log" target="_blank">[Interactive HMM Demo]</a>
  <ul>
  <li>Read: <a href="https://arxiv.org/pdf/1104.2086.pdf" target="_blank">A Universal Part-of-Speech Tagset</a>
  <li>Read: <a href="https://research.googleblog.com/2016/05/announcing-syntaxnet-worlds-most.html" target="_blank">SyntaxNet (Parsey McParseface)</a>
  <li><em>Optional:</em> <a href="http://nlp.stanford.edu/pubs/CICLing2011-manning-tagging.pdf" target="_blank">Part-of-Speech Tagging from 97% to 100%: Is It Time for Some Linguistics?</a>
  <li>Skim: <a href="https://web.stanford.edu/~jurafsky/slp3/15.pdf" target="_blank">Dependency Parsing (J&M Chapter 15)</a>
  <li><em>Optional:</em> <a href="http://cs.stanford.edu/people/danqi/papers/emnlp2014.pdf" target="_blank">A Fast 
and Accurate Dependency Parser using Neural Networks</a> (Chen & Manning 2014)
  <li>Skim: <a href="http://www.nltk.org/book/ch08.html" target="_blank">NLTK book chapter 8 (analyzing sentence structure)</a>
  <li>Skim: <a href="https://web.stanford.edu/~jurafsky/slp3/13.pdf" target="_blank">Constituency Parsing (J&M Chapter 13)</a>
  <li>Skim: <a href="http://ilpubs.stanford.edu:8091/~klein/unlexicalized-parsing.pdf" target="_blank">Accurate Unl
exicalized Parsing</a> (Klein & Manning 2003)
  <li>Play: <a href="http://nlp.stanford.edu:8080/parser/" target="_blank">Stanford parser</a> (online demo)
  <li><em>Optional / reference:</em> <a href="http://www.surdeanu.info/mihai/teaching/ista555-fall13/readings/PennT
reebankConstituents.html" target="_blank">Penn Treebank Constituent Tags</a>
  
  <p>
  <a href="https://cky-dot-nlp-visualizations.appspot.com/cky?sentence=James+ate+the+food" target="_blank">[Interactive CKY Demo]</a>
  </ul>
  </td>
</tr>

<tr><!--- In Class Presentations -->
  <td><strong>Week&nbsp;14&nbsp;</strong><br>(April&nbsp;13)</td>
  <td></td>
  <td><ul>
  <li>In-class project presentations
  </ul></td>
  <td><ul>
  </ul>
  <p>
  </td>
</tr>

</table>

Thanks for a great semester!
