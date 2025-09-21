# Modelagem e Otimização de Sistemas Térmicos


## Identificação
> **Instituição:** Universidade Federal de Pernambuco (UFPE)  
> **Curso:** Graduação em Engenharia Mecânica  
> **Componente:** Disciplina eletiva  
> **Pré-requisito:** Termodinâmica II  
> **Professor:** Fábio Magnani, Prof. Tit., Dr. Eng. Mec. (fabio.magnani@ufpe.br)  

---

## Objetivos
- Integrar Termodinâmica, Mecânica dos Fluidos, Transferência de Calor, Métodos Numéricos e Análise Termoeconômica para **modelar**, **simular** e **otimizar** sistemas térmicos.  
- Reforçar a leitura física dos resultados e a capacidade de propor **melhorias de projeto** (trade-offs técnicos/econômicos/ambientais).

---

## Ementa
- Revisão integradora: **métodos numéricos, ciclos termodinâmicos, perda de carga e trocadores de calor**.  
- Análise **técnica, financeira e ambiental** de sistemas térmicos (tarifas, emissões, ACV, VPL, TIR, payback).  
- **Modelagem** de casos práticos de sistemas térmicos (resolvidos por métodos computacionais de solução de sistemas não-lineares) e **otimização** (multiplicadores de Lagrange, métodos de busca e programação linear).  
- **Mini-projetos** aplicados.

## Bibliografia

### Básica
- Stoecker, W. F. *Design of Thermal Systems*. 3ª ed., McGraw-Hill, 1989.
- Bejan, A.; Tsatsaronis, G.; Moran, M. *Thermal Design and Optimization*. Wiley, 1996.
- Moran, Shapiro, Boettner & Bailey. *Princípios de Termodinâmica para Engenharia*, 8ª ed., LTC, 2018.

### Complementar
- Fox, McDonald, Pritchard & Mitchell. *Introdução à Mecânica dos Fluidos*, 9ª ed., LTC, 2018.
- Incropera, F. P.; DeWitt, D. P. *Fundamentos de Transferência de Calor e de Massa* 8ª ed., LTC, 2019.  
- Chapra, Canale. *Métodos Numéricos para Engenharia*. 7ª ed., McGraw-Hill, 2016.

---

## Habilidades e Competências
Ao final, o(a) estudante deverá ser capaz de:
1. **Modelar** os sistemas, incluindo desde as hipóteses até as equações.  
2. **Implementar** esses modelos em **notebooks Jupyter**, documentando as hipóteses e validando unidades/ordens de grandeza.  
3. **Interpretar** resultados (regimes, sensibilidade, limites físicos) e **propor** ajustes de projeto.  
4. Estruturar e conduzir **mini-projetos** com dados realistas, reportando decisões e limitações.
5. Trabalhar em **equipe**.
6. **Apresentar** bem as suas atividades, seja na forma de *notebooks*, relatórios, palestras ou mesmo durante as reuniões.

---

## Metodologia
- **Jupyter Notebooks** como instrumento central (código reprodutível, gráficos e discussão integrada).  
- **Discussões em sala** (interpretação física, “regras de bolso”, verificação de coerência).  
- **Mini-projetos** em duplas/trios (escopo curto, foco em clareza técnica).  
- **Palavras-chave**: *aprendizagem ativa*, *resolução de problemas*, *uso de tecnologia aberta*, *reprodutibilidade*.

---

## Notas de Estudos

- **Revisão de Ciclo Regenerativo** (Otimização a Uma Variável - Método de Brent)    
📓 [Colab](https://colab.research.google.com/github/Prof-Magnani/sistemas-termicos/blob/main/notebooks/ne-revisao-ciclo-regenerativo.ipynb)  
- **Revisão de Perda de Carga** (Raiz de Função)     
  📓 [Colab](https://colab.research.google.com/github/Prof-Magnani/sistemas-termicos/blob/main/notebooks/ne-revisao-perda-carga.ipynb) · 🌐 [HTML](./html/ne-revisao-perda-carga.html) · 📑 [PDF](./pdf/ne-revisao-perda-carga.pdf)
- **Revisão de Trocador de Calor com Condensação** (Newton-Raphson)  
  📓 [Colab](https://colab.research.google.com/github/Prof-Magnani/sistemas-termicos/blob/main/notebooks/ne-revisao-newton-raphson.ipynb) · 🌐 [HTML](./html/ne-revisao-newton-raphson.html) · 📑 [PDF](./pdf/ne-revisao-newton-raphson.pdf) · 🎞️ [Slides](./revealjs/ne-revisao-newton-raphson-slides.html) · 📊 [PPTX](./pptx/ne-revisao-newton-raphson.pptx)

- **Revisão de Trocadores de Calor**  
🚧 Em construção


 ### Sobre os formatos disponíveis

Cada nota de estudo é publicada em diferentes formatos, para atender a usos variados:

- 📓 **Colab** — versão interativa do notebook no Google Colab, onde é possível executar os códigos em Python diretamente no navegador, sem instalação local.  
- 🌐 **HTML** — versão estática em página web, ideal para leitura rápida e visualização em qualquer dispositivo.  
- 📑 **PDF** — versão em documento fixo, prática para impressão, anotações e uso offline.  
- 🎞️ **Slides (reveal.js)** — versão em formato de apresentação, adequada para revisões em sala de aula ou exposições rápidas.  
- 📊 **PPTX** — versão compatível com PowerPoint/LibreOffice Impress, permitindo editar os slides e adaptá-los a outras apresentações.

---

## Desenvolvimento do Repositório

Se você deseja **reproduzir os notebooks localmente** ou entender como gerar as diferentes saídas (HTML, PDF, Reveal.js, PPTX), consulte o guia de desenvolvimento:

➡️ [DEVELOPMENT.md](./DEVELOPMENT.md)

Esse documento explica:
- Instalação do ambiente (Anaconda, VS Code, MiKTeX, Quarto).  
- Estrutura de arquivos do repositório.  
- Comandos para renderizar os notebooks em diferentes formatos.  
- Orientações básicas de Git/GitHub.  


---

---

<p align="center">
  <a href="https://jupyter.org" target="_blank">
    <img src="https://jupyter.org/assets/homepage/main-logo.svg" alt="Jupyter" width="180"/>
  </a>
</p>

<p align="center">
  <b>Jupyter é um laboratório vivo de ensino e de prática de ciência — livre, aberto, integrado, integrador, transparente, auditável, reprodutível, interativo e colaborativo.</b>
</p>
