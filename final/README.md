# Project: Knowing Your PC

**Description:** A website that allows users to know what to look for when they are getting parts for their PC, and be able to make sure they got the right parts to *beef* up their PC's power. Some components are not always ready to go, most will need some troubleshooting for them to work.

**Key Facts/Inspiration**
1. With each year going by the technology we use everyday gets more advance and gets updated hardware and software to run smoothly and without issue
2. The mother board is the nervous system that connects everything together.
3. GPU renders images, videos, and complex 3D
4. CPU is the brain of the computer and executes the instructions it is given

## Page 1: Home Page
```Text
Common 2026 Issues: Frequent stuttering or "winking" displays are often tied to recent OS updates (like the February 2026 KB5077241 patch) or thermal throttling due to aging thermal paste.

Troubleshooting: Always start by using DDU (Display Driver Uninstaller) in Safe Mode to wipe corrupted drivers before a clean install. If performance drops suddenly during load, check your thermal levels; modern high-TDP cards often require a repaste or a move to an ATX 3.1 power supply for stable voltage delivery.

CPU vs. Motherboard: The Brain and the Nervous System
Think of the CPU as the Brain. It handles the logic, calculations, and decision-making for every task. However, even a genius brain is useless without a Nervous System—the Motherboard. The motherboard’s chipset and traces (the "nerves") determine how quickly and reliably instructions from the brain reach the rest of the body. In 2026, motherboards with PCIe 5.0 lanes are essential to ensure your "nervous system" doesn't bottleneck the lightning-fast data flow between your CPU and Gen5 SSDs.

The 2026 Buyer's Checklist
When scouting for new parts, look for these three critical factors:

AI Readiness: Ensure the CPU includes a dedicated NPU for future-proofing Windows AI features.

Platform Longevity: Prioritize sockets with confirmed support through 2030 (like the AM5 or LGA1851) to avoid "full rebuild" costs later.

Efficiency over Excess: With rising energy costs and hardware heat, look for "Platinum" rated PSUs and high-airflow cases that prioritize thermal management over purely aesthetic RGB.
```

## Page 2: About

```text
Unique Strengths, Shared Success: The Hardware Philosophy
At Knowing Your PC, we believe that every piece of hardware is a specialist with its own unique personality. No component is perfect; rather, each carries a specific set of strengths and weaknesses that define the character of your build. A high-end GPU offers breathtaking visuals but demands massive power and generates significant heat. A high-speed NVMe Gen5 drive slashes load times to seconds but can become a "hot spot" on your motherboard without dedicated cooling. Building a PC isn't about buying the most expensive parts; it's about balancing these unique traits to create a harmonious system.

Our mission is to help you navigate these trade-offs. We focus on the "Structural DNA" of hardware—understanding that a "weak" component isn't necessarily bad; it might just be the wrong fit for your specific goals. By deconstructing how parts interact, we empower you to build a machine that plays to its strengths while mitigating its inherent weaknesses, ensuring your PC remains a reliable tool for years to come.
```
## AI Session Link
[Link to AI Chat](https://gemini.google.com/share/b6011202116e)

### Week 4: Design & Layout

- *Background* = #E4B7E5 Pink Orchid
- *accent* = #750D37 Dark Amaranth
- *Text* = #210124 Midnight Violet

using these colors as my way of limiting any use of cooler colors to lower the strain on the eyes for staring at a screen for too long. Each color seems to pair well with each other as well to create a right view.

for the title headings using the font ```monospace``` can create that digital retro feel to it while using ```arial``` for the body text.

## Week 5: Accessibility & Layout
We switched from ```<px>``` to ```<rem>``` because rem will adjust the size based off the size of the webpage it is presenting on. Makes it easier when trying to adjust in large scales knowing that ```1rem=16px```.

the margin being the space between different elements was set up so that way no matter how the web page changes in size it will always have the needed space without clashing into other elements. For the padding being the space between the element's content and the border of the element, with giving it some space it shows will make the page easier to view.

## Week 7 Engineering Notes
the descendant selectors are confirming scores at ```(0, 1, 1)``` and is necessary so that way it prioritize the results of the specificity score even if the elements are changed later without using the selectors.

## week 8 engineering notes
the changes I have made would make certain cards go from 2-columns to stacking at 700px for mobile users such as phones and tablets. The header helped removing the margin so the links weren't "hugging" the top edge of the border and keeps it even on top and bottom. It is better to put the media query inside the selector instead of underneath it because it helps it keep it clean and easier to read what properties will effect the element.

## Week 9 sub pages
the sub page i added is related based off of security reasons and can help those who are still trying to learn the basics of computers and want to stay protected. it is being linked through the tips window near the end of the page with the card about security, it will be in a new page because of the amount of information about being protected. wanted to test something with ```@media``` in the properties and it actually worked out the way i wanted it to it was a trial and error on what combination and the amount of ```px``` to use for it but it should transition smoothly with the webpage size change.