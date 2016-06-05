# Introduction
This is a very incomplete and subjective selection of Artificial Intelligence (AI) / Machine Learning (ML) / Statistical Inference (SI) / Deep Learning (DL) / Reinforcement Learning (RL) resources. Mainly MOOCs & video lectures for now, books / tutorials / articles etc might come later. It is not an exhaustive list and only contains some of the learning resources *that I have personally completed* so that I can include some brief personal thoughts & comments on them. In a sense it's a documentation of my personal journey into DL.

A lot of the resources below are actually not for DL but ML and more comprehensive SI and pattern recognition algorithms. DL is mostly just tweaks on top of older techniques, so once you have a solid foundation it makes a lot more sense. If you go through the video lectures below (including advanced ones), you'll be able to pick up current DL developments directly from the published papers.

If you really want to understand AI/ML/DL/RL indepth with all the maths, you need a good understanding of linear algebra (vectors & matrices), probability and statistics (which is more complex than it sounds), and calculus (mainly multivariate differential calculus, which is much simpler than it sounds). I've included lectures for these too. You can't cut corners. Take the time and study as much of the below as you can, from the beginning. Strong foundations are crucial. I often started watching one lecture, 5 minutes in I realized I didn't understand anything so went back to watch another lecture which taught the prerequisites, 5 minutes in I realized I didn't understand anything so went back to watch another lecture which taught the prerequisites, etc. until I went back 10 lectures. It has been depressing. 

If you just want to *use* the algorithms without necessarily understanding or delving into the maths, or just want to understand the algorithms at a high conceptual level, that's perfectly fine too. Hopefully my comments below will make it clear what's what. 
  

# Tip
There's a lot of overlap in the lectures below. That's a **good** thing. Don't skip things because you've already read or seen them elsewhere. If you're trying to learn and *understand* something which is potentially quite complicated, having different people explain the same thing to you in different ways is very useful and often gives insight you might not otherwise find.

If there are sections which you are 100% comfortable with, then you could watch those sections at 1.25x, 1.5x, or even 2.0x speed just to see what's going on, and then switch back to 1.0x speed once you encounter new material or new insight.

---
# Video Lectures
These are one off video workshops or lectures that give overview or insight. You won't learn about the depths of how things work, but will at least probably understand what things are, what they mean and what you can do with them. These are usually a good intro before you dive into the heavier MOOCs. 

**Deep Learning by Yann LeCun and Yohua Bengio @ NIPS 2015**  
http://research.microsoft.com/apps/video/?id=259574  
Quite up to date top-level overview of what DL is, how it works (at a very high level) and latest developments, from the grandmasters Yoshua Bengio + Yann LeCun. It's not very technical, but does mention some technical concepts. If you know nothing (or little) about AI/ML/DL it'll probably be useful and you're sure to get some insight. 

**The Unreasonable Effectiveness of Deep Learning by Yann LeCun 2014**  
http://videolectures.net/sahd2014_lecun_deep_learning/  
Famous lecture by Yannn LeCun, godfather of deep convolutional neural networks (CNN). Brief intro to DL, why it's awesome, and then mainly focuses on CNNs. Very similar to above actually. Could probably be skipped if you watch the above.  

**Deep Learning RNNaissance by Juergen Schmidhuber @ NYC ML Meetup 2014**  
https://www.youtube.com/watch?v=6bOMf9zr7N8  
An alternate history of DL from Jurgen Scmidhuber, another grandmaster of DL. He goes into more detailed history of the algorithms and where they come from, and then focuses on Recurrent Neural Networks (RNN), which his lab made many innovations on (including LSTM). This one is a bit more advanced than the above ones. 

**Lots more one-off lectures / tutorials at:**  
http://videolectures.net/Top/Computer_Science/Artificial_Intelligence  

Some of my favourites (some of which are on a bit of a tangent):  

**Basics of Computational Reinforcement Learning by Michael Littman @ RLDM 2015**  
http://videolectures.net/rldm2015_littman_computational_reinforcement/  
Kind of an overview intro to RL. Some experience with MDPs etc would be useful but not essential. Michael Littman is one of the old school stars of RL and a lot of fun.

**Introduction to Reinforcement Learning with Function Approximation by Rich Sutton @ NIPS 2015**  
http://research.microsoft.com/apps/video/?id=259577  
Similar to above but more technical and theoretical. Rich Sutton is old school king of RL. 

**Deep Reinforcement Learning by David Silver @ RLDM 2015**    
http://videolectures.net/rldm2015_silver_reinforcement_learning  
Advanced intro to Deep RL as used by Deepmind on the Atari games and AlphaGo. Quite technical and requires decent understanding of RL, TD learning and Q-Learning etc. (see RL courses below). David Silver is the new school king of RL and superstar of Deepmind's AlphaGo (which uses Deep RL).

**Monte Carlo Inference Methods by Ian Murray @ NIPS 2015**
http://research.microsoft.com/apps/video/?id=259575  
Good introduction and overview of sampling / monte carlo based methods. Not essential for a lot of DL, but good side knowledge to have. 

**How to Grow a Mind: Statistics, Structure and Abstraction by Josh Tenenbaum @ NIPS 2010**  
http://videolectures.net/nips2010_tenenbaum_hgm  
Completely unrelated to current DL and takes a very different approach: Bayesian Heirarchical Models. Not much success in real world yet, but I'm still a fan as the questions and problems they're looking at feels a lot more applicable to real world than DL (e.g. one-shot learning and transfer learning, though Deepmind is looking at this with DL as well now). 

**Two architectures for one-shot learning by Josh Tenenbaum @ NIPS 2013**  
http://videolectures.net/nipsworkshops2013_tenenbaum_learning  
Similar to above but updated. 

---

# Massive Open Online Courses (MOOC)
These are concentrated long term courses consisting of many video lectures. Very roughly in order that I recommend them. 


## Foundation / Maths
If you want to *understand the maths* of ML then these are crucial. If you don't want to understand the maths, but only want to understand the *concepts* then you could probably skip these. However, this is also where some of the fundamental terminology is defined (prior, conditional, expected value, derivative, vector, matrix etc). So even if you don't want to understand the maths, if you just want to understand the concepts you at least need to know what these things mean.

Khan is a superhero and will make you understand things you never knew you could. So at least do the first few sections of each to understand the concepts. But if you can do them all, you will feel like a superhero. I wish I had time to go through every video Khan has ever made. 

Also instead of going through all of these now, you could just do some of the basic lessons first to help you understand the fundamental maths of ML. And then come back to some of the more advanced lessons if and when you encounter them during your adventures in ML. E.g. it's quite probable that you'll never encounter a Hessian matrix, or require eigenvectors or calculate the determinant of a matrix by hand. And only if and when you do, then you can come back and look at the relevant lessons. You can also skip proofs if you're short on time, but they do help you understand better. Try not to be impatient. 


**Khan Academy - Probability & Statistics**  
https://www.khanacademy.org/math/probability  
ML is basically a subdiscipline of applied statistics mashed with computer science. So basic understanding of probality & statistics is essential. You don't need to do all lessons, but at least the first few sections to understand the concepts. Bear in mind as you do the more advanced stuff - which may not be nessecary for ML - they actually help you understand the basic stuff better. 


**Khan Academy - Linear Algebra**  
https://www.khanacademy.org/math/linear-algebra  
Again you probably don't need to do them all, but at least vectors, matrics, operations on them, dot & cross product, matrix multiplication etc. is essential for the most basic understanding of ML maths. Basis, eigenvalues/eigenvectors is essential for deeper understanding for some areas, but you could scrape by without them, at least for now.

**Khan Academy - Calculus**  
https://www.khanacademy.org/math/calculus-home  
**Precalculus** - trigonometry, vectors, matrics are essential. If you took the linear algebra lessons you may not need this. Complex numbers, sequences and series etc. are useful and come up in various advanced areas, but not nessecary for basic ML. 

**Differential Calculus** - Essential (esp chain rule) if you want to understand maths of ML. You could skip proofs and the applications if you're impatient, though maxima / minima, concavity & inflection, optimization is important.

**Integral Calculus** - I don't think integral calculus is integral to DL (see what I did there? :). I've seen it in a few proofs, but it's more of a niche thing I think in ML which beginners could skip for now. Do at least the first sections to know what it is. Function approximation, series etc. do come up in more advanced areas.

**Multivariate Calculus** - Essential if you really want to understand the maths of DL, especially (partial) derivatives of multivariable functions. Hessians, Jacobians, Laplacians etc come up all the time in advanced areas, but you could get by and understand basic ML without knowing these. I.e. you could skip these for now and come back later, once you encounter them. 

---

## Machine Learning / Deep Learning
### Short / Introductory Courses
These are probably enough if you just want to be able to play with and tweak existing ML/DL code and algorithms. 

**Machine Learning by Andrew Ng @ Coursera**  
https://www.coursera.org/learn/machine-learning  
Fantastic introductory course and foundation for ML. Covers basics of ML from linear and logistic regression to large scale neural networks. Gives great insight into concepts and techniques with minimal maths. Requires basic knowledge of linear algebra and differential calculus. Note: doesn't cover specifities of current *deep* learning (e.g. convolutional neural networks, recurrent neural networks etc.), so is mainly a great foundation for more advanced studies. P.S. Andrew Ng was co-founder of Google Brain and now chief scientist at Baidu research. He is great at giving intuition. 

**Deep Learning by Google @ Udacity**  
https://www.udacity.com/course/deep-learning--ud730  
Brief introduction to DL for those who are familiar with ML. This is a very short course, I think I went through the whole thing in under 2 hours. It's almost a reading of the tensorflow tutorials ( https://www.tensorflow.org/versions/master/tutorials/index.html ). It gives a top level summary of basic DL techniques. Assumes you're comfortable with ML and related concepts. So at least Andrew Ngs coursera (or equivalent knowledge) is a must. Don't expect to be a DL wizard after this, but at least you might know what a CNN or RNN is. If you're going to look at any of the advanced ML courses below, take this DL course *after* them.


### Longer / Advanced Courses
These will help you understand what's actually going on, perhaps even understand some DL papers (I say 'some' DL papers because others are just insanely theoretical and dense). 

**CS188 Introduction to Artificial Intelligence by Pieter Abbeel @ Berkeley**
(some videos have audio issues, so below are a bunch of playlists from different years, I had to pick and choose from different playlists depending on audio problems).  
https://www.youtube.com/channel/UCDZUttQj8ytfASQIcvsLYgg (Spring 2015)  
https://www.youtube.com/channel/UCB4_W1V-KfwpTLxH9jG1_iA (Spring 2014)  
https://www.youtube.com/channel/UCshmLD2MsyqAKBx8ctivb5Q (Fall 2013)  
https://www.youtube.com/user/CS188Spring2013 (Spring 2013)  
This is a fantastic introduction to *AI in general*, not specifically *ML*. It covers many different areas of AI and ML. The first half is more agent-based AI starting with CSPs, decision trees, MDPs etc, and in that respect it is a bit unique compared to the others on this list. Then goes into various different (and old school) ML topics. It is an introduction, so requires no prior knowledge of AI or ML, but it does go into the maths, so requires decent understanding of the usual probability, linear algebra, calculus etc. Doesn't cover DL but a great foundation for a lot of AI and ML, especially if you want to get more into agent-based AI such as Reinforcement Learning, Monte Carlo Tree Search etc.

**CS540 Machine Learning by Nando de Freitas @ UBC 2013**  
https://www.youtube.com/playlist?list=PLE6Wd9FR--EdyJ5lbFl8UuGjecvVw66F6    
This covers many oldschool ML and SI etc from start all the way to neural networks. Doesn't require prior knowledge of ML, so can be considered comprehensive introduction but way more thorough and detailed than Andrew Ng's Coursera, goes heavy into maths. Bear in mind it's a post-graduate CS course so it's quite advanced. Doesn't cover DL but very comprehensive foundation in ML and SI. P.S. Nando is ace. Also prof at Oxford and works for Deepmind. 

**CS340 Machine Learning by Nando de Freitas @ UBC 2012**  
https://www.youtube.com/playlist?list=PLE6Wd9FR--Ecf_5nCbnSQMHqORpiChfJf  
Similar to above, but undergraduate version. I haven't actually watched these so I don't know how they're different to CS540. Probably bit simpler.

**Deep Learning by Nando de Freitas @ Oxford 2015**    
https://www.youtube.com/playlist?list=PLE6Wd9FR--EfW8dtjAuPoTuPcqmOV53Fu  
Similar to CS540 but more about DL. Definitely requires prior knowledge in ML/SI (Andrew Ng's coursera may be enough, but I really recommend Nando's CS540) and more understanding of statistics and multivariate differential calculus. Even knowledge of information theory would be useful. Great guest lectures by Alex Graves on generative RNNs (he's *the* guy for that) and Karol Gregor on VAEs (he's *the* guy for that).

**CS229 Machine Learning by Andrew Ng @ Stanford 2008**  
https://www.youtube.com/view_play_list?p=A89DCFA6ADACE599  
Another very comprehensive introduction to ML/SI. Nothing like his Coursera, way more mathy and covers lots more topics, much more thorough. Kind of like a mashup of Pieter Abbeel's CS188 AI Course and Nando de Freitas's CS540 ML Course. This course is more detailed in some areas, and less detailed in others (e.g. AFAIR goes deeper into MDPs and RL than Abbeel's CS188, but doesn't cover bayes nets). They all provide slightly different perspectives and insights. Also doesn't cover DL, just a really solid comprehensive foundation for ML and SI. 

**Neural Networks for Machine Learning by Geoffrey Hinton @ Coursera**  
https://www.coursera.org/course/neuralnets  
Goes deep into some areas of DL and rather advanced. Hinton is one of the titans of DL and there is a lot of insight in here, but I found it a bit all over the place and I wasn't a huge fan of it. I.e. I don't think it's very useful as a *linear educational* resource and requies prior knowledge of ML, SI and DL. If you first learn these topics elsewhere (e.g. videos above) and then come back to this course then you can find great insight. Otherwise if you dive straight into this you will get lost.  


**Computational Neuroscience by Rajesh Rao & Adrienne Fairhall @ Coursera**
https://www.coursera.org/course/compneuro  
Not directly related to DL but fascinating nevertheless. Starts quite fun but gets rather heavy, especially Adrienne's sections. Rajesh takes things quite slow and re-iterates everything, but I think Adrienne is used to dealing with comp-neuroscience postgrad students and flies through the slides. Expect to pause the video on every slide while you try to digest what's on the screen. Requires decent understanding of the usual suspects, linear algebra, differential calculus, probability and statistical analysis, including things like PCA etc.

---
## I haven't completed, but started or skimmed through and looks good:
**Machine Learning for Musicians and Artists by Rebecca Fiebrink @ Kadenze**  
https://www.kadenze.com/courses/machine-learning-for-musicians-and-artists/info  
Aimed at artists and musicians. I haven't watched this but knowing Rebecca and her work this is bound to ace. 

**Machine Learning by Georgia Tech (Charles Isbell & Michael Littman) @ Udacity**  
https://www.udacity.com/course/machine-learning-supervised-learning--ud675  
https://www.udacity.com/course/machine-learning-unsupervised-learning--ud741  
https://www.udacity.com/course/machine-learning-reinforcement-learning--ud820  
Looks like basic introduction to main topics. Doesn't look too heavy. Probably requires basic linear algebra etc but not too complex. Charles Isbell and Michael Littman are really good. 

**Reinforcement Learning by Michael Littman, Chris Pryby & Charles Isbell @ Udacity**  
https://www.udacity.com/course/reinforcement-learning--ud600  
Did about half of this then got distracted by other things. Similar to above but focuses on MDPs and RL and goes quite thorough. I'd like to finish it but have other priorties right now. 

**Reinforcement Learning by David Silver @ UCL 2015**  
http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching.html  
https://www.youtube.com/playlist?list=PL5X3mDkKaJrL42i_jhE4N-p6E2Ol62Ofa
Introduction to MDPs and RL. Looks a lot lighter and brief than above. But perhaps enough for Deep RL. P.S. David Silver is superstar of Deepminds AlphaGo (which uses Deep RL). 

**Probabilistic Graphical Models by Daphne Koller / Stanfod @ Coursera**  
https://www.coursera.org/course/pgm  
Not actually directly related to DL but probabilistic methods, bayes networks etc. (i.e. related to Josh Tenenbaum's talks above). I started this but stopped after a while as I got busy with other things. Starts fun but gets quite heavy. Looks like it's very thorough, perhaps too thorough as it seems to be covering a whole range of topics past and present. I'd like to finish it but have other priorties right now. 

---
# Tutorials / Articles
Coming soon.

---
# Notes
Since this is a list of resources that I have personally watched or read, accompanied by my brief thoughts on them, it doesn't make sense for me to accept pull requests (unless there are typos). But *please* do send me suggestions (probably via issues) for others. 

This list can be found on github and medium.
