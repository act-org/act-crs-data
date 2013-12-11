# ACT College Readiness Standards (CRS) JSON Repository
JSON representations of the ACT College Readiness Standards

## Why?

ACT College Readiness Standards are relevant to 8-12 education. In order for K12 EdTech companies to use these standards in their apps, they need machine readable formats. 

## Guiding Principles on the Schema

* **Each subject should be it's own document**
We will separate the subjects into separate files.

## Example

Here's a sample:

```json
  {
    "URI": "http://www.act.org/standard/planact/math/index.html", 
    "id": "act.crs.math", 
    "jurisdiction": "ACT, Inc.", 
    "jurisdictionAbbreviation": "ACT", 
    "language": "English", 
    "strands": [
        {
            "scoreRanges": [
                {
                    "range": "13-15", 
                    "standards": [
                        {
                            "statement": "Perform one-operation computation with whole numbers and decimals"
                        }, 
                        {
                            "statement": "Solve problems in one or two steps using whole numbers"
                        }, 
                        {
                            "statement": "Perform common conversions (e.g., inches to feet or hours to minutes)"
                        }
                    ]
                }, 
                {
                    "range": "16-19", 
                    "standards": [
                        {
                            "statement": "Solve routine one-step arithmetic problems (using whole numbers, fractions, and decimals) such as single-step percent"
                        }, 
                        {
                            "statement": "Solve some routine two-step arithmetic problems"
                        }
                    ]
                }, 
                {
                    "range": "20-23", 
                    "standards": [
                        {
                            "statement": "Solve routine two-step or three-step arithmetic problems involving concepts such as rate and proportion, tax added, percentage off, and computing with a given average"
                        }
                    ]
                }, 
                {
                    "range": "24-27", 
                    "standards": [
                        {
                            "statement": "Solve multistep arithmetic problems that involve planning or converting units of measure (e.g., feet per second to miles per hour)"
                        }
                    ]
                }, 
                {
                    "application": "PLAN,ACT", 
                    "range": "28-32", 
                    "standards": [
                        {
                            "statement": "Solve word problems containing several rates, proportions, or percentages"
                        }
                    ]
                }, 
                {
                    "application": "ACT", 
                    "range": "33-36", 
                    "standards": [
                        {
                            "statement": "Solve complex arithmetic problems involving percent of increase or decrease and problems requiring integration of several concepts from pre-algebra and/or pre-geometry (e.g., comparing percentages or averages, using several ratios, and finding ratios in geometry settings)"
                        }
                    ]
                }
            ], 
            "title": "Basic Operations and Applications"
        }
    ], 
    "subject": "Mathematics"
}

```


### Notes:

* **Clarifications** TBD

## Progress

Working on:
* Math
* Science

