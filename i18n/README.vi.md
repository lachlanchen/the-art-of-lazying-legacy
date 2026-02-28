[English](../README.md) · [العربية](README.ar.md) · [Español](README.es.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Tiếng Việt](README.vi.md) · [中文 (简体)](README.zh-Hans.md) · [中文（繁體）](README.zh-Hant.md) · [Deutsch](README.de.md) · [Русский](README.ru.md)


# Nghệ Thuật Sống Lười

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub Sponsors](https://img.shields.io/badge/Sponsor-GitHub%20Sponsors-pink)](https://github.com/sponsors/lachlanchen)
[![Website](https://img.shields.io/badge/Website-lazying.art-0a66c2)](https://lazying.art)
[![Docs](https://img.shields.io/badge/Docs-Multilingual-1f883d)](i18n)
[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)](#điều-kiện-tiên-quyết)
[![Platform](https://img.shields.io/badge/Platform-Raspberry%20Pi%20%2B%20Shell%20Tools-6f42c1)](#các-dự-án)

Kho mã này cổ vũ triết lý “lười có chiến lược” để sống đơn giản mà vẫn hiệu quả, bao gồm AI agents, học ngôn ngữ và vlog với mẹo thực hành cùng các tình huống ứng dụng thực tế.

![EinkWordsGPT Demo](https://raw.githubusercontent.com/lachlanchen/the-art-of-lazying/refs/heads/main/code/EinkWordsGPT/demo.jpg)

## Mục lục

- [Tổng quan](#tổng-quan)
- [Tính năng](#tính-năng)
- [Các dự án](#các-dự-án)
- [Cấu trúc dự án](#cấu-trúc-dự-án)
- [Giới thiệu](#giới-thiệu)
- [Lý thuyết về Lazying](#lý-thuyết-về-lazying)
- [Mẹo và thủ thuật thực hành](#mẹo-và-thủ-thuật-thực-hành)
- [Tình huống sử dụng](#tình-huống-sử-dụng)
- [AI Agents và tự động hóa](#ai-agents-và-tự-động-hóa)
- [Học ngôn ngữ và vlog](#học-ngôn-ngữ-và-vlog)
- [Điều kiện tiên quyết](#điều-kiện-tiên-quyết)
- [Cài đặt](#cài-đặt)
- [Cấu hình](#cấu-hình)
- [Cách dùng](#cách-dùng)
- [Ví dụ](#ví-dụ)
- [Ghi chú phát triển](#ghi-chú-phát-triển)
- [Khắc phục sự cố](#khắc-phục-sự-cố)
- [Lộ trình](#lộ-trình)
- [Đóng góp cộng đồng](#đóng-góp-cộng-đồng)
- [Đóng góp](#đóng-góp)
- [Kết nối](#kết-nối)
- [Hỗ trợ / Quyên góp](#hỗ-trợ--quyên-góp)
- [Giấy phép](#giấy-phép)

## Tổng quan

`The Art of Lazying` là kho tổng hợp theo hướng “umbrella”, kết hợp triết lý sống, tự động hóa thực tiễn, công cụ sáng tạo có AI hỗ trợ và các thử nghiệm học ngôn ngữ.

Bao gồm:

- Trưng bày các dự án AI và workflow liên kết.
- Script/công cụ cục bộ cho thao tác shell an toàn và các workflow tiện ích.
- Dự án học ngôn ngữ dựa trên phần cứng (`EinkWordsGPT`) dùng Raspberry Pi + Waveshare e-ink + OpenAI.
- Các thử nghiệm vlog/tooling như tổng hợp DNS/IP và chuyển repository thành văn bản.
- Tài liệu đa ngôn ngữ trong [`i18n/`](i18n).

### Tổng quan nhanh

| Trọng tâm | Những gì bạn nhận được |
|------|---|
| 🧠 Triết lý | Nguyên tắc lười có chiến lược cho công việc đòn bẩy cao |
| 🤖 AI | Hỗ trợ sáng tạo, chép lời, dịch thuật, hỗ trợ xuất bản |
| 🛠️ Tiện ích | Xóa/khôi phục shell an toàn, công cụ DNS/IP, chuyển repo thành văn bản |
| 🌍 i18n | Các phiên bản README đa ngôn ngữ trong `i18n/` |

## Tính năng

- Khung “lười có chiến lược” tập trung vào nỗ lực đòn bẩy cao.
- Tài liệu tham chiếu cho workflow sáng tạo và xuất bản có AI hỗ trợ.
- Tiện ích học ngôn ngữ và hệ thống màn hình e-ink để học tập.
- Bộ trợ giúp an toàn cho shell (`saferm`, `unrm`, `removeitanyway`).
- Tiện ích Python gọn nhẹ cho thu thập DNS/IP và hợp nhất văn bản từ codebase.
- Hỗ trợ README đa ngôn ngữ.

## Các dự án

### 🤖 Công cụ sáng tạo dùng AI

| Dự án | Mô tả | Demo |
|---------|-------------|------|
| [EinkWordsGPT](https://github.com/lachlanchen/the-art-of-lazying/tree/main/code/EinkWordsGPT) | Màn hình e-ink học từ vựng với GPT | ![WordsOrigin](demos/words_card_arabic.JPG) |
| [WordsOrigin](https://github.com/lachlanchen/WordOrigins) | Phân tích nguồn gốc từ và trình bày dạng đồ thị. | ![WordsOrigin](demos/words_origin.jpg) |
| [LazyLanguageLearner](https://github.com/lachlanchen/lazylanguagelearner) | Bộ công cụ học ngôn ngữ hiệu quả với ít công sức hơn | |
| [VideoCaptionerWithClip](https://github.com/lachlanchen/VideoCaptionerWithClip) | Tạo caption cho video & ảnh bằng OpenAI CLIP embeddings + GPT decoder | ![AutoCaption](demos/autocaption.PNG) |
| [VideoCaptionerWithVit](https://github.com/lachlanchen/VideoCaptionerWithVit) | Công cụ caption video: trích xuất keyframe bằng Katna/OpenCV và tạo caption bằng mô hình ViT+GPT-2 | |
| [AutoTranscription - MultilingualWhisper](https://github.com/lachlanchen/MultilingualWhisper) | Pipeline chép lời đa ngôn ngữ với nhận diện ngôn ngữ chi tiết | ![AutoTranscription](demos/autotranscription.PNG) |
| [**AutoTranslation**](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_translate.py) | Phá bỏ rào cản ngôn ngữ để trao đổi sáng tạo toàn cầu | ![AutoTranslation](demos/autotranslation.JPG) |
| [**AutoMeta**](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_metadata.py) | Tự động tạo metadata cho video | |
| [LazyEdit](https://github.com/lachlanchen/LazyEdit) | Công cụ chỉnh sửa video tự động dùng AI với chép lời, phụ đề tự động, highlight và tạo metadata | |
| [AutoPublication](https://github.com/lachlanchen/AutoPublication) | Tinh gọn workflow xuất bản nội dung | ![AutoPublication](demos/autopublication.png) |
| [AutoPubMonitor](https://github.com/lachlanchen/AutoPubMonitor) | Hệ thống tự động theo dõi, xử lý và xuất bản nội dung video lên nhiều nền tảng | |
| [Grilling ChatGPT](https://github.com/lachlanchen/grilling_chatgpt) | Kỹ thuật nâng cao để dùng trợ lý AI hiệu quả | |

### 🔄 Công cụ tự động hóa

Tự động hóa/tooling cục bộ trong repository này bao gồm:

- [`scripts/lazy-care/SafeShell/safeshell_functions.sh`](scripts/lazy-care/SafeShell/safeshell_functions.sh): workflow xóa/khôi phục an toàn hơn cho người dùng shell.
- [`vlogs/chatgpt-traffic/chatgpt-traffic.py`](vlogs/chatgpt-traffic/chatgpt-traffic.py): trình phân giải domain sang IP/CIDR và loại trùng lặp.
- [`vlogs/repo2text/convert-repo-to-merged-text.py`](vlogs/repo2text/convert-repo-to-merged-text.py): gộp các file Python theo thư mục con thành các tệp văn bản.

## Cấu trúc dự án

### Cấu trúc repository hiện tại

```text
the-art-of-lazying/
├── README.md
├── README_EN.md
├── README_CN.md
├── LICENSE
├── .github/
│   └── FUNDING.yml
├── books/
├── code/
│   └── EinkWordsGPT/
├── demos/
├── examples/
│   └── lazy-learning/BuildChachaGPTWithChatGPT/
├── figs/
├── i18n/
│   ├── README.ar.md
│   ├── README.es.md
│   ├── README.fr.md
│   ├── README.ja.md
│   ├── README.ko.md
│   ├── README.vi.md
│   ├── README.zh-Hans.md
│   └── README.zh-Hant.md
├── scripts/
│   └── lazy-care/
│       └── SafeShell/
└── vlogs/
    ├── chatgpt-traffic/
    ├── google-framework/
    └── repo2text/
```

### Cấu trúc thư mục ý niệm ban đầu (được giữ lại)

```text
the-art-of-lazying/
│
├───code/
│ ├───ai-agents/
│ ├───automation/
│ └───language-learning/
│
├───book/
│ ├───manuscript/
│ └───resources/
│
├───examples/
│ ├───practical-tips/
│ ├───use-cases/
│ └───community-contributions/
│
└───vlogs/
  ├───language-learning/
  └───lazy-lifestyle/
```

## Giới thiệu

The Art of Lazying xem “lười có chiến lược” là cách tối ưu năng lượng và tập trung vào điều thực sự quan trọng. Repository này khám phá cách sự lười có chủ đích có thể dẫn đến năng suất, sáng tạo và chất lượng sống cao hơn.

## Lý thuyết về Lazying

Đây là phần giới thiệu toàn diện về các nguyên tắc của “lười có chiến lược”, tập trung vào cách tối đa hóa năng suất và hạnh phúc thông qua ưu tiên, ủy thác và tự động hóa công việc.

Nguyên tắc cốt lõi là áp dụng quy tắc 80/20 của Pareto vào cuộc sống hằng ngày: xác định 20% hoạt động tạo ra 80% kết quả mong muốn.

## Mẹo và thủ thuật thực hành

Tập hợp các lời khuyên có thể hành động ngay để áp dụng nguyên tắc “lười” vào công việc, quan hệ và chăm sóc bản thân:

- Tự động hóa các tác vụ lặp lại.
- Dùng kỹ thuật Pomodoro để quản lý thời gian.
- Xây dựng hệ thống giúp giảm mệt mỏi khi ra quyết định.
- Tận dụng công cụ AI để được hỗ trợ.

## Tình huống sử dụng

Các ví dụ thực tế cho thấy nguyên tắc lazying giải quyết vấn đề và cải thiện hiệu quả như thế nào:

- Cách doanh nhân dùng ủy thác và tự động hóa để tập trung tăng trưởng kinh doanh.
- Cách giới học thuật tinh gọn workflow nghiên cứu.
- Cách nhà sáng tạo nội dung tối ưu quy trình sản xuất.

## AI Agents và tự động hóa

Khám phá việc phát triển AI agents và công cụ tự động hóa để đơn giản hóa tác vụ:

- Dùng ChatGPT làm trợ lý cá nhân.
- Xây dựng workflow tự động hóa tùy chỉnh.
- Tạo màn hình e-ink cho học tập thụ động.

## Học ngôn ngữ và vlog

Tài nguyên và kỹ thuật để học ngôn ngữ hiệu quả, cùng các vlog ghi lại hành trình lazying:

- Tạo lộ trình học ngôn ngữ cá nhân hóa với spaced repetition.
- Triển khai các kỹ thuật học nhập vai.
- Xây dựng dự án khuyến khích học tập thụ động.

## Điều kiện tiên quyết

Repository này gồm nhiều dự án và không có một manifest phụ thuộc cấp cao nhất duy nhất. Chỉ cài những gì bạn cần theo từng module.

Yêu cầu phổ biến:

- `git`
- Python `3.9+` (khuyến nghị)
- `pip`
- Công cụ môi trường ảo (tùy chọn) (`python -m venv`)

Các tín hiệu theo từng module từ source code/README:

- `code/EinkWordsGPT`: `openai`, `Pillow`, `pytz`, `pykakasi`, thư viện Python cho Waveshare e-paper (`waveshare_epd`) và phần cứng tương thích.
- `vlogs/chatgpt-traffic`: `dnspython`.
- `scripts/lazy-care/SafeShell`: Bash/Zsh shell.

## Cài đặt

### 1. Clone repository

```bash
git clone https://github.com/lachlanchen/the-art-of-lazying.git
cd the-art-of-lazying
```

### 2. (Khuyến nghị) Tạo Python virtual environment

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
```

### 3. Cài phụ thuộc Python cho các module đã chọn

```bash
pip install openai pillow pytz pykakasi dnspython
```

### 4. Thiết lập SafeShell (tùy chọn)

```bash
cd scripts/lazy-care/SafeShell
cat safeshell_functions.sh >> ~/.bashrc  # or ~/.zshrc
source ~/.bashrc  # or ~/.zshrc
```

## Cấu hình

### OpenAI / EinkWordsGPT

- `code/EinkWordsGPT/words_gpt.py` và `words_update.py` dùng `OpenAI()` và kỳ vọng thông tin xác thực có sẵn trong môi trường của bạn.
- Khuyến nghị:

```bash
export OPENAI_API_KEY="your_api_key_here"
```

### Vị trí thùng rác của SafeShell

- `safeshell_functions.sh` dùng đường dẫn gốc cố định cho thùng rác:

```bash
/mnt/disk/BIN/ROOT
```

Hãy chỉnh đường dẫn này trong script nếu máy của bạn dùng cấu trúc khác.

### Thư mục nguồn/đích của repo2text

- `vlogs/repo2text/convert-repo-to-merged-text.py` hiện đặt:
  - `source_directory = 'diffraction'`
  - `target_directory = 'merged_py_files'`

Hãy sửa các biến này trước khi chạy.

## Cách dùng

### Chạy vòng lặp hiển thị EinkWordsGPT (cần thiết lập phần cứng)

```bash
cd code/EinkWordsGPT
python words_gpt.py
```

### Chạy script bảo trì/cập nhật từ vựng EinkWordsGPT

```bash
cd code/EinkWordsGPT
python words_update.py
```

### Chạy trình phân giải domain/IP cho ChatGPT traffic

```bash
cd vlogs/chatgpt-traffic
pip install dnspython
python chatgpt-traffic.py
```

### Chạy công cụ gộp file Python trong repository

```bash
cd vlogs/repo2text
python convert-repo-to-merged-text.py
```

### Dùng lệnh SafeShell sau khi đã source

```bash
saferm /path/to/file_or_directory
unrm /path/to/file_or_directory
removeitanyway /path/to/file_or_directory
```

## Ví dụ

- `code/EinkWordsGPT/demo.jpg`: mẫu đầu ra e-ink.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/plain_transformer.ipynb`: ví dụ notebook.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/Prompts of ChachaGPT.pdf`: tài liệu tham chiếu prompt.
- `demos/`: demo hình ảnh dùng trong README này.

## Ghi chú phát triển

- Repository này là dự án umbrella kiểu legacy, không phải một ứng dụng đóng gói dạng đơn khối.
- Một số công cụ liên kết trong bảng Projects nằm ở repository bên ngoài; hãy dùng README riêng của từng repo để biết chi tiết runtime.
- Một số tài liệu nội bộ mô tả cấu trúc file cũ hơn (ví dụ, `scripts/lazy-care` từng tham chiếu script tách rời, trong khi triển khai hiện tại được gom trong `SafeShell/safeshell_functions.sh`).
- Code phụ thuộc phần cứng trong `EinkWordsGPT` giả định môi trường Raspberry Pi + Waveshare e-paper.

### Giả định (tường minh)

- README cấp cao nhất là điểm vào chuẩn (canonical), còn hướng dẫn chạy chi tiết cho các dự án liên kết bên ngoài được duy trì ở repository tương ứng.
- Phiên bản gói Python được để mở có chủ đích vì repo này hiện chưa cung cấp `requirements.txt`/`pyproject.toml` ở thư mục gốc.
- Với `EinkWordsGPT`, các bước cài driver cho phần cứng Waveshare được giả định thực hiện trên môi trường Raspberry Pi đích.

## Khắc phục sự cố

- `ModuleNotFoundError: waveshare_epd`: cài thư viện Waveshare e-paper trên thiết bị đích và xác nhận đủ phụ thuộc đặc thù phần cứng.
- Lỗi xác thực OpenAI: kiểm tra `OPENAI_API_KEY` đã được set trong shell/session đang hoạt động.
- `File not found` liên quan `words_phonetics.db` hoặc font: chạy script từ `code/EinkWordsGPT` để đường dẫn tương đối được resolve đúng.
- Không tìm thấy lệnh SafeShell: bảo đảm `safeshell_functions.sh` đã được append vào đúng file cấu hình shell và reload shell.
- `repo2text` không tạo file: kiểm tra `source_directory` có tồn tại và chứa file `.py`.

## Lộ trình

- Chuẩn hóa quản lý dependencies với `requirements.txt` tùy chọn cho từng module.
- Thêm task runner cấp root hoặc Makefile cho workflow phổ biến.
- Mở rộng tài liệu setup tái lập được cho triển khai Raspberry Pi + Waveshare.
- Bổ sung test cho script tiện ích và helper chuyển đổi dữ liệu.
- Tiếp tục cải thiện độ tương đương tài liệu đa ngôn ngữ trong `i18n/`.

## Đóng góp cộng đồng

Chia sẻ trải nghiệm, mẹo và ý tưởng của bạn về “lười có chiến lược”:

- Diễn đàn trao đổi các mẹo năng suất.
- Công cụ và template cho thói quen hằng ngày.
- Dự án cộng tác cho hiệu quả kiểu “lười mà chất”.

## Đóng góp

Mọi đóng góp cho nội dung, script và tài liệu dự án đều được chào đón.

Luồng làm việc chuẩn:

1. Fork dự án.
2. Tạo nhánh tính năng (`git checkout -b feature/AmazingFeature`).
3. Commit thay đổi (`git commit -m 'Add some AmazingFeature'`).
4. Push nhánh (`git push origin feature/AmazingFeature`).
5. Mở Pull Request.

Nếu thay đổi của bạn ảnh hưởng một submodule cụ thể, hãy cập nhật README của submodule đó luôn.

## Kết nối

| Kênh | Liên kết |
|---|---|
| 🌐 Website | [lazying.art](https://lazying.art) |
| 🧑‍💻 GitHub | [lachlanchen](https://github.com/lachlanchen) |
| ✉️ Email | `lach@lazying.art` |

---

## Hỗ trợ / Quyên góp

<div align="center">
<table style="margin:0 auto; text-align:center; border-collapse:collapse;">
  <tr>
    <td style="text-align:center; vertical-align:middle; padding:6px 12px;">
      <a href="https://chat.lazying.art/donate">https://chat.lazying.art/donate</a>
    </td>
    <td style="text-align:center; vertical-align:middle; padding:6px 12px;">
      <a href="https://chat.lazying.art/donate"><img src="figs/donate_button.svg" alt="Donate" height="44"></a>
    </td>
  </tr>
  <tr>
    <td style="text-align:center; vertical-align:middle; padding:6px 12px;">
      <a href="https://paypal.me/RongzhouChen">
        <img src="https://img.shields.io/badge/PayPal-Donate-003087?logo=paypal&logoColor=white" alt="Donate with PayPal">
      </a>
    </td>
    <td style="text-align:center; vertical-align:middle; padding:6px 12px;">
      <a href="https://buy.stripe.com/aFadR8gIaflgfQV6T4fw400">
        <img src="https://img.shields.io/badge/Stripe-Donate-635bff?logo=stripe&logoColor=white" alt="Donate with Stripe">
      </a>
    </td>
  </tr>
  <tr>
    <td style="text-align:center; vertical-align:middle; padding:6px 12px;"><strong>WeChat</strong></td>
    <td style="text-align:center; vertical-align:middle; padding:6px 12px;"><strong>Alipay</strong></td>
  </tr>
  <tr>
    <td style="text-align:center; vertical-align:middle; padding:6px 12px;"><img alt="WeChat QR" src="figs/donate_wechat.png" width="240"/></td>
    <td style="text-align:center; vertical-align:middle; padding:6px 12px;"><img alt="Alipay QR" src="figs/donate_alipay.png" width="240"/></td>
  </tr>
</table>
</div>

## Giấy phép

Repository này được cấp phép theo MIT License. Xem [LICENSE](LICENSE) để biết chi tiết.

Ghi chú:

- Giấy phép dự án cấp cao nhất: MIT.
- Một số thư mục con có `LICENSE` riêng; khi có nghi ngờ, hãy ưu tiên file giấy phép cụ thể nhất trong đường dẫn đó.
