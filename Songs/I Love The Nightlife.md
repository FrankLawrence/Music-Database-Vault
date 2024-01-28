---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Pure Disco (1978).jpg]]"
---
[Time:: 3:07]
[Artist:: [[Alicia Bridges]] ]
[Genre:: Pop]
[Played:: 2]
[Album:: [[Pure Disco (1978)]]]
[Year:: 1978]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[I Love The Nightlife]]
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
		intensity: page["I_Love_The_Nightlife"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
