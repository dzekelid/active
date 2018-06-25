{
  "info": {
    "name": "Pay Run.IO Runs the active pay instructions report",
    "_postman_id": "ba9bb00a-7968-4388-afaa-2ba259f1e9da",
    "description": "Returns the result of the executed active pay instructions report for the given query parameters",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Runs",
      "item": [
        {
          "id": "bd429362-ed63-49de-b14e-986576dcfdf1",
          "name": "GetActivePayInstructionsReportOutput",
          "request": {
            "url": "http://api.test.payrun.io/Report/ACTPAYINS/run?ActiveOn=%7B%7D&EmployeeKey=%7B%7D&EmployerKey=%7B%7D&Type=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Api-Version",
                "value": "{}",
                "description": "The version of the api to target",
                "disabled": false
              },
              {
                "key": "Authorization",
                "value": "{}",
                "description": "The OAuth 1 authorization header",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns the result of the executed active pay instructions report for the given query parameters"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9be1d270-ddbd-476f-ba70-cc8479bad018"
            }
          ]
        }
      ]
    }
  ]
}