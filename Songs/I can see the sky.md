---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Sleepless (2016).jpg]]"
---
[Time:: 3:25]
[Artist:: [[Breathe Carolina & Jay Cosmic]] [[Haliene]] ]
[Genre:: Dance]
[Played:: 26]
[Album:: [[Sleepless (2016)]]]
[Year:: 2016]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I can see the sky]]
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
		intensity: page["I_can_see_the_sky"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
