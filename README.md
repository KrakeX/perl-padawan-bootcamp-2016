# Perl Padawan Camp 2016

Please, use this repository as a base for you training phase. The idea is to
fork this project so everyone use the same folder structure for the
exercises.

It's extremelly important to keep the key points easy to be verified by
the reviewers, so **don't mix the key points with the rest of the
exercises**

# Material

#PERL Padawan Camp

###Are you ready?
  
####Index

1. [Objective](#objective)

2. [Who Should Attend](#who-should-attend)

3. [Duration](#duration)

4. [Technical Assistance](#technical-assistance)

5. [Performance Measurement](#performance-measurement)

6. [Handling advanced Developers](#handling-advanced-developers)

7. [Materials](#materials)

8. [General Guidelines](#general-guidelines)

9. [Learning Days](#learning-days)

    * [Topic 0: Introduction to Object Oriented Programming Concepts (OOP)](#topic-0-introduction-to-object-oriented-programming-concepts-2-days)

    * [Topic 1: Maven](#topic-1-maven-1-day)

    * [Topic 2: Test Driven Development](#topic-2-test-driven-development-2-days)

    * [Topic 3: Services](#topic-3-services-2-days)

    * [Topic 4: SQL - MySql](#topic-4-sql---mysql-2-days)

    * [Topic 5: NoSQL - MongoDB](#topic-5-nosql---mongodb-2-days)
    
    * [Topic 6: Spring Core & REST](#topic-5-spring-core--rest-3-days)

10. [Your First Project Starts Now!](#your-first-project-starts-now)

###Objective

This course teaches a view of the basics of modern Perl development with a pinch of legacy application migration.

→ [index](#index)

###Who Should Attend

The training will start at a low level and does not require in depth knowledge of the platform in question. Desirable participant profile: trainees and outside Globant candidates. A basic knowledge on OOP is desired. Javascript, Node.js Express, Python, PHP and Java JAX-WS profiles have shown lesser side effects.

→ [index](#index)

###Duration

Four weeks total.

Three weeks for guided learning and one week for app development. 

→ [index](#index)

###Technical Assistance

You can contact other Perl Padawans or any available tutor if you need technical assistance. Two chat rooms will be created. One chat room for force-sensitive Perl Padawans to interact and a second one for Perl Padawans and Perl Jedi Masters alike where doubts and queries will be answered.

###Performance Measurement

1. Peer code review after each practice.

2. Checkpoint completion after Learning stage with your assigned tutor.

3. Each practice level of success is measured as a sum of the amount of commits that make-up each solution, plus the amount of peer comments, plus the amount of collaborative merges a solution has received. Often, you should commit. Generously, you should comment. Collaborate with you fellow Padawans, you should.

4. Each check point level of success is measured by writing a Jedi Master curated Top 10 list of learned items known as a "Padawan Cheat Sheet".

5. Final application success level is mesured in "client value points" as documented in [Proposed Test Application](#Proposed Test Application)

→ [index](#index)

###Handling Advanced Developers

Developers that move faster than average can go ahead and complete as much exercises as wanted.

Helping others has shown to produce better practice and checkpoint level of success.

→ [index](#index)

###Materials

1. (Windows Only) Install VM Software [VirtualBox](http://www.oracle.com/technetwork/java/javase/downloads/index.html).

2. (Windows Only) Download Ubuntu 14.04 64-bit VM Image. [OSBoxes](http://www.osboxes.org/ubuntu/)

3. (Windows Only) Download 7-zip Software [7-zip](http://www.7-zip.org/download.html)

4. (Windows Only) Install Ubuntu 14.04 [OSBoxes Guide](http://www.osboxes.org/guide/).

5. Make a mental note on switching to Linux.

6. Get hold of a Google account + headset (for audio calls).

7. Create your own [GitHub](https://github.com/) account. Follow this [guideline](https://help.github.com/articles/set-up-git) to setup your account. Also you can read further about Git in [Try Git](https://try.github.io/levels/1/challenges/1) or [Learn Git Branching](http://pcottle.github.io/learnGitBranching/)

8. Fork [this repo](https://github.com/gbarco/perl-padawan-camp-2016) to use as a base to host the project code. Read [this](https://help.github.com/articles/fork-a-repo/) for instructions.

9. Create a branch with your name, commit and send a pull request to the main repo adding a directory under the padawans_training_grounds directory with your first name and last name in this format NameLastname in case of collisions device an algorithm to fix the problem freely or read [Collisions](https://en.wikipedia.org/wiki/Collision_%28computer_science%29) for some background and ideas. Read about [Pull Requests](https://help.github.com/articles/creating-a-pull-request/)

10. Run the script called setup_environment.sh from command line under Linux to get most of the required software and modules installed.

→ [index](#index)

###General Guidelines

The Perl Padawan Camp is organized in the following way:

1. The first three weeks will be used for intensive self learning. Each topic will consist of reading and practice parts. Tutors will be available to answer technical questions.

2. The forth week will be used to develop an application following a real life process. The exercise consists of fixing reported bugs, detecting and fixing unreported bugs and developing new functionality collaborativelly.

3. Two chat rooms will exist. The Padawan Chat Room for participants interaction and the Jedi Masters Chat Room for feedback and technical assistance.

Perl Padawan Chat Room 2016
Tutors are not present in this chat room. Here is the place to offer help, interact, discuss and collaborate with your team.

Perl Jedi Masters Chat Room 2016
Every person participating in the boot camp is present here (participants and tutors). Here is the place to ask for technical assistance!

4. [Team play](http://www.dummies.com/how-to/content/ten-qualities-of-an-effective-team-player.html) is encouraged and taken into account when evaluating each participant.

5. Expect vague instructions. Life like this. The force is within you to look for support and guidance from your teammates, tutor, google and stackoverflow.

6. All code and documentation must be in English.

7. Code must adhere PerlTidy defaults. [Perltidy Tutorial] (http://perltidy.sourceforge.net/tutorial.html)

→ [index](#index)

###Proposed Test Application

The test application will consist in a REST API for a functional shopping cart.

Key Points, minimum features to be completed are:

  - POD Documented API. 2 points. [Read perlpod](http://perldoc.perl.org/perlpod.html)
  - POD Documented methods. 2 points. [More perlpod](https://juerd.nl/site.plp/perlpodtut)
  - Unit tests. 2 points. [Read Test::More](http://perldoc.perl.org/Test/More.html)
  - User registration and removal. 2 points.
  - Add products to catalog. 2 points.
  - Products must persist. 2 points. [Read DBD::mysql](http://search.cpan.org/~capttofu/DBD-mysql-4.033/lib/DBD/mysql.pm) 
  - Find products by category and name. 2 points.
  - Export Excel spreadsheet. 2 points. [Read Excel::Writer::XLSX](http://search.cpan.org/~jmcnamara/Excel-Writer-XLSX-0.92/lib/Excel/Writer/XLSX.pm)

Challange points are:

  - Import Excel spreadsheet with all products. 20 points. [Read Spreadsheet::XLSX](http://search.cpan.org/~mikeb/Spreadsheet-XLSX-0.15/lib/Spreadsheet/XLSX.pm)
  - Add products to cart. 10 points.
  - Delete product from cart. 10 points.
  - Get cart contents. 10 points.
  - Consume prices from WS in "wsPrices". 10 points. [Read SOAP::Lite](http://guide.soaplite.com/) [Read More SOAP::Lite](http://search.cpan.org/~phred/SOAP-Lite-1.19/lib/SOAP/Lite.pm)
  - Authenticate against WS in "wsAuthentication". 10 points. [Read Rest::Client](http://search.cpan.org/~kkane/REST-Client/lib/REST/Client.pm) [Read JSON](http://search.cpan.org/~makamaka/JSON-2.90/lib/JSON.pm)
  - Migrate "wsAuthentication" from SQLite to MySQL. [Read DBI](http://search.cpan.org/~timb/DBI-1.636/DBI.pm) [Read DBD::SQLite](http://search.cpan.org/~ishigaki/DBD-SQLite/lib/DBD/SQLite.pm) [Read DBD::mysql](http://search.cpan.org/~capttofu/DBD-mysql-4.033/lib/DBD/mysql.pm) 
  - Cached prices. 10 points. [Read Memoize](http://perldoc.perl.org/Memoize.html)
  - Cached users. 10 points.
  - Cache with Memcached. 10 points. [Read Cache::Membached](http://search.cpan.org/~dormando/Cache-Memcached-1.30/) or [Read Memoize::Memcached](http://search.cpan.org/~tcohen/Memoize-Memcached-0.04/lib/Memoize/Memcached.pm)

Nice to have:

  - Multiple instances with a balancing proxy. 30 points. [Read HAProxy](https://serversforhackers.com/load-balancing-with-haproxy)
  - Multiple instances of memcached. 30 points. [Reread Cache::Memcached](http://search.cpan.org/~dormando/Cache-Memcached-1.30/)
  - Non plain text authentication. 30 points. Read wsAuthentication docs. Also [Read Digest::BCrypt](http://search.cpan.org/~capoeirab/Digest-Bcrypt/lib/Digest/Bcrypt.pm)

All requests except registration must require authentication from the documentation.

Features will be considered "done" when integration tests in the "integration" directory contained in "padawan_training_grounds" pass. Read [Definition of Done](https://www.scrumalliance.org/community/articles/2008/september/definition-of-done-a-reference) for the concept behind this.
Documentation and unit tests will be considered "done" if a Jedi Master judges it to have 100% coverage.
Jedi Masters will write integration tests during week four in parallel with development.

Value for each feature may change at any time. This document holds valid values at any given time.
Requested features may be dropped at any time and will be considered 0 points worth.

Each passing Jedi Master integration test is worth 10 points.
Jedi Masters can change integration tests at any time, even already passing ones.
Wrong integration tests can only be changed by Jedi Masters.

Each unique implemented unit test is worth 1 point.

Missing documentation coverage of a method voids all unit test points.
Missing documentation coverage of API endpoints voids all related feature points.
Not nailing a minimum viable product voids all points. [Read MVP](https://en.wikipedia.org/wiki/Minimum_viable_product)

###Reading Days###

Reading days are organized in sprints of 7 days for each group of knowledge keypoints.

The structure behind each reading week is Read, Practice, Commit (not related to [RPC](https://en.wikipedia.org/wiki/Remote_procedure_call) but a good read anyways...).

1. ####Read:####
A list of suggested topics with a suggested 

2. ####Practice:####
Padawans are encuraged to practice what they have read on a free 

3. ####Commit:####
Padawans will collaborate on the editing and committing of a single small [POD](https://juerd.nl/site.plp/perlpodtut), [More POD](http://perldoc.perl.org/perlpod.html).

The document is formatted with the sections NAME, SYNOPSIS (when aplicable, seek wisdom in CPAN modules like [Dancer](http://search.cpan.org/~bigpresh/Dancer-1.3202/lib/Dancer.pm)) and LEARNED KEYPOINTS where Padawans outline what they consider the most important points.

The POD document should include inline code to test itself for syntax errors. So that executing it with the Perl interpreter will run at least a syntax check on itself. An example exists in the padawans_summaries directory.

Jedi Masters like paragraphs that have been edited by many Padawans over single Padawan paragraphs. Jedi Masters also like to see you write as you read, not by the end of the sprint. Commit often, you should.

Documents are due on Wednesdays.

Each week a pull request with a new file in the padawans_summaries directory as a single pull request when the group agrees the document represents the most important topics.

####Week 1####

1. 

####Week 2####

####Week 3####

###Learning Days###

Each day you will grab the fundamentals of the key building blocks of Perl applications with a focus on Web Applications and Web Services based on SAO and microservices architectures running within containers in clustered environment developed under TDD paradigms with Agile groups. Read [Dancer](https://metacpan.org/pod/Dancer2::Manual), [Web Services](https://en.wikipedia.org/wiki/Web_service), [SAO](https://en.wikipedia.org/wiki/Service-oriented_architecture), [Microservices](https://en.wikipedia.org/wiki/Microservices), [Docker](https://www.docker.com/what-docker), [TDD](http://www.eecs.yorku.ca/course_archive/2003-04/W/3311/sectionM/case_studies/money/KentBeck_TDD_byexample.pdf) and [Agile Principles](http://www.agilemanifesto.org/principles.html). 

On each learning day you will have to:

1. ####Read:####
Jedi Masters have selected documentation about the focal point of each iteration for background reference. Each iteration also has an associated guide and examples.

2. ####Practice:####
You will implement the previously gathered knowledge in simple coding activities.

Every iteration's practice section is divided into "Key Points" (comparable to a definition of the [Minimum Viable Product](https://en.wikipedia.org/wiki/Minimum_viable_product); thus the tasks you should pay the most attention and start as early as possible, "Challange" (tasks that expect to lead you beyond your confort zone and into the hairy matters of camel herding, you can start by looking that up!), "Nice to have" (extra tasks that lead you into the road of Jedi wisdom).

3. ####Commit:####
You will commit all your code on a daily basis, when you finish your practice and receive peer code reviews and optional Perl Jedi Master guidance.

### Introduction

  - [JVM](http://www.oracle.com/webfolder/technetwork/tutorials/obe/java/gc01/index.html#t1s1). See: "Java Technology and the JVM" and "Describing Garbage Collection"

####Topic 0: Introduction to Object Oriented Programming Concepts (2 days)####

#####Reading:#####

1. Beginners: Java Concepts [basic tutorial](http://docs.oracle.com/javase/tutorial/java/concepts/) (in case you need it!)

2. Beginners: Have fun with [Introduction to Java Programming](http://www.ibm.com/developerworks/java/tutorials/j-introtojava1/). Do as much you can.

3. Explore [Design Patterns](http://www.avajava.com/tutorials/categories/design-patterns). Minimum scope: singleton, factory, abstract factory, strategy, template method, proxy, decorator and builder.

#####Extra documentation:#####

* [Design Patterns Card](http://www.mcdonaldland.info/files/designpatterns/designpatternscard.pdf)


#####Practice:#####

Note that you don't need to create real database connections, [just mock it](https://en.wikipedia.org/wiki/Mock_object) (create a simulation of them).

1. Create a singleton example for a database connection.
2. Create a abstract factory example for diferent type of SQL connections. See [this](http://www.tutorialspoint.com/design_pattern/abstract_factory_pattern.htm) example.
3. Create a proxy example for database accesor clases.
4. Create a builder example for database connection.

#####Key Points:#####

3

#####Commit:#####

Commit your practice code.

→ [index](#index)

####Topic 1: Maven (1 day)####

#####Reading:#####
1. [What is Maven?](http://maven.apache.org/what-is-maven.html)

2. Have fun with [Maven in 5 minutes](http://maven.apache.org/guides/getting-started/maven-in-five-minutes.html). 

3. Maven: [best practices](http://books.sonatype.com/mvnref-book/reference/pom-relationships-sect-pom-best-practice.html)

#####Practice:#####

(It is assumed that Maven is already installed and working).

1. Create and build a simple Maven project:
2. Customize the Maven project by adding new dependencies: log4j, junit.
3. Create a simple unit test under src/test/java and run it. Then skip the unit test by property or by adding the skipping test configuration to your pom.xml file.

#####Key Points:#####

1,2,3

#####Commit:#####

Commit your practice code.

→ [index](#index)


####Topic 2: Test Driven Development (2 days)####

#####Reading:#####
1. [Test Driven Development](http://technologyconversations.com/2013/12/24/test-driven-development-tdd-best-practices-using-java-examples-2/)

#####Practice:#####

1. Use TDD to create the 'Recent file list' behaviour. Some examples of this behaviour is:
  * When the program is run for the first time, the list is empty.
  * When a file is opened, it is added to the recent file list.
  * If an opened file already exists in the recent file list, it is bumped to the top, not duplicated in the list.
  * If the recent file list gets full (typical number of items is 15), the oldest item is removed when a new item is added.
2. Using TDD techniques such as mocking, faking and stubs, try to develop your own blog software featuring:
  * Post new entry
  * Delete existing entry
  * Show 10 most recent entries
 
#####Key Points:#####

2

#####Commit:#####

Commit your practice code.

→ [index](#index)


####Topic 3: Services (2 days)####

#####Reading:#####
1. [How to create services in Java](http://www.makinggoodsoftware.com/2009/11/17/how-to-create-services-in-java/)

2. [How to design a good API and why it matters](https://www.youtube.com/watch?v=aAb7hSCtvGw)

#####Practice:#####

1. Create a shopping cart API spec
2. Implement the previous shopping cart using TDD.
3. Document services.
4. Design a UserService for CRUD operations.
5. Implement and document previous UserService.

Note: Do not implement JPA or ORM. Services should return in memory data only.

#####Key Points:#####

2,4,7

#####Commit:#####

Commit your practice code.

→ [index](#index)


####Topic 4: SQL - MySql (2 days)####

#####Reading:#####
1. [MySql basis](http://www.vogella.com/tutorials/MySQL/article.html)

2. [Jdbc basis](http://www.vogella.com/tutorials/MySQLJava/article.html#jdbc)

#####Extra documentation:#####

1. [Optimizaciones en MySql](http://www.arsys.info/programacion/bases-de-datos/como-optimizar-bases-de-datos-mysql/)


#####Practice:#####
Do not solve the practice using JDBC, please just send us the sql scripts.

1. Create a database named 'high-school' and modelate:
 
   - Student: first name, last name, registration number, date of birth)
   - Teacher: first name, last name, date of birth)
   - Course: name, assigned teacher, hours by week, schedule time (they can be dictated several times during the week)

   Notes:
   - An student can assist several courses during the same year.
   - A teacher can be assigned to several courses.
   - For each course, each student has 3 partial notes and a final note.
   - Create all relationship that you think they are required.

2. Insert information for 3 teachers, 3 courses and 10 students per course.
3. List students and teachers for a given course. The output format should be:

        Course: <course-name>
        Teacher: <last-name>, <first-name>
        Students:
          <last-name>, <first-name> (ordered by alphabetically by last name)

4. Percentage of students that passed/failed a given course.
5. For a given teacher, list the timeline for each course that he is assigned to (ordered by date), and the course name. The format should be:

        Teacher: <last-name>, <first-name>
        Schedule:
          Monday 09:00 - 11:00: <course-name>
          Monday 15:00 - 17:30: <course-name>
          Friday 08:45 - 10:40: <course-name>

6. Identify and Optimize all queries.
7. Connect to MySQL using Java JDBC and perform the query you have developed in excercise 5.

#####Key Points:#####

1,2,3,5,7

#####Commit:#####

Commit your practice code.

→ [index](#index)

####Topic 5: NoSQL - MongoDB (2 days)####

#####Reading:#####
1. [SQL vs. NoSQL DB](http://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/)

2. [Installing MongoDB](http://docs.mongodb.org/manual/installation)

3. [SQL to MongoDB Mapping Chart](http://docs.mongodb.org/manual/reference/sql-comparison)

4. [Morphia to Map Java objects in MongoDB](https://dzone.com/articles/using-morphia-map-java-objects)


#####Practice:#####

1. Using the same SQL-MySql data model, map it to the corresponding database, collections and documents.
2. Fetch all students whose notes in a specific course were greater than 4.
3. Fetch all courses ordered by name for a given teacher.
4. Create a new project using Maven and Morphia to map the objects created in 1. Create the necessary DAOs to get same result than 2.

#####Key Points:#####

1,2,4

#####Commit:#####

Commit your practice code.

→ [index](#index)

####Topic 6: Spring Core & REST (3 days)####

#####Reading:#####
1. [Introduction to REST](https://www.youtube.com/watch?v=YCcAE2SCQ6k)

2. [Quick development guide](https://spring.io/guides/gs/rest-service/)

3. [Spring boot - rest services guide](http://spring.io/guides/tutorials/bookmarks/)

4. [REST API documentation](http://swagger.io/getting-started/)
  
#####Practice:#####

1. Expose the shopping cart created in the topic 3.
2. Write the swagger file for point 1.
3. Create and document with swagger a REST API to register users. The API must provide: add, delete, update and find by name and find by nickname operations. Note that the username must be unique.

#####Key Points:#####

3

#####Commit:#####

Commit your practice code.

→ [index](#index)

###Your First Project Starts Now!

####Final Project (2 days)
Create a functional shopping cart (just REST api). The minimum features to be completed are:

  - User registration and login.
  - Find products by category and name.
  - Save Cart.
  - Buy products.

The solution must use MongoDB or MySql as repository as well as Spring Boot and swagger for REST documentation.

Thanks for reading!
