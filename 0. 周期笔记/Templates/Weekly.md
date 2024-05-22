---
CreatedTime: <% tp.file.creation_date() %>
tags:
  - 周记
---


# 周度任务
- [ ] 洗衣服 📅 <% moment().startOf("week").add(2, "days").format("YYYY-MM-DD") %>
- [ ] 全屋打扫 📅 <% moment().startOf("week").add(2, "days").format("YYYY-MM-DD") %>

## 要事维度
```LifeOS
ProjectListByTime
```

## 角色维度
### 职员
- OKR
<%* let weekNum = Number(tp.file.title.match(/-W(\d\d)/)[1]); if (weekNum%2 !== 0) { -%>
- #工作/one-one 
	- [ ] 与 xxx #工作/one-one
<%* } -%>

### 丈夫

### 自己
- [ ] 规划下一周 📅 <% moment().endOf("week").format("YYYY-MM-DD") %>

# 复盘
## 本周收集
```LifeOS
TaskRecordListByTime
```

## 本周完成
```LifeOS
TaskDoneListByTime
```
