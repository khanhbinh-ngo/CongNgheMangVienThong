# Công nghệ GSM
Global system for mobile communication - hỗ trợ cho các thể loại gọi điện thoại các thứ

Cấu trúc của GSM gồm có 3 thành phần 
    Network switching subsystem (nss)
        MSCL
            - THành phần chính, đóng vai trò điều khiển chính các hệ thống BSC khác, đồng thời định tuyến các cuộc gọi vào/ra
        VLR
            - là cơ sở dữ liệu chứa thông tin tạm thời về thuê bao để cung cấp cho msc.
            - nếu thuê bao yeu cầu trong vùng phục vụ của msc thì vlr tích hợp với msc đó yêu cầu dữ liệu thuê bao từ hlr
            - cs tính tạm thời
            - thuwognf xuyên cập nhật thông tin từ vị trí
        HLR 
            - là cơ sở dữ liệu chứa các dịch vụ thuê bao
            - để có thể cung cấp các thông tin cho các thuê bao
        AuC
            - là cơ sở dl khóa để nhận dạng thông tin xác thực thuê bao
        SMSC
            - 
    base station subsystem (bss) 
        BTS
            - trạm thu phát sóng
        BSC
            - bộ điều khiển trạm gốc
            - chuyển voice 13kbps sang kênh 64 kbps dùng các gói pstn hoặc isdn
            - thiết lập các kênh báo hiệu cho các cuộc gọi đến hoặc tin nhắn
            - chuyển đổi tần số hoặc đồng bộ hóa thời gian tần sốc
            - quản lý thời gian và độ trễ của kết nối 
    mobile station (ms)

- Downlink và uplink
sử dụng khác nhau về các băng tần
sử dụng các dải tần số
    + downlink là từ 890 đến 915
    + uplink là từ 935 đến 960
    nói chung là ddeeer quản lý cần có các tổ chức cell một cách hiệu quả (AD hoc)
- Cấu trúc này yêu cầu mỗi node cần điều khiển để có thể dảm bảo công suất điện của cell này không ảnh hưởng lắm đến các cell còn lại trong hệ thống

Phuowgn thức truy cập 
kết hợp tdma/dfma như là phuwogn pháp để phân chia băng thông giữa ng dùng
    - dfma là chia tần số  thành 125 sóng mang có băng thông 200khz
    - tdma là chia tần số thành 8 khe dùng chung truyền và nhận tín hiệu

quy trình vận hành 
- khi thuê bao di động gọi đến pstn và từ khi pstn gọi một thuê bao di động


# Công nghệ GPRS và EDGE
# Công nghệ UMTS và HSPA 
# CÔng nghệ LTE và LTE - Advanced