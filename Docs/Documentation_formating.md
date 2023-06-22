# Formatação da documentação no código

### Variáveis
```Python
    '''tipo:função da variável

        opicionalmente tendo uma observação sobre a variável se necessário. '''
```

### Funções
```Python
    '''Descrição breve da Função

        Parameters:
            Enumera os paramentros da função no formato:
            nome(tipo):Função da vaiável.

        Returns:
            Descrição do retorno da função no formato:
           (tipo do retorno):valor do retorno
    '''
```

### Excessões
```Python
    '''
    Raises:
        AttributeError: A sessão ``Raises`` é a lista de excessões
            muito relevante para a interfaces
        ValueError: se `param2` é igual a `param1`.
            |                   |
    Valor do erro       Condição do erro
    '''
```

#### Referências: 
https://sphinxcontrib-napoleon.readthedocs.io/en/latest/example_google.html
