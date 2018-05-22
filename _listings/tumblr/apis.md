---
name: Tumblr
x-slug: tumblr
description: Tumblr is a re-envisioning of tumblelogging, a subset of blogging that
  uses quick, mixed-media posts. The service hopes to do for the tumblelog what services
  like LiveJournal and Blogger did for the blog. The difference is that its extreme
  simplicity will make luring users a far easier task than acquiring users for traditional
  weblogging. Anytime a user sees something interesting online, they can click a quick
  &ldquo;Share on Tumblr&rdquo; bookmarklet that then tumbles the snippet directly.
  The result is varied string of media ranging links and text to pictures and videos
  that takes very little time and effort to maintain.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/img_logotype_34465d_2x.png
x-kinRank: "7"
x-alexaRank: ""
tags: Tumblr
created: "2018-05-22"
modified: "2018-05-22"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/apis.md
specificationVersion: "0.14"
apis:
- name: Tumblr Get Blog Base Hostname Info
  x-api-slug: tumblr
  description: This method returns general information about the blog, such as the
    title, number of posts, and other high-level data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/img_logotype_34465d_2x.png
  humanURL: https://www.tumblr.com/
  baseURL: https://api.tumblr.com//v2///blog/{base-hostname}/info
  tags: Blog, Base, Hostname, Info
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/blogbasehostnameinfo-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/blogbasehostnameinfo-get-openapi.md
- name: Tumblr Get Blog Base Hostname Avatar Size
  x-api-slug: tumblr
  description: Retrieves a blog's avatar in one of 9 different sizes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/img_logotype_34465d_2x.png
  humanURL: https://www.tumblr.com/
  baseURL: https://api.tumblr.com//v2///blog/{base-hostname}/avatar/{size}
  tags: Blog, Base, Hostname, Avatar, Size
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/blogbasehostnameavatarsize-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/blogbasehostnameavatarsize-get-openapi.md
- name: Tumblr Get Blog Base Hostname Followers
  x-api-slug: tumblr
  description: Retrieves a blog's followers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/img_logotype_34465d_2x.png
  humanURL: https://www.tumblr.com/
  baseURL: https://api.tumblr.com//v2///blog/{base-hostname}/followers
  tags: Blog, Base, Hostname, Followers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/blogbasehostnamefollowers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/blogbasehostnamefollowers-get-openapi.md
- name: Tumblr Get Blog Base Hostname Adds Type
  x-api-slug: tumblr
  description: Retrieves published posts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/img_logotype_34465d_2x.png
  humanURL: https://www.tumblr.com/
  baseURL: https://api.tumblr.com//v2///blog/{base-hostname}/posts/{type}
  tags: Blog, Base, Hostname, Posts, Type
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/blogbasehostnamepoststype-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/blogbasehostnamepoststype-get-openapi.md
- name: Tumblr Get Blog Base Hostname Adds Queue
  x-api-slug: tumblr
  description: Retrieves queued posts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/img_logotype_34465d_2x.png
  humanURL: https://www.tumblr.com/
  baseURL: https://api.tumblr.com//v2///blog/{base-hostname}/posts/queue
  tags: Blog, Base, Hostname, Posts, Queue
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/blogbasehostnamepostsqueue-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/blogbasehostnamepostsqueue-get-openapi.md
- name: Tumblr Get Blog Base Hostname Adds Draft
  x-api-slug: tumblr
  description: Retrieves draft posts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/img_logotype_34465d_2x.png
  humanURL: https://www.tumblr.com/
  baseURL: https://api.tumblr.com//v2///blog/{base-hostname}/posts/draft
  tags: Blog, Base, Hostname, Posts, Draft
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/blogbasehostnamepostsdraft-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/blogbasehostnamepostsdraft-get-openapi.md
- name: Tumblr Get Blog Base Hostname Adds Submission
  x-api-slug: tumblr
  description: Retrieves submission posts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/img_logotype_34465d_2x.png
  humanURL: https://www.tumblr.com/
  baseURL: https://api.tumblr.com//v2///blog/{base-hostname}/posts/submission
  tags: Blog, Base, Hostname, Posts, Submission
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/blogbasehostnamepostssubmission-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/blogbasehostnamepostssubmission-get-openapi.md
- name: Tumblr Add Blog Base Hostname Add
  x-api-slug: tumblr
  description: Creates a new video blog post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/img_logotype_34465d_2x.png
  humanURL: https://www.tumblr.com/
  baseURL: https://api.tumblr.com//v2///blog/{base-hostname}/post
  tags: Blog, Base, Hostname, Post
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/blogbasehostnamepost-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/blogbasehostnamepost-post-openapi.md
- name: Tumblr Add Blog Base Hostname Add Edit
  x-api-slug: tumblr
  description: Edits a blog post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/img_logotype_34465d_2x.png
  humanURL: https://www.tumblr.com/
  baseURL: https://api.tumblr.com//v2///blog/{base-hostname}/post/edit
  tags: Blog, Base, Hostname, Post, Edit
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/blogbasehostnamepostedit-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/blogbasehostnamepostedit-post-openapi.md
- name: Tumblr Add Blog Base Hostname Add Reblog
  x-api-slug: tumblr
  description: Reblogs a post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/img_logotype_34465d_2x.png
  humanURL: https://www.tumblr.com/
  baseURL: https://api.tumblr.com//v2///blog/{base-hostname}/post/reblog
  tags: Blog, Base, Hostname, Post, Reblog
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/blogbasehostnamepostreblog-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/blogbasehostnamepostreblog-post-openapi.md
- name: Tumblr Add Blog Base Hostname Add Delete
  x-api-slug: tumblr
  description: Deletes a post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/img_logotype_34465d_2x.png
  humanURL: https://www.tumblr.com/
  baseURL: https://api.tumblr.com//v2///blog/{base-hostname}/post/delete
  tags: Blog, Base, Hostname, Post, Delete
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/blogbasehostnamepostdelete-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/blogbasehostnamepostdelete-post-openapi.md
- name: Tumblr Get User Dashboard
  x-api-slug: tumblr
  description: Use this method to retrieve the dashboard that matches the OAuth credentials
    submitted with the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/img_logotype_34465d_2x.png
  humanURL: https://www.tumblr.com/
  baseURL: https://api.tumblr.com//v2///user/dashboard
  tags: User, Dashboard
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/userdashboard-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/userdashboard-get-openapi.md
- name: Tumblr Get User Likes
  x-api-slug: tumblr
  description: Use this method to retrieve the liked posts that match the OAuth credentials
    submitted with the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/img_logotype_34465d_2x.png
  humanURL: https://www.tumblr.com/
  baseURL: https://api.tumblr.com//v2///user/likes
  tags: User, Likes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/userlikes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/userlikes-get-openapi.md
- name: Tumblr Get User Following
  x-api-slug: tumblr
  description: Use this method to retrieve the blogs followed by the user whose OAuth
    credentials are submitted with the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/img_logotype_34465d_2x.png
  humanURL: https://www.tumblr.com/
  baseURL: https://api.tumblr.com//v2///user/following
  tags: User, Following
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/userfollowing-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/userfollowing-get-openapi.md
- name: Tumblr Add User Follow
  x-api-slug: tumblr
  description: Follow a blog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/img_logotype_34465d_2x.png
  humanURL: https://www.tumblr.com/
  baseURL: https://api.tumblr.com//v2///user/follow
  tags: User, Follow
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/userfollow-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/userfollow-post-openapi.md
- name: Tumblr Add User Unfollow
  x-api-slug: tumblr
  description: Unfollow a blog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/img_logotype_34465d_2x.png
  humanURL: https://www.tumblr.com/
  baseURL: https://api.tumblr.com//v2///user/unfollow
  tags: User, Unfollow
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/userunfollow-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/userunfollow-post-openapi.md
- name: Tumblr
  x-api-slug: tumblr
  description: Tumblr, is a microblogging platform, emphasizing ease of use, that
    allows users to post text, images, videos, links, quotes and audio to their tumblelog,
    a short-form blog. Users can follow other users, or choose to make their tumblelog
    private.The Tumblr API is currently in its version 2.0, and provides a RESTful
    API that takes advantage of a URI structured including version system(such as
    blog or user), and allows blog owners to use a custom tumblr blog URL or custom
    domains. The API uses OAuth for user authentication and all responses in JSON,
    with JSONP also available. The API provides access to Tumblr Blogs in addition
    to other characteristics like avatars, followers, photos, audio, video and other
    user related information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/img_logotype_34465d_2x.png
  humanURL: https://www.tumblr.com/
  baseURL: https://api.tumblr.com//v2/
  tags: Tumblr
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/tumblr/master/_listings/tumblr/openapi.md
x-common:
- type: x-apijson--authoritative
  url: http://apis.io/apisdef/legacy/tumblr.json
- type: x-base
  url: http://api.tumblr.com
- type: x-blog
  url: http://staff.tumblr.com/
- type: x-blog-rss
  url: http://staff.tumblr.com/rss
- type: x-crunchbase
  url: http://www.crunchbase.com/company/tumblr
- type: x-developer
  url: https://www.tumblr.com/docs/en/api/v2
- type: x-github
  url: https://github.com/tumblr
- type: x-transparency-report
  url: https://www.tumblr.com/transparency
- type: x-twitter
  url: https://twitter.com/tumblr
- type: x-website
  url: https://www.tumblr.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---