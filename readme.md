# Magnate

Magnate is a platform for aggregating and publishing niche newsletters and their supporting websites.

## Architecture

**Administrator**: A website for managing newsletters, sites, and their aggregators.

**Aggregator**: A service for running aggregators and storing their results.

**Site Builder**: A service for building sites and deploying them based on instructions from the administrator.

**Data Store**: Persistence for the newletters, sites, and their metadata.

## News Sources

The original plan was to use the Google News API for sourcing, but that API has been discontinued. See [this article](https://www.quora.com/With-Google-News-API-going-away-what-is-the-best-option-for-company-news-search-feed) for other options.

## Minimum Viable Product

In order to test the viability of Mogul, we need the following:

* A single source of trending topics (ie Twitter)
