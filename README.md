# Forum App
This forum app is "remake" (from scratch) of one of our team projects in Factoria F5 Web Dev Bootcamp. Stack: php, laravel, MySQL &amp; VueJS

## Usage
In order to get the code running on your machine you should:
1. **Clone this repo**
2. **Install dependencies** <br/>
 ``` composer install ``` <br/>
 ``` npm install ``` <br/>
3. **Compile assets** <br/>
 ``` npm run watch ``` <br/>
4. **Run migartions** <br/>
 ``` php artisan migrate ``` <br/>
*If you want to run the database seeders to have some sample data, run: <br/>
 ``` php artisan migrate --seed ``` <br/>
 **I case of adding new database tables or modifying database schema (in dev env), run: <br/>
  ``` php artisan migrate:fresh ``` and add the flag ``` --seed ``` to fill the tables <br/>
5.**Start server** <br/>
 ``` php artisan serve ```

## About Forum App Project
In the original project we were asked to build an Alumni platform where all ex-students could share knowledge, job offers, projects, tech interviews/tests. Each sud-team in the Bootcamp has to build a small part of the project. My team assignment was a forum. You can check the original project GitHub repo [here](https://github.com/CodersFactoria2020/Alumni)

### Requirements
##### MVP
* The Forum is only accessible for students. You must be logged in to see the posts.
* A post can have comments.
* A post can have a tag to categorize the topic it talks about.
* Only the post/comment owner can delete and update his own post
* Twitter-like views. Implement an infinite scroll post list.
##### Extra Features
* Posts and Comments can have likes.
* You can share other user content as a post (like re-tweet feature)