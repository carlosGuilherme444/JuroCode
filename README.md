# 🔐 Juro Code Translator & Decryptor

> Transforme qualquer mensagem em uma sequência de "Juro", "Sim Juro", "Juro Amiga" e outras variações usando um algoritmo baseado em Álgebra Linear.

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![HTML](https://img.shields.io/badge/HTML5-orange)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)
![License](https://img.shields.io/badge/license-MIT-green)

---

## 📖 Sobre

**Juro Code** é uma linguagem de codificação inspirada na forma como amigos conversam utilizando expressões como:

- Juro
- Sim juro
- Juro amiga
- Amiga juro
- Vei juro
- Juro vei

O projeto converte qualquer texto comum em uma sequência dessas seis expressões e consegue reconstruir exatamente a mensagem original através de um algoritmo matemático reversível.

Todo o processamento acontece localmente no navegador, sem necessidade de servidores.

---

# ✨ Funcionalidades

- 🔒 Criptografia baseada em matrizes
- 🔓 Descriptografia completa
- 🧮 Conversão automática para Base 6
- 📐 Álgebra Linear Modular
- 📋 Copiar resultado com um clique
- 🖥 Interface moderna (Tailwind CSS)
- 📊 Log em tempo real do algoritmo
- ⚡ Funciona totalmente offline

---

# 🧠 Como funciona

O algoritmo segue o fluxo abaixo:

```
Texto

↓

ASCII

↓

Base 6

↓

Multiplicação por Matriz (mod 6)

↓

Mapeamento para Tokens

↓

Juro Code
```

Na descriptografia o processo é exatamente o inverso.

---

# 📐 Algoritmo Matemático

A matriz utilizada para embaralhar os dados é:

```
| 2  1 |
| 1  1 |
```

Como seu determinante é igual a **1**, ela possui inversa em módulo 6.

A matriz inversa utilizada é:

```
| 1  5 |
| 5  2 |
```

Cada caractere é convertido em quatro dígitos na Base 6.

Os dígitos são processados em pares utilizando multiplicação matricial modular.

---

# 🗣 Linguagem Juro Code

Cada número de 0 a 5 representa exatamente um token.

| Valor | Token |
|--------|-------|
| 0 | `juro` |
| 1 | `sim juro` |
| 2 | `juro amiga` |
| 3 | `amiga juro` |
| 4 | `vei juro` |
| 5 | `juro vei` |

Assim, uma mensagem pode ficar parecida com:

```
juro,
juro amiga,
sim juro,
vei juro,
amiga juro,
...
```

---

# 📦 Estrutura

```
/
│
├── index.html
└── README.md
```

Todo o projeto está contido em um único arquivo HTML.

---

# 🚀 Como executar

[TESTAR AGORA](https://carlosguilherme444.github.io/JuroCode/index.html)

Basta abrir o arquivo:

```
index.html
```

em qualquer navegador moderno.

Não é necessário instalar dependências.

Não utiliza backend.

Não utiliza banco de dados.

---

# 🛠 Tecnologias

- HTML5
- CSS3
- Tailwind CSS
- JavaScript (Vanilla)
- Lucide Icons

---

# 📋 Recursos

- Interface responsiva
- Sistema de notificações
- Área de logs
- Copiar para área de transferência
- Criptografia reversível
- Decodificação automática

---

# ⚠ Aviso

O Juro Code foi desenvolvido para fins educacionais e demonstra conceitos como:

- Álgebra Linear
- Matrizes
- Aritmética Modular
- Conversão de Bases
- Representação Numérica

Embora utilize operações matemáticas reversíveis, **não deve ser utilizado para proteger informações sensíveis**, pois não possui características de uma criptografia moderna e segura.

---

# 📄 Licença

Este projeto está licenciado sob a licença MIT.

Você pode estudar, modificar e distribuir livremente.

---

# ❤️ Autor

Desenvolvido por **aceleradox**.

Se este projeto foi útil para você, deixe uma ⭐ no repositório.
