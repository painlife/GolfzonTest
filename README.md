# Golfzon R&D Center Android Assignment

[Tiếng Việt](README.md) | [한국어](README-ko.md)

### Cách gửi bài kiểm tra
- `Thời gian: 3 ngày (72 giờ)`
- `Hãy đừng fork.`
- `Hãy clone, tạo git respository cá nhân và thực hiện commit.`
- `Đối với việc gửi bản final thì hãy nén Project lại và gửi kèm theo cả thông tin respository tương ứng.`



### Nội dung bài kiểm tra

Hãy tạo Android app đáp ứng các yêu cầu như sau và sử dụng danh sách ảnh từ API.

```
1. Project cần phải được tạo thành từ multi module (tối thiểu từ 1 cái trở lên ngoài App module)

2. UI sử dụng 2 fragment.

3. Sử dụng Bottom Tab rồi chuyển đổi fragment.

4. fragment thứ nhất (LIST)
  * Hãy show danh sách ảnh theo hình thức Grid (column 3).
  * Thông qua scroll và gọi ảnh của page khác. 
    (Bạn hãy cố gắng làm sao để thực hiện scroll thật tự nhiên nhất có thể)
  * 1 ảnh được hiển thị theo hình vuông.
    (CenterCrop ảnh) 
  * Hãy hiển thị nội dung sau đây trên ảnh
    - Image ID (id nhận được trên API)
    - Ảnh dã được thêm Favorite thì hiển thị icon đã được thêm.
      (Ví dụ như Like/hình ngôi sao/hình trái tim v.v...)
  * Nếu chọn (touch) ảnh thì nó sẽ được thêm vào Favorite.
  * Đối với trường hợp nếu chọn (touch) lại vào ảnh đã được thêm thì nó sẽ được bỏ khỏi Favorite.

5. fragment thứ hai (FAVORITE)
  * Hãy show danh sách ảnh được thêm vào favorite trên màn hình.
  * Nội dung yêu cầu tương tự với fragment thứ nhất.
  * Nội dung đã được thêm ở Favorite cần phải được show kể cả sau khi restart lại app.
    (Sử dụng Room, DataStore, SharedPreferences v.v... một cách chọn lọc)

6. Đối với API thì bạn hãy nhận apikey từ Free plan ở (https://thedogapi.com/) và áp dụng.

7. Hãy tham khảo keyword sau đây và tạo nên project.
   (Không phải tất cả các yếu tố đều là bắt buộc.)
  * MVVM
  * Flow
  * Coroutine
  * Retrofit2
  * Glide
  * Paging3
```

Nội dung yêu cầu phát triển bổ sung

```
1. Trường hợp long click vào gridItem thì di chuyển tới page chi tiết. (Activity mới)
2. Show ảnh đã được chọn.
3. Hãy hiển thị thông tin nhận được từ API ở bên trái, ở dưới.
4. Hãy hiển thị favorite icon ở trên cùng bên phải
   (phân biệt rõ cái được chọn và cái không được chọn)
5. Nếu touch favorite icon thì cần phải thực hiện được hành động thêm và hủy thêm vào Favorite.
6. Khi swipe ảnh thì cần phải di chuyển tới ảnh trước và ảnh sau.
7. Trường hợp cần paging thì hãy request page sau thông qua API.
```

