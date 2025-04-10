# -DIGITAL-FILTER-DESIGN
# COMPANY: CODETECH IT SOLUTIONS
# NAME: INDANURU MALLESH
# INTERN ID: CT04WC90
# DOMAIN: VLSI 
# DURATION: 4 WEEKS
# MENTOR: NEELA SANTOHSH KUMAR 
# DESCPRITION:
  The humble FIR filter is one of the most basic building blocks in digital signal processing on an FPGA, so it's important to know how to throw together a basic module of one with a given number of taps and their corresponding coefficient values. Thus, in this mini-series on the practical way of getting started with DSP basics on FPGAs, I'm going to start with a simple 15-tap low pass filter FIR that I generate the initial coefficient values for in Matlab then convert those values for use in a Verilog module. A finite impulse response or FIR filter is defined as a filter with an impulse response that settles to a zero value over a certain period of time, thus making it finite. This amount of time that it takes the impulse response to settle to zero is directly related to the order of the filter (the number of taps) which is the order of the FIR's underlying transfer function polynomial. A FIR's transfer function contains no feedback, so if you feed in a single impulse of value 1 followed by a bunch of zero values, the output will simply be the coefficient values of the filter. The role of any filter is for signal conditioning, mainly focusing on the selection of which frequencies to either filter out or allow to pass through. One of the simplest examples of this is the low pass filter, which allows frequencies below a certain threshold (cutoff frequency) to pass while greatly attenuating frequencies above that threshold.
