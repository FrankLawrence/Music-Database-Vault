---
tags: Song ⭐⭐⭐⭐ 
banner: "![[Astronaut in the Ocean (2019).jpg]]"
---
[Time:: 2:12]
[Artist:: [[Masked Wolf]] ]
[Genre:: Hip-Hop/Rap]
[Played:: 16]
[Album:: [[Astronaut in the Ocean (2019)]]]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Astronaut in the Ocean]]
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
		intensity: page["Astronaut_in_the_Ocean"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
