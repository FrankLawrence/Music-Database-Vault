# Plays
```dataviewjs
const calendarData = {
  colors: {
    blue: ["#9ccfd8", "#5BAAB8", "#57A1BB", "#5da8c7", "#3e8fb0"]
  },
  entries: []
};

for (let page of dv.pages('"Daily Notes"')) {
  let totalPlays = 0;
  for (let meta of Object.values(page.file.frontmatter)) {
    totalPlays += meta;
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
# Song List
```dataview
TABLE Artist as Artist, Album as Album, Year as Year, Played as Plays, Time as Time, Genre as Genre, tags as Tags
FROM "Songs"
SORT Played desc
```