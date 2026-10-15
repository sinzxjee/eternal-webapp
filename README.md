# ETERNAL · Chơi đơn

Game trên GitHub Pages: https://sinzxjee.github.io/eternal-webapp/

Có Gacha 3/9 với ảnh và bảo hiểm SSR, kho từng bản quái, đội hình tối đa 6, chiến đấu theo lượt, 150 ải, Boss, chốt Boss Gacha từ vòng 30, tháp, đấu trường AI, dung hợp, trứng, chế tạo, trang bị, nâng cấp, nhiệm vụ, thành tựu, cổ vật, nhật ký, xuất/nhập JSON và tiếp tục trận đang chơi sau khi tải lại.

Bản lưu chơi đơn dùng `eternal-singleplayer-v1`. Đọc bản cũ `eternal-mobile-test-v1` khi chưa có bản mới, giữ tổng thẻ và tài nguyên. Dữ liệu bản cũ không bị xóa. 29 hồ sơ thẻ hiếm được khớp theo dữ liệu cũ; 54 thẻ thấp chưa có danh tính giữ ở kho Legacy, không tự đổi thành loài ngẫu nhiên. Những quái UR cũ nằm ngoài catalog 150 vẫn tồn tại với hồ sơ Legacy.

Ảnh cắt thô và tên chưa đối chiếu hoàn toàn. Chỉ số và hệ cho loài chưa có hồ sơ là thiết kế chơi đơn, không phải xác nhận dữ liệu gốc. Đội hình chiến đấu dùng thẻ sở hữu trong menu Đội hình; đội hình tại trang archive là danh sách tham khảo.

Lưu trên một trình duyệt; không có tài khoản hoặc đồng bộ online. Xuất JSON trước khi xóa dữ liệu trình duyệt hoặc đổi máy. Mỗi trận thắng nhận thưởng một lần. Trứng ấp sau ba trận thắng. Công thức cũ 10 R → 10 SR được giữ; UR → EX cần 10 UR và một mảnh dung hợp III.

150 ID đều có hệ, tộc, vai trò, 8 chỉ số và 1–5 kỹ năng theo bậc. R giữ 1 hệ, 1 vai trò, 3 chiêu. Hồ sơ cũ được ưu tiên giữ; phần bổ sung là thiết kế chơi đơn. Các chiêu khác nhau có sức mạnh, hệ và hồi chiêu riêng. Đòn phép dùng MAG/RES, vật lý dùng ATK/DEF; SPD quyết định bên hành động trước; CRIT/CRIT DMG áp dụng vào sát thương.

Trong trận, chọn quái của bạn và mục tiêu rồi chọn chiêu. Có ảnh, thanh HP, số sát thương, hiệu ứng ra đòn, nhận đòn, hồi máu và khiên; tôn trọng thiết lập giảm chuyển động của trình duyệt. Một số quái Legacy không có ảnh riêng dùng ảnh đại diện và ghi rõ tại BST.

UI dùng màu trầm, bo góc tối đa 8px, 6 mục chính và menu phụ. Mọi trang dùng chung catalog.js để tránh tải trùng bộ ảnh. Chế độ `?demo=1` dùng bản lưu thử riêng, không ảnh hưởng tiến trình chính.

Các file deploy: index.html, catalog.js, singleplayer.js, ui.css, ui.js, battle.css, archive.html, archive-ui.css, archive-profile.js, pokedex.json, .nojekyll. Không tải ZIP làm trang chủ.
