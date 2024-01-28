---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Just Another Way To Say I Love You (1975).jpg]]"
---
[Time:: 3:33]
[Artist:: [[Barry White]] ]
[Genre:: R&B]
[Played:: 30]
[Album:: [[Just Another Way To Say I Love You (1975)]]]
[Year:: 1975]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[What Am I Gonna Do With You]]
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
		intensity: page["What_Am_I_Gonna_Do_With_You"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
