---
tags: Song ⭐⭐⭐⭐⭐ 💛
banner: "![[Deep in Abyss (Made in Abyss) - Single (2019).jpg]]"
---
[Time:: 3:43]
[Artist:: [[Miyu Tomita & Mariye Ise]] ]
[Genre:: Pop]
[Played:: 54]
[Album:: [[Deep in Abyss (Made in Abyss) - Single (2019)]]]
[Year:: 2019]
### Dates
````dataview
TABLE Favorite_Song
WHERE Favorite_Song = [[Deep in Abyss (Anime Intro Version)]]
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
		intensity: page["Deep_in_Abyss_(Anime_Intro_Version)"]
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```
