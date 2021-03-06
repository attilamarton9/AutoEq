# Grado RS1
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -0.5; 25 -0.5; 28 -0.5; 31 -0.5; 34 -0.5; 37 -0.5; 41 -0.5; 45 -0.5; 49 -0.5; 54 -0.5; 60 -1.0; 66 -2.1; 72 -3.2; 79 -4.2; 87 -5.2; 96 -5.9; 106 -6.4; 116 -6.5; 128 -6.6; 141 -6.5; 155 -6.3; 170 -6.0; 187 -5.8; 206 -5.4; 227 -4.8; 249 -4.9; 274 -4.8; 302 -4.5; 332 -4.2; 365 -3.8; 402 -4.1; 442 -3.8; 486 -3.7; 535 -3.5; 588 -3.2; 647 -3.1; 712 -3.2; 783 -2.8; 861 -2.9; 947 -3.2; 1042 -3.3; 1146 -3.3; 1261 -4.1; 1387 -5.2; 1526 -7.0; 1678 -8.3; 1846 -13.1; 2031 -11.6; 2234 -10.4; 2457 -8.7; 2703 -7.3; 2973 -5.0; 3270 -3.6; 3597 -2.3; 3957 -5.5; 4353 -13.0; 4788 -11.2; 5267 -8.5; 5793 -8.5; 6373 -11.6; 7010 -13.6; 7711 -11.2; 8482 -11.7; 9330 -12.3; 10263 -6.8; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -8.3; 18182 -10.3; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Grado RS1 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Grado RS1 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.6dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-7.1dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 34 Hz    | 0.8  | 7.0 dB   |
| Peaking | 1996 Hz  | 1.35 | -16.7 dB |
| Peaking | 2537 Hz  | 0.31 | 11.7 dB  |
| Peaking | 4490 Hz  | 6.74 | -10.5 dB |
| Peaking | 7253 Hz  | 1.17 | -11.9 dB |
| Peaking | 60 Hz    | 3.5  | 2.0 dB   |
| Peaking | 113 Hz   | 2.06 | -1.6 dB  |
| Peaking | 2669 Hz  | 7.8  | -1.6 dB  |
| Peaking | 3647 Hz  | 9.9  | 2.6 dB   |
| Peaking | 17815 Hz | 2.68 | -4.9 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-8.0dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 6.7 dB  |
| Peaking | 62 Hz    | 1.41 | 3.8 dB  |
| Peaking | 125 Hz   | 1.41 | -1.7 dB |
| Peaking | 250 Hz   | 1.41 | 1.4 dB  |
| Peaking | 500 Hz   | 1.41 | 2.3 dB  |
| Peaking | 1000 Hz  | 1.41 | 4.4 dB  |
| Peaking | 2000 Hz  | 1.41 | -4.8 dB |
| Peaking | 4000 Hz  | 1.41 | 1.5 dB  |
| Peaking | 8000 Hz  | 1.41 | -6.2 dB |
| Peaking | 16000 Hz | 1.41 | -0.5 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Grado%20RS1/Grado%20RS1.png)