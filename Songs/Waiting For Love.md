---
tags: Song
banner: "![[Stories (2015).jpg]]"
---
[Time:: 3:50]
[Artist:: [[Avicii]]]
[Genre:: ]
[Played:: 0]
[Album:: [[Stories (2015)]]]
[Year:: 2015]
### Dates
```dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Waiting For Love]]
```

```dataviewjs
const calendarData = {
  colors: {
    blue: ["#9ccfd8", "#5BAAB8", "#57A1BB", "#5da8c7", "#3e8fb0"]
  },
  entries: []
};

for (let page of dv.pages('"Daily Notes"')) {
  let song = page["Waiting_For_Love"];
  if (song) {
    calendarData.entries.push({
      date: page.file.name,
      intensity: song
    });
  }
}

renderHeatmapCalendar(this.container, calendarData);
```
