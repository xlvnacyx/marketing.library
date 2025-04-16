---
org: true
category: newsletter
icon: LiNewspaper
homepage: https://dirt.fyi
tags:
  - library
  - publication
  - newsletter
  - beehiiv
---

# articles
```dataview
LIST
FROM
    #library AND
    #article 
WHERE
    contains(publications, [[Dirt]])
```

# contributors
```dataview
LIST
FROM
    #library AND
    #author 
WHERE
    contains(publications, [[Dirt]])
```

