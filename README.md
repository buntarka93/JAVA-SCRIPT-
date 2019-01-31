# JAVA-SCRIPT-
<meta charset="utf-8">
<script>

var money = parseInt(prompt('summa vklada : '));
var prosent = parseInt(prompt('Procentnaya stavka,  %  : '));
var years = parseInt(prompt('Srok vklada, let  : '));

for (var i=1; i<=years; i++) {
	money= money+money*prosent/100;
	alert(Прошло лет '+ i +','сумма на счету' + Math.floor(money));
}
</script>
 
