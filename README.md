# Excelベースの自動化タスク用Pythonスクリプト

## プロジェクト概要

このプロジェクトは、Pythonの `pyautogui` ライブラリを使用して開発された自動化スクリプトです。ユーザーが作成したExcel表を読み込み、指定された自動化タスクを実行します。このスクリプトは、繰り返し作業を自動化し、作業効率を向上させることを目的としています。

## 特徴

- **Excel統合**: Excelファイルから直接データを読み込み、自動化処理に利用します。
- **`pyautogui` を利用**: `pyautogui` ライブラリを活用して、ユーザーの操作を模倣し、自動化タスクを実行します。
- **カスタマイズ可能**: ユーザーが特定のニーズに合わせてスクリプトを簡単にカスタマイズできます。
- **実行ファイルの提供**: ユーザーがPython環境を設定せずに利用できるように、実行可能なEXEファイルも提供しています。
- **ガーベージコレクションの最適化**: スクリプトは垃圾ファイル回收を最適化しており、システムリソースの効率的な使用を確保しています。

## インストール方法

```bash
git clone https://github.com/xlbljz/waterRPA/
cd waterRPA
pip install -r requirements.txt
```

## 使用方法

1. 自動化したいタスクの詳細をExcelファイルに記入します。
2. スクリプトを実行します：

   ```bash
   python waterRPA.py
   ```

## 依存関係

プロジェクトの依存関係は `requirements.txt` ファイルに記載されています。

## 貢献方法

貢献を希望する場合は、以下の手順に従ってください：

1. プロジェクトをフォークします。
2. 新しいブランチを作成します (`git checkout -b feature/AmazingFeature`)。
3. 変更をコミットします (`git commit -m 'Add some AmazingFeature'`)。
4. ブランチにプッシュします (`git push origin feature/AmazingFeature`)。
5. プルリクエストを開きます。
