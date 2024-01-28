---
tags: Song ⭐⭐⭐⭐ 
banner: "![[ABBA (1975).jpg]]"
---
[Time:: 3:17]
[Artist:: [[ABBA]] ]
[Genre:: Pop]
[Played:: 2]
[Album:: [[ABBA (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I Do, I Do, I Do, I Do, I Do]]
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
		intensity: page["I_Do,_I_Do,_I_Do,_I_Do,_I_Do"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
