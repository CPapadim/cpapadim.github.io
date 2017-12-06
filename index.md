# Hello, I'm Charalampos (Harry),

| <img style="width:99px; max-width:99px" src = "https://github.com/CPapadim/cpapadim.github.io/raw/master/other/Photo25.png"> |I'm an experienced Data Scientist and Researcher with over a decade of experience in modeling and analytics, specializing in both applied and theoretical machine learning, as well as experimental design.  I'm a `quantitative storyteller`, and passionate about making data science more accessible through intuitive communication of technical concepts.  I've worked on a number of business challenges, including sales forecasting, marketing problems, image processing, recommendation systems, and many others.  Previously, I worked as a computational neuroscience researcher at Washington University in St. Louis, where I modeled the dynamics of working memory neural circuits.|
| ------------ | ------------- |
| | [LinkedIn](https://www.linkedin.com/in/charalampospapadimitriou/) |

On this page you will find a few examples of some of the projects I've worked on.  If you have any questions about anything on this page or need to reach me for any reason, you can contact me at papadimitriou.c@gmail.com 

***
<div class="section-content">
<h1>Teaching Data Science</h1>

I have created and presented materials including seminars, hands-on labs, and tutorials to intuitively teach data science concepts to others, including Data Scientists and C-Level executives.  Most of this is proprietary work, but you can see some public examples below.

</div>

<div class="section-content">
<h2>Image Recognition With Deep Learning</h2>

In this seminar I cover concepts behind deep convolutional neural network in the context of image recognition.  There is also a hands on lab in which we build a simple CNN from scratch, and use data augmentation methods to improve generalizability of the network.  We also learn how to use a pre-trained network and fine-tune it to our data.  Finally, we talk about how to interpret neural network models to make sure they are using the correct parts of the images in their tasks.
<br><br>
<a href="https://www.datascience.com/typ/image-recognition-with-deep-learning?submissionGuid=f38f78e8-227b-4cbb-9fe3-84d3601ce44a">Image Recognition With Deep Learning Webinar</a>
<br><br>
<img src = "https://github.com/CPapadim/cpapadim.github.io/raw/master/other/nnfilters.PNG">
</div>

<div class="section-content">
<h2>Customer Lifetime Value</h2>

My Customer Life Value seminar.  The seminar includes a 1-hour hands on lab in which we use MCMC methods (PyMC3) to build and fit a Pareto / NBD model.
<br><br>
<a href = "https://www.datascience.com/blog/using-probabilistic-models-to-predict-customer-lifetime-value">Customer Lifetime Value Webinar</a>
<br><br>
<img src = "https://github.com/CPapadim/cpapadim.github.io/raw/master/other/clvseminar.PNG">
</div>

<div class="section-content">
<h2>Overview of Supervised Machine Learning</h2>

In this series I cover supervised learning.  I start by covering the two competing goals of supervised learning (reducing error, and regularizing to reduce complexity, aka. bias / variance tradeoff, aka. over / underfitting).  I then discuss theory and intuition behind each algorithm, and provide code snippets for simple implementations.  
<br><br>
<a href = "https://github.com/CPapadim/ds_tutorials/blob/master/supervised_learning/supervised-learning-part-1.ipynb">Part 1 - Algorithms With Linear Decision Boundaries</a>
<br><br>
<a href ="https://github.com/CPapadim/ds_tutorials/blob/master/supervised_learning/supervised-learning-part-2.ipynb">Part 2 - Algorithms With Non-Linear Decision Boundaries</a>

</div>

<div class="section-content">
<h2>Connecting Tableau to Model APIs</h2>
This tutorial includes both recorded videos and blog-style posts and was created to help those looking to connect Tableau to deployed model APIs as data sources to feed dashboards.  It includes example code for setting up a Flask server, as well as code showing how to use Tableau's Javascript Web Data Connector.
<br><br>
<a href = "http://connecttableau.datascience.com/">Connecting Tableau to Model APIs</a>
<br><br>
<img src = "https://github.com/CPapadim/cpapadim.github.io/raw/master/other/api_to_tableau.png">
</div>


***
<div class="section-content">
<h1>Research</h1>

I've been involved in research for many years, focusing on modeling complex systems, including the dynamics of working memory brain circuits, human vision and protein folding.  Below you can see some examples of my research work.
</div>

<div class="section-content">
<h2>Neural Networks, Computational Modeling, and Machine Learning</h2>

I have implemented and used <code class="highlighter-rouge">artificial neural networks</code> to answer many interesting questions and tell many fascinating stories.  Below are some examples of artificial neural networks I've built and used.  
</div>

<div class="section-content">
<h3>Continuous Attractor Recurrent Neural Network</h3>
How does the brain remember locations in space?  I built this <code class="highlighter-rouge">artificial recurrent line attractor neural network</code> to model how information is remembered.  The network uses recurrent connectivity to maintain the memory of an object even after that object has been removed from the network inputs.
<br><br>
<a href = "https://github.com/CPapadim/Continuous-Attractor-Neural-Network">Continuous Attractor Recurrent Neural Networks</a>
<br><br>
<img src = "https://github.com/CPapadim/cpapadim.github.io/raw/master/other/AttractorNetwork.png">
<br><br>
I've used this model to test a number of theories of how working memories are stored and transformed.  
</div>

<div class="section-content">
<h3>Artificial Neural Network with Backpropagation</h3>
How does your brain compute the trajectory your arm must move in order to reach an object?  It has to take into account where your eyes are looking, where your hand is now, and where the object is.   First, it needs to calculate the distance between your hand is and where your eyes are looking.  We found that to perform this computation the brain uses the response gain of neurons - by making the gain of eye position and hand position equal and opposite.
<br><br>
I built a <code class="highlighter-rouge">neural network with back propagation</code> to model these findings,  The network can <code class="highlighter-rouge">learn how to compute the reaching to objects in space through training</code> on a set of training data of objects and reaches.  When we examine the neurons in the network we find that, like what we see in the actual brain, the artificial neural network uses the response gain of neurons to compute the distance between the eye position and the hand position.  
<br><br>
<a href="https://github.com/CPapadim/Neural-Network-with-Back-Propagation">Artificial Neural Network With Backpropagation</a>
<br><br>
<img src="https://github.com/CPapadim/cpapadim.github.io/raw/master/other/BackPropNN.jpg">
</div>

<div class="section-content">
<h2>Working Memory</h2>

I used the tools and computational models I mentioned above to ask and answer questions about how brains work.  Here you can find an example of a research project that involves collecting data, devising analyses, and building computational models to tell a story about how working memory works.
<br><br>
Here are two versions of the story.  A <code class="highlighter-rouge">technical</code> one and a <code class="highlighter-rouge">conceptual</code> one.  Take a look at the one you feel is most appropriate for you.  I personally prefer the conceptual one because I think it's more fun, and contains just as much of the story as the technical version.
<br><br>
<a href="https://github.com/CPapadim/cpapadim.github.io/raw/master/other/AllPanels.pdf">Intuitive Version</a>
<br><br>
<a href="https://academic.oup.com/cercor/article/3056352">Technical Version - Paper</a>
<br>
<a href="https://github.com/CPapadim/cpapadim.github.io/raw/master/other/Poster.pdf">Technical Version - Poster</a>
</div>

These are some reviews of this work:

>“[This work] is `lucid` and provides an `excellent integration of neural data and theoretical modeling.`  The `insight` that apparently contradictory neural and behavioral aspects of the [data] can be reconciled by shifting movement fields is `clever` …”

>“That's a `terrific` job.  There were some really tough things there, and you did a darn good job of addressing them all.”

>“[This work] takes a psychophysical phenomenon, `tests a reasonable hypothesis` for the underlying neural basis, finds that the data conflict with that hypothesis, and `offers a reasonable alternative explanation.` [The] findings have `major implications` for our understanding of …”

>“The documentation of the spatial and temporal features of residual memory activity in FEF is `very carefully done and valuable.`”

>“[This work] to my view represents `a particularly nice coupling of theory and experiment.`”

***
<div class="section-content">
<h1>Analysis Packages</h1>
In the pursuit to understand and tell the right story, we often need to build custom tools.  Below you can find some of the analysis packages I've built or contributed to over the years.
</div>

<div class="section-content">
<h2>Signal Processing Toolkit</h2>

When the Snyder Laboratory wanted to expand into analysis of local field potentials, I stepped up to develop this package to help me and other lab mates analyze and understand how brains work.  It can analyze <code class="highlighter-rouge">time series</code> of action potentials and local field potentials from the brain in both the <code class="highlighter-rouge">frequency</code> and <code class="highlighter-rouge">time</code> domains to help users uncover how these different brain signals relate to each other and contribute to driving behavior.  
<br><br>
<a href="https://github.com/CPapadim/Signal-Processing-Toolkit">Signal Processing Toolkit</a>
<br><br>
<img src="https://raw.githubusercontent.com/CPapadim/cpapadim.github.io/master/other/LFP1.png"><br>
<img src="https://raw.githubusercontent.com/CPapadim/cpapadim.github.io/master/other/LFP2.png">

This tool is now being used by a new generation of upcoming scientists in the Snyder Laboratory. 
</div>

<div class="section-content">
<h2>Behavioral and Neural Analysis Toolkit</h2>

I wrote this package to determine how neuron spikes are related to behavior.  It can analyze and quantify behavior, especially in the context of eye movements and working memory.  It can also align neural data to these behaviors to help determine how neural activity changes drive these behaviors.  
<br><br>
<a href ="https://github.com/CPapadim/Behavioral-and-Neural-Analysis-Toolkit">Behavioral and Neural Analysis Toolkit</a>
<br><br>
<img src="https://raw.githubusercontent.com/CPapadim/cpapadim.github.io/master/other/BehaviorNeural.png">

</div>
***

<div class="section-content">
<h1>Experimental Design</h1>

In order to tell a good story you have to do the <code class="highlighter-rouge">right experiment</code>.  Below is a document outlining one of my experimental designs to study working memory.  This design won a highly competitive <code class="highlighter-rouge">N.R.S.A grant (~$150,000 in funding) from the National Institutes of Health</code>.
<br><br>
<a href="https://github.com/CPapadim/cpapadim.github.io/blob/master/other/ExperimentalDesign.pdf">Experimental Design Document</a>
</div>

These are some of the reviews of the design:
>"`Very clever set of experiments` to determine whether decay of behavioral spatial working memory can be related to changes in the correlated tuning curves of neurons in DLPC with overlapping receptive fields."

>"`This is a very well developed research plan` aimed at testing complex cortical attractor networks in the extinction of spatial working memory..."

***

<div class="section-content">
<h1>Consulting Work</h1>

I've also worked as a <code class="highlighter-rouge">consultant</code> and <code class="highlighter-rouge">project manager</code> to provide <code class="highlighter-rouge">analysis and data-based insights</code> for a number of companies in various industries.  Below you can see a couple of examples of the types of projects I worked on.  Due to NDAs and other confidentiality agreements, most of the content has been redacted, but you can get a general idea of the types of projects and work I've done.
<br><br>
<a href="https://github.com/CPapadim/cpapadim.github.io/raw/master/other/BusinessAnalysisProject1.pdf">Project 1:  Evaluate investment opportunities</a>
<br><br>
<a href="https://github.com/CPapadim/cpapadim.github.io/raw/master/other/BusinessAnalysisProject2.pdf">Project 2:  Evaluate viability of a new business venture and product</a>
</div>

I was nominated for an award for my work on some of these projects.

>"I am writing to let you know that you were recently nominated for the `Outstanding Consultant award` for The BALSA Group. [...] your nomination is in recognition of your `hard work` on your most recent project and for BALSA as a whole. Though you were not eligible to win [because you are] a current Project Manager, we appreciate your continued dedication to our organization." 

***
<div class="section-content">
<h1>Fun with Machine Learning</h1>

On occasion, I play with machine learning models to tackle interesting projecs.  This is a great way to continue to improve and learn, while having fun at the same time.  Some of these are highlighted below.
</div>

<div class="section-content">
<h2>League Coach</h2>
The game League of Legends is a competitive sports-like team game.  When I started playing this game I noticed that it does not have an easy, intuitive way to keep score.  The team that is ahead is determined by many factors.  I decided to <code class="highlighter-rouge">do something about that.</code>  I created a new measure, the <code class="highlighter-rouge">probability to win</code>.  This measure takes into account all of the relevant factors, and condenses them into the single, intuitive measure.  
<br><br>
It works by first <code class="highlighter-rouge">training a Random Forest Classifier</code> that is trained on ~250,000 games.  It is trained on all of the complicated features that define the state of each game.  The model makes a prediction on whether a team will win after looking at all the features.  The more confident the model is that a team will win, the higher the <code class="highlighter-rouge">probability to win</code> metric will be.  The model can make this prediction at any point in time during the game and performs with very high accuracy.
<br><br>
<img src="https://raw.githubusercontent.com/CPapadim/cpapadim.github.io/master/other/RFProbWin.png">
<br><br>
The web app also has another function.  It can <code class="highlighter-rouge">give advice to novice players</code> by analyzing their most recent games.  It uses an <code class="highlighter-rouge">event-triggered average</code> of player behaviors to determine what good players are doing before and after game-critical events.  It then compares user teams to these metrics and gives them advice on how to improve.
<br><br>
<img src="https://raw.githubusercontent.com/CPapadim/cpapadim.github.io/master/other/Advice.png">
<br><br>
For more information about how this project was done, you can see this slideshow:
<a href="http://www.slidego.com/go/18272">League Coach Slides</a>
<br><br>
You can find the code here:
<a href="https://github.com/CPapadim/LeagueCoach">League Coach Code</a>
</div>

<div class="section-content">
<h2>Music Classification</h2>

People have used all sorts of cool methods to analyze music, from <code class="highlighter-rouge">spectrograms</code> to <code class="highlighter-rouge">Recurrent Neural Networks</code>.  I wanted to play with a different method.  I thought that music may be thought of as a language, so I used a model that makes use of <code class="highlighter-rouge">Latent Dirichlet Allocation</code> to extract <code class="highlighter-rouge">topics</code> from songs, and uses these topics to determine what song a short song-sample came from, and which composer wrote the song.  It worked surprisingly well!
<br><br>
<a href="https://github.com/CPapadim/Music-Classification/blob/master/MusicClassification.ipynb">Music Classification</a>

</div>
***
<div class="section-content">
<h1>The Arts</h1>

When I'm not playing with data I like to dabble in the arts.  You can see some of my previous digital art projects here:
<br><br>
<a href="http://juryiel.deviantart.com/">My deviantArt page</a>
</div>
