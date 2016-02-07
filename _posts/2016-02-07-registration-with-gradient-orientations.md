---
title: Multi-modal Image Registration based on Gradient Orientations
layout: post
---


For my second post, I am inclined to __regurgitate__ part of the work that was included in my [PhD thesis]({{ site.baseurl }}/publications/pdfs/Dante_PhD_thesis.pdf). Mainly, because I have a nice video at hand and it's a (almost offensively) simple idea that proved quite performing. I mean, __ultimately__, I got a PhD out of it!

<div class="align-center">
<iframe color="white" modestbranding="0" width="560" height="315" src="https://www.youtube.com/embed/0GQsdUi8MVk" frameborder="0" allowfullscreen></iframe>
</div>
<br>


The video shown above is a guided demonstration of the performance of this registration method in two substantiall different multi-modal contexts for medical image analysis. The first context is a "classic" problem involving the rigid registration (i.e. distances are preserved) of a CT head scan and a corresponding MRI head scan. This is a fundamental first step towards multi-modal image analysis, either automated or performed by an expert (e.g. radiologist).

The second part of the video shows an arguably harder problem of finding a rigid transformation between a head MRI and an ultrasound (US) scan. This context arises in the context of image-guided neurosurgery (IGNS), where the clinician will rely on an intra-operative imaging technique (in this case ultrasound) to evaluate any tissue displacements suffered since the patient was imaged with the pre-operative MRI. 
