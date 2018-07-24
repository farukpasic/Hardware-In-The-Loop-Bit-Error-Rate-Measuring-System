# Hardware-In-The-Loop-Bit-Error-Rate-Measuring-System

During the data transmission between two or more remote users in each telecommunication system, errors occur in the message. 
The cause of errors lies in the fact that there is no ideal medium through which these messages are transmitted. 
For designing new and evaluating the work of existing telecommunication systems, it is necessary to have unique objective criteria 
that are related to acceptable quality of service. 
Fundamental objective criteria for quality evaluation of each system is Bit Error Rate (BER). 
By measuring BER, it is possible to verify the performance of the entire system, not only its individual components, 
which is its greatest advantage.

Hardware-In-The-Loop BER measuring system is designed using the WinIQSIM software, 
the Dual-Channel Arbitrary Generator R&S AM300, the RF Signal Generator R&S SM300, 
software defined receiver RTL-SDR, and MATLAB software package.

The modulated bit sequence using the BPSK or QPSK modulation type is transmitted through the transmitting antenna, and after passing
through the communication channel, is received by the receiving antenna. Since the original transmitted sequence is known on the receiving 
side, it is possible to compare transmitted and received sequence with each other, and thereby to measure the BER for different 
conditions in the channel. Also, a system setup and monitoring application was created using the MATLAB GUI tool 
that significantly facilitates handling with this measuring system. Using this application, it is possible to adjust all the required parameters 
of the receiving system and to observe various quality indicators of the received signal such as constellation diagrams, IQ components, 
transmitted and received sequences, noise signal etc. Since the transmitter constantly repeats sending the same sequence, 
the application also allows performing multiple consecutive measurements of the signal, whereby the receiving antenna can be moved 
in the space, thereby obtaining different values of BER for the different values of the EbNo ratio that are continuously drawn 
on the BER diagram during the measurements.
