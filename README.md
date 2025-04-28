# Instagram Hashtag Analyzer

A Python-based tool that identifies trending hashtags on Instagram to maximize post reach and engagement.

## 🔍 Problem Solved

Content creators and marketers struggle to identify which hashtags will give their posts the most visibility. This tool analyzes hashtag performance data to recommend optimal tags based on engagement rates, competition levels, and relevance to your niche.

## ✨ Features

- Analyzes hashtag popularity trends over customizable time periods
- Categorizes hashtags by engagement rate, competition level, and growth trajectory
- Recommends optimal hashtag combinations based on your account size and niche
- Exports data to CSV for further analysis
- Scheduled scans to track hashtag performance changes over time

## 🛠️ Technologies Used

- Python 3.9+
- Instagram Graph API
- Pandas for data analysis
- Matplotlib for trend visualization
- Schedule library for automated scanning

## 📋 Usage

```bash
# Install dependencies
pip install -r requirements.txt

# Configure your API credentials
cp config.example.json config.json
# Edit config.json with your API keys

# Run the analyzer
python analyze_hashtags.py --niche "fitness" --count 50
```
## 📊 Sample Output
The tool produces a ranked list of hashtags with metrics including:

Average engagement rate  
Competition score (1-10)  
Growth trend (declining, stable, growing, exploding)  
Best posting times  
Related hashtag  
## 📝 License
MIT
