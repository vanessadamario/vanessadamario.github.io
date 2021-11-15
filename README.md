# Vanessa D'Amario

I am a postdoctoral researcher at Fujitsu and a visitor affiliate 
at Massachusetts Institute of Technology (MIT) since November 2021. 
I joined MIT first as a PhD visiting student (December 2019 - March 2020), then as a postdoctoral researcher (April 2020 - October 2021). 
I got a PhD in computer science in May 2020 from Università degli Studi di Genova (Genoa, Italy). I previously graduated in physics (2015) 
and high energy physics (2016) at the Università degli Studi di Genova.

## My vision

The main goal of my career path is to build knowledge and instruments that contribute to improve humanity. 
Nowadays our society offers a rich variety of resources (in diagnostic, education, wellness) which are too often available 
to very restricted groups of people. I want to work towards the goal of reducing this gap and make 
technologies accessible to anyone.
In this regard, many reasons make me believe that the research I am doing today is going in the right direction.

To be more specific, I have been working at the edge of Machine Learning (ML) research and computational tools for neuroscience (clinical research).

What motivates my research in ML is that too often ML methods are inaccessible to many. 
In most of the cases, training such methods require high computational resources and very large amount of data, which not everyone has access to,
especially in countries with low income and poor research investments. 
Even when both are available, as it is often the case in Western countries, 
ML methods might suffer from bias. Due to the nature of current ML methods and their scarce interpretability,
this bias is hardly traceable to some factor in the data. 
In addition to this, data distribution shifts might reduce the predictive power of such tools on different populations than the
one used at training. All these factors reduce the usability of many ML methods. 
On purposely, I have not mentioned any specific application, because this holds for any dataset
coming from a data population with limited variety.
Fighting against such limitations and evaluating strategies to overcome poor predictive performance due to bias have constituted
a large portion of the time I have been spending at MIT. Despite being fundamental research in ML, 
I see clearly how the questions I am addressing today will help to envision better and more equal algorithms tomorrow.

On the other hand, the use of computational methods in clinical neuroscience have represented an important part of my research interests.
The reasons of my excitement here are two-fold: first, computational methods help to accelerate scientific discoveries, which 
is quite amazing, given the complexity of the brain and how fascinating this organ is. Then, clinical findings 
help doctors in decision making and might guide to new research treatments.
My work in this field has been possible thanks to the collaboration with neurophysiologists at
Ospedale Pediatrico Istituto Giannina Gaslini di Genova (Genoa, Italy), one of the most prominent research centers and children clinics in Europe.
In this context, I see computational tools and ML as a great opportunity to actively help society and improve people's lives.

In the following, there is a map that motivates more broadly but concisely the motivations to the research in intelligence. 
I see at least three main reasons that drive this research, and I am curious of the many more that you can think of!
All of them have strong intersections and provide inspirations and solutions to one another.

<p align="center">
  <a href="https://vanessadamario.github.io/">
    <img src="assets/img/website_fig1.png" width="100%">
  </a>
</p>


## Projects
**How modular should NMN be for systematic generalization?** 
This work deals with the problem of bias in Visual Question Answering (VQA). 
For us, as humans, recognizing a blue dog in an image would not require much of effort, 
despite we had never seen a blue dog before. The performance of state-of-the-art algorithms 
on such counterintuitive examples are nonetheless very poor. In this project, we found a strategy 
to alleviate the low generalization performance of modular architecture in VQA, which can lead to 
high increase in performance (high to 20%). We observe that increasing the modularity of these networks, 
especially at their first stages, by enforcing separation into different computational units 
(e.g., some involved for the inference of colors, other for the inference of shapes) is of vital importance 
for generalization to unseen combinations.

**Unnecessary dimensions harm data efficiency in deep learning.** 
In this project, I focused on the limitation of neural networks to a different type of over-parameterization 
from the one typically discussed in the machine learning literature, which is the over-parameterization at the input level. 
Images, for example, often contain backgrounds which are clearly unrelated to the foreground. 
How robust neural networks are to the presence of these unnecessary dimensions and how this affect their data efficiency, 
was unknown. What we found is that the presence of such unnecessary dimensions hardly impact neural networks,
leading to a degradation of the networks' performance. This finding has important connections to attention and biological mechanisms as the fovea, 
and it leads to the hypothesis that those biological mechanisms might be the reason of higher data efficiency in humans.

**Phasic REM and its suppressive role on interictal spikes in Electrical Status Epilepticus during Sleep.**
Electrical Status Epilepticus during Sleep (ESES) is a rare form of epilepsy that affect children and leads to severe 
cognitive decline over the years. It consists in an abundant presence of high intensity epileptic activity which manifest 
during sleep. Some forms of epilepsy benefit from phasic REM (a micro-state of REM sleep), since this sleeping stage inhibits the 
epileptic activity. The goal of this project was to verify if phasic REM has the same inhibitory role in such an aggressive form of epilepsy as ESES. 
In this context, together with my collaborators, I built a semi-automatic algorithm for the identification 
of epileptic waves in the signal. The count of these waveforms across the different sleep stages allowed us to test the 
inhibitory hypothesis of the phasic REM sleep in ESES. 

## Publications
<a id="1">[1]</a> 
Vanessa D'Amario, Tomotake Sasaki, Xavier Boix (2021). 
**How Modular Should Neural Module Networks Be for Systematic Generalization?**
Proceedings in Advances in Neural Information Processing Systems 34.

<a id="1">[2]</a> 
Vanessa D'Amario, Sanjana Srivastava, Tomotake Sasaki, Xavier Boix (2021). 
**The Foes of Neural Network's Data Efficiency Among Unnecessary Input Dimensions**,
Under review.

<a id="1">[3]</a> 
Stephen Casper, Xavier Boix, Vanessa D'Amario, Lin Guo, Martin Schrimpf, Kasper Vinken, Gabriel Kreiman (2020). 
**Frivolous Units: Wider Networks Are Not Really That Wide**,
Proceedings of the AAAI Conference on Artificial Intelligence.


<a id="1">[4]</a> 
Thea Giacomini, Gianvittorio Luria, Vanessa D'Amario, Carolina Croci, Matteo Cataldi, Maria Piai, Giulia Nobile, Oliviero Bruni, Alessandro Consales, Maria Margherita Mancardi, Lino Nobili (2021). 
**On the role of REM sleep microstructure in suppressing interictal spikes in Electrical Status Epilepticus during Sleep**,
Under review.

<a id="1">[5]</a> 
Vanessa D'Amario (2020). 
**Machine Learning for Understanding Focal Epilepsy**, 
PhD Dissertation in Computer Science, Università degli Studi di Genova.


