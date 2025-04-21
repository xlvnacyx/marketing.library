---
publication: true
category: newsletter
icon: LiLetterText
homepage: https://workweek.com/discover-newsletters/contentment-newsletter/
tags:
  - library
  - publication
  - newsletter
---

# stories
```dataview
LIST
FROM
    #library AND
    !#author
WHERE
    contains(publications, [[Contentment]])
```

# contributors
```dataview
LIST
FROM
    #library AND
    #author 
WHERE
    contains(publications, [[Contentment]])
```

