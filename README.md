# Digital Twin - Projeto de Desenvolvimento Web

## Objetivo do Projeto
O projeto **Digital Twin** tem como principal objetivo atuar como uma **ferramenta de monitoramento e análise de indicadores de saúde**. 

O sistema permite que o usuário realize o **cadastro** e, em seguida, insira dados de seus exames (como frequência cardíaca, colesterol, glicemia, etc.). A função da aplicação é **analisar** esses resultados, informando os **níveis de risco** associados a cada indicador e emitindo **alertas personalizados** sobre pontos que requerem maior atenção ou acompanhamento médico.

## Tecnologias Utilizadas e Implementadas
A arquitetura do projeto foi pensada para ser modular e escalável, utilizando as seguintes tecnologias e separando as responsabilidades de **Frontend** e **Backend**:

### Frontend (Interface do Usuário)
| Categoria | Tecnologia | Detalhes da Implementação |
| :--- | :--- | :--- |
| **Framework** | **React** | Utilizado para a construção de componentes da interface e gerenciar o estado da aplicação de forma dinâmica e reativa, criando uma visualização clara dos indicadores. |
| **Linguagem** | **TypeScript** | Adotado para tipagem estática do código, aumentando a robustez, facilitando a manutenção e reduzindo erros em tempo de desenvolvimento. |

### Backend (Serviço/API)
| Categoria | Tecnologia | Detalhes da Implementação |
| :--- | :--- | :--- |
| **Ambiente** | **Node.js** | Ambiente de execução que serve como base para a nossa API, responsável por toda a lógica de negócio, persistência de dados e comunicação com o motor de análise. |
| **Linguagem** | **JavaScript / TypeScript** | Utilização da sintaxe Node.js para desenvolver os *endpoints* da API. |

### Containerização e Distribuição
| Categoria | Tecnologia | Detalhes da Implementação |
| :--- | :--- | :--- |
| **Containerização** | **Docker** | Utilizamos o Docker para **empacotar** o Frontend e o Backend em **contêineres** separados, garantindo que a aplicação rode de maneira idêntica em qualquer ambiente. |

## Arquitetura da Aplicação
O projeto adota uma arquitetura de aplicação **distribuída**, separando o **serviço (Backend)** da **interface (Frontend)**. Essa separação permite que cada parte seja desenvolvida, implantada e escalada de forma independente. O Frontend se comunica com o Backend através de chamadas **RESTful API** para cadastro de usuários e envio/recebimento dos dados de saúde para análise.

---
## Contribuição Individual (Isabela Suzumura)
Esta seção detalha o objetivo do código-fonte desenvolvido neste *fork* e como ele se integra ao projeto final do grupo.

### Objetivo do Código-Fonte Individual
O código-fonte individual concentra-se primariamente na **experiência do usuário (UX/UI)** da aplicação. 
O objetivo foi **atualizar e estilizar as principais interfaces** da plataforma, garantindo que o tema de monitoramento de saúde fosse refletido de forma clara, funcional e visualmente agradável, com foco na usabilidade e na leitura de dados críticos.

### Integração no Projeto Final

A contribuição está focada no **Frontend**, essencial para a apresentação visual da ferramenta:

1.  **Atualização de Páginas Chave:** Foram realizadas atualizações na **Landing Page** (página inicial) e na página de **DashBoard** (painel de indicadores) para refletir o tema de saúde e as informações de risco.
2.  **Estilização Completa (CSS):** Foi implementada a **estilização (CSS)** de todas as páginas da aplicação. Isso inclui a definição do *design system*, paleta de cores, tipografia e *layout* responsivo, garantindo uma interface coesa em todo o projeto.
3.  **Estrutura do Frontend (React):** O código estabelece a estrutura inicial de componentes no **React** para futura integração com os dados fornecidos pelo Backend.

### Status Atual da Implementação
O projeto, até o momento, apresenta funções básicas para a **exibição da informação e alertas** na interface do usuário. No entanto, é importante notar que toda essa apresentação é, atualmente, um **mockup** e **não** está conectada a um Back-end funcional ou a dados reais. A integração da lógica de API e persistência de dados será realizada nas próximas etapas.

### Próximos Passos Focados na Contribuição
| Categoria | Foco | Ação Detalhada |
| :--- | :--- | :--- |
| **Inteligência Artificial** | **Análise de Risco Real** | Implementação de uma ferramenta de **Inteligência Artificial dedicada** para a leitura dos dados de saúde, permitindo o cálculo **real e simultâneo** das probabilidades de risco. |
| **Banco de Dados** | **Persistência de Dados** | Implementação de um sistema de **Banco de Dados** funcional para duas finalidades: **armazenamento** dos exames de saúde recebidos de dispositivos **IoT** e suporte a um sistema completo de **cadastro e login de usuário**. |
| **Criptografia** | **Segurança** | Implementar mecanismos de **Criptografia** e *Hashing* para garantir a segurança e a privacidade dos dados sensíveis de saúde e credenciais de usuário. |
| **Frontend/UX** | **Aprimoramento da Interface** | Realização de modificações e aprimoramentos adicionais na **Landing Page** e no **DashBoard** para otimizar a experiência do usuário (UX) e a visualização dos dados. |
---
