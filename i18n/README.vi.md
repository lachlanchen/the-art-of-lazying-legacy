[English](../README.md) · [العربية](README.ar.md) · [Español](README.es.md) · [Français](README.fr.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Tiếng Việt](README.vi.md) · [中文 (简体)](README.zh-Hans.md) · [中文（繁體）](README.zh-Hant.md) · [Deutsch](README.de.md) · [Русский](README.ru.md)


[![LazyingArt banner](https://github.com/lachlanchen/lachlanchen/raw/main/figs/banner.png)](https://github.com/lachlanchen/lachlanchen/blob/main/figs/banner.png)

# Nghệ Thuật Lười Biếng

<p align="center">
<a href="LICENSE"><img alt="License" src="https://img.shields.io/badge/License-GPL--3.0-blue.svg" /></a>
<a href="https://github.com/sponsors/lachlanchen"><img alt="GitHub Sponsors" src="https://img.shields.io/badge/Sponsor-GitHub%20Sponsors-pink?logo=github&logoColor=white" /></a>
<a href="https://lazying.art"><img alt="Website" src="https://img.shields.io/badge/Website-lazying.art-0a66c2?logo=Google%20Chrome&logoColor=white" /></a>
<a href="i18n"><img alt="Docs" src="https://img.shields.io/badge/Docs-Multilingual-1f883d?logo=markdown&logoColor=white" /></a>
<a href="#prerequisites"><img alt="Python" src="https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white" /></a>
<a href="https://github.com/lachlanchen/the-art-of-lazying/commits"><img alt="Last commit" src="https://img.shields.io/github/last-commit/lachlanchen/the-art-of-lazying?style=flat-square" /></a>
<a href="https://github.com/lachlanchen/the-art-of-lazying/stargazers"><img alt="GitHub Stars" src="https://img.shields.io/github/stars/lachlanchen/the-art-of-lazying?style=flat-square" /></a>
<a href="https://github.com/lachlanchen/the-art-of-lazying/issues"><img alt="Open Issues" src="https://img.shields.io/github/issues/lachlanchen/the-art-of-lazying?style=flat-square&color=orange" /></a>
<a href="https://github.com/lachlanchen/the-art-of-lazying/network/members"><img alt="Forks" src="https://img.shields.io/github/forks/lachlanchen/the-art-of-lazying?style=flat-square" /></a>
</p>

Một không gian repository để thử nghiệm năng suất có hỗ trợ AI trong thực tế, hệ thống học ngôn ngữ và các công cụ tiện ích.

> Làm việc ít hơn ở những nhiệm vụ giá trị thấp, dành năng lượng cho những kết quả có đòn bẩy cao.

| 🎯 Mục tiêu | 🎛️ Công nghệ chính | 🧭 Mục tiêu |
|---|---|---|
| tự động hóa các công việc lặp lại | Python + shell | giảm tải gánh nặng nhận thức |

---

![EinkWordsGPT Demo](https://raw.githubusercontent.com/lachlanchen/the-art-of-lazying/refs/heads/main/code/EinkWordsGPT/demo.jpg)

## Mục lục

- [Tổng quan](#tổng-quan)
- [Tính năng](#tính-năng)
- [Các dự án](#các-dự-án)
- [Cấu trúc dự án](#cấu-trúc-dự-án)
- [Tổng quan về cách tiếp cận Lazying](#tổng-quan-về-cách-tiếp-cận-lazying)
- [Mẹo thực tế](#mẹo-thực-tế)
- [Tình huống sử dụng](#tình-huống-sử-dụng)
- [AI Agents và Tự động hóa](#ai-agents-và-tự-động-hóa)
- [Học ngôn ngữ và Vlogs](#học-ngôn-ngữ-và-vlogs)
- [Điều kiện tiên quyết](#điều-kiện-tiên-quyết)
- [Cài đặt](#cài-đặt)
- [Cấu hình](#cấu-hình)
- [Cách sử dụng](#cách-sử-dụng)
- [Ví dụ](#ví-dụ)
- [Ghi chú phát triển](#ghi-chú-phát-triển)
- [Khắc phục sự cố](#khắc-phục-sự-cố)
- [Lộ trình](#lộ-trình)
- [Đóng góp cộng đồng](#đóng-góp-cộng-đồng)
- [Đóng góp](#đóng-góp)
- [❤️ Hỗ trợ](#-support)
- [Kết nối](#kết-nối)
- [Giấy phép](#giấy-phép)

## Tổng quan

`The Art of Lazying` là một repository kiểu “umbrella” ở cấp độ hệ thống: một bộ sưu tập thực dụng gồm quy trình làm việc có AI hỗ trợ, công cụ shell tiện ích, các thí nghiệm Raspberry Pi và tài nguyên học tập.

### Dấu hiệu của dự án

| Chỉ số | Giá trị |
|---|---|
| Kiểu repository | Legacy umbrella repo |
| Môi trường chạy chính | Python + shell scripts |
| Trọng tâm phần cứng | Raspberry Pi + e-ink (theo từng module) |
| Tài liệu | Bộ README đa ngôn ngữ trong `i18n/` |
| Giấy phép | GNU General Public License 3.0 (root và các thư mục chính) |

## Tính năng

- ✅ Khung chiến lược lười biếng: ưu tiên nhiệm vụ có đòn bẩy cao hơn là thao tác lặp lại.
- ✅ Công cụ sáng tạo và thí nghiệm xuất bản có hỗ trợ AI.
- ✅ Tiện ích học ngôn ngữ với hiển thị e-ink và quy trình làm việc từ vựng có hỗ trợ OpenAI (`code/EinkWordsGPT`).
- ✅ Tăng độ an toàn cho shell với (`saferm` / `unrm` / `removeitanyway`).
- ✅ Các script Python nhẹ cho thu thập DNS/IP và chuyển mã thành văn bản.
- ✅ Kho tài liệu đa ngôn ngữ với các phiên bản README theo từng ngôn ngữ.

## Các dự án

### 🤖 Công cụ sáng tạo có AI

| Dự án | Loại | Mục tiêu |
|---|---|---|
| [EinkWordsGPT](https://github.com/lachlanchen/the-art-of-lazying/tree/main/code/EinkWordsGPT) | Module cục bộ | Raspberry Pi + màn hình từ khóa e-ink Waveshare dùng OpenAI |
| [WordsOrigin](https://github.com/lachlanchen/WordOrigins) | Dự án bên ngoài | Phân tích nguồn gốc từ và trình bày theo kiểu đồ thị |
| [LazyLanguageLearner](https://github.com/lachlanchen/lazylanguagelearner) | Dự án bên ngoài | Dự án công cụ học ngôn ngữ |
| [VideoCaptionerWithClip](https://github.com/lachlanchen/VideoCaptionerWithClip) | Dự án bên ngoài | Tạo phụ đề bằng embedding CLIP + GPT |
| [AutoTranscription - MultilingualWhisper](https://github.com/lachlanchen/MultilingualWhisper) | Dự án bên ngoài | Pipeline phiên âm đa ngôn ngữ |
| [AutoTranslation](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_translate.py) | Script bên ngoài | Hỗ trợ dịch phụ đề và đa ngôn ngữ |
| [AutoMeta](https://github.com/lachlanchen/LazyEdit/blob/master/lazyedit/subtitle_metadata.py) | Script bên ngoài | Tự động tạo metadata media |
| [LazyEdit](https://github.com/lachlanchen/LazyEdit) | Dự án bên ngoài | Quy trình chỉnh sửa video và phụ đề |
| [AutoPublication](https://github.com/lachlanchen/AutoPublication) | Dự án bên ngoài | Tự động hóa quy trình xuất bản nội dung |
| [AutoPubMonitor](https://github.com/lachlanchen/AutoPubMonitor) | Dự án bên ngoài | Giám sát + điều phối xuất bản |
| [Grilling ChatGPT](https://github.com/lachlanchen/grilling_chatgpt) | Dự án bên ngoài | Mẫu chiến lược prompt và cách dùng AI nâng cao |

### 🛠️ Công cụ tự động hóa cục bộ

- [`scripts/lazy-care/SafeShell/safeshell_functions.sh`](scripts/lazy-care/SafeShell/safeshell_functions.sh): quy trình xóa/khôi phục an toàn hơn cho người dùng shell.
- [`vlogs/chatgpt-traffic/chatgpt-traffic.py`](vlogs/chatgpt-traffic/chatgpt-traffic.py): công cụ giải mã domain-to-IP và danh sách CIDR.
- [`vlogs/repo2text/convert-repo-to-merged-text.py`](vlogs/repo2text/convert-repo-to-merged-text.py): gộp các file Python trong thư mục con thành các cụm văn bản cho việc duyệt bằng AI.

## Cấu trúc dự án

### Bố cục repository hiện tại

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

### Cấu trúc khái niệm lịch sử (tài liệu lịch sử)

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

## Tổng quan về cách tiếp cận Lazying

Repo này định vị năng suất thực tế trên nguyên tắc **lười biếng chiến lược**: tự động hóa các quyết định giá trị thấp, giữ năng lượng nhận thức, và ưu tiên áp dụng hệ thống trước khi ứng xử theo phản xạ.

Nguyên tắc cốt lõi vẫn là góc nhìn thực dụng 80/20:

- Xác định 20% hành động có đòn bẩy cao nhất.
- Chuẩn hóa/tự động hóa các luồng lặp lại.
- Loại bỏ ma sát không cần thiết trong thực hành hằng ngày.

## Mẹo thực tế

- Thay các luồng lệnh lặp lại bằng shell functions.
- Dùng chu kỳ lập kế hoạch ngắn (nhịp tương thích Pomodoro).
- Giảm mệt mỏi quyết định bằng việc tạo template lặp lại.
- Để AI xử lý bước soạn thảo/chuyển đổi ban đầu, sau đó xem xét thủ công.

## Tình huống sử dụng

- Giao phó và tự động hóa các thao tác lặp lại trong quy trình tạo nội dung.
- Tối ưu hóa nghiên cứu/tài liệu hóa thông qua tóm tắt do AI hỗ trợ.
- Chuyển nhanh ngữ cảnh mã thành văn bản dùng được cho AI để phân tích.

## AI Agents và Tự động hóa

Những thí nghiệm được thể hiện trong repository gồm:

- Quy trình trợ lý thực dụng cho học từ vựng và tạo nội dung.
- Gom DNS/IP có thể script hóa cho công việc vận hành.
- Xuất repo thành văn bản để kiểm tra mã bằng AI nhanh hơn.
- Công cụ an toàn cấp shell tùy chọn giúp tránh lỗi hủy dữ liệu.

## Học ngôn ngữ và Vlogs

Nội dung và dự án liên quan ngôn ngữ nhấn mạnh tính nhất quán với nỗ lực thấp:

- Tiếp xúc thụ động + ôn tập định kỳ qua màn hình e-ink.
- Quy trình ghi chú liên ngôn ngữ trong các subproject hỗ trợ.
- Kịch bản vlog và ghi chú như ví dụ thực hành cho kỹ thuật quy trình thường nhật.

## Điều kiện tiên quyết

Repository này theo hướng module; không có manifest phụ thuộc ở cấp root.

### Danh sách kiểm tra môi trường

| Mục | Cơ sở |
|---|---|
| Hệ điều hành | Linux/macOS (công cụ shell), Windows WSL được chấp nhận cho script Python |
| Python | 3.9+ |
| Trình quản lý gói | `pip` |
| Kiểm soát phiên bản | `git` |

### Phụ thuộc theo module (theo mã nguồn)

- `code/EinkWordsGPT`: `openai`, `Pillow`, `pytz`, `pykakasi`, `waveshare_epd`, và runtime Raspberry Pi/e-paper (`font/*`, `pic/*`).
- `vlogs/chatgpt-traffic`: `dnspython`.
- `vlogs/repo2text`: chỉ dùng thư viện chuẩn.
- `scripts/lazy-care/SafeShell`: Bash/Zsh với `mv`, `realpath`, và luồng xác nhận tùy chọn.

## Cài đặt

### 1) Clone

```bash

git clone https://github.com/lachlanchen/the-art-of-lazying.git
cd the-art-of-lazying
```

### 2) Thiết lập môi trường ảo đề xuất

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
```

### 3) Cài đặt phụ thuộc theo module

```bash
pip install openai pillow pytz pykakasi dnspython
```

### 4) Thiết lập tùy chọn: SafeShell bootstrap

```bash
cd scripts/lazy-care/SafeShell
cat safeshell_functions.sh >> ~/.bashrc  # hoặc ~/.zshrc
source ~/.bashrc  # hoặc source ~/.zshrc
```

## Cấu hình

### 1) OpenAI / EinkWordsGPT

Cả hai script của EinkWordsGPT đều khởi tạo trực tiếp `OpenAI()`, vì vậy runtime phải có biến chứng thực.

```bash
export OPENAI_API_KEY="your_openai_api_key"
```

### 2) Vị trí thùng rác SafeShell

`/mnt/disk/BIN/ROOT` được mã hóa cứng làm đường dẫn thùng rác gốc trong `scripts/lazy-care/SafeShell/safeshell_functions.sh`. Hãy chỉnh sửa nếu cần.

### 3) Đường dẫn merge `repo2text`

Mặc định trong `vlogs/repo2text/convert-repo-to-merged-text.py` là:

- `source_directory = 'diffraction'`
- `target_directory = 'merged_py_files'`

Sửa cả hai nếu chạy trong repo có tên thư mục không khớp.

### 4) Mục tùy chỉnh của `chatgpt-traffic`

`custom_ips`, `cidr`, và `domains` hiện đang nằm trong `vlogs/chatgpt-traffic/chatgpt-traffic.py`. Chỉnh trực tiếp theo nhu cầu.

## Cách sử dụng

### Bảng lệnh nhanh

| Nhiệm vụ | Đường dẫn lệnh | Lệnh |
|---|---|---|
| Vòng lặp hiển thị EinkWordsGPT | `code/EinkWordsGPT` | `python words_gpt.py` |
| Trình cập nhật EinkWordsGPT | `code/EinkWordsGPT` | `python words_update.py` |
| Bộ phân giải Domain/IP | `vlogs/chatgpt-traffic` | `python chatgpt-traffic.py` |
| Hợp nhất repo thành text | `vlogs/repo2text` | `python convert-repo-to-merged-text.py` |
| Sử dụng SafeShell | profile shell + shell hiện tại | `saferm`, `unrm`, `removeitanyway` |

### EinkWordsGPT

```bash
cd code/EinkWordsGPT
python words_gpt.py
python words_update.py
```

### ChatGPT Traffic Resolver

```bash
cd vlogs/chatgpt-traffic
python chatgpt-traffic.py
```

### Repo-to-text Merge

```bash
cd vlogs/repo2text
python convert-repo-to-merged-text.py
```

### SafeShell (sau khi source)

```bash
saferm /path/to/file_or_directory
unrm /path/to/file_or_directory
removeitanyway /path/to/file_or_directory
```

## Ví dụ

- `code/EinkWordsGPT/demo.jpg`: ví dụ đầu ra e-ink.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/plain_transformer.ipynb`: ví dụ notebook.
- `examples/lazy-learning/BuildChachaGPTWithChatGPT/Prompts of ChachaGPT.pdf`: tài liệu tham chiếu prompt.
- `demos/`: các artefact hình ảnh dùng trong tài liệu dự án.

## Ghi chú phát triển

- Đây là repository kiểu umbrella legacy; tài liệu cấp module là nguồn đúng cho hành vi chạy chi tiết.
- Một số dự án liệt kê là repo GitHub ngoài; hãy dùng README của từng repo để cấu hình chi tiết.
- `EinkWordsGPT` phụ thuộc phần cứng (Raspberry Pi + màn hình Waveshare).
- Một số phụ thuộc ở mức module được khai báo ngoài repo và có thể khác thời điểm tài liệu.

### Giả định (rõ ràng)

- Repo gốc và các thư mục module lớn dùng **GNU GPL v3.0** nếu không có hướng dẫn `LICENSE` riêng.
- Các bước cài đặt module chưa được tập trung vì không có `requirements.txt`, `pyproject.toml`, hoặc `package.json` ở root.

## Khắc phục sự cố

- `ModuleNotFoundError: waveshare_epd`
  - Cài module e-paper Waveshare trên máy đích và xác nhận driver/phần cứng.
- OpenAI request lỗi xác thực
  - Kiểm tra `OPENAI_API_KEY` đã được export trong shell/session đang dùng.
- Không tìm thấy `words_phonetics.db`
  - Chạy script EinkWordsGPT từ `code/EinkWordsGPT` để đường dẫn tương đối được giải quyết đúng.
- `saferm`/`unrm` không khả dụng
  - Source lại profile shell sau khi thêm `safeshell_functions.sh`.
- `repo2text` không xuất đầu ra
  - Xác nhận `source_directory` tồn tại và chứa file `.py`.

## Lộ trình

- Chuẩn hóa tài liệu phụ thuộc module và thêm các đoạn cấu hình cụ thể theo module.
- Thêm task runner root tùy chọn (Makefile / entrypoint script) cho workflow module.
- Cải thiện tài liệu tái lập cho triển khai Raspberry Pi + Waveshare.
- Thêm test tự động cơ bản cho các script tiện ích.
- Tiếp tục mở rộng tính tương đương ngôn ngữ trong `i18n/`.

## Đóng góp cộng đồng

Chia sẻ cải tiến thực dụng, ý tưởng tự động hóa và thí nghiệm học ngôn ngữ:

- Template workflow cho công việc routine.
- Mẫu laziness thực tế giúp giảm chi phí bảo trì.
- Kết nối giữa module và sửa lỗi ở cấp script.

## Đóng góp

Mọi đóng góp đều được chào đón.

1. Fork repository.
2. Tạo nhánh feature (`git checkout -b feature/your-topic`).
3. Commit thay đổi (`git commit -m 'Add feature'`).
4. Đẩy nhánh và mở PR.

Nếu thay đổi của bạn theo module cụ thể, hãy cập nhật thêm README cục bộ của module đó.

## Kết nối

| Kênh | Liên kết |
|---|---|
| 🌐 Website | [lazying.art](https://lazying.art) |
| 🧑‍💻 GitHub | [lachlanchen](https://github.com/lachlanchen) |
| ✉️ Email | `lach@lazying.art` |

## Giấy phép

Repository này được cấp phép theo **GNU General Public License v3.0** (xem [LICENSE](LICENSE)).

Lưu ý:

- Root và các thư mục module lớn gồm các file `LICENSE` dùng GNU GPL.
- Nếu làm việc trong một thư mục con cụ thể, hãy dùng file `LICENSE` gần nhất để xác định phạm vi cấp phép.


## ❤️ Support

| Donate | PayPal | Stripe |
| --- | --- | --- |
| [![Donate](https://camo.githubusercontent.com/24a4914f0b42c6f435f9e101621f1e52535b02c225764b2f6cc99416926004b7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f6e6174652d4c617a79696e674172742d3045413545393f7374796c653d666f722d7468652d6261646765266c6f676f3d6b6f2d6669266c6f676f436f6c6f723d7768697465)](https://chat.lazying.art/donate) | [![PayPal](https://camo.githubusercontent.com/d0f57e8b016517a4b06961b24d0ca87d62fdba16e18bbdb6aba28e978dc0ea21/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f50617950616c2d526f6e677a686f754368656e2d3030343537433f7374796c653d666f722d7468652d6261646765266c6f676f3d70617970616c266c6f676f436f6c6f723d7768697465)](https://paypal.me/RongzhouChen) | [![Stripe](https://camo.githubusercontent.com/1152dfe04b6943afe3a8d2953676749603fb9f95e24088c92c97a01a897b4942/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5374726970652d446f6e6174652d3633354246463f7374796c653d666f722d7468652d6261646765266c6f676f3d737472697065266c6f676f436f6c6f723d7768697465)](https://buy.stripe.com/aFadR8gIaflgfQV6T4fw400) |
