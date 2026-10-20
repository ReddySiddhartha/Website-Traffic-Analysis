# Website Traffic Analysis

## Project Overview
This project analyses website traffic event data using Python, Pandas, and Matplotlib. The analysis explores event distribution, daily traffic patterns, geographic activity, and popular music links and tracks.

## Dataset
- **Original records:** 226,278
- **Columns:** 9
- **Date range:** August 19–25, 2021
- **Unique link IDs after cleaning:** 3,839
- **Exact duplicate rows removed:** 103,711
- **Records after deduplication:** 122,567

## Key Findings
- Pageviews: 73,360 (59.85%)
- Clicks: 32,499 (26.52%)
- Previews: 16,708 (13.63%)
- Highest recorded daily activity: August 19, 2021, with 21,156 events
- Top country by recorded events: United States, with 28,664
- Second-highest country: India, with 18,689
- Top artist-track combination: Tesher — “Jalebi Baby,” with 8,288 events

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib

## Recommendations
1. Improve call-to-action visibility and mobile usability.
2. Test promoting popular music links.
3. Test localized recommendations for major markets.
4. Simplify the next step after music previews.
5. Add session-level analytics to measure genuine user journeys and conversions.

## Limitations
The dataset does not contain user IDs, session IDs, precise event timestamps, or page URLs. Therefore, unique users, sessions, bounce rate, average session duration, and entry/exit pages cannot be reliably calculated.

The analysis removes exact duplicate rows. Some identical records may represent legitimate repeated events, so the cleaned totals should be interpreted cautiously.

## Project Files
- `Website_Traffic_Analysis.ipynb` — Analysis notebook
- `Website_Traffic_Analysis_Code_and_Report_BW.pdf` — Analysis report

