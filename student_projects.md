---
title: Student Projects
rank: 2.1
---
# Student Projects
Here's a running list of student research and design projects I've mentored. If you're a student looking to get involved, this is a good place to see what others have been up to lately.

## CHART Data Analysis
*Emma Dachel, 2022*

Emma participated in WSU's Early Year Research & Creative Mentoring ([EYRCM](https://www.winona.edu/grants/early-year.asp)) pilot program. The program matches students early in their collegiate career with research mentors. Emma's project was to dive into some CHART data collected at ASU and look for any issues that need to be investigated. She found and cataloged several anomolies, uncovering bugs in our data collection system. She went on to study one of the issues, and found that our SDR is using an automatic gain control (AGC), which is typically not desirable for astronomy applications.

## CHART Filter
*Nahom Nemera, 2021-2022*
![Microstrip](media/microstrip.jpg)

For his engineering design project, Nahom looked to replace the very expensive bandpass filter CHART has been using so far. His goal was to find a more affordable option that performs well enough to detect the 21cm hydrogen line. He explored cheaper off-the-shelf options, home made microstrip filters, and his own printed circuit board versions. While simulations of his latest PCB design showed the best performance, we are still experiencing issues with the implemented filter. Until those issues are worked out, the current best option is a [Nooelec SAWbird filter](https://www.nooelec.com/store/sawbird-h1-barebones.html_).

## Solar Radio Bursts with EPIC
*Isaac Conrad, 2021-2022*

Isaac recently finished his senior research project, which was to demonstrate [EPIC](research#epic)'s ability to observe solar radio bursts. EPIC is a brand new system, and Isaac's work has helped to uncover some bugs in the data collection. He ended up studying one solar burst, which he was able to classify as Type III and measure its drift rate. We hope this analysis will lead to studying many more bursts in the future.

## Machine Learning to Identify RFI
*Sheikh Fahad, 2021*

Fahad is a Computer Science major with an interest in artificial intelligence. He wanted to incorporate that interest into a radio astronomy project by exploring machine learning to identify radio frequency interference (RFI). This has been attempted with other telescopes in the past, but [EPIC](research#epic) has its own challenges because its data product is unlike other radio telescopes. Fahad studied different image classification learning algorithms, and built a training set with existing EPIC data. Along the way, he also implemented continuous integration for the project so we can develop unit tests to ensure project stability.

## Radio Observatory Scouting
*Serdar Chifji, 2021*
![Scouting data](media/scouting_data.png)

Serdar spent the summer working with different radio telescopes, with the goal to study the radio frequency environment around Winona. He assembled and tested an LWA antenna, and designed a portable system to drive around and record RF spectra. Above you can see low-frequency spectra from several locations around town. The Farmer's Community Park shows very little interference, demonstrating that the bluffs in the area can effectively shade us from radio towers. We hope that future expeditions will help us find the perfect location for a Winona Radio Observatory.

## Simulating CHART Data
*Dylan Gappa, 2020-2021*
![chart sim](media/simulated_chart_data.png)

CHART has been able to collect data that looks like the 21cm hydrogen line, but an open question is how we know that the little bump we see is really the galaxy. One piece of evidence is to compare our data with professional surveys. Dylan set out to do this using the [HI4PI Survey](https://ui.adsabs.harvard.edu/abs/2016A%26A...594A.116H/abstract). He used this data and wrote a program to simulate CHART's response (a very large field of view) for any location, time, and pointing direction. We hope to use simulated data like you see above to compare with CHART observations.

## Cosmology Parameter Searches with 21cmFAST
*Megh Khanal, 2020-2021*

Megh was interested in a theoretical cosmology project. So he learned to use the 21cmFAST semi-numerical software to simulate the Epoch of Reionization for a given set of cosmological and astrophysical parameters. We then undertook a "parameter search" exercise where I created a "true" universe, and Megh created a suite of simulations, varying parameters, until he found a set of parameters that statistically matched the universe I created for him. This is the type of strategy cosmologists use to match data to numerical models and constrain our understanding of how the universe evolved. 
