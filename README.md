# A-bandpass-filter-for-a-neurological-signal-acquisation-system
In this project, we aimed to design a bandpass filter for a neural measurement system.
The neural measurement system is composed of an electrode array for signal recording,
multiple low noise amplifiers for signal amplification, multiplexers and A/D converters for
digitalization of the incoming data and a digital ASIC for preprocessing and signal processing.
The energy of the system is constrained to a low power design. Due to the limitation of the
maximum applied field to the brain the transmitted power cannot be too large. Furthermore
the heat dissipation has to be considered, otherwise a small increase in temperature will
lead to tissue damage. So here the maximum power of each amplifier is 180 μW.

Another important constraint is the low noise. For signals detected in this system are
Local Field Potentials (LEP) and Neural Spikes. The Local Field Potentials record signal of a
large number of contributing neurons for each electrode. It represents the activity of a
specific observed area. It can be seen as an envelope of spike activity. The amplitude of LEP
is usually smaller than 5mV and the bandwidth is from 1Hz to 250Hz. Spikers are recorded
from a dedicated neuron. The Amplitude is much higher which is from 50 to 500 μV and
bandwidth is from 1Hz to 10kHz. Due to the attributes of these two signals we need to
design a bandpass filter with a suitable bandwidth. Here the interesting bandwidth is from
0.1kHz to 1kHz. Since he amplifier is very noise sensitive, the input referred noise is limited
to 20 to 30 nV Hz / .
Due to the fact the incoming signals are in the microvolt range, a high amplification is
needed. Here a gain of 40 dB is needed in this bandpass filter.
