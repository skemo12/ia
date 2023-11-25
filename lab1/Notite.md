# Lab1 A*

Dijstkra + euristica

f(s) = c(s) + h(s)

## Euristica

O **euristica** ne arata cat de aproape suntem in momentul actual de pozitia
finala dorita.

## Admisibila

O euristica ce nu supra-estimeaza, ci sub-estimeaza sau cel mult egala.

e.g. cost real = 10 -> h(s) <= 10
h(s) <= cost(s)

## Monotona

h(s) <= C(s,n) + h(n), unde n e nod intermediar

## Consistenta

h(s) <= drum_minim(s,n) + h(n)

Consitenta <==> Monotona (inafara de definitia tehnica)