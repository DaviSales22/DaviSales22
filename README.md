# Olá! Eu sou Davi Souza

Sou um entusiasta de Java, JS apaixonado por desenvolvimento de software. Este é o meu perfil do GitHub, onde compartilho meus projetos relacionados a Java, Spring Boot, JPA, Hibernate, React, JS, TS e outras tecnologias.

## Projetos Principais

### PicPaySimplificado

Breve descrição sobre o projeto, seu propósito e principais funcionalidades. Inclua informações relevantes, como:

- RESTful SPRING BOOT, JPA, REST
- Necessita apenas do POSTMAN ou semelhante

```java
// Exemplo de código
public class UserController {
	
	@Autowired
	private UserService userservice;
	@PostMapping
	public ResponseEntity<User> createUser(@RequestBody UserDTO user){
		User newUser = userservice.createUser(user);
		return new ResponseEntity<>(newUser, HttpStatus.CREATED); 
	}
	
	@GetMapping
	public ResponseEntity<List<User>> getAllUsers(){
		List<User> users = this.userservice.getAllUsers();
		return new ResponseEntity<>(users,HttpStatus.OK);
	}
}
```

### Contribuições
Estou aberto a contribuições e feedback! Se você encontrar algum problema nos meus projetos ou tiver sugestões de melhoria, por favor, crie uma issue ou envie um pull request. Sua colaboração é valiosa para mim.

### Contato
Se você quer entrar em contato, pode me encontrar nos seguintes lugares:

- [Instagram](https://www.instagram.com/davisalesouza/)
- [LinkedIn](https://www.linkedin.com/in/davi-sales-7a2304231/)

#### Ou mandar um email para contatosdavi0@gmail.com
