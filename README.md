<html>
</html>
<head>
<meta charset="utf-8"/>
<style type ="text/css">
body{background-color:black;}
table{
background-color:yellow;
border:2 red solid;
}
</style>
<script type="text/javascript">
function toplama(){
var x = prompt("İlk sayiyi giriniz");
var y = prompt("İkinci sayiyi giriniz");
toplama1 = parseInt(x)+parseInt(y);
alert("Verdiğiniz sayıların toplamı = "+toplama1);
}
function carpma(){
var x = prompt("İlk sayiyi giriniz");
var y = prompt("İkinci sayiyi giriniz");
carpma1= x*y;
alert(carpma1);

}
function bolme(){
var x = prompt("İlk sayiyi giriniz");//girdi
var y = prompt("İkinci sayiyi giriniz");
bolme1= x/y;
alert("Verdiğiniz sayıların bölümü = "+bolme1);//sonucu uyarı şeklinde verir.

}
function cikarma(){
var x = prompt("İlk sayiyi giriniz");
var y = prompt("İkinci giriniz");
cikarma1= x-y;
alert("Verdiğiniz sayıların farkı"+cikarma1);

}
</script>
</head>
<body>
<form>
<table border=10 cellspacing=5 cellpadding=5><!--html bilgisi tabloya sınırlar,hücre arası boşluk hücre büyüklüğü gibi özellikler-->
<tr><th colspan=2> Cakma Hesap Makinesi</th></tr>
<tr>
<th><input type = "button" value="toplama" onclick="toplama()"</th><!--onclick ile istenilen şeyi butona basılınca aktif edebiliriz.Burada javascript ile tasarladığımız fonksiyonları çağırdık.
																	örneğin onlick="alert("butona bastın")" boyle kullanarak butona basınca butona bastın uyarısı verdirmeyeteneğinede sahip-->
<th><input type = "button" value="bolme" onclick="bolme()"</th>
</tr>
<tr>
<th><input type = "button" value="carpma" onclick="carpma()"/></th>
<th><input type = "button" value="cikarma" onclick="cikarma()"</th>
</tr>
</form>
</body>
