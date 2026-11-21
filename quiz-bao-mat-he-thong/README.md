# Ứng dụng Ôn thi Trắc nghiệm: Bảo mật Ứng dụng & Hệ thống (PKA)

> **Dành cho sinh viên Đại học Phenikaa (PKA)**  
> Môn học: **Bảo mật Ứng dụng & Hệ thống**  
> Dữ liệu: **151 câu hỏi ôn thi toàn diện** (Chuẩn ngân hàng câu hỏi ACourse PKA)  
> Cơ chế cốt lõi: **Mastery Loop - Câu sai tự động lặp lại cho đến khi đạt 100% mới hoàn thành**

---

## 🌟 1. Tính năng nổi bật

### 🔄 Cơ chế Học tập Mastery Loop (Học đến khi thuộc 100%)
- Khi bạn chọn đáp án **Đúng**: Câu hỏi được tính điểm nắm vững (*Mastered*), thanh tiến độ tăng lên và câu hỏi được hoàn thành.
- Khi bạn chọn đáp án **Sai**: Hệ thống lập tức hiển thị màu đỏ kèm **lời giải thích chi tiết và cơ sở lý thuyết**. Đồng thời, câu hỏi này được **tự động đưa về cuối danh sách** để bạn ôn luyện lại ở các lượt tiếp theo.
- Vòng học **chỉ kết thúc khi bạn trả lời đúng 100% tất cả các câu hỏi** trong bộ đề!
- Màn hình vinh danh với pháo hoa (*Confetti*) và thống kê số câu làm đúng ngay lần đầu, số câu đã khắc phục thành công.

### ⏱️ Chế độ Thi thử Cuối kỳ (Chuẩn cấu trúc đề thi Phenikaa)
- Rút ngẫu nhiên **40 câu hỏi** từ ngân hàng 151 câu.
- Thời gian đếm ngược: **45 phút**.
- Bảng câu hỏi tương tác (40 ô), cho phép đánh dấu cờ (`🚩`) câu hỏi phân vân để xem lại.
- Tự động chấm điểm theo thang điểm 10 và thang chữ (A, B, C, D, F).
- Phân tích chi tiết bài làm: Lọc xem riêng các câu làm sai kèm đáp án chuẩn.

### 📖 Ngân hàng Tra cứu 151 Câu hỏi (Flashcard & Tìm kiếm)
- Tìm kiếm từ khóa siêu nhanh: Tìm theo các khái niệm như `SQL`, `JWT`, `Bcrypt`, `CIA`, `Firewall`, `XSS`, `X.509`, `DevSecOps`...
- Lọc theo từng chuyên đề.
- Hỗ trợ in ấn và lưu file PDF sạch đẹp phục vụ học tập offline.

### ⚡ Phím tắt Bàn phím Siêu tốc
| Phím tắt | Chức năng trong Chế độ Luyện tập | Chức năng trong Chế độ Thi thử |
|---|---|---|
| `1` hoặc `A` | Chọn đáp án A | Chọn đáp án A |
| `2` hoặc `B` | Chọn đáp án B | Chọn đáp án B |
| `3` hoặc `C` | Chọn đáp án C | Chọn đáp án C |
| `4` hoặc `D` | Chọn đáp án D | Chọn đáp án D |
| `Space` hoặc `Enter` | Chuyển sang câu tiếp theo | - |
| `→` / `←` | - | Chuyển câu tiếp theo / câu trước |
| `F` | - | Bật/tắt cờ đánh dấu câu hỏi |

---

## 📚 2. Cấu trúc Ngân hàng 151 Câu hỏi

| STT | Chuyên đề | Số lượng | Trọng tâm kiến thức |
|---|---|---|---|
| **01** | **Tổng quan, Mô hình CIA, AAA & Nguyên tắc bảo mật** | **25 câu** | Tam giác CIA, mô hình AAA, Least Privilege, Defense in Depth, Fail-Safe Defaults, Zero Trust, RBAC, MAC, STRIDE, SSDLC... |
| **02** | **Lỗ hổng Ứng dụng Web & OWASP Top 10** | **30 câu** | SQL Injection (Classic, Blind, Time-based), Stored/Reflected/DOM XSS, CSRF Token, SameSite Cookie, HttpOnly, IDOR, SSRF, Command Injection, CSP, Clickjacking, Path Traversal, File Upload... |
| **03** | **Mật mã học Ứng dụng, Mã hóa & Chữ ký số** | **25 câu** | Mã hóa đối xứng (AES, DES), mã hóa bất đối xứng (RSA, ECC), Hàm băm (SHA-256, MD5), Salt & Bcrypt/Argon2, Diffie-Hellman, X.509 CA, TLS Handshake, HMAC, AES-GCM AEAD, PFS... |
| **04** | **Bảo mật Mạng, Hệ điều hành & Mã độc** | **25 câu** | Tường lửa Stateful/Stateless, DMZ, IDS vs IPS, IPSec, Virus, Worm, Trojan, Ransomware (quy tắc sao lưu 3-2-1), ASLR, DEP/NX, Linux chmod/SUID, Honeypot, ARP/DNS Poisoning, Wireshark, SIEM, Rootkit, DDoS SYN Flood... |
| **05** | **Đề thi thử Tổng hợp Cuối kỳ (Chuẩn Phenikaa PKA)** | **46 câu** | Đề tổng hợp toàn diện bao quát: OAuth 2.0 & OIDC, JWT Security (`alg: none`), Rate Limiting API, Blind SQLi Time-based, ABAC vs RBAC, DevSecOps SCA... |
| 🌟 | **Toàn bộ Ngân hàng Đề thi** | **151 câu** | Bộ đề đầy đủ nhất bao quát trọn vẹn toàn bộ học phần |

---

## 🚀 3. Hướng dẫn Mở và Sử dụng Ứng dụng

### Cách 1: Mở trực tiếp (Nhanh nhất - Không cần cài đặt)
1. Truy cập thư mục: `d:\HOC\data-source\quiz-bao-mat-he-thong`
2. **Nhấp đúp chuột vào file `index.html`** để mở bằng bất kỳ trình duyệt nào (Chrome, Edge, Cốc Cốc, Firefox, Brave...).
3. Ứng dụng đã được tích hợp sẵn toàn bộ dữ liệu 151 câu hỏi và hiệu ứng âm thanh tổng hợp tự động, **chạy 100% offline không cần internet**!

### Cách 2: Chạy qua Local Web Server (Tùy chọn)
Nếu bạn muốn chia sẻ trong mạng LAN cho điện thoại hoặc máy tính bảng cùng học:
```bash
cd d:\HOC\data-source\quiz-bao-mat-he-thong
python -m http.server 8080
```
Sau đó mở trình duyệt truy cập: `http://localhost:8080` (hoặc `http://<IP_MÁY_BẠN>:8080` trên điện thoại).

---

## 💾 4. Lưu trữ Tiến độ Tự động
- Mọi tiến độ học tập (danh sách câu đã nắm vững, điểm số các bài thi thử đã làm, chế độ Sáng/Tối, Bật/Tắt âm thanh) đều được tự động lưu vào `localStorage` của trình duyệt.
- Bạn có thể tắt trình duyệt hoặc tải lại trang bất cứ lúc nào mà không sợ mất thống kê ôn thi!
