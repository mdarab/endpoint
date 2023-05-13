# endpoint

# Show Login Page
#نمایش صفحه‌ی لاگین کاربر

GET: Core.saadifoundation.ir/login

# Send User Information
#ارسال اطلاعات کاربر برای لاگین

POST: core.saadifoundation.ir/login
Params: username (string), password (string)

--------------------------------------------------

# List Posts
#نمایش پست ها

GET /wp/v2/posts
Params: context (view, embed, edit), page, per_page, search	(string), after, modified_after, author, author_exclude, before, modified_before, exclude, include, offset, order(asc, desc), orderby(author, date, id, include, modified, parent, relevance, slug, include_slugs, title), search_columns, slug, status, tax_relation, categories, categories_exclude, tags, tags_exclude, sticky

# Create a Post
#ایجاد پست

GET /wp/v2/posts/<id>

# Update a Post
  #آپدیت یک پست
  
  POST /wp/v2/posts/<id>
  
 # Delete a Post
  #حذف یک پست
  
  DELETE /wp/v2/posts/<id>
  
  ------------------------------------------------
  
# List Post Revisions
  # نمایش ویرایش های انجام شده برای یک پست
  
 GET /wp/v2/posts/<parent>/revisions
  
  -----------------------------------------------
  
  # List Categories
  #نمایش دسته بندی ها
  
  GET /wp/v2/categories
  
  -----------------------------------------------
  
  # List Tags
  #نمایش برچسب ها
  
  GET /wp/v2/tags
  
  ------------------------------------------------
  
  # List Pages
  #نمایش برگه ها
  
  
  
  GET /wp/v2/pages
  
  -------------------------------------------------
  
  # List Page Revisions
  #نمایش ویرایش های برگه 
  
  GET /wp/v2/pages/<parent>/revisions
  
  -------------------------------------------------
  
  # List Comments
  #نمایش نظرات
  
  GET /wp/v2/comments
  
  ------------------------------------------------
  
 # Retrieve a Taxonomy
  #بازیابی یک طبقه بندی
  
  GET /wp/v2/taxonomies
  
  ------------------------------------------------
  
  # List Media
  #نمایش رسانه
  
  GET /wp/v2/media
  
  -------------------------------------------------
  
  # List Users
  #نمایش کاربران
  
  GET /wp/v2/users
  
  -----------------------------------------------
  
  # Retrieve a Type
  #بازیابی یک نوع پست
  
  GET /wp/v2/types
  
  ----------------------------------------------
  
  # Retrieve a Status
  #بازیابی وضعیت های پست
  
  
GET /wp/v2/statuses
  
  -----------------------------------------------
  
  # Retrieve a Site Setting
  #بازیابی تنظیمات سایت
  
  GET /wp/v2/settings
  
  ----------------------------------------------
  
  # Retrieve a Theme
  #بازیابی یک تم
  
  GET /wp/v2/themes

---------------------------------------------------
  
  # List Search Results
  #نمایش نتایج جستجو
  
  GET /wp/v2/search
  
  -------------------------------------------------
  
  # Retrieve a Block Type
  #بازیابی نوع بلاک
  
  GET /wp/v2/block-types
  
  -------------------------------------------------
  
  # List Editor Blocks
  #نمایش بلاک های ویرایشگر
  
  GET /wp/v2/blocks
  
  ------------------------------------------------
  
  # List Block Revisions 
  #نمایش ویرایش های یک بلاک
  
  GET /wp/v2/blocks/<parent>/revisions
  
  ------------------------------------------------
  
  # Create a Rendered Block
 #ساخت یک بلاک رندرشده
  
  POST /wp/v2/block-renderer/<name>
  
  -------------------------------------------------
  
  # List Block Directory Items
  #نمایش آیتم های دایرکتوری بلاک
  
  GET /wp/v2/block-directory/search
  
  -------------------------------------------------
  
  # Retrieve a Plugin
  #بازیابی یک پلاگین
  
  GET /wp/v2/plugins
  
 
