# 🏙️ Market Analysis of Public Catering Establishments in Moscow #
## 📌 Project Overview ##

Investors from the “Shut Up and Take My Money” fund plan to enter a new market and open a public catering establishment in Moscow.
The format of the future venue — café, restaurant, pizzeria, pub, or bar — is still undecided, as well as its location, menu, and pricing strategy.

We have access to reference data on Moscow’s food service establishments as of summer 2022.
The goal of this project is to analyze the market, uncover meaningful patterns, and provide insights that will help investors choose the most promising concept and location.

## 📁 Dataset Description ##

File: moscow_places.csv

### The dataset contains information about public catering venues in Moscow: ###

- name — establishment name

- address — establishment address

- category — venue type (e.g., café, pizzeria, coffee shop)

- hours — working days and hours

- lat / lng — geographic coordinates

- rating — user rating from Yandex Maps (max 5.0)

- price — price category (e.g., “average”, “below average”)

- avg_bill — average bill information as a text range

- middle_avg_bill — numeric estimate of the average bill:

  - median if a range is provided

  - exact value if a single price is given

  - empty if the string doesn’t start with “Average bill”

- middle_coffee_cup — numeric estimate of the cappuccino price (same rules as above)

- chain — 0/1 indicator showing whether the venue belongs to a chain

- district — administrative district

- seats — number of seats

## 🔍 Research Workflow ##
 1. Load and explore the data

Review the structure of the dataset

Check completeness and basic statistics

 2. Data preprocessing

Handle duplicates

Treat missing and inconsistent values

Compute additional derived features

 3. Exploratory Data Analysis (EDA)

Distribution of venue categories

Ratings, pricing levels, and seat availability

Chain vs non-chain venues

Geographic patterns across districts

 4. Focused study: feasibility of opening a coffee shop

Market density

Competitor analysis

Pricing patterns

Location opportunities

 5. Presentation and recommendations

Summarize key insights

Formulate conclusions and suggest optimal strategies for investors

## 🎯 Project Goal ##

To conduct a detailed market analysis of Moscow's public catering sector and identify data-driven insights that will help investors choose the best concept and location for opening a new establishment.
