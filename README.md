<div align="center">
  
# 💰 Finance - Gestão de Finanças Pessoais

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue?style=flat-square&logo=python)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-4.2.5-darkgreen?style=flat-square&logo=django)](https://www.djangoproject.com/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

Uma aplicação web moderna para gestão de finanças pessoais, desenvolvida com Django e Bootstrap.

[Features](#-features) • [Instalação](#-instalação) • [Como Usar](#-como-usar) • [Rotas](#-rotas) • [Tecnologias](#-tecnologias)

</div>

---

## ✨ Features

- 📊 **Dashboard Intuitivo** - Visualize suas finanças em um só lugar
- 💳 **Gerenciamento de Contas** - Controle múltiplas contas bancárias
- 📝 **Registro de Transações** - Adicione entradas e saídas com categorias
- 💹 **Planejamento Financeiro** - Defina metas e acompanhe seu orçamento
- 📈 **Extrato Detalhado** - Visualize todas suas transações com filtros
- 📄 **Exportar em PDF** - Gere relatórios de extratos

---

## 🚀 Tecnologias

<div align="center">

![Python](https://img.shields.io/badge/Python-3776ab?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

</div>

---

## 📋 Pré-requisitos

- Python 3.9+
- pip (gerenciador de pacotes Python)
- Git

---

## 🔧 Instalação

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/Finance.git
cd Finance
```

### 2. Crie um ambiente virtual

```bash
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate
```

### 3. Instale as dependências

```bash
pip install -r requirements.txt
```

### 4. Execute as migrações

```bash
python manage.py migrate
```

### 5. Crie um superusuário (opcional)

```bash
python manage.py createsuperuser
```

### 6. Execute o servidor de desenvolvimento

```bash
python manage.py runserver
```

Acesse a aplicação em `http://127.0.0.1:8000/`

---

## 💡 Como Usar

### Página Inicial
Acesse a dashboard para visualizar um resumo de suas finanças:
- Saldo total
- Últimas transações
- Gastos por categoria

### Adicionar Transação
1. Vá para **Extrato → Novo Valor**
2. Preencha os dados:
   - Valor
   - Categoria
   - Descrição
   - Data
   - Conta
   - Tipo (Entrada/Saída)
3. Clique em **Salvar**

### Gerenciar Contas
1. Acesse **Contas → Ver Contas**
2. Visualize ou edite suas contas bancárias

### Planejamento
1. Acesse **Planejamento → Definir Planejamento**
2. Defina metas de gastos por categoria
3. Acompanhe seu progresso em **Ver Planejamento**

---

## 🛣️ Rotas Principais

| Rota | Descrição |
|------|-----------|
| `/perfil/home/` | Dashboard principal |
| `/perfil/gerenciar/` | Gerenciamento de categorias |
| `/perfil/dashboard/` | Visualização de gastos |
| `/contas/ver_contas/` | Gerenciar contas bancárias |
| `/extrato/novo_valor/` | Adicionar nova transação |
| `/extrato/view_extrato/` | Ver extrato de transações |
| `/planejamento/definir_planejamento/` | Definir orçamento |
| `/planejamento/ver_planejamento/` | Visualizar planejamento |
| `/admin/` | Painel administrativo |

---

## 📂 Estrutura do Projeto

```
Finance/
├── core/                 # Configurações do Django
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── asgi.py
├── perfil/              # App de perfil do usuário
├── extrato/             # App de transações e extratos
├── contas/              # App de gerenciamento de contas
├── planejamento/        # App de planejamento financeiro
├── templates/           # Templates HTML
├── static/              # Arquivos estáticos (CSS, JS, imagens)
├── manage.py
└── requirements.txt
```

---

## 🐛 Status do Projeto

### ✅ Concluído
- Dashboard e visualização de dados
- CRUD de contas, categorias e transações
- Filtros avançados de extrato
- Sistema de categorias

### 🔄 Em Progresso
- Integração com PDF (WeasyPrint)
- Melhorias na interface
- Relatórios avançados

### 📝 Melhorias Futuras
- [ ] Gráficos interativos com Chart.js
- [ ] Sincronização com contas bancárias reais
- [ ] Mobile responsivo
- [ ] Sistema de metas inteligentes com IA
- [ ] Exportação em múltiplos formatos

---

## 👤 Autor

Desenvolvido como projeto educacional no evento **Pythonando**.

---

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

<div align="center">

**[Voltar ao topo](#-finance---gestão-de-finanças-pessoais)**

</div>
