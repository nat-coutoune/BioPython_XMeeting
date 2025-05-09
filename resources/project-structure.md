# [SUGESTÃO]
---

# **Estrutura de Pastas - Introduction to BioPython - XMeeting 2025**

```
BioPython-XMeeting/
│
├── README.md                     # Visão geral do curso, instruções de setup e informações gerais
├── requirements.txt              # Dependências para todo o curso
├── .gitignore                    # Incluindo .my_venv/ e outros arquivos para ignorar
│
├── day1-introduction/            # Dia 1: Introduction to BioPython
│   ├── notebooks/                
│   │   ├── 01-getting-started.ipynb
│   │   ├── 02-sequences.ipynb
│   │   └── 03-file-formats.ipynb
│   ├── exercises/                # Exercícios práticos 
│   ├── slides/                   # Apresentações do dia 1
│   └── data/                     # Arquivos de dados de exemplo para o dia 1
│
├── day2-entrez/                  # Dia 2: Accessing NCBI databases using Entrez
│   ├── notebooks/
│   │   ├── 01-entrez-basics.ipynb
│   │   ├── 02-searching-databases.ipynb
│   │   └── 03-advanced-queries.ipynb
│   ├── exercises/
│   ├── slides/                
│   └── data/                     # Arquivos de dados baixados via Entrez ou exemplos
│
├── day3-blast/                   # Dia 3: Comparing sequences using BioBlast
│   ├── notebooks/
│   │   ├── 01-blast-introduction.ipynb
│   │   ├── 02-local-blast.ipynb
│   │   └── 03-online-blast.ipynb
│   ├── exercises/
│   ├── slides/
│   └── data/                     # Sequências de exemplo para BLAST
│
├── resources/                    # Materiais de referência gerais para todo o curso
│   ├── cheatsheets/
│   ├── documentation/
│   └── additional_reading/
│
└── solutions/                    # Soluções para os exercícios (opcionalmente em branch separado)
    ├── day1/
    ├── day2/
    └── day3/
```

## Vantagens desta estrutura:

1. **Organização por dia** - Facilita que os participantes encontrem o material relevante para cada sessão
2. **Notebooks numerados** - Permite uma sequência clara de aprendizado
3. **Separação de dados** - Cada seção tem seu próprio diretório de dados
4. **Recursos gerais** - Materiais de referência compartilhados num local central
5. **Exercícios e soluções** - Permite prática independente com verificação posterior