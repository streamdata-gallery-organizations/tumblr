---
swagger: "2.0"
x-collection-name: Tumblr
x-complete: 0
info:
  title: Tumblr Add Blog Base Hostname Add Edit
  description: Edits a blog post.
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
        description: 'The number of results to return: 1???20, inclusive'
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
  /blog/{base-hostname}/posts/{type}:
    get:
      summary: Get Blog Base Hostname Adds Type
      description: Retrieves published posts.
      operationId: blog.base_hostname.posts.type.get
      x-api-path-slug: blogbasehostnamepoststype-get
      parameters:
      - in: path
        name: base-hostname
        description: The unique hostname of the blog
      - in: query
        name: format
        description: Specifies the post format to return, other than HTML
      - in: query
        name: id
        description: A specific post ID
      - in: query
        name: limit
        description: 'The number of posts to return: 1???20, inclusive'
      - in: query
        name: notes_info
        description: Indicates whether to return notes information (specify true or
          false)
      - in: query
        name: offset
        description: Post number to start at
      - in: query
        name: reblog_info
        description: Indicates whether to return reblog information (specify true
          or false)
      - in: query
        name: tag
        description: Limits the response to posts with the specified tag
      - in: path
        name: type
        description: The type of post to return
      responses:
        200:
          description: OK
      tags:
      - Blog
      - Base
      - Hostname
      - Posts
      - Type
  /blog/{base-hostname}/posts/queue:
    get:
      summary: Get Blog Base Hostname Adds Queue
      description: Retrieves queued posts.
      operationId: blog.base_hostname.posts.queue.get
      x-api-path-slug: blogbasehostnamepostsqueue-get
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
      - Posts
      - Queue
  /blog/{base-hostname}/posts/draft:
    get:
      summary: Get Blog Base Hostname Adds Draft
      description: Retrieves draft posts.
      operationId: blog.base_hostname.posts.draft.get
      x-api-path-slug: blogbasehostnamepostsdraft-get
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
      - Posts
      - Draft
  /blog/{base-hostname}/posts/submission:
    get:
      summary: Get Blog Base Hostname Adds Submission
      description: Retrieves submission posts.
      operationId: blog.base_hostname.posts.submission.get
      x-api-path-slug: blogbasehostnamepostssubmission-get
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
      - Posts
      - Submission
  /blog/{base-hostname}/post:
    post:
      summary: Add Blog Base Hostname Add
      description: Creates a new video blog post.
      operationId: blog.base_hostname.post.post
      x-api-path-slug: blogbasehostnamepost-post
      parameters:
      - in: path
        name: base-hostname
        description: The unique hostname of the blog
      - in: query
        name: caption
        description: The user-supplied caption
      - in: query
        name: data
        description: A video file, as URL-encoded binary
      - in: query
        name: date
        description: The GMT date and time of the post, as a string
      - in: query
        name: embed
        description: HTML embed code for the video
      - in: query
        name: markdown
        description: Indicates whether the post uses markdown syntax
      - in: query
        name: tags
        description: Comma-separated tags for this post
      - in: query
        name: tweet
        description: 'Manages the autotweet (if enabled) for this post: set to off
          for no tweet, or enter text to override the default tweet'
      - in: query
        name: type
        description: The type of post to create
      responses:
        200:
          description: OK
      tags:
      - Blog
      - Base
      - Hostname
      - Post
  /blog/{base-hostname}/post/edit:
    post:
      summary: Add Blog Base Hostname Add Edit
      description: Edits a blog post.
      operationId: blog.base_hostname.post.edit.post
      x-api-path-slug: blogbasehostnamepostedit-post
      parameters:
      - in: path
        name: base-hostname
        description: The unique hostname of the blog
      - in: query
        name: date
        description: The GMT date and time of the post, as a string
      - in: query
        name: id
        description: The ID of the post to edit
      - in: query
        name: markdown
        description: Indicates whether the post uses markdown syntax
      - in: query
        name: tags
        description: Comma-separated tags for this post
      - in: query
        name: tweet
        description: 'Manages the autotweet (if enabled) for this post: set to off
          for no tweet, or enter text to override the default tweet'
      - in: query
        name: type
        description: The post type
      responses:
        200:
          description: OK
      tags:
      - Blog
      - Base
      - Hostname
      - Post
      - Edit
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---