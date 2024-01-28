---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Attack on Titan Original Soundtrack ().jpg]]"
---
[Time:: 5:27]
[Artist:: [[Linked Horizon]] ]
[Genre:: J-Pop]
[Played:: 8]
[Album:: [[Attack on Titan Original Soundtrack ()]]]
[Year:: ]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Jiyū No Tsubasa (Der Flügel der Freiheit)]]
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
		intensity: page["Jiyū_No_Tsubasa_(Der_Flügel_der_Freiheit)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
