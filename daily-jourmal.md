| Date | Weather | Moon |
| -- | -- | --  |
| [[本周总结]] | <% tp.user.getWeather() %> | <% tp.user.getMoon() %> |

<% tp.web.daily_quote() %>

**任务列表：**
```dataview
TASK
FROM "每日记录"
WHERE tags AND file.ctime <= date(today)
```

---

### 今天

#### 记录

#### 页面

#### 任务
