# Лозинка

Потребно е да се симулира најава на еден систем. Притоа корисникот внесува корисничко име и лозинка. 
Доколку корисничкото име одговара со лозинката тогаш се печати Najaven, доколку не одговара се печати 
Nenajaven и на корисникот му се дава повторна шанса на корисникот да внесе корисничко име и лозинка.
Во моментот кога корисникот ќе биде најавен престануваат обидите за најава.

Влез: Прво се дава број N на кориснички имиња и лозинки кои ќе бидат внесени во системот. 
Во наредните N реда се дадени корисничките имиња и лозинки разделени со едно празно место. 
Потоа се даваат редови со кориснички имиња и лозинки на корисници кои се обидуваат да се најават 
(Пр. ana banana). 
За означување на крај на обидите во редицата се дава зборот KRAJ.

Излез: За секој од влезовите кои се обидуваат да се најават се печати Nenajaven се додека не 
добиеме Najaven или додека имаме обиди за најава.

Пример:
Влез: 3 ana banana pero zdero trpe trpi ana ana ana banana trpe trpi KRAJ
Излез: Nenajaven Najaven

Забелешка: Работете со хеш табела со затворени кофички. Самите решавате за големината на хеш табела, 
а хеш функцијата ви е дадена.

Input:
3
ana banana
pero zdero
trpe trpi
ana ana
ana bannana
trpe trpe
KRAJ

Output:
Nenajaven
Nenajaven
Nenajaven

Input:
6
ana banana
pero zdero
trpe trpi
ana bannana
mara shara
petre petle
ana ana
petre shara
trpe bannana
pero petle
KRAJ

Output:
Nenajaven
Nenajaven
Nenajaven
Nenajaven

Input:
6
ana banana
pero zdero
trpe trpi
ana bannana
mara shara
petre petle
marija more
mara more
KRAJ

Output:
Nenajaven
Nenajaven

Input:
6
ana banana
pero zdero
trpe trpi
ana bannana
mara shara
petre petle
shara mara
petle petre
pero zdero
KRAJ

Output:
Nenajaven
Nenajaven
Najaven

Input:
8
ana banana
pero zdero
trpe trpi
ana bannana
mara shara
petre petle
darko marko
marko darko
marko marko
mara mara
darko marko
marko darko
KRAJ

Output:
Nenajaven
Nenajaven
Najaven
Najaven

Input:
9
ana banana
pero zdero
trpe trpi
ana bannana
mara shara
petre petle
darko marko
marko darko
mitre mitre
mitra mitre
metri metra
mitre metri
mitra metri
metri mitro
KRAJ

Output:
Nenajaven
Nenajaven
Nenajaven
Nenajaven
Nenajaven

Input:
10
ana banana
pero zdero
trpe trpi
jana bannana
mara shara
petre petle
darko marko
marko darko
mitre mitre
mitra mitre
ana bannana
jana banana
mitra mitra
mitra mitre
KRAJ

Output:
Nenajaven
Nenajaven
Nenajaven
Najaven

Input:
1
ana banana
ana anna
ana ana
trpe trpi
admin admin
KRAJ

Output:
Nenajaven
Nenajaven
Nenajaven
Nenajaven


15
ana banana
pero zdero
trpe trpi
jana bannana
mara shara
petre petle
darko marko
marko darko
mitre mitre
mitra mitre
ana bannana
jana banana
mitra mitra
q q
aba bab
q qq
a a
mm aa
marra shara
jana bannana
pero mero
KRAJ

Output:
Nenajaven
Nenajaven
Nenajaven
Nenajaven
Nenajaven
Nenajaven