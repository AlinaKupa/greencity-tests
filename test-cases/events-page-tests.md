# Test Cases
## ID-1
## Summary:
Change the language of the page to English
## Priority:
Medium
## Preconditions
- Page "Events" is opened
- "Uk" language is selected in dropdown list
## Test steps:

**Step** |             **Action**           | **Data** | **Expected result**
1    | Click on language selector   |   -  | Language options in drop down list are displayed
2    | Select "En" in dropdown list |   -  | "En" option is seleted in dropdown list
3    | Check page content           |   -  | Page content is dispalyed in English

## ID-2
## Summary:
Search the event by key words
## Priority:
High
## Preconditions
- Page "Events" is opened
## Test steps:

Step |                   Action                  |        Data       | Expected result
1    | Click on "Search" field                   |         -         | "Search" field is active for input
2    | Input a valid key words in "Search" field | "Eco Meetup 2026" | - 
3    | Check given results                       |          -        | Events that contain key words are displayed

## ID-3
## Summary:
Filter events by "Event time" criteria 
## Priority:
High
## Preconditions
- Page "Events" is opened
## Test steps:

Step |                   Action                  | Data | Expected result
1    | Click on "Event time" selector            |  -   | Options in dropdown list are displayed
2    | Click on "Upcoming" option                |  -   | "Upcoming" option is selected
3    | Check given results                       |  -   | Records with "Event time" later than current time are displayed
