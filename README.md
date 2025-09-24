-- Modelo lógico no padrão brModelo

-- Tabela REINO
CREATE TABLE REINO (
    id_reino INT PRIMARY KEY,
    nome VARCHAR(100),
    regente VARCHAR(100)
);

-- Tabela CASTELO
CREATE TABLE CASTELO (
    id_castelo INT PRIMARY KEY,
    nome VARCHAR(100),
    localizacao VARCHAR(100),
    id_reino INT,
    FOREIGN KEY (id_reino) REFERENCES REINO(id_reino)
);

-- Tabela GUERREIRO
CREATE TABLE GUERREIRO (
    id_guerreiro INT PRIMARY KEY,
    nome VARCHAR(100),
    classe VARCHAR(50),
    nivel INT,
    id_reino INT,
    FOREIGN KEY (id_reino) REFERENCES REINO(id_reino)
);

-- Tabela MISSAO
CREATE TABLE MISSAO (
    num_missao INT PRIMARY KEY,
    descricao VARCHAR(255),
    data DATE,
    id_guerreiro INT,
    FOREIGN KEY (id_guerreiro) REFERENCES GUERREIRO(id_guerreiro)
);

-- Tabela ARTEFATO_MAGICO
CREATE TABLE ARTEFATO_MAGICO (
    id_artefato INT PRIMARY KEY,
    nome VARCHAR(100),
    poder VARCHAR(100)
);

-- Tabela PORTA (associativa entre GUERREIRO e ARTEFATO_MAGICO)
CREATE TABLE PORTA (
    id_guerreiro INT,
    id_artefato INT,
    num_seq INT,
    PRIMARY KEY (id_guerreiro, id_artefato, num_seq),
    FOREIGN KEY (id_guerreiro) REFERENCES GUERREIRO(id_guerreiro),
    FOREIGN KEY (id_artefato) REFERENCES ARTEFATO_MAGICO(id_artefato)
);


<h1 align="center"> ooo



![Status](https://img.shields.io/badge/Status-Ativo-green)
![Versão](https://img.shields.io/badge/Versão-1.0-blue)
![Python](https://img.shields.io/badge/Python-3.10-yellow)
[![Windows](https://custom-icon-badges.demolab.com/badge/Windows-0078D6?logo=windows11&logoColor=white)](#)

---
⚠️ **Atenção:** Esse projeto ainda está em desenvolvimento!
---

<h1 align="center">🚀 Meu Projeto Incrível</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Ativo-green">
  <img src="https://img.shields.io/badge/Versão-1.0-blue">
  <img src="https://img.shields.io/badge/Python-3.10-yellow">
</p>

---

## ✨ Funcionalidades
- ✅ <span style="color:green; font-weight:bold;">Login seguro</span>  
- 📊 <span style="color:blue; text-decoration:underline;">Dashboard interativo</span>  
- ⚡ <span style="color:red;">Performance otimizada</span>  

---

## 📦 Instalação
```bash
git clone https://github.com/usuario/repositorio.git
cd repositorio
pip install -r requirements.txt








' eee

" eee

{ iiii }

: eee

; eee

* eee *
  
** eee **

  **eee*

**eee*

  *eee**



ssh://[ <usuário>@ ] <host> [ :<porta> ] /<caminho-para-o-repositório-git>

















# LinhaDoTempo-CoEmNuvem
+ 
+ 
# [Python 👨‍💻​](#-sobre-o-projeto)
- iiii
+ iiii


      # oiooiio

[carro](#-sobre-o-projeto)
[carro](#-carro)

     # oiooiio
     #carro

- ![Nível 1: Fundamentos do Python - Aprenda Python em 10min](![Imagem do WhatsApp de 2025-09-16 à(s) 10 02 14_9eaa58a9](https://github.com/user-attachments/assets/8a6663a9-8f8a-4182-9dce-942d596936d7)
)](https://youtu.be/4p7axLXXBGU?si=HIJw6AlfD_t3RMzp) 

- ![Nível 2: O Python na Prática - Curso Python 01 a 142](![Imagem do WhatsApp de 2025-09-16 à(s) 10 02 18_a3c8e2a2](https://github.com/user-attachments/assets/be759371-76ca-425b-8798-960198949437)
)](https://youtu.be/S9uPNppGsGo?si=-RaIIY33bQ_FOQEV)

- ![Nível 3: Projetos e Tópicos Avançados](![Imagem do WhatsApp de 2025-09-16 à(s) 10 10 08_685a2357](https://github.com/user-attachments/assets/5df51f05-c884-4183-bb90-beb751137938)
)](https://youtu.be/BS8mv11SJeo?si=tSNog9Vf4RL0gCEO)

- [📌 Sobre o Projeto](#-sobre-o-projeto)
- [




https://github.com/github/training-kit.git




**x**
**Y**


- [📌 Sobre o Projeto](#-sobre-o-projeto)
- [✨ Funcionalidades](#-funcionalidades)
- [🛠️ Tecnologias](#️-tecnologias)
- [⚙️ Instalação](#️-instalação)
- [🚀 Como Usar](#-como-usar)
- [📸 Demonstração](#-demonstração)
- [🤝 Contribuição](#-contribuição)
- [📄 Licença](#-licença)


git clone[ <diretório-modelo > ]--template=
	  [ -l] [ -s] [ --no-hardlinks] [ -q] [ ] -n[ --bare] [ --mirror]
	  [ <nome> ] [ <nome> ] [ <pacote de upload> ] [ <repositório> ]-o -b -u --reference 
	  [ --dissociate] [ <git-dir> ]--separate-git-dir 
	  [ <profundidade> ] [ [ ] ] [ [ ] ]--depth --no-single-branch--no-tags
	  [ --recurse-submodules[ <pathspec> ]] [ [ ] ]=--no-shallow-submodules
	  [ --[ no-] remote-submodules] [ <n> ] [ ] [ [ ] ]--jobs --sparse--no-reject-shallow
	  [ <especificação-do-filtro > ] [ ]] [ ] <repositório> 
	  [ <diretório> ]--filter=--also-filter-submodules--
   
