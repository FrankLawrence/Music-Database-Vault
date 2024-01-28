---
tags: Song ⭐⭐⭐ 
banner: "![[Pure Disco (1978).jpg]]"
---
[Time:: 3:17]
[Artist:: [[Gloria Gaynor]] ]
[Genre:: Pop]
[Played:: 1]
[Album:: [[Pure Disco (1978)]]]
[Year:: 1978]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I Will Survive]]
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
		intensity: page["I_Will_Survive"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
