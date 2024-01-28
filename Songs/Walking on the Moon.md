---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Reggatta de Blanc (1979).jpg]]"
---
[Time:: 5:01]
[Artist:: [[The Police]] ]
[Genre:: Reggae]
[Played:: 23]
[Album:: [[Reggatta de Blanc (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Walking on the Moon]]
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
		intensity: page["Walking_on_the_Moon"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
