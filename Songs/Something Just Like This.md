---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Memories...Do Not Open (2016).jpg]]"
---
[Time:: 4:27]
[Artist:: [[The Chainsmokers]] [[Coldplay]] ]
[Genre:: EDM]
[Played:: ]
[Album:: [[Memories...Do Not Open (2016)]]]
[Year:: 2016]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Something Just Like This]]
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
		intensity: page["Something_Just_Like_This"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
