# CAPyM

These are some codes related to CAPM and portfolio management with Python. In the next lines I expect to explain the basics about CAPM, Beta, and some of the tools used to calculate it in Python, but I strongly recommend a review of the references at the end of this doc.

## Capital Asset Pricing Model

According to [Wikipedia](https://en.wikipedia.org/wiki/Capital_asset_pricing_model), CAPM is a model used to determine the appropriate rate of return of an asset, and it can be helpful when building a diversified portfolio. It can be expressed by:

![CAPM Formula](https://wikimedia.org/api/rest_v1/media/math/render/svg/0c9bd79589a7b9a957151f62b5dc2fcb285173a6)

Where the Beta represents the sensitivity of an asset in comparison with a benchmark:

![Beta Formula](https://wikimedia.org/api/rest_v1/media/math/render/svg/324ae3c4d7c5bf5816517265100de60f9f603547)

## Python Libraries

The notebooks in this repository will rely on [yfinance](https://pypi.org/project/yfinance/) to import data from yahoo finance directly into the code, [pandas](https://pandas.pydata.org/docs/) will be used for data wrangling, [matplotlib](https://matplotlib.org/3.3.2/contents.html) will be preferred for visualization, and [stats](https://docs.scipy.org/doc/scipy/reference/stats.html) module from SciPy will be the source of the statistical functions.

    import yfinance as yf
    import pandas as pd
    import matplotlib.pyplot as plt
    from scipy import stats

(...)

------------

Please drop me a note with feedback, contribute to this repository and/or send me a message on [LinkedIn](https://www.linkedin.com/in/arthurbretas/).

**Arthur Bretas**
