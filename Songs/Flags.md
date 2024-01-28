---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Everyday Life (2019).jpg]]"
---
[Time:: 3:37]
[Artist:: [[Coldplay]] ]
[Genre:: Pop Rock]
[Played:: 54]
[Album:: [[Everyday Life (2019)]]]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Flags]]
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
		intensity: page["Flags"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
