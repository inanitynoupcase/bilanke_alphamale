# Hướng dẫn tối ưu hóa điểm Binance Alpha

## Giới thiệu về Binance Alpha Points

Binance Alpha Points là hệ thống điểm đánh giá hoạt động của người dùng trong hệ sinh thái Binance Alpha và Binance Wallet. Điểm số này xác định tính đủ điều kiện của bạn cho các chiến dịch như tham gia Token Generation Event (TGE) và nhận airdrop token Alpha.

## Cách tính điểm

Điểm Alpha Points được tính hàng ngày dựa trên tổng số dư tài sản và khối lượng mua token Alpha trên sàn Binance và Binance Wallet (địa chỉ Keyless).

**Lưu ý:** Việc bán token Alpha không ảnh hưởng đến điểm Alpha Points ở giai đoạn hiện tại.

Điểm Alpha Points là tổng tích lũy của điểm hàng ngày kết hợp giữa Điểm Số dư (Balance Points) và Điểm Khối lượng (Volume Points) trong 15 ngày qua.

**Thời gian cập nhật:** Dữ liệu của ngày trước sẽ được cập nhật trước 6 giờ sáng UTC của ngày hiện tại.

## Chiến lược tối ưu hóa điểm

### Phương pháp tối ưu điểm (Tài khoản nhỏ / Nhiều tài khoản)

#### Chiến lược cơ bản:
| Hoạt động | Điểm tích lũy hàng ngày | Chi phí | Tổng 15 ngày |
|---------|-------------------|--------|------------|
| Nắm giữ ≥ $100 | 1 điểm | Chi phí một lần $100 | 15 điểm |
| Mua $8 Alpha mỗi ngày | 3 điểm | $8 mỗi ngày | 45 điểm |
| **Tổng cộng** | **4 điểm** | **Tỷ lệ hiệu quả cao** | **60 điểm** |

*Mua $8 SOL Alpha tương đương 3 điểm, thực tế tối thiểu chỉ khoảng $7.93, phí giao dịch khoảng 0.75%*

### Chiến lược kết hợp theo quy mô tài khoản:
| Loại người dùng | Chiến lược | Chi phí hàng ngày | Điểm hàng ngày | Tổng 15 ngày |
|--------------|----------|------------|-----------|------------|
| Tài khoản nhỏ | Nắm giữ $100 + Giao dịch $8 mỗi ngày | ~$8 | 4 điểm | 60 điểm |
| Tài khoản trung bình | Nắm giữ $1,000 + Giao dịch $16 mỗi ngày | ~$16 | 6 điểm | 90 điểm |
| Tài khoản lớn | Nắm giữ $100,000 + Giao dịch $512 | ~$512+ | 13 điểm | 195 điểm |

### Chiến lược tối đa hóa điểm:
| Hạng mục | Hoạt động | Điểm/ngày | Tổng 15 ngày |
|---------|---------|----------|------------|
| Số dư nắm giữ | Nắm giữ 100,000+ USDT | 4 | 60 |
| Khối lượng giao dịch | Giao dịch $512 Alpha mỗi ngày | 9 | 135 |
| **Tổng cộng** | | **13** | **195** |

*Lưu ý: $512 là mức giao dịch mục tiêu, không có lợi ích khi tăng gấp đôi. Càng mua nhiều, càng nhận được nhiều điểm.*

### Bảng tính điểm theo khối lượng giao dịch cao (tham khảo):
| Công thức | Giá trị | Điểm |
|---------|-------|-----|
| 2² × 2⁹ | $1,024 | 10 điểm |
| 2² × 2¹⁰ | $2,048 | 11 điểm |
| 2² × 2¹¹ | $4,096 | 12 điểm |
| 2² × 2¹² | $8,192 | 13 điểm |
| 2² × 2¹³ | $16,384 | 14 điểm |
| 2² × 2¹⁴ | $32,768 | 15 điểm |
| ...tiếp tục nhân đôi | | không giới hạn trên |

## Quy tắc tính điểm

### Quy tắc Điểm Số dư (Balance Points)
Số dư tài sản Spot và token Alpha trên sàn Binance và Binance Wallet (Địa chỉ Keyless):
- $100 đến <$1,000 = 1 điểm/ngày
- $1,000 đến <$10,000 = 2 điểm/ngày
- $10,000 đến <$100,000 = 3 điểm/ngày
- ≥$100,000 = 4 điểm/ngày

### Quy tắc Điểm Khối lượng (Volume Points)
Mua token Alpha trên sàn Binance và/hoặc Binance Wallet:
- 1 điểm cho $2 đầu tiên
- +1 điểm cho mỗi lần nhân đôi (ví dụ: $4 = 2 điểm, $8 = 3 điểm)

| Giá trị mua | Điểm |
|------------|-----|
| $2 | 1 điểm |
| $4 | 2 điểm |
| $8 | 3 điểm |
| $16 | 4 điểm |
| $32 | 5 điểm |
| $64 | 6 điểm |
| $128 | 7 điểm |
| $256 | 8 điểm |
| $512 | 9 điểm |
| ...và tiếp tục tăng |

## Câu hỏi thường gặp

1. **Tôi có thể chia $100,000 thành nhiều tài khoản phụ để kiếm nhiều điểm hơn không?**
   - Chỉ tài khoản chính mới đủ điều kiện nhận điểm Alpha. Số dư tài khoản phụ được hợp nhất vào điểm của tài khoản chính. Không được phép chia số dư trên nhiều tài khoản riêng biệt để kiếm thêm điểm.

2. **Tỷ giá nào được sử dụng để tính số dư và/hoặc giá trị giao dịch của tôi?**
   - Giá trị token Alpha được đo bằng giá trị tương đương USD theo giá thị trường tại thời điểm giao dịch. Điều này đảm bảo theo dõi điểm công bằng và nhất quán.

3. **Nếu tôi mua token trị giá $600 và sau đó bán $500. Tôi có vẫn nhận được Điểm Khối lượng cho $600 không?**
   - Có. Cơ chế mua token theo dõi khối lượng mua của bạn, không phải số dư hiện tại. Vì vậy, bạn sẽ được ghi công cho toàn bộ số token Alpha trị giá $600 mà bạn đã mua, ngay cả khi sau đó bạn bán một số.
