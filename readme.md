# S&P 500 Data Analysis App

Welcome to the S&P 500 Data Analysis App! This Streamlit web application retrieves and visualizes the list of **S&P 500** companies along with their **year-to-date stock closing prices**. Gain insights into the performance of different sectors and companies within the S&P 500.

## Features

- Retrieve the list of S&P 500 companies from [Wikipedia](https://en.wikipedia.org/wiki/List_of_S%26P_500_companies).
- Filter companies by sector using the sidebar interface.
- Display company data and statistics for the selected sector.
- Download the filtered company data as a CSV file.
- Visualize the year-to-date closing prices of selected companies using interactive plots.

## Installation

To run this application, you need to have the following packages installed:


```bash
pip install streamlit pandas base64 matplotlib seaborn numpy yfinance
streamlit run app.py
```

## Acknowledgments

This application is built upon the foundation of the powerful [dmis-lab/biobert-v1.1](https://huggingface.co/dmis-lab/biobert-v1.1) model from Hugging Face's Transformers library. We are grateful for the open-source contributions that have made this project possible.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to modify and adapt the code to your needs. We encourage contributions and collaboration from the open-source community.
