# Some common equations that I find myself using fairly often
## Ohm's Law and Power equations
$V = IR$

$I = \frac{V}{R}$

$R = \frac{V}{I}$

$P = IV$

$I = \frac{P}{V}$

$V = \frac{P}{I}$

$P = I^2 R$

$P = \frac{V^2}{R}$
### Decibel equations
_Note that doubling power = a 3dB increase (halving is -3db)... to double the power in a fixed load, you must increase voltage by 1.414214X_ 

_Other useful rules of thumb: 4X = ~6dB / 5X = ~7dB / 10X = 10dB / 100X = 20dB_

_In terms of voltage, some useful rules of thumb: 2X voltage = ~6dB / 4X voltage = 12dB / 10X voltage = 20dB / 100X voltage = 40dB_

_A point of confusion is that doubling the voltage is a 6dB increase in power (since V^2/R = P), so you need a 1.414214 increase in voltage to double the power..._

_If you do the math with the correct dB equation, you will see that dbV and dbP will be the same when doubling power and 1.414214X'ing the voltage_

$Power_{dB} = 10 \log_{10} \left( \frac{P_2}{P_1} \right)$

$Voltage_{dB} = 20 \log_{10} \left( \frac{V_2}{V_1} \right)$

## Capacitor equations:
$i(t) = C \frac{dv(t)}{dt}$

$v(t) = \frac{1}{C} \int i(t) \, dt + v(0)$

## Inductor equations:
$v(t) = L \frac{di(t)}{dt}$

$i(t) = \frac{1}{L} \int v(t) \, dt + i(0)$

## Op-Amp Equations
### Gain: Op-amp with simple feedback (non-inverting amplifier)
$A_v = 1 + \frac{R_f}{R_{in}}$

### Gain: Inverting amplifier:
$A_v = -\frac{R_f}{R_{in}}$
