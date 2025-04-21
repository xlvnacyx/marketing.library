---
publication: true
category: newsletter
icon: LiLetterText
homepage: https://www.newsletteroperator.com
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
    contains(publications, [[Newsletter Operator]])
```

# contributors
```dataview
LIST
FROM
    #library AND
    #author 
WHERE
    contains(publications, [[Newsletter Operator]])
```

