---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[Stark Wie Zwei (2008).jpg]]"
---
[Time:: 4:17]
[Artist:: [[Udo Lindenberg]] ]
[Genre:: German Rock-Pop]
[Played:: 12]
[Album:: [[Stark Wie Zwei (2008)]]]
[Year:: 2008]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Was Hat Die Zeit Mit Uns Gemacht]]
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
		intensity: page["Was_Hat_Die_Zeit_Mit_Uns_Gemacht"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
