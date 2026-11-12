### Scanovich · an applied AI lab · AI that a person can sign

We build AI-operated workflows where a model does the reading and a person signs off:
- document intelligence;
- evidence-grounded agents;
- private inference that keeps data on your own hardware.

These repositories are how we think, written down as code.

#### How we think

- **No quote, no claim.** A finding the model cannot ground in the source is rejected, not
  discouraged. See [evidencegene-court](https://github.com/FUYOH666/evidencegene-court) and
  [precedent](https://github.com/FUYOH666/precedent).
- **A correction is a code change.** When a person overrides an AI, the override becomes a rule that
  is reviewed, tested against everything that already worked, and can be reverted. See
  [precedent](https://github.com/FUYOH666/precedent).
- **Publish what we measured, including when we were wrong.**
  - [What precedent's first version got wrong](https://github.com/FUYOH666/precedent/blob/main/docs/what-v1-got-wrong.md)
  - [negative results in agent-web-lab](https://github.com/FUYOH666/scanovich-agent-web-lab)
  - [the Services-BGE eval harness](https://github.com/FUYOH666/Services-BGE)
- **Runs on your hardware.** See [VoiceToText](https://github.com/FUYOH666/VoiceToText),
  [Services-BGE](https://github.com/FUYOH666/Services-BGE) and
  [call analytics](https://github.com/FUYOH666/Scanovich.ai-audio-call).

#### Showcases

| the problem | repository | one thing we measured | status |
|---|---|---|---|
| Human corrections to an AI judge go live untested | [**precedent**](https://github.com/FUYOH666/precedent) | the keyword rule our v1 learned breaks 3 of 112 verdicts; the gate blocks it, and the rule stating the real reason passes with 0 broken | released |
| AI forensics that cannot invent a finding | [**evidencegene-court**](https://github.com/FUYOH666/evidencegene-court) | found the documented implant on DFIR Madness Case 001 and rejected a planted fabricated finding, on a laptop with a local model | prototype |
| Retrieval you can measure before you trust it | [**Services-BGE**](https://github.com/FUYOH666/Services-BGE) | recall@1 0.861 for bge-m3 + Qwen3-Reranker-0.6B on its eval set, with every model swap compared in one table | released |
| How AI agents read the live web | [**agent-web-lab**](https://github.com/FUYOH666/scanovich-agent-web-lab) | a 4% baseline mention rate in AI search, and lift targets reported as not met | research |
| Voice typing that never leaves the Mac | [**VoiceToText**](https://github.com/FUYOH666/VoiceToText) | Whisper and Qwen3-ASR on MLX; audio never leaves the machine | released |
| Call analytics on infrastructure you control | [**call analytics**](https://github.com/FUYOH666/Scanovich.ai-audio-call) | speech recognition → LLM cleanup and classification → local QA artifacts, self-hosted | prototype |

#### Work with the lab

- **Correction review.** Send a sample of the decisions your reviewers overrode. We show which
  corrections are safe rules and which would have broken something (precedent).
- **Retrieval evaluation on your documents.** Measure your search or assistant on your own questions
  before you trust it (Services-BGE).
- **Private inference.** Speech and search that stay on your hardware (VoiceToText, Services-BGE).

→ [scanovich.ai/contact](https://scanovich.ai/contact/?ref=github-profile)

<sub>Also public: [attestrwa](https://github.com/FUYOH666/attestrwa) ·
[LocalScript](https://github.com/FUYOH666/LocalScript) ·
[scanovich-webUI](https://github.com/FUYOH666/scanovich-webUI)</sub>
