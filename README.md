# Cách viết file Markdown (README.md)
- [Cách viết file Markdown (README.md)](#cách-viết-file-markdown-readmemd)
  - [Giới thiệu](#giới-thiệu)
  - [Các phương pháp thường dùng trong markdown](#các-phương-pháp-thường-dùng-trong-markdown)
    - [Formating](#formating)
      - [Bằng cách dùng dấu # để tạo thành các heading.](#bằng-cách-dùng-dấu--để-tạo-thành-các-heading)
      - [Fonts](#fonts)
      - [Quotation](#quotation)
      - [Tạo bảng](#tạo-bảng)
      - [Code Block](#code-block)
      - [Gạch ngang](#gạch-ngang)
      - [Chèn link](#chèn-link)
      - [Hình ảnh](#hình-ảnh)
      - [Vẽ biểu đồ](#vẽ-biểu-đồ)
      - [Import file](#import-file)
      - [Math](#math)
      - [Đánh số tự động](#đánh-số-tự-động)
      - [Tạo mục lục](#tạo-mục-lục)

## Giới thiệu
- Đây là file lưu trữ cách viết tài liệu markdown (*.md)
- Tiện ích cần tải trên VScode để giúp việc đánh tài liệu Markdown được nhanh hơn
1. Markdown All in One
2. Markdown Preview Enhance
>Cách gõ tiếng Việt trong Markdown: Search >Preferences: Open Keyboard Shortcuts --> markdown.extension.onBackspaceKey --> Delete.
>Backspace 2 lần để xuống dòng
## Các phương pháp thường dùng trong markdown
### Formating
#### Bằng cách dùng dấu # để tạo thành các heading.
#### Fonts
- Bôi đậm dùng **bold**
- In nghiêng dùng *Italic* hoặc _Italic_
- Gạch bỏ dùng ~~delete~~
- Giữ lại ký tự đặc biệt dùng \ (\*\*Vidu\*\*)

#### Quotation
Dùng dấu >
> Đây là Quote

Dùng dấu \` để nhấn mạnh chữ trong câu `vidu`

#### Tạo bảng
Dưới đây là cách tạo bảng, dấu : dùng để canh lề
| STT  |   A1 | A2   |
| :--- | ---: | :--- |
| B    |  B11 | B21  |
| C    |  C11 | C21  |

Format bảng bằng `>Format Document`
Tạo bảng nhanh nhờ Extension
Tìm kiếm: `>markdown preview enhanced: Insert Table`

|     |     |
| --- | --- |
|     |     |

#### Code Block
```c
void main
{
printf('hướng dẫn');
}
```

Có thể tạo code block bằng tab
    
    code block

#### Gạch ngang
Dùng 3 dấu - hoặc *

---
***

#### Chèn link
Có thể chèn link băng dấu ngoặc vuông và tròn như sau:
[Google](www.google.com)
Có thể dùng format cho link
Cách viết chuyên nghiệp hơn. Đây là [Link1][1] và đây là [Link2][2]. Cách 1 dòng trống

[1]: <www.google.com>
[2]: <www.youtube.com>

#### Hình ảnh
Để chèn ảnh trong vscode cần ảnh để cùng folfer hoặc có thể upload ảnh lên imgur.com và lấy link chèn vào
![Imgur](https://imgur.com/GZL4iPM.png)  
Nhớ thêm đuôi .png vào cuối

#### Vẽ biểu đồ
Dùng [mermaid](https://mermaid-js.github.io/mermaid/#/) Hoặc PlanUML

#### Import file
Dùng @import "file"

#### Math
Để viết công thức toán cần đặt giữa 2 dấu \$
$\alpha$
$x^2$
$x_{2n}$
$H_2SO_4$
$\to$
$\infty$
$\frac{1}{2n}$
$\sqrt[n]{k}$
Trang tạo code cho toán học: <https://www.latex4technics.com/>

#### Đánh số tự động
Tìm kiếm: >markdown: add and update section number

#### Tạo mục lục
Tìm kiếm: >markdown: create table of content
