# angular-tutorial

# Angular 公式ドキュメントチュートリアル

このリポジトリは、Angular 公式ドキュメントのチュートリアルを実践するために作成されました。環境構築の手順に従って、必要なツールをインストールしてください。

## 環境構築手順

以下の手順に従って、環境を構築してください。

### 1. Windows PowerShell を管理者権限で開く

このリポジトリのセットアップ手順は、Windows PowerShell を使用します。以下の手順に従って PowerShell を管理者権限で開いてください。

1. スタートメニューで "PowerShell" と検索します。
2. 右クリックして、「管理者として実行」を選択します。

### 2. Chocolatey をインストールする

以下のコマンドを管理者権限で開いた PowerShell で実行し、Chocolatey をインストールしてください。

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

### 3. Visual Studio Code (VSCode) のインストール

以下のコマンドを管理者権限の PowerShell で実行して、VSCode をインストールします。

```powershell
choco install vscode
```

### 4. Node.js のインストール

以下のコマンドを管理者権限の PowerShell で実行して、Node.js をインストールします。
```powershell
choco install nodejs
```

### 5. Git のインストール

以下のコマンドを管理者権限の PowerShell で実行して、Git をインストールします。
```powershell
choco install git
```

### 6. Python のインストール

以下のコマンドを管理者権限の PowerShell で実行して、Python をインストールします（バージョン 3.11.4）。
```powershell
choco install python --version 3.11.4 -y
```

以上で環境構築が完了しました。これらの手順を実行することで、Angular 公式ドキュメントのチュートリアルをスムーズに進めることができます。