{
  "info": {
    "name": "Steem get_active_witnesses",
    "_postman_id": "6e258faa-b7dc-4ac8-9d4c-6d33a553961b",
    "description": "get_active_witnesses",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Get",
      "item": [
        {
          "id": "0cc39d25-0abb-40a1-8fe9-82858885ad27",
          "name": "get-active-witnesses",
          "request": {
            "url": "http://api.steemjs.com/get_active_witnesses",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "get_active_witnesses"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1fd90ffa-de28-4e2e-9817-b32ba51773d2"
            }
          ]
        }
      ]
    }
  ]
}