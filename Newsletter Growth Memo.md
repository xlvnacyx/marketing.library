---
publication: true
category: newsletter
icon: LiNewspaper
homepage: https://newslettergrowthmemo.beehiiv.com
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
    contains(publications, [[Newsletter Growth Memo]])
```

# contributors
```dataview
LIST
FROM
    #library AND
    #author  
WHERE
    contains(publications, [[Newsletter Growth Memo]])
```
