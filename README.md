GETTING SOMETHING RUN - BUILD A RAILS PROJECT
-------

1. Requirements:
	- Build a blog and let you create and publish articles
2. User stories:
	- As a admin of blog, I should be able to post and publish an article.
	- As a user/reader, I should be able to comment on a block.
	- ......
3. Create a blog application (note: introduce rails structure page 32)
	- `rails new blog`
	- `cd blog`
4. Create project db: `rake db:create`
5. Create article model: `rails g model article name:string body:text`
6. Add publised add to article table - create a migration: `rails g migration add_published_at_to_articles`
7. Create article controller: `rails g controller articles`
8. Use scaffold: `rails g scaffold Article name:string body:text`
9. Add more fields: `rails g migration <name>`
10. Add validation