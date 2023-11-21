# HTML

- attributes: thuộc tính
- _div_: là thẻ `block`, thường dùng để bao 1 khối chưa nhiều phần tử, đây là thẻ thông dụng nhất và được dùng nhiều nhất
- _p_: là thẻ `block`, thường dùng để hiển thị văn bản, có nhiều chữ và thường là các chữ nhỏ
- _a_: là thẻ `inline`, thường dùng để cho mục đích là liên kết, có `href` là thuộc tính để điền vào đường dẫn, muốn nhấn vào mở tab mới thì thêm thuộc tính `target="\_blank"`, nếu sử dụng target là \_blank thì nên thêm thuộc tính `rel="noopener norefferer"`
- _header_: thường dùng cho các khối ở trên
- _footer_: thường dùng cho khối dưới cùng của trang
- _main_: là phần chính của trang
- _article_: thẻ block, thường dùng cho các giao diện dạng bài viết
- _aside_: thẻ block, thường dùng cho các giao diện sidebar
- _span_: là thẻ inline, thường dùng cho các đoạn chữ ngắn
- _strong_, _b_: là thẻ inline, chức năng tương tự thẻ span, nhưng nó khác ở chỗ là làm cho chữ in đậm
- _em_, _i_: là thẻ inline, chức năng tương tự span, nhưng làm cho chữ in nghiêng
- h1->h6: thẻ block, nó dùng cho các tiêu đề từ lớn đến nhỏ
- _h1_: trong 1 trang chỉ có tối đa 1 thẻ h1 mà thôi vì nó liên quan tới SEO
- _h2_: thường đại diện cho 1 khối lớn
- _h3_: đại diện cho khối nhỏ hơn
- _h4_: tiêu đề nhỏ
- _img_: là thẻ inline, dùng để hiển thị hình ảnh, `src` là để truyền vào đường dẫn hình ảnh, đường dẫn hình có thể lấy từ thư mục đang làm hoặc là hình ảnh online, `alt`(alternate text) mô tả tên tấm ảnh(liên quan tới SEO), là thẻ tự đóng
- _br_: xuống hàng mới, là thẻ tự đóng
- _hr_: sẽ tạo ra đường kẻ ngang, là thẻ tự đóng
- _ul_: thường dùng để hiển thị danh sách không có thứ tự(ko có đánh số)
- _ol_: thường hiển thị danh sách có đánh số
- thẻ đóng mở có thể chứa các thẻ khác,
- thẻ div có thể chứa thẻ div, thẻ div chứa hầu hết các thẻ khác đều được
- thẻ a không nên chứa thẻ a
- thẻ tự đóng là thẻ không có children(con): img, br, hr
- thẻ p không chứa được thẻ div, thẻ p(chính nó)
- _class_ là thuộc tính dùng cho các thẻ, mục đích của nó là để styling trong CSS, hoặc truy vấn trong Javascript, class có thể trùng nhau, class có nhiều cách đặt tên, thông thường hay gặp là BEM(Block\_\_Element--Modifier)
- _id_ là thuộc tính dùng cho các thẻ, id là duy nhất cho nên ko được trùng nhau, cũng dùng cho truy vấn trong Javascript
- vấn đề đặt tên không được tốt là do thiếu vốn từ tiếng Anh
- Naming convention: tên ngắn gọn, dễ hiểu, không dấu, không có khoảng trắng. 1 ví dụ tốt: header, header-item, button, button--primary
- 2 dấu -- gọi là modifier nghĩa là tùy biến của một thành phần
- Block\_\_Element--modifier
- Block: header
- Element: search, user, noti, message, button
- Modifier: header big, header small, search long, search gray, user rounded, user round, noti small, message active, message unactive, button big, button primary, button secondary
- BEM: header--big, header--small, search--gray, buttoon--primary, button--secondary, header\_\_button--primary
- evondev way: buton--primary, button, header-button
- Từ tiếng Anh hay gặp: danh sách(list)
- phần tử(item)
- tiêu đề(title
- heading)
- nội dung(content)
- chữ(text)
- hình ảnh(image
- img
- avatar)
- liên kết(link
- url)
- đường dẫn(url
- src)
- thông tin(info)
- thời gian(time)
- khối(box
- boxed)
- viền(border
- line)
- trạng thái(status)
- kích hoạt(active/unactive)
- xóa(delete
- remove)
- cập nhật(update) thêm(new
- create)
- sửa(edit
- change)
- biểu tượng(icon)
- đánh giá(review
- rating)
- thích(like
- love)
- đánh dấu(saved
- bookmark)
- tab
- slider
- progress
- slider bullet
- tìm kiếm(search)
- dropdown(danh sách sổ xuống)
- lớp phủ(overlay)
- ...

# Gõ nhanh HTML trong VSCode

- Settings: Trigger expandsion on Tab: checked
- class: dấu chấm(.)
- dấu + tạo nhiều thành phần liền kề nhau
- dấu > để tạo ra thành phần là thành phần con
- dấu \* để tạo ra số lượng mà mình muốn
- dấu {item $} nó sẽ tạo ra chữ đánh số nếu mình dùng dấu \* ở trên
- Khi gõ emmet HTML thì không nên có khoảng trắng
- dấu ^ nghĩa là cùng cấp, dùng trong trường hợp đã đi sâu vào phần tử của phần tử trước đó
- dấu [] dành cho việc các thuộc tính khác ngoài class và id

# CSS

- Thẻ block: là thẻ có độ rộng 100% thằng chứa nó( chưa áp dụng CSS), khi các thẻ block nằm với nhau thì nó sẽ rớt xuống và tạo hàng mới
- Thẻ inline: là thẻ có độ rộng bằng với nội dung nó chứa, khi các thẻ inline nằm với nhau thì nó sẽ nằm cạnh nhau, hạn chế 1 vài thuộc tính CSS
- Thẻ inline-block: nó sẽ có độ rộng bằng với nội dung nó chứa, nó không bị hạn chế về CSS, khi nằm với nhau thì không bị rớt xuống hàng, có 1 khoảng trống tầm 4px ở giữa
- display: inline, block, inline-block
- ./: cùng cấp
- ../: truy xuất ở trong ra ngoài
- user agent stylesheet: CSS mặc định của trình duyệt
- \*: là selector chọn toàn bộ các thẻ trong HTML
- _selectors_:
- tags(h1, header, div, p, span, a, img..)
- class: .heading, .button, .section--primary
- id: #header, #main, #container, #footer
- attributes: href, src, rel, target, arial-label, placeholder, type, name, disabled, alt...
- đối với các thuộc tính ngoài class và id thì dùng dấu []
- [alt="evondev-image"] -> chọn toàn bộ các thẻ có thuộc tính alt là "evondev-image"
- img[alt="evondev-image"] -> chọn toàn bộ thẻ `img` có thuộc tính alt là "evondev-image"
- dấu = nghĩa là chính xác tuyệt đối
- dấu ^ nghĩa là bắt đầu với
- a[href^="https"] -> chọn toàn bộ các thẻ a có thuộc tính href `bắt đầu` bằng chữ https
- a[href$=".com"] -> chọn toàn bộ các thẻ a có thuộc tính href `kết thúc` bằng chữ .com
- a[href*="com"] -> chọn toàn bộ các thẻ a có thuộc tính href `có chứa` chữ .com
- a[lang|="en"] -> chọn toàn bộ các thẻ a có thuộc tính lang là chữ `en` hoặc bắt đầu với chữ `en-`

# CSS cơ bản

- color: đổi màu chữ
- line-height: khoảng cách giữa các dòng chữ
- word-break: phù hợp cho những đoạn chữ dài dính nhau, làm cho nó tự ngắt xuống dòng
- white-space: nowrap làm cho chữ luôn nằm trên 1 hàng
- letter-spacing: khoảng cách giữa các kí tự
- word-spacing: khoảng cách giữa các từ
- text-align: căn lề cho chữ
- text-decoration: gạch cho chữ, giữa, trên và dưới
- text-indent: di chuyển chữ vào trong hoặc ra ngoài
- serif: chữ có gạch chân
- sans-serif: chữ không có gạch chân
- baseline: đáy chữ
- overflow: hidden -> nếu nội dung bị tràn thì sẽ bị cắt mất đi
- text-overflow: ellipse -> nếu kết hợp overflow hidden thì nó sẽ hiển thị dấu 3 chấm ...
- cắt chữ 1 dòng thì kết hợp thêm white-space: nowrap
- cắt chữ nhiều dòng thì kết hợp thêm display: -webkit-box; -webkit-box-orient: vertical -webkit-line-clamp: 3; ko nên dùng white-space: nowrap
- font-weight: độ đậm nhạt của chữ
- font-style: in thường hoặc in nghiêng
- font-family: tên font
- font-size: kích thước chữ px rem em ch vw vh %
- background-color -> màu nền
- object-fit: cover(phủ), contain(theo tỉ lệ tấm ảnh gốc)
- object-position: căn chỉnh trên dưới hoặc trung tâm
- cursor: con trỏ
- border-radius: bo góc, giá trị càng lớn thì bo càng lớn, muốn bo góc hình tròn thì khối nên là hình vuông
- `border-radius: 1px` nghĩa top=right=bottom=left = 1px
- `border-radius: 2px 4px` nghĩa top-left-radius=bottom-right-radius = 2px, top-right-radius=bottom-left-radius = 4px
- `border-radius: 2px 4px 6px` nghĩa top-left-radius = 2px, top-right-radius=bottom-left-radius = 4px, bottom-right-radius: 6px
- `border-radius: 2px 4px 6px 8px` nghĩa top-left-radius = 2px, top-right-radius = 4px, bottom-right-radius: 6px, bottom-left-radius=8px;
- list-style: hiển thị phía trước thẻ li khi dùng trong ol hoặc ul

## Box-sizing

- _content-box_:
- độ rộng = độ rộng(trong css) + padding-left + padding-right + border-left + border-right
- chiều cao = chiều cao(trong css) + padding-top + padding-bottom + border-top + border-bottom
- _border-box_:
- độ rộng = độ rộng(đã trừ padding-left, padding-right, border-left, border-right) + padding-left + padding-right + border-left + border-right
- chiều cao = chiều cao(đã trừ padding-top, padding-bottom, border-top, border-bottom) + padding-top + padding-bottom + border-top + border-bottom

## Margin

- `margin`: có 4 hướng top right bottom và left, giá trị của margin có thể là số âm, số dương và auto
- margin-left và margin-right auto không cho ra giữa đối với inline
- `margin: 1px` nghĩa là top=right=bottom=left = 1px
- `margin: 1px 2px` nghĩa top=bottom = 1px, right=left = 2px
- `margin: 1px 2px 3px` nghĩa là top= 1px right=left = 2px và bottom = 3px
- `margin: 1px 2px 3px 4px` top = 1px, right = 2px, bottom = 3px, left = 4px
- `margin: 0 auto` nghĩa là làm khối chạy ra giữa(chỉ có tác dụng với block hoặc flex)
- `margin-inline: auto` tương đương margin-left: auto và margin-right: auto
- `margin-block: auto` tương đương margin-top: auto và margin-bottom: auto
- _margin-collapse_: trường hợp phần tử dùng margin-bottom và margin-top đứng trên dưới, thì giá trị nào lớn hơn nó sẽ lấy giá trị đó, nếu bằng nhau thì lấy 1 trong 2
- có thể khắc phục bằng cách dùng inline-block
- dùng `text-align: center` cho thằng cha chứa inline-block nếu muốn inline-block ra giữa(center)

## Padding

- padding ko dùng được số âm(>=0)
- khi để độ rộng hoặc chiều cao là auto, thì nếu tăng padding lên thì kích thước cũng sẽ tăng theo
- khi để độ rộng hoặc chiều cao là cố định, khi dùng padding nên lưu ý cẩn thận chiếm hết diện tích của width height
- nếu không sử dụng padding thì nên thiết lập width và height cố định
- khi sử dụng padding và không thiết lập width height cố định: tăng font-size, line-height thì width và height sẽ tăng theo
- nên thiết lập padding left và padding right để không bị dính chữ hai bên(UI)

## Border, outline

- border thuộc về box-sizing, còn outline thì không
- border: border-width border-style border-color
- border-width: 2px, 3px
- border-style: solid, dashed, double, dotted
- border-color: red, #ff6bcb, rgb, rgba, hsl

# CSS

- `currentColor`: nó sẽ lấy giá trị của thuộc tính color
- `opacity: 0` nghĩa là không thấy, nhưng vẫn chiếm diện tích và có thể rê chuột vào được(con trỏ)
- `visibility: hidden` là không thấy, vẫn chiếm diện tích nhưng không rê chuột vào được(con trỏ)
- `display: none` là ko thấy, ko chiếm diện tích, ko còn gì cả
- _vw_: viewport width
- _vh_: viewport height
- _viewport_ độ rộng hoặc chiều cao của document, cẩn thận khi sử dụng `vw` nếu không hiểu cách nó hoạt động
- _rem_: đơn vị này sẽ phụ thuộc vào thuộc tính font-size của thẻ html(root)
- _em_: đơn vị em sẽ phụ thuộc vào thuộc tính font-size gần nhất(chính nó hoặc phần tử chứa nó), hạn chế dùng nếu không nắm vững
- Mặc định font-size của hầu hết trình duyệt là 100%(16px)
- _1rem_ = 1em = 16px
- Khi đổi font-size trong thẻ html thì tất cả những chỗ sử dụng đơn vị `rem` đều bị ảnh hưởng
- Thường ngta hay thiết lập font-size cho thẻ html là 62.5% để đổi đơn vị về cơ số 10px = 1rem, cho dễ tính toán
- box-shadow: x y blur scale color
- box-shadow không chiếm diện tích, có thể viết nhiều shadow ngăn cách nhau bởi dấu phẩy
- thông thường đi làm thì sẽ copy từ thiết kế vào, nhưng cũng hiểu để biết tùy chỉnh
- button, input, textarea, select nó sẽ lấy font từ trình duyệt chứ không kế thừa từ body
- max-width: Độ rộng tối đa
- Nếu width nhỏ hơn max-width thì nó sẽ lấy giá trị của width (170px < 200px -> 170px)
- Nếu width lớn hơn hoặc bằng max-width thì nó sẽ lấy giá trị max-width(200px)
- min-width: Độ rộng tối thiểu
- Nếu có min-width và max-width thì nó sẽ ưu tiên min-width hơn(nếu min-width > max-width)
- Nếu nội dung không có gì cả thì vẫn rộng theo min-width
- min-content nó sẽ độ rộng của từ dài nhất
- max-content và fit-content tương tự nhau, nhưng khuyến khích sử dụng fit-content
- inherit kế thừa từ thằng chứa nó gần nhất
- initial nó sẽ lấy theo giá trị của trình duyệt
- unset nó sẽ có giá trị là inherit nếu thằng cha chứa nó có thuộc tính tương ứng, không thì nó sẽ là initial
- SEO
- Khi sử dụng background thì phải có width height, đường dẫn phải chính xác
- Parallax
- linear-gradient(dir)
- dir: to left, to right, to top, to bottom, 0->360deg, to right top, to top right, to bottom left
  ....
- variables(biến): 1 giá trị dùng để dùng đi dùng lại ở nhiều chỗ và khi nó thay đổi thì những chỗ nào sử dụng nó sẽ thay đổi hết
- Khai báo thông thường ở :root(html)
- Cách đặt tên: --primary-color
- Cách sử dụng: var(--primary-color, orange) -> nếu ko tồn tại biến --primary-color thì nó sẽ lấy giá trị là orange
- Nếu tên biến trùng nhau nó sẽ ưu tiên thằng gần nhất

# Selectors

- selector:first-child: chọn thằng đầu tiên
- selector:last-child: chọn thằng cuối cùng
- selector:nth-child(number): chọn thằng theo thứ tự từ trên xuống dưới bắt đầu từ 1
- selector:nth-last-child(number): chọn từ dưới lên cũng bắt đầu từ 1
- selector:not(selector2): chọn selector này và không phải 1 selector khác

- type nó sẽ lấy theo thẻ
- selector:first-of-type
- selector:last-of-type
- selector:nth-of-type(number)
- selector:nth-last-of-type(number)

- is, where

- \+ đừng liền kế phía sau
- \~ đứng cùng cấp là được
- dấu cách tức là phần tử con là được
- \> nghĩa là con trực tiếp

# Flexbox

- Thuộc tính là `display` và giá trị là `flex` hoặc `inline-flex`
- _flex-direction_
- `row`: theo chiều ngang từ trái qua phải
- `row-reverse`: theo chiều ngang từ phải qua trái
- `column`: theo chiều dọc từ trên xuống dưới
- `column-reverse`: theo chiều dọc từ dưới lên trên
- _align-items_
- stretch(default): nó sẽ làm các phần tử cao bằng nhau nếu theo chiều ngang(row), rộng bằng nhau nếu chiều dọc(column)
- `center`: canh giữa các phần tử
- `flex-start`: canh phần trên đầu
- `flex-end`: canh phần dưới cùng
- `baseline`: liên quan tới typography, canh theo đít chữ của dòng đầu tiên
- _flex-wrap_
- `nowrap`: nó sẽ làm các phần tử luôn nằm trên 1 hàng khi container chứa nó không còn đủ diện tích
- `wrap`: làm cho các phần tử xuống hàng khi không còn đủ diện tích
- `wrap-reverse`: như wrap, nhưng thay vì rớt xuống thì nó sẽ rớt lên trên
- _justify-content_
- `flex-start`: các phần tử sẽ nằm dồn về phía bên trái
- `flex-end`: các phần tử sẽ nằm dồn về phía bên phải
- `center`: các phần tử sẽ nằm giữa thằng cha chứa nó
- `space-between`: các phần tử sẽ tự động chia khoảng trống sao cho có 1 thằng nằm đầu, 1 thằng nằm cuối còn lại sẽ nằm giữa đảm bảo các khoảng trống bằng nhau, nếu chỉ có 2 phần tử thì 1 thằng đầu, 1 thằng cuối
- `space-around`: các phần từ sẽ nằm rải rác và khoảng trống giữa 2 phần tử sẽ gấp đôi khoảng trống ở đầu cuối
- `space-evenly`: khoảng trống giữa các phần tử sẽ bằng nhau
- _gap_
- `row-gap`: khoảng trống giữa các phần tử theo chiều dọc
- `column-gap`: khoảng trống giữa các phần tử theo chiều ngang
- gap: row-gap column-gap
- gap: 10px 20px -> row-gap: 10px column-gap: 20px
- gap: 10px -> row-gap=column-gap=10px
- gap cũng tác động tới diện tích của container chứa các phần tử như margin
- _flex-grow_
- Cho phép các phần tử giãn ra(nếu giá trị lớn hơn 0) nếu container có đủ diện tích, số chúng ta truyền vào nếu như nhau tức là theo tỉ lệ thì bằng nhau, nếu có phần tử có số lơn thì cứ tính theo tỉ lệ. Nếu giá trị là 0 thì nó sẽ không giãn ra
- _flex-shrink_
- Cho phép các phần tử co lại nếu giá trị là 1, ngược lại nếu là 0 thì sẽ không co lại ở 1 kích thước nào đó(width, flex-basis), lưu ý nó chỉ có tác dụng khi chúng ta thiết lập độ rộng cố định với thuộc tính width hoặc flex-basis.
- Nếu giá trị là 2 3 4... thì phần tử có giá trị lớn hơn sẽ co lại nhiều hơn, nếu ko có flex-basis thì vẫn co lại như nhau
- _flex-basis_
- Nếu làm việc theo chiều ngang(row) thì flex-basis lúc này sẽ là độ rộng tối thiểu, còn nếu là chiều dọc(column) thì nó sẽ là chiều cao tối thiểu
- _flex_: grow shrink basis
- 3 thằng ở trên code vào phần tử con - phần tử chịu tác động của flexbox
- Đối với thẻ img là con trực tiếp bị tác động bởi flexbox thì hành vi của img hoạt động hơi khác so với các thẻ còn lại như div, section...
- Thông thường ngta sẽ bọc thẻ img vào 1 div cho an toàn
- flex-flow: flex-direction flex-wrap
- hàm calc(1 + 2)
- khi sử dụng calc thì các toán tử thực hiện phải có khoảng cách

# Giải pháp chia cột theo yêu cầu trong khóa học

- Xác định số cột -> 3 -> --columns: 3
- Xác định gap -> 12px -> --gap: 12px
<!-- - Xác định độ rộng -> 100% / số cột -> 100% / 3 -> calc(100% / var(--columns))
- Xác định số lượng gap giữa các cột -> calc(var(--columns) - 1);
- Xác định khoảng trống cần trừ ra của mỗi phần tử con -> --remove-spacing: calc((var(--gap) \* var(--gap-count)) / var(--columns));
- Xác định độ rộng của phần tử sau cùng -> --item-width-final: calc(var(--item-width) - var(--remove-spacing)); -->
  **Solution**
  -> flex-basis: calc(
  (100% / var(--columns)) - (var(--gap) \* (var(--columns) - 1)) /
  var(--columns)
  );

  example: columns 3 and gap 30x
  --spacing: calc(
    ((var(--columns) - 1) * var(--gap) / var(--columns))
  ) = 20px

  width: calc((100% / var(--columns)) - var(--spacing))


# Pseudo

- :hover rê chuột vào phần tử
- .header:hover
- (an + b) -> n chạy từ 0, a và b được chúng ta truỳen vào

# Responsive

- Mobile first: code ban đầu sẽ là cho giao diện điện thoại trước, và sau đó dùng media queries để code cho những màn hình lớn hơn, chúng ta sẽ dùng media queries min-width
- Desktop first: code ban đầu sẽ là cho giao diện máy tính trước, và sau đó dùng media queries để code cho những màn hình nhỏ hơn, chúng ta sẽ dùng media queries max-width
- Có thể kết hợp cả min-width và max-width
- Có thể sử dụng và(and), hoặc(,)
- Trong media queries thì sử dụng breakpoints, breakpoints chuẩn thì tham khảo bootstrap
- Breakpoints những điểm của độ rộng hoặc chiều cao của màn hình

# Grid

- Thuộc tính display và giá trị sẽ là `grid` hoặc là `inline-grid`
- Track line được đánh số thứ tự bắt đầu 1, cuối cùng là -1
- Có track-line theo cột và theo hàng
- Track line được đánh số dựa vào cột, track line cuối cùng là -1 hoặc số cột + 1
- Track line được đánh số dựa vào hàng, track line cuối cùng là -1 hoặc số hàng + 1
- grid-template-columns: cột1 cột2 cột3 cột4 cột n....
- cột sẽ có giá trị là những cái đã học ví dụ như 100px 50% 2rem
- hàm `repeat(số cột, giá trị`) -> repeat(4, 240px)
- Khi chia cột nếu có sử dụng `gap` thì gap cũng được cộng vào độ rộng của container
- Khi muốn chia bằng nhau sử dụng `gap` mà muốn các cột luôn đều và không bị quá độ rộng của container thì chúng ta nên sử dụng đơn vị `fr`
- grid-template-rows: hàng1 hàng2 hàng3 hàng n...
- Nếu số phần tử vượt quá số hàng đã thiết lập thì hàng mới sẽ có giá trị là auto
- grid-column và grid-row: sử dụng cho phần tử con chịu tác động của phần tử cha dùng grid
- grid-column: grid-column-start(track-line) / grid-column-end(track-line);
- grid-row: grid-row-start(track-line) / grid-row-end(track-line);
- grid-row và grid-column được xác định theo track-line
- grid-template-areas: dùng cho phần tử cha dùng grid, chia layout tổng quan rất xịn xò
- grid-area: dùng cho phần tử con dựa vào layout của grid-template-areas
- grid-auto-flow: theo row hoặc column
- grid-auto-rows: giá trị của row
- grid-auto-columns: giá trị của column
- auto-fit cố gắng lấp đầy hết khoảng trống của phần tử cha
- auto-fill cố gắng lấp đủ số cột mà chúng ta thiết lập, nếu giá trị minmax của các phần tử cộng lại + gap lớn hơn phần tử cha thì nó sẽ rớt xuống hàng
- repeat(auto-fill, minmax(100px, 1fr))
- repeat(auto-fit, minmax(100px, 1fr))
- align-self: áp dụng tương tự align-item nhưng chỉ cho phần tử con chính nó
- align-content: chỉ hoạt động khi flex-wrap không phải là `nowrap`
- align-content nếu flex-direction là row thì nó sẽ hoạt động theo chiều dọc
- align-content nếu flex-direction là column thì nó sẽ hoạt động theo chiều ngang
- align-content là toàn bộ content, khác với align-items là các phần tử canh với nhau

# Position

- Giá trị của nó gồm có `static` `relative` `absolute` `fixed` `sticky`
- Đi kèm với thuộc tính position thì sẽ có các thuộc tính như top right bottom left z-index và inset

## Relative
- khi sử dụng giá trị này thì phải lưu ý xem phần tử con của nó có sử dụng position là `absolute` hay không 
- Khi sử dụng position: relative nó vẫn chiếm diện tích như bình thường
- Khác với margin thì sử dụng những giá trị vào top right bottom left không tác động tới box-sizing của các phần tử khác, không ảnh hưởng tới layout khác
- Các giá trị của top right bottom left có thể là số âm, đơn vị px % em rem
- top: số âm thì đi lên trên, ngược lại đi xuống dưới
- left: số âm thì đi qua trái, ngược lại đi qua phải
- right: số âm thì đi qua phải, ngược lại đi qua trái
- bottom: số âm thì đi xuống dưới, ngược lại đi lên trên
- Thông thường position: relative dùng rất nhiều, dùng cho trường hợp có absolute chạy theo relative hoặc sticky chạy theo relative
- Nếu giá trị của top right bottom left mà là % thì % đó chính là % của thằng chứa nó, top bottom là chiều cao, right left là độ rộng của thằng chứa nó

## Absolute

- Phải xác định phần tử sử dụng absolute chạy theo ai ? -> 1 phần tử chứa nó gần nhất có sử dụng thuộc tính position: relative hoặc là absolute
- Phủ hết toàn bộ phần tử chứa nó thì dùng:
- top right bottom left đều là 0
- top left là 0 kết hợp với width: 100% và height: 100%
- inset: 0;
- inset: top right bottom left;
- Phủ hết theo chiều ngang -> top: 0 left: 0 right: 0 hoặc top:0 left:0 + width: 100% + height: 1 giá trị nào đó tùy vào yêu cầu
- Phủ hết theo chiều dọc -> top: 0 left: 0 bottom: 0 hoặc top:0 left:0 + height: 100% + width: 1 giá trị nào đó tùy vào yêu cầu
- z-index: thứ tự ưu tiên hiển thị khi xếp lên nhau

# Static

- Thường dùng khi mà muốn đè code, hoặc là reset thuộc tính position

# Fixed

- Fixed thì nó không chạy theo ai cả
- Fixed sẽ chạy theo body mà thôi
- Fixed không chiếm diện tích như absolute
- Khi sử dụng fixed thì ảnh hưởng tới layout nên cẩn thận khi sử dụng
- margin không có tác dụng khi sử dụng fixed
- padding của phần tử bao ngoài cũng không ảnh hưởng tới fixed

# Sticky

- Khi scroll chuột tới nó thì nó sẽ đứng im
- Thông thường sẽ là top: value; right: value hoặc top: value; left: value

# :before :after

- Thuộc tính bắt buộc là content: ""
- Nội dung trong content có thể có hoặc không
- Về cơ bản thì before và after tương tự khi chúng ta thêm 2 thẻ html phía trước và sau phần tử muốn dùng, lưu ý trước sau ở đây nghĩa là bên trong phần tử đó ví dụ: <h4><span>before</span>content<span>after</span></h4>
- Sử dụng 1 trong 2 hoặc 2 cái cùng lúc tùy thuộc yêu cầu bài toán

# transform: translate

- translateX(value) -> > 0 thì di chuyển qua phải, ngược lại qua trái
- translateY(value) -> > 0 thì di chuyển xuống dưới, ngược lại lên trên
- translate(x, y)
- translate3d(x, y, z)
- value có thể là px em rem là cố định giá trị
- value là % nếu là X thì nó sẽ là độ rộng của phần tử đang dùng, 100% là full độ rộng
- Nếu là Y thì nó sẽ là chiều cao của phần tử đang dùng, 100% là full chiều cao

# Pug

- Cài đặt NodeJS
- Mở vscode terminal _ctrl + `_
- Chạy lệnh `npm install -g pug`
- Chạy lệnh `npm install -g pug-cli`
- Extensions: Convert HTML to Pug,
- Pug không có các dấu đóng mở như html, xác định cha con thông qua tab size
- Tài liệu tham khảo: https://pugjs.org/api/getting-started.html

## Lệnh chạy file pug

- Tạo file pug ví dụ index.pug -> index.html
- Chạy lệnh `pug index.pug --pretty --watch`
- `pug \*.pug --pretty --watch` chạy toàn bộ file pug

## Chèn file pug

- Sử dụng include -> include ./views/sidebar
- `block` là những khối chúng ta định nghĩa để sử dụng cho nội dung nào đó
- `extends` dùng để kế thừa layout
- Khi sử dụng `block` thì nó sẽ không kế thừa những biến đã khai báo trước đó nếu có
- Muốn kế thừa các biến hiện tại thì dùng `append blockName`
- Khi sử dụng cấu trúc có `# {}` thì không cần sử dụng dấu = ở trước

## Mixins

- Cơ bản là component có thể tái sử dụng nhiều nơi và có thể thay đổi giá trị của từng component đó
- mixin menuItem -> +menuItem
- mixin menuItem(text, icon, url) -> +menuItem("evondev",<svg>, "https://evondev.com")
- camelCase -> menuItem, blogItem, header, howToBecomeDev
- Sử dụng biến thông thường trong mixin -> img(href= href)
- Sử dụng biến trong chuỗi thì dùng dấu `${tên biến}` -> `background-color: ${bg}`

## Object

- Là 1 tập hợp có key và value -> {key: value} -> {age: 30}

```js
{name: 'evondev', age: 30, school: 'Cao Thang'}
```

- Để truy xuất giá trị của 1 key nào đó thì mình sẽ dùng cấu trúc `object.key` -> val.name -> 'evondev', val.age -> 30, val.school -> 'Cao Thang'

## Array( danh sách, mảng )

- Là 1 danh sách chứa nhiều phần tử, ngăn cách bởi dấu phẩy, các phần tử có thể là số, chữ, boolean(true, false), hoặc là object -> [1,2,3,4,5]

## Vòng lặp

- each `val` in [1,2,3,4,5]
- `val` tương ứng là 1,2,3,4,5
- Nếu `val` là object thì sử dụng như kiến thức object đã chỉ ở trên val.name, val.href, val.icon

## Lưu ý

- Nếu sử dụng pug mà bị lỗi dùng cả space và tab mà thông báo lỗi từ terminal thì dùng lệnh `ctrl + shift + P` và gõ `convert indentation to Tabs` rồi lưu lại để sửa lỗi

# Sass

- CSS Preprocessor
- main.scss main.sass

## Cài đặt

- Mở terminal trong vscode hoặc terminal bên ngoài bất kỳ sau đó chạy lệnh `npm install -g sass`
- Truy cập vào thư mục chứa file .scss, chạy lệnh để generate file ví dụ `sass file-scss.scss file-css-generate.css --watch`
- Nếu thấy dòng `Compiled app.scss to app.css.` nghĩa là thành công
- Nếu thành dòng `No such file or directory` nghĩa là chạy sai dường dẫn hoặc sai file
- Nếu file có dạng \_name.scss thì dạng này là dùng để import là chính chứ không phải để generate
- Nếu file có dạng như bình thường thì dùng để generate
- Để ra file riêng để dễ dàng quản lý
- Lệnh chạy nhiều file theo thư mục `sass thu-muc-sass:thu-muc-css --watch`

## Variable

- $primary-color: red;
- color: $primary-color;

## Nested

- Tìm điểm chung của những class ví dụ .host, .host-item, .host-list, .host-heading -> Bắt đầu bằng chữ `.host`
- Để nối từ ở trong Sass thì chúng ta dùng dấu `&` -> `&-item{}`, `&-list{}`, `&-heading{}`

## @import @use @forward

- @import -> Nó sẽ import code global, nếu để nó ở trên cùng thì những file được import ở dưới có thể sử dụng từ nó ví dụ ở trên cùng chúng ta import biến thì những file sass ở dưới có thể sử dụng những biến đó
- @use -> Nó sẽ import theo dạng block scope
- @forward -> Thông thường dùng để import những đoạn code có tính sử dụng chung như biến, function, mixins
- @use "../abstracts/helper"; thì mặc định tên của file sẽ là `helper`, nếu muốn đổi tên thì dùng
- @use "../abstracts/helper" as h;

## Mixins

- Những đoạn code sử dụng đi sử dụng lại và có thể tùy biến tùy thuộc vào giá trị mà chúng ta yêu cầu
- Cách viết `@mixin name($var1, $var2....){code}`
- Cách sử dụng `@include name(red, 5px...)`
- Nếu gặp lỗi `mixin argument` nghĩa là quên truyền giá trị vào mixin
- Giá trị mặc định có cấu trúc `$value: value`

## Conditional

- Điều kiện @if true {} @else {}
- @if value -> value phải là đúng(true) hoặc là 1 điều kiện nào đó khác
- @else là ngược lại của if
- @else if

## @each

## @for

## Function

- Tài liệu tham khảo: https://www.tutorialsteacher.com/sass/sass-string-functions

## Content

- @content -> nội dung code truyền vào, thông thường sử dụng cho mixin responsive

## Pattern 7-1

# CSS3

## Transition

- `transition`: Thuộc tính này dùng để làm cho chuyển động được mượt mà hơn, những thuộc tính được áp dụng ví dụ như opacity, transform, color, background-color, shadow, width...
- Những thuộc tính không áp dụng được transition như display, top right bottom left,
- Thường sử dụng vào phần tử trước khi được tác động(:hover)
- cấu trúc: property(background-color, all) duration(0.5s) easing(linear, ease, ease-in, ease-in-out, ease-out, cubic-bezier) delay(1s)
- transition: background-color 1s ease 0s;

## Transform

- `transform`: Thuộc tính này bản chất là thay đổi hình dạng của vật thể, nhưng không giống như box-sizing tức là nó sẽ ko gây ra khoảng cách cho các phần tử, nói tóm gọn là element đang dùng transform bản chất vẫn đứng yên.
- Lưu ý: Những phần tử bên trong sẽ bị tác động theo, nếu không muốn bị tác động theo thì dùng lớp giả before hoặc after
- `rotateX(deg)`: dùng để xoay vật thể theo chiều ngang
- `rotateY(deg)`: xoay theo chiều dọc
- `rotateZ(deg)`: xoay theo mặt phẳng trước mặt
- `rotate(deg)`: giống rotateZ
- `skewX(deg)`
- `skewY(deg)`
- `skew(deg)`
- `scaleX(number)`
- `scaleY(number)`
- `scale(number)`

## Animation

- animation: chuyển động lặp đi lặp lại áp dụng những thuộc tính css vào
- cú pháp: animation: animation-name(loading) animation-duration(1s) animation-iteration-count() animation-delay animation-timing-function animation-direction animation-fillmode;
- keyframes: nếu chạy đơn giản thì dùng cú pháp from to
- Nếu animation phức tạp thì dùng % (0 -> 100%)
- animation-timing-function: ease, linear, ...
- animation-duration: 0.5s, 1s
- animation-name: spinner
- animation-direction: normal(0 -> 100%), reverse(100% -> 0), alternate(0 -> 100%, 100% -> 0)
- animation-fill-mode: forwards chạy xong rồi dừng, backwards chạy xong quay lại trạng thái ban đầu
- animation-iteration-count: 1, infinite
- animation-delay: 1s

## Table

- table, thead, tbody, tfoot, tr, td
- table nếu dùng border-collapse: separate thì có thể dùng border-spacing, nếu là border-collapse: collapse thì không có sử dụng được border-spacing
- Nếu dùng `border-collapse: separate` thì không thể css border cho thẻ `tr` được, muốn css border thì phải áp dụng cho thẻ `td`, nếu có radius thì cũng dùng cho thẻ `td`, nếu có hover đổi màu thì sẽ hover vào `tr` và tác động vào thẻ `td`
- Responsive cách 1: dùng 1 thẻ bao ngoài rồi css width: 100% và overflow-x: auto;
- Responsive cách 2: dùng custom attribute (data-cell)
- sticky

## Form

- Thẻ `form` dùng để làm các tác vụ liên quan tới form, ví dụ giao diện đăng ký tài khoản, đăng nhập, sử dụng Javascript để xử lý logic và có sự kết hợp của Backend
- Những thẻ trong form như input, textarea, button và select thì nó sẽ lấy font theo trình duyệt cho nên cần lưu ý thiết lập cho chúng kế thừa từ body
- <input type="submit" value="Update"/>
- <button type="submit"></button>

### Input

- `input` có các attributes hay gặp như

#### type

- `text`: Cho phép nhập vào chữ hoặc số, nói chung gì cũng được
- `number`: Nhập số, 2, 3, 5.5
- `email`: Nhập vào địa chỉ email
- `password`: Nhập vào mật khẩu hiển thị dưới dạng dấu \*
- `phone`: Số điện thoại
- `time`: Nhập vào thời gian
- `date`: Nhập vào ngày
- `submit`: Tương tự button submit, dùng để submit form
- `checkbox`: Hiển thị checkbox, checkbox cho phép người dùng chọn nhiều ví dụ như sở thích
- `radio`: Hiển thị radio, radio cho phép chọn 1 trong nhiều cái, ví dụ như giới tính chỉ được phép chọn nam hoặc nữ
- `file`: Cho phép người dùng chọn tập tin
- `reset`: Tương tự button reset, dùng để reset form
- `range`: Hiển thị dưới dạng thanh bar, dạng như tiến trình

#### placeholder

- Hiển thị lớp chữ cho thẻ input, và nó sẽ mất khi chúng ta gõ vào input

#### name

- Là tên của thẻ input, thuộc tính này dùng để lấy dữ liệu khi làm việc với Javascript, sự kiện submit của form
- Khi dùng với input có type là `checkbox` giúp chúng ta biết được người dùng chọn những cái nào
- Khi dùng với input có type là `radio` giúp chúng ta biết được người dùng chọn cái nào

### Other

- `required`: Bắt buộc người dùng phải nhập vào
- `readonly`: Không cho phép sửa input, nhưng khi submit form thì dữ liệu vẫn được gửi
- `disabled`: Tương tự readonly, khác chỗ là khi submit form thì dữ liệu ko được gửi đi
- `min`: Số tối thiểu
- `max`: Số tối đa
- `minlength`: Độ dài kí tự tối thiểu
- `maxlength`: Độ dài kí tự tối đa
- `autofocus`: Tự động focus vào thẻ input
- `autocomplete="off"`: Dùng vào thẻ `form`, mục đích là cho phép tự động điền hay không
- `inputmode`: Nó sẽ có các giá trị như search, email, tel, url, decimal, numeric

### textarea

- Thẻ này cho phép nhập nhiều dòng, thường dùng cho các kiểu nhập thông tin cá nhân hoặc là giới thiệu bản thân
- có `rows` và `columns` tương ứng cho chiều cao và chiều dọc, nhưng khuyến khích dùng css width và height
- có thuộc tính `resize` trong css cho phép người dùng kéo hoặc không cho kéo chiều cao hoặc chiều rộng của textarea

### select

- Hiển thị dưới dạng danh sách, cho phép người dùng chọn 1 hoặc nhiều tùy mục đích của giao diện
- Thẻ `select` trình duyệt không cho phép tùy biến được nhiều cho nên là dev hay tùy biến lại bằng cách dùng cấu trúc ul li và sau đó dùng Javascript để truy xuất dữ liệu

### Custom

- Tùy biến lại giao diện của checkbox, radio, toggle hoặc select bằng việc dùng các thẻ HTML khác và kết hợp Javascript để lấy dữ liệu

### pseudo (CSS)

- `:focus`: Khi nhấn chuột vào input
- `:valid`: Khi dữ liệu điền vào input thỏa yêu cầu
- `:invalid`: Ngược lại với :valid
- `:checked`: Khi input có type là `checkbox` hoặc `radio` được check vào
- `:disabled`: Dựa vào attribute để xử lý 1 giao diện nào đó
- `:read-only`:
- `:required`:
- `:out-of-range`:

### label

- Thẻ này dùng như các thẻ khác, là thẻ `inline`, đặc biệt có thuộc tính `for` và truyền vào `id` của input hoặc textarea
- Nếu thẻ `label` bọc thẻ `input` có type là `checkbox` hoặc `radio` thì khi nhấn vào label nó sẽ tự động checked

## Textarea editor

- Khung soạn thảo có nhiều option lựa chọn như in hoa in đậm... thông thường là dùng thư viện như ckeditor, quill,...

##

- pointer-events: none -> không hiển thị con trỏ cho phần tử, tức là không chọn được
- placeholder-show -> Kiểm tra xem input có hiển thị placeholder không ?

# Priority

- (id, (class, attribute), tag)
- x y z
- x: Độ ưu tiên cao nhất như id, #header, #blog, #container
- y: Độ ưu tiên thứ nhì như class, hoặc các attribute khác(href, alt, src...)
- z: Độ ưu tiên thấp nhất như các thẻ p, div,...
- inline styles có độ ưu tiên cao nhất, muốn đè được inline styles thì phải dùng `!important`

# dark-mode

- Khi làm giao diện có giao diện dark mode và light mode thì tốt nhất là lưu toàn bộ màu vào biến(CSS), sau đó làm mặc định 1 chế độ ví dụ light mode trước rồi copy toàn bộ biến sang darkmode rồi sửa lại cho phù hợp
- Lưu ý nếu sử dụng toggle với JS thì nên dùng custom attribute như data-theme="dark" rồi tùy thuộc vào đó mà styling cho phù hợp

# 3d

- perspective
- transform-style: preverse-3d
- backface-visibility: hidden

# container query

- https://ishadeed.com/article/say-hello-to-css-container-queries/
- @container feedSection (max-width: 500px) {}
  -> feedSection sẽ là tên container của phần tử cha
- @container feedItem (min-width: 501px) and style(--is-mobile: true) {}
  -> feedItem sẽ là tên container của nó và nó có sử dụng variable là --is-mobile:true
- Khi sử dụng container query thì phần tử con dùng position: fixed không hoạt động, thay vào đó dùng thử position: sticky, nếu mà vẫn chưa được như ý muốn thì chuyển sang dùng media query cho chắc


caniuse la 1 trang web giup chung ta kiem tra thuoc tinh trong css xem no co dc trinh ho tro hay khong

semantic tags(html 5): header, footer, main, section, article, nav, aside
