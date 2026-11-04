
# Sala Certa CNA

Sistema web desenvolvido para organizar a distribuição de turmas, professores e salas da CNA, com um painel administrativo para gerenciamento e uma tela pública otimizada para exibição em TV.

## Funcionalidades

- Cadastro, edição e exclusão de turmas.
- Organização das turmas por andar e sala.
- Registro de professores, turmas e disciplinas.
- Controle da quantidade de alunos por turma.
- Cadastro dos horários de início e término das aulas.
- Busca e filtragem de turmas por andar.
- Indicadores de quantidade de turmas, salas ocupadas e alunos.
- Tela de TV com as turmas agrupadas por andar.
- Exibição de relógio e data em tempo real.
- Interface responsiva para diferentes dispositivos.
- Armazenamento local dos dados utilizando `localStorage`.
- Sincronização de informações entre abas do mesmo navegador.

## Tecnologias utilizadas

- **HTML5** — estrutura das páginas.
- **CSS3** — estilização e identidade visual.
- **JavaScript (Vanilla JS)** — lógica e interatividade.

## Como executar

1. Clone ou baixe este repositório.
2. Abra o arquivo `index.html` em um navegador.
3. Acesse o painel administrativo e cadastre as turmas.
4. Selecione a opção **Tela da TV** para visualizar a distribuição das turmas.

Não é necessário instalar dependências para executar o projeto localmente.

## Telas do sistema

- `index.html#admin` — painel de gerenciamento das turmas.
- `index.html#tv` — painel de exibição para TV, para compatibilidade.
- `/view/` — endereço direto da tela de TV.

## Armazenamento de dados

Os dados são armazenados localmente no navegador por meio do `localStorage`. A sincronização permite atualizar as informações entre abas do mesmo navegador.

Para compartilhar os dados entre computadores e TVs diferentes, será necessária a integração com um backend e um banco de dados remoto, como o Supabase.

## Melhorias futuras

- Integração com banco de dados remoto.
- Sincronização de dados em tempo real entre dispositivos.
- Sistema de autenticação para administradores.
- Cadastro e gerenciamento de horários e períodos.
- Validação de conflitos de horários e reservas de salas.
- Aprimoramento do painel administrativo e da tela de TV.

## Identidade visual

A interface utiliza a paleta de cores vermelha da CNA, com a marca aplicada sobre fundo branco.

A tela de TV prioriza o fundo branco, textos escuros e detalhes em vermelho, proporcionando boa legibilidade e facilitando a visualização das informações à distância.

## Idealização e orientação

**Aluno idealizador:** Lorenzo Dalla Vechia Ribeiro

**Professor orientador:** Harris Alexandre

**LinkedIn do professor orientador:** [Harris Alexandre](https://www.linkedin.com/in/harris-alexandre/)

---

*Projeto educacional desenvolvido para a CNA.*
