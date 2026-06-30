# Script OS

Version: 1.0

---

# What is Script OS?

Script OS là một hệ thống hỗ trợ viết script YouTube theo quy trình chuẩn hóa.

Thay vì viết theo cảm tính, Script OS chia toàn bộ quá trình thành các module độc lập:

- Playbook
- Knowledge Base
- Script Audit

Mỗi module có một nhiệm vụ riêng và phối hợp với nhau để tạo ra một script hoàn chỉnh.

---

# Architecture

```text
                INPUT
                  │
                  ▼
            Playbook
                  │
                  ▼
          Knowledge Base
                  │
                  ▼
         Generate Script
                  │
                  ▼
          AI Voice Optimize
                  │
                  ▼
            Script Audit
                  │
                  ▼
           Final Script
```

---

# Folder Structure

```text
Script OS

├── README.md
├── Playbook/
├── Knowledge Base/
├── Script Audit/
└── Examples/
```

---

# Playbook

Playbook định nghĩa quy trình tạo script.

Playbook trả lời câu hỏi:

"Làm gì trước? Làm gì sau?"

Nó không chứa kiến thức.

Nó chỉ chứa quy trình.

---

# Knowledge Base

Knowledge Base là nơi lưu toàn bộ tri thức được sử dụng trong quá trình tạo script.

Nó không quy định quy trình.

Nó chỉ cung cấp kiến thức cho từng bước trong Playbook.

Knowledge Base bao gồm:

- Framework Library
- Mental Model Library
- Explanation Library
- Story Structure Library
- Story Device Library
- Writing Pattern Library
- Retention Library
- Evidence Library
- Style Guide
- AI Voice Guide

---

# Script Audit

Script Audit là bước kiểm tra cuối cùng.

Nó không tạo nội dung mới.

Nó chỉ đánh giá chất lượng script trước khi hoàn thành.

---

# Script Generation Workflow

## Step 1 — Input

Chuẩn bị:

- Topic
- Discovery
- Key Points
- Audience (optional)
- Goal (optional)
- Length (optional)

↓

## Step 2 — Idea Challenge

Đọc Playbook.

Kiểm tra:

- Discovery có rõ không?
- Có lỗ hổng Logic không?
- Có giả định chưa được kiểm chứng không?

↓

## Step 3 — Logic Planning

Sử dụng:

- Framework Library
- Mental Model Library

Đầu ra:

- Framework chính
- Mental Model chính
- Logic Flow

↓

## Step 4 — Story Planning

Sử dụng:

- Story Structure Library
- Story Device Library

Đầu ra:

- Story Structure
- Story Devices
- Emotional Flow

↓

## Step 5 — Writing

Sử dụng:

- Explanation Library
- Writing Pattern Library
- Style Guide

Đầu ra:

- First Draft

↓

## Step 6 — Optimization

Sử dụng:

- Retention Library
- Evidence Library
- AI Voice Guide

Đầu ra:

- Optimized Draft

↓

## Step 7 — Script Audit

Sử dụng:

Script Audit

Kiểm tra:

- Discovery
- Logic
- Story
- Style
- AI Voice

↓

Final Script

---

# Which File Is Used At Each Step?

| Step | File |
|------|------|
| Input | Playbook |
| Idea Challenge | Playbook |
| Logic Planning | Framework Library, Mental Model Library |
| Story Planning | Story Structure Library, Story Device Library |
| Writing | Explanation Library, Writing Pattern Library, Style Guide |
| Optimization | Retention Library, Evidence Library, AI Voice Guide |
| Final Check | Script Audit |

---

# Guiding Principles

Toàn bộ Script OS được xây dựng trên các nguyên tắc sau:

- Observation First
- Discovery First
- Logic Before Story
- Concrete Before Abstract
- Natural Spoken Language
- Optimize AI Voice Last

Mọi module trong hệ thống đều phải tuân thủ các nguyên tắc này.

---

# How To Expand Script OS

Khi bổ sung kiến thức mới:

1. Xác định Library phù hợp.
2. Không tạo Library mới nếu có thể mở rộng Library hiện tại.
3. Chỉ bổ sung những phương pháp đã được kiểm chứng qua quá trình sử dụng.
4. Không thêm kỹ thuật chỉ vì nó phổ biến.
5. Luôn giữ hệ thống đơn giản và nhất quán.

---

# Design Philosophy

Script OS không cố gắng tạo ra những script phức tạp.

Mục tiêu của hệ thống là:

- Logic rõ ràng.
- Discovery tự nhiên.
- Story hấp dẫn.
- Ngôn ngữ dễ hiểu.
- Dễ mở rộng.
- Dễ bảo trì.

Nếu có sự đánh đổi, luôn ưu tiên:

Discovery > Logic > Clarity > Story > Style.
