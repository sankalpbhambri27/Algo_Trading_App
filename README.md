# Algo_Trading_App
Real-Time Trading Bot integrating MT5 and Python.

Strategy to buy/sell stocks so as to maximize the profit

1)close price of current candle is greater than high price of previous candle then its a long condition 
2) close price of current candle is less than low price of previous candle then its a short condition

Strategy to close previously open trade
1)close price of current candle is less than close price of previous candle then its time to close long condition
2)close price of current candle is greater than close price of previous candle then its time to close short condition


MT5 Python API is used to extract Financial Data from the backend broker. We used order_send, positions_total, and positions_get functions.

## Repository Contents

This repository includes the Jupyter Notebooks

## Getting Started

To get started with the tutorial:

1. **Clone the Repository**: Clone this repository to your local machine using:
   ```bash
   git clone 
   ```

2. **Set Up Your Environment**:
    - It is recommended to use a virtual environment.
    - Open the getting_started.md file to follow the setup instructions.
    ## How to run?

```bash
conda create -n algotradingapp python=3.8 -y
```

```bash
conda activate algotradingapp
```

```bash
pip install -r requirements.txt
```




4. **Run the Jupyter Notebooks**: Open the notebooks in Jupyter and follow along with the course.

## Prerequisites

Before starting this course, you should have:

- Basic knowledge of Python programming.
- Understanding of financial markets and trading principles.
- Familiarity with Jupyter Notebooks.
- This is taught at a graduate level.

## Contributing

We welcome contributions to this tutorial! If you have suggestions for improvements, please feel free to make a pull request or open an issue.

## License

This tutorial is provided under the [MIT License](LICENSE).

## Contact

For any queries or feedback related to this course, please contact system[at]wegood.com
'## Git commands

```bash
git add .

git commit -m "Updated"

git push origin main
```