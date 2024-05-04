```dataview
TABLE WITHOUT ID
Favorite_Song as Favorite, length(rows) as "Favorite Song Count"
WHERE Favorite_Song
GROUP BY Favorite_Song
SORT length(rows) desc
```