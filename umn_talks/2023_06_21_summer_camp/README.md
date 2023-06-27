# UMN Data Summer Camp

This is a directory contains the two notebooks that were used to present time series forecasting and classification at the 2023 Summer Data Camp at the University of Minnesota.

- [m5 competition](notebooks/m5_competition.ipynb)
- [time series classification](notebooks/signal_processing.ipynb)

# Setup

## Virtual Environment Primer

You will need the required libraries to run these notebooks. You can create a virtual environment with the [requirements.txt](requirements.txt) file. Here is a useful [guide](https://realpython.com/python-virtual-environments-a-primer) for creating and managing python environments.

If you don't have time to read the guide, just run the following:

## Windows Setup
```powershell
python -m venv .venv
.\.venv\Scripts\activate

pip install -r requirements.txt
python -m ipykernel install --user --name=.venv
```

## MacOS/Linux Setup
```powershell
python -m venv .venv
source .venv/bin/activate

pip install -r requirements.txt
python -m ipykernel install --user --name=.venv
```

# References

- [M5 Competition](https://www.kaggle.com/competitions/m5-forecasting-accuracy/overview)

# Contact

If you have questions about these notebooks, feel free to use the GitHub issues tab in this repo to post your question. This will hopefully result in answers and updated documentation.
