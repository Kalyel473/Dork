# 📌 GERADOR DE DORKS PARA SQL INJECTION — ULTRA MAX

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/Security-Educational-red?style=for-the-badge&logo=hackthebox">
  <img src="https://img.shields.io/badge/Platform-Linux%20%7C%20Windows%20%7C%20Mac-success?style=for-the-badge">
</p>

---

## 🔥 Sobre a Ferramenta

O **GERADOR DE DORKS PARA SQL INJECTION - ULTRA MAX** é uma ferramenta educacional desenvolvida em Python para gerar automaticamente Google Dorks relacionados a possíveis vulnerabilidades de **SQL Injection**.

A ferramenta combina:

* 📌 Parâmetros vulneráveis comuns
* 📌 Mensagens de erro SQL
* 📌 Padrões de URLs dinâmicas
* 📌 Erros específicos de bancos de dados
* 📌 Combinações inteligentes para pesquisa avançada

Ideal para:

* 🎓 Estudos de Pentest
* 🛡️ Treinamentos de Segurança
* 🔎 Laboratórios CTF
* 🧪 Ambientes autorizados de teste

---

# ⚠️ Aviso Legal

> Esta ferramenta foi criada exclusivamente para fins educacionais e testes autorizados.

O uso indevido desta ferramenta contra sistemas sem autorização explícita é ilegal.

O autor não se responsabiliza por quaisquer danos ou ações realizadas por terceiros.

---

# ✨ Funcionalidades

✅ Geração automática de dorks SQLi
✅ Dorks por categorias
✅ Suporte a múltiplos SGBDs
✅ Exportação para arquivo `.txt`
✅ Modo verbose com estatísticas
✅ Geração aleatória avançada
✅ Compatível com Python 3+

---

# 🧠 Bancos de Dados Suportados

A ferramenta reconhece padrões de erro de:

* MySQL
* MSSQL
* PostgreSQL
* Oracle
* SQLite

---

# 📦 Instalação

## Linux / Termux

```bash
git clone https://github.com/kalyel473/sqli-dork-generator.git

cd Dorks

python3 dorks.py
```

---

## Windows

Instale o Python:

* [https://www.python.org/downloads/](https://www.python.org/downloads/)

Depois execute:

```powershell
python dorks.py
```

---

# 🚀 Como Usar

## Gerar todos os dorks

```bash
python3 dorks.py
```

---

## Gerar apenas erros SQL

```bash
python3 dorks.py -c errors
```

---

## Gerar apenas parâmetros vulneráveis

```bash
python3 dorks.py -c parameters
```

---

## Gerar dorks combinados

```bash
python3 dorks.py -c combined
```

---

## Limitar quantidade de resultados

```bash
python3 dorks.py -n 50
```

---

## Salvar saída em arquivo

```bash
python3 dorks.py -o dorks.txt
```

---

## Modo Verbose

```bash
python3 dorks.py -v
```

---

# 📸 Exemplo de Saída

```txt
inurl:".php?id="
"You have an error in your SQL syntax"
inurl:"page=" "mysql_fetch"
inurl:"/index.php?id="
```

---

# 📂 Estrutura do Projeto

```bash
📦 sqli-dork-generator
 ┣ 📜 dorks.py
 ┣ 📜 README.md
 ┗ 📜 LICENSE
```

---

# 🛠️ Tecnologias Utilizadas

* Python 3
* argparse
* itertools
* random

---

# 📈 Possíveis Melhorias Futuras

* [ ] Interface gráfica (GUI)
* [ ] Exportação JSON/CSV
* [ ] Integração com APIs OSINT
* [ ] Gerador avançado por país/domínio
* [ ] Modo stealth
* [ ] Interface Web

---

# 🤝 Contribuição

Contribuições são bem-vindas!

Faça um fork do projeto e envie um Pull Request 🚀

---

# ⭐ Apoie o Projeto

Se você gostou da ferramenta:

⭐ Deixe uma estrela no repositório
📢 Compartilhe com a comunidade
🛡️ Apoie conteúdos de cibersegurança ética




📌 Canal: *Cybersegurança na Prática*


# 📜 Licença

Este projeto está sob a licença MIT.

---

<p align="center">
  ⚡ EDUCACIONAL • ETHICAL HACKING • CYBERSECURITY ⚡
</p>
