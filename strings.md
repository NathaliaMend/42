- O que é
- [Como declarar](#Como-declarar)
- [como saber quando a string acaba](#como-saber-quando-a-string-acaba)
- [como saber o tamanho da string](#como-saber-quando-a-string-acaba)



# O que é

ARRAY de chars.
```
{'a','m','o','r'};
```

# Como declarar
## Variavel

- Chaves sem o tamanho
```
int main (){
    char text[] = {'a','m','o','r'};
}
```

- Chaves COM o tamanho
```c
int main (){
    char text[4] = {'a','m','o','r'};
}
```

- Ponteiro
```c
int main (){
    char *text = "amor";
}
```

## Parametro de funcao (ASSINATURA)

```c
int ft_algo (char text[]){
}
```

- Como se fosse ponteiro
```c
void ft_algo(char *txt) {
}
```

# como saber quando a string acaba

O final da string tem o char '\0'. Então vc pode fazer:

- Se vc declarar
```c
        char txt[] = "amor";
	int i = 0;

	while (txt[i] != '\0') // Enquanto n for final da string
	{
		printf("%c", txt[i]);
		i++;
	}
```


- Se receber por parametro
```c
void ft_algo(char txt[]) 
{
	int i = 0;
  
	while (txt[i] != '\0') // Enquanto n for final da string
	{
		printf("%c", txt[i]);
		i++;
	}
}
```

# como saber o tamanho da string
```c
#include <string.h>

int main (){
	char txt[] = "amor";
	int tamanho;
	tamanho = strlen(txt); // String lenght
}

```

