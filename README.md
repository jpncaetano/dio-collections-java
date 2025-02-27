# 📚 Catálogo de Livros - Collections Java

📌 **Descrição**  
Este repositório contém a implementação de um **Catálogo de Livros**, desenvolvido como parte do módulo de **Collections Java** do **Bootcamp DIO - Claro**. O objetivo deste projeto é praticar o uso das principais estruturas de dados da **Java Collections Framework (JCF)**, como `List`, `Set` e `Map`, aplicando conceitos de organização, busca e manipulação de dados.

---

## 🚀 Funcionalidades  

✅ **Adicionar livros ao catálogo** com título, autor e ano de publicação.  
✅ **Remover livros** com base em critérios específicos.  
✅ **Buscar livros** pelo título ou pelo autor.  
✅ **Listar livros ordenados** de diferentes formas:  
  - Ordem de inserção  
  - Ordem alfabética (Título/Autor)  
  - Ordem cronológica (Ano de publicação)  

---

## 🛠️ Tecnologias Utilizadas  

- **Java 8+**  
- **Coleções (`List`, `Set`, `Map`)**  
- **Comparator e Comparable**  
- **Stream API**  
- **Maven** (para gerenciamento de dependências, se aplicável)  

---

## 🔧 Como Rodar o Projeto  

1. **Clone o repositório**  
   ```sh
   git clone https://github.com/jpncaetano/dio-collections-java.git
   cd dio-collections-java
   ```

2. **Compile e execute a aplicação**  
   ```sh
   mvn clean package
   java -jar target/catalogo-livros.jar
   ```

   Ou, caso esteja rodando sem um empacotamento Maven, execute diretamente via:  
   ```sh
   javac -d bin src/main/java/*.java
   java -cp bin Main
   ```

---

## 📜 Licença  

Este projeto foi desenvolvido para fins educacionais no Bootcamp **DIO - Claro**. Sinta-se à vontade para explorar e modificar o código.  

📩 **Contato:** Caso tenha dúvidas ou sugestões, entre em contato pelo GitHub.  
