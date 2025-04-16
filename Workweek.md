---
journal: true
category: newsletter
icon: LiNewspaper
homepage: https://workweek.com
tags:
  - library
  - publication
  - newsletter
---

# articles
```dataview
LIST
FROM
    #library AND
    #article 
WHERE
    contains(publications, [[Workweek]])
```

# contributor
```dataview
LIST
FROM
    #library AND
    #author 
WHERE
    contains(publications, [[Workweek]])
```

