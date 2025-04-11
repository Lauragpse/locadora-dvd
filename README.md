# locadora-dvd

## Estrutura de pastas
```
dvd-emprestimos/
│
├── src/
│   ├── models/              # Classes principais (entidades)
│   │   ├── Amigo.js
│   │   ├── DVD.js
│   │   ├── Emprestimo.js
│   │   ├── FaixaEtaria.js
│   │   ├── Genero.js
│   │   └── Pessoa.js
│   │
│   ├── services/            # Lógicas de negócio, controle, cadastros
│   │   ├── CadastroAmigo.js
│   │   ├── CadastroDVD.js
│   │   ├── RegistroEmprestimo.js
│   │   └── RelatorioEmprestimos.js
│   │
│   ├── ui/                  # Interface simulada
│   │   └── Interface.js
│   │
│   ├── core/                # Arquivo principal de execução
│   │   └── Main.js
│   │
│   └── utils/               # Funções utilitárias (se necessário)
│       └── dateUtils.js
│
├── index.js                 # Ponto de entrada
├── package.json
└── README.md
```
