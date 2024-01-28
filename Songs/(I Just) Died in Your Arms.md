---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Broadcast (1986).jpg]]"
---
[Time:: 4:31]
[Artist:: [[Cutting Crew]] ]
[Genre:: Pop Rock]
[Played:: 2]
[Album:: [[Broadcast (1986)]]]
[Year:: 1986]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[(I Just) Died in Your Arms]]
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
		intensity: page["(I_Just)_Died_in_Your_Arms"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
