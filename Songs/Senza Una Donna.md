---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[The Best Of Zucchero (1987).jpg]]"
---
[Time:: 4:27]
[Artist:: [[Zucchero]] ]
[Genre:: Rock/Pop]
[Played:: 7]
[Album:: [[The Best Of Zucchero (1987)]]]
[Year:: 1987]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Senza Una Donna]]
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
		intensity: page["Senza_Una_Donna"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
