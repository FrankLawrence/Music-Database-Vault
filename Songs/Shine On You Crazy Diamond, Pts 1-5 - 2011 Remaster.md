---
tags: Song
banner: "![[Wish You Were Here (Remastered Version) (1975).jpg]]"
---
[Time:: 13:30]
[Artist:: [[Pink Floyd]]]
[Genre:: ]
[Played:: 0]
[Album:: [[Wish You Were Here (Remastered Version) (1975)]]]
[Year:: 1975]
### Dates
```dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Shine On You Crazy Diamond, Pts 1-5 - 2011 Remaster]]
```

```dataviewjs
const calendarData = {
  colors: {
    blue: ["#9ccfd8", "#5BAAB8", "#57A1BB", "#5da8c7", "#3e8fb0"]
  },
  entries: []
};

for (let page of dv.pages('"Daily Notes"')) {
  let song = page["Shine_On_You_Crazy_Diamond,_Pts_1-5_-_2011_Remaster"];
  if (song) {
    calendarData.entries.push({
      date: page.file.name,
      intensity: song
    });
  }
}

renderHeatmapCalendar(this.container, calendarData);
```
