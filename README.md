# راهنمای راه‌اندازی Titan Network

## 1. ثبت‌نام
ابتدا در سایت [Titan Network](https://test1.titannet.io/intiveRegister?code=JYSlEv) ثبت‌نام کنید.


## 2. دریافت کد هویت (Identity)
- به بخش **Console** بروید.
- سپس وارد **Node Management** شوید و روی دکمه ی **get Identity code** بزنید و کد را دریافت کنید.
- اگر چند سرور دارید، می‌توانید برای هر سرور یک کد جداگانه بگیرید.

## 3. اجرای اسکریپت
برای راه‌اندازی Titan Network روی سرور خود، این دستورات را وارد کنید:

```bash
wget -q https://raw.githubusercontent.com/0xs3nat0r/titan-network/refs/heads/main/titanbot.sh && chmod +x titanbot.sh && ./titanbot.sh
```
در انتها از شما کدی رو میخواد که از پنل گرفتید ، پس از وارد کردن کد و Enter زدن اسکریپت اجرا شده و از طریق [Dashboard](https://test1.titannet.io/newoverview/activationcodemanagement) میتونید نودی که اجرا کردین روی سرور رو مشاهده کنید.
