# 🎵 Projeto 01 — Base de Dados: Festival de Música

## 📌 Sobre o projeto

Este projeto foi desenvolvido como parte do desafio prático da formação de **Analista de Dados da Generation Brasil**.

O objetivo foi trabalhar com a estruturação, carregamento e validação de uma base de dados fictícia de um festival de música, utilizando Python, Google Colab e Google Sheets.

O desafio permitiu praticar conceitos de manipulação de dados, integração entre ferramentas e organização de tabelas.

## 🎯 Objetivo

Criar e disponibilizar uma base de dados com informações sobre atrações musicais e vendas de ingressos de um festival fictício, garantindo que os dados fossem carregados corretamente e respeitassem a estrutura definida.

## 🛠️ Tecnologias e ferramentas utilizadas

- **Python:** linguagem utilizada para executar as operações de carregamento e validação dos dados.
- **Google Colab:** ambiente utilizado para desenvolver e executar o código.
- **Google Sheets:** ferramenta utilizada para armazenar as tabelas.
- **Pandas:** biblioteca utilizada para leitura e manipulação dos arquivos CSV.
- **Gspread:** biblioteca utilizada para conectar o Python ao Google Sheets.
- **Google Sheets API:** integração utilizada para enviar os dados à planilha.

## 📊 Estrutura da base de dados

O projeto possui duas tabelas:

### 1. Atracoes
Tabela de dimensão com informações sobre as atrações musicais.

Principais informações:
- ID da atração;
- Nome fictício do artista;
- Gênero musical;
- Edição do festival;
- Dia da apresentação;
- Palco;
- Horário de início.

**Total: 10.100 registros.**

### 2. Ingressos_vendidos
Tabela de fatos com informações sobre as vendas de ingressos.

Principais informações:
- ID da venda;
- ID da atração;
- Tipo de ingresso;
- Canal de venda;
- Data e hora da venda;
- Valor;
- Forma de pagamento.

**Total: 55.000 registros.**

## ⚙️ Etapas desenvolvidas

1. Configuração da conexão entre Python e Google Sheets.
2. Organização das tabelas e definição dos cabeçalhos.
3. Upload dos arquivos CSV fornecidos pelo instrutor.
4. Leitura dos arquivos utilizando Pandas.
5. Envio dos dados para o Google Sheets em lotes de 5.000 registros.
6. Validação da quantidade de registros e dos cabeçalhos das tabelas.
7. Conferência dos dados armazenados na planilha.

## ✅ Resultado final

A base de dados foi carregada e validada com sucesso.

| Tabela | Registros |
|---|---:|
| Atracoes | 10.100 |
| Ingressos_vendidos | 55.000 |
| **Total** | **65.100** |

As verificações confirmaram que:
- O volume mínimo de 20.000 registros foi atingido.
- Os cabeçalhos correspondem à estrutura definida.
- A quantidade de registros na planilha corresponde aos arquivos carregados.

## 📚 Aprendizados

Durante o desenvolvimento deste desafio, pratiquei:

- Manipulação e leitura de arquivos CSV com Python.
- Utilização da biblioteca Pandas.
- Integração entre Python e Google Sheets.
- Envio de grandes volumes de dados em lotes.
- Organização de tabelas de dimensão e fatos.
- Validação e conferência da integridade dos dados.

---

**Desenvolvido por:** Nathany Raisa Gonçalves de Assis

**Formação:** Analista de Dados — Generation Brasil
