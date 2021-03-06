# JVC HA-FXT90
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -1.0; 25 -1.5; 28 -2.3; 31 -3.0; 34 -3.6; 37 -4.1; 41 -4.6; 45 -5.1; 49 -5.5; 54 -6.0; 60 -6.6; 66 -7.1; 72 -7.5; 79 -7.9; 87 -8.5; 96 -8.9; 106 -9.2; 116 -9.3; 128 -9.4; 141 -9.6; 155 -9.5; 170 -9.4; 187 -9.2; 206 -9.0; 227 -8.6; 249 -8.2; 274 -7.8; 302 -7.2; 332 -6.9; 365 -6.3; 402 -5.8; 442 -5.0; 486 -4.5; 535 -4.0; 588 -3.2; 647 -2.7; 712 -2.4; 783 -1.9; 861 -2.0; 947 -2.0; 1042 -2.3; 1146 -2.8; 1261 -2.8; 1387 -3.5; 1526 -2.6; 1678 -2.4; 1846 -3.2; 2031 -3.7; 2234 -4.0; 2457 -4.1; 2703 -4.2; 2973 -3.1; 3270 -1.6; 3597 -1.1; 3957 -2.4; 4353 -5.6; 4788 -8.1; 5267 -8.5; 5793 -6.1; 6373 -4.0; 7010 -4.5; 7711 -7.3; 8482 -8.3; 9330 -5.3; 10263 -5.2; 11289 -5.2; 12418 -5.2; 13660 -5.2; 15026 -5.2; 16529 -5.2; 18182 -5.2; 20000 -5.2
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`JVC HA-FXT90 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `JVC HA-FXT90 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-5.5dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-5.1dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 15 Hz   | 0.53 | 6.0 dB  |
| Peaking | 151 Hz  | 0.43 | -4.9 dB |
| Peaking | 813 Hz  | 0.61 | 4.0 dB  |
| Peaking | 3589 Hz | 3.47 | 4.6 dB  |
| Peaking | 4963 Hz | 4.1  | -4.6 dB |
| Peaking | 1457 Hz | 3.07 | -1.3 dB |
| Peaking | 1611 Hz | 5.29 | 2.1 dB  |
| Peaking | 5559 Hz | 6.12 | -1.4 dB |
| Peaking | 6487 Hz | 3.46 | 2.5 dB  |
| Peaking | 8152 Hz | 5.39 | -4.0 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-4.0dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 3.6 dB  |
| Peaking | 62 Hz    | 1.41 | -1.8 dB |
| Peaking | 125 Hz   | 1.41 | -4.1 dB |
| Peaking | 250 Hz   | 1.41 | -3.0 dB |
| Peaking | 500 Hz   | 1.41 | 1.3 dB  |
| Peaking | 1000 Hz  | 1.41 | 3.1 dB  |
| Peaking | 2000 Hz  | 1.41 | 1.3 dB  |
| Peaking | 4000 Hz  | 1.41 | 1.2 dB  |
| Peaking | 8000 Hz  | 1.41 | -1.8 dB |
| Peaking | 16000 Hz | 1.41 | 0.2 dB  |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/JVC%20HA-FXT90/JVC%20HA-FXT90.png)