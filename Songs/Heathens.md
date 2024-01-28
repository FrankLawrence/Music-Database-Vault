---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Suicide Squad: The Album (2016).jpg]]"
---
[Time:: 3:38]
[Artist:: [[Twenty One Pilots]] ]
[Genre:: Rap Rock]
[Played:: 6]
[Album:: [[Suicide Squad: The Album (2016)]]]
[Year:: 2016]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Heathens]]
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
		intensity: page["Heathens"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
