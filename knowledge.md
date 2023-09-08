- _user-agent-stylesheet_: CSS mặc định của các trình duyệt, mỗi trình duyệt sẽ có CSS mặc định khác nhau.
- _css-reset_: dùng để reset CSS mặc định của mỗi trình duyệt và 'bắt buộc' phải có đầu tiên
- _html-reference_: all elements and attributes
- _box-sizing_: margin, padding, border, width, height ==> đơn vị px
- content-box: độ rộng của box = width + padding(left + right) + border(left + right)
- border-box: độ rộng của box = padding + border

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
- _grap_: column-grap row-grap

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

