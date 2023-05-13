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


