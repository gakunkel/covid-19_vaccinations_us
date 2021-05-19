Context
This dataset provides State-by-state data on United States COVID-19 vaccinations between 20 December of 2020 and 8 May of 2021. Data is taken daily by the United States Centers for Disease Control and Prevention

Columns
us_state_vaccinations File
- location: State name.
- date: date of the case.
- total_vaccinations: total number of doses administered. This is counted as a single dose, and may not equal the total number of people vaccinated, depending on the specific dose regime (e.g. people receive multiple doses). If a person receives one dose of the vaccine, this metric goes up by 1. If they receive a second dose, it goes up by 1 again.
- total_vaccinations_per_hundred: total_vaccinations per 100 people in the total population of the state.
- daily_vaccinations_raw: daily change in the total number of doses administered. It is only calculated for consecutive days. This is a raw measure provided for data checks and transparency, but we strongly recommend that any analysis on daily vaccination rates be conducted using daily_vaccinations instead.
- daily_vaccinations: new doses administered per day (7-day smoothed). For countries that don't report data on a daily basis, we assume that doses changed equally on a daily basis over any periods in which no data was reported. This produces a complete series of daily figures, which is then averaged over a rolling 7-day window. An example of how we perform this calculation can be found here.
- daily_vaccinations_per_million: daily_vaccinations per 1,000,000 people in the total population of the state.
- people_vaccinated: total number of people who received at least one vaccine dose. If a person receives the first dose of a 2-dose vaccine, this metric goes up by 1. If they receive the second dose, the metric stays the same.
- people_vaccinated_per_hundred: people_vaccinated per 100 people in the total population of the state.
- people_fully_vaccinated: total number of people who received all doses prescribed by the vaccination protocol. If a person receives the first dose of a 2-dose vaccine, this metric stays the same. If they receive the second dose, the metric goes up by 1.
- people_fully_vaccinated_per_hundred: people_fully_vaccinated per 100 people in the total population of the state.
- total_distributed: cumulative counts of COVID-19 vaccine doses recorded as shipped in CDC's Vaccine Tracking System.
- total_distributed_per_hundred: cumulative counts of COVID-19 vaccine doses recorded as shipped in CDC's Vaccine Tracking System per 100 people in the total population of the state.
- share_doses_used: share of vaccination doses administered among those recorded as shipped in CDC's Vaccine Tracking System.
Total COVID-19 Vaccinations in the United States File
- State/Territory/Federal Entity
- Total Doses Administered by State where Administered
- Doses Administered per 100k by State where Administered
- 18+ Doses Administered by State where Administered
- 18+ Doses Administered per 100K by State where Administered
Data as of: May 8, 2021
