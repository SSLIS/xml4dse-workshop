---
title: 0. Before the Workshop
layout: home
nav_order: 2
---
# Before the Workshop
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## Install a Text Editor

To participate in this workshop, you will need to download and install a text editor. Text editors allow us to read and write plain text documents, like the `.html`, `.css`, `xml` and `xslt` files we will be working with. Text editors are quite different from the Word Processors you might be more familiar with, such as MS Word, LibreOffice Writer, or Pages. If this is new to you, and you would like some more information about different document types and data formats, check out my [quick introducion to data formats below](#a-quick-introduction-to-data-formats). 

Since we will mostly be focussing on transcribing documents in `TEI-XML`, I highly recommend installing the specialized XML-editor [oXygen](#oxygen) for this purpose, which comes with baked in `TEI-XML` support, and the `XSLT` processor I will be using to demonstrate how we can transform our `TEI-XML` into `HTML` towards the end fo the workshop. Since oXygen is a paid propietary software package, however, I can also recommend a freely available open source alternative: Microsoft's [Visual Studio Code](#alt-visual-studio-code), which can be extended to include similar functionalities.

Either way, please make sure that you have a functioning text editor installed on your personal computer *before class*, as we will not have time to go through and troubleshoot the installation of this software during the workshop.

### oXygen

{: .note}
[oXygen](https://www.oxygenxml.com/) is a specialized XML editor with a wide range of useful functionalities that will be relevant to this workshop, incuding integrated support for writing `TEI-XML`. While oXygen is proprietary software that requires a paid licnese to work, it does offer a 30-day free trial license, which would be more than enough for this workshop. 

To install oXygen: 

1. Visit: [https://www.oxygenxml.com/xml_editor/register.html?p=editor](https://www.oxygenxml.com/xml_editor/register.html?p=editor)
2. Fill out the information in the form (only fields marked with * are obligatory)
3. Select 'Academic' as your License Type
4. Click 'Submit', and wait for the software to Download
5. Open the downloaded file, and follow the prompted installation steps
6. At some point during the installation process, you will be asked to provide a license key. This key has been sent to the email address you provided in step 2. Copy paste this information where prompted.

### [alt:] Visual Studio Code

{: .tip }
Since I will be using oXygen for demonstration purposes during the workshop, I highly recommend that you use oXygen too. If you would like to use these materials for your selfstudy, or are looking for a long-term solution and do not have the means to acquire an oXygen license you are of course welcome to use any XML editor of your choice. In that case, I recommend [Visual Studio Code]([https://code.visualstudio.com/](https://code.visualstudio.com/)). 

{: .warning }
Unlike oXygen, Visual Studio Code does not come with the same useful functionalities we will be using in the workshop 'out of the box', and will require you to find and intall extensions.  

To achieve an equivalent function to oXygen's on the fly validation against the TEI's schema, for example (which we will learn more about during the workshop), for example, you could download, install and configure the [XML Language Support by Red Hat](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-xml). To learn how to do that, you can watch the following 15-minute video tutorial I recorded for that purpose: 

<iframe id="kaltura_player" src="https://api.kaltura.nordu.net/p/330/sp/33000/embedIframeJs/uiconf_id/23450308/partner_id/330?iframeembed=true&playerId=kaltura_player&entry_id=0_nsz1hdfo&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=en&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=left&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[hotspots.plugin]=1&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=0_y4zdxa65" width="400" height="285" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-downloads allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="TEI-XML Validation with Visual Studio Code"></iframe>

For an index of the `XSD` schemas of the TEI's official subsets you could use, see [https://tei-c.org/release/xml/tei/custom/schema/xsd/](https://tei-c.org/release/xml/tei/custom/schema/xsd/).

{: .highlight-title}
>TL;DR
>
>1. Install Visual Studio Code
>2. Install the XML Language Support Extension by Red Hat
>3. Add the following line to the prologue (i.e. before the root <TEI> opening tag) of your TEI-XML document): 
> 
> `<?xml-model href="https://tei-c.org/release/xml/tei/custom/schema/xsd/tei_all.xsd" type="application/xml-xsd"?>`

{: .warning }
As with most open source text editors, extensions such as these are developed and maintained by third parties (here: Red Hat). In this ecosystem, exensions are continuously updated or depracated, and new ones spring up all the time. 

I recorded this video in 2022, and much may have changed by the time you are watching it. If this method stops working at some point, hopefully it may still help you understand how it works, and find a more up-to-date method or alternative extension to achieve a similar result. In that case, you are of course always welcome to suggest changes, e.g. via a pull request on GitHub. This also goes for adding links or instructions to other tools or extensions that may be useful for this workshop.

## Video Lectures 

### A Quick Introduction to Data Formats

<iframe id="kaltura_player" src="https://api.kaltura.nordu.net/p/330/sp/33000/embedIframeJs/uiconf_id/23450308/partner_id/330?iframeembed=true&playerId=kaltura_player&entry_id=0_ei585yg2&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=en&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=left&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[hotspots.plugin]=1&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=0_7kzdsmcl" width="400" height="285" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-downloads allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="A Quick Introduction to Data Formats (Datalogical Thinking Version)"></iframe>

In this video, we take a closer look at what happens when we store those documents onto our computers. After a quick experiment with file extensions in this video, it will become clear how important it is to consider data formats at the outset of a project, to help safeguard the interoperability and long-term sustainability of the data we produce and share. 

This video was made for the Datalogical Thinking course, specifically its Module called: 'A Quest for Meaning'. A large part of the video was directly copied from a video Wout originally made for a course called 'Technologies for Digital Libraries 1' at the University of Borås. Some voice over and slide images were added to contextualise the lecture in the Datalogical Thinking course. 

To try out the experiment on your own, you can [download the `.zip` folder mentioned in the video here](https://github.com/WoutDLN/xml4dse-workshop/raw/refs/heads/main/assets/dataformats.zip) (`< 200 kb`).

### Text for Humans, Text for Computers.

<iframe id="kaltura_player" src="https://api.kaltura.nordu.net/p/330/sp/33000/embedIframeJs/uiconf_id/23450308/partner_id/330?iframeembed=true&playerId=kaltura_player&entry_id=0_ou0h7gxz&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=en&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=left&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[hotspots.plugin]=1&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=0_vv0bo8lb" width="400" height="285" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-downloads allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="Text for Humans and Text for Computers"></iframe>