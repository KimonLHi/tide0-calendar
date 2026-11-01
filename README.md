# Santa Monica Beach running forecast

## Daily forecast dashboard

Open the latest interactive forecast in a browser: [https://kimonlhi.github.io/tide0-calendar/](https://kimonlhi.github.io/tide0-calendar/). It is refreshed by the daily forecast workflow. The dashboard includes the hourly favorability charts, tide/weather context, advisory status and 30-day calendar.

## Favorable-tide calendar

Subscribe using this feed URL:

- HTTPS: https://raw.githubusercontent.com/KimonLHi/tide0-calendar/main/calendar.ics
- Webcal: webcal://raw.githubusercontent.com/KimonLHi/tide0-calendar/main/calendar.ics

The feed is regenerated daily and covers a rolling 90 days. The first 16 days can use available marine-model data. Later events are explicitly titled **Tide-led outlook (provisional)**: they use NOAA tide predictions only because wave and weather forecasts are not available that far ahead. Those longer-range times can move or disappear as the horizon approaches.

Events are heuristic estimates at Santa Monica Beach near the Pier, with thresholds calibrated to target about two qualifying windows per week; actual frequency varies by conditions. Scores are not probabilities, beach-width measurements, or safety/water-quality assessments. Check current local conditions and official advisories. This public repository contains generated forecast output only, not the private forecast source or configuration.
