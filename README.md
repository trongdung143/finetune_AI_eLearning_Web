# AI-Powered eLearning Fine-Tuning Platform

Nền tảng fine-tuning toàn diện cho các mô hình AI phục vụ hệ thống học tập trực tuyến. Dự án này tập trung vào việc tối ưu hóa các mô hình ngôn ngữ lớn (LLM) để cải thiện trải nghiệm học tập của người dùng.

## 🎯 Mục Tiêu Dự Án

- **Fine-tuning Mô hình**: Tối ưu hóa các mô hình AI cho các tác vụ học tập cụ thể
- **Hỗ trợ Toán học**: Chuyển đổi biểu thức toán học sang văn bản tự nhiên để giải thích dễ hiểu
- **Nền tảng Học tập**: Cung cấp các mô hình AI chất lượng cao cho nền tảng eLearning
- **Khả năng Mở rộng**: Hỗ trợ fine-tuning nhiều mô hình khác nhau

## 📁 Cấu Trúc Dự Án

```
finetune_AI_eLearning_Web/
├── README.md                              # Tài liệu dự án
├── math_to_nl/                            # Module chuyển đổi toán học → ngôn ngữ tự nhiên
│   ├── gemma_2_2b_math_to_nl.ipynb       # Notebook Jupyter cho training
│   ├── gemma_2_2b_math_to_nl.py          # Script Python chính
│   └── train_math_text_flexible.jsonl     # Dữ liệu huấn luyện (JSONL format)
```

## 🚀 Các Mô Hình Hiện Tại

### 1. Gemma 2 2B - Math to Natural Language
Mô hình chuyên biệt để giải thích biểu thức toán học bằng ngôn ngữ tự nhiên.

**Thông tin:**
- **Base Model**: Google Gemma 2 2B
- **Tác vụ**: Math Expression → Natural Language Explanation
- **Kích thước**: 2 Tỷ parameters
- **Format dữ liệu huấn luyện**: JSONL

**Ứng dụng:**
- Giải thích công thức toán học
- Hỗ trợ học sinh hiểu các khái niệm toán học
- Tạo bài tập và giải thích tự động

**Cập nhật lần cuối**: Tháng 1, 2026
