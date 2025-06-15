# 🧠 労力をかけずに、実力は磨いて、生成AI活用で国際学会発表を乗り切ろう

## 📅 発表情報

| 項目 | 詳細 |
|------|------|
| **発表番号** | [SY37-5] |
| **シンポジウム** | [SY37] 生成AIを「正しく」使って論文を効率的に作成しよう<br>－若手精神科医のための臨床研究事始め（第三弾） |
| **日時** | 2025年6月19日（木）15:45 〜 17:45 |
| **会場** | L会場（神戸ポートピアホテル 本館 B1階 偕楽2） |
| **主催** | PCN Reports編集委員会 |
| **発表者** | 宋龍平（岡山県精神科医療センター） |

## 📋 概要

国際学会での発表に不安を持つ方向けに、生成AIを使った具体的な準備方法を紹介するプレゼンテーションです。発表者自身の2024年メルボルンでの国際学会発表経験をもとに、生成AIを活用して効率的に発表準備を行う手法を実演・解説します。

### 🎯 労力はかけずに

#### 4つのステップ
1. **英語スライド作成** - 論文や日本語スライドからChatGPT/Claude/Geminiで英語スライドを生成
2. **トークスクリプト作成** - 英語スライドから発表用原稿を生成AIで作成
3. **発表音声生成** - Gemini AI Studioでトークスクリプトから音声を生成
4. **質疑応答練習** - ChatGPTのAdvanced Voice Modeで実践的な会話練習

#### デモ動画
1–3: https://youtu.be/GRagMGKmN2s
4: https://youtu.be/QgRSgsPpGX4

### 実力は磨いて
- 論文を名刺代わりに活用
- 事前のネットワーク構築
- 専門家としての適切な評価能力の重要性

## 📁 ファイル構成

### 📄 プレゼンテーション資料
- [`2025JSPN_PCNR_outline.md`](presentation/2025JSPN_PCNR_outline.md) - プレゼンテーションの基となったアウトライン
- [`2025JSPN_PCNR_Presentation.md`](presentation/2025JSPN_PCNR_Presentation.md) - Marp形式の中間プレゼンテーション資料
- [`2025JSPN_PCNR_Presentation.pdf`](presentation/2025JSPN_PCNR_Presentation.pdf) - PDF形式の中間プレゼンテーション資料
- [`2025JSPN_PCNR_Presentation.pptx`](presentation/2025JSPN_PCNR_Presentation.ppptx) - pptx形式の最終プレゼンテーション資料（Movie含む）

### 📂 生成コンテンツフォルダ
- `generated/text/` - 生成AIで作成されたテキストファイル
- `generated/speech/` - 生成AIで作成された音声ファイル
- `generated/movie/` - 生成AIで作成された動画ファイル

## 🔗 参考リンク・ツール

### 使用した生成AIツール
- **Claude AI**: スライド・トークスクリプト生成
  - [プレゼンテーション作成チャット](https://claude.ai/chat/4b815f8c-5948-4410-bcd5-a8eafff49c81)
  - [Markdownアーティファクト](https://claude.ai/public/artifacts/20c4be74-2d07-4b65-ae19-880df928a01b)
  - [英語トークスクリプト](https://claude.ai/public/artifacts/98b7efe6-773b-47d0-9fca-72fde0697958)
  - [日本語トークスクリプト](https://claude.ai/public/artifacts/e39145fe-1ed5-4cd0-b229-47e5869e5108)

- **Gemini AI Studio**: 音声生成
  - [Generate Speech](https://aistudio.google.com/generate-speech)

- **ChatGPT**: 会話練習
  - genkAIjokyo|ChatGPT/Claudeで論文作成と科研費申請  
    - [ChatGPTのVoice Modeでリアルな会話練習](https://note.com/genkaijokyo/n/n64efcfcd6cdd)
        - [英会話練習プロジェクト](https://chatgpt.com/g/g-p-684e7519facc819189b652c8e407c5a4-ying-hui-hua-lian-xi/project)
        - [質疑応答練習プロジェクト](https://chatgpt.com/g/g-p-684e76f420e48191aba5c4ddbbf46bce-2025jspn-demo-qanda/project)

### プレゼンテーション作成ツール
- [Marp Web Editor](https://marpwebeditor.app/)

## 📦 リポジトリ情報

### GitHubリポジトリ
- **URL**: https://github.com/Ryuhei-So/2025JSPN_PCNR_Presentation_in_English
- **公開設定**: パブリック
- **説明**: 生成AI活用で国際学会発表を乗り切る方法 - 日本精神神経学会2025年発表資料

### Git LFS設定
このリポジトリでは、大きなファイルを効率的に管理するためにGit Large File Storage (LFS) を使用しています。

**LFS管理対象ファイル:**
- `*.mp4` - 動画ファイル（デモ動画など）
- `*.pptx` - PowerPointプレゼンテーションファイル

**クローン時の注意:**
```bash
# Git LFSが必要です
git lfs install
git clone https://github.com/Ryuhei-So/2025JSPN_PCNR_Presentation_in_English.git
```

---

**発表者について**  
宋龍平（岡山県精神科医療センター）  
[Researchmap](https://researchmap.jp/rso)
[Google Scholar](https://scholar.google.co.jp/citations?user=F5Q3kqoAAAAJ&hl=ja)