### Passwordless Authentication: Nó là gì và cách thức hoạt động của nó

#### Giới thiệu

Passwordless Authentication hứa hẹn sẽ loại bỏ điểm yếu số một về bảo mật: mật khẩu. Vì lý do đó, Passwordless Authentication đang tạo ra rất nhiều cuộc thảo luận, bao gồm cả những ý kiến ​​​​khác nhau mà đáng tiếc là có thể gây hiểu lầm và khó hiểu. Bài viết này cung cấp một số thông tin rõ ràng về Passwordless Authentication là gì và cách thức hoạt động của nó.

Như chúng ta đã biết **Password** từ lâu đã được biết đến là mắt xích yếu nhất trong vấn đề bảo mật. Người dùng sử dụng lại mật khẩu trên nhiều hệ thống, họ quên hoặc ghi lại mật khẩu và mật khẩu rất dễ bị xâm phạm. Theo Báo cáo điều tra vi phạm dữ liệu của Verizon năm 2020, hơn 80% vi phạm liên quan đến brute force hoặc sử dụng thông tin xác thực bị mất hoặc bị đánh cắp.

Qua nhiều năm, một số lựa chọn thay thể mật khẩu đã được phát triển như: Common Access Cards (CAC), smartcards, ... Tuy nhiên, mật khẩu vẫn tiếp tục được sử dụng làm bản sao lưu cho các phương pháp này. Miễn là mật khẩu được sử dụng, bạn vẫn dễ bị tấn công bởi các mối đe dọa dựa trên mật khẩu như tấn công lừa đảo, hoán đổi SIM, v.v.

Xác thực 2 yếu tố (2FA) cũng không tốt hơn nhiều. 2FA truyền thống được cho là cải thiện vấn đề bảo mật bằng cách thêm lớp bảo mật bổ sung sau bước nhập mật khẩu. Tức là sau khi người dùng nhập mật khẩu ban đầu, hệ thống sẽ yêu cầu thêm bước xác thực để xác định danh tính. Thật không may, với 2FA cũng không mạnh hơn mật khẩu là bao. Do các phương thức này sử dụng SMS, là một cách thức dễ tấn công. Nhưng xét cho cùng, 2FA không loại bỏ bước không an toàn nhất trong quá trình đăng nhập đó là Password. Cuối cùng 2FA cũng gây thêm cản trở cho quá trình xác thực, ảnh hưởng đến trải nghiệm của người dùng, bởi người dùng phải tốn thêm thời gian để nhập mã xác thực và việc này gây khó chịu đến mực ảnh hưởng năng suất (Ví dụ: Khi đang có việc gấp cần truy cập ứng dụng nhưng hệ thống lại yêu cầu 2FA từ đó gây bức xúc cho người dùng => Gây ảnh hưởng đến năng suất)

Từ đó Passwordless authentication thay thế các yếu tố yếu của 2FA bằng các yếu tố mạnh hơn đáng kể. Do đó, giải pháp xác thực không cần mật khẩu sẽ cải thiện tính bảo mật và trải nghiệm người dùng bằng cách loại bỏ trở ngại khỏi quá trình đăng nhập (Loại bỏ bước nhập OTP).

#### Passwordless authentication: Nó là gì và cách thức hoạt động của nó
