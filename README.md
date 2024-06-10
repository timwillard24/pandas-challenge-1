# Pandas Challenge 1

This repository contains a Jupyter Notebook that demonstrates data analysis using the Pandas library. The notebook showcases various data manipulation techniques applied to a dataset of client orders.

## Repository Contents

- `pandas-challenge-1.ipynb`: Jupyter Notebook containing the data analysis and manipulation tasks.

## Project Overview

The `pandas-challenge-1.ipynb` notebook covers the following tasks:

1. **Data Exploration**:
    - Loading and inspecting the dataset.
    - Checking for missing values and data types.
    - Basic statistics and data distribution.

2. **Data Transformation**:
    - Creating new columns such as `subtotal`, `total_shipping_price`, `total_price`, and `profit`.
    - Calculating shipping prices based on conditions.
    - Adding columns for total price and profit calculations.

3. **Data Analysis**:
    - Identifying the top 5 clients by the number of entries and total spending.
    - Summarizing key metrics for the top 5 clients, including total units purchased, total shipping price, total revenue, and total profit.
    - Converting total values to millions and formatting the numbers as strings with two decimal places followed by 'M'.

4. **Summary and Visualization**:
    - Creating a summary DataFrame for the top 5 clients.
    - Sorting and formatting the data for presentation.

## Usage

To run the notebook and reproduce the analysis:

1. Clone the repository:
    ```bash
    git clone https://github.com/timwillard24/pandas-challenge-1.git
    cd pandas-challenge-1
    ```

2. Install the necessary dependencies (if not already installed):
    ```bash
    pip install pandas jupyter
    ```

3. Start the Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

4. Open and run `pandas-challenge-1.ipynb`.

## Example Output

The notebook generates a summary of the top 5 clients by various metrics, formatted for easy readability:
Client ID Units Shipping (millions) Total Revenue (millions) Total Profit (millions)
0 24741 239862 $5.13M $82.27M $36.58M
2 38378 73667 $3.43M $12.91M $3.27M
4 66037 43018 $1.40M $10.26M $3.26M
3 46820 75768 $1.60M $9.74M $2.74M
1 33615 64313 $1.83M $8.38M $2.20M


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## Contact

For any questions or inquiries, please contact Tim Willard.

---

Happy coding!


