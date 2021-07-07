---
title: "Synthesizing Designs with Inter-Part Dependencies using Hierarchical Generative Adversarial Networks"
collection: publications
permalink: /publications/2018-11-02-hgan-idetc
date: 2018-11-02
venue: 'Proceedings of the ASME 2018 International Design Engineering Technical Conferences and Computers and Information in Engineering Conference'
paperurl: '/files/pdf/publications/chen_hgan_idetc_2018.pdf'
link: 'https://tribology.asmedigitalcollection.asme.org/IDETC-CIE/proceedings-abstract/IDETC-CIE2018/51753/V02AT03A007/273548'
github: 'https://github.com/IDEALLab/hgan_idetc2018'
authors: '<b>Wei Chen</b>, Ashwin Jeyaseelan, Mark Fuge'
abstract: "Real-world designs usually consist of parts with hierarchical dependencies, i.e., the geometry of one component (a child shape) is dependent on another (a parent shape). We propose a method for synthesizing this type of design. It decomposes the problem of synthesizing the whole design into synthesizing each component separately but keeping the inter-component dependencies satisfied. This method constructs a two-level generative adversarial network to train two generative models for parent and child shapes, respectively. We then use the trained generative models to synthesize or explore parent and child shapes separately via a parent latent representation and infinite child latent representations, each conditioned on a parent shape. We evaluate and discuss the disentanglement and consistency of latent representations obtained by this method. We show that shapes change consistently along any direction in the latent space. This property is desirable for design exploration over the latent space."
---
