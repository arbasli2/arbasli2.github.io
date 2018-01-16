---
layout: post
title: Fairy circles of Namibia desert
---
Beauty, simplicity and power of model thinking

Some time ago I saw an article on [BBC Earth](http://www.bbc.com/earth/story/20140916-mystery-fairy-circles-defy-explanation) about Fairy circles in Namibia desert.
Like a lot of other people I thought of an explanation for it.

I am a physicist, I like mathematical models. That time I made a simulation using a simple modified logistic growth model.

The result of the simulation was pretty close to the aerial images of the fairy circles. The self organizing structure appears in conditions like when the plants support each other in a resource limited land. Compare in the image the result of the simulation and an aerial image from Namibrand.

![Namibrand simulation]({{ site.baseurl }}/images/Namibrand_simulation2.png)



Figure: The comparison between the simulation and the aerial image of the fairy circles. The periodicity in the simulation can be because of the periodic boundary condition.

The model is expressed simply by the following formula:
$$\frac{d\rho}{dt}  = k_1 \rho_{avg1} (1- k_2 \rho_{avg2} )$$



There are two factors in this relation: The first factor 
$$k_1\rho_{avg1}$$ 
which supports the population growth and the second 
$$(1- k_2 \rho_{avg2})$$ 
which diminishes it.

The realization of the first factor in nature can be in cases such as reproduction or protection and the realization of the second factor can be depletion of the resources by the population or increase of some common threat.

This is intuitive. Imagine some plants that need each other to stay alive. In other words some plants that the existence and reproductivity of them depends on the density of plants that they see in the close neighborhood of them. So they need to be dense. On the other hand if the resources are limited if they can gather access the resources from far distance, if they effectively reduce the density in large scale by leaving some empty patches there will be enough resources while in small scale they are still dense. So to capture this phenomena in this model the second factor that is related to consumption of resources (or any other things that undermines the existence of the plants) has to reflect an average value that is calculated over a larger area.

Any initial condition given the parameters that are in the correct range, will lead to the fairy circles. It is beautifully simple.

Note 1: The periodicity that we observe in the simulation is due to the limited size of the simulation. This is a known characteristic of the small size simulations. In small size simulation if we use periodic boundary condition we will have such artifacts.

Note 2: We apparently are observing a pattern in the growth of plants. But it can be a totally different phenomena. we might be looking at growth phenomena of other natural existing creature in the matrix of the plants such as bacteria that where it populates it creates empty patches; but still this following the growth model as described above. I think it is not the case, since the field studies does not show existence of other living organisms.

notice: I have moved post to here from my previouse blog. Posted on March 19, 2017

<script type="text/javascript" async
  src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.2/MathJax.js?config=TeX-MML-AM_CHTML">
</script>


