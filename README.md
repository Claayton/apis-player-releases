<p align="center">
  <img src="https://raw.githubusercontent.com/Claayton/apis-player-app/main/app/src/main/res/drawable-nodpi/ic_launcher_fg.png" alt="Apis Player" width="120" />
</p>

<h1 align="center">Apis Player — Releases</h1>

<p align="center">
  Canal oficial de download e atualização do <strong>Apis Player</strong> para Android e Android TV.
</p>

---

## O que é este repositório

Este repositório **não contém código-fonte**. Ele existe apenas para hospedar os APKs assinados do Apis Player, de forma pública, para que o aplicativo consiga verificar e baixar atualizações automaticamente.

O código permanece em um repositório privado.

## Como baixar

1. Abra a aba [**Releases**](../../releases)
2. Escolha a versão mais recente
3. Em **Assets**, baixe o arquivo `app-direct-release.apk`
4. Confira o SHA-256 em `SHA256SUMS.txt` (opcional, mas recomendado)
5. Instale o APK no dispositivo

> Ao instalar, o Android pode pedir permissão para "instalar apps de fontes desconhecidas". Isso é esperado para qualquer app distribuído fora da Play Store.

## Atualizações

O próprio aplicativo verifica este repositório ao abrir. Quando existe uma versão mais nova, ele oferece a atualização e instala o APK baixado.

Não é necessário baixar manualmente a cada versão.

## Verificar a integridade do download

```bash
sha256sum -c SHA256SUMS.txt
```

Ou, no Windows (PowerShell):

```powershell
Get-FileHash .\app-direct-release.apk -Algorithm SHA256
```

Compare o resultado com o valor publicado em `SHA256SUMS.txt`.

## Requisitos

- Android 6.0 (API 23) ou superior
- Android TV é suportado

## Aviso

O Apis Player não fornece, hospeda ou distribui conteúdo. Ele apenas reproduz a fonte configurada pelo próprio usuário (Xtream Codes ou lista M3U).
