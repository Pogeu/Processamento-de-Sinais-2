# Processamento de Sinais II

Repositório contínuo para as listas de exercícios de Pedro Batsos.

## Organização

```text
2026_2_pedro_batsos_l1_v1/
├── lista_1/
│   ├── lista_1.pdf
│   └── 2026_2_pedro_batsos_l1_v1.ipynb
├── data/
│   ├── dataset.zip                   # Dataset compartilhado
│   └── dataset/                      # Dataset extraído
├── requirements.txt
└── README.md
```

As próximas listas devem receber sua própria pasta, seguindo o mesmo padrão:

```text
lista_2/lista_2.pdf
lista_2/2026_2_pedro_batsos_l2_v1.ipynb
lista_3/lista_3.pdf
lista_3/2026_2_pedro_batsos_l3_v1.ipynb
```

Cada notebook deve reutilizar `data/dataset.zip`/`data/dataset/` e evitar cópias locais das imagens. Se uma lista precisar de dados adicionais, coloque-os em `data/lista_2/`, por exemplo.

## Execução

Na raiz do repositório:

```bash
python -m pip install -r requirements.txt
jupyter notebook
```

Abra os notebooks a partir da raiz do repositório ou da pasta da lista. O notebook da Lista 1 encontra `data/dataset.zip` automaticamente e extrai o dataset quando necessário.
