---
org: true
category: newsletter
icon: LiNewspaper
homepage: https://www.creatorspotlight.com
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
    contains(publications, [[Creator Spotlight]])
```

# contributor
```dataview
LIST
FROM
    #library AND
    #author 
WHERE
    contains(publications, [[Creator Spotlight]])
```

 