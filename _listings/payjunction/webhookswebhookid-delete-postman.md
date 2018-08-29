{
  "info": {
    "name": "PayJunction Delete Webhooks",
    "_postman_id": "4c13e48f-9266-4c7f-9bf2-a69cff8ad013",
    "description": "/webhooks/{webhookid}.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Customers",
      "item": [
        {
          "id": "f5378d96-a624-4c54-8173-dc2a2d436ab1",
          "name": "CustomersGet",
          "request": {
            "url": "http://example.com/customers?limit=%7B%7D&offset=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "X-PJ-Application-Key",
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
            "description": "Gets a list of 15 customers"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9df30832-f313-4051-91e3-a4704df9ecec"
            }
          ]
        },
        {
          "id": "23f0a934-85c5-4e42-9b6c-2b102652c490",
          "name": "CustomersByCustomerIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId"
              ],
              "variable": [
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "X-PJ-Application-Key",
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
            "description": "/customers/{customerid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9b7536b9-cb41-443e-903d-3134268e43b3"
            }
          ]
        },
        {
          "id": "a3e09e0d-7ca3-4a1a-85c8-7d468dcd1a57",
          "name": "CustomersByCustomerIdPut",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId"
              ],
              "variable": [
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "header": [
              {
                "key": "X-PJ-Application-Key",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "companyName",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "custom1",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "defaultAddressId",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "email",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "firstName",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "identifier",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "jobTitle",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "lastName",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "middleName",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "phone",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "phone2",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "website",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "/customers/{customerid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "428854a7-f6cd-4514-bf9b-08a1ca9fc8ce"
            }
          ]
        },
        {
          "id": "8a778c35-f4ca-4575-b267-bd17d399b719",
          "name": "CustomersByCustomerIdDelete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId"
              ],
              "variable": [
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "header": [
              {
                "key": "X-PJ-Application-Key",
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
            "description": "/customers/{customerid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "40dc020a-7af9-47ac-ab20-3d18222ba8ef"
            }
          ]
        },
        {
          "id": "600b3e6e-99a6-463b-8af3-7490efe8599e",
          "name": "CustomersPost",
          "request": {
            "url": "http://example.com/customers/",
            "method": "POST",
            "header": [
              {
                "key": "X-PJ-Application-Key",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "companyName",
                  "value": "{}",
                  "disabled": false,
                  "description": "Text, Max Length 64"
                },
                {
                  "key": "custom1",
                  "value": "{}",
                  "disabled": false,
                  "description": "Text, Max Length 32"
                },
                {
                  "key": "email",
                  "value": "{}",
                  "disabled": false,
                  "description": "Email (1), Max Length 128"
                },
                {
                  "key": "firstName",
                  "value": "{}",
                  "disabled": false,
                  "description": "Text, Max Length 16"
                },
                {
                  "key": "identifier",
                  "value": "{}",
                  "disabled": false,
                  "description": "Text, Max Length 64"
                },
                {
                  "key": "jobTitle",
                  "value": "{}",
                  "disabled": false,
                  "description": "Text, Max Length 32"
                },
                {
                  "key": "lastName",
                  "value": "{}",
                  "disabled": false,
                  "description": "Text, Max Length 32"
                },
                {
                  "key": "middleName",
                  "value": "{}",
                  "disabled": false,
                  "description": "Text, Max Length 32"
                },
                {
                  "key": "phone",
                  "value": "{}",
                  "disabled": false,
                  "description": "Phone Number, Max Length 24, Must contain at least 10 digits"
                },
                {
                  "key": "phone2",
                  "value": "{}",
                  "disabled": false,
                  "description": "Phone Number, Max Length 24, Must contain at least 10 digits"
                },
                {
                  "key": "website",
                  "value": "{}",
                  "disabled": false,
                  "description": "Text, Max Length 128"
                }
              ]
            },
            "description": "Add a new customer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "079142f5-6a92-4fd5-884b-fb979a87ea08"
            }
          ]
        },
        {
          "id": "f53a643f-6658-4407-b1f9-b6e13a99e0a0",
          "name": "CustomersNotesByCustomerIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId/notes"
              ],
              "query": [
                {
                  "key": "limit",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "offset",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "X-PJ-Application-Key",
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
            "description": "/customers/{customerid}/notes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b2f4fb13-ed00-4f56-a16a-2d77f7608725"
            }
          ]
        },
        {
          "id": "0d895843-88c5-473c-86d9-25926a44da76",
          "name": "CustomersNotesByCustomerIdPost",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId/notes"
              ],
              "variable": [
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "X-PJ-Application-Key",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "note",
                  "value": "{}",
                  "disabled": false,
                  "description": "Max Length 2048"
                }
              ]
            },
            "description": "/customers/{customerid}/notes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "61bac5ad-f587-438e-bde3-aaa52e43e736"
            }
          ]
        },
        {
          "id": "78f74eca-0dca-4880-968d-fdb0536b2cd6",
          "name": "CustomersNotesByCustomerIdAndNoteIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId/notes/:noteId"
              ],
              "variable": [
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "noteId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "X-PJ-Application-Key",
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
            "description": "/customers/{customerid}/notes/{noteid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "da8c3b84-2f9a-48f0-ae6a-a6cfb10cc4d0"
            }
          ]
        },
        {
          "id": "6e1757b1-a4fa-416f-8f1a-5a77d6211543",
          "name": "CustomersNotesByCustomerIdAndNoteIdPut",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId/notes/:noteId"
              ],
              "variable": [
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "noteId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "X-PJ-Application-Key",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "note",
                  "value": "{}",
                  "disabled": false,
                  "description": "Max Length 2048"
                }
              ]
            },
            "description": "/customers/{customerid}/notes/{noteid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "231cc438-2156-4ee6-9cc2-5b95c4058af5"
            }
          ]
        },
        {
          "id": "6225cb0f-2270-46a6-a443-bbbdbc72148c",
          "name": "CustomersNotesByCustomerIdAndNoteIdDelete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId/notes/:noteId"
              ],
              "variable": [
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "noteId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "header": [
              {
                "key": "X-PJ-Application-Key",
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
            "description": "/customers/{customerid}/notes/{noteid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6ec5a58a-55bd-47dc-b830-3f1f1e8bd4ab"
            }
          ]
        },
        {
          "id": "0975db4c-fdf1-4750-9d22-55b1a4e69b64",
          "name": "CustomersVaultsByCustomerIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId/vaults/"
              ],
              "variable": [
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "X-PJ-Application-Key",
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
            "description": "Retrieve customer's payment vaults"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6cb4aa64-d60a-407a-9234-6c49a29aa3a5"
            }
          ]
        },
        {
          "id": "66095354-6a7d-480c-ba53-f8d176b4856f",
          "name": "CustomersVaultsByCustomerIdAndVaultIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId/vaults/:vaultId"
              ],
              "variable": [
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "vaultId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "X-PJ-Application-Key",
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
            "description": "/customers/{customerid}/vaults/{vaultid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d74d855a-e582-45b8-96c4-6b9f7e0882b7"
            }
          ]
        },
        {
          "id": "3d763225-e841-490c-8358-a81d59437075",
          "name": "CustomersVaultsByCustomerIdAndVaultIdDelete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId/vaults/:vaultId"
              ],
              "variable": [
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "vaultId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "header": [
              {
                "key": "X-PJ-Application-Key",
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
            "description": "/customers/{customerid}/vaults/{vaultid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7e1bc0c5-d33b-45ec-872e-b49e5653bd68"
            }
          ]
        },
        {
          "id": "68ea48cc-c0ce-4c61-88dd-54a92c24d3f4",
          "name": "CustomersVaultsByCustomerIdPost2",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId/vaults"
              ],
              "variable": [
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "X-PJ-Application-Key",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "address",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "addressId",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "cardExpMonth",
                  "value": "{}",
                  "disabled": false,
                  "description": "1-12"
                },
                {
                  "key": "cardExpYear",
                  "value": "{}",
                  "disabled": false,
                  "description": "YYYY, YY"
                },
                {
                  "key": "cardNumber",
                  "value": "{}",
                  "disabled": false,
                  "description": "5105105105105100,5105-1051-0510-5100,5105 1051 0510 5100"
                },
                {
                  "key": "city",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "state",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "zip",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "/customers/{customerid}/vaults (card)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "68763223-fc07-4811-baf3-4e44df0d841e"
            }
          ]
        },
        {
          "id": "3d511620-0267-45ee-b472-3419d93da299",
          "name": "CustomersVaultsByCustomerIdAndAchVaultPut",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId/vaults/:achVault"
              ],
              "variable": [
                {
                  "id": "achVault",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "header": [
              {
                "key": "X-PJ-Application-Key",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "achAccountType",
                  "value": "{}",
                  "disabled": false,
                  "description": "CHECKING, SAVINGS"
                },
                {
                  "key": "achType",
                  "value": "{}",
                  "disabled": false,
                  "description": "CCD, PPD, TEL, WEB"
                },
                {
                  "key": "address",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "addressId",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "city",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "state",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "zip",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "/customers/{customerid}/vaults/{vaultid} (ach)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1dfa51c0-3543-4616-a1bf-3ff9146f5bf8"
            }
          ]
        },
        {
          "id": "99aebe6a-72e3-4980-b26c-ffda2c7d0e90",
          "name": "CustomersVaultsByCustomerIdAndCardVaultPut",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId/vaults/:cardVault"
              ],
              "variable": [
                {
                  "id": "cardVault",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "header": [
              {
                "key": "X-PJ-Application-Key",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "address",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "addressId",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "cardExpMonth",
                  "value": "{}",
                  "disabled": false,
                  "description": "1-12"
                },
                {
                  "key": "cardExpYear",
                  "value": "{}",
                  "disabled": false,
                  "description": "YYYY, YY"
                },
                {
                  "key": "city",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "state",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "zip",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "/customers/{customerid}/vaults/{vaultid} (card)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0458c334-fdda-4261-a9ef-b2e1fb56488a"
            }
          ]
        },
        {
          "id": "48c43bf4-c381-4061-b480-a3ac6bd1d6f6",
          "name": "CustomersAddressesByCustomerIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId/addresses"
              ],
              "variable": [
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "X-PJ-Application-Key",
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
            "description": "Gets a list of a customer's addresses."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "16710f97-a14c-4d72-8ff3-1acf19e1b644"
            }
          ]
        },
        {
          "id": "ce573756-d678-4ef1-8d57-c29d8cbdd0ee",
          "name": "CustomersAddressesByCustomerIdPost",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId/addresses"
              ],
              "variable": [
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "X-PJ-Application-Key",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "address",
                  "value": "{}",
                  "disabled": false,
                  "description": "Text, Max Length 128"
                },
                {
                  "key": "city",
                  "value": "{}",
                  "disabled": false,
                  "description": "Text, Max Length 32"
                },
                {
                  "key": "country",
                  "value": "{}",
                  "disabled": false,
                  "description": "Text, Max Length 32"
                },
                {
                  "key": "state",
                  "value": "{}",
                  "disabled": false,
                  "description": "Text, Max Length 32"
                },
                {
                  "key": "zip",
                  "value": "{}",
                  "disabled": false,
                  "description": "Text, Max Length 16"
                }
              ]
            },
            "description": "/customers/{customerid}/addresses/."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "34bb3efd-07df-41ca-90d6-d9203d9c823f"
            }
          ]
        },
        {
          "id": "b3caa88c-e179-4a0a-86df-efeeb8e14564",
          "name": "CustomersAddressesByCustomerIdAndAddressIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId/addresses/:addressId"
              ],
              "variable": [
                {
                  "id": "addressId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "X-PJ-Application-Key",
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
            "description": "/customers/{customerid}/addresses/{addressid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a99629ff-d6dd-4475-bc45-7d3203714512"
            }
          ]
        },
        {
          "id": "84b1a55d-fe1d-4068-98ee-112e25f5d6a3",
          "name": "CustomersAddressesByCustomerIdAndAddressIdPut",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId/addresses/:addressId"
              ],
              "variable": [
                {
                  "id": "addressId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "header": [
              {
                "key": "X-PJ-Application-Key",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "address",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "city",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "country",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "state",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "zip",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "/customers/{customerid}/addresses/{addressid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5e063b4a-becb-4fdf-9a69-d7da7d4adf3d"
            }
          ]
        },
        {
          "id": "80884605-d5dc-4e13-a8e5-9539187c9482",
          "name": "CustomersAddressesByCustomerIdAndAddressIdDelete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "customers/:customerId/addresses/:addressId"
              ],
              "variable": [
                {
                  "id": "addressId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "customerId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "X-PJ-Application-Key",
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
            "description": "/customers/{customerid}/addresses/{addressid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "57c6ffa6-ae9b-4b20-affb-bb9016dde64a"
            }
          ]
        }
      ]
    },
    {
      "name": "Transactions",
      "item": [
        {
          "id": "7173e30b-69d6-4179-a037-dc7fafb4a85f",
          "name": "TransactionsPost6",
          "request": {
            "url": "http://example.com/transactions",
            "method": "POST",
            "header": [
              {
                "key": "X-PJ-Application-Key",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "action",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "amountBase",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "billingCompanyName",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "billingFirstName",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "billingLastName",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "cardTrack",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "/transactions/ (swiped cc)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3056cf83-d796-422f-945d-f3d9bb740925"
            }
          ]
        },
        {
          "id": "69a39ca1-8cf4-4834-a20f-1ad8b28a2e93",
          "name": "TransactionsGet",
          "request": {
            "url": "http://example.com/transactions/?limit=%7B%7D&offset=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "X-PJ-Application-Key",
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
            "description": "Not Available At Time at Time of Publishing this collection: Get a list of transactions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8a2108d6-c540-4cf7-bcac-1afba7d73f38"
            }
          ]
        },
        {
          "id": "ce06145f-5454-43ab-8030-1e99e86df55b",
          "name": "TransactionsByTransactionIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "transactions/:transactionId"
              ],
              "variable": [
                {
                  "id": "transactionId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "X-PJ-Application-Key",
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
            "description": "/transactions/{transactionid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bd281e35-a4f4-4f89-96e1-2a0aad93229c"
            }
          ]
        },
        {
          "id": "1415ff26-3577-41de-95b5-ac85075e4a5b",
          "name": "TransactionsByTransactionIdPut",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "transactions/:transactionId"
              ],
              "variable": [
                {
                  "id": "transactionId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "X-PJ-Application-Key",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "amountBase",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "amountReject",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "amountShipping",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "amountTax",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "amountTip",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "status",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Update an unsettled transaction"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c5a95bdd-57c9-4356-981c-a0a5b3d31847"
            }
          ]
        },
        {
          "id": "10ed0dc3-5cd1-402e-b284-560a5f1661fc",
          "name": "TransactionsNotesByTransactionIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "transactions/:transactionId/notes"
              ],
              "query": [
                {
                  "key": "limit",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "offset",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "transactionId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "X-PJ-Application-Key",
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
            "description": "Get a list of notes for a transaction"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4ec221a4-8dec-4716-a262-e87cef0f27cb"
            }
          ]
        },
        {
          "id": "fb94cfc5-39ba-439c-8cb6-1638a22fddb5",
          "name": "TransactionsNotesByTransactionIdPost",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "transactions/:transactionId/notes"
              ],
              "variable": [
                {
                  "id": "transactionId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "X-PJ-Application-Key",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "note",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "/transactions/{transactionid}/notes/."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "96021130-1ec7-4eec-86fa-4e46ee527917"
            }
          ]
        },
        {
          "id": "fa697b9c-b4e2-470b-a126-b135bdbef1d0",
          "name": "TransactionsNotesByTransactionIdAndNoteIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "transactions/:transactionId/notes/:noteId"
              ],
              "variable": [
                {
                  "id": "noteId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "transactionId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "X-PJ-Application-Key",
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
            "description": "/transactions/{transactionid}/notes/{noteid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e744a75b-f6a7-4acf-90cb-b4740d3f3721"
            }
          ]
        },
        {
          "id": "5152e03f-0272-46e8-8ae8-1211be44003b",
          "name": "TransactionsNotesByTransactionIdAndNoteIdPut",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "transactions/:transactionId/notes/:noteId"
              ],
              "variable": [
                {
                  "id": "noteId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "transactionId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "header": [
              {
                "key": "X-PJ-Application-Key",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "note",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "/transactions/{transactionid}/notes/{noteid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "29ebf575-568e-4748-bf99-97919d655401"
            }
          ]
        },
        {
          "id": "8587c2b2-7a98-4dcc-adf9-e25df773a3bf",
          "name": "TransactionsNotesByTransactionIdAndNoteIdDelete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "transactions/:transactionId/notes/:noteId"
              ],
              "variable": [
                {
                  "id": "noteId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "transactionId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "header": [
              {
                "key": "X-PJ-Application-Key",
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
            "description": "/transactions/{transactionid}/notes/{noteid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d49835d2-e8df-4f55-8ca0-28da313f24fa"
            }
          ]
        },
        {
          "id": "29ee2bef-893b-4d01-98b3-e92c6e996421",
          "name": "TransactionsSignatureCaptureByTransactionIdPost",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "transactions/:transactionId/signature/capture"
              ],
              "variable": [
                {
                  "id": "transactionId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "X-PJ-Application-Key",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "signature",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Capture a signature using the scriptel signature capture"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f052405d-2384-4332-96f2-71f06e5e6359"
            }
          ]
        },
        {
          "id": "161f6dcc-57f1-4aa7-b176-6a5e118a9121",
          "name": "TransactionsReceiptsLatestEmailByTransactionIdPost",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "transactions/:transactionId/receipts/latest/email"
              ],
              "variable": [
                {
                  "id": "transactionId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "X-PJ-Application-Key",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "replyTo",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "requestSignature",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "to",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "/transactions/{transactionid}/receipts/latest/email."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f14186af-ac65-488f-9e30-28f8a2cc4fae"
            }
          ]
        },
        {
          "id": "22a86649-ac11-4d85-9cb7-ba389e5fa2aa",
          "name": "TransactionsReceiptsByTransactionIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "transactions/:transactionId/receipts"
              ],
              "variable": [
                {
                  "id": "transactionId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "X-PJ-Application-Key",
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
            "description": "Get all of the signed receipts for a transaction."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c753aa0b-a8e1-443f-ab1c-075da0bb5573"
            }
          ]
        },
        {
          "id": "721a4e25-53fa-4358-9b22-3f69eb9bc7e5",
          "name": "TransactionsReceiptsLatestByTransactionIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "transactions/:transactionId/receipts/latest"
              ],
              "variable": [
                {
                  "id": "transactionId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "X-PJ-Application-Key",
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
            "description": "Retrieve the most recent version of the receipt."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ab9d184d-154c-4aa3-a715-47f95d0a63ae"
            }
          ]
        },
        {
          "id": "14ffc451-46e9-49ec-bc2d-673826124b9f",
          "name": "TransactionsReceiptsLatestThermalByTransactionIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "transactions/:transactionId/receipts/latest/thermal"
              ],
              "variable": [
                {
                  "id": "transactionId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "X-PJ-Application-Key",
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
            "description": "Get the most recent version of the thermal receipt HTML Document"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "018f8536-aa51-48c5-874c-367f13327c5d"
            }
          ]
        },
        {
          "id": "3f303635-afcc-4f1d-8137-6a28beba153d",
          "name": "TransactionsReceiptsLatestFullpageByTransactionIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "transactions/:transactionId/receipts/latest/fullpage"
              ],
              "variable": [
                {
                  "id": "transactionId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "X-PJ-Application-Key",
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
            "description": "Get the most recent version of the full page (8.5x11) receipt HTML document"
          },
          "response": [
            {
              "status": "OK",
          