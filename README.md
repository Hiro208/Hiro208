### Hi, I'm Guangjian (Jayden) Dong 👋

M.S. in Data Science at **New York University**. I work on **LLM inference serving**, **GPU / cluster scheduling**, and the backend systems around them, and I contribute to the **vLLM ecosystem**.

---

#### 🔧 Featured projects

**[sglang-inference-optimization](https://github.com/Hiro208/sglang-inference-optimization)** · SGLang, CUDA, Mooncake, NCCL
- Fused MoE SiLU, gating, absmax and FP8 conversion into one CUDA kernel: **−35.5%** kernel latency
- Prefill/decode disaggregation over Mooncake + InfiniBand RDMA: SLO attainment **52.9% → 99.2%**, SLO-meeting throughput **+82.1%**
- Deadline-aware scheduling (**+11.8%**) and speculative decoding (**+21.3%** throughput), measured with an audited benchmark harness

**[research-agent-framework](https://github.com/Hiro208/research-agent-framework)** · Python, LangGraph, MCP, RAG
- Query plans compiled into parallel sub-agent DAGs: **−57.2%** latency, **−32.8%** cost on live-web tasks
- Hybrid retrieval with reranking and sub-agent context isolation: **−79.2%** main-agent tokens
- Citation checks, prompt-injection guardrails and human-in-the-loop approval: false acceptance **80% → 0%** on 120 eval cases

**[cold-chain-monitor](https://github.com/Hiro208/cold-chain-monitor)** · Go, Kafka, PostgreSQL, Redis, EKS, Terraform
- Telemetry from 2,000 simulated reefers through Kafka; breach detection **p99 under 1 s** in the CI end-to-end test
- Idempotent at-least-once ingest, Lambda alert routing, S3 archive, partner webhooks behind API Gateway

---

#### 🌱 Open source

| Project | Merged pull requests |
| --- | --- |
| [vLLM-Omni](https://github.com/vllm-project/vllm-omni) | [#7390](https://github.com/vllm-project/vllm-omni/pull/7390) · [#7349](https://github.com/vllm-project/vllm-omni/pull/7349) · [#7384](https://github.com/vllm-project/vllm-omni/pull/7384) · [#7341](https://github.com/vllm-project/vllm-omni/pull/7341) — config regressions, LoRA bind checks, MiniCPM-o 4.5 multimodal embeddings |
| [AIBrix](https://github.com/vllm-project/aibrix) | [#2694](https://github.com/vllm-project/aibrix/pull/2694) · [#2699](https://github.com/vllm-project/aibrix/pull/2699) — integer overflow in Go config, Redis sync busy loop |
| [Semantic Router](https://github.com/vllm-project/semantic-router) | [#3711](https://github.com/vllm-project/semantic-router/pull/3711) · [#3699](https://github.com/vllm-project/semantic-router/pull/3699) — domain score lookup, React lazy-loading loop |

In review: [volcano-sh/volcano#6224](https://github.com/volcano-sh/volcano/pull/6224) — scheduler status publication and node-filtering performance.

---

#### 📄 Publications

- **G. Dong.** ReKV: Overlapping Quantized KV Transfer and Suffix Recomputation. *ICASSP 2027, under review.*
- **G. Dong.** Motion Recency Maps for Zero-Shot Traffic Accident Localisation in Fixed Surveillance Cameras. *CVPR 2026 AUTOPILOT Workshop.*

---

#### 🧰 Stack

`Python` `Go` `C++` `CUDA` `PyTorch` `vLLM` `SGLang` `Kubernetes` `Volcano` `Slurm` `Kafka` `PostgreSQL` `Redis` `AWS` `Terraform`

📫 [jayden26017@gmail.com](mailto:jayden26017@gmail.com)
