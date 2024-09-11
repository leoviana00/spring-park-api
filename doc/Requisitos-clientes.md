## Requisitos / Clientes

```console
O cadastro de cliente só será possível depois de realizado o cadastro como usuário. Um
usuário poderá ter apenas um único cadastro como cliente e um cliente poderá estar
vinculado a um único usuário.
```
 
- Todas as ações necessitam de autenticação
- O cadastro vai conter dados como nome completo
- O cadastro vai conter um cpf (deve ser único)
- O cadastro deve estar vinculado ao usuário.
- O cliente deverá realizar um cadastro com o nome completo e cpf.
    - Apenas o cliente está autorizado.
- Um cliente poderá ser localizado pelo identificador gerado no cadastro.
    - Apenas o administrador está autorizado.
- Um administrador poderá listar todos os clientes.
- O cliente poderá recuperar os próprios dados via token.
- Documentar todos os recursos criados.
- Realizar testes de integração do tipo ponto a ponto (end-to-end) dos recursos criados.