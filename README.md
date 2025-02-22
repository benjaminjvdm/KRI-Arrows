# Kairi Relative Index with Arrows 📈📉

<div align="center">
  <img src="https://github.com/benjaminjvdm/KRI-Arrows/blob/8c9ba7d37c178b382f70678f567eb1ef718531f3/logo" alt="KRI Logo" width="200"/>
</div>

This Pine Script calculates the Kairi Relative Index (KRI) and plots buy/sell signals on the chart. 

## How it works ⚙️

The script calculates the KRI as follows:

```
KRI = 100 * (Source - SMA) / SMA
```

where:

*   `Source` is the price source (e.g., close price).
*   `SMA` is the Simple Moving Average of the source price.

Buy signals are plotted when the KRI crosses above zero 🟢, and sell signals are plotted when the KRI crosses below zero 🔴.

## Usage 💻

1.  Add the script to your TradingView chart.
2.  Adjust the `Length` input to control the period of the Simple Moving Average.
3.  Adjust the `Source` input to select the price source.

## Custom Script Development 🧑‍💻

Need a Custom Script Developed? Contact Me = sales@byeol.tech or https://byeol.tech/#contact

## License

MIT License

Copyright (c) 2024 byeol.tech

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
