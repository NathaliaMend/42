# Coisas basicas 

Declarando

```
int *pont;
int x = 10;

pont = &x;
```


|----|---|
|*p| Acessa o VALOR ou para alterar ou para pegar|
|p| Acessa o ENDERECO ou para alterar ou para pegar|


# Magias


```
int *pont;

pont = 42; // Nao funciona pois o ponteiro ainda n aponta pra nenhuma VARIVAEL/ENDERECO

// MAAAAGIIIIIAA
int pont = &(int){42}; // FUNCIONA pois aponta para un ENDERECO
```
