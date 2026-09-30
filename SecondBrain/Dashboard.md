---
tags:
  - dashboard
---
# Dashboard

## Recent Mistakes
```dataview
TABLE file.mtime AS "Last updated", tags FROM #mistake SORT file.mtime DESC
```

## DSA Notes
```dataview
LIST FROM #dsa SORT file.name ASC
```

## Recently Modified Notes
```dataview
TABLE file.mtime AS "Modified", tags FROM "" SORT file.mtime DESC LIMIT 10
```
