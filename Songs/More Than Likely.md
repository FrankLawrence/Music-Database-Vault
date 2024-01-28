---
tags: Song ⭐ 💔
banner: "![[At Worse...The Best Of Boy George And Culture Club (1993).jpg]]"
---
[Time:: 3:52]
[Artist:: [[Boy George & Culture Club with De La Soul]] ]
[Genre:: Rock]
[Played:: 1]
[Album:: [[At Worse...The Best Of Boy George And Culture Club (1993)]]]
[Year:: 1993]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[More Than Likely]]
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
		intensity: page["More_Than_Likely"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
