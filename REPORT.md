# Lab 21 — Evaluation Report

**Học viên**: Lê Quốc Bảo — 2A202600561
**Ngày nộp**: 25/06/2026
**Submission option**: B (HF Hub) 

## 1. Setup
- **Base model**: <điền model bạn chọn — vd: `unsloth/Llama-3.2-3B-Instruct-bnb-4bit`>
- **Dataset**: <tên dataset>, <số samples> (X train + Y eval)
- **max_seq_length**: <số> (p95 = <số>, rounded up)
- **GPU**: <Tesla T4 / L4 / A100>, <X> GB VRAM
- **Training cost**: $<số> (~<phút> @ $<rate>/hr)
- **HF Hub link** : https://huggingface.co/lebao135/qwen2.5-3b-vi-lab21-r16/

## 2. Rank Experiment Results

| Rank | Trainable Params | Train Time | Peak VRAM | Eval Loss | Perplexity |
|------|-----------------|------------|-----------|-----------|------------|
| 8    | ...             | ... min    | ... GB    | ...       | ...        |
| 16   | ...             | ... min    | ... GB    | ...       | ...        |
| 64   | ...             | ... min    | ... GB    | ...       | ...        |
| Base | -               | -          | -         | ...       | ...        |

## 3. Loss Curve Analysis
[Đính kèm loss_curve.png]
- Quan sát: <có / không có overfitting? Lý do?>

## 4. Qualitative Comparison (5 examples)

### Example 1
**Prompt**: ...
**Base**: ...
**Fine-tuned (r=16)**: ...
**Nhận xét**: <improved / same / degraded?>

[... lặp lại 4 examples nữa ...]

## 5. Conclusion về Rank Trade-off

<Tối thiểu 100 từ. Trả lời 3 câu hỏi:>
- Rank nào cho ROI tốt nhất trên dataset này? Tại sao?
- Khi nào tăng rank không còn cải thiện perplexity (diminishing returns)?
- Recommendation: nếu deploy production, bạn chọn rank nào? Tại sao?

## 6. What I Learned
- <Bullet 1: insight cá nhân>
- <Bullet 2: insight cá nhân>
- <Bullet 3: optional>
