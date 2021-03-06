# Logitech UE4000 2012
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -10.9; 23 -11.1; 25 -11.2; 28 -11.4; 31 -11.5; 34 -11.6; 37 -11.7; 41 -11.8; 45 -11.8; 49 -11.9; 54 -12.0; 60 -12.1; 66 -12.3; 72 -12.5; 79 -12.8; 87 -13.1; 96 -13.2; 106 -13.2; 116 -13.9; 128 -13.9; 141 -13.4; 155 -13.7; 170 -13.2; 187 -13.4; 206 -13.6; 227 -13.1; 249 -12.3; 274 -11.2; 302 -10.3; 332 -9.3; 365 -8.6; 402 -8.6; 442 -8.6; 486 -9.2; 535 -9.6; 588 -9.9; 647 -10.5; 712 -11.2; 783 -11.2; 861 -11.4; 947 -10.8; 1042 -11.2; 1146 -10.8; 1261 -10.2; 1387 -9.6; 1526 -8.9; 1678 -8.0; 1846 -6.5; 2031 -5.1; 2234 -3.5; 2457 -1.7; 2703 -0.5; 2973 -0.5; 3270 -0.5; 3597 -0.5; 3957 -1.0; 4353 -3.7; 4788 -2.9; 5267 -0.7; 5793 -0.5; 6373 -1.0; 7010 -4.0; 7711 -6.2; 8482 -6.5; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Logitech UE4000 2012 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Logitech UE4000 2012 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.1dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.8dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 48 Hz   | 0.3  | -5.2 dB |
| Peaking | 172 Hz  | 0.93 | -4.6 dB |
| Peaking | 1043 Hz | 0.85 | -5.3 dB |
| Peaking | 2973 Hz | 1.33 | 7.4 dB  |
| Peaking | 5849 Hz | 3.54 | 5.4 dB  |
| Peaking | 170 Hz  | 2.41 | 2.4 dB  |
| Peaking | 200 Hz  | 1.16 | -2.1 dB |
| Peaking | 366 Hz  | 2.19 | 1.6 dB  |
| Peaking | 694 Hz  | 5.04 | -0.8 dB |
| Peaking | 8319 Hz | 4.08 | -1.1 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-7.3dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | -4.8 dB |
| Peaking | 62 Hz    | 1.41 | -4.0 dB |
| Peaking | 125 Hz   | 1.41 | -6.4 dB |
| Peaking | 250 Hz   | 1.41 | -4.2 dB |
| Peaking | 500 Hz   | 1.41 | -0.5 dB |
| Peaking | 1000 Hz  | 1.41 | -6.1 dB |
| Peaking | 2000 Hz  | 1.41 | 1.8 dB  |
| Peaking | 4000 Hz  | 1.41 | 6.7 dB  |
| Peaking | 8000 Hz  | 1.41 | 0.4 dB  |
| Peaking | 16000 Hz | 1.41 | -0.3 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Logitech%20UE4000%202012/Logitech%20UE4000%202012.png)