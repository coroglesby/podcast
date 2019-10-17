---
title: Set Up
nav: true
--- 

# <i style='color:black;' class='fas'>&#xf0ad;</i> Getting Set Up

**What you'll find on this page:**
- <a href="#software">Audio editing software</a>
- <a href="#hardware">Audio recording hardware</a>

<a id="software"></a>
{% capture text %}
#### Choosing an audio editor

First thing's first: we need to download the audio editing software that we'll be using to assemble the podcast. Luckily, there are a lot of options. Here are a just few of the most commonly used applications:

##### Free

- [Audacity](https://github.com){:target='_blank'}—Audacity is an easy-to-use, multi-track audio editor and recorder for **Windows, Mac OS X, GNU/Linux** and other operating systems. Developed by a group of volunteers as open source.

{% capture text %}
**NOTE:** You'll want to download a few extra plug-ins to use Audacity to its fullest potential—be sure to check out the links at the bottom of this section.
{% endcapture %}
{% include alert.md text=text %}

- [GarageBand](https://itunes.apple.com/us/app/garageband/id682658836?mt=12&ls=1){:target='_blank'}—A **Mac OS-only** audio editor with lots of easy-to-use, built-in features. Used commonly for music creation, it comes with lots of loops and special effects.

##### Not-so-free

- [Logic Pro X](https://itunes.apple.com/us/app/logic-pro-x/id634148309?mt=12){:target='_blank'}—A more expansive (and expensive, at **$199**) version of GarageBand. 
- [Adobe Audition](https://www.adobe.com/products/audition.html?sdid=KKQPG&mv=search&ef_id=EAIaIQobChMI4_OotaDs4QIVrB-tBh2q9g2PEAAYASAAEgLfh_D_BwE:G:s&s_kwcid=AL!3085!3!332933959191!e!!g!!adobe%20audition&gclid=EAIaIQobChMI4_OotaDs4QIVrB-tBh2q9g2PEAAYASAAEgLfh_D_BwE){:target='_blank'}—Similar to Logic Pro X in terms of expansiveness, with slightly different user interfaces (in other words, if you're more comfortable with Apple applications, you'll likely feel more at home with Logic Pro X, and vice versa). [Adobe's Creative Suite](https://www.adobe.com/creativecloud/plans.html?single_app=audition&promoid=KTKAY){:target='_blank'} is **plan-based** these days, so prices vary.
{% endcapture %}
{% include card.md text=text header="Audio Editing Software" %}

#### ...but let's go with **Audacity**

There are a few reasons this workshop will use Audacity as its primary example of an audio editor: it's *free*, it's *usable on all operating systems*, and it has [fantastic documentation](https://manual.audacityteam.org/){:target='_blank'} (if at some point you need more help with Audacity beyond the examples we'll be providing throughout this workshop).  

{% capture text %}
**Note:** You'll want to download these Audacity plug-ins:
- [Lame v3.99.3](https://manual.audacityteam.org/man/installing_and_updating_audacity_on_windows.html#winlame){:target='_blank'}—a third-party encoder that allows you to easily export your finished project as an MP3 file.
- [FFmpeg Import/Export Library](https://manual.audacityteam.org/man/installing_and_updating_audacity_on_windows.html#winff){:target='_blank'}—allows Audacity to import and export a much larger range of audio formats including M4A (AAC), AC3, AMR (narrow band) and WMA (as well as audio from most video files).
{% endcapture %}
{% include alert.md text=text %}
---
<a id="hardware"></a>
{% capture text %}

#### How you'll actually record the audio

In truth, there are too many different audio recording devices and methods out there for us to get *too* into them, so we'll break it all down into two broad categories: **field** recording and **direct-to-computer** recording.

##### Field recording

- Simple, handheld devices like the [TASCAM DR-100mkII](https://www.amazon.com/dp/B006JVNTXO/?tag=1010128-20){:target='_blank'}, the [Zoom H2n](https://www.amazon.com/dp/B005CQ2ZY6/?tag=1010128-20){:target='_blank'}, and even... 
- ...**your smartphone** (i.e. any voice-memo app you might be able to download).

Field recorders are great for...recording in the field. You can't always bring your computer and microphone setup everywhere with you, right? With this method, you'd record audio on the handheld device and later "drag & drop" them into your audio editing software.

##### Direct-to-computer recording

- USB microphones like the very popular [Blue Yeti](https://www.bluedesigns.com/products/yeti-nano/){:target='_blank'}—a super-simple setup that consists of the microphone, your computer, and a USB cord to connect the two.
- Audio interfaces like the [Focusrite Scarlett 2I2](https://focusrite.com/usb-audio-interface/scarlett/scarlett-2i2){:target='_blank'}—a piece of hardware that (often) allows for more than 1 microphone (note: regular [XLR](https://en.wikipedia.org/wiki/XLR_connector){:target='_blank'} microphones are used with these).

Direct-to-computer recording is arguably the quickest/easiest way to get going, as the audio gets dumped into your editing software in real time as it's being recorded. 

**That said, you'll likely be using a combination of the above methods**—for instance, you might record an interview out in the field using a handheld device, come back to your computer and drop the audio in, then use a direct-to-computer microphone to record your voice-overs or other commentary.
{% endcapture %}
{% include card.md text=text header="Audio Recording Hardware" %}
