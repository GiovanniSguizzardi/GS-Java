# GS-Java
Repositório criado para armazenar todos os arquivos e assuntos, sobre a globalsolution de JavaAdvanced.

## Instruções para acessos e testes | Eventos
Para fazer os testes no POSTMAN, siga essas etapas:

- Método GET | Eventos:
```bash
  http://localhost:8080/eventos
```

- Método GET | BuscarId:
```bash
  http://localhost:8080/eventos/buscarid/id
```
 
- Método POST | Add
```bash
  http://localhost:8080/eventos/add

{
    "titulo": "Teste",
    "descricao": "Teste",
    "data_inicio": "2024-06-01",
    "data_fim": "2024-06-10",
    "local": "Teste",
    "url": "www.Teste.com.br"
}
```

- Método PUT | Atualizar:
```bash
  http://localhost:8080/eventos/atualizar/id
```

- Método DEL | Delete:
```bash
  http://localhost:8080/eventos/delete/id
```
## Instruções para acessos e testes | Artigos
Para fazer os testes no POSTMAN, siga essas etapas:

- Método GET | Artigos:
```bash
  http://localhost:8080/artigos
```

- Método GET | BuscarId:
```bash
  http://localhost:8080/artigos/buscarid/id
```
 
- Método POST | Add
```bash
  http://localhost:8080/artigos/add

{
    "titulo": "Corais Marinhos",
    "conteudo": "Corais marinhos estao em grave perigo na costa Brasileira",
    "autor": "Giovanni Sguizzardi",
    "data_publicacao": "2024-06-02",
    "visualizacoes": 2535
}
```

- Método PUT | Atualizar:
```bash
  http://localhost:8080/artigos/atualizar/id
```

- Método DEL | Delete:
```bash
  http://localhost:8080/artigos/delete/id
```
## Instruções para acessos e testes | Usuarios
Para fazer os testes no POSTMAN, siga essas etapas:

- Método GET | Usuarios:
```bash
  http://localhost:8080/usuarios
```

- Método GET | BuscarId:
```bash
  http://localhost:8080/artigos/usuarios/id
```
 
- Método POST | Add
```bash
  http://localhost:8080/usuarios/add

{
    "nome": "Tobias",
    "email": "Tobias@gmail.com",
    "senha": "1234567Tobias",
    "data_criacao": "2024-04-02"
}
```

- Método PUT | Atualizar:
```bash
  http://localhost:8080/usuarios/atualizar/id
```

- Método DEL | Delete:
```bash
  http://localhost:8080/usuarios/delete/id
```
