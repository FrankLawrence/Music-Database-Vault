---
tags: Album
banner: "![[Metallica (1997).jpg]]"
---
[Year:: 1997]
[Artist:: [[Metallica]]]
```dataview
TABLE FROM [[Metallica (1997)]]
```
```dataviewjs
const calendarData = {
  colors: {
    blue: ["#9ccfd8", "#5BAAB8", "#57A1BB", "#5da8c7", "#3e8fb0"]
  },
  entries: []
};

const albumSongs = dv.pages('"Songs"')
  .where(p => p.Album && p.Album.path && p.Album.path.includes("Metallica (1997)"))
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
