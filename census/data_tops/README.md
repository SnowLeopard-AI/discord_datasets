[![Discord](https://img.shields.io/discord/1379929746875617413?logo=discord&logoColor=white)](https://discord.gg/WGAyr8NpEX)

# Census Dataset Tops

There are 2 tables in the set. In the examples each table has 4 records:

    - 2 for county: geo_id starts with 050
    - 2 for county division: geo_id starts with 060

These are the first 100 rows of each dataset from the IMDb non-commercial-datasets.

More information, and the raw data, can be found at [imdb.com/non-commercial-datasets/](https://developer.imdb.com/non-commercial-datasets/).


## Census Dataset Schema

### census_demographics_by_county_division_2023
**Unique identifiers**
* **geo_id** (string) - PRIMARY KEY Geography
* **geographic_area_name** (string) - unique Geographic Area Name

**Total Population - Sex and Age**
* **total_population** (float) - Estimate!!SEX AND AGE!!Total population
* **male_population** (float) - Male
* **female_population** (float) - Female
* **sex_ratio_males_per_100_females** (float) - Sex ratio (males per 100 females)

**Age Groups**
* **age_under_5** (float) - Under 5 years
* **age_5_to_9** (float) - 5 to 9 years
* **age_10_to_14** (float) - 10 to 14 years
* **age_15_to_19** (float) - 15 to 19 years
* **age_20_to_24** (float) - 20 to 24 years
* **age_25_to_34** (float) - 25 to 34 years
* **age_35_to_44** (float) - 35 to 44 years
* **age_45_to_54** (float) - 45 to 54 years
* **age_55_to_59** (float) - 55 to 59 years
* **age_60_to_64** (float) - 60 to 64 years
* **age_65_to_74** (float) - 65 to 74 years
* **age_75_to_84** (float) - 75 to 84 years
* **age_85_and_over** (float) - 85 years and over
* **median_age DECIMAL(4,1), -- Median age** (years)

**Age Categories**
* **age_under_18** (float) - Under 18 years
* **age_16_and_over** (float) - 16 years and over
* **age_18_and_over** (float) - 18 years and over
* **age_21_and_over** (float) - 21 years and over
* **age_62_and_over** (float) - 62 years and over
* **age_65_and_over** (float) - 65 years and over

**Adult Population by Sex**
* **adults_18_and_over_male** (float) - 18 years and over!!Male
* **adults_18_and_over_female** (float) - 18 years and over!!Female
* **adults_18_and_over_sex_ratio** (float) - 18 years and over!!Sex ratio (males per 100 females)

**Senior Population by Sex**
* **seniors_65_and_over_male** (float) - 65 years and over!!Male
* **seniors_65_and_over_female** (float) - 65 years and over!!Female
* **seniors_65_and_over_sex_ratio** (float) - 65 years and over!!Sex ratio (males per 100 females)


### census_language_by_county_division_2023
**Unique identifiers**
* **geo_id** (string) - PRIMARY KEY Geography
* **geographic_area_name** (string) - unique Geographic Area Name

* **total_estimate** (float) - Estimate Total
* **total_english_only_estimate** (float) - Speak only English
* **total_spanish_estimate** (float) - Spanish
* **total_spanish_EP_estimate** (float) - Spanish Speak English very well
* **total_spanish_ELP_estimate** (float) - Spanish Speak English less than very well
* **total_french_haitian_or_cajun_estimate** (float) - French, Haitian, or Cajun
* **total_french_haitian_or_cajun_EP_estimate** (float) - French, Haitian, or Cajun Speak English very well
* **total_french_haitian_or_cajun_ELP_estimate** (float) - French, Haitian, or Cajun Speak English less than very well
* **total_german_or_other_west_germanic_languages_estimate** (float) - German or other West Germanic languages
* **total_german_or_other_west_germanic_languages_EP_estimate** (float) - German or other West Germanic languages Speak English very well
* **total_german_or_other_west_germanic_languages_ELP_estimate** (float) - German or other West Germanic languages Speak English less than very well
* **total_russian_polish_or_other_slavic_languages_estimate** (float) - Russian, Polish, or other Slavic languages
* **total_russian_polish_or_other_slavic_languages_EP_estimate** (float) - Russian, Polish, or other Slavic languages Speak English very well
* **total_russian_polish_or_other_slavic_languages_ELP_estimate** (float) - Russian, Polish, or other Slavic languages Speak English less than very well
* **total_other_indo_european_languages_estimate** (float) - Other Indo-European languages
* **total_other_indo_european_languages_EP_estimate** (float) - Other Indo-European languages Speak English very well
* **total_other_indo_european_languages_ELP_estimate** (float) - Other Indo-European languages Speak English less than very well
* **total_korean_estimate** (float) - Korean
* **total_korean_EP_estimate** (float) - Korean Speak English very well
* **total_korean_ELP_estimate** (float) - Korean Speak English less than very well
* **total_chinese_incl_mandarin_cantonese_estimate** (float) - Chinese (incl. Mandarin, Cantonese)
* **total_chinese_incl_mandarin_cantonese_EP_estimate** (float) - Chinese (incl. Mandarin, Cantonese) Speak English very well
* **total_chinese_incl_mandarin_cantonese_ELP_estimate** (float) - Chinese (incl. Mandarin, Cantonese) Speak English less than very well
* **total_vietnamese_estimate** (float) - Vietnamese
* **total_vietnamese_EP_estimate** (float) - Vietnamese Speak English very well
* **total_vietnamese_ELP_estimate** (float) - Vietnamese Speak English less than very well
* **total_tagalog_incl_filipino_estimate** (float) - Tagalog (incl. Filipino)
* **total_tagalog_incl_filipino_EP_estimate** (float) - Tagalog (incl. Filipino) Speak English very well
* **total_tagalog_incl_filipino_ELP_estimate** (float) - Tagalog (incl. Filipino) Speak English less than very well
* **total_other_asian_and_pacific_island_languages_estimate** (float) - Other Asian and Pacific Island languages
* **total_other_asian_and_pacific_island_languages_EP_estimate** (float) - Other Asian and Pacific Island languages Speak English very well
* **total_other_asian_and_pacific_island_languages_ELP_estimate** (float) - Other Asian and Pacific Island languages Speak English less than very well
* **total_arabic_estimate** (float) - Arabic
* **total_arabic_EP_estimate** (float) - Arabic Speak English very well
* **total_arabic_ELP_estimate** (float) - Arabic Speak English less than very well
* **total_other_and_unspecified_languages_estimate** (float) - Other and unspecified languages
* **total_other_and_unspecified_languages_EP_estimate** (float) - Other and unspecified languages Speak English very well
* **total_other_and_unspecified_languages_ELP_estimate** (float) - Other and unspecified languages Speak English less than very well
