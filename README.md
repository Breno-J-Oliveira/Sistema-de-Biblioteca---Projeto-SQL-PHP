# 📚 Sistema de Biblioteca - Projeto SQL/PHP

<p align="center"> 
  <img src="https://img.shields.io/badge/status-concluído-green?style=for-the-badge" alt="Status do Projeto"> 
  <img src="https://img.shields.io/badge/versão-1.0-blue?style=for-the-badge" alt="Versão"> 
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white" alt="SQL"> 
</p>

---

## 🎯 Sobre o Projeto  

Este projeto consiste em um **sistema de biblioteca** desenvolvido com **SQL**, simulando o gerenciamento de livros, usuários e empréstimos.  
O objetivo é praticar **criação de tabelas**, **inserção, atualização, exclusão de dados**, além de **consultas** com filtros e ordenações, consolidando habilidades em **bancos de dados relacionais**.

---

## 🧩 Estrutura do Banco de Dados

### Tabelas Criadas:

1. **livros**  
   Armazena informações sobre os livros da biblioteca:
   - `id_livro` (PK)
   - `titulo`
   - `autor`
   - `genero`
   - `postagem` (data de postagem)

2. **usuario**  
   Armazena os usuários cadastrados:
   - `id_usuario` (PK)
   - `nome`
   - `email`
   - `tipousuario` (aluno, professor ou funcionário)

3. **emprestimos**  
   Registra os empréstimos realizados:
   - `id_emprestimos` (PK)
   - `id_usuario` (FK)
   - `id_livro` (FK)
   - `dataemprestimos`
   - `datadedevolucao`

---

## 🚀 Dados Inseridos

**Livros:**
- Adrenocromo - Dsluqui (Ficção)  
- Luzitas - diogocasacomigo (Romance)  
- A tropa da ak - MaiconKuster (Ficção)  
- Olavo de Carvalho - Olavo de Carvalho (Política)  
- Cancer - Zaneti (Medicina)  

**Usuários:**
- Clebin (Aluno)  
- Gordão da XJ (Funcionário)  
- Goatlipe (Professor)  

**Empréstimos:**
- Aluno 1 pegou o livro 2 (10/10 a 20/10)  
- Funcionário pegou o livro 4 (11/10 a 25/10)  
- Professor pegou o livro 1 (12/10 a 30/10)  

---

🧠 Explicação Técnica

Este projeto permite praticar:

Criação de tabelas e definição de tipos de dados (INT, VARCHAR, DATE, ENUM).

Chaves primárias e relacionamentos entre tabelas (FKs).

Inserção, atualização e exclusão de dados.

Consultas SQL com filtros (WHERE), ordenações (ORDER BY) e funções (MONTH()).

Gerenciamento de empréstimos e controle de dados de usuários e livros.

🛠 Tecnologias Utilizadas
<p align="center"> <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white" alt="SQL"> <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP"> </p>
🏆 Conclusão

O projeto serviu como exercício completo de SQL, consolidando conceitos de modelagem de dados, integridade referencial, consultas e manipulação de registros.

É uma base sólida para aplicações futuras de gerenciamento de bibliotecas ou qualquer sistema que envolva dados relacionais.

👤 Contatos
<p align="center"> <a href="https://github.com/Breno-J-Oliveira" target="_blank"> <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"> </a> <a href="https://www.linkedin.com/in/breno-j-oliveira-672619352/" target="_blank"> <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"> </a> <a href="https://www.instagram.com/brenot300" target="_blank"> <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"> </a> <a href="https://x.com/BrenoJOliveira_" target="_blank"> <img src="https://img.shields.io/badge/X-1DA1F2?style=for-the-badge&logo=x&logoColor=white" alt="X"> </a> </p> ```
