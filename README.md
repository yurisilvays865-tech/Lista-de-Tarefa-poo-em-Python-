# 📝 Lista de Tarefas – POO em Python

Projeto desenvolvido para praticar **Programação Orientada a Objetos (POO)** em Python.  
O sistema permite criar, listar, concluir e filtrar tarefas — incluindo tarefas **prioritárias**, que herdam e estendem o comportamento da classe base `Tarefa`.

---

## 🚀 Funcionalidades

- ✅ Adicionar novas tarefas com título e descrição  
- 🔁 Marcar tarefas como concluídas  
- 🔍 Filtrar tarefas por status (pendentes, concluídas ou prioritárias)  
- ⏫ Ordenar tarefas por nível de prioridade (`alta`, `média`, `baixa`)  
- 💾 Estrutura orientada a objetos, com herança e sobrescrita de métodos

---

## 🧠 Conceitos de POO aplicados

| Conceito | Aplicação |
|-----------|------------|
| **Classe e Objeto** | `Tarefa` e `TarefaPrioritaria` representam entidades do sistema |
| **Encapsulamento** | Atributos privados e métodos getters |
| **Herança** | `TarefaPrioritaria` herda de `Tarefa` |
| **Polimorfismo / Sobrescrita** | Método `exibir()` redefinido na subclasse |

---

## ⚙️ Como executar o projeto

1. **Clone o repositório**
   ```bash
   git clone https://github.com/yurisilvays865-tech/Lista-de-Tarefa-poo-em-Python-.git
Acesse a pasta do projeto

bash
Copiar código
cd Lista-de-Tarefa-poo-em-Python-
Execute o código

bash
Copiar código
python "Projeto Lista de Tarefas com POO finalizado.py"
📂 Estrutura do projeto
css
Copiar código
📦 Lista-de-Tarefa-poo-em-Python-
├── Projeto Lista de Tarefas com POO finalizado.py
├── README.md
└── (outros arquivos, se houver)
🧩 Exemplo de uso
python
Copiar código
tarefa1 = Tarefa("Lavar o carro", "Lavar e encerar o carro da garagem")
tarefa2 = TarefaPrioritaria("Reunião da equipe", "Projeto novo", "alta")

lista = ListaDeTarefas()
lista.adicionar_tarefa(tarefa1)
lista.adicionar_tarefa(tarefa2)
lista.exibir_tarefas()
👨‍💻 Autor
Yuri Magalhães
📫 GitHub
💼 Estudante de Análise e Desenvolvimento de Sistemas
🧠 Praticando Python e Programação Orientada a Objetos

🏁 Status do Projeto
✅ Concluído – Projeto finalizado como parte do estudo de POO em Python.
Em breve, será integrado ao portfólio no GitHub.

“Aprender é transformar lógica em prática.” ✨


