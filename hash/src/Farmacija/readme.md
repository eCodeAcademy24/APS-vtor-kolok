# Фармација

Во магацинот на една фармацевска компанија се чуваат најразлични видови лекови. За секој лек потребно е да се чуваат 
податоци за името на лекот, цената во денари и намената на лекот. За поефикасен пристап до податоците за лековите, 
фармацевската компанија одлучила податоците да ги чува во CBHT табела каде се сместуваат соодветните податоци.

Хеш табелата е достапна до крајните клиенти и истите може да пребаруваат низ внесените податоци. Бидејќи на пазарот 
постојат повеќе лекови кои таргетираат иста болест, најчесто клиентите го бараат оној лек кој има најниска цена. 
Па вашата задача е со користење на хеш табелата, за дадена намена (болест), да го испечатите лекот кој има најниска цена 
на пазарот. Доколку бараната намена во магацинот нема лек се печати "Нема лек за бараната намена во магацин"

Влез:
Најпрво е даден бројот на лекови N, а потоа секој лек е даден во нов ред во форматот:

"Име на лек" "Намена" "Цена во денари"

На крај е дадена намената за која треба да се пронајде лекот со најниска цена.

Излез:

Името на лекот со најмала цена.

Пример:

Влез:
5
Analgin Glavobolka 80
Daleron Glavobolka 90
Lineks Bolki_vo_stomak 150
Spazmeks Bolki_vo_stomak 150
Loratadin Alergija 150
Glavobolka

Излез:
Analgin