---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Give My Regards to Broad Street (1984).jpg]]"
---
[Time:: 4:40]
[Artist:: [[Paul McCartney]] ]
[Genre:: Rock]
[Played:: 17]
[Album:: [[Give My Regards to Broad Street (1984)]]]
[Year:: 1984]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[No More Lonely Nights]]
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
		intensity: page["No_More_Lonely_Nights"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
