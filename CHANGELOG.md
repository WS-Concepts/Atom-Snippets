## 2.3.0 - 12-01-18
- ADD Anchor External:
    - **NOTE:** `ext-link` will be dropped in favour of the new `a-ext` in future release.
    - `a-ext` will load full Anchor with the ext-link options.
- ADD source-picture since Atom now supports picture as snippet.
- ADD space-css, an html space value for css.
- ADD LESS if statement (Mixin/CSS Guard).
- ADD GitHub as social icon.
- RENAME snippets social to brands.
- IMP LESS each snippet:
    - renamed `each` to `for`.
    - added new `each` that will loop values via mixin to math scss version.
    - added `loop` function as snippet (simple version of for).
- IMP added space between icon-custom class `icon` and snippet variable.
- IMP Placeholder image:
    - For HTML version emptied alt tag for A11y reasons.
    - Changed color set from #52c/fff to #ccc/777. As the #52c didn't mix well with some project as placeholder color.
    - Changed name value from img to <img> to make it stand out more as an placeholder image.
- FIX SCSS debug snippet. The snippet didn't work, since Atom already used it for a comment. Changed from `debug` to `log.scss`.

## 2.2.1 - 05-11-17
- FIX states focus

## 2.2.0 - 05-11-17
- DEL unneeded unicode symbols
- IMP placeholder snippet size editing
- ADD trbl snippet
- ADD Picture full snippet
- IMP sourceJS as option for doc snippet

## 2.1.0 - 24-09-17
- ADD social snippets
- ADD to placeholder snippet option to change size

## 2.0.2 - 21-09-17
- FIX removed the . (class) from the tr and td in the tbuild

## 2.0.1 - 28-08-17
- FIX states var selection

## 2.0.0 - 11-08-17
- DEL support-css as it was unhandy with the default snippet
- RENAME linear-gradient to gradient and added linear as var option
- FIX focus selection of states snippet with default sign(&) since it is mostly used in SCSS, LESS
- FIX each-loop for LESS version as it was using the complex version also use for some mixin's
- MOVED Printr to debug snippets
- ADD to debug:
    - @debug (scss)
    - console.log (js)
- DEL list-desc as it was unhandy in practice, easer with an Emmet command
- RENAME fig to figure-full as this works better with default snippet
- DEL detsum-open and added it as a var to detsum
- RENAME detsum to details-full as this works better with default snippet
- ADD icon-custom to icons snippet
- RENAME placeholder for all versions to img-placeholder as this has less conflict with default code like padding

## 1.1.2 - 08-07-17
- Typo in uni snippet

## 1.1.1 - 08-07-17
- HTML new snippets added see README
- CSS new snippets added see README
- Unicode new snippets added see README
- docs added
- updated placehold.it to placeholder.com
- skipped version 1.1.0 do wrong use of apm publish in version 1.0.4

## 1.0.4 - 05-06-17
- First Release
- skipped versions do wrong use of apm publish
