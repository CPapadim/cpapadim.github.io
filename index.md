# Hello, I'm Charalampos (Harry),

| <img style="width:99px" src = "https://github.com/CPapadim/cpapadim.github.io/raw/master/other/Photo25.png"> | I'm a `quantitative storyteller`.  I enjoy taking strings of words in the form of questions, turning them into numbers and math, using data to find quantitative answers, and finally turning those quantitative answers into compelling stories.|
| ------------ | ------------- |
| | |
On this page you will find a few examples of some of the projects I've worked on.  If you have any questions about anything on this page or need to reach me for any reason, you can contact me at papadimitriou.c@gmail.com 

***

# Analysis Packages
In order to tell truly compelling stories about data a storyteller often needs to create customized storytelling tools.  

## Signal Processing Toolkit

When the Snyder Laboratory wanted to expand into analysis of local field potentials, I stepped up to develop this package to help me and other lab mates tell stories about how brains work.  It can analyze `time series` of action potentials and local field potentials from the brain in both the `frequency` and `time` domains to help users uncover how these different brain signals relate to each other and contribute to driving behavior.  

[Signal Processing Toolkit](https://github.com/CPapadim/Signal-Processing-Toolkit)

![](https://raw.githubusercontent.com/CPapadim/cpapadim.github.io/master/other/LFP1.png)
![](https://raw.githubusercontent.com/CPapadim/cpapadim.github.io/master/other/LFP2.png)

This tool is now being used by a new generation of upcoming scientists in the Snyder Laboratory. 

## Behavioral and Neural Analysis Toolkit

I wrote this package to determine how neuron spikes are related to behavior.  It can analyze and quantify behavior, especially in the context of eye movements and working memory.  It can also align neural data to these behaviors to help determine how neural activity changes drive these behaviors.  

[Behavioral and Neural Analysis Toolkit](https://github.com/CPapadim/Behavioral-and-Neural-Analysis-Toolkit)

![](https://raw.githubusercontent.com/CPapadim/cpapadim.github.io/master/other/BehaviorNeural.png)

***
# Experimental Design

In order to tell a good story you have to do the `right experiment`.  Below is a document outlining one of my experimental designs to study working memory.  This design won a highly competitive `N.R.S.A grant (~$150,000 in funding) from the National Institutes of Health`.

[Experimental Design Document](https://github.com/CPapadim/cpapadim.github.io/blob/master/other/ExperimentalDesign.pdf)

These are some of the reviews of the design:
>"`Very clever set of experiments` to determine whether decay of behavioral spatial working memory can be related to changes in the correlated tuning curves of neurons in DLPC with overlapping receptive fields."

>"`This is a very well developed research plan` aimed at testing complex cortical attractor networks in the extinction of spatial working memory..."

***
# Research

## Neural Networks, Computational Modeling, and Machine Learning

I have implemented and used `artificial neural networks` to answer many interesting questions and tell many fascinating stories.  Below are some examples of artificial neural networks I've built and used.  

###Continuous Attractor Recurrent Neural Network
How does the brain remember locations in space?  I built this `artificial recurrent line attractor neural network` to model how information is remembered.  The network uses recurrent connectivity to maintain the memory of an object even after that object has been removed from the network inputs.

[Continuous Attractor Recurrent Neural Network](https://github.com/CPapadim/Continuous-Attractor-Neural-Network)

![](https://github.com/CPapadim/cpapadim.github.io/raw/master/other/AttractorNetwork.png)

I've used this model to test a number of theories of how working memories are stored and transformed.  

### Artificial Neural Network with Backpropagation
How does your brain compute the trajectory your arm must move in order to reach an object?  It has to take into account where your eyes are looking, where your hand is now, and where the object is.   First, it needs to calculate the distance between your hand is and where your eyes are looking.  We found that to perform this computation the brain uses the response gain of neurons - by making the gain of eye position and hand position equal and opposite.

I built a `neural network with back propagation` to model these findings,  The network can `learn how to compute the reaching to objects in space through training` on a set of training data of objects and reaches.  When we examine the neurons in the network we find that, like what we see in the actual brain, the artificial neural network uses the response gain of neurons to compute the distance between the eye position and the hand position.  

[Artificial Neural Network with Backpropagation](https://github.com/CPapadim/Neural-Network-with-Back-Propagation)

![](https://github.com/CPapadim/cpapadim.github.io/raw/master/other/BackPropNN.jpg)

##Working Memory

I used the tools and computational models I mentioned above to ask and answer questions about how brains work.  Here you can find an example of a research project that involves collecting data, devising analyses, and building computational models to tell a story about how working memory works.

Here are two versions of the story.  A `technical` one and a `conceptual` one.  Take a look at the one you feel is most appropriate for you.  I personally prefer the conceptual one because I think it's more fun, and contains just as much of the story as the technical version.

[Intuitive Version](https://github.com/CPapadim/cpapadim.github.io/raw/master/other/AllPanels.pdf)

[Technical Version](https://github.com/CPapadim/cpapadim.github.io/raw/master/other/Poster.pdf)

These are some reviews of this work:

>“[This work] is `lucid` and provides an `excellent integration of neural data and theoretical modeling.`  The `insight` that apparently contradictory neural and behavioral aspects of the [data] can be reconciled by shifting movement fields is `clever` …”

>“That's a `terrific` job.  There were some really tough things there, and you did a darn good job of addressing them all.”

>“[This work] takes a psychophysical phenomenon, `tests a reasonable hypothesis` for the underlying neural basis, finds that the data conflict with that hypothesis, and `offers a reasonable alternative explanation.` [The] findings have `major implications` for our understanding of …”

>“The documentation of the spatial and temporal features of residual memory activity in FEF is `very carefully done and valuable.`”

>“[This work] to my view represents `a particularly nice coupling of theory and experiment.`”

***
# Consulting Work

Not all stories I tell have an academic focus.  I've also worked as a `consultant` and `project manager` to provide `analysis and data-based insights` for a number of companies in various industries.  Below you can see a couple of examples of the types of projects I worked on.  Due to NDAs and other confidentiality agreements, most of the content has been redacted, but you can get a general idea of the types of projects and work I've done.

[Project 1:  Evaluate investment opportunities](https://github.com/CPapadim/cpapadim.github.io/raw/master/other/BusinessAnalysisProject1.pdf)

[Project 2:  Evaluate viability of a new business venture and product](https://github.com/CPapadim/cpapadim.github.io/raw/master/other/BusinessAnalysisProject2.pdf)

I was nominated for an award for my work on some of these projects (though, as a Project Mananger, it was not possible for me to win).
>"I am writing to let you know that you were recently nominated for the `Outstanding Consultant award` for The BALSA Group. [...] your nomination is in recognition of your `hard work` on your most recent project and for BALSA as a whole. Though you were not eligible to win [because you are] a current Project Manager, we appreciate your continued dedication to our organization." 

***
# Fun with Machine Learning

##League Coach 
The game League of Legends is a competitive sports-like team game.  When I started playing this game I noticed that it does not have an easy, intuitive way to 'keep score'.  The team that is ahead is determined by many factors.  I decided to `do something about that.`  I created a new measure, the `probability to win`.  This measure takes into account all of the relevant factors, and condenses them into the single, intuitive measure.  

It works by first `training a Random Forest Classifier` that is trained on ~250,000 games.  It is trained on all of the complicated features that define the state of each game.  The model makes a prediction on whether a team will win after looking at all the features.  The more confident the model is that a team will win, the higher the 'probability to win' metric will be.  The model can make this prediction at any point in time during the game and performs with very high accuracy.

You can try it out by clicking the following link.   Please note that the web app queries the Riot API several times for game data, and that API has a time limit between queries.  Several queries are needed, and the app can take up to 30 seconds to produce a result due to this time limit.  

[Random Forest Classifier Model](http://league-coach.net/gsinput)

![](https://raw.githubusercontent.com/CPapadim/cpapadim.github.io/master/other/RFProbWin.png)

The web app also has another function.  It can `give advice to novice players` by analyzing their most recent games.  It uses an `event-triggered average` of player behaviors to determine what good players are doing before and after game-critical events.  It then compares user teams to these metrics and gives them advice on how to improve.

![](https://raw.githubusercontent.com/CPapadim/cpapadim.github.io/master/other/Advice.png)

For more information about how this project was done, you can see this slideshow:
[LeagueCoach Slides](http://www.slidego.com/go/18272)

You can find the code here:
[League Coach Code](https://github.com/CPapadim/LeagueCoach)

## Music Classification

People have used all sorts of cool methods to analyze music, from `spectrograms` to `Recurrent Neural Networks`.  I wanted to play with a different method.  I thought that music may be thought of as a language, so I used a model that makes use of `Latent Dirichlet Allocation` to extract `topics` from songs, and uses these topics to determine what song a short song-sample came from, and which composer wrote the song.  It worked surprisingly well!

[Music Classification](https://github.com/CPapadim/Music-Classification/blob/master/MusicClassification.ipynb)

***
# Teaching Data Science

I have also created and presented materials including seminars, hands-on labs, and tutorials to intuitively teach data science concepts to others.  Most of this is proprietary work, but you can see a public example at the following link:

[Customer Lifetime Value Webinar](https://www.datascience.com/blog/using-probabilistic-models-to-predict-customer-lifetime-value)

***
# The Arts

When I'm not playing with data I like to dabble in the arts.  You can see some of my previous digital art projects here:

[My deviantArt page](http://juryiel.deviantart.com/)
