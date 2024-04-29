# Gluten F (Free or F***?)

Celiac disease diagnoses are steadily increasing in Italy, and the goal of this project is to analyze the current situation, compare it with the past, and investigate the phenomenon in detail.

## About

The data were collected by downloading the PDF ["Relazione annuale al Parlamento sulla celiachia - Anno 2021"](https://www.salute.gov.it/portale/documentazione/p6_2_2_1.jsp?lingua=italiano&id=3308), extracting the tables inside it with Excel in a CSV format ([read more here](https://www.makeuseof.com/easily-extract-table-from-pdf/)). After some data cleaning and pre-processing, like handling whitespaces, null values, incorrect commas and punctuation, data types and more, I started performing my analysis by performing queries with SQL.

- https://www.epicentro.iss.it/celiachia/epidemiologia-italia
- https://www.epicentro.iss.it/celiachia/aggiornamenti

## Repository overview

```
├── README
├── data
│   └── raw
├── notebooks
└── figures
```