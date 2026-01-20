---
title: 4. Markup, XML, and the TEI
layout: home
nav_order: 6
---

# Markup, XML, and the TEI
{: .no_toc }

## Table of Contents {#slides}
{: .no_toc .text-delta }

1. TOC
{:toc}

## From Markup to Tagging with the TEI Guidelines {#slides}

Now that we know more or less [what a Digital Scholarly Edition is](the-digital-scholarly-edition.html#what-is-a-digital-scholarly-edition), it's time to get to know the cornerstone of each edition: its scholarly edited transcriptions. In most cases, these documents are meticulously enoded in `TEI-XML`, an `XML` vocabulary developed by the [Text Encoding Initiative](https://tei-c.org). But whatever vocabulary is used, the scholar's annotations to the edition's texts are always encoded in some type of markup. That is why we first will start this section of our workshop with a brief introduction of [what markup is and how it works](#markup), before [going into more detail about `XML` specifically](#xml), and finally [the TEI's XML vocabulary in particular](#tei). These introductions should give us a solid basis to start from, before [we try encoding a document in `TEI-XML` ourselves](hands-on-1-tei-xml.html).[^1] 

<div class="iframeWrapper">
<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vS8nu5mvzbz_fzvGi7RiNDifAhGr4liH4poo5seSY8Ji-Vp3ZqQmG40Arc7uoBaAvQZQfEgJBLIBFy2/pubembed?start=false&loop=false&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
</div>

### Why Markup? {#markup}

Building on the distinction we made between quantitative and qualitative approaches to digital text analysis in the [Text for Humans, Text for Computers](text-in-the-computer-age.html#text-for-humans-text-for-computers) video lecture, we start with an introduction to the concept of markup, which we can use to explicitly annotate our interpretation into digital texts. 

### Markup Languages: A Quick Demo {#markup-demo}

To make everything a bit more concrete, our general introduction to the concept of markup is followed by a live demonstration of what markup can look like in action, by showing some examples of different markup languages. This demonstration is also part of the [relevant video recording listed under the workshop's resources](markup-xml-tei-video.html). If you would like to try it out for yourself afterwards, you can download the materials that were used in the demonstration by clicking on the button below.

[Workshop Materials: **markup-examples.zip** (<5kb)](https://github.com/WoutDLN/xml4dse-workshop/raw/refs/heads/main/assets/materials/markup-examples.zip){: .btn .btn-purple } 


### Our Markup Syntax: `XML` {#xml}

After this introduction to markup and markup languages in general, we start to zoom more and more closely in on the markup language we will be using for [our own transcriptions](transcribing-in-tei-xml.html) later. This is where we start to familiarise ourelves more with XML, the eXtensible Markup Language, which provides the syntactical framework for the TEI's tagging vocabulary. As such, it is good to keep in mind that XML is strictly speaking not a 'markup language' by itself, but considered what is called a 'metalanguage': a framework for writing markup languages. This is where we learn more about different levels of XML quality, as we distinguish between *well-formed*, *consistent*, and *valid* XML. Thankfully, many of XML's syntax rules are already familiar to us, as [they were used as an example to explain the concept of markup](#markup). 

### Introducing The Text Encoding Initiative {#tei}

Now that we grasp the basics of markup and the XML syntax, we need a vocabulary to start filling in the blanks. Since we'll be using the [TEI](https://www.tei-c.org)'s vocabulary, we will start with an introduction to the consortium that developed it: what is the Text Encoding Initiative, exactly? And what is it designed to help us encode? 

### Our Markup Vocabulary: `TEI-XML` {#teixml}

Finally, we finish this section with an introduction to the vocabulary itself: `TEI-XML`. We take a closer look at how a `TEI-XML` document is structured, where to put the transcription, and where to put the metadata. We also check out a first set of tags that will be useful [when we transcribe our document in the hands-on part of the workshop](htranscribing-in-tei-xml.html#instructions). 

----

[^1]: At the workshop this section is taught live, but most of the materials touched upon here are also based on a lecture taught and recorded earlier. [You will find this video lecture listed among the workshop's resources.](markup-xml-tei-video.html) 
