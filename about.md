---
layout: page
title: About
permalink: /about/
--- 

I am Niels, 24 years old, living in Belgium.

I studied [Business and Information Systems Engineering](https://feb.kuleuven.be/eng/prospective-students/master-of-business-and-information-systems-engineering) (a Master of Science) at KU Leuven. I graduated magna cum laude (83%). This programme is a more technical version of Business Engineering. Besides business-oriented courses like management accounting, economics, and finance, I got technical courses including introduction to object-oriented programming, operating systems, computer networks, and so on. 

During my masters, I discovered deep learning by watching [this wonderful video](https://www.youtube.com/watch?v=aircAruvnKk&t=294s&ab_channel=3Blue1Brown) (and the subsequent ones) by 3Blue1Brown. I immediately fell in love with the way neural networks work, how they are able to recognize handwritten digits without being explicitly programmed. It felt like magic to me :) I also really liked the fact that they involve linear algebra, which was one of my favorite courses during my first year at university. A bit later, pure out of self-interest, I discovered and followed the lectures of Andrej Karpathy in his [cs231n course](http://cs231n.stanford.edu/) thaught at the University of Stanford. This course gave me the foundations to understand deep learning, to understand the forward pass, backward pass of neural networks, and so on. To me, cs231n (and especially the courses given by Karpathy) is a gem. All assignments are in Python (first in pure Numpy, later in Tensorflow/PyTorch). 

I also had the opportunity to follow a specialization as part of my masters called Architecture, Infrastructure and Big Data, and it included courses such as machine learning and natural language processing. When I discovered natural language processing, I also immediately fell in love with it. I got introduced to things like dependency parsing, constitutency parsing, semantic role labeling (more traditional NLP) and the wonderful [SpaCy](https://spacy.io/) package. It was also in the NLP course that I was introduced to the [Transformer](https://arxiv.org/abs/1706.03762), a "new architecture by Google" that replaced a lot of the complexity of RNNs by a stack of encoder layers relying on a thing called self-attention. I immediately wanted to know more about this architecture, so I read the paper and the [wonderful blog post by Jay Allamar](http://jalammar.github.io/illustrated-transformer/).  

My master thesis was about deep learning and natural language processing (my two favorite topics combined!). We investigated the applicability of deep learning to automatically construct (BPMN-like) business process flowcharts based on textual process descriptions. As I really wanted to use the Transformer as part of my master thesis and [HuggingFace Transformers](https://github.com/huggingface/transformers) did not yet exist, we used the [tensor2tensor package](https://github.com/tensorflow/tensor2tensor) by Google Brain to train a Transformer on Google Cloud. The project was a success, and we got a grade of 18 out of 20. You can find our paper and source code [here](https://github.com/NielsRogge/Description2Process). 

As I wanted to dive more deeply into the technical bits of deep learning, I decided to start working as an Applied AI Researcher at [Howest](https://www.howest.be/en), where I apply state-of-the-art deep learning algorithms (mostly NLP) for all kinds of business cases. I'm involved in several projects supported by [VLAIO](https://vlaio.be/nl), the Flemish Institute for Innovation and Entrepreneurship. Besides this, I'm consulting several companies to assist them in applying NLP. 

During my projects at Howest, I used HuggingFace Transformers more and more. However, I didn't fully understood the library and how the models/tokenizers are to be used. In August 2020, I decided to challenge myself: implement [TAPAS](https://arxiv.org/abs/2004.02349), an algorithm built by Google, and port it to HuggingFace Transformers to make it available for everyone. This was quite a challenge, as the original algorithm was written in Tensorflow 1 and had [lots of utility files](https://github.com/google-research/tapas). Moreover, the data format that was used by the Google authors of TAPAS were [Protocol Buffers](https://developers.google.com/protocol-buffers), which is not the easiest format. My goal was to implement the algorithm in PyTorch. However, after several months of coding, diving into the Github repo, I was satisfied with my implementation and opened up a pull request on the Transformers repo. After some time, my PR got merged! Moreover, the people of HuggingFace asked me to become part of the core contributors team of HuggingFace :) After that, I worked on several other models, including [improving](https://github.com/huggingface/transformers/pull/9476) [LayoutLM](https://arxiv.org/abs/1912.13318) by Microsoft Research, [added](https://github.com/huggingface/transformers/pull/10950) the [Vision Transformer (ViT)](https://arxiv.org/abs/2010.11929) by Google AI and [added](https://github.com/huggingface/transformers/pull/11056) [Data-efficient Image Transformers (DeiT)](https://arxiv.org/abs/2012.12877) by Facebook AI to the library. 

### Technologies
At the time of writing, I'm mostly working with:
- Programming languages: Python
- Tools (libraries): PyTorch, HuggingFace Transformers, Flair NLP (I do know the basics of Tensorflow and JAX/FLAX)
- IDEs: Visual Studio Code, Google Colab, Jupyter Notebook

### Contact me

You can contact me on the following email address:

[niels.rogge1@gmail.com](mailto:niels.rogge1@gmail.com)
