# Magnate

Magnate is a platform for aggregating and publishing niche newsletters and their supporting websites.

## Architecture

**Administrator**: A website for managing newsletters, sites, and their aggregators.

**Aggregator**: A service for running aggregators and storing their results.

**Site Builder**: A service for building sites and deploying them based on instructions from the administrator.

**Data Store**: Persistence for the newletters, sites, and their metadata.
