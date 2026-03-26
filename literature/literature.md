# Literature

## Background on LLMs, GPTs, and transformers

- J. MacCormick (2026). _Thinking AI: How Artificial Intelligence Emulates Human Understanding_. Princeton University Press. [chapter 10](https://dickinson0.sharepoint.com/:b:/r/sites/COMP560spring2026/Shared%20Documents/General/literature/maccormick-thinkingAI-ch10.pdf?csf=1&web=1&e=fuMXU7) (link is restricted to members the COMP560 MS Team), [PUP](https://press.princeton.edu/books/hardcover/9780691191737/thinking-ai), [Amazon](https://www.amazon.com/Thinking-AI-Artificial-Intelligence-Understanding-ebook/dp/B0FTKHZ676/).
  * This is a chapter from a general audience book about modern AI systems. This chapter explains how a GPT works, employing simple descriptions that require no computer science background.  



## Our original inspiration: "Revealing the mystery behind chain of thought"

- Feng, G., Zhang, B., Gu, Y., Ye, H., He, D., &amp; Wang, L. (2023). Towards revealing the mystery behind chain of thought: a theoretical perspective. _Advances in Neural Information Processing Systems_, 36, 70757-70798. [pdf at neurips.cc](https://proceedings.neurips.cc/paper_files/paper/2023/file/dfc310e81992d2e4cedc09ac47eff13e-Paper-Conference.pdf). [Teams discussion channel](https://teams.microsoft.com/l/channel/19%3A6df87f59d4de410b8a2a75e94f6b0c7c%40thread.tacv2/Feng2023?groupId=327c5cf0-93db-45ce-be36-d648004b666f&tenantId=6232b055-76b9-4c13-9b88-b562ae7db6fb).
  * This is the original motivation for our research project. It demonstrates how certain simple tasks such as arithmetic or solving linear equations can be tackled with chain-of-thought reasoning and how/why that is beneficial. We aim to replicate or extend these results in the specific domain very small simple tasks and small transformer models that can be trained on consumer laptops in only a few minutes. (The paper contains some very interesting theoretical results, but we focus more on the practical experiments.)

### Other CoT analyses

- Shojaee, P., Mirzadeh, I., Alizadeh, K., Horton, M., Bengio, S., & Farajtabar, M. (2025). [*The Illusion of Thinking: Understanding the Strengths and Limitations of Reasoning Models via the Lens of Problem Complexity*](https://arxiv.org/abs/2506.06941). arXiv:2506.06941.
  * This paper analyses large reasoning models (LRMs) -- the successors to chain of thought reasoning in LLMs. It identifies certain properties of LRMs, such a complete accuracy collapse after a level of difficulty is reached in a certain puzzle, and the fact that exact algorithms are typically not employed.

_suggested by Aziz_

## Elementary properties of the attention operator

- Elhage, et al., "A Mathematical Framework for Transformer Circuits", Transformer Circuits Thread, 2021. [html at Anthropic](https://transformer-circuits.pub/2021/framework/index.html)


## Connections between LLMs and biology

- Lindsey, et al., "On the Biology of a Large Language Model", _Transformer Circuits_, 2025. [html at Anthropic](https://transformer-circuits.pub/2025/attribution-graphs/biology.html)

_suggested by Aziz_

## Tackling simple arithmetic using GPT architectures

- Baeumel, Tanja, Josef van Genabith, and Simon Ostermann. "The lookahead limitation: Why multi-operand addition is hard for LLMs." arXiv preprint arXiv:2502.19981 (2025). [pdf at arXiv](https://arxiv.org/pdf/2502.19981).


## Representation of concepts within LLMS

- Dong, Z., Zhou, Z., Liu, Z., Yang, C., & Lu, C. (2025). [*Emergent Response Planning in LLMs*](https://arxiv.org/abs/2502.06258). arXiv:2502.06258 [cs.CL].
  * This paper shows that large language models (LLMs) trained only to predict the next token nonetheless encode representations that reveal future planning behavior across their entire output, suggesting latent capabilities for anticipating structure, content, and overall response attributes beyond the next token.

_suggested by Aziz_

## The effect of prompts

- Leviathan, Y., Kalman, M., & Matias, Y. (2025). [*Prompt Repetition Improves Non-Reasoning LLMs*](https://arxiv.org/abs/2512.14982). arXiv:2512.14982 [cs.LG].
  * The authors demonstrate that simply repeating an input prompt (i.e., duplicating the text) can improve the performance of popular language models on non-reasoning benchmarks without increasing the number of generated tokens or inference latency.

_suggested by Aziz_

## Augmenting transformer with memory

- Burtsev, M. S., Kuratov, Y., Peganov, A., & Sapunov, G. V. (2021). [*Memory Transformer*](https://arxiv.org/abs/2006.11527). arXiv:2006.11527 [cs.CL].
  * This paper introduces transformer architectures augmented with memory tokens that help capture both local and global sequence information, leading to improved performance on tasks like machine translation and language modeling by effectively storing and attending to non-local representations.

_suggested by Aziz_

## Tool use

- Li, W., Li, D., Dong, K., Zhang, C., Zhang, H., Liu, W., Wang, Y., Tang, R., & Liu, Y. (2025). [*Adaptive Tool Use in Large Language Models with Meta-Cognition Trigger*](https://arxiv.org/abs/2502.12961). arXiv:2502.12961 [cs.CL].
  * Proposes a strategy for when to invoke external tools within an LLM

_suggested by Biruk_


<!-- start at Hemanth -->
