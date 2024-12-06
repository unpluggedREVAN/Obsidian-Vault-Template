### 📅 **Daily Log Template**

**Metadata**:

`created: "{{date}} {{time}}"   tags: ["Log/Daily"]   aliases: ["Daily Log {{date}}"]`  

#### **Day Overview**

- Goals:
- Meetings/Events:

#### **Tasks**

`TABLE description, status AS "Status", due-date AS "Due Date"   FROM "Tasks/Daily/{{date}}"   WHERE status != "Completed"   SORT priority DESC`  

#### **Reflection**

1. Wins of the day:
2. Challenges:
3. Improvements for tomorrow: