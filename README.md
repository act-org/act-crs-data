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
    "id":"2A26EE660F72412EA29765D79C367F0B",
    "language":"English",
    "subject":"Math",
    "gradeLevel":"Grade 1",
    "code":"Math.1.OA.7",
    "shortCode":"1.OA.7",
    "listIdentifier":"7",
    "statement":"Understand the meaning of the equal sign, and determine if equations involving addition and subtraction are true or false.",
    "clarifications":[
      "For example, which of the following equations are true and which are false? 6 = 6, 7 = 8 - 1, 5 + 2 = 2 + 5, 4 + 1 = 5 + 2."
    ],
    "gradeLevels":[
      "01"
    ],
    "jurisdiction":"Common Core State Standards Initiative",
    "jurisdictionAbbreviation":"CC",
    "ASN":{
      "identifier":"http://purl.org/ASN/resources/S114343E",
      "id":"S114343E",
      "parent":"S1143430",
      "indexingStatus":"Yes",
      "authorityStatus":"Original Statement",
      "statementNotation":"1.OA.7",
      "leaf":"true"
    },
    "CCSSI":{
      "GUID":"2A26EE660F72412EA29765D79C367F0B",
      "dotNotation":"Math.1.OA.7",
      "URI":"http://corestandards.org/2010/math/content/1/OA/7",
      "currentURL":"http://www.corestandards.org/the-standards/mathematics/grade-1/operations-and-algebraic-thinking/#1-oa-7"
    }
  }
```


### Notes:

* **Clarifications** TBD

## Progress

Working on:
* Math

