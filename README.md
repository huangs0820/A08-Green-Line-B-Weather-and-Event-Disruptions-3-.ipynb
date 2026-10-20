# A08-Green-Line-B-Weather-and-Event-Disruptions-3-.ipynb

1. Overview

This project measures how precipitation, temperature and public events affect travel time and reliability on the MBTA Green Line B Branch. It compares September 2025 with December 2025. The B Branch runs above ground from Boston College to Kenmore and underground from Kenmore to Government Center, so we can also compare the two sections.

2. Data

- MBTA Light Rail Travel Times: MBTA Open Data Portal
- NOAA Local Climatological Data: Boston Logan, hourly (NOAA NCEI)
- Boston Special Event Applications: Analyze Boston

The three datasets are merged by date and hour into a single dataset of 539,798 rows.

3. Key Findings

- Above-ground segments drive unreliability. Their travel times vary nearly three times as much as underground segments, even on days with no rain and no events.
- Rush hour is slower but more predictable. It adds about 1.5 minutes to the median trip, but off-peak trips vary more.
- September is slower than December. The back-to-school period adds several minutes to a typical trip.
- Rain alone has little effect on travel time.
- Events have a small effect. Event days had more extreme delays, mostly at Government Center and near BU.
- Weather and events together produced the longest average trips, though the differences are small.

4. Recommendations

- MBTA: add transit signal priority on Commonwealth Avenue, increase service in September, and use weather forecasts and event permits to plan staffing.
- Riders: leave extra time for off-peak trips and in September.

5. AI Disclosure

The team used Claude, Gemini and ChatGPT for planning, coding, visualization and writing support, and reviewed all work for accuracy. See Section 12 of the notebook for the full statement.
