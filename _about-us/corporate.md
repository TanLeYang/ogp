---
title: Corporate team
permalink: /about-us/corporate
---

## **Corporate Team**

{%- assign people = site.data.people | where_exp: "staff", "staff.function == 'finance' or staff.function == 'workplace'" -%}
{% include people-of-OGP.html people=people color=site.colors.function-colors.corporate %}