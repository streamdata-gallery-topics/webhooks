{
  "info": {
    "name": "PayJunction Get Webhooks",
    "_postman_id": "c5e8a107-1871-46a2-b869-c3a805f60dcc",
    "description": "Gets a list of webhooks",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Customers",
      "item": [
        {
          "id": "4569889e-9d3f-490e-8221-4324b2e0f4b8",
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
              "id": "acd5d8eb-f865-4240-863c-7fc0efdae3a9"
            }
          ]
        },
        {
          "id": "0ce58162-40f8-4bac-9d4d-60bfa46f1b46",
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
              "id": "152ed108-e296-4045-a6b1-4d74f64095f5"
            }
          ]
        },
        {
          "id": "8ad7fa36-0978-4421-8238-57420779f28c",
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
              "id": "6f0b59e7-6604-4b5d-b3a8-90186153df8c"
            }
          ]
        },
        {
          "id": "e333b75d-6cf6-4552-9309-aefe4de6ede6",
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
              "id": "8a583ba5-4880-408c-96a2-49a4aaa9cab9"
            }
          ]
        },
        {
          "id": "b5d7f9f2-3e68-41e4-8305-aa52eca5d937",
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
              "id": "4bcea851-bc7c-478e-b638-b145594a1091"
            }
          ]
        },
        {
          "id": "457c420f-50f5-41b0-9fad-e5a15a6446c7",
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
              "id": "449929eb-9914-4608-a256-5466731d982e"
            }
          ]
        },
        {
          "id": "9835ac70-78c5-4411-bcf5-44c4cd5b1c5c",
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
              "id": "43ab490b-c413-42a9-9899-ff8b7f1b7660"
            }
          ]
        },
        {
          "id": "5f85402c-2bde-4f53-9fc9-007646a7f032",
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
              "id": "c935b5ed-7d6c-448e-8247-48c3cc27b2cb"
            }
          ]
        },
        {
          "id": "91c576de-9a8f-45e2-96e8-bf3980cc6bb9",
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
              "id": "0baa596b-3b2a-4c0c-b923-04e2632a7ff4"
            }
          ]
        },
        {
          "id": "3b2d6f0a-2f46-4864-aa78-f736e82007d9",
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
              "id": "3091a076-0df1-4e38-9183-a91cadf71649"
            }
          ]
        },
        {
          "id": "1b371960-7f8d-4918-bd38-77273dbdef16",
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
              "id": "41897520-ad99-44b6-91e9-eae081fe951b"
            }
          ]
        },
        {
          "id": "a2ed6bce-b50f-4913-ac26-c6114c1c1293",
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
              "id": "f061a103-0adf-45d5-94db-3a7697bb4e4d"
            }
          ]
        },
        {
          "id": "244a479f-9a3b-4ffa-bbda-d502927b6e1d",
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
              "id": "1bb5dda0-3d6a-4a23-b533-e63f02527d40"
            }
          ]
        },
        {
          "id": "2b7333b6-ddc2-438a-bcb3-91151a41d0db",
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
              "id": "81a4d78b-e7fc-448d-bc36-6222ae565490"
            }
          ]
        },
        {
          "id": "f497948f-642a-4286-969f-a6d24150c14f",
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
              "id": "bb1c5477-398a-4132-bdd2-dd255a33f9ca"
            }
          ]
        },
        {
          "id": "04f26606-e094-4184-84d6-133e64159d86",
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
              "id": "4a6f386d-341e-4fac-847c-f9b484292b47"
            }
          ]
        },
        {
          "id": "faed8a7d-5e0e-4097-bc02-c115f03e4472",
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
              "id": "63275d1d-3e3c-46c1-9a99-3282feb48b9d"
            }
          ]
        },
        {
          "id": "520b4f0f-e137-41c9-afee-687d352f7aeb",
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
              "id": "19d8b237-2275-4600-bb6a-6e3121b1d68d"
            }
          ]
        },
        {
          "id": "5f46aa8e-e72c-464a-b966-ff59a2795525",
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
              "id": "6ed7b621-9fef-417c-b36b-9e5e4602f4ac"
            }
          ]
        },
        {
          "id": "a1d22c8f-77f2-4571-a5f6-176cf158b280",
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
              "id": "fe0df2b6-002b-4344-bc3e-acf32bcaa5d6"
            }
          ]
        },
        {
          "id": "df6a19c9-4698-4320-8a8c-4b63c6131c15",
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
              "id": "3a6d0fd1-142d-4647-9c2c-df837dda07db"
            }
          ]
        }
      ]
    },
    {
      "name": "Transactions",
      "item": [
        {
          "id": "e524b832-fa02-4da6-b176-f162669c5d1d",
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
              "id": "10306831-b1f3-456e-b21c-d06154a77a82"
            }
          ]
        },
        {
          "id": "bfe2e6ac-e686-4394-908e-c7213d9d0f16",
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
              "id": "a9b5a20e-2425-40a0-8c1b-d42165b05d34"
            }
          ]
        },
        {
          "id": "1c2fb8dd-23f7-41f7-a17c-ffc5f2bbab04",
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
              "id": "c61d0760-c6a5-4197-aee4-13c14ce929e7"
            }
          ]
        },
        {
          "id": "cd11272a-a74f-4e2a-994d-fc74805359ae",
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
              "id": "cd2cdfc0-2e16-4ae9-8ac2-4b9ea5dcd823"
            }
          ]
        },
        {
          "id": "cb1722a7-91ea-4811-8dda-a13de6727396",
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
              "id": "2b353d9a-e908-466b-902f-393a7ec8d945"
            }
          ]
        },
        {
          "id": "b22d5aa8-0507-450c-9168-dcce94128cc2",
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
              "id": "a3cb97f6-6a28-4072-a728-1c89f29bb471"
            }
          ]
        },
        {
          "id": "429dd92f-7f4a-4d38-90e9-33652cb78e35",
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
              "id": "0ad7040c-1fca-4cf2-a500-5cc82bf9031b"
            }
          ]
        },
        {
          "id": "08a7794b-1f78-4349-bea2-9a49e62b368c",
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
              "id": "9d197329-0461-4ca6-a19d-c4fe62c9f8f3"
            }
          ]
        },
        {
          "id": "8ca4b9c9-630c-4e7a-bd46-4635ef0ee6a0",
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
              "id": "b71074fe-dbce-4a0a-9e54-fe026ec87e2d"
            }
          ]
        },
        {
          "id": "37b1ca2c-b193-496c-854f-3a6f55e341f2",
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
              "id": "55726302-62fe-42dd-bc03-b47b757124a8"
            }
          ]
        },
        {
          "id": "2ac167a4-ded6-44b5-9dec-6f06350bc5aa",
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
              "id": "5a2c5ac5-615c-42f1-8e68-eaf3fb257d40"
            }
          ]
        },
        {
          "id": "4ed2ad7a-3083-4a4a-98bd-cb3da9f91663",
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
              "id": "348d1988-a8cf-498c-8d2b-da153dd9c429"
            }
          ]
        },
        {
          "id": "e67ed03c-3267-48ae-b825-c721905667c7",
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
              "id": "e75c46c0-5e36-4761-99df-4b8177704a22"
            }
          ]
        },
        {
          "id": "a18c7b0d-7958-4605-a6e1-8d5a0edaa198",
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
              "id": "88707749-4bcd-4bec-b69a-4a2068e1b8aa"
            }
          ]
        },
        {
          "id": "bc53ec0e-b648-4bc0-8630-25e881dd7659",
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
            