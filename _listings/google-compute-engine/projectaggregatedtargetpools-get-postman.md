{
  "info": {
    "name": "Compute Engine",
    "_postman_id": "c6c2f037-0e0d-4ebd-81d0-daa282274177",
    "description": "Creates and runs virtual machines on Google Cloud Platform.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "target pools",
      "item": [
        {
          "id": "ac7804c7-c483-4dd8-8ab8-3a64985c99b7",
          "name": "compute.targetPools.aggregatedList",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.googleapis.com",
              "path": [
                "compute",
                "v1",
                "projects",
                ":project/aggregated/targetPools"
              ],
              "query": [
                {
                  "key": "filter",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "maxResults",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "orderBy",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "pageToken",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "project",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves an aggregated list of target pools"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "69044ecd-eae8-4729-b2e0-135295e53067"
            }
          ]
        }
      ]
    }
  ]
}