# Hardware driver

**1. Không truy cập được vào thiết bị usb khi không ở trong quyền root.**

Cần add user vào 2 group plugdev và dialout

```
sudo adduser -aG $USER plugdev
sudo adduser -aG $USER dialout
```
