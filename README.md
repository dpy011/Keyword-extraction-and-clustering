# Keyword-extraction-and-clustering
The repository contains Jupyter Notebook of codes used to extract keywords using KeyBERT and clustering of keywords using Fast clustering algorithm.

Unfortunatley, the data used to extract keywords cannot be open sourced due to data privacy. However the sample json file would look like following:
```
{
  "userInfo": {
    "institute": true,
    "member": false,
    "individual": true,
    "guest": false,
    "subscribedContent": true,
    "fileCabinetContent": false,
    "fileCabinetUser": false,
    "institutionalFileCabinetUser": false,
    "showPatentCitations": true,
    "showGet802Link": false,
    "showOpenUrlLink": false,
    "tracked": true,
    "desktop": true,
    "delegatedAdmin": false,
    "isInstitutionDashboardEnabled": false,
    "isInstitutionProfileEnabled": false,
    "isRoamingEnabled": false,
    "isDelegatedAdmin": false,
    "isMdl": true,
    "isCwg": false,
    "isIel": false
  },
  "authors": [
    {
      "name": "John Doe",
      "affiliation": [
        "University of XYZ"
      ],
      "firstName": "John",
      "lastName": "Doe"
    }
  ],
  "isbn": [
    {
      "format": "Electronic ISBN",
      "value": "123-456-7890",
      "isbnType": ""
    },
    {
      "format": "Print ISBN",
      "value": "987-654-3210",
      "isbnType": ""
    }
  ],
  "articleNumber": "123456",
  "dbTime": "100 ms",
  "metrics": {
    "citationCountPaper": 5,
    "citationCountPatent": 2,
    "totalDownloads": 1000
  },
  "purchaseOptions": {
    "showOtherFormatPricingTab": true,
    "showPdfFormatPricingTab": false,
    "pdfPricingInfoAvailable": false,
    "otherPricingInfoAvailable": true,
    "mandatoryBundle": true,
    "optionalBundle": false,
    "pdfPricingInfo": [
      {
        "memberPrice": "$10.00",
        "nonMemberPrice": "$20.00",
        "partNumber": "123456",
        "type": "PDF"
      }
    ]
  },
  "getProgramTermsAccepted": true,
  "sections": {
    "abstract": true,
    "authors": true,
    "figures": true,
    "multimedia": false,
    "references": true,
    "citedby": false,
    "keywords": true,
    "definitions": false,
    "algorithm": false,
    "dataset": false,
    "cadmore": false,
    "footnotes": false,
    "disclaimer": false,
    "relatedContent": false,
    "metrics": true
  },
  "keywords": [
    {
      "type": "IEEE Keywords",
      "kwd": [
        "Dummy keyword 1",
        "Dummy keyword 2",
        "Dummy keyword 3"
      ]
    },
    {
      "type": "INSPEC: Controlled Indexing",
      "kwd": [
        "Dummy keyword 4",
        "Dummy keyword 5",
        "Dummy keyword 6"
      ]
    },
    {
      "type": "INSPEC: Non-Controlled Indexing",
      "kwd": [
        "Dummy keyword 7",
        "Dummy keyword 8",
        "Dummy keyword 9"
      ]
    }
  ],
  "articleCopyRight": "1",
  "pubLink": "/dummy/link",
  "abstract": "This is a dummy abstract.",
  "doiLink": "https://doi
```
