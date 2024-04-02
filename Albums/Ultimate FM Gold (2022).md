---
tags: Album
banner: "![[Ultimate FM Gold (2022).jpg]]"
---
[Year:: 2022]
[Artist:: [[Limahl]]]
```dataview
TABLE FROM [[Ultimate FM Gold (2022)]]
```
```dataviewjs
const calendarData = {
  colors: {
    blue: ["#9ccfd8", "#5BAAB8", "#57A1BB", "#5da8c7", "#3e8fb0"]
  },
  entries: []
};

const albumSongs = dv.pages('"Songs"')
  .where(p => p.Album && p.Album.path && p.Album.path.includes("Ultimate FM Gold (2022)"))
  .map(p => {
  let songTitle = p.file.name.split(".")[0];
  return songTitle.replace(/ /g, "_");
});
for (let page of dv.pages('"Daily Notes"')) {
  let totalPlays = 0;
  for (let song of albumSongs) {
    totalPlays += page[song] || 0;
  }
  if (totalPlays > 0) {
    calendarData.entries.push({
      date: page.file.name,
      intensity: totalPlays
    });
  }
}

renderHeatmapCalendar(this.container, calendarData);
```
