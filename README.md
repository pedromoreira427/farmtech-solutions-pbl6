# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href= "https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

# Nome do projeto

## Nome do grupo

## 👨‍🎓 Integrantes: 
- <a >Pedro Gustavo França Moreira 

## 👩‍🏫 Professores:
### Coordenador(a)
- <a href="https://www.linkedin.com/company/inova-fusca">Andre Godoi </a>


## 📜 Descrição

*Contexto do Projeto
A FarmTech Solutions está expandindo seus serviços de IA para além do agronegócio. Entre os novos projetos, a empresa passou a atuar na área de visão computacional, oferecendo soluções para saúde animal, segurança patrimonial, controle de acesso e análise de documentos.

Neste notebook, demonstramos para um cliente fictício da FarmTech como funciona um sistema completo de visão computacional na prática, utilizando o framework YOLOv5 para detecção de objetos.

Cenário Escolhido: Detecção de Gatos vs Cachorros
Escolhemos um cenário de saúde animal e controle de acesso em fazendas — identificar automaticamente se o animal presente é um gato ou um cachorro. Isso pode ser integrado a câmeras em portões, canis ou clínicas veterinárias parceiras da FarmTech.

Classe	Objeto	Quantidade	Treino	Validação	Teste
0	Gato (cat)	40 imagens	32	4	4
1	Cachorro (dog)	40 imagens	32	4	4
Total		80 imagens	64	8	8 *


## 📁 Estrutura de pastas

farmtech-fase6/

farmtech-fase6/
│
├── 📓 Pedrogustavofrancanmoreira_rm568262_pbl_fase6.ipynb
│   └── Notebook Jupyter com toda a solução (Entregas 1 e 2)
│       ├── Entrega 1: YOLOv5 Customizado (30 e 60 épocas)
│       ├── Entrega 2: YOLO Tradicional + CNN do Zero
│       └── Análise comparativa final
│
├── 📄 README.md
│   └── Este arquivo (documentação do projeto)
│
├── 📝 farmtech_dataset.yaml
│   └── Arquivo de configuração do dataset para YOLOv5
│
├── 📁 document/
│   ├── README.md (documentação adicional)
│   └── Outros documentos do projeto
│
├── 📁 config/
│   └── Arquivos de configuração
│
├── 📁 assets/
│   └── Imagens e recursos visuais
│
├── 📁 scripts/
│   └── Scripts auxiliares (se necessário)
│
├── 📁 src/
│   └── Código-fonte adicional
│
├── 📄 link para acesso ao drive.txt
│   └── Link para a pasta do dataset no Google Drive
│
├── 📄 .gitignore
│   └── Arquivos ignorados pelo Git
│
└── 📄 .gitattributes
    └── Configurações de atributos do Git

## 🔧 Como executar o código

*Como Executar
Pré-requisitos
Conta Google (para Google Colab + Drive)
GPU ativada no Colab: `Runtime → Change runtime type → T4 GPU`
Passo a Passo
1. Clone o repositório
```bash
git clone https://github.com/seu-usuario/farmtech-fase6.git
```
2. Organize suas imagens no Google Drive
```
MyDrive/FarmTech_Fase6/
├── dataset/images/train/   ← suas 64 imagens (nomeadas cat_*.jpg e dog_*.jpg)
├── dataset/images/val/     ← suas 8 imagens de validação
├── dataset/images/test/    ← suas 8 imagens de teste
└── dataset/labels/train/   ← labels .txt exportados do Make Sense AI
```
3. Abra o notebook no Google Colab
![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)
4. Execute as células em ordem — o notebook está organizado em seções com comentários detalhados em cada célula.
---
*


## 🗃 Histórico de lançamentos

* 01/05/2026 * 

## 📋 Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/agodoi/template">MODELO GIT FIAP</a> por <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a> está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>


