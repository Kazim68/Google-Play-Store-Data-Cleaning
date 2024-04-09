# Google Play Store Data Cleaning using Pandas

This project focuses on cleaning and preprocessing a dataset obtained from Data Wars containing information about apps from the Google Play Store. The dataset was cleaned using the pandas library in Python.

## Dataset Information

The dataset contains the following columns:

- `App`: Name of the application
- `Category`: Category to which the app belongs
- `Rating`: Overall user rating of the app (out of 5)
- `Reviews`: Number of user reviews for the app
- `Size`: Size of the app
- `Installs`: Number of times the app has been installed
- `Type`: Paid or Free
- `Price`: Price of the app
- `Content Rating`: Target audience for the app
- `Genres`: Genres under which the app falls
- `Last Updated`: Date when the app was last updated
- `Current Ver`: Current version of the app
- `Android Ver`: Minimum required Android version

## Data Cleaning Process

- Converted the 'Installs' column to numeric format.
- Removed commas and plus signs from the 'Installs' column to convert it to a numeric type.
- Cleaned the 'Size' column to remove unnecessary characters and convert it to a numeric type.
- Cleaned the 'Price' column to remove currency symbols and convert it to a numeric type.
- Standardized the 'Genres' column by removing redundant information.

## Usage

1. Clone the repository to your local machine.
2. Ensure you have pandas and any other required libraries installed.
3. Open the Jupyter notebook file `Google_Play_Store_Data_Cleaning.ipynb`.
4. Run each cell in the notebook to see the cleaning process and the cleaned dataset.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
