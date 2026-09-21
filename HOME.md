# 工作台

[[00 Inbox/Capture|随手记]] · [[10 Journal/Action List|零散待办]] · [[90 System/工作台使用说明|使用说明]]

## 今天

```tasks
not done
(path includes 40 Projects/) OR (path includes 10 Journal/Action List.md) OR (path includes 00 Inbox/)
path does not include 40 Projects/Routines/
(scheduled today) OR (due today)
sort by due
sort by scheduled
hide toolbar
hide task count
hide postpone button
```

## 需要重排

```tasks
not done
(path includes 40 Projects/) OR (path includes 10 Journal/Action List.md) OR (path includes 00 Inbox/)
path does not include 40 Projects/Routines/
((scheduled before today) OR (due before today)) AND NOT ((scheduled today) OR (due today))
sort by due
sort by scheduled
hide toolbar
hide task count
hide postpone button
```

> [!todo]- 其他待办 · 展开查看
>
> ```tasks
> not done
> (path includes 40 Projects/) OR (path includes 10 Journal/Action List.md) OR (path includes 00 Inbox/)
> path does not include 40 Projects/Routines/
> NOT ((scheduled before tomorrow) OR (due before tomorrow))
> sort by due
> sort by scheduled
> hide toolbar
> hide task count
> hide postpone button
> group by filename
> ```
