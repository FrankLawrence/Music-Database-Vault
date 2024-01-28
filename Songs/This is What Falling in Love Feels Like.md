---
tags: Song ⭐⭐⭐⭐⭐ 

[Time:: 2:05]
[Artist:: [[JVKE]] ]
[Genre:: ]
[Played:: 22]
[Played:: 4]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[This is What Falling in Love Feels Like]]
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
		intensity: page["This_is_What_Falling_in_Love_Feels_Like"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
