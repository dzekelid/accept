---
swagger: "2.0"
x-collection-name: Stack Exchange
x-complete: 1
info:
  title: Stack Exchange
  description: stack-exchange-is-a-network-of-130-qa-communities-including-stack-overflow-
  version: "2.0"
host: api.stackexchange.com
basePath: /2.2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{ids}/questions/unaccepted:
    get:
      summary: Get User Questions Unnacepted
      description: "Gets the questions asked by the users in {ids} which have at least
        one answer, but no accepted answer.\n \nQuestions returned by this method
        have answers, but the owner has not opted to accept any of them.\n \n{ids}
        can contain up to 100 semicolon delimited ids, to find ids programatically
        look for user_id on user or shallow_user objects.\n \nThe sorts accepted by
        this method operate on the follow fields of the question object:\n - activity
        - last_activity_date\n - creation - creation_date\n - votes - score\n  activity
        is the default sort.\n \n It is possible to create moderately complex queries
        using sort, min, max, fromdate, and todate.\n \nThis method returns a list
        of questions."
      operationId: gets-the-questions-asked-by-the-users-in-ids-which-have-at-least-one-answer-but-no-accepted-answer-q
      x-api-path-slug: usersidsquestionsunaccepted-get
      parameters:
      - in: query
        name: callback
        description: All API responses are JSON, we do support JSONP with the callback
          query parameter
      - in: query
        name: filter
        description: '#DiscussionThe Stack Exchange API allows applications to exclude
          almost every field returned'
      - in: query
        name: fromdate
        description: Unix date
      - in: path
        name: ids
        description: Number list (semicolon delimited)
      - in: query
        name: max
        description: sort = activity => datesort = creation => datesort = votes =>
          number
      - in: query
        name: min
        description: sort = activity => datesort = creation => datesort = votes =>
          number
      - in: query
        name: order
      - in: query
        name: page
      - in: query
        name: pagesize
      - in: query
        name: site
        description: Each of these methods operates on a single site at a time, identified
          by the site parameter
      - in: query
        name: sort
      - in: query
        name: todate
        description: Unix date
      responses:
        200:
          description: OK
      tags:
      - Users
      - Unaccepted
---