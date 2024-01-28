---
tags: Song ⭐⭐⭐ 
banner: "![[Kissing To Be Clever (1982).jpg]]"
---
[Time:: 4:29]
[Artist:: [[Culture Club]] ]
[Genre:: Rock]
[Played:: 9]
[Album:: [[Kissing To Be Clever (1982)]]]
[Year:: 1982]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Do You Really Want To Hurt Me]]
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
		intensity: page["Do_You_Really_Want_To_Hurt_Me"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
