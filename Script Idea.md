---
cssclass: cards, cards-cover, table-max, cards-1-1, cards-cols-4
---

```dataview
TABLE without id banner as Poster, file.link as Name, "" + year as Year, Artist, Genre as Genres, "Length: " + Time as Length, tags, Album from "Songs" 
WHERE banner != null AND Artist = [[ABBA]]
SORT file.name asc
```
