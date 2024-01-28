---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Pure Disco (1978).jpg]]"
---
[Time:: 3:45]
[Artist:: [[The Village People]] ]
[Genre:: Pop]
[Played:: 2]
[Album:: [[Pure Disco (1978)]]]
[Year:: 1978]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Y.M.C.A.]]
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
		intensity: page["Y.M.C.A."]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
