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
