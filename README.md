# SeasonalJobs Automator

Aplicativo para Windows que ajuda a organizar vagas sazonais H-2A e H-2B, preparar currículos e acompanhar candidaturas em um só lugar.

[![Baixar SeasonalJobs Automator](https://img.shields.io/badge/Baixar-Windows_10%2F11_64--bit-2563EB?style=for-the-badge&logo=windows11&logoColor=white)](https://github.com/joaovmartinsg/seasonal-jobs-releases/releases/latest/download/SeasonalJobs_Setup.exe)

**[Baixar a versão mais recente — SeasonalJobs_Setup.exe](https://github.com/joaovmartinsg/seasonal-jobs-releases/releases/latest/download/SeasonalJobs_Setup.exe)**

[Ver detalhes, notas e arquivos da versão mais recente](https://github.com/joaovmartinsg/seasonal-jobs-releases/releases/latest)

## Instalação

Compatível com **Windows 10 e Windows 11, 64 bits**.

1. Baixe o arquivo `SeasonalJobs_Setup.exe` pelo botão acima.
2. Execute o instalador e siga as etapas exibidas.
3. Abra o **SeasonalJobs Automator** pelo Menu Iniciar ou pelo atalho criado.

O aplicativo não exige Python, Git nem permissão de Administrador. A instalação é feita somente para o usuário atual em:

```text
%LOCALAPPDATA%\Programs\SeasonalJobs Automator
```

### Aviso do Windows SmartScreen

Na primeira execução, o Windows pode exibir a mensagem **“O Windows protegeu o computador”**. Nesse caso, clique em **Mais informações** e depois em **Executar assim mesmo**.

## Primeiro acesso

O checklist inicial orienta três configurações rápidas:

1. Informe seu Gmail e uma **Senha de App do Google**.
2. Selecione os PDFs dos seus currículos para vagas H-2A, Máquinas/Motorista e H-2B.
3. Baixe os feeds oficiais de vagas do DOL dentro do aplicativo.

## Atualizações e dados

O botão **Atualizar App** instala novas versões em um clique. Seus perfis, histórico, configurações e demais dados são preservados em:

```text
%LOCALAPPDATA%\SeasonalJobsAutomator
```

## Verificação opcional do download

Cada versão pode incluir o arquivo [`SHA256SUMS.txt`](https://github.com/joaovmartinsg/seasonal-jobs-releases/releases/latest/download/SHA256SUMS.txt). Para calcular o hash do instalador no PowerShell, abra a pasta do download e execute:

```powershell
Get-FileHash .\SeasonalJobs_Setup.exe -Algorithm SHA256
```

Compare o valor exibido com o SHA-256 publicado em `SHA256SUMS.txt` na versão mais recente.
