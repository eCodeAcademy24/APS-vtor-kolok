# Преведувач

Треба да изработите автоматски преведувач за зборови од анлиски јазик на македонски. Влезот се состои од парови од зборови 
разделени со празно место. Така прво е даден зборот на македонски, па има едно празно место, па преводот на зборот на англиски 
јазик. Потоа на влез се добиваат странски зборови (секој во посебен ред). За излез треба да се преведат овие зборови. 
Доколку не е познат преводот на зборот на излез се печати "/"

Влез. Прво се дава број N на поими кои ќе ги содржи речникот. Потоа во наредните N реда се дадени поимите, прв на македонски,
потоа на англиски. Потоа следуваат зборови на англиски (секој збор во посебен ред), кои треба да се преведат на македонски. 
За означување на крај во редицата се дава зборот KRAJ

Излез. За секој од дадените зборови на англиски во посебен ред е даден преводот на зборот на македонски. Доколку не е познат преводот на 
зборот се печати /

Забелешка. Работете со хеш табела со отворени кофички. Сами треба да го одредите бројот на кофички и хеш функцијата.

Име на класа: Preveduvac

Input:
5
machka cat
kuche dog
prase pig
papagal parrot
riba fish
cat
parrot
fish
KRAJ

Output:
machka
papagal
riba

Input:
6
machka cat
kuche dog
prase pig
papagal parrot
riba fish
zmija snake
snake
zmija
doog
dog
KRAJ

Output:
zmija
/
/
kuche

Input:
5
tigar tiger
puma puma
lav lion
kamila camel
nosorog rhinoceros
cat
camel
tiger
KRAJ

Output:
/
kamila
tigar

Input:
6
zebra zebra
kokoshka hen
pile chicken
zajak rabbit
bik bull
slon elephant
rabit
bul
elephant
KRAJ

Output:
/
/
slon

Input:
6
koza goat
mravka ant
mechka bear
shkolka shell
gushter lizard
crv worm
warm
beard
got
KRAJ

Output:
/
/
/
