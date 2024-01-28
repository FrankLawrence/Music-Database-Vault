---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Küssen verboten (1992).jpg]]"
---
[Time:: 2:27]
[Artist:: [[Die Prinzen]] ]
[Genre:: German Rock-Pop]
[Played:: 11]
[Album:: [[Küssen verboten (1992)]]]
[Year:: 1992]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Ich brauch Dich gar nicht mehr]]
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
		intensity: page["Ich_brauch_Dich_gar_nicht_mehr"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
