# Auto Amazon Search

[🇧🇷 Português](#português) | [🇺🇸 English](#english)

---

## Português

Teste de automação web desenvolvido durante um treinamento corporativo em 2020, utilizando Ruby com o framework Cucumber e o padrão Page Objects (SitePrism).

O projeto realiza uma busca pelo livro "Código Limpo" no site da Amazon Brasil e valida se o resultado é exibido corretamente.

### Stack

- Ruby 2.6+
- Cucumber (BDD)
- Capybara
- SitePrism (Page Objects)
- Selenium WebDriver
- Report Builder

### Estrutura

```
├── features/
│   ├── clean_code.feature          # Cenário em Gherkin
│   ├── pages/
│   │   └── web_page.rb            # Page Object da Amazon
│   ├── step_definitions/
│   │   └── amazon_steps.rb        # Definição dos steps
│   └── support/
│       ├── env.rb                 # Configuração do Capybara
│       └── hooks.rb               # Hooks (screenshots, relatórios)
├── cucumber.yaml                   # Perfis do Cucumber
├── gemfile                         # Dependências
└── .gitattributes                  # Configuração do Linguist
```

### Como executar

```bash
# Instalar dependências
bundle install

# Executar os testes
cucumber
```

Os relatórios serão gerados em `cucumber_web_report.html` e `report.json`.

🔗 [Versão anterior do projeto (sem orientação a objetos)](https://github.com/lucasthomaz97/auto-amazon-search)

---

## English

Web automation test developed during a corporate training in 2020, using Ruby with the Cucumber framework and the Page Objects pattern (SitePrism).

The project searches for the book "Código Limpo" (Clean Code) on Amazon Brazil and validates that the result is displayed correctly.

### Stack

- Ruby 2.6+
- Cucumber (BDD)
- Capybara
- SitePrism (Page Objects)
- Selenium WebDriver
- Report Builder

### Project Structure

```
├── features/
│   ├── clean_code.feature          # Gherkin scenario
│   ├── pages/
│   │   └── web_page.rb            # Amazon Page Object
│   ├── step_definitions/
│   │   └── amazon_steps.rb        # Step definitions
│   └── support/
│       ├── env.rb                 # Capybara config
│       └── hooks.rb               # Hooks (screenshots, reports)
├── cucumber.yaml                   # Cucumber profiles
├── gemfile                         # Dependencies
└── .gitattributes                  # Linguist config
```

### How to run

```bash
# Install dependencies
bundle install

# Run tests
cucumber
```

Reports will be generated at `cucumber_web_report.html` and `report.json`.

🔗 [Previous version of the project (without OOP)](https://github.com/lucasthomaz97/auto-amazon-search)

---

*Projeto criado em 2020 como parte de um treinamento corporativo em automação de testes.*

*Project created in 2020 as part of a corporate training in test automation.*