# test.github.io
### script(code) to send messages to mail by php deployed application.

### First, let’s discuss why developers choose PHP for a project. The language allows programmers to get started quickly, it’s well-documented and mature, and there are tons of free resources out there already. Meanwhile, some of the weaknesses that people have pointed out in PHP — including performance — have been greatly improved in version 7, and as Keith Adams, Chief Architect at Slack, points out: “PHP gets several things very deeply, and uniquely, right.”

### Because one of PHP’s strengths is its ease of use, I would argue that deploying PHP should be easy as well. In this article, I’m going to offer an overview of the tools and patterns used for setting up modern, scalable, efficient PHP applications on the web. Along the way, I hope to introduce you to some alternatives for each step so you can craft your own unique PHP development environment that has the best balance of simplicity and scalability for your project.

### Once your application meets the following requirements, you’re ready to get started with the rest of this guide:

1-The application’s database is manageable independent of the application. Usually this requires an ORM like Doctrine or Laravel’s Eloquent.
2-The application loads server and environment-specific variables from a .env file.
3-Dependencies are managed using Composer.
4-The application has unit tests (and hopefully integration and acceptance tests too) using PHPUnit.
5-Changes are tracked via version control. I’m going to assume git for the rest of this guide.
