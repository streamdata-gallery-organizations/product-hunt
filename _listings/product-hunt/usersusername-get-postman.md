{
  "info": {
    "name": "Product Hunt Get Users",
    "_postman_id": "d1809886-c453-4509-92b5-c8443fb3a883",
    "description": "Get users.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Users",
      "item": [
        {
          "id": "6b44a6f6-d7ad-4156-a2a3-f5063662c825",
          "name": "getUsersUsername",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.producthunt.com",
              "path": [
                "v1",
                "users/:username"
              ],
              "variable": [
                {
                  "id": "username",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get users."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f539910e-7798-4d4d-82fc-ce58da62026f"
            }
          ]
        }
      ]
    }
  ]
}