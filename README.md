### Passwordless Authentication: Nó là gì và cách thức hoạt động của nó?

#### Giới thiệu

Passwordless Authentication hứa hẹn sẽ loại bỏ điểm yếu số một về bảo mật: mật khẩu. Vì lý do đó, Passwordless Authentication đang tạo ra rất nhiều cuộc thảo luận, bao gồm cả những ý kiến ​​​​khác nhau mà đáng tiếc là có thể gây hiểu lầm và khó hiểu. Bài viết này cung cấp một số thông tin rõ ràng về Passwordless Authentication là gì và cách thức hoạt động của nó.

Như chúng ta đã biết **Password** từ lâu đã được biết đến là mắt xích yếu nhất trong vấn đề bảo mật. Người dùng sử dụng lại mật khẩu trên nhiều hệ thống, họ quên hoặc ghi lại mật khẩu và mật khẩu rất dễ bị xâm phạm. Theo Báo cáo điều tra vi phạm dữ liệu của Verizon năm 2020, hơn 80% vi phạm liên quan đến brute force hoặc sử dụng thông tin xác thực bị mất hoặc bị đánh cắp.

Qua nhiều năm, một số lựa chọn thay thể mật khẩu đã được phát triển như: Common Access Cards (CAC), smartcards, ... Tuy nhiên, mật khẩu vẫn tiếp tục được sử dụng làm bản sao lưu cho các phương pháp này. Miễn là mật khẩu được sử dụng, bạn vẫn dễ bị tấn công bởi các mối đe dọa dựa trên mật khẩu như tấn công lừa đảo, hoán đổi SIM, v.v.

Xác thực 2 yếu tố (2FA) cũng không tốt hơn nhiều. 2FA truyền thống được cho là cải thiện vấn đề bảo mật bằng cách thêm lớp bảo mật bổ sung sau bước nhập mật khẩu. Tức là sau khi người dùng nhập mật khẩu ban đầu, hệ thống sẽ yêu cầu thêm bước xác thực để xác định danh tính. Thật không may, với 2FA cũng không mạnh hơn mật khẩu là bao. Do các phương thức này sử dụng SMS, là một cách thức dễ tấn công. Nhưng xét cho cùng, 2FA không loại bỏ bước không an toàn nhất trong quá trình đăng nhập đó là Password. Cuối cùng 2FA cũng gây thêm cản trở cho quá trình xác thực, ảnh hưởng đến trải nghiệm của người dùng, bởi người dùng phải tốn thêm thời gian để nhập mã xác thực và việc này gây khó chịu đến mực ảnh hưởng năng suất (Ví dụ: Khi đang có việc gấp cần truy cập ứng dụng nhưng hệ thống lại yêu cầu 2FA từ đó gây bức xúc cho người dùng => Gây ảnh hưởng đến năng suất)

Từ đó Passwordless authentication thay thế các yếu tố yếu của 2FA bằng các yếu tố mạnh hơn đáng kể. Do đó, giải pháp xác thực không cần mật khẩu sẽ cải thiện tính bảo mật và trải nghiệm người dùng bằng cách loại bỏ trở ngại khỏi quá trình đăng nhập (Loại bỏ bước nhập OTP).

#### Passwordless authentication: Nó là gì và cách thức hoạt động của nó?

Passwordless authentication: một hình thức xác thực không bao giờ sử dụng mật khẩu. Mật khẩu không được sử dụng làm phương thức xác thực thay thế hoặc thậm chí là phương pháp dự phòng. Mật khẩu cũng không được lưu trữ trong kho mật khẩu hoặc trình quản lý.

Đây là một điểm quan trọng cần hiểu vì một số nhà cung cấp công nghệ cho biết giải pháp xác thực của họ không cần mật khẩu nhưng trong khi thực tế thì không. Họ tiếp tục sử dụng mật khẩu làm bản sao lưu nên bất kỳ ai cũng có thể sử dụng mật khẩu đó để đăng nhập và bạn vẫn dễ bị tấn công dựa trên mật khẩu.

Mục đích của việc không cần mật khẩu là sử dụng phương thức xác thực an toàn hơn. Mật khẩu là một yếu tố kiến ​​thức. Sẽ không có nhiều cải thiện nếu bạn thay thế mật khẩu bằng mật khẩu khác, giống như yếu tố kiến ​​​​thức không an toàn.

#### Lợi ích của việc xác thực không cần mật khẩu

Passwordless authentication mang lại một số lợi ích:

1. Dừng việc chiếm đoạt tài khoản khỏi các cuộc tấn công thông tin xác thực: Việc xóa mật khẩu làm phương thức xác thực sẽ **loại bỏ tất cả các cuộc tấn công dựa trên mật khẩu.** Những kẻ tấn công đơn giản là không thể sử dụng mật khẩu để đăng nhập vì chúng không tồn tại. Xác thực không cần mật khẩu có thể chống lại việc thông tin đăng nhập bị đánh cắp hoặc rò rỉ trong việc nhồi thông tin xác thực (credential stuffing), bẻ khóa thông tin xác thực, tấn công bảng cầu vồng (rainbow table attacks), ransomware thông qua RDP, kỹ thuật xã hội và tấn công lừa đảo.

2. Cải thiện trải nghiệm người dùng: Với thông tin đăng nhập không cần nhấp chuột, Passwordless authentication sẽ loại bỏ những khó khăn khi xác thực. Người dùng không cần phải sử dụng thiết bị thứ hai, kiểm tra email, ghi nhớ mật khẩu hoặc gặp rắc rối khi đặt lại chúng.
3. Tiết kiệm thời gian và tiền bạc khi đặt lại mật khẩu và gọi tới bộ phận trợ giúp: Người dùng không còn cần phải nhớ các mật khẩu duy nhất hoặc thường xuyên đặt lại chúng như một phần của chính sách mật khẩu mạnh, đồng nghĩa với việc bộ phận CNTT sẽ ít phải làm việc hơn
4. Tăng cường tình trạng bảo mật của bạn bằng tính năng xác thực dựa trên rủi ro liên tục: Người dùng được cấp lại quyền với mỗi yêu cầu truy cập để đảm bảo rằng tình trạng rủi ro của người dùng không thay đổi.

#### Cách thức hoạt động của Passwordless authentication?

Passwordless authentication đề cập đến phương pháp xác minh danh tính người dùng mà không cần sử dụng mật khẩu. Thay vì mật khẩu, người dùng xác thực bằng cách sử dụng thứ họ có (chẳng hạn như thiết bị di động) hoặc thứ gì đó của họ (chẳng hạn như sinh trắc học). Mỗi khi người dùng yêu cầu quyền truy cập, một thông báo xác thực mới sẽ được tạo. Do đó, không có thông tin xác thực nào được cố định trong nền tảng không mật khẩu nên không có gì để kẻ tấn công đánh cắp.

Passwordless authentication tận dụng công nghệ được tích hợp trong các thiết bị hiện đại để cung cấp xác thực an toàn. Những công nghệ này là sinh trắc học và Mô-đun nền tảng đáng tin cậy (TPM). TPM là một khu vực an toàn nơi dữ liệu nhạy cảm có thể được lưu trữ. Trong trường hợp xác thực không cần mật khẩu, dữ liệu nhạy cảm đó là khóa mật mã riêng. TPM ký chứng chỉ bằng khóa riêng có thể được xác thực bằng khóa chung tương ứng.

Mô hình này vốn đã được tin cậy. Trên thực tế, nó được sử dụng vô số lần trong ngày bởi mọi người ở khắp mọi nơi gửi thông tin cá nhân qua Internet. Mô hình này được Transport Layer Security (TLS) sử dụng để đảm bảo rằng dữ liệu riêng tư được trao đổi với máy chủ vẫn ở chế độ riêng tư và an toàn. TLS sử dụng chứng chỉ X.509 dựa trên mật mã bất đối xứng và cặp khóa công khai.

Giải pháp xác thực không cần mật khẩu tận dụng chứng chỉ X.509 mà không cần tổ chức phát hành chứng chỉ hoặc bất kỳ quản lý chứng chỉ nào. Nó chỉ đơn giản là mở rộng Chuỗi tin cậy™ do TLS thiết lập cho người dùng và thiết bị của họ.

Sử dụng chứng chỉ X.509 và cặp khóa công khai sẽ an toàn hơn các phương thức xác thực khác. Mật khẩu, cụm mật khẩu và mã PIN sử dụng bí mật chung—một phần dữ liệu được lưu trữ trong cơ sở dữ liệu có thể dễ bị xâm phạm. Các khóa phần cứng có vấn đề bảo mật đã biết với Bluetooth và Giao tiếp trường gần (NFC). Họ cũng thiếu chế độ bảo mật thiết bị chi tiết, toàn diện.

Ngoài các lỗ hổng được đề cập, MFA còn tăng khả năng hiển thị thông qua việc hack SIM, phần mềm độc hại và tràn thông báo. Tuy nhiên, với công nghệ X.509 và TLS, khóa riêng được lưu trữ an toàn trong TPM của thiết bị cá nhân. Bất kỳ ai cũng không thể xóa hoặc xem khóa riêng—kể cả người dùng.

Một số tổ chức có hệ thống cũ vẫn yêu cầu người dùng phải có mật khẩu trong thư mục. Bạn cũng có thể sử dụng xác thực không cần mật khẩu cho các hệ thống này. Trong bảng điều khiển Beyond Identity, bạn có thể thiết lập chính sách truy cập để không ai có thể sử dụng mật khẩu để đăng nhập. Nếu kẻ tấn công cố gắng truy cập vào hệ thống bằng mật khẩu bị đánh cắp, cảnh báo sẽ được kích hoạt và kẻ tấn công sẽ bị từ chối truy cập.

[Nguồn Beyond Identity](https://www.beyondidentity.com/resources/passwordless-authentication)
