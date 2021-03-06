# Creative Fatal1ty
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -7.8; 23 -8.5; 25 -9.2; 28 -9.9; 31 -10.5; 34 -11.1; 37 -11.5; 41 -12.0; 45 -12.3; 49 -12.6; 54 -12.8; 60 -13.1; 66 -13.2; 72 -13.4; 79 -13.5; 87 -13.7; 96 -13.6; 106 -13.5; 116 -13.5; 128 -13.5; 141 -13.4; 155 -13.2; 170 -12.8; 187 -12.6; 206 -12.1; 227 -11.6; 249 -11.0; 274 -10.4; 302 -9.5; 332 -8.9; 365 -8.0; 402 -7.6; 442 -7.0; 486 -6.9; 535 -7.3; 588 -7.7; 647 -8.5; 712 -9.0; 783 -8.7; 861 -9.1; 947 -9.2; 1042 -9.0; 1146 -8.7; 1261 -8.6; 1387 -8.8; 1526 -8.6; 1678 -8.0; 1846 -7.0; 2031 -5.4; 2234 -4.1; 2457 -2.5; 2703 -1.5; 2973 -0.6; 3270 -0.9; 3597 -1.8; 3957 -1.1; 4353 -0.5; 4788 -0.5; 5267 -0.5; 5793 -0.5; 6373 -1.0; 7010 -4.0; 7711 -6.2; 8482 -6.5; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Creative Fatal1ty GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Creative Fatal1ty ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.1dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.8dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 68 Hz   | 0.51 | -6.5 dB |
| Peaking | 175 Hz  | 1.1  | -3.6 dB |
| Peaking | 1378 Hz | 0.82 | -3.6 dB |
| Peaking | 2916 Hz | 1.29 | 6.4 dB  |
| Peaking | 5373 Hz | 2.11 | 5.5 dB  |
| Peaking | 467 Hz  | 3.45 | 1.4 dB  |
| Peaking | 721 Hz  | 3.65 | -0.9 dB |
| Peaking | 6439 Hz | 6.48 | 2.1 dB  |
| Peaking | 6722 Hz | 4.53 | 0.7 dB  |
| Peaking | 7664 Hz | 2.05 | -1.9 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-8.0dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | -3.2 dB |
| Peaking | 62 Hz    | 1.41 | -5.6 dB |
| Peaking | 125 Hz   | 1.41 | -6.1 dB |
| Peaking | 250 Hz   | 1.41 | -3.5 dB |
| Peaking | 500 Hz   | 1.41 | 0.9 dB  |
| Peaking | 1000 Hz  | 1.41 | -3.7 dB |
| Peaking | 2000 Hz  | 1.41 | 0.3 dB  |
| Peaking | 4000 Hz  | 1.41 | 7.6 dB  |
| Peaking | 8000 Hz  | 1.41 | 0.3 dB  |
| Peaking | 16000 Hz | 1.41 | -0.3 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Creative%20Fatal1ty/Creative%20Fatal1ty.png)