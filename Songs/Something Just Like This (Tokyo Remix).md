---
tags: Song ⭐⭐⭐ 
banner: "![[Kaleidoscope EP (2017).jpg]]"
---
[Time:: 4:27]
[Artist:: [[The Chainsmokers]] [[Coldplay]] ]
[Genre:: EDM]
[Played:: 2]
[Album:: [[Kaleidoscope EP (2017)]]]
[Year:: 2017]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Something Just Like This (Tokyo Remix)]]
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
		intensity: page["Something_Just_Like_This_(Tokyo_Remix)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
