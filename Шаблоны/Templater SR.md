<%*
// Определение id требования по названию раздела
let idNumber = tp.file.title.slice(0, tp.file.title.indexOf(" ")).replaceAll(".", "");
idNumber = (idNumber.length < 3) ? idNumber + "0" : idNumber;
%>
### SR-<% idNumber %>-000-000

**Теги:** <% await tp.system.suggester(["Crit", "High", "Mid", "Low"], ["#priority/crit", "#priority/high", "#priority/mid", "#priority/low"]) %>  **Источник:** BR | Стейкхолдер

**Ревизия:** <% tp.date.now("DD.MM.YYYY") %>

Требование

