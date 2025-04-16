---
org: true
category: 
icon: LiNewspaper
homepage: https://blog.beehiiv.com
tags:
  - library
  - publication
  - blog
  - beehiiv
---

# articles
```dataview
LIST
FROM
    #library AND
    #article 
WHERE
    contains(publications, [[beehiiv Blog]])
```

# contributor
```dataview
LIST
FROM
    #library AND
    #author 
WHERE
    contains(publications, [[beehiiv Blog]])
```

