# 🚀 Projeto PHP — Demonstração Introdutória

![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/Licen%C3%A7a-MIT-blue?style=for-the-badge)

Documentação técnica do projeto introdutório em PHP desenvolvido por **Murilo Ribeiro Barbosa Camelo**. Este repositório demonstra a integração básica entre scripts PHP (*server-side*) e marcação HTML5, além de celebrar o **100º projeto gerenciado com Git**.

---

## 📌 Sumário
- [Visão Geral](#-visão-geral)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Código-Fonte](#-código-fonte)
- [Como Executar](#-como-executar)
- [Fluxo Git & Commits](#-fluxo-git--commits)
- [Autor & Licença](#-autor--licença)

---

## 📌 Visão Geral

Este projeto é uma página web dinâmica simples que utiliza variáveis em PHP para armazenar informações do desenvolvedor e renderizá-las no HTML.

### 🎯 Objetivos:
- Declaração e manipulação de variáveis PHP (`$nome`, `$profissao`, `$mensagem`).
- Renderização dinâmica no HTML via `echo` / `<?= ?>`.
- Aplicação das especificações HTML5 e codificação `UTF-8`.
- Prática de versionamento e controle de código com Git.

---

## 📋 Identificação do Projeto

| Item | Detalhe |
| :--- | :--- |
| **Nome** | Projeto PHP — Demonstração Introdutória |
| **Autor** | Murilo Ribeiro Barbosa Camelo |
| **Linguagens** | PHP (Server-Side) & HTML5 |
| **Codificação** | UTF-8 |
| **Idioma** | Português do Brasil (`pt-BR`) |
| **Status** | Concluído / 100º Projeto Git |

---

## 🛠️ Tecnologias Utilizadas

- **PHP**: Processamento e renderização dinâmica no servidor.
- **HTML5**: Estruturação semântica e acessível da página.
- **Git**: Controle de versão e histórico do código.

---

## 📂 Estrutura do Repositório

```text
meu-projeto-php/
├── index.php         # Código principal (PHP + HTML5)
├── README.md         # Documentação completa para o GitHub
└── .gitignore        # Arquivos ignorados pelo Git
```

---

## 💻 Código-Fonte (`index.php`)

```php
<?php
/**
 * Projeto PHP - Demonstração Introdutória
 * Autor: Murilo Ribeiro Barbosa Camelo
 */

$nome = "Murilo Ribeiro Barbosa Camelo";
$profissao = "Aprendiz de Desenvolvimento de Sistemas";
$mensagem = "Esse é meu centésimo projeto usando Git.";

?>
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projeto PHP - <?= htmlspecialchars($nome, ENT_QUOTES, 'UTF-8') ?></title>
</head>
<body>

    <main>
        <h1><?= htmlspecialchars($nome, ENT_QUOTES, 'UTF-8') ?></h1>
        <p><strong>Cargo:</strong> <?= htmlspecialchars($profissao, ENT_QUOTES, 'UTF-8') ?></p>
        <p><?= htmlspecialchars($mensagem, ENT_QUOTES, 'UTF-8') ?></p>
    </main>

</body>
</html>
```

---

## ⚡ Como Executar

1. **Clonar o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/meu-projeto-php.git
   cd meu-projeto-php
   ```

2. **Iniciar o servidor embutido do PHP:**
   ```bash
   php -S localhost:8000
   ```

3. **Acessar no navegador:**
   [http://localhost:8000](http://localhost:8000)

---

## 🌿 Comandos Git Utilizados

```bash
git init
git add .
git commit -m "feat: cria estrutura principal do projeto PHP"
git branch -M main
git remote add origin https://github.com/seu-usuario/meu-projeto-php.git
git push -u origin main
```

---

## 👨‍💻 Autor

**Murilo Ribeiro Barbosa Camelo**  
*Aprendiz de Desenvolvimento de Sistemas*

---

## 📜 Licença

Este projeto está sob a licença [MIT](LICENSE).