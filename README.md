# Từ điển Anh-Việt tổng hợp cho Kindle, Kobo, KOReader, StarDict...

🇻🇳  [Cài đặt giao diện tiếng Việt và sửa lỗi hiển thị tiếng Việt cho Kobo](https://sachxy.github.io)

## Thông tin
- **Dữ liệu:**
  - Lạc Việt
  - TFlat
  - DictBox
  - Babylon
  - Laban
- **Số từ:** hơn 170,000 từ  
- Tích hợp từ điển Kỹ thuật
- Trình bày đẹp, tối ưu cho máy đọc sách
- Hỗ trợ tra cứu các biến thể của từ. Vd: tra cứu `remembered` sẽ ra `remember`.
- Hiển thị kèm các từ liên quan. Vd: hiển thị nghĩa của `cook` khi đang tra `cooking`.

> [!NOTE]
> Vì từ điển được tổng hợp từ nhiều nguồn nên khả năng bị lặp nghĩa là không thể tránh khỏi. Nếu bạn thấy có vấn đề về nghĩa, vui lòng tạo Issue mới hoặc liên hệ fb: [fb.me/getsachxy](https://fb.me/sachxycom).

<img height="600" src="https://github.com/user-attachments/assets/75e1938e-adff-45b0-ba84-ff26437a044d" />

## Cài đặt cho máy đọc sách Kindle
1. Tải file `tudien-kindle-en-vi.mobi` trong mục [Releases](https://github.com/redphx/tudien/releases/latest)   
2. Kết nối Kindle với máy tính/điện thoại qua cổng USB  
3. Chép file vừa tải vào thư mục: `documents/dictionaries/` (xóa file từ điển cũ nếu cần)  
4. Dùng chức năng `Tháo/Eject USB` trên máy tính để tránh mất dữ liệu  
5. Có thể sẽ cần phải khởi động lại máy  

## Cài đặt cho máy đọc sách Kobo
1. Cài đặt [Kobo tiếng Việt](https://github.com/redphx/kobo-tieng-viet) để máy hỗ trợ từ điển Tiếng Việt (chỉ cần làm cho lần đầu cài đặt)  
2. Tải file `tudien-kobo-en-vi.zip` trong mục [Releases](https://github.com/redphx/tudien/releases/latest)  
3. Kết nối Kobo với máy tính/điện thoại qua cổng USB  
4. Chép file vừa tải vào thư mục: `.kobo/custom-dict` (để nguyên, không giải nén)  
5. Sửa tên file thành `dicthtml-en-vi.zip` (không phải `dicthtml-en-vi.zip.zip`, xóa file từ điển cũ nếu cần)  
6. Dùng chức năng `Tháo/Eject USB` trên máy tính để tránh mất dữ liệu  

## Cài đặt cho KOReader
1. Tải file `tudien-stardict-en-vi.zip` trong mục [Releases](https://github.com/redphx/tudien/releases/latest)  
2. Kết nối Kobo/Kindle với máy tính/điện thoại qua cổng USB
3. Giải nén nội dung file vừa tải vào thư mục (tạo mới nếu chưa có sẵn):  
  - Kindle: thư mục `koreader/data/dict/tudien-en-vi`  
  - Kobo: thư mục `.adds/koreader/data/dict/tudien-en-vi`  
  Nếu làm đúng, trong thư mục `dict/tudien-en-vi/` sẽ có 3 file cùng tên với đuôi `.dict.dz`, `.idx` và `.ifo` (không có thư mục con)
  ```
.../
├─ dict/
│  ├─ tudien-en-vi/
│  │  ├─ tudien.dict.dz
│  │  ├─ tudien.idx
│  │  ├─ tudien.ifo
  ```

4. Dùng chức năng `Tháo/Eject USB` trên máy tính để tránh mất dữ liệu  

Xem [trang này](https://github.com/koreader/koreader/wiki/Dictionary-support) để xem cách cài đặt từ điển cho KOReader trên các hệ máy khác.

## Cài đặt cho Xteink, Crosspoint, Crossink...

Bạn có thể dùng từ điển bản Stardict cho Xteink, Crosspoint, Crossink... Vui lòng tra cứu cách cài từ điển tùy theo firmware đang sử dụng.  
  
⚠️ Lưu ý: phiên bản từ điển hiện tại chưa được tối ưu cho máy đọc sách mini. Mình đang tìm các bạn đang sử dụng Xteink X4 Pro để giúp mình tạo bản mới cho các máy/firmware này. Có thể nhắn tin FB mình tại [fb.me/sachxycom](fb.me/sachxycom)


## Cài đặt cho máy đọc sách Boox

1. Tải file `tudien-stardict-en-vi.zip` trong mục [Releases](https://github.com/redphx/tudien/releases/latest)  
2. Xem [hướng dẫn](https://youtu.be/6YUC9jct6QA?t=32) để biết cách cài đặt

## Cập nhật
Nếu muốn cập nhật phiên bản mới của thư viện chỉ cần làm lại các bước như lúc cài đặt, nhưng khuyến khích xóa phiên bản cũ (xóa file) trong máy trước để tránh bị lỗi.  

## TODO
- [ ] Chia sẻ mã nguồn tạo từ điển  
- [ ] Thêm nội dung Grammar (các thì của một từ)  
- [ ] Thêm mẫu câu  
- [ ] Tích hợp từ điển Việt-Anh  
- [x] Tích hợp từ điển Kỹ thuật  
  
### Nếu phát hiện lỗi gì vui lòng tạo issue để được hỗ trợ.  
