---
name: User Story
about: Template for creating user story
title: ''
labels: ''
assignees: ''

---

**As a Customer of T&S Course**
**I need a voucher redeemer**
**so that i can have discount price when check out the course**

### Details and Assumptions
*  Database for the details of the voucher like the price and the validity period

### Acceptance Criteria

```gherkin
Given the customer are on the bill / payment detail page of the course product
when the customer fill the voucher 
Then it will cut the price according to the discount applied on the voucher
