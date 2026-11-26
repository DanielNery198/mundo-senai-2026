# Mundo SENAI 2026 — Mini-Workshop de Canva e Excel

Registro oficial do projeto apresentado durante o **Mundo SENAI 2026** no **SENAI Varginha**, desenvolvido pelo curso **Técnico de Informática para Internet**.

🔗 **Páginas da Apresentação:**
- [Abrir Apresentação Principal (`html/apresentacao.html`)](html/apresentacao.html)
- [Abrir Desafios Interativos (`html/desafios.html`)](html/desafios.html)

---

## O que é o Mundo SENAI?

O **Mundo SENAI** é um evento anual promovido pelas unidades do SENAI em todo o Brasil que abre as portas da instituição para a comunidade, estudantes e empresas. Durante o evento, os alunos apresentam projetos práticos, oficinas e demonstrações tecnológicas desenvolvidas nos cursos técnicos e de qualificação profissional.

---

## O que foi feito

Realizamos um **mini-workshop prático de Canva e Microsoft Excel** voltado aos visitantes do evento, com o objetivo de demonstrar o funcionamento, a aplicabilidade e boas práticas dessas ferramentas:

- **Conceitos e Utilização:** Explicação sobre o que são o Canva e o Excel e como aplicá-los no dia a dia acadêmico e profissional.
- **Planilha Financeira no Excel:** Apresentação de uma planilha financeira funcional com recursos automatizados por macros.
- **Edição ao Vivo no Canva:** Demonstração prática de design ao corrigir e reestruturar, ao vivo, um mapa mental mal formatado.
- **Dinâmica Interativa com Visitantes:** Aplicação de desafios práticos diretamente nos computadores do laboratório.

---

## Como foi feito

### 1. Divisão da Equipe
A execução do mini-workshop foi dividida entre cinco integrantes:
- **2 alunos** ficaram responsáveis por apresentar os conceitos iniciais das ferramentas;
- **2 alunos** conduziram a apresentação e demonstração da planilha financeira no Excel;
- **1 aluno** realizou a demonstração ao vivo de correção do mapa mental no Canva.

### 2. Desenvolvimento e Uso de Inteligência Artificial
- **Roteiro e Apresentação (`prompt.docx`):** A partir de um prompt de exemplo fornecido pelo instrutor, adaptamos as instruções para o tema e a estrutura da nossa apresentação, enviando-o para uma Inteligência Artificial auxiliar na criação do material.
- **Planilha Financeira (`tabela-excel.xlsm`):** Toda a estrutura da tabela, formatação e fórmulas foram construídas manualmente pela equipe. Para a automação, solicitamos à Inteligência Artificial a geração completa do código das macros VBA.
- **Mapa Mental no Canva (`mapa-menta-antes.png` e `mapa-mental-depois.png`):** Preparamos um mapa mental propositalmente mal formatado para mostrar aos visitantes, na prática, como aplicar alinhamento, hierarquia visual e organização até chegar à versão final.

### 3. Dinâmica em Sala com Veyon
Durante o evento, a página `html/apresentacao.html` foi projetada na tela principal da sala para guiar as explicações. Já a página `html/desafios.html` — composta por slides interativos de perguntas — foi enviada e aberta simultaneamente nos computadores de todos os visitantes por meio do software de gerenciamento de laboratório **Veyon**.

---

## Estrutura do Repositório

```text
mundo-senai-2026/
├── index.html                   # Página inicial que replica este README e aponta para os arquivos
├── README.md                    # Documentação principal do repositório
├── prompt.docx                  # Prompt adaptado pela equipe e utilizado com IA
├── tabela-excel.xlsm            # Planilha financeira desenvolvida manualmente com macros geradas por IA
├── html/
│   ├── apresentacao.html        # Slides exibidos na tela principal da sala
│   └── desafios.html            # Slides interativos de perguntas enviados aos visitantes via Veyon
└── fotos/
    ├── apresentacao.png         # Registro da apresentação em sala
    ├── desafios.png             # Registro da tela/dinâmica de desafios
    ├── divisao.jpg              # Registro da divisão de tarefas da equipe
    ├── equipe.jpg               # Foto da equipe participante
    ├── mapa-menta-antes.png     # Mapa mental mal formatado (antes da demonstração)
    ├── mapa-mental-depois.png   # Mapa mental reestruturado ao vivo (depois da demonstração)
    └── tabela.png               # Visualização da planilha financeira no Excel