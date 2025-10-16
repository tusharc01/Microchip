# Microchip
Interview Experience

### Written Test 

Total Questions- 60 [(Apti, Digital, Verilog, and C Programming and DVLSI]

### Round 1 (F2F Interview)(Physical Design) - 45 min

The interview started with my introduction. Based on that, he asked what I was currently doing in my project. I told him about the ASIC Design Flow that I'm currently working on, and that I'm also learning physical design to get a better understanding of it.

I explained the ASIC Design flow to him properly, mentioning which steps I had completed and what was still remaining. Then, he started asking in-depth questions about my project.

He asked me the difference between Post-Synthesis STA and Post-Layout STA, which I answered. He also asked what should be done to avoid Post-Layout STA violations that might not appear in Post-Synthesis STA. I answered by explaining the reason and offering a suggestion to prevent it.

Then, he moved on to the fundamentals of STA and asked for my understanding of setup and hold time. I was asked to explain it with a proper definition and to draw it on paper, including a two flip-flop case and its waveform.

Next, he asked about the buffers present in the .lib file: what they are and their purpose. Then, he began asking me to analyze buffers of different sizes.

He asked me about the difference between small-sized buffers and larger ones. Initially, I answered, "Sorry sir, I haven't analyzed the buffers present in the standard library," but he insisted that I just think about it.

He gave me a hint, asking, "Let's suppose there are two metal wires, one short and one long, starting from (a). What would the signal waveform look like upon reaching the end (b)?" At first, I wasn't able to get it right, so he gave me another hint to think in terms of changing capacitance, skew, etc. After that, I was able to explain it perfectly.

Then, he gave me a second case about driving several gates (e.g., inverters) using buffers. The scenarios were: (i) driving 2 inverters with one clock signal, and (ii) driving 4 inverters with the same clock signal. He asked what the difference in the waveforms would be if buffers were inserted in the path and how we would determine which size buffer to use. I analyzed everything based on our previous discussion and gave him a complete answer. At that point, he was impressed with me.

Finally, he asked if I had any questions for him. I asked about what Microchip does and what profile he works in.


### Round 2 (Virtual Interview) - 1 hr

The interview then went deep into the basics, starting with a heading on my resume where Machine Learning and Deep Learning were mentioned. He asked me to explain the basics and what algorithms I know, but I wasn't very familiar with ML as it was only a small part of my MTech curriculum. He suggested that I shouldn't mention anything I don't know from scratch.

Initially, I was asked to explain what happens in physical design and what steps are involved. The questions also covered the die area and IO pads. Then, I was asked for a simple definition of a layout. Since I panicked, I started describing it according to the elements present in the Cadence tool layout. However, he said he was just expecting a basic answer: that it is the physical representation of the chip's interior, which can be used by the foundry to fabricate it on a silicon chip.

Next, we moved to STA, starting with drawing the internal structure of a Flip-Flop and explaining how it functions with proper signal and data waveforms. This took a lot of time to explain properly, as I panicked and couldn't remember the exact internal connections.

Then, he delved into MOS basics. He asked me to draw the characteristics graph, showing the different regions, and then explain the reason for a MOS being in saturation. I explained it to him by drawing the internal structure of an NMOS.

After that, I was asked to write the current-voltage expressions for the saturation and linear regions.

Then, he asked me about amplifiers and in which of the three regions they operate. I wasn't able to answer that. He then explained the reason for it working in saturation.

At the end, the only feedback he gave me was that I have good basic knowledge but should try to answer more confidently. He also mentioned that while knowledge of tools is fine, I should also understand how they have evolved over the years and what happens internally.

### Round 3 (HR) - 15 min

The next HR round started with questions about what I knew about the role, if I had any idea who had taken my second interview, and why I had chosen to attend NIT Rourkela. 

I was also asked why I switched from Electrical to Electronics, and I justified the decision based on my interests. 

Then, the interviewer asked about my family and where I am from. 

Finally, I was asked to give a short introduction, which led to questions about my current project. 

After that, she provided information about the job location and package, and the interview concluded.
