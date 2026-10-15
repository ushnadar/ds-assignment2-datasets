# ds-assignment2-datasets

# CS4048 Assignment 2 — Cleaned Datasets (v1.0)
Date: <date> · Author: Roll No. 23L-0529

## 23L_0529_A2_netflix_cleaned.csv
- Source: Netflix Movies and TV Shows, Kaggle (shivamb): https://www.kaggle.com/datasets/shivamb/netflixshows
- Changes: whitespace stripped and multi-value cells standardised; `date_added` parsed; 3 durations moved from `rating` to `duration`; missing rating/director/cast/country filled with "Unknown" (with `*_known` flags); `rating_clean` and `rating_group` added; `duration` split into `duration_min` and `n_seasons`; derived `year_added`, `month_added`, `added_gap`, `n_countries`, `n_genres`, `n_cast`, `primary_country`, `primary_genre`; outliers kept and flagged. No rows removed (8,807 rows × 31 columns).

## 23L_0529_A2_supermarket_cleaned.csv
- Source: `supermarket_Sales.csv` provided by the instructor (used as supplied).
- Changes: no missing values or duplicates found; `Date`/`Time` parsed; derived `datetime`, `month`, `day`, `weekday`, `weekday_num`, `is_weekend`, `hour`, `daypart`. Original columns unchanged. No rows removed (1,000 rows × 25 columns).

Original datasets belong to their authors; please respect their licences.
