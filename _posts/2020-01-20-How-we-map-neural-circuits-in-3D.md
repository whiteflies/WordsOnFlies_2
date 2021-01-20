**How we map the neural network in 3D w/ synaptic resolution**

You probably wondered at some point if this is possible and if so how?

So I will try my best to answer here.

Why we do it? Discovering the neural circuit architecture underlying behavior is key to understanding computational models of network activity. It's essentially reverse engineering on the brain; by seeing its structure -and omplementing it with behavioural experiments - we can relate it to its functions.

Is this easy? No. Has technology made it (kinda) easy? Yes

So how do you reverse engineer the brain? In neuroscience this is what we call **connectomics** (as the name implies, the study of the brain connectivity). In connectomics, the brain is sliced into very thin sections (~70μm), then slowly reconstrcted computionally. The reconstruction just means  identifying and marking (tracing) a specific cell across all brain sections.

As an analogy, let's say we slice up an orange into 20 thin transverse sections looking like fig 1. If I ask you to color one triangle from the orange across all 20 sections, you would find that you colored an entire orange segment (fig 2), and what's more if you stack up the slices on top of each other you could simulate how it would look in 3D.



![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/71a4274d-7e86-485f-9c40-3a6695659695/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/71a4274d-7e86-485f-9c40-3a6695659695/Untitled.png)

Fig 1

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6e71518c-1edf-44bb-99a5-6e04e783fb7e/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6e71518c-1edf-44bb-99a5-6e04e783fb7e/Untitled.png)

Fig 2



This is what we do with the brain, only the orange is the brain and the orange segments are the neurons. In addition to shape, what we can also capture by imaging the brain is such a way, is synapses between neurons (identifiable through specific structural features), and in this way we acquire the a map of the whole brain connectivity (connectome).