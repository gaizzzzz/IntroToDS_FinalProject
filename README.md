# Đồ án cuối kỳ môn Nhập môn khoa học dữ liệu
## Thông tin nhóm 5

| **STT** | **Họ và tên** | **MSSV** |
|-------|---------------|---------|
| 1     | Bùi Hồng Đăng   | 21120045|
| 2     | Nguyễn Tiến Nhật | 21120108|
| 3     | Thái Chí Vỹ      | 21120169|
| 4     | Bùi Đình Bảo     | 21120201|
  
---
# Tổng quan đề tài
Từ khi xuất hiện đến nay, phim được xem như là *môn nghệ thuật thứ 7* và được rất nhiều người ưa thích. Trong suốt quá trình phát triển của ngành công nghiệp phim ảnh, nó đã trải qua rất nhiều thăng trầm và có rất nhiều bộ phim chất lượng được sản xuất. Tuy nhiên, thị trường phim hiện nay khá là tệ vì đại dịch Covid-19 và các tranh cãi về đề tài phim kém chất lượng. Vì vậy, nhóm quyết định chọn đề tài phim điện ảnh để thực hiện đồ án.
---
# Cụ thể đồ án

**Chủ đề**: Nghiên cứu, tìm hiểu các bài toán liên quan đến phim điện ảnh và phân tích dữ liệu để giải quyết các bài toán đó; mô hình hóa dữ liệu để tìm ra mô hình hiệu suất cao nhất

**Nguồn dữ liệu**: https://www.themoviedb.org/movie/

**Ý tưởng**: Tiền xử lý dữ liệu sau khi crawl; đặt ra các câu hỏi có ý nghĩa và phân tích dữ liệu để giải đáp; mô hình hóa dữ liệu bằng các mô hình khác nhau trong việc dự đoán và phân loại để tìm ra mô hình tốt nhất

---
# Tổ chức GitHub
Sử dụng template của Lab 2 - môn Nhập môn Khoa học Dữ liệu.
```
├── README.md                                  <- The top-level README for developers using this project.
│
├── data
│   ├── movie.csv                              <- Data crawled from website.
│   ├── processed.csv                          <- Data after preprocessing.
│
├── notebooks                                  <- Jupyter notebooks.
│   ├── figures                                <- Contain plotly export.
│   │    ├── plot.html                         <- For question about Genre in eda.
│   │    ├── correlation_actual_predict.html   <- For model comparison in score prediction.
│   ├── 0.0-introduction.ipynb                 <- Unimportant!
│   ├── 0.1-introduction.ipynb                 <- Contain project and group information.
│   ├── 1.0-data-collecting.ipynb              <- Notebook for crawling data.
│   ├── 2.0-preprocessing.ipynb                <- Notebook for preprocessing.
│   ├── 3.0-eda.ipynb                          <- Notebook for exploratory data analysis.
│   ├── 4.0-data-modelling.ipynb               <- Notebook for data modelling.
│   ├── 5.0-reflection.ipynb                   <- Contain reflection information of our group and each team member.
│
├── submit                                     <- Folder for submitting Moodle.
│   ├── ...
│                     
├── ...                                        <- Other unimportant files and folders.
```

---
# Support links
## Trello 
> Thông tin phân chia công việc của nhóm:
> 
https://trello.com/invite/21_21intro2ds_g5_finalproject/ATTIf5ca31e2c424d3bdeb02c6716fd504b126CD83D9
## Canva 
> Slide vấn đáp:
> 
https://www.canva.com/design/DAF4pAMqYRY/TtnFOVx5M-9beJx_t60bEQ/edit?utm_content=DAF4pAMqYRY&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

---
# Tham khảo
- Các notebook demo và bài tập của thầy.
- Tài liệu tham khảo về phần mô hình hóa:
  - <https://www.spiceworks.com/tech/artificial-intelligence/articles/top-ml-algorithms/>
  - <https://medium.com/kernel-x/fine-tuning-machine-learning-models-using-scikit-learn-9e274782ef05>
