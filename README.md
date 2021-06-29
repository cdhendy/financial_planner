
Module 5 - Challenge 5 : Financial Planner
=============================================

## Purpose

 The purpose of this notebook is twofold: First, to determine if the credit union member has enough funds to create an emergency fund, and secondly, to determine if the credit union member has enough funds to plan for retirement. When planning for retirement, 10 and 30 year forecast models were created with the help of monte carlo simulation, with different weights added to the stock and bond portfolios.

---

## Technologies

Jupyter notebooks and the Pandas data analysis library were used in the creation of this project. MCForecast Tools were also used to create expected probabilities over the course of 10 and 30 year projections. The Alpaca API was used for the current market prices of AGG and SPY. 

---

## Installation Guide

First, install the jupyter and pandas libraries. In your terminal or command shell type the following: 

```python
pip install jupyter
```

```python
pip install pandas
```

```python
pip install numpy
```

Additionally, matplotlib was used in the creation of the data visualization. This is included in the imports at the beginning of the jupyter notebook. 

In order for this simulation to work, the user needs to create a .env file containing their Alpaca API key and Alpaca secret key.

---

## Conclusion

Contained within the notebook are the results of the analysis. 

---

## Contributors

Created by: Chris Henderson

cdhendy@gmail.com

[LinkedIn](https://www.linkedin.com/in/chris-henderson123/)

---

## License

(c) Copyright 2021 Chris Henderson

Licensed under the MIT license:

    http://www.opensource.org/licenses/mit-license.php

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.