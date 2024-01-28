---
tags: Song  
banner: "![[1 (2000).jpg]]"
---
[Time:: 1:56]
[Artist:: [[The Beatles]] ]
[Genre:: ]
[Played:: ]
[Album:: [[1 (2000)]]]
[Year:: 2000]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[From Me To You]]
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
		intensity: page["From_Me_To_You"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
