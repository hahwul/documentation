# Search

The `Search` tab provides a comprehensive view of all the requests that have been generated by tools, such as the Replay and Automate features, in addition to requests that are proxied through Caido via Intercept.

Search differs from other tools in Caido in that way - as the other tabs do not list any request generated by Automate and Replay.

This extra inclusion allows you to sort through the results of all your testing using other Caido features in a single location.

<img alt="Search overview." src="/_images/search_tab.png" center/>
<br>

> PRO FEATURE

An HTTPQL query search bar is available within Search for Caido Pro users.

## Filtering

Additional default Filter Presets in the `Advanced options` panel are included to display/exclude traffic generated by Replay and Automate. Within this panel are also options to filter by the following:

- The source of the requests (implicit OR).
- The status code of the responses (implicit OR).
- The presets to use (implicit AND).

::: info
There is an implicit AND in between each of those sections.
:::

View the [Filters](../overview/filters.md) documentation for more information.

<img alt="Advanced search options" src="/_images/search_adv_menu.png" center/>

::: tip

- Clicking the column names (_located at the top and spanning horizontally_) within the top request list pane will sort the requests by the selected column category. View the [Sorting by Properties](../overview/sorting.md) documentation for more information.

:::