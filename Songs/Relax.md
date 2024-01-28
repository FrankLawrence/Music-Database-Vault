---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Now that's what I call music (1984).jpg]]"
---
[Time:: 3:54]
[Artist:: [[Frankie Goes To Hollywood]] ]
[Genre:: Rock/Pop]
[Played:: 35]
[Album:: [[Now that's what I call music (1984)]]]
[Year:: 1984]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Relax]]
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
		intensity: page["Relax"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
