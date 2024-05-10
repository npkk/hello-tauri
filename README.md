# Hello-Tauri

Tauriことはじめ用リポジトリ

.devcontainerで構築済み

コンテナに入ったら[localhost:8080](localhost:8080)でlite-desktopを開く

bunをinstallする

```
curl -fsSL https://bun.sh/install | bash
source $HOME/.bashrc
```

↓コマンドをlite-desktop上で叩くとtauriが起動する

```
bun tauri dev
```

フロントエンド側はhot reloadに対応しているが、Rust側は対応していない模様