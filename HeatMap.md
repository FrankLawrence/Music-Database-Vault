```dataviewjs
const calendarData = { 
	colors: { 
		green: ["#c6e48b", "#7bc96f", "#49af5d", "#2e8840", "#196127"] 
	}, 
	entries: [] 
}; 

for (let page of dv.pages('#Songs').where(p => p.Heatmap)) { 
	calendarData.entries.push({ 
		date: page.file.name, 
		intensity: page.Heatmap 
	}); 
} 

renderHeatmapCalendar(this.container, calendarData);
```