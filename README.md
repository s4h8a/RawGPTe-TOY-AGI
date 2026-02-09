# RawGPTe: AGI from Scratch

[![Training Status](https://img.shields.io/badge/training-live-green)]()
[![Phases Complete](https://img.shields.io/badge/phases-14%2F15-blue)]()
[![Parameters](https://img.shields.io/badge/parameters-153M-orange)]()

> **Not a chatbot. Not an LLM. A world model that learns physics from experience.**

## 🚀 What is This?

I spent 6 months building AGI from scratch in my bedroom.

**No OpenAI. No Google. No pre-trained models.**

Just PyTorch and a dream.

Here's what 14 phases of building a World Model looks like.

### Current AI (LLMs) is just autocomplete.

It doesn't understand:
- Physics
- Causality  
- Time
- Space

I wanted to build something that actually **UNDERSTANDS** the world, not just predicts text.

So I started from first principles.

## 📈 Phase 15 (Current): MASSIVE Scale-Up

**Before**: 77K parameters
**Now**: 153M parameters (2,000x larger)

- 12 transformer layers
- 8 attention heads
- 1024 hidden dimensions

Training live for 1-2 weeks straight.

This is where emergent capabilities appear.

### Current Status: Training RIGHT NOW

📊 **Epoch 1, Step 30,000+**
📉 **Loss**: -2.37 (improving)
⚡ **Speed**: 0.7 steps/sec on RTX 3090
💾 **Auto-checkpointing** every 100 steps

- 300,000 training transitions
- 10 diverse environments

**It's learning as we speak.**

## ✨ What Makes This NOT Just Another Neural Network

✅ **Triquetra architecture** (World + Agent + Critic)
✅ **Uncertainty quantification** (knows what it doesn't know)
✅ **Curiosity-driven exploration**
✅ **Temporal abstraction** (learns skills, not just steps)
✅ **Grounded language interface**

## 🎯 What It Can Do NOW

• Predict physics 10+ steps ahead
• Generalize across different environments
• Learn symbols from raw data
• Plan using learned models
• Estimate its own uncertainty

## 🚀 What It Will Do After Scale

• Zero-shot transfer to new tasks
• Long-horizon planning
• Real-time reasoning
• Genuine understanding

## 🏗️ Architecture Highlights

### The Triquetra Core

Three interconnected systems that mimic human cognition:

1. **World Model**: Predicts `State + Action → Next State`
2. **Agent**: Plans using learned models
3. **Critic**: Evaluates uncertainty and curiosity
4. **Memory**: Episodic + world-state
5. **Language**: Grounded in physical experience

### Scaled Model (Phase 15)
- 12 Transformer blocks
- 8 attention heads
- 1024 hidden dimensions
- Uncertainty quantification
- Temporal abstraction

## 📊 Live Training Metrics

| Metric | Value |
|--------|-------|
| Parameters | 153,000,000 |
| Architecture | 12-layer Transformer |
| Training Data | 300,000 transitions |
| Current Loss | -2.37 ↓ |
| Speed | 0.7 steps/sec |
| Training Status | 🔴 LIVE |

## 📈 14 Complete Phases

1. ✅ World model foundation
2. ✅ Constraint learning
3. ✅ Latent state structuring
4. ✅ Planning loop
5. ✅ Triquetra architecture
6. ✅ State discipline
7. ✅ Complex dynamics
8. ✅ Temporal abstraction
9. ✅ Curiosity-driven learning
10. ✅ Memory systems
11. ✅ Grounded language
12. ✅ Symbol emergence
13. ✅ Metacognition
14. ✅ Multi-world generalization
15. 🔄 **Scale-up (IN PROGRESS)**

## 🎯 Why This Matters

| Aspect | LLMs (GPT-4) | RawGPTe |
|--------|--------------|---------|
| Understanding | Statistical patterns | Causal physics |
| Generalization | Prompt-dependent | Environment-agnostic |
| Efficiency | Trillion parameters | 153M parameters |
| Grounding | Text only | Physical simulation |
| Uncertainty | Overconfident | Calibrated |

## 🚦 Roadmap to AGI

**Current**: AGI-adjacent foundation  
**Phase 16**: Visual perception  
**Phase 17**: Continuous control  
**Phase 18**: Lifelong learning  
**Phase 19**: Real embodiment  

**Estimate**: 2-5 years to AGI-adjacent system

## 🛠️ Quick Start

```bash
git clone https://github.com/s4h8a/RawGPTe-TOY-AGI
cd RawGPTe-TOY-AGI
pip install -r requirements.txt

# Run training
bash start_continuous_training.sh

# Monitor progress
python3 monitor.py
```

## 📝 Technical Details

### Why This Approach Works

Current Large Language Models (LLMs) like GPT-4 are fundamentally limited:
- They learn statistical correlations in text
- They lack causal understanding
- They cannot plan or reason about physics
- They require massive amounts of data (trillions of tokens)

RawGPTe takes a different approach:

**Physics First**: Train on simulated environments where the rules are clear  
**Learn Causality**: Understand how actions affect the world  
**Build Understanding**: Develop true comprehension, not pattern matching  
**Scale Efficiently**: Achieve more with 153M parameters than LLMs with trillions

### The Triquetra Design

```
State + Action → World Model → Predicted Next State
                      ↓
              Uncertainty Quantifier
                      ↓
            Is prediction uncertain?
                      ↓
        YES: Trigger Curiosity → Exploration
        NO: Use for Planning → Agent Actions
```

This loop creates genuine curiosity-driven learning.

## 🔮 Vision: Real AGI

The ultimate goal isn't a better chatbot. It's a system that:

1. **Understands physics** - Can reason about real-world interactions
2. **Plans ahead** - Solves multi-step problems
3. **Learns from experience** - Improves without retraining
4. **Communicates clearly** - Language grounded in real understanding
5. **Knows its limits** - Aware of uncertainty
6. **Remains safe** - Can be aligned with human values

## 📞 Contact

- **Email**: shn.koshy@gmail.com
- **GitHub**: [@s4h8a](https://github.com/s4h8a)

## 📄 License

MIT License - See LICENSE file for details

---

**Status**: 🔴 Training Live | Last Updated: 2026-02-09