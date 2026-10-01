# QP Terminal

Phần mềm nghiên cứu chỉ báo và chiến lược giao dịch cho thị trường Việt Nam và tiền mã hoá, chạy trên máy tính Windows của bạn. Nhà phát hành: **Quant Percent** ([quantpercent.com](https://quantpercent.com)).

*English below.*

## Tải về

**[Tải QP Terminal cho Windows](https://github.com/namngyh/QP-TERMINAL-OFFICIAL/releases/latest/download/QP-Terminal-setup.exe)**

Hoặc vào mục [Releases](https://github.com/namngyh/QP-TERMINAL-OFFICIAL/releases) để xem mọi phiên bản và ghi chú thay đổi.

## Yêu cầu

- Windows 10 hoặc Windows 11, 64-bit.
- Khoảng 600 MB ổ đĩa trống.
- Kết nối Internet: để kích hoạt bản quyền và tải dữ liệu thị trường. Không cần VPN.
- Microsoft Edge WebView2. Windows 11 có sẵn; Windows 10 thường cũng đã có qua Windows Update.
- Một **mã bản quyền** dạng `QP-XXXXX-XXXXX-XXXXX-XXXXX`, nhận từ Quant Percent.

## Cài đặt

1. Tải `QP-Terminal-setup.exe` và mở nó.
2. Windows có thể hiện "Windows protected your PC", vì bộ cài chưa có chữ ký số. Bấm **More info**, rồi **Run anyway**.
3. Chọn ngôn ngữ, đọc điều khoản sử dụng, tích ô chấp thuận, rồi bấm **Cài đặt**.
   - Không cần quyền quản trị. App được cài vào `%LOCALAPPDATA%\Programs\QuantPercent`.
4. Mở **QP Terminal** từ Start Menu.

Nếu máy bật **Smart App Control**, Windows sẽ chặn hẳn app chưa có chữ ký số. Hiện chưa có cách chạy trên máy bật tính năng này.

## Kích hoạt

Lần đầu mở, app hiện màn hình nhập mã bản quyền.

1. Dán mã bản quyền vào ô, rồi bấm **Kích hoạt**.
2. Mỗi mã dùng được trên **tối đa 2 máy**. Kích hoạt lại trên cùng một máy không tốn thêm lượt.
3. Muốn chuyển sang máy khác: mở app, bấm **Ctrl+K**, chọn **Bản quyền**, rồi bấm **Gỡ máy này** để trả lại lượt.

App kiểm tra bản quyền qua Internet mỗi 12 giờ. Mất mạng thì vẫn dùng được tối đa **3 ngày**. Sau đó app khoá lại cho tới khi kết nối lại và bấm **Kiểm tra lại**.

## Dữ liệu của bạn

Cài đặt, bố cục, phiên giao dịch giả lập, cảnh báo và plugin bạn viết được lưu ở `%APPDATA%\QuantPercent`, tách khỏi thư mục cài.

- Cài bản mới đè lên bản cũ thì giữ nguyên dữ liệu.
- Khi gỡ cài, bạn được hỏi có xoá dữ liệu không. Nếu chọn xoá, dữ liệu được chuyển vào **Thùng rác**, không xoá hẳn.

## Gỡ cài đặt

Vào Settings, chọn Apps, tìm **QP Terminal**, rồi bấm Uninstall.

## Lưu ý quan trọng

QP Terminal là công cụ nghiên cứu, **không phải lời khuyên đầu tư**. Kết quả backtest và mô phỏng dựa trên dữ liệu quá khứ và các giả định về phí, trượt giá, khớp lệnh; chúng không bảo đảm kết quả trong tương lai. Bản đầy đủ của điều khoản sử dụng: [TERMS.vi.txt](TERMS.vi.txt).

## Hỗ trợ

Mua mã bản quyền, gia hạn, báo lỗi: [quantpercent.com](https://quantpercent.com).

---

# QP Terminal (English)

A Windows desktop application for researching trading indicators and strategies on Vietnamese markets and crypto. Published by **Quant Percent** ([quantpercent.com](https://quantpercent.com)).

## Download

**[Download QP Terminal for Windows](https://github.com/namngyh/QP-TERMINAL-OFFICIAL/releases/latest/download/QP-Terminal-setup.exe)**

All versions and release notes are under [Releases](https://github.com/namngyh/QP-TERMINAL-OFFICIAL/releases).

## Requirements

- Windows 10 or 11, 64-bit.
- About 600 MB of free disk space.
- An Internet connection, to activate the licence and load market data. No VPN is needed.
- Microsoft Edge WebView2. It ships with Windows 11 and usually reaches Windows 10 through Windows Update.
- A **licence key** in the form `QP-XXXXX-XXXXX-XXXXX-XXXXX`, issued by Quant Percent.

## Install

1. Download `QP-Terminal-setup.exe` and open it.
2. Windows may show "Windows protected your PC", because the installer is not code-signed yet. Click **More info**, then **Run anyway**.
3. Choose a language, read and accept the terms, then click **Install**.
   - No administrator rights are needed. The app installs to `%LOCALAPPDATA%\Programs\QuantPercent`.
4. Start **QP Terminal** from the Start Menu.

If **Smart App Control** is on, Windows blocks unsigned apps outright. There is currently no way to run QP Terminal on such a machine.

## Activate

The first time the app starts, it asks for your licence key.

1. Paste the key, then click **Activate**.
2. Each key works on **up to 2 computers**. Activating again on the same computer does not use another slot.
3. To move to another computer: open the app, press **Ctrl+K**, choose **Licence**, then click **Release this machine** to free its slot.

The app checks the licence online every 12 hours. It keeps working offline for up to **3 days**. After that it locks until you are back online and click **Check again**.

## Your data

Settings, layouts, paper-trading sessions, alerts and your own plugins are stored in `%APPDATA%\QuantPercent`, separate from the install folder.

- Installing a new version over an old one keeps your data.
- When you uninstall, you are asked whether to remove your data. If you choose to remove it, it goes to the **Recycle Bin** and is not deleted outright.

## Uninstall

Open Settings, go to Apps, find **QP Terminal**, then click Uninstall.

## Important

QP Terminal is a research tool, **not investment advice**. Backtests and simulations rely on past data and on assumptions about fees, slippage and order fills; they do not guarantee future results. Full terms of use: [TERMS.en.txt](TERMS.en.txt).

## Support

Licence purchase, renewals and bug reports: [quantpercent.com](https://quantpercent.com).
