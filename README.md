# LUMIÈRE SKIN — Design Tokens

Tokens Studio for Figma 用デザイントークンリポジトリ。

## 構成
- `tokens.json` … Tokens Studio v1.1.0 形式（global / components / motion）

## Tokens Studio から同期する手順
1. Figma で `Tokens Studio for Figma` プラグインを起動
2. 右上 ⚙️ → `Sync providers` → **`+ New`** → **`GitHub`**
3. 入力：
   - **Name**: `LUMIERE`
   - **Personal Access Token**: GitHub PAT（`repo` スコープのみ）
   - **Repository**: `<your-account>/lumiere-design-tokens`
   - **Default Branch**: `main`
   - **File Path**: `tokens.json`
4. `Save` → `Pull from GitHub`

## 編集フロー
- Figma 側で変更 → Tokens Studio の `Push to GitHub` で反映
- ローカルで編集 → `git push` → Figma 側で `Pull from GitHub`
