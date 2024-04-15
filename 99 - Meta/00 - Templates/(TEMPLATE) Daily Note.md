---
date: <%tp.date.now("YYYY-MM-DD")%>T<%tp.date.now("HH:mm")%>
tags:
  - daily
cssclasses:
  - daily
  <% "- " + tp.date.now("dddd", 0, tp.file.title, "YYYY-MM-DD").toLowerCase() %>
---

# Daily Note
## <% tp.date.now("dddd, MMMM Do, YYYY", 0, tp.file.title, "YYYY-MM-DD") %>
***
### Notes
