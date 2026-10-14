# Bai tập : Tìm lỗi "ERROR" rồi in vào tệp .txt
**- Bước 1: truy cập vào file bằng lệnh gci:**
```powershell
gci -recurse HeThong_web_logs
```
**- Bước 2 : lọc các từ "ERROR"**
```powershell
gci -recurse HeThong_web_logs | select-string "ERROR"
```
**- Bước 3:In vào file txt**
```powershell
gci -recurse HeThong_web_logs | select-string "ERROR">>loi.txt
```# DEMO
# Demo
