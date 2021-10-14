# How online computer games are helping drive scientific discovery 
#### BINFsights<br />Issue 12
###### Originally published 12 October 2021<br />Written by Anthony Nguyen<br />Edited by Cam McMenamie and Gabrielle Younes 

<br />

> “*...integrating games and citizens science can provide a virtually limitless human computation engine for scientists.*”  
>     — Attila Szantner, CEO and Co-Founder of MMOS

<br />

In the previous release of BINFsights, we explored how complex biological questions were being answered by applying cutting-edge, machine learning techniques.
To recap, data needed to be collected and prepared from a variety of sources before being fed into a model that could learn the patterns within the data and output
accurate predictions.

Needless to say, these methods are incredibly promising. However, we only touched upon the details involved in those first stages of the workflow: the data collection itself.


<p float="left">
  <img src="/img1.png" width="100" />
  <img src="/img2.png" width="100" /> 
</p>


< IMAGE >

 ![space-1.jpg](https://blog-assets.thedyrt.com/uploads/2019/01/shutterstock_1033306540-1.jpg) <b>Image Credits - Fig.2 - 4K Mountains Wallpaper</b>|
 
 
 ### A dive into data
 
 Machine learning tasks are either supervised or unsupervised. Supervised simply means that our model is trying to learn how to map an input to an output. For instance, we can give our model pictures of trees, some of which contain birds. If we label these as containing birds, we are supervising the model and training it to better classify future images; recognising whether it contains a bird. 
 
 The downside to these sorts of tasks is the amount of labelled data needed to train a model well. Although there are currently many repositories of data, those that contain labelled data are often the result of hours of expert efforts or were collected through outsourcing the task of labelling, as paid micro-tasks. Adding to the problem, integrating data from heterogeneous sources is not only tedious but also time-consuming. Even once this data has been cleaned up and is ready for use, machine learning models may still struggle to accurately recognise and classify entities that appear once or twice in the dataset; what we call *class imbalance*. 

### Citizen Science

An exciting approach to address these pitfalls is the idea of citizen science, which *National Geographic* describes as the engagement of the public in advancing scientific knowledge. This can range from data collection and monitoring to solving complex computational problems. The idea of involving the everyday public to increase data volumes is not trivial. In fact, during the pandemic with more people staying at home, the upswing in citizen science project participation has provided valuable data to forward research. The notion of voluntary tasks is not only scalable, helping in cases of severe class imbalance, but is also invaluable in engaging the wider community in science.

>  “Humans are great at recognising patterns.”

<br> </br>

[Hoot Detective](https://hootdetective.net.au) is one such example of how the ecology and conservation field is actively utilising citizen science in Australia to speed up the discovery process and improve on algorithms which recognise animal sounds. Humans are great at recognising patterns. The idea is for participants to listen to short audio clips from an archive and identify which creatures, for example, frogs and birds, can be heard in the clip. Such an algorithm can help understand how the Australian biodiversity might be changing as the environment changes after bushfires and the like.

### Help from the online gaming community

If that isn’t exciting enough, there have already been efforts to gamify these projects in order to garner a larger public base. By incorporating scientific problems into their gameplays or designs, game creators are hoping to attract a community of bright minds and talents, or simply to leverage insights from massive-scale crowd participation. 

The [EterRNA Project](https://eternagame.org/about) engages players in the structural biology problem of RNA folding. Players are given a target RNA structure, which might consist of knots, lattices, and loops, and are tasked to solve puzzles ordering RNA nucleotides (`A`, `C`, `G`, and `U`) before submitting their RNA model for community review. The gaming community then holds weekly votes on the most promising RNA design, which is subsequently sent off to be synthesised in a laboratory to compare the player/computer-generated models with the actual folding patterns that occurred.  RNA design is notoriously difficult, however, by generating such promising hypotheses in this way, computer models can be iteratively improved with the ambition of discovering a consistent and repeatable set of folding rules that will allow researchers to accurately design a target RNA shape in silico. Arguably, this could prove extremely useful in designing novel bioactive compounds.

[Project Discovery](https://www.eveonline.com/discovery), a minigame featured in the popular video game *EVE Online*, was a collaboration between CCP Games and researchers which saw 33 million image classifications generated by a community of over 300 thousand players in the year 2018. As part of a paper published in Nature Biotechnology, fluorescent microscopy images from the Human Protein Atlas were incorporated into challenges part of EVE Online, which saw players identifying one or more cellular structures (e.g., nucleus, cytoplasm, microtubule, etc.) that were being pictured in image samples. After completing a basic in-game tutorial, images were introduced in increasing levels of difficulty and involved a large number of cell types as well as proteins with multiple localisations. 

As the first study of its kind, the researchers set out to assess the quality and consensus across players’ image classifications as well as their potential usefulness in training deep-learning models (a subfield of machine learning) to better understand how proteins were localised and distributed within human cells and tissues.

Benchmarked against a deep learning tool developed to classify microscopy images, the players were outperformed on common patterns of protein localisation. However, interestingly players excelled at recognising and marking out rarer and more unusual patterns. By combining the player’s annotations with the deep learning model, the model was able to predict a range of protein localisation patterns with incredible accuracy. 

< IMAGE >

### How sustainable is Citizen Science?

Engaging the broader public in big data projects has become increasingly popular in the scientific community. There are concerns that this engagement and ‘buzz’ is only short-term and are often only focussed on a few biological questions, leading to a dip in participation after the first few days following release.

To combat this, platforms like EteRNA and Project Discovery regularly release new challenges and game mechanics for their player base. Examples include the OpenVaccine challenge, recently hosted by EteRNA, in which the problem of designing stable mRNAs is being tackled. Project Discovery rewards players of their game with in-game currencies and exclusive badges, whereas Hoot Detective was an initiative heavily promoted during the 2021 Australian National Science Week. 

In actively encouraging players to participate, citizen science is emerging as a promising means to complement the existing computational methods in ecology through to molecular biology.





