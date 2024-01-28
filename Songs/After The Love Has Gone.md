---
tags: Song ⭐⭐⭐⭐ 
banner: "![[I Am (1979).jpg]]"
---
[Time:: 3:28]
[Artist:: [[Earth, Wind & Fire]] ]
[Genre:: Jazz]
[Played:: 2]
[Album:: [[I Am (1979)]]]
[Year:: 1979]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[After The Love Has Gone]]
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
		intensity: page["After_The_Love_Has_Gone"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
