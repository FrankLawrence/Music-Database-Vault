---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[I Am a Photograph (1977).jpg]]"
---
[Time:: 4:13]
[Artist:: [[Amanda Lear]] ]
[Genre:: Pop]
[Played:: 4]
[Album:: [[I Am a Photograph (1977)]]]
[Year:: 1977]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Queen Of Chinatown]]
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
		intensity: page["Queen_Of_Chinatown"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
