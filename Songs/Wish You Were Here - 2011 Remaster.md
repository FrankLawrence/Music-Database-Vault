---
tags: Song
banner: "![[Wish You Were Here (Remastered Version) (1975).jpg]]"
---
[Time:: 5:04]
[Artist:: [[Pink Floyd]]]
[Genre:: ]
[Played:: 0]
[Album:: [[Wish You Were Here (Remastered Version) (1975)]]]
[Year:: 1975]
### Dates
```dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Wish You Were Here - 2011 Remaster]]
```

```dataviewjs
const calendarData = {
  colors: {
    blue: ["#9ccfd8", "#5BAAB8", "#57A1BB", "#5da8c7", "#3e8fb0"]
  },
  entries: []
};

for (let page of dv.pages('"Daily Notes"')) {
  let song = page["Wish_You_Were_Here_-_2011_Remaster"];
  if (song) {
    calendarData.entries.push({
      date: page.file.name,
      intensity: song
    });
  }
}

renderHeatmapCalendar(this.container, calendarData);
```
