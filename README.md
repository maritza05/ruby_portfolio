# Planning our application
1. Answer Questions
	- What are we building?
	- Who are we building it for?
	- What features do we need to have?
2. User Stories
3. Model our Data
4. Think through the pages we need in our app 

## Questions

1. What are we building? We are building a personal site. A place where we can blog, share examples 
of our work, and have people contact us.
2. Who are we building it for? We are building it for ourselves, but also the community. Sharing
what we are learning by blogging is a great way to learn for ourselves, but we teach others in the 
process. Show potential employers that we know what we are doing.
3. What features do we want to have? 
	- Posts
		- Create / Edit / Destroy
		- Markdown
		- Syntax highlighting
		- Comments (Disquis)
	- Projects
		- Create / Edit / Destroy
	- Contact
		-Contact form 
		-Sendgrid
	- User (Devise)

## User Stories 

	1. As a user, I want to be able to create posts so that I can share what I am learning on my blog.
	2. As a user. I want to be able to edit & destroy posts, so that I can manage my blog.
	3. As a user, I want to be able to write posts in markdown format so that it's easy for me to write posts.
	4. As a user, I want to be able to highlight the various syntax of code blocks that I share on my blog.
	5. As a user, I want to show the visitors and potential employers examples of my work, or stuff I've built.
	6. As a user, I want to be able to have visitors contact me through a form on my site.
	7. As a user, I want visitors to be able to leave comments on my posts.

## Modeling our Data 
	
	1. Post
		* title:string
		* content:string 
	2. Project
		* title:string
		* description:text 
		* link:string
	3. User

## Think through the pages that need our app 
	- Home
	- Posts#index 
	- Posts#Show
	- Projects#index 
	- Projects#show 
	- Contact 
