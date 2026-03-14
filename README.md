# TrendScope

TrendScope is a simple project for collecting and analyzing social trend data.

The system gathers data such as posts, hashtags, and engagement metrics and stores them as structured datasets.

Shelby is used as the data layer to store and index this data so it can be searched and analyzed.

## Data Example

post_id  
text  
hashtags  
likes  
timestamp  

## Goal

Build a simple pipeline for collecting, storing, and querying trend data.

## Architecture

Crawler → Data Processing → Shelby Storage → Query Layer

- Crawler collects social posts and hashtags
- Data processing extracts keywords and metrics
- Shelby stores structured datasets
- Query layer enables searching and trend analysis
