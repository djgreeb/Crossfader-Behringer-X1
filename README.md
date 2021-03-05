# Crossfader-Behringer-X1
UART to PWM converter for Behringer X1 crossfader

Meet the budget (10-12$) optical (!) Behringer X1 crossfader with mechanical force control. Can be used as a fader. The crossfader is made on the principle of an optical absolute encoder, has a resolution of 7 bits (128 positions). It's not much, but enough for the crossfader. Why didn't it become popular? It has an output signal that is not typical for crossfader: UART, and also not the standard frequency of 31kbps. Perhaps this drawback dictates a low price. To install it in the DJM 900nxs, I had to install an additional board with an STM32F103C8T6 microcontroller, to convert UART to PWM, and then to a constant signal. The mounting holes are 65mm apart, vs the pioneer 80mm. We drill. The stem for the knob is 8mm shorter - we are making a new one. In general, the cross is cool, but not suitable for everyone, it needs some work.


