---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Xanadu (From The Original Motion Picture Soundtrack) (1980).jpg]]"
---
[Time:: 3:47]
[Artist:: [[Electric Light Orchestra]] ]
[Genre:: Electronic, Pop, Stage & Screen]
[Played:: 98]
[Album:: [[Xanadu (From The Original Motion Picture Soundtrack) (1980)]]]
[Year:: 1980]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I'm Alive]]
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
		intensity: page["I'm_Alive"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
