---
tags: Song  
banner: "![[Pure Disco (1978).jpg]]"
---
[Time:: 3:46]
[Artist:: [[Diana Ross]] ]
[Genre:: Pop]
[Played:: 1]
[Album:: [[Pure Disco (1978)]]]
[Year:: 1978]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Love Hangover]]
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
		intensity: page["Love_Hangover"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
