# Python Name-Matching Exercise

## Overview
This is a data analysis exercise designed to test your ability to match records across datasets based on name matching. You will work with congressional data to identify and link politicians across different datasets.

## Datasets
You will be working with two types of datasets:

1. **Primary Dataset**: `congress_members_with_parties.csv`
   - Contains information about congress members and their party affiliations
   - This is your reference dataset

2. **Election Datasets**: `congressional_elections_YYYY.csv` (where YYYY ranges from 1992 to 2005)
   - Contains congressional election data for each year
   - Multiple files covering elections from 1992 through 2005
   - **Important**: The `status` column in these datasets is unreliable and should be ignored

## Task Objective
Your goal is to **match as many people from the congress members dataset as possible** with records in the election datasets using **name-based matching only**.

## Requirements

### Core Task
- Match records between `congress_members_with_parties.csv` and the various `congressional_elections_YYYY.csv` files
- Use **only name-based matching** - ignore the status column in election data
- Maximize the number of successful matches from the primary dataset

### Technical Specifications
- Implement your solution in Python
- Handle name variations and potential inconsistencies
- Consider different name formats (e.g., "John Smith" vs "Smith, John")
- Account for nicknames, middle names, and common name variations
- Document your matching strategy and assumptions

## Deliverables

1. **Python Script(s)**: Your name-matching implementation
2. **Results File**: A CSV or similar file showing:
   - Matched records
   - Confidence scores (if applicable)
   - Unmatched records from the primary dataset
3. **Documentation**: 
   - Explanation of your matching algorithm
   - Assumptions made
   - Challenges encountered and how you addressed them
   - Statistics on matching success rates

## Evaluation Criteria

- **Coverage**: How many congress members you successfully matched
- **Accuracy**: Quality of the matches (avoiding false positives)
- **Code Quality**: Clean, well-documented, and efficient code
- **Documentation**: Clear explanation of your approach and methodology

## Getting Started

1. Clone this repository
2. Obtain the datasets (will be provided separately)
3. Explore the data structure and identify potential matching challenges
4. Develop and test your matching algorithm
5. Generate results and document your findings

Good luck!
