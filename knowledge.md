- _user-agent-stylesheet_: CSS mặc định của các trình duyệt, mỗi trình duyệt sẽ có CSS mặc định khác nhau.
- _css-reset_: dùng để reset CSS mặc định của mỗi trình duyệt và 'bắt buộc' phải có đầu tiên
- _html-reference_: all elements and attributes

- _CSS-variables_: :root {}

- _css-selectors-child_: :nth-child(number), :nth-last-child(number) :first-child, :last-child, những phần tử cùng cấp, :not(selectors) = : not(:fist-child), :not-first-child(selectors) = :not(:nth-child(5))

- _time_: html-tag, inline

- _box-sizing_: margin, padding, border, width, height ==> đơn vị px
- content-box: độ rộng của box = width + padding(left + right) + border(left + right)
- border-box: độ rộng của box = padding + border

- _font-size_: 18px
- _line-height_: identical to box height or 75%

- _display_: block, inline, inline-block, none, flex, grid
- `block`: biến thành thẻ block
- `inline`: biến thành thẻ inline, bị hạn chế vài thuộc tính CSS liên quan tới box-sizing: padding-top, padding-bottom, margin-top, margin-bottom.
- `inline-block`: biến thành thẻ inline-block, inline-block là kết hợp giữa inline & block, khi các thẻ có thuộc tính inline-block nó sẽ kế thừa đặc tính của inline tức là nằm cạnh nhau thì sẽ nằm trên 1 hàng và có độ rộng bằng nội dung mà nó chứa, không bị hạn chế CSS.
- `none`: ẩn tag

- _min-width_: độ rộng tối thiểu
- _max-width_: độ rộng tối đa

- _flex-box_: display: flex
- _flex-diretion_: row, row-reverse. column, column, column-reverse
- _align-items_: căn chỉnh
- `stretch`(defaul): kéo dài cho các phần tử bằng nhau
- `flex-start`: căn chỉnh theo top
- `flex-end`: căn chỉnh theo bottom
- `baseline`: căn chỉnh đích chữ đầu tiên
- _justify-content_:
- `flex-start`
- `flex-end`
- `justify-center`
- `space-between`
- `space-around`: khoang trong right + left = khoang trong center
- `space-evenly`: khoang trong se deu nhau
- _flex-wrap_: wrap, nowrap, wrap-reverse
- _column-gap_: khoang trong theo chieu doc
- _row-gap_: khoang trong theo chieu ngang
- _gap_: column-grap row-grap
- `columns`: Số column cần chia
- `gap`: khoang trong theo chieu doc và theo chieu ngang
- `spacing`: khoang cach giua 2 item với nhau = ((columns - 1) \* gap) / columns
- _flex-shrink_: Co cho phep co lai hay khong

- _word-break_: break-all, break-word
- _white-space_: nowrap
- _overflow_: hidden
- _text-overflow_: ellipsis

- _display_: -webkit-box
- _-webkit-line-clamp-_: 2
- _-webkit-box-orient-_: vertical
- _overflow_: hidden
- _text-overflow_: ellipsis
- _word-break_: break-word

- _calc_: hàm dùng để tính toán

- _responsvie_:
- `breakpoints`: 320px, 480px, 768px, 1024px, 1200px, 1366px, 1440px, 1600px, 1920px
- `min-width`: @media screen and (min-width: breakpoints)
- `max-width`: @media screen and (max-width: breakpoints - 1px/0.2px)
- `media-queries`

- _transform_: translate(translateX(value), translateY(value)), skew(skewX, skewY), rotate(rotateX, Y, Z), scale(x, Y)
- `translateX`: Nếu giá trị là số dương thì nó sẽ di chuyển qua bên phải, ngược lại di chuyển qua bên trái
- `translateY`: Nếu giá trị số dương thì nó di xuống ngược lại nó sẽ đi lên
- `value`: 10px, -20px, 10%. Lưu ý % ở đây chính là độ rộng hoặc chiều cao của khối chúng(đang xài thuộc tính transform chứ không phải phần tử ngoài) áp dụng thuộc tính transform và hàm translate

- _grid_:
- `1fr`: 1 traction unit
- `grid-template-columns`: px, %, 1fr, repeat(columns, 1fr)
- `grid-auto-flow`: column, row ==> sẽ không wrap khi có multi items
- `grid-auto-columns`: 1fr ==> sẽ không wrap khi có multi items
- `grid-auto-row`: bao nhieu row thi co bao nhieu gia tri
- `grid-column`: vi tri item muon set
- `grid-row`: vi tri item muon set

- _img_:
- `object-fit`: hiển thị hình ảnh hoặc video vừa với khung của nó
- `object-position`: căn chỉnh hiển thị của img hoặc video và chỉ dùng với `object-fit`

- _width_: fit-content ==> có độ rộng bằng với nội dung chứa nó
- _margin-inline_: ==> margin-left: auto && margin-right: auto
- _margin-block_: ==> margin-top: auto && margin-bottom: auto
- _padding-inline_: ==> padding-left: auto && padding-right: aut
- _padding-block_: ==> padding-top: auto && padding-bottom: auto

- _sematic-tags_: header, footer, main, secgtion, article, nav, aside
- _list-style_: thuoc tinh dung cho the ul(`disc`) & ol(`decimal`)
- _list-style-position_: outside hoac inside
