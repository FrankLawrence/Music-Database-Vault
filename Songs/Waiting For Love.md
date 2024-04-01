---
tags: Song
---
[Time:: 3:50]
[Artist:: [[Avicii]]]
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
  let song = page["Waiting For Love"];
  if (song) {
    calendarData.entries.push({
      date: page.file.name,
      intensity: song
    });
  }
}

renderHeatmapCalendar(this.container, calendarData);
```
