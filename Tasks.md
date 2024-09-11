## Todo
```tasks
not done
is not blocked
status.name includes todo
filter by function !task.tags.includes("#reading")
group by path reverse
```

## Todo (blocked)
```tasks
not done
is blocked
status.name includes todo
filter by function !task.tags.includes("#reading")
group by path reverse
```

## Done this week
```tasks
done this week
status.name includes done
filter by function !task.tags.includes("#reading")
group by function reverse task.done.format("YYYY[%%]-MM[%%] MMM [- Week] WW")
sort by done reverse
```


## Done this month
```tasks
done this month
status.name includes done
filter by function !task.tags.includes("#reading")
group by function reverse task.done.format("YYYY[%%]-MM[%%] MMM [- Week] WW")
```


## Done last month
```tasks
done last month
status.name includes done
filter by function !task.tags.includes("#reading")
group by function reverse task.done.format("YYYY[%%]-MM[%%] MMM [- Week] WW")
```
