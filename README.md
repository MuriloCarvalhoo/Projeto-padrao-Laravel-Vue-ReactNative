## CRUD PERFEITO

-   Esse projeto tem a finalidade de criar um padrão de projeto utilizando todos os recursos disponivel do laravel e seguindos as melhores praticas 

- [Melhores práticas](https://github.com/jonaselan/laravel-best-practices).
- [Código limpo: Habilidades práticas do Agile Software - Autor: Robert C. Martin](l1nq.com/y2W5j).


### REQUISITOS 

- **[PHP 8.2](https://www.php.net/downloads)**
- **[MARIA DB 10.10.2](https://mariadb.org/download)**
- **[MARIA DB 2.4.54](https://httpd.apache.org/download.cgi)**


### FRAMEWORK E BIBLIOTECAS 

- **[LARAVEL 8](https://laravel.com/docs/9.x)**
- **[VUE 2](https://vuejs.org/guide/introduction.html)**
- **[REACT NATIVE]**


### RECURSOS 

- FORM REQUEST VALIDATION - PARA VALIDAR DADOS RECEBIDOS VIA REQUEST
- Eloquent: API Resources - TRANSFORMAR O ELOQUENT GERADO PARA RESPOSTAS JSON
- Error Handling - Criar tratamento de erros personalizadas


### ARQUITETURA

- TABELA USERS: {
    id,
    name,
    cpf,
    email,
    tipo_id,
    ativo,
}

-  TABELA POSTS: {
    id,
    user_id,
    title,
    body,
}
