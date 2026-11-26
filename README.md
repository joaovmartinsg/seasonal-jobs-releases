# SeasonalJobs Automator

<p align="center">
  <a href="https://github.com/joaovmartinsg/seasonal-jobs-releases/releases/tag/v1.5.0">
    <img src="https://img.shields.io/badge/Vers%C3%A3o-v1.5.0-2563EB?style=for-the-badge" alt="Versão v1.5.0">
  </a>
  <img src="https://img.shields.io/badge/Windows-10%2F11%20(64--bit)-0F172A?style=for-the-badge" alt="Windows 10/11 64-bit">
  <a href="https://github.com/joaovmartinsg/seasonal-jobs-releases/releases/latest/download/SeasonalJobs_Setup.exe">
    <img src="https://img.shields.io/badge/Baixar%20Instalador-SeasonalJobs__Setup.exe-16A34A?style=for-the-badge" alt="Baixar SeasonalJobs_Setup.exe">
  </a>
</p>

O **SeasonalJobs Automator** é um aplicativo desktop para **Windows 10 e Windows 11 (64 bits)** criado para facilitar a busca, filtragem e gestão de candidaturas em vagas sazonais oficiais **H-2A** (agrícolas) e **H-2B** (não agrícolas) publicadas no portal **SeasonalJobs.dol.gov**.

---

## Download (Versão Atual)

[**Baixar SeasonalJobs_Setup.exe (v1.5.0)**](https://github.com/joaovmartinsg/seasonal-jobs-releases/releases/latest/download/SeasonalJobs_Setup.exe)

| Informação | Detalhes |
| --- | --- |
| **Versão atual** | `v1.5.0` |
| **Data de lançamento** | 26/11/2026 |
| **Tamanho do instalador (`SeasonalJobs_Setup.exe`)** | 43.50 MB |
| **Hash SHA-256** | `55ae9d930ec28796c9684041ac2d97a7a89f7e6f00f2fd1b1fdd97a9dc2ab61c` |

- [Ver todas as versões lançadas e arquivos de verificação](https://github.com/joaovmartinsg/seasonal-jobs-releases/releases)

---

## Novidades da versão v1.5.0

- Pré-validação DNS/MX e blacklist automática de bounces permanentes (hard bounces) - Suporte a Spintax nos modelos de e-mail, intervalo aleatório (jitter) e limite diário configurável por conta - Correção da duração e do ganho estimado em vagas H-2B itinerantes e padronização do prefixo `$` nos salários

---

## Principais Recursos

- **Vagas oficiais do DOL (H-2A e H-2B):** baixa e organiza os dados oficiais do portal *SeasonalJobs.dol.gov*, exibindo duração do contrato, salário estimado, detalhes da vaga e localização no Google Maps.
- **Filtros inteligentes:** filtre por tipo de visto, estado, salário por hora, horas semanais, duração do contrato e índice de compatibilidade, além de tradução rápida dos detalhes da vaga.
- **Múltiplos currículos em PDF:** seleção automática entre até 3 currículos (Geral H-2A, Máquinas/Motorista e Não-Agrícola H-2B), com editor integrado para criar ou atualizar seus PDFs.
- **Envio em fila persistente:** gerencia o envio de candidaturas em lotes de forma contínua em segundo plano, respeitando o horário comercial de Nova York (ET).
- **Verificação de respostas no Gmail:** monitora retornos de empregadores, destaca perguntas e links de formulários exigidos, permite resposta rápida, recupera candidaturas anteriores do Gmail, oferece modo Sentinela, exporta relatórios em Excel e limpa automaticamente e-mails devolvidos (*bounces*) com segurança.
- **Tour guiado de 1º acesso:** guia interativo passo a passo com checklist inicial para configurar tudo sem complicação.
- **Atualização em 1 clique:** avisa dentro do aplicativo quando há nova versão disponível e atualiza automaticamente com checagem de integridade SHA-256.

---

## Como Instalar e Primeiro Acesso

Você **não precisa instalar Python, Git nem usar conta de Administrador** no Windows. O instalador configura tudo automaticamente para o seu usuário em `%LOCALAPPDATA%\Programs\SeasonalJobs Automator`.

1. Baixe e execute [**SeasonalJobs_Setup.exe**](https://github.com/joaovmartinsg/seasonal-jobs-releases/releases/latest/download/SeasonalJobs_Setup.exe).
2. **Aviso do Windows SmartScreen:** como o instalador é distribuído diretamente sem assinatura comercial, o Windows pode exibir a tela *"O Windows protegeu o computador"*. Basta clicar em **Mais informações** e depois em **Executar assim mesmo** para prosseguir com a instalação.
3. Ao abrir o **SeasonalJobs Automator** pela primeira vez, siga os **3 passos iniciais** (ou acompanhe pelo tour guiado):
   - **Passo 1 — Conta Gmail:** informe seu endereço Gmail e sua **Senha de App** do Google na aba de configurações da conta.
   - **Passo 2 — Currículos em PDF:** selecione seus arquivos PDF (ou crie diretamente no editor integrado) na aba de currículos.
   - **Passo 3 — Vagas oficiais do DOL:** clique para baixar as vagas atualizadas do portal *SeasonalJobs.dol.gov*, aplique seus filtros e inicie suas candidaturas.

---

## Atualizações, Dados Preservados e Verificação de Integridade

- **Atualização em 1 clique:** sempre que uma nova versão estiver disponível, o botão **Atualizar App** dentro do programa destacará a atualização. Basta clicar para baixar, validar o hash SHA-256 e instalar automaticamente.
- **Seus dados sempre preservados:** configurações, histórico de candidaturas, respostas verificadas e backups ficam salvos em `%LOCALAPPDATA%\SeasonalJobsAutomator` e são mantidos integralmente em todas as atualizações.
- **Conferência opcional do arquivo baixado (SHA-256):** se desejar validar a integridade do instalador antes de executá-lo, abra o PowerShell na pasta onde o arquivo foi salvo e execute:

```powershell
Get-FileHash .\SeasonalJobs_Setup.exe -Algorithm SHA256
```

Compare o resultado exibido no PowerShell com o hash desta versão:

```text
55ae9d930ec28796c9684041ac2d97a7a89f7e6f00f2fd1b1fdd97a9dc2ab61c
```
