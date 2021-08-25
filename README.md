### Hi there 👋

<!--
**guilhermeSolski/guilhermeSolski** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<details>
    <summary>
        <h3>Json</h3>
    </summary>

    ```json
    {
               "metadata": {
                 "eventId": "string",
                 "eventType": "string",
                 "timestamp": "string"
               },
               "data": {
                 "id": "string",
                 "identity": {
                   "stripesInstance": "string",
                   "stripesNumber": "string",
                   "externalIds": {
                     "salesforceLubesId": "string",
                     "salesforceId": "string"
                   },
                   "internalName": "string",
                   "legalName": "string",
                   "tradingName": "string",
                   "accountGroup": "string"
                 },
                 "status": "string",
                 "blocking": {
                   "order": "string",
                   "delivery": "string"
                 },
                 "contact": {
                   "primaryLanguage": {
                     "name": "string",
                     "ISOcode": "string"
                   },
                   "telephones": [],
                   "emails": [
                     {
                       "address": "string",
                       "default": "boolean"
                     }
                   ]
                 },
                 "address": {
                   "streetAddress": "string",
                   "district": "string",
                   "city": "string",
                   "postalCode": "string",
                   "region": {
                     "isoCode": "string",
                     "name": "string"
                   },
                   "country": {
                     "isoCode": "string",
                     "name": "string"
                   },
                   "timeZone": {
                     "offset": "number",
                     "utcDiff": "string"
                   }
                 },
                 "segmentation": {
                   "customerSegment": "string"
                 },
                 "hierarchy": {
                   "parent": "string",
                   "highestParent": "string"
                 },
                 "delivery": {
                   "transportationZone": {
                     "code": "string",
                     "description": "string"
                   }
                 },
                 "salesAreas": [
                   {
                     "salesOrganization": "string",
                     "distributionChannel": "string",
                     "division": "string",
                     "status": "string",
                     "valueChain": {
                       "FVC": {
                         "businessUnit": "string",
                         "RBU": "string"
                       },
                       "LVC": {
                           "businessUnit": "string",
                           "GBU": "string",
                           "MBU": "string"
                       }
                     },
                     "marketing": {
                       "accountCategories": ["string..."],
                       "accountType": "string",
                       "salesDistrict": {
                         "code": "string",
                         "description": "string"
                       },
                       "salesGroup": {
                         "code": "string",
                         "description": "string"
                       },
                       "salesOffice": {
                         "code": "string",
                         "description": "string"
                       }
                     },
                     "segmentation": {
                       "marketSegment": {
                         "LVC":  {
                           "level1": "string",
                           "level2": "string",
                           "level3": "string",
                           "level4": "string",
                           "level5": "string",
                           "level6": "string"
                         },
                         "FVC": "string"
                       }
                     },
                     "blocking": {
                       "order": "string",
                       "delivery": "string"
                     },
                     "pricing": {
                       "priceGroup": {
                         "code": "string"
                       }
                     },
                     "delivery": {
                       "deliveringPlant": {
                         "code": "string"
                       },
                       "shippingCondition": {
                         "code": "string"
                       },
                       "modeOfTransportation": "string"
                     },
                     "billing": {
                       "incoTerms": {
                         "code": "string"
                       },
                       "currency": {
                         "isoCode": "string"
                       },
                       "paymentTerms": {
                         "code": "string",
                         "description": "string"
                       }
                     }
                   }
                 ]
               }
             }       
    ```
</details>
