<div align="center">

  <h1>💱 Conversor de Moedas</h1>

  <p>
    <img src="https://img.shields.io/badge/Python-3.14-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
    <img src="https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge" alt="Status"/>
  </p>

  <p>Conversor de câmbio em tempo real rodando no terminal, com suporte a Real, Dólar, Euro e Libra.</p>

</div>

---

## Sobre o projeto

O programa busca a cotação atual diretamente da [AwesomeAPI](https://economia.awesomeapi.com.br/) e realiza a conversão na hora. O usuário escolhe a moeda de origem, a moeda de destino e o valor a converter — tudo via menus interativos no terminal.

---

## Como funciona

1. O usuário escolhe a **moeda de origem** no menu (ex: Real).
2. O usuário escolhe a **moeda de destino** (ex: Dólar).
3. O programa monta o par de conversão (ex: `BRL-USD`) e faz uma requisição `GET` à AwesomeAPI.
4. O valor atual da cotação (`bid`) é retornado e multiplicado pelo valor digitado.
5. O resultado é exibido formatado com 2 casas decimais.

---

## Moedas suportadas

| # | Símbolo | Moeda |
|---|---------|-------|
| 1 | R$      | Real  |
| 2 | $       | Dólar |
| 3 | €       | Euro  |
| 4 | £       | Libra |

---

## Exemplo de uso

```
╔═════════════════════════════════════════╗
║           Conversor de Moedas           ║
╠═════════════════════════════════════════╣
║                                         ║
║ De qual moeda você deseja converter?    ║
║ 1 - Real(R$)                            ║
║ 2 - Dolár($)                            ║
║ 3 - Euro(€)                             ║
║ 4 - Libra(£)                            ║
║                                         ║
╚═════════════════════════════════════════╝
```

**Saída após conversão:**
```
A conversão do(a) Real para o(a) Dólar é: $5.73
Multiplicado por R$100.0, é igual á: $ 573.00
```

---

## Tecnologias utilizadas

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/requests-Library-orange?style=flat-square"/>
  <img src="https://img.shields.io/badge/AwesomeAPI-Exchange%20Rates-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/os-Built--in-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/sys-Built--in-blue?style=flat-square"/>
</p>

---

## Como executar

**Pré-requisitos:** Python 3.x instalado.

```bash
# Clone o repositório
git clone https://github.com/Eduardo-Nicolete37/CAMBIO_MOEDAS.git
cd CAMBIO_MOEDAS

# Instale a dependência
pip install requests

# Execute
python main.py
```

---

## Autor

**Eduardo Nicolete**

[![GitHub](https://img.shields.io/badge/GitHub-Eduardo--Nicolete37-181717?style=flat-square&logo=github)](https://github.com/Eduardo-Nicolete37)

---

<div align="center">
  <sub>Feito com 🐍 e dedicação para aprender Python na prática.</sub>
</div>
