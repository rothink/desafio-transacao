# Desafio - Transaction

- Clonar repositório
    > 
        git clone https://github.com/rothink/desafio-transaction.git


- Entrar no repositório clonado
    > 
        cd desafio-transaction


- Subir os serviços com docker
    > 
        docker-compose up --build -d


- Install migration
    > 
        docker exec -it picpay_back php artisan migrate:fresh  --seed

- Install passport laravel
  >
        docker exec -it picpay_back php artisan passport:install        

- Executar os testes 
    >  
        docker exec -it picpay_back php artisan test
        
- Swagger API
    >  
        http://localhost:8000/api/documentation
        
        --------------------------------------
        
        Login
        
        email: comum@user.com
        password: 123456

- Aplicação
    >  
        http://localhost:8080
        
        Na tela de login, basta clicar no botão para auto preenchimento do formulário.
        Ex:
        
        Para entrar como usuário comum, clique no botão escrito: USUÁRIO COMUM.
        Para entrar como usuário lojista, clique no botão escrito: USUÁRIO LOJISTA.

        
