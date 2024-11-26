Как достать значение и текст из <select> блока:
let a = document.getElementById('selectBlockId');
console.log(a.value) и console.log(a.options[a.selectedIndex].text)


Если нужно выбрать определенные цвета для диаграммы PIE в eCharts, то нужно назначить
свои цвета в series (color: ["blue","red"]), а порядок их распределения зависит от порядка в легенде:
(shiftReadyLegend = [{name : 'Загрузка'}, {name : 'Простой'}]
