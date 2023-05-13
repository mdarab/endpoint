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
  
  
 
