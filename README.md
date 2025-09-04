# MBP: Mission Brief Protocol (Runtime v1.0)

MBP is a structured execution protocol for AI models that replaces memory sprawl and prompt bloat with deterministic, auditable Capsules.

## 🔧 Runtime Architecture

- **Stateless execution** (no chat history)
- **Scoped memory** with TTLs and identity pinning
- **Capsule Chain**: Maestro → Engine → Verify+
- **Echo Log**: 72h buffer for transient emotion/context
- **Capsule Chains**: Hallucination Safety, Bias Balancer, Creative Synthesis

## 📦 Included Components

```
protocol/             → MBP prompt (Goal, Constraints, Facts, Directive)
runtime/              → Stateless rules, Capsule Chain config
memory/               → Sam memory kernel config (TTLs, scope)
chains/               → Capsule Chains logic
echo/                 → Echo Log config and policy
LICENSE               → Apache License 2.0
README.md             → This file
CONTRIBUTING.md       → Guidelines for improving MBP
.gitignore            → Runtime and Python ignores
```

## 📜 License

MBP is licensed under the [Apache License 2.0](LICENSE).

## 👤 Author

Created by Amul Bham  
Contact: amul.bham@gmail.com  
Version: `v1.0.0`  
Status: Public Release

