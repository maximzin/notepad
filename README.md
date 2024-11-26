Как достать значение и текст из <select> блока:
let a = document.getElementById('selectBlockId');
console.log(a.value) и console.log(a.options[a.selectedIndex].text)
