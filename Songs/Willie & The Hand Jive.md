---
tags: Song ⭐⭐ 
banner: "![[Time Pieces - The Best Of Eric Clapton (1974).jpg]]"
---
[Time:: 3:28]
[Artist:: [[Eric Clapton]] ]
[Genre:: Blues]
[Played:: 2]
[Album:: [[Time Pieces - The Best Of Eric Clapton (1974)]]]
[Year:: 1974]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Willie & The Hand Jive]]
````
  ```dataviewjs
const calendarData = { 
	colors: { 
		blue: ["#9ccfd8", "#5BAAB8", "#57A1BB", "#5da8c7", "#3e8fb0"] 
	}, 
	entries: [] 
}; 

for (let page of dv.pages('"Daily Notes"')) { 
	calendarData.entries.push({ 
		date: page.file.name, 
		intensity: page["Willie_Eyes_Without_A_Face_The_Hand_Jive"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
