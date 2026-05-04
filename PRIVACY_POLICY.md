# Chính Sách Bảo Mật / Privacy Policy

**Ngày có hiệu lực / Effective Date:** 04 May 2026

---

## Tiếng Việt

### 1. Giới Thiệu

**Trolly là công cụ nội bộ riêng tư dành cho gia đình nhà phát triển — KHÔNG phải ứng dụng công cộng.**

Trolly là ứng dụng iOS quản lý nhà trọ được phát triển bởi Hai Ng. (craftzcatdev) để sử dụng nội bộ trong gia đình. Ứng dụng giúp quản lý phòng cho thuê, ghi chỉ số điện nước hàng tháng, tính toán hóa đơn tiện ích, quét và lưu trữ thông tin Căn cước công dân (CCCD) của người thuê theo quy định pháp luật Việt Nam, và chia sẻ hóa đơn với người thuê qua Zalo.

**Ứng dụng này KHÔNG mở cho công chúng đăng ký.** Chỉ các thành viên gia đình của nhà phát triển (khoảng 5 người dùng) được cấp quyền truy cập.

### 2. Ai Có Thể Sử Dụng Ứng Dụng Này

Trolly là công cụ riêng tư dành cho gia đình nhà phát triển. **KHÔNG có chức năng đăng ký tài khoản trong ứng dụng.**

- Tài khoản quản trị viên được tạo thủ công bởi nhà phát triển trong Firebase Console
- Chỉ các thành viên gia đình được nhà phát triển cấp quyền mới có thể sử dụng
- Ứng dụng không cho phép người dùng tự đăng ký hoặc tạo tài khoản mới

Nếu bạn cần tài khoản hoặc muốn xóa tài khoản hiện có, vui lòng liên hệ trực tiếp với nhà phát triển tại **craftzcatdev@gmail.com**.

### 3. Thông Tin Chúng Tôi Thu Thập

#### 3.1 Thông Tin Tài Khoản Quản Trị Viên
- **Email và mật khẩu:** Được lưu trữ qua Firebase Authentication (mật khẩu được mã hóa)
- **User ID (UID):** Mã định danh duy nhất do Firebase tự động tạo

#### 3.2 Thông Tin Phòng Trọ
- Số phòng, giá thuê, diện tích, trạng thái phòng
- Danh sách ID người thuê đang ở

#### 3.3 Thông Tin Người Thuê (Tenant)
Theo quy định pháp luật Việt Nam (Thông tư 17/2018/TT-BCA và các quy định liên quan), chủ nhà trọ **bắt buộc phải thu thập và lưu giữ thông tin giấy tờ tùy thân của người thuê**. Ứng dụng thu thập các thông tin sau:

- **Họ và tên** (fullName)
- **Số Căn cước công dân (CCCD) / Chứng minh nhân dân (CMND)** (personalIdentificationNumber)
- **Ngày sinh** (dob)
- **Giới tính** (sex)
- **Nơi thường trú** (placeOfResidence)
- **Nơi sinh** (placeOfBirth)
- **Quốc tịch** (nationality)
- **Ngày cấp CCCD** (dateOfIssue)
- **Ngày hết hạn CCCD** (dateOfExpiry)
- **Nơi cấp CCCD** (placeOfIssue)
- **Ngày nhận phòng** (checkInDate)
- **Số tiền đặt cọc** (depositAmount)
- **Thời gian tạo/cập nhật/xóa bản ghi** (createdAt, updatedAt, deletedAt)

**Tính năng quét CCCD:**
- Ứng dụng sử dụng camera và/hoặc NFC để quét thông tin từ thẻ CCCD
- Chỉ các trường văn bản được trích xuất và lưu trữ trong Firestore
- **KHÔNG lưu trữ hình ảnh CCCD**

#### 3.4 Dữ Liệu Hóa Đơn Hàng Tháng
- Chỉ số điện, chỉ số nước
- Tính toán tiền điện, tiền nước, tiền phòng
- Số người ở trong phòng (numberOfPerson)

#### 3.5 Thông Tin Thiết Bị và Bảo Mật
- **Firebase App Check / App Attest:** Thu thập mã định danh thiết bị tạm thời để xác minh yêu cầu đến từ ứng dụng chính thức
- **Dữ liệu chẩn đoán Firebase SDK:** Loại thiết bị, phiên bản iOS, thông tin lỗi (crash data) — được Firebase SDK tự động thu thập
- **KHÔNG sử dụng Firebase Analytics, Firebase Crashlytics, hoặc bất kỳ SDK theo dõi/quảng cáo nào**

### 4. Mục Đích Sử Dụng Thông Tin

Chúng tôi sử dụng thông tin thu thập được **chỉ** cho các mục đích sau:

1. **Tuân thủ pháp luật Việt Nam:** Lưu trữ thông tin CCCD của người thuê theo quy định của Thông tư 17/2018/TT-BCA về quản lý cư trú tạm trú
2. **Quản lý nhà trọ:** Theo dõi phòng trống/đã thuê, thông tin người thuê, ngày nhận phòng, tiền đặt cọc
3. **Tính toán hóa đơn:** Ghi chỉ số điện nước hàng tháng và tính toán chi phí
4. **Xác thực người dùng:** Đăng nhập tài khoản quản trị viên
5. **Bảo mật ứng dụng:** Ngăn chặn truy cập trái phép thông qua Firebase App Check

**Dữ liệu KHÔNG được sử dụng cho:**
- Quảng cáo
- Phân tích hành vi người dùng
- Chia sẻ với bên thứ ba (trừ trường hợp pháp luật yêu cầu)
- Bất kỳ mục đích nào khác ngoài quản lý nhà trọ và tuân thủ pháp luật

### 5. Chia Sẻ Thông Tin

**Chúng tôi KHÔNG chia sẻ thông tin cá nhân với bất kỳ bên thứ ba nào**, ngoại trừ:

#### 5.1 Firebase / Google Cloud Platform
- Dữ liệu được lưu trữ trên Firebase Firestore (cơ sở hạ tầng của Google)
- Tuân theo [Chính sách bảo mật của Google](https://policies.google.com/privacy)
- Firebase chỉ đóng vai trò nhà cung cấp hạ tầng — Google không truy cập hoặc sử dụng dữ liệu người thuê của bạn

#### 5.2 Cơ Quan Có Thẩm Quyền Tại Việt Nam
- Nếu luật pháp Việt Nam yêu cầu, chúng tôi có thể tiết lộ thông tin cho cơ quan công an, chính quyền địa phương, hoặc cơ quan có thẩm quyền khác
- Điều này bao gồm việc cung cấp thông tin tạm trú/tạm vắng theo yêu cầu của cơ quan quản lý

#### 5.3 Chia Sẻ Hóa Đơn Qua Zalo
- Khi bạn chủ động chia sẻ hóa đơn với người thuê qua Zalo, hành động đó do bạn khởi tạo
- Việc chia sẻ tuân theo chính sách riêng của Zalo
- Chúng tôi không kiểm soát cách Zalo xử lý dữ liệu sau khi bạn chia sẻ

**Lưu ý quan trọng:**
- Ứng dụng **KHÔNG sử dụng** bất kỳ SDK quảng cáo, phân tích, hoặc theo dõi hành vi người dùng nào
- Không có tích hợp bên thứ ba nào khác ngoài Firebase

### 6. Bảo Mật Dữ Liệu

Chúng tôi thực hiện các biện pháp bảo mật hợp lý:

- **Mã hóa truyền tải:** Tất cả dữ liệu được truyền qua HTTPS
- **Mã hóa mật khẩu:** Firebase Authentication mã hóa mật khẩu
- **Quy tắc bảo mật Firestore:** Chỉ người dùng đã xác thực mới có thể truy cập dữ liệu
- **Firebase App Check:** Ngăn chặn truy cập trái phép từ ứng dụng giả mạo
- **Không lưu hình ảnh CCCD:** Chỉ lưu trữ các trường văn bản được trích xuất

Tuy nhiên, không có phương thức truyền tải hoặc lưu trữ điện tử nào là an toàn tuyệt đối 100%.

### 7. Quyền Của Bạn

#### 7.1 Quyền Truy Cập và Chỉnh Sửa
- Bạn có thể xem và chỉnh sửa dữ liệu phòng trọ, người thuê, và hóa đơn trong ứng dụng bất kỳ lúc nào
- Bạn có thể xóa bản ghi người thuê hoặc hóa đơn trong ứng dụng

#### 7.2 Xóa Tài Khoản (Apple App Store Guideline 5.1.1(v))
**Vì Trolly là công cụ nội bộ riêng tư dành cho gia đình nhà phát triển, việc quản lý tài khoản được thực hiện thủ công bởi nhà phát triển.**

- **KHÔNG có chức năng tự xóa tài khoản trong ứng dụng**
- Tài khoản được tạo và xóa thủ công bởi nhà phát triển trong Firebase Console
- Nếu bạn muốn xóa tài khoản và tất cả dữ liệu liên quan, vui lòng liên hệ **craftzcatdev@gmail.com**
- Nhà phát triển cam kết xóa tài khoản và dữ liệu trong vòng 30 ngày kể từ khi nhận yêu cầu
- Tài khoản sẽ được xóa tự động khi không còn sử dụng hoặc khi ứng dụng ngừng hoạt động

**Lý do không có chức năng tự xóa tài khoản:**
- Ứng dụng chỉ có ~5 người dùng (thành viên gia đình)
- Không có quy trình đăng ký công khai
- Quản lý tài khoản được thực hiện trực tiếp giữa nhà phát triển và người dùng

### 8. Lưu Trữ Dữ Liệu

Dữ liệu được lưu trữ trên Firebase Firestore (Google Cloud Platform) và sẽ được giữ lại cho đến khi:

- Bạn chủ động xóa dữ liệu trong ứng dụng
- Bạn yêu cầu xóa tài khoản qua email
- Nhà phát triển xóa tài khoản khi không còn sử dụng
- Ứng dụng ngừng hoạt động

**Thời gian lưu trữ thông tin CCCD:**
- Theo quy định pháp luật Việt Nam, thông tin tạm trú phải được lưu giữ trong thời gian người thuê còn ở và có thể được lưu trữ thêm để phục vụ kiểm tra của cơ quan có thẩm quyền
- Dữ liệu sẽ được xóa khi không còn cần thiết cho mục đích quản lý hoặc tuân thủ pháp luật

### 9. Trẻ Em

Ứng dụng Trolly không dành cho người dưới 18 tuổi. Chúng tôi không cố ý thu thập thông tin cá nhân từ trẻ em dưới 18 tuổi trong vai trò người dùng ứng dụng.

**Lưu ý:** Thông tin người thuê (bao gồm cả người thuê dưới 18 tuổi) được chủ nhà trọ nhập vào là để tuân thủ quy định pháp luật về quản lý tạm trú, không phải do trẻ em tự cung cấp.

### 10. Thay Đổi Chính Sách

Chúng tôi có thể cập nhật Chính sách bảo mật này theo thời gian. Mọi thay đổi sẽ được thông báo qua:
- Email đến các tài khoản quản trị viên
- Thông báo trong ứng dụng
- Cập nhật ngày hiệu lực ở đầu tài liệu này

Bạn nên xem lại chính sách này định kỳ.

### 11. Liên Hệ

Nếu bạn có bất kỳ câu hỏi nào về Chính sách bảo mật này, muốn yêu cầu xóa tài khoản, hoặc cần hỗ trợ, vui lòng liên hệ:

**Email:** craftzcatdev@gmail.com  
**Nhà phát triển:** Hai Ng. / craftzcatdev

---

## English

### 1. Introduction

**Trolly is a private, family-only internal tool — NOT a public app.**

Trolly is an iOS rental property management app developed by Hai Ng. (craftzcatdev) for internal family use. The app helps manage rental rooms, record monthly electricity and water meter readings, calculate utility bills, scan and store tenant Citizen Identity Card (CCCD) information as required by Vietnamese law, and share invoices with tenants via Zalo.

**This app is NOT open to public registration.** Only the developer's family members (approximately 5 users) are granted access.

### 2. Who Can Use This App

Trolly is a private tool for the developer's family. **There is NO sign-up functionality in the app.**

- Admin accounts are created manually by the developer in Firebase Console
- Only family members authorized by the developer can use the app
- The app does not allow users to self-register or create new accounts

If you need an account or want to delete an existing account, please contact the developer directly at **craftzcatdev@gmail.com**.

### 3. Information We Collect

#### 3.1 Admin Account Information
- **Email and password:** Stored via Firebase Authentication (password is encrypted)
- **User ID (UID):** Unique identifier automatically generated by Firebase

#### 3.2 Room Information
- Room number, rental price, area, room status
- Array of tenant IDs currently occupying the room

#### 3.3 Tenant Information
Under Vietnamese law (Circular 17/2018/TT-BCA and related regulations), landlords are **legally required to collect and retain identity document information of tenants**. The app collects the following information:

- **Full name** (fullName)
- **Citizen Identity Card (CCCD) / National ID number** (personalIdentificationNumber)
- **Date of birth** (dob)
- **Gender** (sex)
- **Place of residence** (placeOfResidence)
- **Place of birth** (placeOfBirth)
- **Nationality** (nationality)
- **CCCD issue date** (dateOfIssue)
- **CCCD expiry date** (dateOfExpiry)
- **CCCD issuing authority** (placeOfIssue)
- **Check-in date** (checkInDate)
- **Deposit amount** (depositAmount)
- **Record creation/update/deletion timestamps** (createdAt, updatedAt, deletedAt)

**CCCD Scanning Feature:**
- The app uses camera and/or NFC to scan information from CCCD cards
- Only text fields are extracted and stored in Firestore
- **NO CCCD images are stored**

#### 3.4 Monthly Billing Data
- Electricity meter readings, water meter readings
- Calculated electricity, water, and rent charges
- Number of occupants (numberOfPerson)

#### 3.5 Device and Security Information
- **Firebase App Check / App Attest:** Collects temporary device identifiers to verify requests come from the legitimate app
- **Firebase SDK diagnostic data:** Device type, iOS version, crash information — automatically collected by Firebase SDK
- **NO Firebase Analytics, Firebase Crashlytics, or any tracking/advertising SDKs are used**

### 4. How We Use Information

We use the collected information **only** for the following purposes:

1. **Vietnamese legal compliance:** Store tenant CCCD information as required by Circular 17/2018/TT-BCA on temporary residence management
2. **Property management:** Track vacant/occupied rooms, tenant information, check-in dates, deposits
3. **Billing calculation:** Record monthly utility meter readings and calculate charges
4. **User authentication:** Admin account login
5. **App security:** Prevent unauthorized access through Firebase App Check

**Data is NOT used for:**
- Advertising
- User behavior analytics
- Sharing with third parties (except when legally required)
- Any purpose other than property management and legal compliance

### 5. Information Sharing

**We DO NOT share personal information with any third parties**, except:

#### 5.1 Firebase / Google Cloud Platform
- Data is stored on Firebase Firestore (Google's infrastructure)
- Subject to [Google's Privacy Policy](https://policies.google.com/privacy)
- Firebase only serves as infrastructure provider — Google does not access or use your tenant data

#### 5.2 Vietnamese Competent Authorities
- If required by Vietnamese law, we may disclose information to police, local authorities, or other competent authorities
- This includes providing temporary residence information as requested by regulatory agencies

#### 5.3 Invoice Sharing via Zalo
- When you actively share invoices with tenants via Zalo, that action is initiated by you
- Sharing is subject to Zalo's own policies
- We do not control how Zalo processes data after you share it

**Important notes:**
- The app **DOES NOT use** any advertising, analytics, or user behavior tracking SDKs
- There are no third-party integrations other than Firebase

### 6. Data Security

We implement reasonable security measures:

- **Transmission encryption:** All data is transmitted over HTTPS
- **Password encryption:** Firebase Authentication encrypts passwords
- **Firestore security rules:** Only authenticated users can access data
- **Firebase App Check:** Prevents unauthorized access from fake apps
- **No CCCD images stored:** Only extracted text fields are stored

However, no method of electronic transmission or storage is 100% secure.

### 7. Your Rights

#### 7.1 Access and Edit Rights
- You can view and edit room, tenant, and invoice data in the app at any time
- You can delete tenant records or invoices within the app

#### 7.2 Account Deletion (Apple App Store Guideline 5.1.1(v))
**Because Trolly is a private internal tool for the developer's family, account management is performed manually by the developer.**

- **There is NO self-service account deletion feature in the app**
- Accounts are created and deleted manually by the developer in Firebase Console
- If you want to delete your account and all associated data, please contact **craftzcatdev@gmail.com**
- The developer commits to deleting accounts and data within 30 days of receiving the request
- Accounts will be automatically deleted when no longer in use or when the app is discontinued

**Why there is no self-service account deletion:**
- The app has only ~5 users (family members)
- There is no public registration process
- Account management is handled directly between the developer and users

### 8. Data Retention

Data is stored on Firebase Firestore (Google Cloud Platform) and will be retained until:

- You actively delete data within the app
- You request account deletion via email
- The developer deletes the account when no longer in use
- The app is discontinued

**CCCD information retention period:**
- Under Vietnamese law, temporary residence information must be retained while the tenant is residing and may be stored longer to serve inspections by competent authorities
- Data will be deleted when no longer necessary for management purposes or legal compliance

### 9. Children

The Trolly app is not intended for individuals under 18 years of age. We do not knowingly collect personal information from children under 18 in their role as app users.

**Note:** Tenant information (including tenants under 18) entered by landlords is for compliance with temporary residence management regulations, not provided by children themselves.

### 10. Policy Changes

We may update this Privacy Policy from time to time. Any changes will be communicated via:
- Email to admin accounts
- In-app notifications
- Updated effective date at the top of this document

You should review this policy periodically.

### 11. Contact

If you have any questions about this Privacy Policy, want to request account deletion, or need support, please contact:

**Email:** craftzcatdev@gmail.com  
**Developer:** Hai Ng. / craftzcatdev

---

## App Privacy Nutrition Label (for App Store Connect)

**Data Types Collected:**

- **Contact Info:** Name, Phone Number (tenant data entered by admin)
- **Sensitive Info:** Government ID Number (CCCD/CMND), Date of Birth, Gender, Place of Residence, Place of Birth, Nationality, ID Issue/Expiry Dates, Issuing Authority
- **Financial Info:** Rent amount, deposit amount, utility charges
- **Identifiers:** User ID (Firebase UID), Device ID (App Attest temporary identifier)
- **Usage Data:** Crash data and diagnostics (Firebase SDK auto-collection)

**Data Use:**
- App Functionality (property management, legal compliance)
- Product Personalization (user authentication)

**Data Linked to User:**
- All tenant data, room data, and billing data are linked to the admin user account

**Third Parties with Access:**
- Firebase/Google Cloud Platform (infrastructure provider only)

---

*This privacy policy is provided in both Vietnamese and English. In case of any discrepancy between the two versions, the Vietnamese version shall prevail.*
