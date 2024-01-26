---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Rebel Yell (1983).jpg]]"
---
[Time:: 4:54]
[Artist:: [[Billy Idol]] ]
[Genre:: Rock]
[Played:: 105]
[Album:: [[Rebel Yell (1983)]]]
[Year:: 1983]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Eyes Without A Face]]
````

```dataviewjs
const calendarData = { 
	colors: { 
		blue: ["#9ccfd8", "#5BAAB8", "#57A1BB", "#5da8c7", "#3e8fb0"] 
	}, 
	entries: [] 
}; 

for (let page of dv.pages('"Daily Notes"').where(p => p.Eyes_Without_A_Face)) { 
	calendarData.entries.push({ 
		date: page.file.name, 
		intensity: page.Eyes_Without_A_Face
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```