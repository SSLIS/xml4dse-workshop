---
title: 0. Before We Begin
layout: home
nav_order: 2
---
# Before We Begin
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## Install a Text Editor

To participate in this workshop, you will need to download and install a text editor. Text editors allow us to read and write plain text documents, like the `.html`, `.css`, `xml` and `xslt` files we will be working with. Text editors are quite different from the Word Processors you might be more familiar with, such as MS Word, LibreOffice Writer, or Pages. If this is new to you, and you would like some more information about different document types and data formats, check out my [quick introducion to data formats](text-in-the-computer-age.html#a-quick-introduction-to-data-formats). 

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

### [alt:] Visual Studio Code {#vsc}

{: .tip }
Since I will be using oXygen for demonstration purposes during the workshop, I highly recommend that you use oXygen too. If you would like to use these materials for your selfstudy, or are looking for a long-term solution and do not have the means to acquire an oXygen license you are of course welcome to use any XML editor of your choice. In that case, I recommend [Visual Studio Code]([https://code.visualstudio.com/](https://code.visualstudio.com/)). 

{: .warning }
Unlike oXygen, Visual Studio Code does not come with the same useful functionalities we will be using in the workshop 'out of the box', and will require you to find and intall extensions.  

To achieve an equivalent function to oXygen's on the fly validation against the TEI's schema, for example (which we will learn more about during the workshop), for example, you could download, install and configure the [XML Language Support by Red Hat](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-xml). To learn how to do that, you can watch [a 15-minute video tutorial I recorded for that purpose](tei-xml-validation-with-vsc.html). 