# Laravel SMS.ir Service

سرویس پیامک ساده برای پروژه‌های لاراولی که با API رسمی سایت SMS.ir کار می‌کند.

## نصب

```bash
git clone https://github.com/atefehesmaili/laravel-sms-service.git
cd laravel-sms-service
composer install
cp .env.example .env
php artisan key:generate


در پروژه به صورت زیر استفاده شود 
        $sms = new mobileSmsService();
        $sms->sendSms($mobile, $message);
