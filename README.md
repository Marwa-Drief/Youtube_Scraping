

# 📊 YouTube Data Scraping

## Description
This script scrapes YouTube channel and video data using the YouTube Data API v3. It collects statistics like subscribers, views, and video details (title, views, likes, duration) and stores them in CSV files. Additionally, the script generates visualizations to analyze channel performance.

## Features
- Scrape channel statistics (subscribers, views, total videos).
- Scrape video details (title, views, likes, duration).
- Save results in CSV format.
- Generate charts: subscribers, views, total videos, and video duration vs views.

## Requirements
- Python 3.x
- Libraries: `google-api-python-client`, `pandas`, `isodate`, `matplotlib`, `seaborn`

```bash
pip install google-api-python-client pandas isodate matplotlib seaborn
```

## Setup
1. Replace `api_key` with your YouTube Data API key.
2. Add channel IDs to the `channel_ids` list.
3. Run the script to fetch and save data.

## Output
- **CSV Files**: `channel_comparison.csv`, `[channel_name]_videos.csv`
- **Visualizations**: Charts showing subscribers, views, video count, and video performance.

