# ecoforecast: an interpretable data-driven macroeconomic forecasting method based on N-BEATS&N-BEATSX neural network

To some extent, EcoForecast can balance the effectiveness, the efficiency, the generalizability and the interpretability while the conditions such as forecast frequency and time window changed, even unexpected incidents happened. Based on the actual macroeconomic data for China from 1995 to 2021, experimental results indicated that EcoForecast improved the accuracy up to 4.52 times compared with the traditional BVAR. In the robustness test, EcoForecast requires only a quarter of the data to achieve 2.62 times minor forecast errors of the BVAR. Our findings provide a new possible research direction for short-term macroeconomic forecasting.

###
using N-BEATS (https://arxiv.org/pdf/1905.10437v3.pdf) AND  NBEATSx (https://arxiv.org/pdf/2104.05522.pdf)

### result
![alt](https://github.com/navfour/ecoforest/results/result1.png)

We also retain the explainable function of NBEATSx

![alt](https://github.com/navfour/ecoforest/results/result2.png)

### From PyPI
you can also use `pip install ecoforecast`

## License
This project is licensed under the MIT License - see the LICENSEfile for details.

## Example
you can just use `GDPexample.py` or install the `ecoforecast` package
