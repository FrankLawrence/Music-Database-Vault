---
tags: Song  
banner: "![[Horizont (1986).jpg]]"
---
[Time:: 4:35]
[Artist:: [[Udo Lindenberg]] ]
[Genre:: German Rock-Pop]
[Played:: 1]
[Album:: [[Horizont (1986)]]]
[Year:: 1986]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Sie brauchen keinen Führer]]
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
		intensity: page["Sie_brauchen_keinen_Führer"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
