# Chuyển đổi CSS có sẵn sang SASS theo chuẩn

Bài thực hành tổ chức SCSS theo các thư mục:
- `abstracts`: variables và mixins
- `base`: style toàn cục
- `layout`: bố cục
- `components`: button và card
- `main.scss`: import các partials

## Biên dịch
Nếu đã cài Sass, chạy:

```bash
sass scss/main.scss css/styles.css
```

Chế độ watch:

```bash
sass scss/main.scss css/styles.css --watch
```

Sau đó mở `index.html` bằng Live Server.
