---
layout: bidder
title: Trion Interactive
description: Prebid Trion Interactive Bidder Adaptor
hide: true
biddercode: trion
biddercode_longer_than_12: false
---



### bid params

{: .table .table-bordered .table-striped }
| Name        | Scope    | Description                                | Example                             | Type     |
|-------------|----------|--------------------------------------------|-------------------------------------|----------|
| `pubId`     | required | publisher Id provided by Trion Interactive | `'111111'`                          | `string` |
| `sectionId` | required | section Id provided by Trion Interactive   | `'11'`                              | `string` |
| `re`        | optional | click through redirect                     | `'http://clicktrackingurl.com?re='` | `string` |
