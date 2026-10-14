# 參考資料（References）

證據等級：**A**＝有控制變因的對照實驗／學術評測；**B**＝生產系統內部評測；**C**＝案例、觀點、實務經驗。

## 原始討論

1. Martin (@cantcomputer), [X 貼文 #2110116906581848217](https://x.com/i/web/status/2110116906581848217)，2026-10-13 — 徵求「agent swarm 做得到、單 agent 做不到」的案例（討論題，67 則回覆）。〔C〕

## 支持多代理的證據

2. Anthropic Engineering, [How we built our multi-agent research system](https://www.anthropic.com/engineering/multi-agent-research-system), 2025-06 — 內部評測多代理較單一 Opus 4 高 90.2%；多代理 token 約為聊天 15×；同步瓶頸與「多數 coding 不適合」警語。〔B〕
3. [Capable language models can outgrow the benefits of collaboration](https://www.nature.com/articles/s42256-026-01268-y), *Nature Machine Intelligence*, 2026 — 跨領域對照：Finance Agent +57~+81%、PlanCraft −39~−70%、SWE-bench −1~−13%；協調通訊量隨 agent 數超線性成長。〔A〕
4. Li et al., [More Agents Is All You Need](https://openreview.net/forum?id=bgzUSZ8aeg), TMLR 2024 — 抽樣式（best-of-n）多 agent 的效能提升；注意與「協作式分工」不同。〔A〕

## 質疑多代理的證據

5. [Single-Agent LLMs Outperform Multi-Agent Systems on Multi-Hop Reasoning Under Equal Thinking Token Budgets](https://arxiv.org/abs/2604.02460), arXiv — 控制思考 token 後單代理追平或勝出；多代理優勢常來自未記帳的額外運算。〔A〕
6. [Should we be going MAD? A Look at Multi-Agent Debate Strategies for LLMs](https://arxiv.org/abs/2311.17371) — 多代理辯論無法可靠勝過 self-consistency / ensembling。〔A〕
7. Cemri et al., [Why Do Multi-Agent LLM Systems Fail?（MAST）](https://arxiv.org/abs/2503.13657), NeurIPS 2025 — 1600+ 軌跡、14 種失敗模式、3 大類；MAS 在熱門基準上的提升通常很小。〔A〕
8. Gao et al., [Single-agent or Multi-agent Systems? Why Not Both?](https://arxiv.org/abs/2505.18286), 2025 — MAS 收益隨模型能力提升而遞減；hybrid 級聯 +1.1~12% 準確率、−20% 成本。〔A〕
9. Yan (Cognition), [Don't Build Multi-Agents](https://cognition.ai/blog/dont-build-multi-agents), 2025-06 — 上下文割裂論：共享 context 是長程 agent 的可靠性核心。〔C〕
10. Neubig (OpenHands), [Don't Sleep on Single-agent Systems](https://openhands.dev/blog/dont-sleep-on-single-agent-systems), 2024-09 — 把一個 agent 變強優於養一群弱 agent。〔C〕

## 方法論與延伸閱讀

11. Anthropic Engineering, [Building effective agents](https://www.anthropic.com/engineering/building-effective-agents) — 先用最簡單的形狀（workflow 優於 agent），需要時再升級。
12. OpenAI, [BrowseComp](https://openai.com/index/browsecomp/) / Wei et al., [arXiv 2504.12516](https://arxiv.org/abs/2504.12516) — 瀏覽型搜尋基準；Anthropic 用它分析 token 用量對表現的解釋力。
13. [MultiAgentBench](https://arxiv.org/abs/2503.01935), ACL 2025 — 多 agent 協作與競爭的評測框架。

---

### 如何引用本站

本站是對上述來源的**二手整理與教學改寫**，結論以原始論文為準。討論題本質（原貼文）尚無定論——引用時請標明「討論中」而非「已證實」。
