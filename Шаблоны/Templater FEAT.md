<%* let featName = await tp.system.prompt("Название FEAT"); %>

<%*
// Определение id фичи по названию раздела
let idNumber = tp.file.title.slice(0, tp.file.title.indexOf(" ")).replaceAll(".", "");
idNumber = (idNumber.length < 3) ? idNumber + "0" : idNumber;
%>

---
## FEAT-<% idNumber %>-000 <% featName %>

**Макеты:**

