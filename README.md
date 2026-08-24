# Pawora – Smart Pet Care Dropshipping Store

Cửa hàng dropshipping phụ kiện thú cưng thông minh.

**Cấu trúc đơn giản (không dùng thư mục src)** – dễ upload trên điện thoại.

## Cách chạy

```bash
npm install
npm run dev
```

Mở http://localhost:3000

## Deploy lên Vercel

1. Upload toàn bộ file lên GitHub (các thư mục app, components, data, lib, store phải nằm ở ngoài cùng)
2. Vào vercel.com → Import project → Deploy

## Cấu trúc thư mục

```
/
├── app/                 ← Trang chủ, sản phẩm, giỏ hàng, checkout
├── components/          ← Header, Footer, ProductCard
├── data/                ← Dữ liệu sản phẩm
├── lib/                 ← Tiện ích + CJ API
├── store/               ← Giỏ hàng
├── package.json
├── next.config.ts
├── tailwind.config.ts
└── tsconfig.json
```

## Kết nối CJ Dropshipping

Xem file `lib/cj-api.ts` và hướng dẫn trong các phiên chat trước.
