# Quesito della Susi (Settimana enigmistica N° 23/2023)

```
Trovare la negazione della frase "Umberto ha almeno un figlio non biondo"
```

${Xu}$ = {Tutti i figli di Umberto}

${Au}$ = {Tutti i figli di Umberto non biondi}

${Bu}$ = {Tutti i figli di Umberto biondi}

${A}$ = {Tutti i figli non biondi}

${B}$ = {Tutti i figli biondi}

${0}$ = Insieme vuoto

# 

Data il seguente:
```
Umberto ha almeno un figlio non biondo
```

vuol dire che l'intersezione dell'insieme dei figli di umberto con l'insieme dei figli non biondi è diverso dall'insieme vuoto:

(1) ${Xu}$ $\cap$ ${A}$ $\neq$ ${0}$

Negare la preposizione vuol dire che tale intersezione è uguale all'insieme vuoto:

(2) ${Xu}$ $\cap$ ${A}$ = ${0}$

Tenendo conto che 

(3) ${Xu}$ = ${Au}$ $\cup$ ${Bu}$ 

e sostituendolo alla precedente:

(4) (${Au}$ $\cup$ ${Bu}$) $\cap$ ${A}$ = ${0}$

dove

(5) (${Au}$ $\cup$ ${Bu}$) $\cap$ ${A}$ = ${Au}$

ovvero

(6) ${Au}$ = ${0}$

cioè: 

```
{Tutti i figli di Umberto non biondi} = {0}
```

Quindi ricordando la (3)

${Xu}$ = ${Au}$ $\cup$ ${Bu}$ 

${Xu}$ = ${0}$ $\cup$ ${Bu}$ = ${Bu}$

che equivale a 

```
 Tutti figli di Umberto sono biondi oppure non ha figli (se Bu = 0)
```

