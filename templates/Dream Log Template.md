---
date: <% tp.date.now("YYYY-MM-DD") %>
type: <% await tp.system.suggester(["Dream", "Nightmare", "Various"], ["dream", "nightmare", "various"]) %>
---
<% await tp.file.rename(tp.date.now("YYYY-MM-DD")) -%>
## What Happened?

<% tp.file.cursor(1) %>