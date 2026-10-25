# Assignment 2.4 — Solution

## Errors Found and Fixed

| No. | Error in buggy.html | Fix in index.html |
|-----|---------------------|-------------------|
| 1 | `<html>` has no `lang` attribute | Added `lang="en"` |
| 2 | Missing `<meta charset>` tag | Added `<meta charset="UTF-8">` |
| 3 | `<title>` tag not closed | Added `</title>` |
| 4 | `<h1>` closed with `</h2>` (wrong closing tag) | Changed to `</h1>` |
| 5 | Incorrect nesting: `<strong><em></strong></em>` | Corrected to `<strong><em></em></strong>` |
| 6 | Both `<p>` tags not closed | Added `</p>` |
| 7 | `<img>` missing `alt` attribute | Added `alt="Sample photo"` |
| 8 | `<a>` missing `href` attribute | Added `href="https://github.com/mrityunjay369"` |
| 9 | `<li>` tags not closed | Added `</li>` |
| 10 | `<div>` not closed | Added `</div>` |
| 11 | No indentation | Indented the whole code properly |

## Steps Followed
1. Opened `buggy.html` in the browser and inspected it using the Elements panel in DevTools.
2. Checked the markup with the W3C Markup Validator (validator.w3.org) and noted the errors.
3. Fixed all errors and indented the code properly.
4. Validated again and confirmed there were no errors.

## Code
- Before: [buggy.html](buggy.html)
- After: [index.html](index.html)

## Screenshots

### DevTools Elements panel (buggy page)


![DevTools](devtools-elements.png)



### Validator result


![Validator](validator-result.png)



### Fixed webpage


![Fixed page](fixed-page.png)
