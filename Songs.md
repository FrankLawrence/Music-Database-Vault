```dataview
TABLE Artist as Artist, Album as Album, Year as Year, Played as Plays, Time as Time, Genre as Genre, tags as Tags
FROM "Songs"
SORT Played desc
```