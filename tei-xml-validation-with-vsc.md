---
title: TEI-XML Validation with Visual Studio Code
layout: home
nav_order: 1
parent: Video Lectures
---

# `TEI-XML` Validation With Visual Studio Code

<div class="iframeWrapper">
<iframe id="kaltura_player" src="https://api.kaltura.nordu.net/p/330/sp/33000/embedIframeJs/uiconf_id/23450308/partner_id/330?iframeembed=true&playerId=kaltura_player&entry_id=0_nsz1hdfo&flashvars[streamerType]=auto&amp;flashvars[localizationCode]=en&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=left&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[hotspots.plugin]=1&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=0_y4zdxa65" width="720" height="500" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-downloads allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="TEI-XML Validation with Visual Studio Code"></iframe>
</div>

As a free open-source alternative to [oXygen](https://www.oxygenxml.com/), I've suggested using Visual Studio Code]([https://code.visualstudio.com/](https://code.visualstudio.com/)) [in our pre-workshop installation instructions](before-we-begin.html#vsc). The video below explains how you can install an extension in Visual Studio Code that can still give you the benefit of on the fly validation against the TEI's XML namespace when you do. 

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