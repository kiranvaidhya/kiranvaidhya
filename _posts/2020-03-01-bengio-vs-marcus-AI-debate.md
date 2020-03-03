---
toc: true
description: Connectionism vs Symbolism
categories: [deep-learning, AI, robustness]
---
# Bengio vs Marcus AI debate

The war between connectionism and symbolism has regained traction following some of the rather conspicuous failures of the current deep learning system used in practice. Gary Marcus authored the popular science non-fiction book, [Rebooting AI](https://www.amazon.com/Rebooting-AI-Building-Artificial-Intelligence-ebook/dp/B07MYLGQLB) to highlight the drawbacks of deep learning systems and to promote the Symbolic AI program. Ranging from the errors seen in [self-driving cars](https://www.vox.com/future-perfect/2020/2/14/21063487/self-driving-cars-autonomous-vehicles-waymo-cruise-uber) to [skin cancer diagnosis](https://www.sciencedirect.com/science/article/pii/S0022202X18322930), deep learning systems have consistently showcased their brittle nature. However, it is important to not forget the significant advances in machine learning triggered by the development of training procedures for neural networks using C/CUDA on GPUs. Hand-crafted features have been replaced by deep neural networks in virtually every domain you can think of. The 2010s has been one of the most successful decades for Artificial Intelligence.

## Connectionism vs Symbolism

The spat came to light when Yann LeCun posted this rather alarming tweet.

{% twitter https://twitter.com/ylecun/status/1201233472989356032 %}

This was a direct dig at Gary Marcus who was pushing for the field to reinvest in Symbolic AI. Another major criticism of deep learning is that neural networks are “black-box” systems lacking understandable explanations which can highlight their decision making processes.

{% twitter https://twitter.com/geoffreyhinton/status/1230592238490615816 %}

This takes me to the fundamental differences between Connectionism and Symbolism. Connectionism is grounded on the idea that there exists an universal learning algorithm which can be trained without hand-crafting a large set of priors. Symbolism, however, says you cannot develop a robust system without encoding a rich knowledge base similar to feature engineering (the very idea that deep learning has been replacing). This is where Gary Marcus differs from Yoshua Bengio, Yann LeCun and Geoffrey Hinton (the Turing Award winners).

Gary Marcus has been pretty [vocal](https://thegradient.pub/an-epidemic-of-ai-misinformation/) in his idea that deep neural networks trained on large datasets can be brittle. He has also very rightly called out Open AI for their questionable management driven decisions showcased in [GPT-2](https://thegradient.pub/gpt2-and-the-nature-of-intelligence/). Bengio continues to advocate further research into [deep learning](https://www.ibm.com/watson/advantage-reports/future-of-artificial-intelligence/yoshua-bengio.html). He hypothesizes that objective reasoning, understanding cause and effect and building good world models can be achieved by deep learning. Yann LeCun and Geoffrey Hinton have started championing self-supervised learning. It remains to be seen if they can be achieved through neural networks through self/weakly/un-supervised learning methodologies.

{% twitter https://twitter.com/ylecun/status/1123235709802905600 %}

{% twitter https://twitter.com/devvarma/status/1228581787816742913 %}

## Conclusion

I'm not an expert in symbolism but it's important to isolate concerns regarding marketing and scientific progress. Deep learning is not about exactly replicating human intelligence nor is it about reverse engineering the human brain. When the first airplane took off from Earth, it didn’t have to flap its wings to mimic birds. Deep learning is simply a machine learning methodology grounded on elegant computational mathematics. Significant progress has been made on several narrow domains and there's no technical reason for us to shift the methodology. 

Should we slow down the research and ground the progress on first principles? Yes. Current implementations of backpropagation for fast training are not deterministic. Should we regulate AI products in the market and dial down on extravagant claims? Yes. Should we put more resources into a completely different paradigm? I'm not so sure.

Gary Marcus probably has the best interests in terms of scientific research and development but it's hard to make sense of his proposed alternatives. At the time of this writing, Marcus has published some papers about the drawbacks of deep learning systems. I'm not particularly aware of any of his peer-reviewed publications on Symbolic AI that's gained sufficient traction at top conferences or journals. He is the CEO of [Robust AI](robust.ai) but it needs more than a startup and writing popular science books to drive the field forward in a different direction. It needs collaborations with major institutions and companies. If Gary Marcus really believes in the Symbolic AI program, I would kindly recommend him to fund research projects in collaboration with the MITs, Stanfords and MILAs and publish top quality peer-reviewed papers on Symbolic AI to steer the field in the appropriate directions.

