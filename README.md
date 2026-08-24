# 🌐 Metaverso v2 - Experiência em Realidade Virtual (VR)

Uma aplicação interativa em **Realidade Virtual (VR)** desenvolvida na **Unity**, criada para demonstrar os conceitos fundamentais de eXtended Reality (XR) através de um ambiente tridimensional navegável.

---

## 🎯 Objetivo do Projeto

O objetivo principal deste projeto é consolidar e demonstrar a compreensão dos **fundamentos de XR** adquiridos durante a primeira fase do curso. O projeto consiste em um ambiente navegável simples em VR onde os conceitos de posicionamento, rastreamento de movimento, interação e imersão são aplicados de forma prática.

---

## 🚀 Funcionalidades Principais

- **Ambiente Imersivo 3D**: Terreno e cenários interativos projetados para imersão em VR.
- **Navegação & Locomoção**: Suporte a métodos de locomoção em ambiente virtual (Teleporte e/ou Locomoção Contínua).
- **Rastreamento de Movimento**: Suporte a rastreamento de cabeça (Head Tracking) e controladores hands/motion.
- **Integração Meta SDK (Opcional)**: Suporte para dispositivos Oculus/Meta Quest (via Oculus / Meta XR SDK).
- **Sistema de Input**: Configurado utilizando o **Unity Input System** moderno.

---

## 🛠️ Tecnologias Utilizadas

- **Engine**: [Unity](https://unity.com/)
- **Linguagem**: C# (.NET Framework)
- **Pacotes XR**:
  - Unity XR Interaction Toolkit / XR Plugin Management
  - Meta XR SDK / Oculus Integration Package (Opcional)
  - Unity Input System (`InputSystem_Actions`)

---

## 📁 Estrutura do Projeto

```text
metaverso_v2/
├── Assets/
│   ├── Scenes/               # Cenas da aplicação (ex: SampleScene)
│   ├── XR/                   # Configurações e rig do XR Controller / Rig
│   ├── Oculus/               # Ativos e prefabs do Meta XR SDK (se utilizado)
│   ├── Settings/             # Configurações de Render Pipeline e Inputs
│   └── Plugins/              # Plugins de terceiros e utilitários
├── Packages/                 # Manifesto de dependências do Unity
├── ProjectSettings/          # Configurações do projeto e do XR Plugin Management
└── README.md                 # Documentação do projeto
```

---

## ⚙️ Como Executar o Projeto

### Pré-requisitos

1. **Unity Editor** instalado (versão recomendada com suporte a build Android/Windows XR).
2. **Unity Hub**.
3. **Meta Quest Link / Air Link** (caso deseje testar diretamente em um headset Meta Quest).

### Passo a Passo

1. **Clonar o Repositório**:

   ```bash
   git clone https://github.com/seu-usuario/metaverso_v2.git
   ```

2. **Abrir no Unity**:
   - Abra o **Unity Hub**.
   - Clique em **Add** / **Open** e selecione a pasta `metaverso_v2`.
   - Aguarde o Unity carregar os pacotes e compilar as dependências.

3. **Executar a Cena**:
   - No painel _Project_, navegue até `Assets/Scenes/`.
   - Abra a cena `SampleScene.unity`.
   - Pressione o botão **Play** no Unity Editor (garanta que seu Headset VR ou o XR Simulator esteja ativo).

---

## 🎮 Controles & Interação

- **Olhar/Orientação**: Rastreamento de cabeça do Headset VR.
- **Movimentação**: Analógico esquerdo (Locomoção Contínua) ou gatilho para Teleporte.
- **Rotação**: Analógico direito (Snap Turn / Smooth Turn).
- **Interação com Objetos**: Gatilhos laterais (Grip/Select) nos controles XR.

---

## 🎓 Requisitos da Avaliação (Fase 1)

- [x] **Configuração do Rig VR**: Câmera de VR e tracking de controladores funcionais.
- [x] **Construção do Cenário**: Ambiente 3D navegável com elementos visuais e colisores.
- [x] **Navegação**: Sistema de locomoção configurado para o usuário explorar o ambiente.
- [x] **Organização do Projeto**: Estrutura limpa de diretórios e boas práticas no Unity.
- [ ] _(Opcional)_ **Recursos Avançados Meta SDK**: Funcionalidades específicas do ecossistema Oculus/Meta (Passthrough, Hand Tracking, etc.).

---
