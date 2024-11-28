# Projeto SauceDemo - Testes Automatizados com Playwright

Este é um projeto de automação de testes para o site [SauceDemo](https://www.saucedemo.com/), desenvolvido com **Playwright** e escrito em **JavaScript**. O objetivo do projeto é validar funcionalidades principais do site.


# 📝 Funcionalidades Testadas

## Login

1. Login com credenciais válidas.
2. Login com credenciais inválidas.
3. Login com campos em branco.
4. Login com usuário bloqueado.

## Fluxo de Compra
5. Adiciona itens ao carrinho
6. Faz o checkout preenchendo os campos obrigatórios
7. Finaliza a compra e valida que a mensagem de sucesso aparece.

## Filtros
8. Filtra os produtos por nome e por preço.
9. Valida se o primeiro produto listado após o filtro é o esperado.

## Logout
10. Clica no menu lateral.
11. Valida que o botão de logout está visível.
12. Executa o logout.


## Instalação e Configuração

 **Clone o repositório:**
   ```bash
   git clone https://github.com/EstevaoCabral/playwright-sauce-demo.git 
```                                                                   

## Instale as dependências
```bash
    npx install 
```

## Executando os Testes
```bash
    npx playwright test
```

### Executar um teste específico
```bash
    npx playwright test tests/login.spec.js
```

### Executar testes com relatório interativo
```bash
    npx playwright show-report
```

