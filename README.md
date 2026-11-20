> **Kho này đã chuyển.** Widget này nay nằm ở [nhatnguyet-widgets/xo-so](https://github.com/Nhat-Nguyet/nhatnguyet-widgets/tree/main/xo-so), cùng 13 widget khác. Kho này chỉ còn để lưu trữ.

# Kết quả xổ số

Kết quả xổ số ba miền và Vietlott kỳ mới nhất, tự cập nhật sau giờ quay mỗi ngày.

*[Read this in English](README.en.md)*

**Xem nó chạy thật:** https://nhatnguyet.org/widget/xo-so

## Dán hai dòng này là xong

```html
<div data-widget="xo-so"></div>
<script async src="https://nhatnguyet.org/embed/w.js"></script>
```

Không cần tài khoản, không cần khoá API, không mất phí.

## Nó giúp gì cho trang của bạn

Kết quả kỳ mới nhất của ba miền và Vietlott, bốn kiểu: theo loại, tự chuyển qua các loại, tổng hợp mọi giải Đặc biệt và Jackpot, hay bảng đủ giải. Widget tự lấy kết quả mới sau giờ quay mỗi ngày, anh chị không phải cập nhật tay.

## Vài điều nên biết trước

- Chỉ có kết quả đã công bố: giải Đặc biệt và các giải chính của ba miền, bộ số và giá trị Jackpot của Vietlott.
- Không thống kê, không dự đoán, không gợi số.
- Muốn xem đủ bảng và dò vé, người đọc bấm sang trang tra cứu của Nhật Nguyệt.

## Các bước

1. Dán mã nhúng vào cột bên hay cuối bài viết.
2. Chọn kiểu bằng data-kieu: tab (theo loại), xoay (tự chuyển), tong-hop (tổng hợp) hay bang (bảng đủ giải).
3. Đặt data-loai là mien-bac, mien-trung, mien-nam, mega-6-45 hay power-6-55 để chọn loại mở sẵn.
4. Chọn sáng hay tối cho hợp với trang của anh chị ngay ở khung xem thử.

## Dán vào đâu

**WordPress.** Thêm một khối *HTML tuỳ chỉnh* vào bài hoặc vào widget
*Text* ở cột bên, rồi dán cả hai dòng vào đó. Đừng dán vào trình soạn thảo
thường: nó sẽ hiện ra đúng chữ mã thay vì chạy mã.

**Wix, Squarespace, Haravan, Shopify.** Dùng khối *Nhúng mã HTML* (Embed
HTML / Custom HTML) rồi dán vào.

**Site tự viết.** Dán thẳng vào chỗ bạn muốn widget xuất hiện. Dòng
`<script>` có thể để chung một chỗ nếu bạn nhúng nhiều widget, nó chỉ cần
xuất hiện một lần trên trang.

**Ghi chú về chiều rộng.** Widget tự co theo bề ngang chỗ bạn đặt nó. Nếu chỗ ấy hẹp dưới 280px thì thêm `data-size="compact"`;
nếu là một dải ngang rộng thì `data-size="wide"`.

## Chỉnh cho hợp trang của bạn

| Thuộc tính | Giá trị | Ý nghĩa |
|---|---|---|
| `data-widget` | `xo-so` | Bắt buộc |
| `data-theme` | light hoặc dark | Mặc định light |
| `data-accent` | #b5402f | Màu nhấn dạng hex 6 ký tự, để khớp bộ nhận diện của anh chị |
| `data-lang` | vi, en hoặc zh | Mặc định vi |
| `data-size` | compact, standard hoặc wide | Mức chi tiết theo bề ngang khung: compact bỏ bớt chi tiết phụ, wide trải ngang. Mặc định standard |
| `data-kieu` | tab, xoay, tong-hop hoặc bang | Kiểu trình bày của widget kết quả xổ số: theo loại, tự chuyển, tổng hợp hay bảng đủ giải |
| `data-loai` | mien-bac, mien-trung, mien-nam, mega-6-45 hoặc power-6-55 | Tab mở sẵn của widget kết quả xổ số, mặc định Miền Bắc |

Đặt hết mọi thứ widget này nhận thì trông như sau:

```html
<div data-widget="xo-so" data-theme="dark" data-accent="#1f6f5c" data-size="compact"></div>
<script async src="https://nhatnguyet.org/embed/w.js"></script>
```

Muốn xem tận mắt trước khi dán lên trang thật thì mở
[`vi-du/index.html`](vi-du/index.html) bằng trình duyệt, không cần cài gì.

## Vài điều xin thưa trước

- Miễn phí cho website cá nhân và doanh nghiệp, không giới hạn lượt hiển thị.
- Giữ nguyên dòng ghi nguồn ở đáy widget. Đây là điều kiện đổi lại việc dùng
  miễn phí.
- Không nhúng trên trang cờ bạc, nội dung người lớn, lừa đảo hoặc vi phạm
  pháp luật Việt Nam.
- Nội dung là tri thức dân gian và quy ước văn hoá, để tham khảo, không phải
  lời khuyên về sức khoẻ, tài chính hay pháp lý.

Bản đầy đủ: [`DIEU-KHOAN.md`](DIEU-KHOAN.md) · [https://nhatnguyet.org/widget/dieu-khoan](https://nhatnguyet.org/widget/dieu-khoan)

## Nhật Nguyệt là ai

Nhật Nguyệt (https://nhatnguyet.org) là trang tra cứu lịch pháp và văn hoá tâm linh Việt
Nam: lịch âm tính theo múi giờ nước mình, can chi, tiết khí, giờ hoàng đạo,
tử vi, phong thuỷ, và một từ điển thuật ngữ.

Có một điều chúng tôi cố giữ cho bằng được, kể cả trong một khung widget
300px: nói rõ đâu là thứ tính ra được, đâu là quan niệm dân gian.

Ngày âm lịch, can chi, tiết khí là **tính ra được**: ai chạy cùng phép tính
cũng ra cùng kết quả, và chúng tôi công bố luôn bộ dữ liệu gốc theo giấy
phép CC BY 4.0 để bạn tự đối chiếu.

Giờ hoàng đạo, cung Bát Trạch, cung thước Lỗ Ban là **quy ước văn hoá**: có
bảng tra hẳn hoi, nhưng không phải phép đo. Widget cho bạn biết bảng nói gì,
còn tin tới đâu là việc của mỗi người.

Chỗ nào các phái không thống nhất, chúng tôi nói ra chỗ ấy, thay vì lặng lẽ
chọn một bên rồi trình bày như thể chỉ có một cách.

Dữ liệu mở: [GitHub](https://github.com/Nhat-Nguyet/du-lieu-am-lich) ·
[Hugging Face](https://huggingface.co/datasets/nhatnguyet)

## Thấy gì chưa ổn?

Mở một issue ngay trong kho này. Chúng tôi có đọc.

Toàn bộ thư viện widget: [https://nhatnguyet.org/widget](https://nhatnguyet.org/widget)
