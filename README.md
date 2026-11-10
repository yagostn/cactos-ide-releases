# Cactos IDE — Downloads oficiais

[![Versão](https://img.shields.io/badge/versão-v0.2.0--beta.1-16c98d)](https://github.com/yagostn/cactos-ide-releases/releases/tag/v0.2.0-beta.1)
[![Canal](https://img.shields.io/badge/canal-Beta-f59e0b)](https://github.com/yagostn/cactos-ide-releases/releases)
[![Plataformas](https://img.shields.io/badge/plataformas-macOS%20%7C%20Windows%20%7C%20Linux-737373)](https://github.com/yagostn/cactos-ide-releases/releases)

Este repositório publica os instaladores, checksums e manifestos de atualização do **Cactos IDE**. O código-fonte e a documentação de desenvolvimento ficam no repositório principal privado.

> A versão atual é Beta e pode conter falhas. Faça backup dos projetos importantes antes de testar.

## Versão atual

**Cactos IDE v0.2.0-beta.1** · publicada em 10 de novembro de 2026

| Sistema | Arquitetura | Instalador |
| --- | --- | --- |
| macOS | Apple Silicon (M1 ou mais recente) | [Baixar DMG](https://github.com/yagostn/cactos-ide-releases/releases/download/v0.2.0-beta.1/Cactos-IDE_0.2.0-beta.1_macos-arm64.dmg) |
| macOS | Intel x64 | [Baixar DMG](https://github.com/yagostn/cactos-ide-releases/releases/download/v0.2.0-beta.1/Cactos-IDE_0.2.0-beta.1_macos-x64.dmg) |
| Windows | x64 | [Baixar instalador EXE](https://github.com/yagostn/cactos-ide-releases/releases/download/v0.2.0-beta.1/Cactos-IDE_0.2.0-beta.1_windows-x64.exe) |
| Linux | x64 | [Baixar AppImage](https://github.com/yagostn/cactos-ide-releases/releases/download/v0.2.0-beta.1/Cactos-IDE_0.2.0-beta.1_linux-x64.AppImage) |

[Ver notas da versão](https://github.com/yagostn/cactos-ide-releases/releases/tag/v0.2.0-beta.1) · [Verificar SHA-256](https://github.com/yagostn/cactos-ide-releases/releases/download/v0.2.0-beta.1/SHA256SUMS.txt) · [Site oficial](https://cactoside.vercel.app)

## Integridade e assinatura

- Todos os arquivos publicados têm SHA-256 no `SHA256SUMS.txt` da release.
- Os pacotes usados pelo atualizador automático possuem assinatura própria do Tauri.
- Os DMGs atuais usam assinatura ad hoc e não foram notarizados pela Apple.
- O instalador Windows atual não possui assinatura Authenticode e pode exibir um aviso do SmartScreen.

## Instalação

### macOS

Abra o `.dmg` correspondente ao processador e arraste o Cactos IDE para **Aplicativos**. O Gatekeeper pode pedir confirmação adicional nesta Beta.

### Windows

Execute o instalador `.exe`. Confirme o aviso do SmartScreen somente se o arquivo veio desta página e o checksum confere.

### Linux

Torne o AppImage executável e abra o arquivo:

```bash
chmod +x Cactos-IDE_0.2.0-beta.1_linux-x64.AppImage
./Cactos-IDE_0.2.0-beta.1_linux-x64.AppImage
```

## Canais

- **Alpha:** experimentos iniciais e compatibilidade limitada.
- **Beta:** versões de teste recomendadas para avaliação.
- **Stable:** será usado após a homologação pública.

Os arquivos com `_updater` e o `latest.json` são consumidos automaticamente pelo aplicativo e não são instaladores manuais.

## Suporte

Relate problemas no repositório principal do Cactos IDE ou pelo canal oficial informado no aplicativo. Inclua sistema operacional, arquitetura, versão e passos para reproduzir, sem anexar tokens ou arquivos `.env`.
