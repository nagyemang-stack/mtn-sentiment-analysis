# MTN Ghana Data Depletion — Public Sentiment Analysis
> Portfolio analysis repository. Findings are based on publicly available materials and clearly identified assumptions; this is not commissioned client work or an official company report.

**Author:** Caleb Agyemang  
**Portfolio:** [calebagyemang.vercel.app](https://calebagyemang.vercel.app)

## Overview

A public-response timeline and sentiment analysis tracking the MTN Ghana data depletion controversy from subscriber complaints through corporate response, regulatory intervention, and resolution. Built with real public data from news coverage, social media, and regulatory guidance documents.

## Data Sources

| Source | Type | Coverage |
|--------|------|----------|
| Graphic Online | News Media | Customer complaints, MTN response |
| MyJoyOnline | News Media | Corporate statements, dashboard launch |
| Citi Business News | Financial | ARPU data, financial context |
| Reddit r/ghana | Social Media | Consumer complaints (200+ threads) |
| NCA Publications | Regulatory | Consumer protection guidance |
| Ministry of Communications | Government | Investigation announcements |
| MTN Annual Reports | Corporate | ARPU, subscriber data |

## Key Findings

- **Negative sentiment dominated early coverage** (60% of events scored negative)
- **MTN CEO's "zero incentive" defense** was widely perceived as dismissive
- **NCA regulatory intervention** was the most impactful turning point
- **Data transparency dashboard launch** (Dec 2025) shifted sentiment positive
- **Total public reach across all events:** 631,000+ impressions

## Technical Stack

- Python 3.11
- Pandas, NumPy
- Matplotlib (custom Editorial Precision styling)
- TextBlob, VADER (sentiment scoring)
- BeautifulSoup, Requests (web scraping)

## How to Run

```bash
pip install -r requirements.txt
python scripts/analyze_mtn_sentiment.py
```

## Outputs

- `output/mtn_sentiment_timeline.png` — Event timeline with sentiment scores
- `output/mtn_media_reach.png` — Media reach by platform type
- `output/mtn_sentiment_distribution.png` — Sentiment pie chart
- `output/mtn_executive_summary.json` — Structured findings

## Methodology

Public event timeline construction from verified news coverage, social media, regulatory filings, and corporate announcements. Sentiment scored on a -1 to +1 scale using a combination of TextBlob polarity and contextual manual coding. All data points are traceable to public sources.

## License

MIT — Feel free to use this analysis framework for your own research.
