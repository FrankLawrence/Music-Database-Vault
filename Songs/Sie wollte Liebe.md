---
tags: Song  
banner: "![[Horizont (1986).jpg]]"
---
[Time:: 3:50]
[Artist:: [[Udo Lindenberg]] ]
[Genre:: German Rock-Pop]
[Played:: 1]
[Album:: [[Horizont (1986)]]]
[Year:: 1986]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Sie wollte Liebe]]
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
		intensity: page["Sie_wollte_Liebe"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
