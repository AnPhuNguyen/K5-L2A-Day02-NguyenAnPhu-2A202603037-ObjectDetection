# Mini guideline — bài làm cá nhân

> Điền nội dung này trước khi bắt đầu gán nhãn. Giữ lại các quyết định sau khi self-QC.

## Định nghĩa lớp

| Lớp | Định nghĩa của bạn | Ví dụ/điểm phân biệt |
| --- | --- | --- |
| `car` | Loại xe bốn bánh, kích cỡ nhỏ | xe con có cửa kính, mô tô không có và nhìn rõ người ở trên nếu có |
| `truck` | Loại xe bốn bánh, kích cỡ từ trung bình đến lớn | truck có một đầu cho buồng lái, nhìn rời rạc so với mọi phương tiện còn lại |
| `bus` | Loại xe bốn bánh, kích cỡ dài | thân hình dài nhất, có nhiều cửa sổ ở 2 bên xe |
| `van` | Loại xe bốn bánh, kích cỡ lớn hơn car nhưng nhỏ hơn truck | ví dụ, xe van, xe minivan |

## Quy tắc chung

- Box bám sát vật thể nghĩa là: vẽ một hình chữ nhật chứa vật thể càng sát đường biên ngoài thực tế của nó càng tốt, cùng với hạn chế phần gây nhiễu dưới nền
- Vật thể bị che khuất: vẫn gán nhãn nếu có thể chắc chắn từ 50% trở lên về đặc điểm vật thể
- Vật thể bị cắt bởi rìa ảnh: cạnh của box tại phía bị cắt sẽ dừng lại chính xác tại rìa của bức ảnh,
- Vật thể rất nhỏ/mơ hồ: bỏ qua nếu kích thước vật trên ảnh nhỏ hơn $20 \times 20$ pixels

## Ghi lại quyết định cho ít nhất ba ca mơ hồ

| Ảnh | Tình huống | Quyết định cuối | Lý do theo schema |
| --- | --- | --- | --- |
| `drive_002` | vài xe con ở bên trái làn đường ở vị trí rất xa | không gán nhãn | máy có thể không nhận ra đây là vật gì |
| `drive_018` | xe con màu trắng bị cắt bởi rìa ảnh, lại có người mặc áo vàng đi bên cạnh | gán nhãn 'car' | vẫn có đủ đặc điểm nhận dạng xe con |
| `drive_021` | một số xe bị khuất bởi bến dừng xe buýt | chỉ gán nhãn xe hiển thị không quá nhỏ trên ảnh | dựa vào đặc điểm nhận dạng của xe mà xác định xe bị khuất có gán nhãn hay không |
