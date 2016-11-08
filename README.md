# regex
Regular expressions.

## JSON Unescaped Quotes
Find unescaped quotes in JSON strings, and escape them.

`("\s*:\s*".*[^\\])"(.*")` => `$1\\"$2`
