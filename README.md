# 🏥 Hospital - Exercício de Modelagem e Manipulação de Dados

Este projeto simula um sistema de gestão hospitalar utilizando arquivos JSON. Ele representa entidades e relacionamentos comuns em hospitais, com foco em estruturação e análise de dados.

---

## 📊 Diagrama de Relacionamento

Abaixo está o fluxo de decisão e estrutura de dados utilizados neste exercício:

![image](https://github.com/user-attachments/assets/42abe41a-ad69-4555-aaad-e0a2a00274b5)


---

## 📁 Estrutura dos Arquivos

| Arquivo                         | Descrição |
|--------------------------------|-----------|
| `Hospital.pacientes.json`      | Dados de pacientes: informações pessoais, contato, endereço e convênio. |
| `Hospital.medicos.json`        | Cadastro dos médicos: CRM, especialidades, status e documentos. |
| `Hospital.enfermeiros.json`    | Lista dos enfermeiros com CPF e número do COREN. |
| `Hospital.quartos.json`        | Informações sobre quartos disponíveis: tipo, número e valor da diária. |
| `Hospital.internacoes.json`    | Registros de internações: datas, procedimentos, paciente, médico e enfermeiros. |
| `Hospital.consultas.json`      | Consultas realizadas: data, especialidade, médico, paciente, valor e receituário. |

---

## 🎯 Objetivos do Exercício

- 📌 Treinar o uso de arquivos JSON como estrutura de dados.
- 📌 Compreender e aplicar relacionamentos entre entidades (ex: paciente → consultas).
- 📌 Simular funcionalidades de um sistema hospitalar, como:
  - Histórico de internações por paciente.
  - Consultas por médico.
  - Médicos por especialidade.
  - Receituário por paciente.
  - Tempo médio de internação.
  - Quartos mais utilizados.

---

## 💡 Sugestões de Uso

- Utilizar Python (`json`, `pandas`) para explorar e manipular os dados.
- Criar um banco de dados NoSQL (MongoDB) e importar os arquivos.
- Construir uma API com Flask, Django ou Node.js para servir os dados.
- Analisar os dados com dashboards (Power BI, Tableau, etc.).

---

## 🧪 Exemplo de Consulta (JSON)

```json
// Consultas do paciente "Maria Oliveira"
{
  "paciente_id": "707f1f77bcf86cd799439041"
}

