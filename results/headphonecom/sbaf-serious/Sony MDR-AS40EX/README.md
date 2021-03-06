# Sony MDR-AS40EX
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -6.4; 23 -6.7; 25 -7.0; 28 -7.4; 31 -7.6; 34 -7.9; 37 -8.1; 41 -8.3; 45 -8.6; 49 -8.8; 54 -9.0; 60 -9.3; 66 -9.6; 72 -9.9; 79 -10.2; 87 -10.5; 96 -10.6; 106 -10.9; 116 -10.9; 128 -11.0; 141 -11.0; 155 -11.0; 170 -11.0; 187 -10.8; 206 -10.6; 227 -10.2; 249 -9.8; 274 -9.3; 302 -8.7; 332 -8.2; 365 -8.0; 402 -7.4; 442 -6.9; 486 -6.4; 535 -5.8; 588 -5.2; 647 -4.7; 712 -4.1; 783 -3.9; 861 -3.7; 947 -3.9; 1042 -4.2; 1146 -4.4; 1261 -4.7; 1387 -5.2; 1526 -5.7; 1678 -6.4; 1846 -6.3; 2031 -5.2; 2234 -4.1; 2457 -3.0; 2703 -1.9; 2973 -1.0; 3270 -0.5; 3597 -1.2; 3957 -4.0; 4353 -7.6; 4788 -9.0; 5267 -7.2; 5793 -4.7; 6373 -3.7; 7010 -4.5; 7711 -7.6; 8482 -10.3; 9330 -7.8; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.6; 16529 -10.4; 18182 -8.1; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Sony MDR-AS40EX GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sony MDR-AS40EX ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.3dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.7dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 84 Hz    | 0.62 | -2.6 dB |
| Peaking | 186 Hz   | 0.72 | -3.3 dB |
| Peaking | 818 Hz   | 1.22 | 3.2 dB  |
| Peaking | 3098 Hz  | 2.81 | 6.5 dB  |
| Peaking | 22050 Hz | 2.3  | 1.2 dB  |
| Peaking | 3696 Hz  | 6.14 | 2.6 dB  |
| Peaking | 4731 Hz  | 2.76 | -5.9 dB |
| Peaking | 6330 Hz  | 1.54 | 4.6 dB  |
| Peaking | 8465 Hz  | 4.17 | -5.8 dB |
| Peaking | 17113 Hz | 2.76 | -4.6 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-3.6dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | -0.5 dB |
| Peaking | 62 Hz    | 1.41 | -2.4 dB |
| Peaking | 125 Hz   | 1.41 | -4.1 dB |
| Peaking | 250 Hz   | 1.41 | -3.1 dB |
| Peaking | 500 Hz   | 1.41 | 0.9 dB  |
| Peaking | 1000 Hz  | 1.41 | 2.3 dB  |
| Peaking | 2000 Hz  | 1.41 | 1.2 dB  |
| Peaking | 4000 Hz  | 1.41 | 3.0 dB  |
| Peaking | 8000 Hz  | 1.41 | -1.3 dB |
| Peaking | 16000 Hz | 1.41 | -2.1 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Sony%20MDR-AS40EX/Sony%20MDR-AS40EX.png)