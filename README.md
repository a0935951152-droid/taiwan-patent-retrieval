
# 🇹🇼 台灣法律與專利 AI 微調系列 (Lab 01 - 05)

本倉庫記錄了使用 **NVIDIA RTX 4070 Ti SUPER** 進行的一系列 Embedding 與 RAG 微調實驗。

## 📁 內容清單
- **Lab 01-03**: 基礎檢索與資料處理
- **Lab 04**: 模型微調實戰 (MNRL vs Triplet Loss)
- **Lab 05**: 完整評估與指標分析

## 📊 Lab 04 核心實驗數據 (Patent QA)
| Model | Recall@1 | Recall@5 | MRR@5 (忠誠度) | NDCG@5 |
| :--- | :---: | :---: | :---: | :---: |
| **Base (Original)** | 0.44 | 0.65 | 0.5296 | 0.5841 |
| **MNRL (Pair-v2)** | **0.75** | **0.99** | **0.8537** | **0.8884** |
| **Triplet (Final)** | 0.37 | 0.57 | 0.4373 | 0.4702 |

## 💻 訓練硬體
- **GPU**: NVIDIA GeForce RTX 4070 Ti SUPER (16GB VRAM)
