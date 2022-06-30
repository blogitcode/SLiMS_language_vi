# Ngôn ngữ tiếng Việt cho phần mềm SLiMS

Mặc định ngôn ngữ của cms này là tiếng anh, để cài đặt tiếng Việt và việt hóa slims bạn có thể làm như sau:

# Cài đặt tiếng Việt:

– Tải file ngôn ngữ tiếng Việt

– Sau khi tải về bạn tiến hành giải nén và copy vào thư mục locate (đường dẫn \slims\lib\lang\locale)

– Mở file localisation.php (đường dẫn \slims\lib\lang), thêm đoạn code sau ngay vị trí:

// Array with available translations

$available_languages[] = array(‘vi_VN’, __(‘Vietnamese’), ‘Vietnamese’);

– Tiếp theo đăng nhập trang quản lý slims, chọn System -> System Configuration – >

bạn sẽ thấy tùy chọn Default App. Language, chọn Vietnamese và Save lại để thay đổi có hiệu lực.
