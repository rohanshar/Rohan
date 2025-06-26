```dataview
TASK
FROM "50000 Feet/Projects Todo"
WHERE contains(tags, "#computer") AND !completed
SORT file.name ASC
```