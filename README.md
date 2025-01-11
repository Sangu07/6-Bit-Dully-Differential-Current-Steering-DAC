# 6-Bit-Dully-Differential-Current-Steering-DAC
This project involves the design and analysis of a 6-bit fully differential current steering 
Digital-to-Analog Converter (DAC) tailored to meet specific performance criteria. The DAC 
was designed for a 180 nm process with a 1.8 V analog supply and a full-scale output voltage 
of 1.6 V (peak-to-peak). The design process was divided into two main stages. In the first 
stage, the DAC was implemented using ideal current sources, and its output transfer 
characteristics were evaluated. 
In the second stage, a practical implementation was achieved using PMOS current sources 
and a row-column decoder (2:3-to-8 priority decoder) to control the DAC's output based on 
digital input. The design utilized current mirroring with MOSFETs to generate the required 
analog output. The transfer characteristics were plotted, and Integral Non-Linearity (INL) and 
Differential Non-Linearity (DNL) were calculated using a Python script developed for this 
purpose. Furthermore, the effects of random mismatches in the width of unit transistors, with 
deviations of 0.1% and 1%, were analysed to evaluate the impact on INL and DNL. 
Simulations were performed using LTspice, and the results demonstrated compliance with the 
design specifications, providing insights into the trade-offs and limitations of the DAC 
architecture.
