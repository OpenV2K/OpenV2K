# OpenV2K Overview
**Audio Waveform Zero-Crossing Pulse Stream Generator**  
OpenV2K is an open-source software application that converts arbitrary audio — including natural
speech — into a pulse-modulated radio-frequency (RF) waveform, transmitted via a software-defined
radio (SDR). The project's signal design is directly inspired by the historical microwave-auditory-effect
(MAE) literature, most notably Sharp and Grove's 1975 demonstration that appropriately pulse-
modulated microwave energy could convey intelligible words.  
  
The app captures microphone audio, or generates eSpeak TTS voice; conditions the input with signal processing filters; detects every
zero-crossing of the audio waveform, across the x-axis (as depicted in profile thumbnail); and emits a configurable-width pulse stream through a HackRF SDR via gr-osmosdr, or saves raw IQ samples to disk, and generates a "waterfall" [spectrogram](https://en.wikipedia.org/wiki/Spectrogram).  

# Sandbox
![StandBackImTryingScience](https://github.com/OpenV2K/Sandbox/blob/main/_emot-science.gif?raw=true)  **For screenshots and functional [pre-alpha](https://en.wikipedia.org/wiki/Software_testing#Alpha_testing) Python software**: https://github.com/OpenV2K/Sandbox  

# Tutorial
Tell me what you want to know, and I'll integrate your feedback.  
See the Tutorial to reproduce my environment and get started:  
https://github.com/OpenV2K/Sandbox/tree/main/Tutorial  

# Features Implemented
Audio Waveform Zero-Crossing Detection, SDR Pulse Modulation Output, Raw IQ Recording, Waterfall Spectrogram Generation, Live Microphone Input, eSpeak/MBROLA Text-To-Speech Engine, Signal Conditioning Filters, Noise Filters, Pulse Shaping Filters, Rectangular Pulses, Duty Cycle Meters, Adjustable Pulse Width, Adjustable High Pass and Low Pass Filters, Automatic High Power Calculator, Event Log, Tooltips, Dependency Checks, and 49 Languages Supported.  

# Compact Qt5 GUI
All GUI descriptions, text labels, and tooltips, automatically translate, when selecting another language.  
You will need to download the Translation.xml file from the Sandbox, and place it in the same directory.  
Use the language dropdown in the upper left corner. When available, a regional accent dropdown is shown.  
Language selection, also selects which eSpeak/MBROLA language voice pack to use for TTS, automatically.
  
<img src="https://github.com/OpenV2K/Sandbox/blob/main/Screenshots/Screenshot%20From%202026-08-18%2013-46-13.png" width="33%"> > <img src="https://github.com/OpenV2K/Sandbox/blob/main/Screenshots/Screenshot%20From%202026-08-18%2013-51-49.png" width="32%">

# Project Block Diagram
![DiagramSplash](https://github.com/OpenV2K/Sandbox/blob/main/_diagram_openV2K_github.png?raw=true)  
  
# Acoustic Transduction From Microwave Absorbing Foam
Excerpt from Chapter 7.2.1, Page 178, Auditory Effects of Microwave Radiation:  
> In attempting to elucidate the mechanism responsible for microwave-induced auditory sensation, a microwave exposure system was set up in 1973 at the Walter Reed Army Institute of Research in Maryland. Investigators found that carbon-impregnated polyurethane microwave absorber (Eccosorb WG4, Emerson and Cuming) acted as a transducer from microwave energy to acoustic energy [Sharp et al., 1974]. If the microwave absorber was placed between the human subject and the pulsed microwave source, the apprent locus of the audible click moved from the observer's head to the absorber. Using a microphone and sound level meter, sounds produced by pulsed microwaves in absorbers of different sizes and shapes were detectable for absorber sizes as small as 4 mm square by 2 mm thick. Several other types of microwave absorbers also produced audible sound. However, aluminum foil had to be crumbled before audible sound was detected from it. Thus, the observed sonic phenomenon implicated a connection of microwave absorbtion to pulse-induced auditory sensation in humans, but also provided a counterexample against radiation pressure as an operating interaction mechanism.  
  
# Reference Materials
1. https://www.amazon.com/Auditory-Effects-Microwave-Radiation-James/dp/3030645436
2. https://en.wikipedia.org/wiki/Signal_modulation#Miscellaneous_modulation_techniques
3. https://web.archive.org/web/20160910133313/http://www.mitchelleffect.com/1973_voice_to_skull.pdf
4. https://www.reddit.com/r/OpenV2K/comments/1g69tey/exodus_12ghz_solid_state_high_pulse_power/
  
# Why Would I Do This?
Please place any outrage you feel [where it's most appropriate](https://michaelebybarr.substack.com/p/our-perverse-legal-system). Do you mind that I'm doing praxis over here?  
Showing me how brain damaged you already are, with character attacks and [conflation](https://en.wikipedia.org/wiki/Conflation), does not make this capability, not work.  
This project's ultimate end goal, is both safe, with microwave absorbing foam acting as a [transducer](https://en.wikipedia.org/wiki/Transducer), instead of a human cranium (so observers can still hear the output, *without* the brain damage potential, *not that the average American would notice*); and legal, when transmitting on HAM bands, with valid license. I have not become death, destroyer of worlds, for disinfecting with sunlight, what came before I was born. I'm not the assholes who developed similar capabilities in secret, for decades; who then deployed classified R&D, on unsuspecting civilians, [like me](https://rrab.substack.com/p/why-the-openv2k-project-exists). I adopted the term "V2K" from the US Army: [from a 2008 WIRED magazine article](https://www.wired.com/2008/05/army-removes-pa/). I'm validating the term, with [FOSS](https://en.wikipedia.org/wiki/Free_and_open-source_software) RF engineering, so [quacks](https://en.wikipedia.org/wiki/Quackery) cannot continue their health fraud, on [targeted civilians](https://en.wikipedia.org/wiki/Microwave_auditory_effect#Conspiracy_theories). Unfounded conspiracy no more, I've recreated in free software, what has come before, in expensive lab hardware. **How is this RF hacking?** It's a [vulnerability](https://en.wikipedia.org/wiki/Vulnerability_\(computer_security\)) disclosure that applies to all of humanity. There is no firmware patch. Do you care yet?  
  
# Developer
- 🔭 I’m currently working on: the core software for the [OpenV2K](https://www.reddit.com/r/OpenV2K/) project
- 💬 Ask me about: how to punch Nazis really hard
- 📫 How to reach me: rrab@tuta.com
