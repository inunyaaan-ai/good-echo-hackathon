# 🌱 GOOD ECHO — シミュレーション一覧

**AUTOMATA Space ハッカソン 2026 / チーム：GOOD ECHO**

> 「善性を育む環境を設計したら、社会はどう変わるか？」  
> 強制なく、環境の側に小さな仕掛けを置くことで、善性が自然と引き出されるか検証したマルチエージェントシミュレーション群。

---

## 📦 シミュレーション一覧

### 🚀 ISS（国際宇宙ステーション）

| シミュレーション名 | 担当者 | エージェント | ステップ | LLMモデル | 創発 | リポジトリ |
|---|---|---|---|---|---|---|
| ISS メインシミュレーション | karesansuiさん | 20人 | 100 | Claude Sonnet 4.6 | ◯ | [📁 GitHub](https://github.com/karesansui-u/hackathon-singulab-inu) |
| ISS 空間移動シミュレーション（50step） | バッツさん | 10人 | 50 | Cursor Composer 2 | ◯ | [📁 GitHub](https://github.com/Hop-Step-Jump/good_echo_iss_sim_cursor_50s_no_accident) |
| ISS 空間移動シミュレーション（事故対応版・100step） | バッツさん | 10人 | 100 | Cursor Composer 2 | △ | [📁 GitHub](https://github.com/Hop-Step-Jump/good_echo_iss_sim_cursor_100s_w_accident) |
| ISS 心理乖離測定版 | REREさん | 10人 | 50日 | qwen2.5:7b (Ollama) | △ | [📁 GitHub](https://github.com/reireichel01/goodecho_r) |

### 🌳 公園

| シミュレーション名 | 担当者 | エージェント | ステップ | LLMモデル | 創発 | リポジトリ |
|---|---|---|---|---|---|---|
| 公園「話しかけていい」ベンチ vs 通常ベンチ | もんさん | 10人 | 多数 | gpt-oss:20b (Ollama) | ◯ | [📁 GitHub](https://github.com/ops324/happy-to-chat-bench-simulation) |

---

## 🔬 創発の定義

| 記号 | 意味 |
|---|---|
| ◯ | 設計外の行動パターン（自発的慣習形成・橋渡し役出現・ナッジ文化の撤去後持続など）を確認 |
| △ | 局所的な自発行動はあるが、全体的な創発パターンとして断定不十分、または集計中 |

---

## 💡 プロジェクト概要

善性 ＝ **ego**（自分が気持ちいい）× **共感**（相手を感じる）× **協力**（一人では難しいことを一緒にやる）

ナッジ（行動経済学の概念）を環境に配置し、強制・命令なしに善性が育つかをLLMマルチエージェントで検証。

**実験空間：** ISS（閉鎖高ストレス）／ 公園（開放的な日常空間）

---

*AUTOMATA Space Hackathon 2026 — Team GOOD ECHO*
