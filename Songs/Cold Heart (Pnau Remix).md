---
tags: Song ⭐⭐⭐⭐⭐ 
banner: "![[The Lockdown Session (2021).jpg]]"
---
[Time:: 4:14]
[Artist:: [[Elton John]] [[Dua Lipa]] ]
[Genre:: Disco]
[Played:: 32]
[Album:: [[The Lockdown Session (2021)]]]
[Year:: 2021]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Cold Heart (Pnau Remix)]]
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
		intensity: page["Cold_Heart_(Pnau_Remix)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
