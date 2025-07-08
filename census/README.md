[![Discord](https://img.shields.io/discord/1379929746875617413?logo=discord&logoColor=white)](https://discord.gg/WGAyr8NpEX)

# Census Dataset

U.S. Census Data by County Division (2023)
This dataset contains detailed demographic and language information for Census County Divisions (CCDs) across the United States from 2023. CCDs are statistical areas created by the Census Bureau to provide consistent geographic divisions for data analysis in areas without established local government boundaries.
It was downloaded via [US Census Bureau page](https://data.census.gov/table?q=2023%20C16001%20Detailed%20Language%20Spoken%20at%20Home%20for%20the%20Population%205%20Years%20and%20Over%20Counties)

## Dataset Overview

The Census dataset includes 2 tables with the following information:

The Census Bureau produces population estimates for a range of geographic areas, including the nation, states, the District of Columbia, Puerto Rico, counties and equivalents (such as parishes, boroughs, and municipios), incorporated places, minor civil divisions, consolidated cities, census regions and divisions, and core-based statistical areas like metropolitan and micropolitan areas. Each of these geographic area types is defined by specific legal or statistical criteria, with boundaries and designations varying by state and territory to ensure accurate and consistent population data collection and reporting.
This dataset has information on county and county division levels (050, 060)

- **Unique Identifier in both tables: Geographic Information:**
  - **geo_id**: see [geo_id at census.gov](https://www.census.gov/programs-surveys/geography/guidance/geo-identifiers.html): state, county, and local area names with geographic boundary codes for mapping
      
    The “GEO_ID” field contains 14-digit codes that identify the summary level of data, the geographic component of the data and FIPS codes that uniquely identify the data.
    
    For example, the 14-digit “GEO_ID” for geographic_area_name="Harris County, TX" is “0500000US48201” where
      - “050” represents the summary level of the data - county
      - “0000” represents the 2-digit geographic variant and the 2-digit geographic component
      - “US” represents the United States
      - “48” represents the state of Texas (state fips)
      - “201” represents Harris County (county fips)

  - **geographic_area_name**: corresponds with geo_id - see above and [terms&definitions](https://www.census.gov/programs-surveys/popest/guidance-geographies/terms-and-definitions.html)
- **Demographics Data:** 
  - Population counts by age groups (under 5, 5-9, 10-14, etc.)
  - Gender ratios
  - Median age statistics
  - Population counts for adults (18+), seniors (62+, 65+), and minors(under 18)
- **Language Data:** 
  - Primary languages spoken at home
  - English proficiency levels for non-English speakers
  - Detailed breakdown by language families (Spanish, Chinese, Korean, Arabic, etc.)

## Getting Started

1. Join [Snow Leopard's Discord server](https://discord.gg/WGAyr8NpEX)
2. Enter the `census` channel to ask snowy about the census datasets
3. Ask your demographic and language usage related questions!

🤔 Not sure what to ask? Here are a few sample questions.

### Population Analysis:
```
@snowy, What's the age distribution in New York County, New York?
```
```
@snowy, Which communities in California have the highest senior populations?
```
```
@snowy, Where are the youngest/oldest communities in Texas?
```
```
@snowy, What's the median age in [city/state]?
```

### Language Diversity:
```
@snowy, How diverse is [location] ethnically?
```
```
@snowy, What languages are most commonly spoken in Bern township, Athens County, Ohio?
```
```
@snowy, which city has most french speaking county in Texas?
```
```
@snowy, Which communities have the highest non-English speaking populations?
```
```
@snowy, How well do non-English speakers in Clark County, Kentucky speak English?
```
```
@snowy, Where are the most linguistically diverse communities?
```

### Community Planning:
```
@snowy, Which areas might need multilingual services?
```
```
@snowy, Where should age-specific services be prioritized?
```
```
@snowy, What communities might benefit from specific cultural outreach programs?
```
