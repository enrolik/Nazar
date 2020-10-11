# Nazar
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewpoint" content="width=device-width, initial-scale=1.0">
    <title>Lesson 1</title>
    
  </head>
   <body>
<div id="welcome"></div>


<script>//приветствие
const name = prompt('Введите свое имя и фамилию');
alert('Привет,'+name)
    </script>

<script>//год
const year = new Date(2020);
const birth = prompt ('Введите год рождения');
    alert ('твой возраст: '+(year - birth));
    </script>

<script>//квадрат
const dlina = prompt('Введите длину стороны квадрата');
const P = (dlina*4);
const S =(dlina**2);
alert('Периметр =' + P  + ' Площадь =' + S);
    </script>

<script>//площадь круга
const r = prompt('Введите радиус');
const S1=(Math.PI*r**2);
var qq = S1.toFixed(2);
alert('Площадь окружности '+qq);
    </script>

<script>//скорость
const S2 = prompt('Введите расстояние в км между двумя городами ');
const T = prompt('Ведите за сколько часов вы хотите добраться ');
alert('Вы должны двигатся со скоростью '+S2/T +' км/час');
    </script>

<script>//конвертор валют
const USD = 28.21; const EUR=33.38; 
const UA = prompt('Введите сумму в ГРН ');
alert('USD: '+(USD*UA)+' EUR: '+(EUR*UA));
    </script>

<script>//флешка
let f1= 820;
const GB = prompt('Введите объем USB-флешки в ГБ ');
const FGB = (f1 / GB);
var a = Math.floor(FGB);
alert('На USB-флешку вмещается '+ a +' файлов, размером 820 мб');
    </script>

<script>//шоколадки
const money=prompt('Введите сколько у вас денег в грн ');
const choc=prompt('Введите цену шоколадки');
var kolich=(money/choc);
var ko = Math.floor(kolich);

const ost = (money-(ko*choc));
var os = ost.toFixed(2);

alert ('Вы можете купить '+ ko +' шоколадок, '+'у вас осталось ' + os + ' грн');
    </script>

  <script>
const tri=prompt('Введите трехзначное число');

function getReversedNum(tri) {
  let result = 0;
  while (tri) {
    result = result * 10 + tri % 10;
    tri = Math.floor(tri / 10);
  }

  return result;
}
alert('ваше число наоборот '+(getReversedNum(tri)));
  </script>


    <script src="app/main.js"></script>
   </body>
</html>
