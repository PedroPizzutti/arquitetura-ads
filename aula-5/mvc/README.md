# Projeto MVC

Projeto de estudo de **Spring MVC + Thymeleaf + JPA + H2**.

## 1. Criar o projeto

Acesse o [Spring Initializr](https://start.spring.io/) e utilize:

- **Project:** Maven
- **Language:** Java
- **Spring Boot:** versão estável atual
- **Group:** `br.com.dominio`
- **Artifact:** `mvc`
- **Packaging:** Jar
- **Java:** 21

### Dependências

Adicionar:

- Spring Web
- Thymeleaf
- Spring Data JPA
- H2 Database
- Lombok
- Spring Boot DevTools

## 2. Abrir no VS Code

Abra a pasta do projeto no **VS Code**.

Recomenda-se instalar:

- Extension Pack for Java
- Spring Boot Extension Pack

## 3. Verificar a JDK

No terminal:

```powershell
java -version
javac -version
```

Ambos devem indicar a versão **21**.

No VS Code:

**Ctrl + Shift + P → Java: Configure Java Runtime**

Verifique se a JDK 21 está configurada.

## 4. Executar o projeto

No terminal, na raiz do projeto:

```powershell
.\mvnw.cmd spring-boot:run
```

Se aparecer algo semelhante a:

```text
Tomcat started on port 8080
Started MvcApplication
```

o projeto está configurado corretamente.

---
