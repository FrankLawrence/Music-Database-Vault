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
		green: ["#c6e48b", "#7bc96f", "#49af5d", "#2e8840", "#196127"] 
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