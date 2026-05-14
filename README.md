# ishikawa-kanko-stat

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A web application for searching and visualizing open data from the Ishikawa Prefecture Tourism Survey. This project is a fork of the [Fukui Prefecture version](https://code4fukui.github.io/fukui-kanko-stat/comment-search.html).

## Demo

- [Ishikawa Tourism Open Data Comment Search](https://code4fukui.github.io/ishikawa-kanko-stat/comment-search.html)

## Features

The comment search application allows users to:

- **Search by Keyword:** Find specific terms within survey comments.
- **Filter Results:** Narrow down comments by various criteria:
  - Area and facility
  - Visitor's home prefecture (e.g., show only non-residents)
  - Sentiment (e.g., show only "厳しい意見" - negative feedback)
  - Age group
- **Visualize Satisfaction:** View an interactive pie chart summarizing the satisfaction levels for the filtered results.
- **View Details:** See metadata for each comment, including response date, satisfaction score, NPS, and visitor demographics.

## Data Source

This application utilizes open data from the Ishikawa Prefecture Tourism Data Analysis Platform "Milli".

- **Source:** [Milli - QR Survey Data](https://sites.google.com/view/milli-ishikawa-pref/qr%E3%82%A2%E3%83%B3%E3%82%B1%E3%83%BC%E3%83%88%E3%83%87%E3%83%BC%E3%82%BF)
- **Processed Data on GitHub:** [code4fukui/ishikawa-kanko-survey](https://github.com/code4fukui/ishikawa-kanko-survey)

## License

MIT License — see [LICENSE](LICENSE).