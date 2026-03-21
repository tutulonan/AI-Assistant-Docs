<%* let reqName = await tp.system.prompt("Название BR"); %>

<%*
// Определение id требования по названию раздела
let idNumber = tp.file.title.slice(0, tp.file.title.indexOf(" ")).replaceAll(".", "");
idNumber = (idNumber.length < 3) ? idNumber + "0" : idNumber;
%>
### BR-<% idNumber %>-000 <% reqName %>

**Источник:** –

**Ревизия:** <% tp.date.now("MM.YYYY") %>

Текст требования
