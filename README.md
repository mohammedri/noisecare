# Noisecare
## Active Noise Attenuation Speaker System 
### Group 005 - EE Class of 17' - University of Waterloo
#### Prepared by Mohammed Ridwanul, Alexander Kozachuk, Joshua Demkiw, Syed Huq, Varun Sharma
##### Consultant: William Bishop

## Abstract
Unwanted external noise sources can be detrimental to sleeping patterns. There are significant negative health effects associated with insufficient sleep, such as high blood pressure, heart disease and stroke. There are many noise cancellation techniques available, but they require uncomfortable equipment such as earbuds or headphones which introduces further sleeping difficulty. The objective of this project is to attenuate the loudest frequency sound in a localized region near the ear. The system takes in environmental noise and successively attenuates it by outputting a destructively interfering audio signal generated through adaptive signal processing. The necessary waves are determined using wave and control theory. The benefit of this project over existing alternatives is in its comfortable and simple design. The system does not require complicated installations when compared to acoustic insulation. There is no longer a requirement for uncomfortable equipment such as noise canceling headphones or earbuds. The system prevents ear health issues associated with wearing some existing alternatives.

# Acknowledgements
We would like to acknowledge our consultant William Bishop for the constant support, motivation, and technical direction provided to us throughout the duration of the project, as well as during our undergrads. We would also like to thank Dr. Oleg Michailovich and Dr. Zhou Wang for their advice and guidance on technical challenges encountered.

# Table of Contents
*   High Level Description
 *  Motivation
 *  Project Objective
 *  Block Diagram
   *   Microphone & Pre-Amplifier
   *   Speakers
   *   System Hardware Mount*   Microphone & Pre-Amplifier
   *   Speakers
   *   System Hardware Mount
   *   DSP (Digital Signal Processing)
   *   Noise Attenuation Algorithm
 *  Project Specifications
   *  Functional Specifications
   *  Non-functional Specifications
 *  Detailed Design
 *  Microphone and Pre-Amplifier
   *  Microphone and Pre-Amplifier Design Choice
 *  Speaker
 *  System Hardware Mount
 *  Digital Signal Processing (DSP) Board
   *  Comparison of the Texas Intruments DSP Boards
   *  Noise Attenuation Algorithm
   *  Data Flow & Structure
   *  Frequency Setup and Selection System
   *  Tone Generation
   *  Adaptive Algorithm
 *  Prototype Data
   *  Hardware System Mount
   *  Prototype Testing Results
 *  Discussion and Conclusions
   *  Evaluation of Final Design
   
# 1 High Level Description
## 1.1 Motivation
Environmental noises can be detrimental to sleeping patterns, whether they are caused by traffic just outside the window or construction on the building next door. While most people are able to sleep fine through a certain noise level, loud noise patterns at low mechanical tones throughout the night lead to lower sleep quality and satisfaction. Increased noise stimuli during sleep leads to increased sleep fragmentation, arousals, reductions, awakenings and latency [1]. These effects lead to a worse sleep overall, which results in adverse health effects. The total number of sleep awakenings per year were shown to increase exponentially when environmental noise exceeded 42 dB [1]. There are significant negative health effects associated with insufficient sleep, such as high blood pressure, heart disease and stroke [1]. Though noise cancelling solutions such as earbuds, headphones, or professional soundproofing installations are available, they can be expensive or require construction. NoiseCare provides an affordable option for noise attenuation near the user’s ears without the use of headwear, leading to a better sleeping experience with less disruption.

## 1.2 Project Objective
The objective is to successfully sample environmental noise and reduce the strength of the frequency with the most amount of power (i.e. loudest); focused on the lower frequency range noises generated by mechanical systems, at a region near the ears to reduce noise levels to a total of no more than 42 dB. The system will not aim to cancel a large range of frequencies, but rather the loudest frequencies. The final product should be usable and affordable for the average consumer, with the system being powered from a standard wall outlet. The consumer does not need to wear additional headgear or earplugs, and any form of installation or construction should be limited to the ability of the common household equipped with common tools.

## 1.3 Poster
![alt text](noisecare/Noisecare_poster.jpg)

### For full details and comprehensive design specifications, see the attached pdf report.




