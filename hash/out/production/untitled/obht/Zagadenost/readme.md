# Квалитет на воздух

Дадени се мерења на PM10 честички за населбите во Скопје. Вашата задача е за дадена населба да се најде просечната концентрација на PM10 честички.

Влез:
Во првиот ред од влезот е даден бројот на мерења (N≤10,000), а во секој нареден ред е дадена населбата и концентрацијата на PM10 честички, разделени со празно место. 
Во последниот ред е дадена населбата за која треба да ја најдете просечната концентрација на PM10 честички.

Излез:
Просечната концентрација на PM10 честички за дадената населба (заокружена на 2 децимали).

Ограничувања:

Не е дозволено користење на помошни структури како низи или слично. Единствена структура на располагање е хеш структура.

Помош:
За заокружување во Java може да се користи следниот код:

DecimalFormat df = new DecimalFormat("######.##");
double a = 335.453333;
df.format(a);

Input:
8  
Centar 319.61  
Karposh 296.74  
Centar 531.98  
Karposh 316.44  
GaziBaba 384.05  
GaziBaba 319.3  
Karposh 393.18  
GaziBaba 326.42  
Karposh

Output:
335.45  