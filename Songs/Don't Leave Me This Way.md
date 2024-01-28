---
tags: Song ⭐⭐⭐ 
banner: "![[Pure Disco (1976).jpg]]"
---
[Time:: 3:36]
[Artist:: [[Thelma Houston]] ]
[Genre:: Pop]
[Played:: ]
[Album:: [[Pure Disco (1976)]]]
[Year:: 1976]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Don't Leave Me This Way]]
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
		intensity: page["Don't_Leave_Me_This_Way"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
