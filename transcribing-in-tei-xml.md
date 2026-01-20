---
title: "5. Transcribing in TEI-XML"
layout: home
nav_order: 7
---

# Transcribing in TEI-XML
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## Getting Started with oXygen {#tei-oxygen}

Now that we know [what markup is, what the basic rules of the XML syntax are, how a minimal TEI-XML document is structured, and that we've come across our first few TEI-XML tags](markup-xml-tei.html), it's time to start transcribing our first document! And so we come to the hands-on part of this workshop. 

We will write our transcriptions in [a text-editor, preferably oXygen](before-we-begin.html). To help you on your way, I offer a quick tour of the software's main functionalities you'll need for the workshop. For people who cannot participate in this demonstration live, I have made [an alternative video recording](transcribing-in-tei-xml-with-oxygen.html) available. [If you prefer to use Visual Studio Code instead of oXygen](before-we-begin.html#vsc), don't forget to [install the extension to enable on the fly TEI-XML validation](tei-xml-validation-with-vsc.html).

## The Case: Mary Shelley's *Frankenstein*

For this workshop, we will be transcribing some page(s) from a notebook Mary Shelley used to write the first draft of her most famous novel: *Frankenstein, or the Modern Prometheus*. Notoriously, Mary Shelley's *Frankenstein* was originally not conceived as a novel, but as a shorter ghost story. In the historically cold and rainy summer of 1816, Mary Wollstonecraft Shelly, her husband Percy Bysshe Shelley and couple others were staying near Geneva with Lord Byron, where they entertained themselves in the evenings by reading ghost stories aloud, which prompted Byron to propose that they each write one. 

Mary Shelley's contribution to the challenge contained the beginnings of what would later become her *Frankenstein* novel, but is now sadly lost. In the following year, she continued to developed it further into a novel, with some help of her husband, before publishing its first edition in 1818. The earliest extant drafts of Mary's text, with Percy's edits, are contained in two notebooks that are currently held by the [Bodleian Library](https://digital.bodleian.ox.ac.uk) in Oxford (UK), which also digitized the manuscript. These digital images, provided by the Bodleian, will be the starting point of our transcription exercise. Specifically, we'll start at the beginning of the chapter where Dr. Viktor Frankenstein, "on a dreary night of November", first lays eyes on his completed creature.

## The Materials

For this workshop, you will have some tools at your disposal. You will need:

1. **A link to the manuscipt,** digitized by the Bodleilan Library. Specifically, we'll use: [MS. Abinger c. 56, Notebook A, folio 21r](https://digital.bodleian.ox.ac.uk/objects/53fd0f29-d482-46e1-aa9d-37829b49987d/surfaces/5359a811-63e4-49d7-8cc1-e6b4308a7969/).
2. **The equivalent chapter in the published edition,** to help decipher some of Mary Shelley's handwriting. For your convenience, I have screengrabbed [the `EPUB` version of the public domain text digitized by Project Gutenberg](https://www.gutenberg.org/ebooks/84), which you can [read here as a PDF](/assets/materials/frankenstein-chapter-V.pdf).
3. **An XML file to start transcribing in.** [As we saw earlier](#tei-oxygen), oXygen can generate one of those for us.
4. One or more **references to TEI-XML tags** we can use. You can check out:
    1. [the slides from the previous section](markup-xml-tei.html#slides), which includes the basics;
    2. [the BDMP's encoding manual](https://bdmpmanual.uantwerpen.be), which includes some more useful tags and attributes for draft materials such as these; and
    3. [the complete TEI-guidelines](https://tei-c.org/release/doc/tei-p5-doc/en/html/index.html) for pretty much anything else you might want to encode.

## Instructions

For this workshop, you will be devided into small groups of preferably about three or four people each. That way, one group member can pull up the manuscript, another the published version as a transcription aid, while the third writes the code. The idea is, however, that all group members work together to come up with their joint transcription. 

Study the manuscript closely, and try to make sense of the page. What is written, and what subsequently deleted and/or added? Which words can you clearly decypher, possibly using the published version, which are you uncertain about, and which can't you read at all? Remember that the published text is still at least a few versions separated from the draft you're reading, and that even the 'top layer' of the text is still likely to have changed in the interim. Which tags would you use to encode which textual phenomena on the page? How deep do you feel you would like or need to encode the text? Are there any other aspects of the document that you think are interesting or relevant, that you would like to find a way to encode?

Try, in the first place, to find answers to these questions, and solutions to these problems, by discussing them in group. In many cases, there will be no right or wrong answers; instead, there will be differences of opinion, and of perspective. This will hopefully also bring to light some interesting contrasts and spark discussion when we compare your results with those of your classmates.

I will be available for questions while you work on your transcriptions, so just raise your hand if you run into problems.

See how far you can get in your encoding, within the allotted time. There is no minimum or maximum amount to transcribe. Some groups will be quicker than others, and editorial decision making processes can take up a lot of discussion time. After the group work, and perhaps a short break, we will discuss  results and compare findings across groups. The editorial decisions you've made (and the discussions you had making them) will be equally relevant to this session, as the words you've transcribed and the tags you've used to transcribe them. Also don't worry if you can't decypher certain words, [as we've already glimpsed in our first introduction to the TEI-XML vocaublary](markup-xml-tei-html#teixml), there are strategies you can use to convey your uncertainty in your transcription (and markup).
