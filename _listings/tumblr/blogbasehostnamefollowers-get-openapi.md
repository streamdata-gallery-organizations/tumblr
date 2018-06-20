---
swagger: "2.0"
x-collection-name: Tumblr
x-complete: 0
info:
  title: Tumblr Get Blog Base Hostname Followers
  description: Retrieves a blog's followers.
  version: 1.0.0
host: api.tumblr.com
basePath: /v2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /blog/{base-hostname}/info:
    get:
      summary: Get Blog Base Hostname Info
      description: This method returns general information about the blog, such as
        the title, number of posts, and other high-level data.
      operationId: blog.base_hostname.info.get
      x-api-path-slug: blogbasehostnameinfo-get
      parameters:
      - in: path
        name: base-hostname
        description: The unique hostname of the blog
      responses:
        200:
          description: OK
      tags:
      - Blog
      - Base
      - Hostname
      - Info
  /blog/{base-hostname}/avatar/{size}:
    get:
      summary: Get Blog Base Hostname Avatar Size
      description: Retrieves a blog's avatar in one of 9 different sizes.
      operationId: blog.base_hostname.avatar.size.get
      x-api-path-slug: blogbasehostnameavatarsize-get
      parameters:
      - in: path
        name: base-hostname
        description: The unique hostname of the blog
      - in: path
        name: size
        description: The size of the avatar (square, one value for both length and
          width)
      responses:
        200:
          description: OK
      tags:
      - Blog
      - Base
      - Hostname
      - Avatar
      - Size
  /blog/{base-hostname}/followers:
    get:
      summary: Get Blog Base Hostname Followers
      description: Retrieves a blog's followers.
      operationId: blog.base_hostname.followers.get
      x-api-path-slug: blogbasehostnamefollowers-get
      parameters:
      - in: path
        name: base-hostname
        description: The unique hostname of the blog
      - in: query
        name: limit
        description: 'The number of results to return: 120, inclusive'
      - in: query
        name: offset
        description: Result to start at
      responses:
        200:
          description: OK
      tags:
      - Blog
      - Base
      - Hostname
      - Followers
x-streamrank:
  polling_total_time_average: "0"
  polling_size_download_average: "0"
  streaming_total_time_average: "0"
  streaming_size_download_average: "0"
  change_yes: "0"
  change_no: "0"
  time_percentage: "0"
  size_percentage: "0"
  change_percentage: "200"
  last_run: ~
  days_run: "0"
  minute_run: "0"
---