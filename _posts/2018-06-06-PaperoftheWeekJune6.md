---
layout: post
title: Paper of the Week - June 6th
---

This week's paper can be found here: [A high-impedance detector-array glove for magnetic resonance imaging of the hand](https://www.nature.com/articles/s41551-018-0233-y)

Note: This paper is behind a paywall on the Nature Biomedical Engineering website. Unfortunately, this is all too common for scientific literature, making it difficult for non-scientists (or even scientists who are not from 
the same field) to access current research. If you do have access through your institution, I'd encourage you to check it out! If you don't, I'd encourage you to join the discussion over open access publications that the academic community 
is currently having. There is also an [earlier paper](https://arxiv.org/pdf/1709.03416.pdf) from this lab on a similar topic. 

 **Welcome back to Paper of the Week!**

We are two for two on papers that I found via Twitter! I'm not sure if that is a good thing, but I can tell you that this is a really cool paper
and I am really excited to write about it. 

Note #2: Have a cool paper that you'd like to see me talk about? Thought this paper was cool and want to talk about it? Have questions about 
STEM, undergrad, grad (haven't started yet so no promises there), or anything else? Tweet it to me -> [@jordanbharrod](https://twitter.com/jordanbharrod)

This week's paper is titled "A high-impedence detector-array glove for magnetic resonance imaging of the hand" and it comes from New York University's School of Medicine. 

Why is this paper so cool? Well, for anyone who has ever had an MRI, we know that they are rather large and unbecoming machines that force our bodies to 
bend to their will (Yes, it's not that bad, but still). During my undergrad, I volunteered for a bunch of fMRI studies that required me to sit in MRIs for a couple hours every week (it was worth it $$$), so 
I've been in enough different MRI machines to know that, in most clinical cases, there are two rules: 

1. You can either have high spatial resolution (really detailed images) or high temporal resolution (a lot of images in a short period of time), but 
not both. 
2. Don't move. 

The second rule is the one that really gets to us - the people getting the MRI - because what if you have an itch? Or you have to sneeze? 
Hopefully, you have the self-control to restrain yourself, because otherwise, you might have to retake that MRI. 

Why is that the case? Well, it has to do with the way that MRI images are taken and reconstructed. If you're interested in an in-depth review, 
check out [this website](http://mriquestions.com/index.html), which I found to be really useful when I was taking the medical imaging class that 
I would later go on to TA. In short, the raw MRI data contains information about where that each data point should be in the recontructed image, and how bright that data point should be. 
When you move, the information about where that data point should be is changed, and the reconstructed image does not accurately represent your body. 

This second rule is inconvenient for another reason - MRI is typically used to image tissues (as opposed to bone), and could be used to monitor 
how tissues move after an injury, which currently can't be done. This has applications in areas like sports medicine, where muscle injuries are common 
but can be hard to diagnose. 

But we're in luck! This detector array glove has the potential to erase that second rule by allowing doctors to image a moving hand during an MRI without the reconstruction 
problems that we would normally have. The glove uses high-impedence coils (MRIs typically use low impedence) that are attached to your standard glove, which you would 
then wear into the MRI machine for imaging. 

Why high impedence over low impedence? Let's go back to how MRI images are taken. When you lay down in an MRI for a scan, the machine uses extremely strong magents to apply 
a magnetic field to all of the protons in your body, aligning them. Then, another field is applied, causing protons in different tissues to 
move away from this alignment to varying degrees. The MRI machine's detector records the energy each proton releases as they realign with the original magnetic field. The detector is 
typically made up of those low impedence coils. 

Impendence is a measure of how much resistance to current flow something exhibits, so low impedence 
coils allow a lot of current to flow. Unfortunately, that current can interfere with the other coils in the MRI, which messes up the resultant image, so the coils can only be arranged 
in specific designs to prevent that interferance. On the other hand, this glove uses high impedence coils, which prevent current flow, and therefore prevent that interference between coils, 
allowing you to move your hand in the glove without ruining the image. 

Your next question might be: Why does high impedence seem to work better for this application than low impedence? Aaaand that's where my expertise runs out. 
Based on the paper, it seems like the appeal of low impedence coils was energy efficiency - you can use less energy to record the signal for the image. High impedence coils 
might require more energy, at which point the cost of energy used might not be worth it (or may be unsafe). 

In either case, I thought this paper was very cool, and am looking forward to further developments in the field of MRI that might expand applications towards 
high resolution images of moving patients for sports medicine!
