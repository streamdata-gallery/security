---
swagger: "2.0"
x-collection-name: Cisco Unity Connection Messaging Interface
x-complete: 0
info:
  title: Cisco PSIRT open Vuln Get Security Advisories Advisory Advisory
  description: Used to obtain an advisory in CVRF format for a given advisory ID `advisory_id`
    (i.e., cisco-sa-20150819-pcp)
  contact:
    name: Omar Santos
    email: os@cisco.com
  version: 0.0.3
host: api.cisco.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /security/advisories/cvrf/advisory/{advisory_id}:
    get:
      summary: Get Security Advisories Advisory Advisory
      description: Used to obtain an advisory in CVRF format for a given advisory
        ID `advisory_id` (i.e., cisco-sa-20150819-pcp)
      operationId: used-to-obtain-an-advisory-in-cvrf-format-for-a-given-advisory-id-advisory-id-i-e--ciscosa20150819pc
      x-api-path-slug: securityadvisoriescvrfadvisoryadvisory-id-get
      parameters:
      - in: path
        name: advisory_id
        description: advisory ID
      responses:
        200:
          description: OK
      tags:
      - Security
      - Advisories
      - Advisory
      - Advisory
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