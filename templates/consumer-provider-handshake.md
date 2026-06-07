# Consumer–Provider Handshake

## Thông tin chung

- Lab: FIT4110 Lab 03
- Ngày: 07/06/2026
- Provider team: Nguyễn Đình Huy, Nguyễn Phạm Hồng Lâm, Vũ Việt Long
- Consumer team: Hoàng Văn Thi, Đoàn Duy Mạnh, Lương Quang Huy
- Provider service: Multi-Channel Alert Service API (Notification Service)
- Consumer service: IoT Ingestion Service / AI Vision Core
## Contract

- Contract file: contracts/notification-service.openapi.yaml
- Mock base URL: http://localhost:4011
- Auth method: Bearer Token (Authorization Header)
- Endpoint được test: /health, /readings, /readings/latest, /detect

## Smoke test

### Request

```http
METHOD /path
Authorization: Bearer <token>
Content-Type: application/json
```

```json
{
}
```

### Expected response

```json
{
}
```

## Kết quả

- [ ] Consumer gọi mock thành công.
- [ ] Consumer parse được field cần dùng.
- [ ] Consumer hiểu lỗi 4xx/5xx provider trả về.
- [ ] Có Newman report hoặc screenshot.

## Ghi chú thay đổi hợp đồng

| Nội dung | Trước | Sau | Người đồng ý |
|---|---|---|---|
| | | | |

## Xác nhận

- Provider representative:
- Consumer representative:
