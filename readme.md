# Finnish IT Job Market Analysis

An exloratory analysis of Finnish IT job posting using Python, Pandas and data visualization

## 1. Overview

- Project purpose
- What the analysis examines
- Data size: 21 job postings
- Data source: LinkedIn
- Collection period

## 2. Research question:

1. What IT job categories are represented in the collected sample?
2. Which technical skills appear most frequently?
3. How does skill demand differ across job categories?
4. What experience levels are requested?
5. What work models are offered?

## 3. Dataset

### Data fields

Main columns:

- Job ID
- Job title
- Company
- Location
- Posted date
- Collected date
- Experience requirement
- Skills
- Work model

### Data preparation

- Data cleaning
- Date conversion
- Experience extraction
- Skill cleaning and transformation
- Work model classification
- Job category classification

## 4. Analysis

02_skill_analysis.ipynb

- Overall skill frequency
- Top 10 skills
- Skill demand by job category
- Cross-category skills
- Category-specific skills

03_market_analysis.ipynb

- Job posting distribution by category
- Experience requirement
- Work model distribution

## 5. Key Findings

### Job Categories

Software Development represented the largest share of the collected sample, with 11 of 21 postings.

### Skills

SQL and Python were the most frequently mentioned skills in the collected sample.

### Experience

Among postings with a specified numerical minimum experience requirement, 3 years was the most common requirement.

### Work Model

Hybrid was the dominant work model in the collected sample.

These findings describe the collected sample and should not be interpreted as representative of the entire Finnish IT job market.

## 6. Visualizations

Charts from the notebooks:

- Top 10 Skills

- Top Skills by Job Category

- Job Postings by Category

- Minimum Experience Requirements

- Work Model Distribution

## 7. Limitations

- Small sample size: 21 postings

- Uneven number of postings across categories

- Data collected from a limited source

- Skill names largely preserved as they appeared in job postings

- Some skill entries contain grouped alternatives

- Results are exploratory rather than representative

## 10. How to Run

Basic instructions for:

- Clone the repository

- Create a virtual environment

- Install dependencies

- Open and the notebooks
