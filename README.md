Как достать значение и текст из <select> блока:
let a = document.getElementById('selectBlockId');
console.log(a.value) и console.log(a.options[a.selectedIndex].text)

Если нужно выбрать определенные цвета для диаграммы PIE в eCharts, то нужно назначить
свои цвета в series (color: ["blue","red"]), а порядок их распределения зависит от порядка в легенде:
(shiftReadyLegend = [{name : 'Загрузка'}, {name : 'Простой'}]

Замена с помощью регулярных выражений: например нужно все вхождения class="my-class" заменить на className={my-class},
тогда нужно в Visual Code нажать Ctrl-H, включить режим Regex, в строку что меняем ввести: class="([^"]+)", в строку на что
меняем ввести: className={$1}

Работа с датой в JavaScript: например есть строка "2024-12-11" и нужно представить в виде "11 декабря 2024 г.":
const str = '2024-12-11'
const options = {
  year: 'numeric',
  month: 'long',
  day: 'numeric',
};
const formattedDate = new Intl.DateTimeFormat('ru-RU', options).format(new Date(str));
Это работает и со строками типа timestamp "2024-11-30T14:29:42.782046"
