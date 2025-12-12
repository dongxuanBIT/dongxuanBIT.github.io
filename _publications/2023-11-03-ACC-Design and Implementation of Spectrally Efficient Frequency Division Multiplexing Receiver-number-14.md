---
title: "[J14] Design and Implementation of Spectrally Efficient Frequency Division Multiplexing Receiver"
collection: publications
category: manuscripts
permalink: /publication/2023-11-03-ACC-Design and Implementation of Spectrally Efficient Frequency Division Multiplexing Receiver-number-14
excerpt: 'This paper is about the design of SEFDM receiver, including sampling frequency synchronization (SFS), timing synchronization, phase recovery, and detector design.'
date: 2023-11-03
venue: 'IEEE Access '
paperurl: 'http://dongxuanBIT.github.io/files/J14_Design_and_Implementation_of_Spectrally_Efficient_Frequency_Division_Multiplexing_Receiver.pdf'
citation: 'Y. Qi, T. Zhang, Y. Feng, Z. Qin and D. He, &quot;Design and Implementation of Spectrally Efficient Frequency Division Multiplexing Receiver,&quot; <i>IEEE Access</i>, vol. 11, pp. 121482–121491, Nov. 2023.'

---

Compared to orthogonal frequency division multiplexing (OFDM), spectrally efficient frequency division multiplexing (SEFDM) provides higher spectrum efficiency, which has been regarded as a promising waveform for future wireless communications. Against this background, the design of SEFDM receiver is investigated in this paper, considering its sampling frequency synchronization (SFS), timing synchronization, phase recovery, and detector design. Specifically, a two-step SFS module, which consists of a coarse sampling frequency offset (SFO) compensation and a frequency domain zero-forcing based fine estimation, is proposed first. Next, a low-complexity timing synchronization scheme is designed to avoid excessive multipliers and look-up-tables. Furthermore, an SFO-based phase recovery is proposed, which shares the compensation and SFO estimation with SFS module, thus further reducing the complexity of SEFDM receiver. Moreover, the truncated singular value decomposition-fixed sphere decoder (TSVD-FSD) based detector has been studied to efficiently eliminate intercarrier interference. Simulation results demonstrate the superiority of our proposed SEFDM receiver, where the transmission rate can be improved by 25% at a loss of only 0.7dB bit error ratio compared to OFDM. Finally, field programmable gate array (FPGA) based implementation is carried out to verify the effectiveness of our proposed SEFDM receiver in practice.
