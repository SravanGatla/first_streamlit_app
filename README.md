# My Mom's New Healthy Diner 🥗🍓🥑

Welcome to **My Mom's New Healthy Diner**! This Streamlit app provides an interactive platform to explore breakfast favorites, build custom fruit smoothies, and learn more about different fruits using external APIs. Users can also manage a fruit load list stored in Snowflake.

## Features

### Breakfast Favorites
- **Omega 3 & Blueberry Oatmeal** 🥣
- **Kale, Spinach, Rocket Smoothie** 🥗
- **Hard-Boiled Free-Range Egg** 🐔
- **Avocado Toast** 🥑🍞

### Build Your Own Fruit Smoothie 🍌🥭🥝🍇
- **Select Fruits**: Choose from a list of fruits to customize your fruit smoothie.
- **Nutritional Information**: Get the nutritional details of the selected fruits.

### Fruityvice Fruit Advice 🍎🍊🍋
- **Fruit Information**: Enter a fruit name to fetch detailed information from the Fruityvice API.

### Snowflake Fruit Load List 🍒🍍
- **Get Fruit Load List**: Retrieve the list of fruits stored in Snowflake.
- **Add a Fruit**: Add a new fruit to the Snowflake database.

## Setup Instructions

### Prerequisites
- Python 3.x
- Streamlit
- Pandas
- Requests
- Snowflake Connector

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   ```
2. Navigate to the project directory:
   ```bash
   cd your-repo
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

### Running the App
```bash
streamlit run app.py
```

## Data Sources
- **Fruit Macros**: [CSV File](https://uni-lab-files.s3.us-west-2.amazonaws.com/dabw/fruit_macros.txt)
- **Fruityvice API**: [Fruityvice](https://fruityvice.com/api)
- **Snowflake Database**: Managed Snowflake database for storing the fruit load list.

## Acknowledgments
- **Streamlit**: For creating interactive web apps with Python.
- **Pandas**: For data manipulation and analysis.
- **Requests**: For making HTTP requests to external APIs.
- **Snowflake Connector**: For connecting and interacting with Snowflake databases.

## Author
- **Sravankumar Galta**
- **GitHub**: [Your GitHub Profile](https://github.com/SravanGatla)

