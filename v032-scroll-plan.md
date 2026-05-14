# V0.3.2 Scroll UX Fix Plan

The current `sort-v03.html` test page uses an iframe to preserve `index.html`. On iPhone/Safari, this keeps the header sticky and prevents the floating top button from reliably appearing.

The durable fix is to promote the sort code into the actual app document instead of running the app inside an iframe. This should be done by merging the sort controls into `index.html` after the feature is confirmed stable.
