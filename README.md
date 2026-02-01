# 🚀 Visual-Studio-Code

> **Chạy VS Code trên trình duyệt miễn phí với GitHub Actions**

[![GitHub Actions](https://img.shields.io/badge/GitHub-Actions-blue?logo=github)](https://github.com/features/actions)
[![VS Code](https://img.shields.io/badge/VS%20Code-Web-007ACC?logo=visual-studio-code)](https://github.com/coder/code-server)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## 📋 Mục lục

- [Giới thiệu](#-giới-thiệu)
- [Tính năng](#-tính-năng)
- [Cấu hình hệ thống](#-cấu-hình-hệ-thống)
- [Cài đặt](#-cài-đặt)
- [Sử dụng](#-sử-dụng)
- [Lưu ý quan trọng](#-lưu-ý-quan-trọng)
- [FAQ](#-faq)
- [Troubleshooting](#-troubleshooting)
- [Credits](#-credits)

---

## 🌟 Giới thiệu

**VS Code Web IDX** là giải pháp cho phép bạn chạy Visual Studio Code trên trình duyệt hoàn toàn **MIỄN PHÍ** bằng GitHub Actions. Không cần cài đặt gì, chỉ cần trình duyệt web!

### ✨ Tại sao nên dùng?

- ✅ **Miễn phí 100%** - Sử dụng tài nguyên GitHub Actions
- ✅ **Không cần cài đặt** - Chạy ngay trên trình duyệt
- ✅ **Cấu hình mạnh** - 4 CPU Cores, 16GB RAM, 60GB SSD
- ✅ **Truy cập mọi nơi** - Chỉ cần có Internet
- ✅ **Đầy đủ tính năng** - Terminal, Git, Extensions, Upload/Download

---

## 🎯 Tính năng

### 💻 Môi trường phát triển hoàn chỉnh

| Tính năng | Mô tả |
|-----------|-------|
| **Full Terminal** | Truy cập terminal Linux đầy đủ quyền |
| **Git Integration** | Clone, commit, push/pull repository |
| **Extensions** | Cài đặt extensions từ VS Code Marketplace |
| **Multi-language** | Hỗ trợ Python, Node.js, Java, C++, Go... |
| **File Manager** | Upload/Download files dễ dàng |
| **Live Server** | Test web app với port forwarding |

### 🔧 Công cụ có sẵn

- **Languages:** Python 3, Node.js, npm, Java, C/C++, Go
- **Tools:** Git, wget, curl, vim, nano
- **Package Managers:** pip, npm, apt-get

---

## 💪 Cấu hình hệ thống

```
┌─────────────────────────────────────────────┐
│  🖥️  CPU      : 4 Cores Intel Xeon          │
│  🧠 RAM      : 16 GB DDR4                   │
│  💾 Storage  : 60 GB SSD                    │
│  🐧 OS       : Ubuntu 22.04 LTS             │
│  🌐 Network  : 100 Mbps                     │
└─────────────────────────────────────────────┘
```

---

## 📦 Cài đặt

### Bước 1: Fork Repository

1. Click nút **Fork** ở góc trên bên phải
2. Đợi GitHub fork repo về tài khoản của bạn

### Bước 2: Tạo Workflow File

1. Vào repo vừa fork
2. Tạo thư mục `.github/workflows/` (nếu chưa có)
3. Tạo file `vscode.yml` trong thư mục đó
4. Copy nội dung từ file `vscode-web-idx.yml` vào

### Bước 3: Enable Actions

1. Vào tab **Actions** trong repo
2. Click **I understand my workflows, go ahead and enable them**

---

## 🚀 Sử dụng

### Khởi động VS Code Web

1. Vào tab **Actions** trong repo của bạn
2. Click vào workflow **🚀 VS Code Web IDX (Zun x Kami Tunnel)**
3. Click nút **Run workflow**
4. Chọn thời gian sử dụng:
   - `1h` - 1 giờ
   - `3h` - 3 giờ  
   - `5h40m` - 5 giờ 40 phút (Khuyên dùng)
5. Click **Run workflow** để bắt đầu

### Truy cập VS Code

Sau **~3 phút**, workflow sẽ hiển thị:

```
🌐 LIÊN KẾT TRUY CẬP:
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
http://your-unique-url.kami.link
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

🔐 MẬT KHẨU:
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
123456
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

**Cách truy cập:**
1. Copy URL ở trên
2. Mở trên trình duyệt
3. Nhập mật khẩu: `123456`
4. Bắt đầu code! 🎉

---

## ⚠️ Lưu ý quan trọng

### 📌 Về dữ liệu

- ❌ **Dữ liệu sẽ BỊ XÓA** khi workflow kết thúc
- ✅ **Luôn backup code** lên GitHub hoặc Git
- ✅ Sử dụng `git push` thường xuyên để lưu code

### 🕐 Về thời gian

| Thời gian | Phù hợp cho |
|-----------|-------------|
| 1h | Test nhanh, code nhỏ |
| 3h | Dự án vừa, học tập |
| 5h40m | Dự án lớn, làm việc lâu dài |

### 🔒 Về bảo mật

- 🔐 Mật khẩu mặc định: `123456`
- ⚠️ **KHÔNG lưu thông tin nhạy cảm** (API keys, passwords...)
- ✅ Sử dụng environment variables cho secrets

### 📊 Giới hạn GitHub Actions

- Mỗi workflow tối đa: **6 giờ**
- Mỗi tài khoản free: **2000 phút/tháng**
- Chạy đồng thời: **20 workflows**

---

## ❓ FAQ

### 1. Tôi có thể thay đổi mật khẩu không?

Có! Sửa dòng này trong file workflow:

```yaml
echo "password: 123456" >> ~/.config/code-server/config.yaml
```

Thay `123456` bằng mật khẩu của bạn.

### 2. Làm sao để lưu code khi hết giờ?

```bash
# Trong terminal VS Code
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
git add .
git commit -m "Save work"
git push
```

### 3. Tôi có thể cài thêm phần mềm không?

Có! Sử dụng terminal:

```bash
# Cài qua apt
sudo apt install package-name

# Cài Python packages
pip install package-name

# Cài Node packages
npm install -g package-name
```

### 4. Làm sao kiểm tra ổ đĩa 60GB?

Trong terminal VS Code, chạy:

```bash
df -h /mnt/workspace
```

### 5. Tôi có thể chạy web server không?

Có! Nhưng chỉ truy cập được qua VS Code port forwarding:

```bash
# Python
python -m http.server 3000

# Node.js
npx http-server -p 3000
```

Sau đó dùng tính năng Port Forwarding trong VS Code.

### 6. Workflow bị lỗi, phải làm sao?

- Kiểm tra tab Actions xem lỗi gì
- Đọc phần [Troubleshooting](#-troubleshooting) bên dưới
- Re-run workflow

---

## 🔧 Troubleshooting

### Lỗi: "No space left on device"

**Nguyên nhân:** Hệ thống không đủ dung lượng tạo ổ đĩa ảo

**Giải pháp:**
- Workflow đã tối ưu, lỗi này ít xảy ra
- Nếu vẫn gặp, giảm kích thước ổ đĩa xuống 30GB

### Lỗi: "Không lấy được URL"

**Nguyên nhân:** Kami Tunnel chưa khởi động kịp

**Giải pháp:**
- Đợi thêm 1-2 phút
- Re-run workflow

### Lỗi: "Authentication failed"

**Nguyên nhân:** Sai mật khẩu

**Giải pháp:**
- Kiểm tra lại mật khẩu: `123456`
- Kiểm tra có gõ thêm dấu cách không

### VS Code chạy chậm

**Nguyên nhân:** Mạng hoặc extensions nặng

**Giải pháp:**
- Tắt extensions không cần thiết
- Kiểm tra kết nối Internet
- Reload trang

### Không kết nối được sau 5 phút

**Nguyên nhân:** Kami Tunnel có thể bị chặn

**Giải pháp:**
- Thử đổi mạng (4G, WiFi khác)
- Tắt VPN/Proxy
- Re-run workflow

---

## 🎓 Hướng dẫn nâng cao

### Tùy chỉnh Code-Server

Sửa phần cấu hình trong workflow:

```yaml
- name: ⚙️ Cấu hình Code-Server
  run: |
    mkdir -p ~/.config/code-server
    cat > ~/.config/code-server/config.yaml << 'EOF'
    bind-addr: 127.0.0.1:8080
    auth: password
    password: YOUR_PASSWORD_HERE  # Đổi mật khẩu ở đây
    cert: false
    user-data-dir: /mnt/workspace/.vscode
    EOF
```

### Cài extensions tự động

Thêm vào workflow sau bước khởi động Code-Server:

```yaml
- name: 📦 Cài extensions
  run: |
    code-server --install-extension ms-python.python
    code-server --install-extension dbaeumer.vscode-eslint
    code-server --install-extension esbenp.prettier-vscode
```

### Tăng thời gian sử dụng

Sửa phần `options` trong workflow:

```yaml
options:
  - '1h'
  - '3h' 
  - '5h40m'
  - '6h'  # Thêm tùy chọn 6 giờ (Max của GitHub)
```

---

## 📊 Monitoring

Trong quá trình chạy, workflow sẽ hiển thị thông tin mỗi 5 phút:

```
┌──────────────────────────────────────────────────┐
│                                                  │
│  ⏰ THỜI GIAN: 1h 25m | Lần kiểm tra: #17/68     │
│                                                  │
├──────────────────────────────────────────────────┤
│                                                  │
│  🌐 VS Code đang chạy tại:                       │
│                                                  │
│     http://your-url.kami.link                    │
│                                                  │
├──────────────────────────────────────────────────┤
│                                                  │
│  📊 TRẠNG THÁI HỆ THỐNG:                         │
│                                                  │
│     💾 Ổ cứng    : 2.3G sử dụng / 56G còn trống  │
│     🧠 RAM       : 4.2G / 16G (26.2%)            │
│     ⚡ CPU Load  : 0.52                           │
│     ✅ Trạng thái: Hoạt động bình thường         │
│                                                  │
└──────────────────────────────────────────────────┘
```

---

## 🌐 Use Cases

### 👨‍💻 Lập trình viên

- Code khi không có máy tính mạnh
- Test code trên server Linux
- Làm việc từ xa với bất kỳ thiết bị nào

### 🎓 Học sinh - Sinh viên

- Học lập trình không cần máy mạnh
- Làm bài tập coding
- Thực hành Git & Terminal

### 🚀 Freelancer

- Demo project cho khách hàng
- Code khi đi công tác
- Backup workspace khẩn cấp

### 🔬 Research & Testing

- Test thư viện mới
- Chạy scripts nhanh
- Thử nghiệm môi trường Linux

---

## 🛡️ Security

- ✅ Kết nối qua HTTPS (Kami Tunnel)
- ✅ Mật khẩu bảo vệ
- ✅ Session timeout tự động
- ⚠️ Không lưu trữ thông tin nhạy cảm
- ⚠️ Sử dụng GitHub Secrets cho API keys

---

## 📝 Changelog

### Version 1.0.0 (2026-02-01)
- ✨ Release đầu tiên
- ✅ Hỗ trợ Code-Server
- ✅ Tích hợp Kami Tunnel
- ✅ Ổ đĩa ảo 60GB
- ✅ 3 tùy chọn thời gian
- ✅ Monitoring real-time

---

## 🤝 Contributing

Contributions, issues và feature requests luôn được chào đón!

1. Fork repo
2. Tạo branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Mở Pull Request

---

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 💖 Credits

### Công nghệ sử dụng

- [Code-Server](https://github.com/coder/code-server) - VS Code in the browser
- [Kami Tunnel](https://github.com/kami2k1/tunnel) - Expose local servers
- [GitHub Actions](https://github.com/features/actions) - CI/CD platform

### Tác giả

- **Zun** - *Initial work* - Tạo workflow và tối ưu hóa

---

## 📞 Support

Nếu bạn gặp vấn đề hoặc có câu hỏi:

- 📫 Tạo [Issue](../../issues) trên GitHub
- 💬 Tham gia discussions
- ⭐ Star repo này nếu thấy hữu ích!

---

## 🎯 Roadmap

- [ ] Hỗ trợ nhiều tunnel providers
- [ ] Tích hợp database (MySQL, PostgreSQL)
- [ ] Auto-backup code lên GitHub
- [ ] Dark theme cho log output
- [ ] Docker support
- [ ] Multiple VS Code instances

---

## ⚖️ Disclaimer

⚠️ **Lưu ý:** 

- Tool này dùng tài nguyên GitHub Actions, vui lòng tuân thủ [GitHub Terms of Service](https://docs.github.com/en/site-policy/github-terms/github-terms-of-service)
- Không sử dụng cho mục đích thương mại hoặc vi phạm pháp luật
- Tác giả không chịu trách nhiệm về việc sử dụng sai mục đích
- Dữ liệu của bạn sẽ bị xóa sau khi workflow kết thúc

---

<div align="center">

**Made with ❤️ by Zun**

[⬆ Back to top](#-vs-code-web-idx---zun-x-kami-tunnel)

</div>
