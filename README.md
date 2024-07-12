Examples for the work to add `reading-flow` to the [CSS Display 4 specification](https://drafts.csswg.org/css-display-4/#reading-flow).

To try these out, install Chrome Dev or Canary (version 128 or higher) and launch it using the [command line flag](https://developer.chrome.com/docs/web-platform/chrome-flags#command-line_flags) `CSSReadingFlow`. For example, on a Mac:

```
/Applications/Google\ Chrome\ Canary.app/Contents/MacOS/Google\ Chrome\ Canary --enable-features=CSSReadingFlow
```

## Grid examples

- [Grid with `grid-template-areas`, `reading-flow: grid-row`](/grid-placement-row.html)

## Flex examples

### Writing mode horizontal-tb, dir ltr

- [Flex with order modifications, `reading-flow: flex-flow`](/flex-flow-with-order.html)
- [Flex with order modifications, `reading-flow: flex-flow`, `flex-direction: row-reverse`](/flex-flow-with-order-reverse.html)
- [Flex with order modifications, `reading-flow: flex-visual`, `flex-direction: row-reverse`](/flex-visual-with-order-reverse.html)
- [Flex with `row-reverse`, `reading-flow: flex-visual`](/flex-row-reverse-visual.html)

### Writing mode horizontal-tb, dir rtl

- [Flex with order modifications, rtl, `reading-flow: flex-flow`, `flex-direction: row-reverse`](/flex-flow-with-order-reverse-rtl.html)
- [Flex with order modifications, rtl, `reading-flow: flex-visual`, `flex-direction: row-reverse`](/flex-visual-with-order-reverse-rtl.html)


### Writing mode vertical-lr

- [Flex with order modifications, `reading-flow: flex-flow`](/flex-flow-with-order-vertical-lr.html)
- [Flex with `row-reverse`, `reading-flow: flex-visual`](/flex-row-reverse-visual-vertical-lr.html)
