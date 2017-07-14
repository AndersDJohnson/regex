# regex
Regular expressions.

## JSON Unescaped Quotes
Find unescaped quotes in JSON strings, and escape them.

```
("\s*:\s*".*[^\\])"(.*")
```
to:
```
$1\\"$2
```

## JS Arrow Function Single Argument

```
\(([^\(\)\{\},=]+)\)(\s*=>)
```
to:
```
$1$2
```
