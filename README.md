# Roberta Attorre

Landing page estática e responsiva de pré-lançamento para **Roberta Attorre**.

## Endereços

- Site principal: `https://robertaattore.com/`
- Subdomínio do portfólio: `https://roberta.w7ti.com/`

## Execução local

O projeto não exige compilação. Sirva a pasta com qualquer servidor HTTP estático, por exemplo:

```powershell
python -m http.server 8088
```

Depois acesse `http://localhost:8088/`.

## Estrutura

- `index.html`: conteúdo e metadados.
- `assets/site.css`: apresentação responsiva e animações acessíveis.
- `assets/roberta-hero.png`: imagem editorial original da página.
- `docs/FUNCIONALIDADES.md`: documentação funcional e operacional.

## Produção

Na infraestrutura do portfólio, o diretório é publicado no contexto Tomcat `/robertaattorre/`. O balanceador redireciona a raiz dos dois domínios para esse contexto.
