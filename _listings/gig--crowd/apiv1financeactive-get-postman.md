{
  "info": {
    "name": "GIGANDCROWD Get Finance Active",
    "_postman_id": "da62d25a-0c35-47b8-a27e-5aa31feeeccb",
    "description": "Get finance active.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Event",
      "item": [
        {
          "id": "39d6ab86-d56b-43a1-a288-7df76708fa49",
          "name": "getApiV1EventActive",
          "request": {
            "url": "http://gigandcrowd.com/api/v1/event/active",
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get event active."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c38660e5-8ca9-462c-a6eb-85832b202436"
            }
          ]
        }
      ]
    },
    {
      "name": "Finance",
      "item": [
        {
          "id": "a82b1173-a784-4888-92dd-2ae9e1c4a64f",
          "name": "getApiV1FinanceActive",
          "request": {
            "url": "http://gigandcrowd.com/api/v1/finance/active",
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get finance active."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "253129eb-79a7-48b3-88da-c9a865ad7590"
            }
          ]
        }
      ]
    }
  ]
}