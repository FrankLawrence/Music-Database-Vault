---
tags: Song ⭐⭐ 
banner: "![[Scoundrel Days (1986).jpg]]"
---
[Time:: 3:43]
[Artist:: [[A-ha]] ]
[Genre:: Pop Rock]
[Played:: 1]
[Album:: [[Scoundrel Days (1986)]]]
[Year:: 1986]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[We're Looking for the Whales]]
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
		intensity: page["We're_Looking_for_the_Whales"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
