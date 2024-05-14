---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Everyday Life (2019).jpg]]"
---
[Time:: 4:42]
[Artist:: [[Coldplay]] ]
[Genre:: Soft Rock]
[Played:: 17]
[Album:: [[Everyday Life (2019)]]]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Trouble In Town]]
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
		intensity: page["Trouble_In_Town"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
