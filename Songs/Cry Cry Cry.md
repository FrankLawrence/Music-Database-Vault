---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Everyday Life (2019).jpg]]"
---
[Time:: 2:54]
[Artist:: [[Coldplay]] ]
[Genre:: Soft Rock]
[Played:: 39]
[Album:: [[Everyday Life (2019)]]]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Cry Cry Cry]]
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
		intensity: page["Cry_Cry_Cry"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
