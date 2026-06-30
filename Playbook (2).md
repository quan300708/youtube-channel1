# Playbook

## Standard Operating Procedure (SOP) for YouTube Script OS

**Version:** 1.0

# 1. Purpose

## 1.1 Why This Document Exists

Handbook định nghĩa **chúng ta viết như thế nào**.

Libraries lưu trữ **những gì chúng ta đã học được**.

Playbook định nghĩa **AI phải làm gì mỗi khi nhận một chủ đề mới.**

Nói cách khác:

-   Handbook là triết lý.
-   Libraries là kiến thức.
-   Playbook là quy trình sản xuất.

Mọi script được tạo ra trong Script OS đều phải đi qua cùng một quy
trình được mô tả trong tài liệu này. Không được bỏ qua bất kỳ giai đoạn
nào chỉ vì chủ đề có vẻ đơn giản.

Mục tiêu không phải tạo ra script nhanh nhất.

Mục tiêu là tạo ra script có chất lượng ổn định, có thể lặp lại và liên
tục cải thiện theo thời gian.

## 1.2 Philosophy

Một script tốt không phải là kết quả của cảm hứng.

Nó là kết quả của một quy trình.

Nếu quy trình đủ tốt:

-   chất lượng sẽ ổn định
-   dễ phát hiện lỗi
-   dễ tối ưu
-   dễ đào tạo AI
-   dễ mở rộng sang nhiều chủ đề khác nhau

Playbook được thiết kế với giả định rằng:

> **Một quy trình đúng sẽ tạo ra kết quả tốt thường xuyên hơn một người
> viết giỏi nhưng làm việc ngẫu hứng.**

Do đó mọi quyết định trong Script OS đều ưu tiên:

-   tính nhất quán
-   khả năng tái sử dụng
-   khả năng cải tiến
-   khả năng mở rộng

thay vì chỉ tối ưu cho một video riêng lẻ.

# 2. Position Inside Script OS

``` text
                    Handbook
                        │
                        ▼
                  Define Principles
                        │
                        ▼
                    Playbook
              (Execution Workflow)
                        │
                        ▼
                 Knowledge Libraries
                        │
                        ▼
                Project-specific Input
                        │
                        ▼
                  Final Script Output
```

Vai trò của từng thành phần:

### Handbook

Trả lời câu hỏi:

> Chúng ta tin vào điều gì?

Ví dụ:

-   Discovery First
-   Observation First
-   Concrete Before Abstract
-   Zoom Out Ending

Đây là những nguyên tắc gần như không thay đổi.

### Libraries

Trả lời câu hỏi:

> Chúng ta đã học được những gì?

Ví dụ:

-   Hook Library
-   Framework Library
-   Story Device Library
-   Mental Model Library

Libraries liên tục phát triển sau mỗi dự án.

### Projects

Trả lời câu hỏi:

> Chúng ta đang làm video nào?

Bao gồm:

-   research
-   outline
-   script
-   revision
-   final version

### Playbook

Trả lời câu hỏi quan trọng nhất:

> **AI phải làm gì tiếp theo?**

Playbook không lưu kiến thức.

Playbook không lưu nguyên tắc.

Playbook chỉ định nghĩa quy trình ra quyết định.

# 3. Design Principles

## Principle 1 --- Every Script Is Built, Not Written

Script không được xem là một văn bản.

Script là một sản phẩm được xây dựng từng lớp.

``` text
Topic
 ↓
Challenge
 ↓
Logic
 ↓
Story
 ↓
Style
 ↓
Retention
 ↓
Voice
 ↓
Audit
```

Không bao giờ nhảy thẳng từ Topic sang Script.

## Principle 2 --- Thinking Before Writing

Không được viết khi chưa hoàn thành quá trình tư duy.

Toàn bộ reasoning phải hoàn tất trước khi sinh câu chữ.

## Principle 3 --- Decisions Must Be Explicit

Mọi quyết định quan trọng đều phải được đưa ra một cách chủ động.

## Principle 4 --- One Module, One Responsibility

Mỗi module chỉ giải quyết một loại vấn đề.

## Principle 5 --- Continuous Improvement

Sau mỗi video cần trả lời:

-   Điều gì hoạt động tốt?
-   Điều gì chưa tốt?
-   Điều gì có thể tái sử dụng?
-   Điều gì nên chuẩn hóa?

# 4. Workflow Overview

``` text
INPUT
   │
   ▼
Idea Challenge Engine
   │
Quality Gate 1
   ▼
Logic Engine
   │
Quality Gate 2
   ▼
Story Engine
   │
Quality Gate 3
   ▼
Style Engine
   │
Quality Gate 4
   ▼
Draft Generation
   │
Quality Gate 5
   ▼
Retention Engine
   │
Quality Gate 6
   ▼
AI Voice Engine
   │
Quality Gate 7
   ▼
Final Audit
   ▼
FINAL SCRIPT
```

Điểm quan trọng nhất của pipeline này là mỗi module phải xác minh chất
lượng đầu vào của mình. Nếu đầu vào chưa đạt chuẩn, quy trình phải quay
lại module trước thay vì tiếp tục xử lý.
# 5. Input Specification

## 5.1 Purpose

Input Specification là bước chuẩn hóa toàn bộ dữ liệu đầu vào trước khi hệ thống bắt đầu suy luận.

Một script chất lượng không bắt đầu từ việc viết, mà bắt đầu từ việc hiểu đúng vấn đề cần giải quyết.

Trong thực tế, phần lớn các script kém chất lượng không xuất phát từ khả năng diễn đạt, mà đến từ việc đầu vào không đủ rõ ràng. Nếu Topic mơ hồ, Core Ideas thiếu logic hoặc Goal không xác định, mọi module phía sau đều sẽ phải làm việc trên một nền tảng sai lệch.

Vì vậy, trước khi bước vào quá trình Challenge hay Story Planning, Playbook yêu cầu mọi đầu vào phải được chuẩn hóa theo cùng một tiêu chuẩn.

---

# 5.2 Required Inputs

Mỗi project tối thiểu phải có các trường sau.

| Field | Required | Description |
|---------|----------|-------------|
| Topic | ✅ | Chủ đề trung tâm của video |
| Core Ideas | ✅ | Những ý chính người viết muốn truyền tải |
| Audience | Optional | Đối tượng khán giả |
| Goal | Optional | Điều người xem cần đạt được sau video |
| Length | Optional | Thời lượng mục tiêu |
| Constraints | Optional | Các yêu cầu đặc biệt |

Nếu người dùng chỉ cung cấp Topic, hệ thống phải yêu cầu hoặc tự xây dựng Core Ideas trước khi tiếp tục.

Không được bỏ qua bước này.

---

# 5.3 Topic Requirements

Topic phải đủ cụ thể để có thể tạo ra một Discovery rõ ràng.

Ví dụ:

❌ Chính trị

Quá rộng.

Không xác định được video muốn khám phá điều gì.

---

❌ Nền kinh tế

Quá rộng.

Không có trọng tâm.

---

✅ Tại sao Singapore trở nên giàu có?

Có Discovery rõ ràng.

---

✅ Vì sao nhiều người hiểu sai về chủ nghĩa tư bản?

Có câu hỏi trung tâm.

---

Một Topic tốt phải trả lời được ít nhất một trong các câu hỏi sau:

- Chúng ta đang muốn giải thích điều gì?
- Chúng ta đang muốn khám phá điều gì?
- Chúng ta đang muốn thay đổi nhận thức nào?
- Điều gì khiến chủ đề này đáng để người xem dành thời gian?

Nếu chưa trả lời được, Topic cần được tinh chỉnh trước khi tiếp tục.

---

# 5.4 Core Ideas

Core Ideas là tập hợp những luận điểm người viết muốn truyền tải.

Đây **không phải outline**.

Đây **không phải script**.

Đây chỉ là những ý tưởng cốt lõi.

Ví dụ:

Topic:

"Tại sao nhiều quốc gia giàu vẫn suy thoái?"

Core Ideas:

- GDP không phản ánh toàn bộ sức khỏe nền kinh tế.
- Thể chế quan trọng hơn tài nguyên.
- Nợ công có thể trở thành rào cản dài hạn.
- Dân số già làm giảm tốc độ tăng trưởng.

Những ý này sẽ được Challenge Engine kiểm tra ở bước tiếp theo.

---

# 5.5 Audience

Nếu không có Audience, AI sẽ mặc định sử dụng Audience được định nghĩa trong Handbook.

Nếu có Audience riêng cho từng video, cần xác định càng cụ thể càng tốt.

Ví dụ:

❌ Người xem YouTube

Quá rộng.

---

✅ Học sinh THPT

---

✅ Sinh viên kinh tế

---

✅ Người mới bắt đầu tìm hiểu chính trị

---

Audience sẽ ảnh hưởng trực tiếp tới:

- độ sâu lập luận
- lượng thuật ngữ
- tốc độ giải thích
- ví dụ sử dụng
- storytelling

---

# 5.6 Goal

Goal trả lời câu hỏi:

> Sau khi xem xong, người xem nên thay đổi điều gì?

Goal không phải:

"Tăng lượt xem."

Goal cũng không phải:

"Video hay."

Goal là thay đổi về nhận thức.

Ví dụ:

- Hiểu vì sao GDP không đủ để đánh giá một quốc gia.
- Nhìn chính trị dưới góc nhìn hệ thống.
- Biết cách phân biệt tăng trưởng và phát triển.
- Có thêm động lực tìm hiểu lịch sử.

Một video chỉ nên có **một Goal chính**.

Nếu tồn tại nhiều Goal ngang nhau, script sẽ dễ mất trọng tâm.

---

# 5.7 Length

Length ảnh hưởng đến toàn bộ chiến lược kể chuyện.

Ví dụ:

### YouTube Shorts

60–120 giây

Ưu tiên:

- một Discovery
- ít nhánh
- tốc độ cao

---

### Video trung bình

5–10 phút

Có thể triển khai:

- nhiều Discovery
- nhiều ví dụ
- nhiều tầng lập luận

---

### Video dài

15–30 phút

Cho phép:

- nhiều chương
- nhiều Case Study
- nhiều Callback
- Final Zoom Out lớn hơn

Không được sử dụng cùng một cấu trúc cho mọi độ dài video.

---

# 5.8 Constraints

Constraints là những giới hạn đặc biệt.

Ví dụ:

- Không sử dụng thuật ngữ chuyên ngành.
- Chỉ dùng ví dụ tại Việt Nam.
- Không dùng số liệu cũ hơn 5 năm.
- Hạn chế yếu tố chính trị nhạy cảm.
- Tối ưu cho AI Voice.

Mọi Constraint phải được lưu lại trước khi bắt đầu lập luận.

---

# 5.9 Input Validation

Sau khi thu thập đầu vào, hệ thống phải tự kiểm tra.

## Checklist

□ Topic đã đủ cụ thể chưa?

□ Discovery trung tâm đã rõ chưa?

□ Core Ideas có mâu thuẫn không?

□ Có ý nào chưa có bằng chứng?

□ Goal có rõ ràng không?

□ Audience đã xác định chưa?

□ Có thiếu dữ liệu nghiên cứu không?

□ Có cần nghiên cứu trước khi viết không?

Nếu bất kỳ câu trả lời nào là "Chưa", quy trình phải dừng lại để hoàn thiện đầu vào.

Không được chuyển sang bước tiếp theo.

---

# 5.10 Quality Gate 0

Module Input chỉ hoàn thành khi đáp ứng đồng thời tất cả các điều kiện sau:

- Topic rõ ràng.
- Core Ideas đầy đủ.
- Discovery trung tâm đã xác định.
- Goal thống nhất.
- Audience xác định.
- Không có mâu thuẫn logic.
- Không thiếu dữ liệu quan trọng.
- Đủ điều kiện để bắt đầu Challenge Engine.

Nếu không vượt qua Quality Gate này, toàn bộ pipeline phải dừng.

Không có ngoại lệ.

---

# 5.11 Output

Đầu ra của Module Input không phải là script.

Đầu ra là một **Input Package** đã được chuẩn hóa, bao gồm:

- Topic
- Core Ideas
- Audience
- Goal
- Length
- Constraints
- Discovery trung tâm
- Những giả định cần kiểm chứng
- Những phần cần nghiên cứu thêm (nếu có)

Input Package này sẽ trở thành đầu vào chính thức của **Module 1 — Idea Challenge Engine**.

---

# Module 1 — Idea Challenge Engine

## Purpose

Kiểm tra và hoàn thiện chất lượng của ý tưởng trước khi bắt đầu xây dựng lập luận.

Module này không tạo outline và không viết script.

Đầu ra của module là một tập hợp các Core Ideas đã được kiểm chứng, đủ điều kiện để chuyển sang Logic Engine.

---

## Input

- Topic
- Core Ideas
- Goal
- Audience
- Constraints
- Research Notes (nếu có)

---

## Workflow

```
Receive Input
      │
      ▼
Challenge Core Ideas
      │
      ▼
Identify Weak Ideas
      │
      ▼
Strengthen or Remove
      │
      ▼
Identify Missing Perspectives
      │
      ▼
Define Central Discovery
      │
      ▼
Prepare Output Package
```

---

## Process

### Step 1 — Challenge Core Ideas

Đánh giá từng Core Idea bằng các phương pháp trong Framework Library.

Mục tiêu là phát hiện các ý tưởng yếu, các giả định chưa được kiểm chứng và những góc nhìn còn thiếu.

---

### Step 2 — Refine Ideas

Loại bỏ hoặc chỉnh sửa những ý tưởng chưa đủ mạnh.

Nếu cần, bổ sung thêm các ý tưởng hỗ trợ để hoàn thiện lập luận.

---

### Step 3 — Define Central Discovery

Xác định Discovery quan trọng nhất của video.

Mọi lập luận phía sau phải phục vụ Discovery này.

---

### Step 4 — Prepare Output

Tổng hợp toàn bộ kết quả để chuyển sang Logic Engine.

---

## Decision Rules

- Không giữ lại các ý tưởng không thể bảo vệ bằng lập luận hợp lý.
- Không giữ các ý tưởng trùng lặp.
- Không để nhiều Discovery trung tâm trong cùng một video.
- Nếu thiếu thông tin quan trọng, yêu cầu nghiên cứu bổ sung trước khi tiếp tục.

---

## Output

- Refined Core Ideas
- Central Discovery
- Missing Perspectives
- Research Questions (nếu có)

---

## Quality Gate

Chỉ được chuyển sang Logic Engine khi:

- Tất cả Core Ideas đã được rà soát.
- Discovery trung tâm đã xác định.
- Không còn mâu thuẫn logic rõ ràng.
- Không còn thiếu dữ liệu quan trọng.

# Module 2 — Logic Engine

## Purpose

Chuyển các Core Ideas đã được kiểm chứng thành một hệ thống lập luận mạch lạc và có sức thuyết phục.

Module này không quyết định cách kể chuyện hay cách diễn đạt. Nhiệm vụ duy nhất là xây dựng "xương sống" logic của video.

---

## Input

- Refined Core Ideas
- Central Discovery
- Goal
- Audience
- Research Notes

---

## Workflow

```
Receive Input
      │
      ▼
Select Reasoning Framework
      │
      ▼
Design Argument Flow
      │
      ▼
Design Emotional Flow
      │
      ▼
Assign Supporting Evidence
      │
      ▼
Validate Logic
      │
      ▼
Prepare Output Package
```

---

## Process

### Step 1 — Select Reasoning Framework

Lựa chọn framework phù hợp từ Framework Library để tổ chức toàn bộ lập luận.

Một video chỉ nên có một framework chính.

---

### Step 2 — Design Argument Flow

Sắp xếp các luận điểm theo trình tự giúp người xem dễ theo dõi và dễ bị thuyết phục nhất.

Mỗi luận điểm phải phục vụ Discovery trung tâm.

---

### Step 3 — Design Emotional Flow

Xác định cảm xúc mong muốn của người xem tại từng giai đoạn của video.

Ví dụ:

- Tò mò
- Đồng tình
- Bất ngờ
- Thuyết phục
- Chiêm nghiệm

Emotional Flow phải hỗ trợ Argument Flow, không thay thế nó.

---

### Step 4 — Assign Supporting Evidence

Xác định bằng chứng, ví dụ hoặc dữ liệu cần sử dụng cho từng luận điểm.

Việc lựa chọn và đánh giá bằng chứng tuân theo Evidence Library.

---

### Step 5 — Validate Logic

Kiểm tra lại toàn bộ chuỗi lập luận.

Đảm bảo không có:

- Mâu thuẫn.
- Khoảng trống logic.
- Luận điểm thừa.
- Luận điểm không phục vụ Discovery.

---

## Decision Rules

- Chỉ sử dụng một Argument Flow chính.
- Không thêm luận điểm không phục vụ Discovery.
- Không để Evidence dẫn dắt lập luận; Evidence chỉ có nhiệm vụ hỗ trợ.
- Nếu phát hiện lỗ hổng logic, quay lại Idea Challenge Engine thay vì tiếp tục.

---

## Output

- Logic Structure
- Argument Flow
- Emotional Flow
- Evidence Plan

---

## Quality Gate

Chỉ chuyển sang Story Engine khi:

- Framework đã được xác định.
- Argument Flow hoàn chỉnh.
- Emotional Flow rõ ràng.
- Mỗi luận điểm đều có vai trò cụ thể.
- Không còn khoảng trống logic.

# Module 3 — Story Engine

## Purpose

Chuyển hệ thống lập luận thành một hành trình khám phá tự nhiên, giúp người xem tiếp nhận thông tin một cách liền mạch và hấp dẫn.

Module này không thay đổi nội dung lập luận mà quyết định cách người xem trải nghiệm lập luận đó.

---

## Input

- Logic Structure
- Argument Flow
- Emotional Flow
- Evidence Plan
- Goal

---

## Workflow

```text
Receive Input
      │
      ▼
Select Story Structure
      │
      ▼
Design Discovery Flow
      │
      ▼
Design Chapters
      │
      ▼
Apply Story Devices
      │
      ▼
Validate Story Flow
      │
      ▼
Prepare Output Package
```

---

## Process

### Step 1 — Select Story Structure

Chọn cấu trúc kể chuyện phù hợp từ Story Structure Library.

Toàn bộ video nên sử dụng một Story Structure chính.

---

### Step 2 — Design Discovery Flow

Xây dựng trình tự các Discovery để người xem liên tục khám phá thêm thông tin mới.

Mỗi Discovery phải dẫn tự nhiên đến Discovery tiếp theo.

---

### Step 3 — Design Chapters

Chia video thành các chương hoặc các phân đoạn rõ ràng.

Mỗi Chapter chỉ nên giải quyết một Discovery chính.

---

### Step 4 — Apply Story Devices

Áp dụng các Story Devices phù hợp để tăng khả năng giữ chân người xem.

Việc lựa chọn Story Devices tuân theo Story Device Library.

---

### Step 5 — Validate Story Flow

Kiểm tra lại toàn bộ hành trình kể chuyện.

Đảm bảo:

- Không có Discovery bị lặp.
- Chuyển đoạn tự nhiên.
- Nhịp độ phù hợp.
- Discovery cuối cùng dẫn đến Final Zoom Out.

---

## Decision Rules

- Một Chapter chỉ phục vụ một Discovery chính.
- Không thêm Story Device nếu không phục vụ Discovery.
- Không hy sinh tính logic để tạo kịch tính.
- Nếu Story Flow làm thay đổi Logic Flow, quay lại Logic Engine.

---

## Output

- Story Structure
- Discovery Flow
- Chapter Plan
- Story Device Plan

---

## Quality Gate

Chỉ chuyển sang Style Engine khi:

- Story Structure đã xác định.
- Discovery Flow hoàn chỉnh.
- Chapter rõ ràng.
- Story Flow không làm thay đổi Logic Flow.
- Final Zoom Out đã được xác định.

# Module 4 — Style Engine

## Purpose

Chuyển Story Plan thành phong cách đặc trưng của kênh.

Module này đảm bảo mọi script đều tuân thủ Handbook và Style Guide, bất kể chủ đề là gì.

---

## Input

- Story Structure
- Discovery Flow
- Chapter Plan
- Goal
- Audience

---

## Workflow

```text
Receive Input
      │
      ▼
Apply Macro Style
      │
      ▼
Apply Micro Style
      │
      ▼
Optimize Readability
      │
      ▼
Validate Style
      │
      ▼
Prepare Output Package
```

---

## Process

### Step 1 — Apply Macro Style

Áp dụng các nguyên tắc về cấu trúc, tốc độ triển khai và chiến lược giải thích theo Style Guide.

---

### Step 2 — Apply Micro Style

Áp dụng quy tắc về câu văn, chuyển đoạn, giọng điệu và cách diễn đạt.

---

### Step 3 — Optimize Readability

Kiểm tra tính tự nhiên của ngôn ngữ.

Ưu tiên văn nói thay vì văn viết.

---

### Step 4 — Validate Style

Đảm bảo toàn bộ script tuân thủ Handbook và Style Guide.

---

## Decision Rules

- Không vi phạm các nguyên tắc trong Handbook.
- Không sử dụng văn phong làm giảm độ rõ ràng của lập luận.
- Ưu tiên sự tự nhiên hơn sự hoa mỹ.
- Nếu Style làm thay đổi Story Flow, quay lại Story Engine.

---

## Output

- Style Blueprint
- Writing Guidelines cho bản nháp

---

## Quality Gate

Chỉ chuyển sang Draft Generation khi:

- Macro Style hoàn chỉnh.
- Micro Style hoàn chỉnh.
- Ngôn ngữ phù hợp Audience.
- Tuân thủ toàn bộ Style Guide.

# Module 5 — Draft Generation

## Purpose

Chuyển toàn bộ kế hoạch đã xây dựng thành bản nháp đầu tiên của script.

Đây là giai đoạn thực thi, không phải giai đoạn thiết kế. Mọi quyết định về Logic, Story và Style đều đã được hoàn thành ở các module trước.

---

## Input

- Logic Structure
- Story Structure
- Discovery Flow
- Chapter Plan
- Style Blueprint
- Writing Guidelines

---

## Workflow

```text
Receive Input
      │
      ▼
Generate Draft
      │
      ▼
Check Structural Consistency
      │
      ▼
Refine Transitions
      │
      ▼
Prepare Draft
```

---

## Decision Rules

- Không thay đổi Logic Structure.
- Không thay đổi Story Structure.
- Không thêm Discovery mới.
- Chỉ được điều chỉnh cách diễn đạt nếu giúp nội dung rõ ràng hơn.
- Nếu cần thay đổi cấu trúc, quay lại module tương ứng.

---

## Output

- First Draft Script

---

## Quality Gate

Chỉ chuyển sang Retention Engine khi:

- Script đã bao phủ toàn bộ Discovery.
- Không thiếu Chapter.
- Không có đoạn ngoài phạm vi mục tiêu.
- Flow giữa các Chapter hoàn chỉnh.

# Module 6 — Retention Engine

## Purpose

Tăng khả năng giữ chân người xem mà không làm thay đổi nội dung cốt lõi của video.

Module này tối ưu cách truyền tải, không tối ưu lập luận.

---

## Input

- First Draft Script

---

## Workflow

```text
Receive Draft
      │
      ▼
Evaluate Viewer Engagement
      │
      ▼
Optimize Pacing
      │
      ▼
Optimize Information Density
      │
      ▼
Refine Curiosity Flow
      │
      ▼
Prepare Optimized Draft
```

---

## Decision Rules

- Không thêm thông tin chỉ để tạo kịch tính.
- Không tạo Curiosity Gap giả tạo.
- Không hy sinh tính rõ ràng để tăng Retention.
- Mọi kỹ thuật Retention phải phục vụ Discovery.

---

## Output

- Retention Optimized Draft

---

## Quality Gate

Chỉ chuyển sang AI Voice Engine khi:

- Không có đoạn bị chậm nhịp.
- Không có đoạn dư thừa.
- Curiosity Flow liên tục.
- Pacing phù hợp với thời lượng mục tiêu.

# Module 7 — AI Voice Engine

## Purpose

Tối ưu bản nháp để AI Voice hoặc người đọc có thể trình bày tự nhiên, rõ ràng và mạch lạc.

Module này chỉ được thực hiện sau khi script đã hoàn thiện về nội dung.

---

## Input

- Retention Optimized Draft

---

## Workflow

```text
Receive Draft
      │
      ▼
Optimize Sentence Rhythm
      │
      ▼
Insert Natural Pause Points
      │
      ▼
Improve Spoken Flow
      │
      ▼
Final Voice Review
```

---

## Decision Rules

- Không thay đổi Discovery.
- Không thay đổi Logic.
- Không thay đổi Story.
- Chỉ tối ưu khả năng đọc thành tiếng.

---

## Output

- AI Voice Optimized Script

---

## Quality Gate

Chỉ chuyển sang Final Audit khi:

- Đọc thành tiếng tự nhiên.
- Không có câu quá dài.
- Nhịp đọc ổn định.
- Phù hợp với AI Voice Guide.

# Module 8 — Final Audit

## Purpose

Đánh giá toàn bộ script trước khi phát hành.

Đây là bước kiểm tra cuối cùng nhằm đảm bảo mọi module trước đó đã được thực hiện đúng.

---

## Input

- AI Voice Optimized Script

---

## Workflow

```text
Receive Script
      │
      ▼
Review Handbook Compliance
      │
      ▼
Review Playbook Compliance
      │
      ▼
Run Final Checklist
      │
      ▼
Approve or Return
```

---

## Final Checklist

### Logic

- □ Discovery rõ ràng.
- □ Không có mâu thuẫn logic.
- □ Mọi luận điểm đều phục vụ Discovery.

### Story

- □ Story Flow mạch lạc.
- □ Discovery phát triển tự nhiên.
- □ Chapter rõ ràng.

### Style

- □ Tuân thủ Style Guide.
- □ Ngôn ngữ tự nhiên.
- □ Phù hợp Audience.

### Retention

- □ Nhịp độ ổn định.
- □ Không có đoạn thừa.
- □ Curiosity Flow liên tục.

### AI Voice

- □ Đọc thành tiếng tự nhiên.
- □ Có khoảng nghỉ hợp lý.
- □ Không có câu khó đọc.

---

## Decision Rules

Nếu bất kỳ hạng mục nào không đạt, script phải quay về đúng module chịu trách nhiệm thay vì chỉnh sửa trực tiếp trong Final Audit.

---

## Output

- Approved Script
- Revision Report (nếu cần)

---

## Quality Gate

Script chỉ được xem là hoàn thành khi toàn bộ Checklist đều đạt.

# Continuous Improvement

Mỗi video hoàn thành đều là một cơ hội để cải thiện Script OS.

Sau khi xuất bản, cần thực hiện Post-project Review với các câu hỏi sau:

- Điều gì hoạt động tốt?
- Điều gì hoạt động chưa tốt?
- Discovery có hiệu quả không?
- Phần nào giữ chân người xem tốt nhất?
- Có framework nào mới đáng bổ sung?
- Có Story Device nào nên chuẩn hóa?
- Có quy tắc nào trong Handbook cần cập nhật?

Nếu một phương pháp được chứng minh hiệu quả nhiều lần, hãy chuyển nó vào Library tương ứng.

Nếu chỉ mới hiệu quả trong một số trường hợp, lưu vào Experiments để tiếp tục kiểm chứng.

Playbook chỉ thay đổi khi quy trình làm việc thay đổi.

Libraries thay đổi khi có kiến thức mới.

Handbook chỉ thay đổi khi triết lý cốt lõi của Script OS thay đổi.

# Operating Rules

Các quy tắc dưới đây áp dụng cho toàn bộ Script OS, bất kể chủ đề hay loại video.

Nếu có xung đột giữa các module, Operating Rules luôn được ưu tiên.

---

## Rule 1 — Respect Module Boundaries

Mỗi module chỉ được thực hiện đúng trách nhiệm của mình.

Không được thay đổi công việc của module khác.

Ví dụ:

- Logic Engine không chỉnh Story.
- Story Engine không sửa Logic.
- Style Engine không thay đổi Discovery.
- AI Voice Engine không thay đổi nội dung.

Nếu cần thay đổi, phải quay lại đúng module chịu trách nhiệm.

---

## Rule 2 — One Direction Workflow

Workflow luôn đi theo một chiều.

```text
Input
    │
    ▼
Idea Challenge
    ▼
Logic
    ▼
Story
    ▼
Style
    ▼
Draft
    ▼
Retention
    ▼
AI Voice
    ▼
Final Audit
```

Không được bỏ qua module.

Không được nhảy cóc.

---

## Rule 3 — Revision Must Follow Ownership

Mỗi lỗi phải được sửa tại đúng nơi phát sinh.

Ví dụ:

Sai lập luận

→ Logic Engine

Story thiếu hấp dẫn

→ Story Engine

Giọng văn chưa phù hợp

→ Style Engine

Nhịp đọc chưa tốt

→ AI Voice Engine

Không sửa lỗi ở module cuối nếu nguyên nhân nằm ở module đầu.

---

## Rule 4 — Discovery Is The Highest Priority

Mọi quyết định đều phải phục vụ Discovery trung tâm.

Nếu một phần nội dung không giúp người xem tiến gần hơn đến Discovery, phần đó nên được loại bỏ.

---

## Rule 5 — Simplicity Over Complexity

Luôn ưu tiên giải pháp đơn giản hơn nếu đạt cùng mục tiêu.

Không thêm:

- ví dụ
- framework
- story device
- hiệu ứng

nếu chúng không làm video tốt hơn.

---

## Rule 6 — Libraries Are The Source Of Knowledge

Playbook không chứa kiến thức chuyên môn.

Nếu một module cần:

- Framework
- Story Structure
- Story Device
- Hook
- Transition
- Evidence
- Style

thì phải tham chiếu Library tương ứng.

---

## Rule 7 — Handbook Defines Principles

Nếu có mâu thuẫn giữa Playbook và Handbook.

Handbook luôn được ưu tiên.

Playbook chỉ mô tả cách thực hiện.

Handbook định nghĩa tiêu chuẩn phải đạt.

---

## Rule 8 — Continuous Improvement

Sau mỗi dự án cần đánh giá:

- Điều gì nên đưa vào Library?
- Điều gì nên giữ trong Experiments?
- Điều gì cần sửa trong Handbook?
- Điều gì cần cập nhật Playbook?

Script OS phải liên tục tiến hóa thông qua từng video.

---

# Error Flow

Nếu một module không vượt qua Quality Gate, quy trình phải quay về đúng nơi phát sinh lỗi.

```text
Input
    │
    ▼
Idea Challenge
    │
    ▼
Logic
    │
    ▼
Story
    │
    ▼
Style
    │
    ▼
Draft
    │
    ▼
Retention
    │
    ▼
AI Voice
    │
    ▼
Final Audit
```

Các quy tắc xử lý lỗi:

- Lỗi Idea → quay về Module 1.
- Lỗi Logic → quay về Module 2.
- Lỗi Story → quay về Module 3.
- Lỗi Style → quay về Module 4.
- Lỗi Draft → quay về Module 5.
- Lỗi Retention → quay về Module 6.
- Lỗi AI Voice → quay về Module 7.

Final Audit không được phép tự sửa lỗi.

Final Audit chỉ có quyền:

- Phê duyệt.
- Hoặc yêu cầu quay lại module phù hợp.

---

# End of Playbook
