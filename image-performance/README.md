## Trang web sử dụng ít hình ảnh
### tối ưu sử dụng hình ảnh trên trang web?
1. Sử dụng hình ảnh phù hợp?
- Hình học vector: svg
- Bitmap tranparent: png
- Bitmap không tranparent: jpg, WEBP
2. Nén hình ảnh (giảm dung lượng)
- https://tinypng.com/
- https://compressor.io/
3. sử dung kich thước hình ảnh phù hợp
- Original: 4000px x 4000px, Figma: 800px x 800px, Resize: 1600px x 1600px (2x), đaps ứng tốt cho màn hình PPI/DPI cao (retina)
- PPI (Pixel Per Inch): số điểm ảnh trên một inch (2.54cm)
- DPI (Dot Per Inch): số điểm ảnh trên một inch (2.54cm) (100 DPI, 300 DPI)

- Loại màn hình:
1. Màn hình thường (DPI thấp - 1:1): 800px x 800px(ok), 1600px x 1600px (not ok)
2. Màn hình cao (DPI cao - 2:1): 800px x 800px(not ok), 1600px x 1600px (ok)

## Trang web sử dụng nhiều hình ảnh
    Thiết bị: 
    1. Mobile: 1600px x 1600px (not ok) -> TỐn băng thông, chờ lâu hơn=>  trải nghiệm kém
    2. tablet: 1600px x 1600px (not ok) -> 
    3. Desktop: 1600px x 1600px (ok)