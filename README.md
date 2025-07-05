# WeatherArchives

**WeatherArchives** is a weather data visualization website focused on the Central England Temperature (CET) record. It provides interactive, modern, and user-friendly tools to explore over 250 years of temperature data, including daily extremes, monthly averages, seasonal patterns, yearly trends, and year-to-year comparisons.

## Features
- **Daily Extremes:** Visualize the warmest and coldest temperatures ever recorded for each day of the year. Highlight records for any selected year.
- **Monthly Averages:** Explore monthly temperature trends, filter by year range, and highlight extreme years.
- **Seasonal Patterns:** Analyze how spring, summer, autumn, and winter temperatures have changed over time.
- **Yearly Trends:** See long-term annual temperature trends and climate change signals.
- **Compare Years:** Compare annual, monthly, or seasonal temperature patterns across multiple years, with interactive charts and statistics.
- **Consistent, modern UI:** Responsive cards, info sections, and navigation for a seamless experience.
- **Export:** Download high-resolution images of all charts.

## Data Sources
- **Central England Temperature (CET):**
  - Source: [Met Office Hadley Centre](https://www.metoffice.gov.uk/hadobs/hadcet/)
  - Coverage: 1772 to present
  - Resolution: Daily mean, maximum, and minimum temperatures
  - Quality: Quality-controlled and homogenized dataset

## Setup & Usage
1. Clone or download this repository.
2. Place the project files in your web server directory or open the HTML files directly in your browser.
3. No build step or backend required—everything runs client-side.
4. For best experience, use a modern desktop browser. (Mobile support coming soon!)

## File Structure
- `index.html` — Home/landing page
- `temperature.html` — Temperature analysis overview
- `cet_mean_daily_extremes.html` — Daily extremes visualization
- `cet_monthly_averages.html` — Monthly averages visualization
- `cet_seasonal_patterns.html` — Seasonal patterns visualization
- `cet_yearly_trends.html` — Yearly trends visualization
- `cet_compare_years.html` — Compare years tool
- `about.html` — Data sources, methodology, and contact
- `style.css` — Main stylesheet
- `logo.svg` — Project logo
- `MeanTempCET.csv`, `MaxTempCET.csv` — CET data files

## Credits & Contact
- Data from the UK Met Office Hadley Centre.
- For questions, suggestions, or collaboration, email: pr.141.59.141@gmail.com

---

*WeatherArchives is best viewed on desktop. Mobile support and additional features are planned for future releases!*

## Changelog

### v1.2 (Current)
- Bugfixes:
  - Fixed error in email in "About"
  - Fixed error where Year Comparison fails when a temperature value is zero.
- Tidied up the x-axis Year Comparison graph to split into months rather than weeks.
- Changed from American date format (2/13) to British date format (13 Feb).

### v1.1
- Added printable styles for all visualization pages
- Added a changelog page
- Updated the logo on the 404 and "Coming Soon" pages

### v1.0 – Initial Release
- Temperature Analysis module with:
  - Daily Extremes
  - Monthly Averages
  - Seasonal Patterns
  - Annual Trends
  - Year Comparison
- Index and overview pages
- About page with data sources and methodology
- 404 Not Found page
- Coming Soon placeholders for Precipitation, Sunshine, and Fun & Learning
- Interactive charts with filtering and export
- Responsive design and consistent branding

_Future updates will be listed here as new versions are released._ 