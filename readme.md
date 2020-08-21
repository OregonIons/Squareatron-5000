Ultra-low noise limiting amplifier. Designed for stabilizing the amplitude of the RF voltages used in ion traps.

The circuit uses a low-noise digital circuit to convert an input "clock" to a square-wave with very stable amplitude. After band-pass filtering, we recover a sinusoid with stable amplitude.

Measurements using an R&S phase/amplitude noise meter demonstrate:
- No added phase noise compared with a top-of-the-range R&S synth
- AM noise limited by the measurement device at almost all offset frequencies (100k correlations). Broadband noise approximately at the -197dBc/Hz thermal noise floor!

Measurements with power detector show very low long-term drift. Temperature coefficient of output voltage amplitude is roughly -500ppm/C.

The output RF power is fixed at around 10dBm depending on frequency. The optional [DAC Board](https://github.com/OregonIons/Squareatron_DAC_Board) provides very fine digital tuning (1dB with 16-bit resolution).  If a larger dynamic range is required, a step attenuator after the squareatron is recommended.

Locking barrel connector is [Switchcraft 760K](http://www.switchcraft.com/Product.aspx?ID=2582).
