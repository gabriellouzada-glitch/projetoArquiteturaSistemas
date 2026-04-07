# Sistema CRUD Trio

Projeto acadêmico em Java orientado a objetos com 3 cadastros CRUD:

- Produtos
- Clientes
- Funcionários

## Requisitos

- Java 21
- Maven 3.9+

## Como executar

```bash
mvn spring-boot:run
```

Acesse no navegador:

- http://localhost:8080

## Estrutura

- `src/main/java/br/com/trio/sistema/model` -> entidades de domínio
- `src/main/java/br/com/trio/sistema/controller` -> controllers MVC
- `src/main/java/br/com/trio/sistema/service` -> regras de negócio e estratégias de validação
- `src/main/java/br/com/trio/sistema/repository` -> abstração e implementação de repositório em memória
- `src/main/java/br/com/trio/sistema/config` -> configuração de serviços e fábrica

## Artefatos solicitados

- Documento simplificado: `DOCUMENTO_SISTEMA.md`
- Implementação: código completo neste repositório
- Explicação dos padrões GoF e GRASP: `PADROES_GOF_GRASP.md`

## Checklist de entrega AVA

1. Subir este projeto no GitHub com nome da equipe.
2. Gerar prints das telas:
   - Tela inicial
   - Lista e formulário de Produtos
   - Lista e formulário de Clientes
   - Lista e formulário de Funcionários
3. Enviar no AVA:
   - Link do repositório GitHub
   - Prints das telas
   - Documento simplificado (pode anexar o `DOCUMENTO_SISTEMA.md` exportado em PDF, se solicitado)
