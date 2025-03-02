---
title: console.timeStamp()
slug: Web/API/console/timeStamp
tags:
  - API
  - DOM
  - Debugging
  - Method
  - Non-standard
  - Web Development
  - web console
browser-compat: api.console.timeStamp
---
{{APIRef("Console API")}}{{Non-standard_header}}

The **`console.timeStamp`** method adds a single marker to the browser's [Performance](https://developer.chrome.com/docs/devtools/evaluate-performance/reference/)
or [Waterfall](https://firefox-source-docs.mozilla.org/devtools-user/performance/waterfall/index.html) tool. This lets you
correlate a point in your code with the other events recorded in the timeline, such as
layout and paint events.

You can optionally supply an argument to label the timestamp, and this label will then
be shown alongside the marker.

{{AvailableInWorkers}}

## Syntax

```js
timeStamp(label);
```

### Parameters

- `label`
  - : Label for the timestamp. Optional.

## Browser compatibility

{{Compat}}

## See also

- {{domxref("console.time()")}}
- {{domxref("console.timeEnd()")}}
- [Adding timestamps to the waterfall](https://firefox-source-docs.mozilla.org/devtools-user/performance/waterfall/index.html#timestamp_markers)
