Anw01:
Speicheradresse von VariableA wird in r0 Geladen.
r0 hat nun die Adresse im RAM.

Anw02:
1 byte wird von r0 nach r2 geladen
r2 ist nun bei 0xef

Anw03:
r0 + 1 laden das byte in r3
r2 ist nun bei 0xef

Anw04:
r2 schiebt sich 8 Bits nach links

Anw05:
zwischen r2 und r3 findet eine oder-verknüfung stattt (ORR)

Anw06:
von r2 wird in r0 das halbwort zurückgeschrieben
in r0 sollte jetzt ef be zu be ef geworden sein.