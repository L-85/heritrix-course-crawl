# Heritrix Course Crawling Experiment

## Project Overview

This repository documents a small-scale web crawling experiment for an undergraduate Information Retrieval course.

The experiment uses Heritrix 3.18.0 to collect publicly accessible university news and announcements from the official website of Central China Normal University (CCNU).

## Crawling Purpose

The collected pages are intended for academic experimentation, including:

- Web page preprocessing and content extraction
- Full-text indexing with Apache Lucene
- Keyword and phrase search
- Search result evaluation and analysis

## Crawling Scope

- Target website: https://www.ccnu.edu.cn/
- Content focus: University news and public announcements
- Maximum crawl size: 50 pages initially
- Maximum crawl depth: 3
- Crawl delay: At least 2 seconds between requests
- Robots policy: Obey

Crawling will be restricted to the authorized target scope and will respect applicable website access rules.

## Data Usage

Collected web pages are used only for coursework and academic demonstration. The experiment does not intend to overload the target website or redistribute copyrighted content.

## Contact and Feedback

If you have questions or concerns regarding this experiment's crawling activity, please open an issue in this repository.

Feedback and requests concerning crawling scope or access can be submitted through GitHub Issues.

GitHub Issues:
https://github.com/L-85/heritrix-course-crawl/issues

## Tools

- Heritrix 3.18.0
- Apache Lucene
- Java
- Maven

This repository is maintained for educational purposes.
