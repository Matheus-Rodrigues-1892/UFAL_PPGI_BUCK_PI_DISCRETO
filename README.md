# UFAL PPGI Simulação em Tempo Real e HIL: Buck PI Discreto

Repositório acadêmico desenvolvido no âmbito do Programa de Pós-Graduação em Informática (PPGI) da Universidade Federal de Alagoas (UFAL) para a disciplina de **Hardware-in-the-Loop** (Período: 2026.2).

---

## 1. Objetivo
Este pacote didático tem como objetivo fornecer uma abordagem prática e teórica sobre o funcionamento e o controle de um conversor CC-CC Buck. O material divide-se em duas partes principais:
* **Prática 1:** Caracterização analítica e simulação da planta do conversor Buck em malha aberta.
* **Prática 2:** Projeto, implementação e validação de um controlador Proporcional-Integral (PI) discreto em malha fechada.

---

## 2. Versão do Software e Pré-requisitos
* **Software:** Typhoon HIL Control Center versão 2026.x.
* **Ferramentas de Apoio:** 
  * Python 3.13.7
  * Jupyter Notebook.

---

## 3. Lista de Arquivos do Repositório
```text
UFAL_PPGI_BUCK_PI_DISCRETO/
│
├── Analysis/
│   └── buck.ipynb                        # Notebook com cálculos analíticos e comparações
├── Models/
│   ├── buck.tse                          # Modelo unificado do conversor Buck (.tse)
│   └── buck_scada.cus                    # Painel de controle HIL SCADA (.cus)
├── docs/
│   ├── Lab_Manual_Buck_P1_Student.pdf    # Manual do aluno - Prática 1
│   ├── Lab_Manual_Buck_P2_Student.pdf    # Manual do aluno - Prática 2
│   └── solutions/                        # Gabaritos e resoluções detalhadas (uso restrito)
├── Tests/
│   └── test_buck.py                      # Scripts de testes automáticos (opcional)
├── LICENSE                               # Licença MIT
└── README.md                             # Documentação principal do repositório

```

---

## 4. Atribuição de Papéis

Conforme as diretrizes da atividade, os membros da equipa assumiram os seguintes papéis e responsabilidades:

| Membro | Papel Principal | Contribuições Específicas |
| --- | --- | --- |
| **[Nome do Aluno]** | Coordenação & Gestão | Gestão do repositório, cronograma, checklist e contacto institucional. |
| **[Nome do Aluno]** | Redação | Elaboração dos Manuais do Aluno (Práticas 1 e 2) em inglês. |
| **[Nome do Aluno]** | Verificação | Execução e validação cega dos manuais e preenchimento dos gabaritos. |
| **[Nome do Aluno]** | Modelagem | Desenvolvimento do modelo unificado `.tse` no Schematic Editor. |
| **[Nome do Aluno]** | Painel e Testes | Construção do painel HIL SCADA (`.cus`) e rotinas de teste. |
| **[Nome do Aluno]** | Projeto Analítico | Desenvolvimento dos cálculos analíticos no Jupyter Notebook (`.ipynb`). |

---

## 5. Uso de Inteligência Artificial

Declara-se que ferramentas de Inteligência Artificial (como modelos de linguagem baseados em LLM) foram utilizadas de forma auxiliar no projeto para:

* Auxílio na estruturação textual e revisão gramatical dos manuais em língua inglesa.
* Consulta de suporte sintático para blocos de programação e scripts de automação.
* *Nota:* Toda a validação técnica, modelagem matemática, montagem no Typhoon HIL e verificação de resultados foram executadas e auditadas diretamente pelos autores.

---




