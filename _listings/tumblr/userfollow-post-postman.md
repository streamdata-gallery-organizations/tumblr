{
  "info": {
    "name": "Tumblr Add User Follow",
    "_postman_id": "ac3c4e3e-a363-4a15-b198-56c4595e3a09",
    "description": "Follow a blog.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Blog",
      "item": [
        {
          "id": "9985e843-bd59-46cd-bd86-0acea19b010e",
          "name": "blog.base_hostname.info.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tumblr.com",
              "path": [
                "v2",
                "blog/:base-hostname/info"
              ],
              "variable": [
                {
                  "id": "base-hostname",
                  "value": "base-hostname",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This method returns general information about the blog, such as the title, number of posts, and other high-level data."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bb85747f-8a48-4ede-b976-51afb7d78265"
            }
          ]
        },
        {
          "id": "ae70034d-569e-4570-a4a8-b5e3fb8bfa9e",
          "name": "blog.base_hostname.avatar.size.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tumblr.com",
              "path": [
                "v2",
                "blog/:base-hostname/avatar/:size"
              ],
              "variable": [
                {
                  "id": "base-hostname",
                  "value": "base-hostname",
                  "type": "string"
                },
                {
                  "id": "size",
                  "value": "size",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves a blog's avatar in one of 9 different sizes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5d3f13f9-5892-47c2-a63a-72c64279b1b7"
            }
          ]
        },
        {
          "id": "96ef7f11-b6a9-4c12-b94a-8a333f3238ec",
          "name": "blog.base_hostname.followers.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tumblr.com",
              "path": [
                "v2",
                "blog/:base-hostname/followers"
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
                  "id": "base-hostname",
                  "value": "base-hostname",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves a blog's followers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "41a4e170-0271-4a2c-bbee-c5e2101f8c70"
            }
          ]
        },
        {
          "id": "1400f148-0e4e-4a79-8550-64bbe95d1995",
          "name": "blog.base_hostname.posts.type.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tumblr.com",
              "path": [
                "v2",
                "blog/:base-hostname/posts/:type"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "id",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "limit",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "notes_info",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "offset",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "reblog_info",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "tag",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "base-hostname",
                  "value": "base-hostname",
                  "type": "string"
                },
                {
                  "id": "type",
                  "value": "type",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves published posts."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "daafd717-ce41-45b4-93bb-88ccc96d7b61"
            }
          ]
        },
        {
          "id": "e8d82ae4-f0cb-41a2-b146-ff49d6b4e472",
          "name": "blog.base_hostname.posts.queue.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tumblr.com",
              "path": [
                "v2",
                "blog/:base-hostname/posts/queue"
              ],
              "variable": [
                {
                  "id": "base-hostname",
                  "value": "base-hostname",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves queued posts."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "375b5238-a1b5-4c63-a61c-c2d693cf923b"
            }
          ]
        },
        {
          "id": "6d293d1c-26a4-4bbb-a36d-7fc3352e4847",
          "name": "blog.base_hostname.posts.draft.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tumblr.com",
              "path": [
                "v2",
                "blog/:base-hostname/posts/draft"
              ],
              "variable": [
                {
                  "id": "base-hostname",
                  "value": "base-hostname",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves draft posts."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "014bbb99-0879-4f22-a6ab-79d75aef58f1"
            }
          ]
        },
        {
          "id": "e342d891-971e-4428-b6b1-eb1ef62f387e",
          "name": "blog.base_hostname.posts.submission.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tumblr.com",
              "path": [
                "v2",
                "blog/:base-hostname/posts/submission"
              ],
              "variable": [
                {
                  "id": "base-hostname",
                  "value": "base-hostname",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves submission posts."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "290f9e74-12a9-4a19-afff-5e63b82be663"
            }
          ]
        },
        {
          "id": "38c58e99-b7b9-4229-958f-1169d8029d27",
          "name": "blog.base_hostname.post.post",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tumblr.com",
              "path": [
                "v2",
                "blog/:base-hostname/post"
              ],
              "query": [
                {
                  "key": "caption",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "data",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "date",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "embed",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "markdown",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "tags",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "tweet",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "type",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "base-hostname",
                  "value": "base-hostname",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new video blog post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "70198a4c-e9ad-40ef-85cc-1f2670aeb47c"
            }
          ]
        },
        {
          "id": "149b9070-7510-44bd-999b-3c9dda62531f",
          "name": "blog.base_hostname.post.edit.post",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tumblr.com",
              "path": [
                "v2",
                "blog/:base-hostname/post/edit"
              ],
              "query": [
                {
                  "key": "date",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "id",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "markdown",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "tags",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "tweet",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "type",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "base-hostname",
                  "value": "base-hostname",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Edits a blog post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e491bd01-4d73-47a3-a108-fd1a41a755a7"
            }
          ]
        },
        {
          "id": "e24995e1-f22c-4bf5-bc3a-c7406d1edbc4",
          "name": "blog.base_hostname.post.reblog.post",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tumblr.com",
              "path": [
                "v2",
                "blog/:base-hostname/post/reblog"
              ],
              "query": [
                {
                  "key": "comment",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "date",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "id",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "markdown",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "reblog_key",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "tags",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "tweet",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "type",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "base-hostname",
                  "value": "base-hostname",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Reblogs a post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "01fd72af-0409-4cdb-b011-017044ffdf5f"
            }
          ]
        },
        {
          "id": "a988e336-df97-4bb3-8ca8-ba6e93b020eb",
          "name": "blog.base_hostname.post.delete.post",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tumblr.com",
              "path": [
                "v2",
                "blog/:base-hostname/post/delete"
              ],
              "query": [
                {
                  "key": "id",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "base-hostname",
                  "value": "base-hostname",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a post."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "49e256a6-b2db-461f-8ef5-175d78aac5ac"
            }
          ]
        }
      ]
    },
    {
      "name": "User",
      "item": [
        {
          "id": "dd64889a-0583-4256-b283-bc2344f1898a",
          "name": "user.dashboard.get",
          "request": {
            "url": "http://api.tumblr.com/v2/user/dashboard?limit=%7B%7D&offset=%7B%7D&since_id=%7B%7D&type=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Use this method to retrieve the dashboard that matches the OAuth credentials submitted with the request."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c014b500-7f40-49d2-b1b2-ebb66f317851"
            }
          ]
        },
        {
          "id": "5cea79c9-15e6-4940-aa04-2960d27c09b3",
          "name": "user.likes.get",
          "request": {
            "url": "http://api.tumblr.com/v2/user/likes?limit=%7B%7D&offset=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Use this method to retrieve the liked posts that match the OAuth credentials submitted with the request."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e0ac10a2-9587-4868-a0e5-e34217b6e1cc"
            }
          ]
        },
        {
          "id": "2f196459-bcbe-40e9-89a9-acff2fa8e27d",
          "name": "user.following.get",
          "request": {
            "url": "http://api.tumblr.com/v2/user/following?limit=%7B%7D&offset=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Use this method to retrieve the blogs followed by the user whose OAuth credentials are submitted with the request."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8b82e9ca-3466-47f9-b867-f77f181f941e"
            }
          ]
        },
        {
          "id": "c1e01d8a-74b9-4077-be51-84540b3e4c0e",
          "name": "user.follow.post",
          "request": {
            "url": "http://api.tumblr.com/v2/user/follow?url=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Follow a blog."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8bf5ada6-fd11-4b6b-838c-9b6dc47f2efd"
            }
          ]
        }
      ]
    }
  ]
}