---
tags: Song  
banner: "![[Reach the Beach (1983).jpg]]"
---
[Time:: 3:16]
[Artist:: [[The Fixx]] ]
[Genre:: New Wave]
[Played:: 1]
[Album:: [[Reach the Beach (1983)]]]
[Year:: 1983]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[One Thing Leads To Another]]
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
		intensity: page["One_Thing_Leads_To_Another"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
