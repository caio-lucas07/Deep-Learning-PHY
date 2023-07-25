# Deep-Learning-PHY
Scripts used for my undergraduate thesis in the theme "A Deep Learning assessment applied to end-to-end wireless communications."

### Context
This work proposes to evaluate the possibility of using Deep Learning techniques in the physical layer of a digital communication system. The main and only architecture used in this work
consists of an Autoencoder framework composed by two deep neural networks (DNN), one as an encoder and another as a decoder. Thus, we sought to remodel the physical layer of a classic
wireless communication system as a single block, specifically replacing the modulation and encoding blocks, in such a way as to optimize the end-to-end transmission and reception process.
The results of the work are obtained by computational simulations with comparisons made with conventional modulation and coding schemes to investigate the aforementioned possibility. The
results using bit error rate (BER) and block error rate (BLER) show that the approach based on Deep Learning is somehow promising, presenting comparable performances to conventional ones
or even superior in certain cases. Some constellation diagrams also demonstrate the ability of the Autoencoder architecture to learn a unique symbol scheme robust to the channel impairments.
A single-user scenario with the AWGN (Additive White Gaussian Noise) channel model was adopted in this work.

### Project Structure
+ *Caio-Lucas-undergrad-thesis.pdf* - the thesis file in which one can read for a better and deeper understanding of the proposed problem and solution. 
+ *coded-systems.ipynb* refers to the comparison between the Autoencoders and a mobile communication chain **with** encoding/decoding part (with modulation/demodulation + encoding/decoding blocks).
+ *uncoded-systems.ipynb* refers to the comparison between the Autoencoders and a mobile communication chain **without** encoding part (only with modulation/demodulation blocks).
