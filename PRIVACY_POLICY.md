# Chính Sách Bảo Mật / Privacy Policy

**Ngày có hiệu lực / Effective Date:** Mon 04 May 2026

---

## Tiếng Việt

### 1. Giới Thiệu

Trolly là ứng dụng quản lý nhà trọ dành cho chủ nhà trọ, được phát triển bởi Hai Ng. / craftzcatdev. Ứng dụng giúp quản lý phòng cho thuê, ghi chỉ số điện nước hàng tháng, tính toán hóa đơn tiện ích, và chia sẻ hóa đơn với người thuê qua Zalo.

Chính sách này mô tả cách chúng tôi thu thập, sử dụng và bảo vệ thông tin của bạn khi sử dụng ứng dụng Trolly.

### 2. Thông Tin Chúng Tôi Thu Thập

#### 2.1 Thông Tin Tài Khoản
- **Email và mật khẩu:** Khi bạn đăng ký tài khoản quản trị viên thông qua Firebase Authentication, chúng tôi lưu trữ địa chỉ email và mật khẩu đã được mã hóa của bạn.
- **User ID (UID):** Firebase tự động tạo một mã định danh duy nhất cho tài khoản của bạn.

#### 2.2 Dữ Liệu Quản Lý Nhà Trọ
Bạn (với vai trò chủ nhà trọ) nhập các thông tin sau vào ứng dụng:
- **Thông tin phòng:** Số phòng, giá thuê, diện tích, trạng thái phòng
- **Thông tin người thuê:** Họ tên, số điện thoại, ngày bắt đầu thuê, ngày kết thúc thuê
- **Chỉ số điện nước:** Chỉ số điện, chỉ số nước được ghi lại hàng tháng
- **Hóa đơn:** Thông tin tính toán tiền điện, nước, tiền phòng theo tháng

Tất cả dữ liệu này được lưu trữ trong Firebase Firestore thuộc dự án Firebase của nhà phát triển.

#### 2.3 Thông Tin Thiết Bị và Bảo Mật
- **Firebase App Check / App Attest:** Để bảo vệ ứng dụng khỏi truy cập trái phép, Firebase App Check có thể thu thập thông tin thiết bị cơ bản (như mã định danh thiết bị tạm thời) để xác minh rằng yêu cầu đến từ ứng dụng chính thức.
- **Thông tin chẩn đoán Firebase:** Firebase SDK có thể tự động thu thập dữ liệu chẩn đoán cơ bản (như loại thiết bị, phiên bản iOS, thông tin lỗi) để duy trì và cải thiện dịch vụ.

### 3. Cách Chúng Tôi Sử Dụng Thông Tin

Chúng tôi sử dụng thông tin thu thập được để:
- Xác thực danh tính của bạn khi đăng nhập
- Lưu trữ và quản lý dữ liệu phòng trọ, người thuê, và hóa đơn
- Tính toán hóa đơn tiện ích hàng tháng
- Bảo vệ ứng dụng khỏi truy cập trái phép
- Duy trì và cải thiện chức năng của ứng dụng

### 4. Chia Sẻ Thông Tin

**Chúng tôi KHÔNG chia sẻ thông tin cá nhân của bạn với bất kỳ bên thứ ba nào**, ngoại trừ:
- **Firebase/Google Cloud Platform:** Dữ liệu được lưu trữ trên cơ sở hạ tầng Firebase (thuộc Google), tuân theo [Chính sách bảo mật của Google](https://policies.google.com/privacy).
- **Yêu cầu pháp lý:** Nếu luật pháp yêu cầu, chúng tôi có thể tiết lộ thông tin cho cơ quan có thẩm quyền.

**Lưu ý quan trọng:**
- Ứng dụng **KHÔNG sử dụng** bất kỳ SDK quảng cáo, phân tích, hoặc theo dõi hành vi người dùng nào.
- Thông tin người thuê (tên, số điện thoại) mà bạn nhập vào ứng dụng được lưu trữ trong dự án Firebase của nhà phát triển và không được chia sẻ với bên thứ ba.
- Khi bạn chia sẻ hóa đơn qua Zalo, việc chia sẻ đó do bạn chủ động thực hiện và tuân theo chính sách của Zalo.

### 5. Bảo Mật Dữ Liệu

Chúng tôi thực hiện các biện pháp bảo mật hợp lý để bảo vệ dữ liệu của bạn:
- Mật khẩu được mã hóa bởi Firebase Authentication
- Dữ liệu được truyền tải qua kết nối HTTPS được mã hóa
- Firebase App Check giúp ngăn chặn truy cập trái phép vào cơ sở dữ liệu
- Quy tắc bảo mật Firestore được cấu hình để chỉ cho phép người dùng đã xác thực truy cập dữ liệu của họ

Tuy nhiên, không có phương thức truyền tải hoặc lưu trữ điện tử nào là an toàn 100%. Chúng tôi không thể đảm bảo tuyệt đối về bảo mật.

### 6. Quyền Của Bạn

Bạn có quyền:
- **Truy cập:** Xem dữ liệu cá nhân của bạn trong ứng dụng
- **Chỉnh sửa:** Cập nhật hoặc sửa đổi thông tin trong ứng dụng
- **Xóa:** Xóa dữ liệu phòng trọ, người thuê, hoặc hóa đơn bất kỳ lúc nào
- **Xóa tài khoản:** Liên hệ với chúng tôi để xóa hoàn toàn tài khoản và tất cả dữ liệu liên quan

### 7. Lưu Trữ Dữ Liệu

Dữ liệu của bạn được lưu trữ trên Firebase Firestore (máy chủ của Google Cloud Platform) và sẽ được giữ lại cho đến khi:
- Bạn chủ động xóa dữ liệu trong ứng dụng
- Bạn yêu cầu xóa tài khoản
- Ứng dụng ngừng hoạt động

### 8. Trẻ Em

Ứng dụng Trolly không dành cho người dưới 18 tuổi. Chúng tôi không cố ý thu thập thông tin cá nhân từ trẻ em. Nếu bạn phát hiện một trẻ em đã cung cấp thông tin cá nhân cho chúng tôi, vui lòng liên hệ để chúng tôi có thể xóa thông tin đó.

### 9. Thay Đổi Chính Sách

Chúng tôi có thể cập nhật Chính sách bảo mật này theo thời gian. Chúng tôi sẽ thông báo cho bạn về bất kỳ thay đổi nào bằng cách đăng chính sách mới trong ứng dụng hoặc qua email. Bạn nên xem lại chính sách này định kỳ.

### 10. Liên Hệ

Nếu bạn có bất kỳ câu hỏi nào về Chính sách bảo mật này, vui lòng liên hệ:

**Email:** [craftzcatdev@gmail.com]  
**Nhà phát triển:** Hai Ng. / craftzcatdev

---

## English

### 1. Introduction

Trolly is a rental property management app for landlords, developed by Hai Ng. / craftzcatdev. The app helps manage rental rooms, record monthly electricity and water meter readings, calculate utility bills, and share invoices with tenants via Zalo.

This policy describes how we collect, use, and protect your information when you use the Trolly app.

### 2. Information We Collect

#### 2.1 Account Information
- **Email and password:** When you register an admin account through Firebase Authentication, we store your email address and encrypted password.
- **User ID (UID):** Firebase automatically generates a unique identifier for your account.

#### 2.2 Rental Property Management Data
You (as the landlord) enter the following information into the app:
- **Room information:** Room number, rental price, area, room status
- **Tenant information:** Full name, phone number, lease start date, lease end date
- **Utility meter readings:** Electricity and water meter readings recorded monthly
- **Invoices:** Calculated electricity, water, and rent charges by month

All this data is stored in Firebase Firestore within the developer's Firebase project.

#### 2.3 Device and Security Information
- **Firebase App Check / App Attest:** To protect the app from unauthorized access, Firebase App Check may collect basic device information (such as temporary device identifiers) to verify that requests come from the legitimate app.
- **Firebase diagnostic information:** Firebase SDKs may automatically collect basic diagnostic data (such as device type, iOS version, crash information) to maintain and improve the service.

### 3. How We Use Information

We use the collected information to:
- Authenticate your identity when logging in
- Store and manage room, tenant, and invoice data
- Calculate monthly utility bills
- Protect the app from unauthorized access
- Maintain and improve app functionality

### 4. Information Sharing

**We DO NOT share your personal information with any third parties**, except:
- **Firebase/Google Cloud Platform:** Data is stored on Firebase infrastructure (owned by Google), subject to [Google's Privacy Policy](https://policies.google.com/privacy).
- **Legal requirements:** If required by law, we may disclose information to authorized authorities.

**Important notes:**
- The app **DOES NOT use** any advertising, analytics, or user behavior tracking SDKs.
- Tenant information (names, phone numbers) that you enter into the app is stored in the developer's Firebase project and is not shared with third parties.
- When you share invoices via Zalo, that sharing is initiated by you and is subject to Zalo's policies.

### 5. Data Security

We implement reasonable security measures to protect your data:
- Passwords are encrypted by Firebase Authentication
- Data is transmitted over encrypted HTTPS connections
- Firebase App Check helps prevent unauthorized access to the database
- Firestore security rules are configured to allow only authenticated users to access their data

However, no method of electronic transmission or storage is 100% secure. We cannot guarantee absolute security.

### 6. Your Rights

You have the right to:
- **Access:** View your personal data within the app
- **Edit:** Update or modify information in the app
- **Delete:** Remove room, tenant, or invoice data at any time
- **Delete account:** Contact us to permanently delete your account and all associated data

### 7. Data Retention

Your data is stored on Firebase Firestore (Google Cloud Platform servers) and will be retained until:
- You actively delete data within the app
- You request account deletion
- The app is discontinued

### 8. Children

The Trolly app is not intended for individuals under 18 years of age. We do not knowingly collect personal information from children. If you discover that a child has provided personal information to us, please contact us so we can delete that information.

### 9. Policy Changes

We may update this Privacy Policy from time to time. We will notify you of any changes by posting the new policy in the app or via email. You should review this policy periodically.

### 10. Contact

If you have any questions about this Privacy Policy, please contact:

**Email:** craftzcatdev@gmail.com 
**Developer:** Hai Ng. / craftzcatdev

---

*This privacy policy is provided in both Vietnamese and English. In case of any discrepancy between the two versions, the Vietnamese version shall prevail.*
