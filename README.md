<b><h1>Tutorial para instalação do Laravel e criação de uma migration</h1></b>

<h2>- Instalação do Laravel:</h2>  
Rodar o comando: composer global require laravel/installer:<br>
<img width="534" height="337" alt="3" src="https://github.com/user-attachments/assets/dd9982fb-91c3-4fc6-82dc-fb9ab9cc868e" />  

Rodar o comando: laravel new (nome do projeto):<br>
<img width="559" height="275" alt="4" src="https://github.com/user-attachments/assets/d36a0e7b-b41b-4eb8-a1ae-10b35562ca51" /><br>
<img width="1101" height="872" alt="5" src="https://github.com/user-attachments/assets/a9ee682f-f76d-47b9-bb1e-d1636777fcc1" /><br>
Rodar os comados: npm install e npm run build:<br>
<img width="500" height="347" alt="6" src="https://github.com/user-attachments/assets/00d24e12-0d2f-4e4c-baa8-9b2f3112013a" /><br>
<br>

<h2>- Criação e execução das migrations:</h2>  
Configurar a conexão com o banco de dados no arquivo .env (caso você não tenha criado um banco de dados automaticamente na criação do projeto, faça um agora e confire apropriadamente o .env):<br>
<img width="238" height="134" alt="7" src="https://github.com/user-attachments/assets/4ec7b562-2155-457d-b950-3bc4e5189970" />

Utilize o comando php artisan make:migration create_alunos_table para criar o arquivo da migration:<br>
<img width="931" height="98" alt="8" src="https://github.com/user-attachments/assets/713566b4-a3b0-476b-a2a5-7e2ed4e64f6d" />

Personalize o código da nova migration para incluir os campos necessários(nome, telefone, email, motivo do contato e mensagem):<br>
<img width="581" height="619" alt="9" src="https://github.com/user-attachments/assets/7a546f1b-eeb9-4c7e-b5f4-bc0d2e745dde" />

Execute a migration com o comando php artisan migrate:<br>
<img width="1056" height="125" alt="10" src="https://github.com/user-attachments/assets/c01dc46f-dcf6-460f-9f86-9acc216e1576" />

Resultado no banco de dados:<br>
<img width="1917" height="705" alt="11" src="https://github.com/user-attachments/assets/ce386517-08c2-423c-b50d-e075b004de1b" />
