# 🕵️‍♂️ Case #001: The Vanished Briefcase

## 🔍 Summary

![Summary](../assets/Case1.png)

```sql
SELECT *
FROM interviews AS i
JOIN suspects AS s
ON i.suspect_id = s.id
WHERE s.scar="left cheek"
AND s.attire="trench coat"
```
