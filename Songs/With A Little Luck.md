---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[All The Best (1987).jpg]]"
---
[Time:: 3:13]
[Artist:: [[Paul McCartney]] ]
[Genre:: Pop]
[Played:: 43]
[Album:: [[All The Best (1987)]]]
[Year:: 1987]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[With A Little Luck]]
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
		intensity: page["With_A_Little_Luck"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
