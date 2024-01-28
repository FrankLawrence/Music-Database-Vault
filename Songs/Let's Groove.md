---
tags: Song ⭐⭐⭐⭐ 💛
banner: "![[Raise! (1981).jpg]]"
---
[Time:: 3:55]
[Artist:: [[Earth, Wind & Fire]] ]
[Genre:: Funk]
[Played:: 19]
[Album:: [[Raise! (1981)]]]
[Year:: 1981]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Let's Groove]]
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
		intensity: page["Let's_Groove"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
