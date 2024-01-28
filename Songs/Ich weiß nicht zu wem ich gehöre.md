---
tags: Song  
banner: "![[Horizont (1986).jpg]]"
---
[Time:: 3:51]
[Artist:: [[Udo Lindenberg]] ]
[Genre:: German Rock-Pop]
[Played:: ]
[Album:: [[Horizont (1986)]]]
[Year:: 1986]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Ich weiß nicht zu wem ich gehöre]]
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
		intensity: page["Ich_weiß_nicht_zu_wem_ich_gehöre"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
