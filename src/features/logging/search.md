# Search

The Search feature provides a comprehensive view of all the requests that have been generated by tools, such as the automate and replay features, in addition to requests that are proxied through Caido. The Search page is similar to the [HTTP History](/features/proxy/intercept.md) page, with the same layout and scoping options but different filtering.

<img alt="Search overview" src="/_images/search.png" no-shadow/>

## Filtering

> **PRO FEATURE**

The filtering is using our new query language [HttpQL](/internals/httpql.md).

To avoid having to always some very common filters, we also offer an `Advanced` panel that allows you to select:

- The `source` of the requests (implicit `OR`)
- The `status code` of the responses (implicit `OR`)
- The `presets` to use (implicit `AND`)

There is an implicit `AND` in between each of those sections.

<img height="500" alt="Advanced search options" src="/_images/search_advanced.png" center/>