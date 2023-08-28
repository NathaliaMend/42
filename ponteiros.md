# Coisas basicas 

Declarando

```c
int *pont;
int x = 10;

pont = &x;
```

Exemplo| O que faz
|----|---|
*p | Acessa o VALOR ou para alterar ou para pegar
p  | Acessa o ENDERECO ou para alterar ou para pegar


# Erros

bus error => Iniciou um ponteiro mas precisa apontar para um endereço, cria uma variavel aleatoria so pra ter um endereço 


# Magias


```c
int *pont;

pont = 42; // Nao funciona pois o ponteiro ainda n aponta pra nenhuma VARIVAEL/ENDERECO

// MAAAAGIIIIIAA
int pont = &(int){42}; // FUNCIONA pois aponta para un ENDERECO
```
