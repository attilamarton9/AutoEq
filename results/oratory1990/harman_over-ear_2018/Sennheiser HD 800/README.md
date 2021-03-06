# Sennheiser HD 800
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -0.5; 25 -0.5; 28 -0.6; 31 -0.9; 34 -1.2; 37 -1.5; 41 -1.9; 45 -2.2; 49 -2.3; 54 -2.2; 60 -2.1; 66 -2.5; 72 -3.3; 79 -4.0; 87 -4.6; 96 -5.2; 106 -5.7; 116 -6.2; 128 -6.6; 141 -6.9; 155 -7.2; 170 -7.4; 187 -7.6; 206 -7.7; 227 -7.8; 249 -7.8; 274 -7.6; 302 -7.4; 332 -7.2; 365 -7.1; 402 -7.0; 442 -6.9; 486 -6.8; 535 -6.7; 588 -6.6; 647 -6.5; 712 -6.4; 783 -6.4; 861 -6.3; 947 -6.2; 1042 -6.0; 1146 -5.7; 1261 -5.1; 1387 -4.4; 1526 -3.8; 1678 -3.5; 1846 -3.5; 2031 -3.4; 2234 -3.7; 2457 -4.9; 2703 -5.7; 2973 -5.9; 3270 -5.2; 3597 -4.8; 3957 -5.5; 4353 -6.8; 4788 -8.5; 5267 -11.6; 5793 -14.2; 6373 -10.4; 7010 -8.3; 7711 -9.5; 8482 -6.7; 9330 -6.5; 10263 -6.6; 11289 -10.9; 12418 -12.7; 13660 -12.0; 15026 -10.0; 16529 -9.2; 18182 -10.6; 20000 -14.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Sennheiser HD 800 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sennheiser HD 800 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.0dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.6dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 25 Hz    | 1.03 | 6.3 dB  |
| Peaking | 60 Hz    | 2.28 | 3.3 dB  |
| Peaking | 1926 Hz  | 1.33 | 3.3 dB  |
| Peaking | 5703 Hz  | 5.29 | -7.8 dB |
| Peaking | 20608 Hz | 0.11 | -5.4 dB |
| Peaking | 230 Hz   | 1.14 | -1.5 dB |
| Peaking | 3731 Hz  | 5.16 | 1.9 dB  |
| Peaking | 9960 Hz  | 2.2  | 6.9 dB  |
| Peaking | 11789 Hz | 1.03 | -6.4 dB |
| Peaking | 16027 Hz | 1.38 | 3.5 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-7.0dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 5.9 dB  |
| Peaking | 62 Hz    | 1.41 | 3.2 dB  |
| Peaking | 125 Hz   | 1.41 | -0.7 dB |
| Peaking | 250 Hz   | 1.41 | -1.4 dB |
| Peaking | 500 Hz   | 1.41 | -0.2 dB |
| Peaking | 1000 Hz  | 1.41 | 0.0 dB  |
| Peaking | 2000 Hz  | 1.41 | 3.7 dB  |
| Peaking | 4000 Hz  | 1.41 | -1.2 dB |
| Peaking | 8000 Hz  | 1.41 | -2.8 dB |
| Peaking | 16000 Hz | 1.41 | -5.7 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/oratory1990/harman_over-ear_2018/Sennheiser%20HD%20800/Sennheiser%20HD%20800.png)