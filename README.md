# endpoint

# Show Login Page
#نمایش صفحه‌ی لاگین کاربر

GET: Core.saadifoundation.ir/login

--------------------------------------------------

# Send User Information
#ارسال اطلاعات کاربر برای لاگین

POST: core.saadifoundation.ir/login

Params: username (string), password (string)

--------------------------------------------------

# Logout
#خروج کاربر

POST: https://core.saadifoundation.ir/my-account/customer-logout

Params: username (string)

--------------------------------------------------

# User Registration
#ثبت نام کاربران

POST: core.saadifoundation.ir/register

Params: username (string), password (string), name (string), lastName (string), email(string), country(string), phone(Integer)

--------------------------------------------------

# Verify a User Registration
#تایید ثبت نام کاربر

POST: https://core.saadifoundation.ir/verify-registration

Params: verificationId (string)

--------------------------------------------------

# Resend a User Registration Verification Email
#ارسال مجدد ایمیل تایید

PUT: https://core.saadifoundation.ir/verify-registration?username={username}&email={email}

Params: username (string), email (string)

--------------------------------------------------

# Send Welcome Email
#ارسال ایمیل خوشامدگویی

GET: core.saadifoundation.ir/welcome
 
Params: email (string), subject (string), body (string)

--------------------------------------------------

# My Account
#حساب کاربری

GET: core.saadifoundation.ir/my-account

Params: username (string)

--------------------------------------------------

# Edit My Account
#ویرایش اطلاعات کاربری

PUT: core.saadifoundation.ir/my-account/edit-account/

Params: PreviousPassword (string), NewPassword (string), name (string), lastName (string), email(string), country(string), phone(Integer)

--------------------------------------------------

# Forgot Password
#فراموشی رمز عبور

POST: https://core.saadifoundation.ir/my-account/lost-password/

Params: username (string), email(string)

--------------------------------------------------

# Chat

# Send Message
#ارسال پیام

POST: https://core.saadifoundation.ir/message

Params: username (string), Message(string)

--------

# Recieve Message
#دریافت پیام

GET: https://core.saadifoundation.ir/message

Params: username (string), Message(string)

--------------------------------------------------

# Delete User
#حذف کاربر

DELETE: https://core.saadifoundation.ir/my-account/remove

Params: username (string)




