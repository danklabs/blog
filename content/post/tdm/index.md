---
title: "A Gui to make Text-to-speech datasets(TDM)"
date: 2020-03-09T19:44:20+05:30
description: "Text-to-speech dataset maker"
categories: ["Products"]
displayInMenu: false
displayInList: true
draft: false
dropCap: false
resources:
  - name: featuredImage
    src: "tdmlogo.png"
    params:
      description: "Tdm Logo"
---

A Open Source GUI to help you make custom TTS datasets to replicate other people's voices.<br />
Manually transcribing speech is hard but this gui is intended to make it a little less hard and more streamlined. You can use this directly in the [tacotron](https://github.com/NVIDIA/tacotron2) model

### [Download](https://github.com/danklabs/tts_dataset_maker/releases)

### Source code(github): https://github.com/danklabs/tts_dataset_maker.

* Install the application.
* Enter a name for your project.<br />
{{< image src="first.gif" alt="firts-step" >}}
* Select the folder containing **one or multiple** audio files that need to be transcribed.
* Select the **Destination folder** where you want the generated datset to be stored.<br />
{{< image src="firsta.png" alt="select-folder" >}}
* Use the wavesurfer to select the part that you want , Transcribe the selected portion unto to the text area and hit **use Selected Area**.Voila! You have successfully added a clip and its transcribed text into the dataset.<br/>
{{< image src="second.gif" alt="tts-selecteor-gif" >}}
* You can edit and move the selected region like this:<br />
{{< image src="third.gif" alt="editing Wavesurfer selected area" >}}

**Note: If you stop or close the application all the data will be saved to the destination follder but you wont be able to continue where you left off**
If you can help with this, submit a PR to this github link ===> https://github.com/danklabs/tts_dataset_maker.

#### Every week we make something open source and awesome like this. We would love to share it with you!
 <br />
 <form style="border:1px solid #ccc;padding:3px;text-align:center;" action="https://tinyletter.com/danklabs" method="post" target="popupwindow" onsubmit="window.open('https://tinyletter.com/danklabs', 'popupwindow', 'scrollbars=yes,width=800,height=600');return true"><p><label for="tlemail">Enter your email address</label></p><p><input type="text" style="width:140px" name="email" id="tlemail" /></p><input type="hidden" value="1" name="embed"/><input type="submit" value="Subscribe" /><p><a href="https://tinyletter.com" target="_blank">powered by TinyLetter</a></p></form>

Hope you found this useful,
Also we want collaborators for this project, submit a PR if you can [here](https://github.com/danklabs/tts_dataset_maker).

> **If you are into memes, [check this this out](/blog/meh-meh/)** 