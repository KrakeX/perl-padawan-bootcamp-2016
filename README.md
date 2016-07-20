# Perl Padawan Camp 2016

Please, use this repository as a base for you training phase. Fork this project
and keep the directory structure as a base for your commits.

It's extremelly important to keep the key points easy to be verified by
the reviewers. *Do not mix the key points with the rest of the exercises*

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

    * [Topic 0: Introduction to Perl](#topic-0-introduction-to-perl)

    * [Topic 1: Introduction to Object Oriented Programming Concepts](#topic-1-introduction-to-object-oriented-programming-concepts)

    * [Topic 2: CPAN dependencies](#topic-2-cpan-dependencies)
    
	* [Topic 3: Test Driven Developments](#topic-3-test-driven-development)

    * [Topic 4: Services](#topic-4-services)

    * [Topic 5: SQL - MySql](#topic-5-sql---mysql)

    * [Topic 6: NoSQL - MongoDB](#topic-6-nosql---mongodb)
    
    * [Topic 7: REST](#topic-7-rest)

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

###Reading Days###

Reading days are organized in sprints of 7 days for each group of knowledge keypoints.

The structure behind each reading week is Read, Practice, Commit (not related to [RPC](https://en.wikipedia.org/wiki/Remote_procedure_call) but a good read anyways...).

1. ####Read:####
A list of suggested topics with a suggested reading order.

2. ####Practice:####
Padawans are encouraged to practice what they have read and commit code and POD formatted summaries under their personal directory in padawan_training_grounds/user/week#.pod. If you choose to commit a personal pull request it should be done by Wednesday.

3. ####Commit:####
Padawans will collaborate on the editing and committing of a single small [POD](https://juerd.nl/site.plp/perlpodtut), [More POD](http://perldoc.perl.org/perlpod.html).

The document is formatted with the sections NAME, SYNOPSIS (when aplicable, seek wisdom in CPAN modules like [Dancer](http://search.cpan.org/~bigpresh/Dancer-1.3202/lib/Dancer.pm)) and LEARNED KEYPOINTS where Padawans outline what they consider the most important points.

The POD document should include inline code to test itself for syntax errors. So that executing it with the Perl interpreter will run at least a syntax check on itself. An example exists in the padawans_summaries directory.

Jedi Masters like paragraphs that have been edited by many Padawans over single Padawan paragraphs. Jedi Masters also like to see you write as you read, not by the end of the sprint. Commit often, you should.

Documents are due on Wednesdays.

Each week a pull request with a new file in the padawans_summaries directory as a single pull request when the group agrees the document represents the most important topics.

####Week 1####
Basic development frameworks and Perl Syntax

1. POD. Plain Old Documentation. Standard Perl documentation format suppointing inline documentation, coverage test and automatic documentation generation in PDF and HTML amongs others.
	- [Writing POD](http://perlhacks.com/articles/rtfm/writing-plain-old-documentation/)
	- Practice: Write a minimalistic pod document. With a title and a paragraph about pod. Name practice1.pod in your personal directory.
	- [POD in 5 minutes](https://juerd.nl/site.plp/perlpodtut)
	- Practice: Write a pod document with a bulleted list of all pod syntax elements you can remember. Name practice2.pod in your personal directory.
	- [POD embedded](http://perldoc.perl.org/perlsyn.html#PODs%3a-Embedded-Documentation)
	- Practice: Search for a hello world Perl example document with Embedded POD. Name practice3.pl in your personal directory.
	- [the Plain Old Documentation format](http://perldoc.perl.org/perlpod.html)
	- Commit: Write a summary, you must. Think "What is POD and what are its main features?". Contact peers. Name summary1.pod in padawan_summaries directory.
2. Perl Basic Syntax. Mostly from Beggining Perl, [free in full here](http://learn.perl.org/books/beginning-perl/).
	- [Beggining Perl, Chapter 1: First Steps In Perl](http://blob.perl.org/books/beginning-perl/3145_Chap01.pdf)
	- [Beggining Perl, Chapter 2: Working with Simple Values](http://blob.perl.org/books/beginning-perl/3145_Chap02.pdf)
	- [Beggining Perl, Chapter 3: Lists and Hashes](http://blob.perl.org/books/beginning-perl/3145_Chap03.pdf)
	- Practice: Write a simple program that instances one variable of each type you know and print its value. Document with pod. Name practice4.pl.
	- [Beggining Perl, Chapter 4: Loops and Decisions](http://blob.perl.org/books/beginning-perl/3145_Chap04.pdf)
	- Practice: Write a simple program that instances one variable of each type you know and print all even values. Print at least 50 values. Reduce code to a minimum. Name practice5.pl.
	- [Beggining Perl, Chapter 7: References](http://blob.perl.org/books/beginning-perl/3145_Chap07.pdf)
	- [Beggining Perl, Chapter 8: Subroutines](http://blob.perl.org/books/beginning-perl/3145_Chap08.pdf)
	- Practice: 
	- [Beggining Perl, Chapter 10: Modules](http://blob.perl.org/books/beginning-perl/3145_Chap10.pdf)
	- Practice:
	- [Beggining Perl, Chapter 11: Object-Oriented Perl](http://blob.perl.org/books/beginning-perl/3145_Chap11.pdf)
	- Practice: Write an OOP module that represents a person that has a name, age (numeric) a list of friends (persons) an unlimited list of favorites, favorite color, favorite car model, favorite icecream, should remember any favorite it is told without changing implementation. All files into practice6 directory under your personal directory.
	- [Perl Syntax](http://perldoc.perl.org/perlsyn.html)
	- Summarized syntax cannot be. Write a SYNOPSIS with examples, you should. Contact peers. Name summary2.pod.
3. TDD. Test Driven Development. Software development methodology that simplifies programming to the repetition of a short Red/Green/Refector loop.
	- [Test::Simple Tutorial](http://search.cpan.org/dist/Test-Simple/lib/Test/Tutorial.pod)
	- Practice: Write a test for person. That ensures that after setting an initial age, attempts to set a non numeric age do not change the person's age. Into practice7 directory.
	- [Test::More](http://search.cpan.org/~exodist/Test-Simple-1.302022/lib/Test/More.pm)
	- [Test::Exception](http://search.cpan.org/~exodist/Test-Exception-0.43/lib/Test/Exception.pm)
	- Practice: Research exceptions and modify person to throw an exception when a non numeric age is set. Test the module to verify that numeric ages do not produce an exception but non numeric ages do. Into practice8 directoy. Into practice8 diractory.
	- [Test Driven Development by Example](http://www.eecs.yorku.ca/course_archive/2003-04/W/3311/sectionM/case_studies/money/KentBeck_TDD_byexample.pdf)
	- Practice with a simple module with a test, you should.
	- Summarize what are the main points behind the TDD cycle, Perl modules that aid in testing and list methods can be used from each module. Name summary3.pod.  
4. Review summaries with peers and create a single pull request with your group's tribute of knowledge to the Jedi Masters. Repeat each reading week for summaries.
5. [Self organize](https://en.wikipedia.org/wiki/Self-organization) with your peers during week 2 to select what to practice and what to write about in summaries during the course of the week. Maintain the pattern of names and directories from week 1. Select an ammount of practice and summaries the whole group can commit to achive their commitment. Document your decisions with a similar format to week 1 in the next section of this document. Produce a single pull request when done.

####Week 2####
1. Design Patterns with Perl. Understand Factory, Builder, Factory method, Object Pool, Singleton, Adapter, Composite, Decorator, Facade, Proxy, Command, Observer, Strategy, Template Method and Visitor.
	- [Check patterns in Wikipedia](https://en.wikipedia.org/wiki/Software_design_pattern)
	- [Contrast with nice graphics from sourcemaking.com](https://sourcemaking.com/design_patterns)
	- [See them translated to Perl in Perl Design Patterns](http://perldesignpatterns.com/perldesignpatterns.html) 
	- Summarize three patterns either coordinating with your peers to collaborate and avoid repeating patterns. Provide an explanation in Spanish and an example with real life objects. In the lines of "Un cajon con utensilios de cocina se puede considerar un Object Pool ya los mismos se comparten entre varias personas que los devuelven para ser reutilizados ahorrando la complejidad de crear un tenedor y destruirlo antes y despues de cada comida a diferencia de un tenedor descartable de plastico que debe de ser instanciado y destruido antes y despues de cada uso".
2. Modern Perl OOP.
	- [Getting started with Moose](http://www.theperlreview.com/articles/moose.html)
	- [Moose Manual](http://search.cpan.org/~ether/Moose-2.1804/lib/Moose/Manual.pod)
	- [Moose Cookbook](http://search.cpan.org/~ether/Moose-2.1804/lib/Moose/Cookbook.pod)
	- [Moose Person Example](http://perlmaven.com/object-oriented-perl-using-moose)
	- [Yet Another Moose Person Example](http://search.cpan.org/~ether/Moose-2.1804/lib/Moose/Cookbook/Basics/Person_BUILDARGSAndBUILD.pod)
	- [Extending Non Moose Classes with Moose](http://search.cpan.org/~doy/MooseX-NonMoose-0.26/lib/MooseX/NonMoose.pm)
	- You do get to self organize but you should be thinking about porting that person example to Moose and rewriting some tests.
	- It seems a summary per point was the standard for last week. Hopefully self organization keeps up with it.
3. For next week. Only a list of modules is provided. Self organize to determine sources of study. CPAN is recommended. Also define and execute practices and provide a summary for each modules core functionality. Document your choices in next section of this document. Produce a single pull request when done.

####Week 3####
1. App::Prove
2. App::Cpanminus
1. LWP::UserAgent
2. DBI
3. JSON
4. DateTime
5. Dancer
6. WWW::Mechanize
7. WWW::Mechanize::PhantomJS
8. Digest::SHA
9. Crypt::Rijndael
10. Excel::Write::XLSX
11. SOAP::Lite
12. REST::Client
13. Find a module that process [CSV](https://en.wikipedia.org/wiki/Comma-separated_values)
14. Find a module that allows to resize images.
15. Test SOAP
16. Send mail with attachments
17. Implement a mail server
18. Implement a HTTP server
19. Use Memcached
20. Connect to SSH
21. Generate Barcodes
22. Generate PDF documents
23. Parse HTML
24. Parse XML
25. Implement a Binary Tree
26. Parse config files
27. Test TCP servers
28. Extract links from HTML
29. Automate Facebook Graph querying
30. Minifies Javascript
31. Test each module with a proposed practice. Each Padawan should produce a pull request.
32. Document each modules functionality in pod format follow module documentation guidelines. Produce a single pull request for your group.

###Learning Days###

Each day you will grab the fundamentals of the key building blocks of Perl applications with a focus on Web Applications and Web Services based on SAO and microservices architectures running within containers in clustered environment developed under TDD paradigms with Agile groups. Read [Dancer](https://metacpan.org/pod/Dancer2::Manual), [Web Services](https://en.wikipedia.org/wiki/Web_service), [SAO](https://en.wikipedia.org/wiki/Service-oriented_architecture), [Microservices](https://en.wikipedia.org/wiki/Microservices), [Docker](https://www.docker.com/what-docker), [TDD](http://www.eecs.yorku.ca/course_archive/2003-04/W/3311/sectionM/case_studies/money/KentBeck_TDD_byexample.pdf) and [Agile Principles](http://www.agilemanifesto.org/principles.html). 

On each learning day you will have to:

#####Read:#####
Jedi Masters have selected documentation about the focal point of each iteration for background reference. Each iteration also has an associated guide and examples.

#####Practice:#####
You will implement the previously gathered knowledge in simple coding activities.

Every iteration's practice section is divided into "Key Points" (comparable to a definition of the [Minimum Viable Product](https://en.wikipedia.org/wiki/Minimum_viable_product); thus the tasks you should pay the most attention and start as early as possible, "Challange" (tasks that expect to lead you beyond your confort zone and into the hairy matters of camel herding, you can start by looking that up!), "Nice to have" (extra tasks that lead you into the road of Jedi wisdom).

#####Commit:#####
You will commit all your code on a daily basis, when you finish your practice and receive peer code reviews and optional Perl Jedi Master guidance.

→ [index](#index)

### Introduction

####Topic 0: Introduction to Perl####

#####Reading:#####
1. Basics: [Perl language structure](https://en.wikipedia.org/wiki/Perl_language_structure).
2. Basics: [Perl Intro](http://perldoc.perl.org/perlintro.html).
3. Basics: [Perl Data Types](http://perldoc.perl.org/perldata.html).
4. Basics: [Perl Operators](http://perldoc.perl.org/perlop.html).
5. Basics: [Perl Functions](http://perldoc.perl.org/perlfunc.html).
6. Basics: [Perl Subroutines](http://perldoc.perl.org/perlsub.html).

#####Practice:#####

1. Write a piece of code that calculates the first 10 Fibonacci numbers. Only numbers 0 and 1 can be hardcoded.
2. Change your code to output to a file.
3. Create a subroutine that takes the 10th Fibonacci number and uses it as the length parameter. The subroutine should output a string of the given length of random caracters choosen from an array that contains the range a..z.
4. Take the resulting string and convert to A-Z range with a single function call.
5. Create a subrouting that receives the previous string and computes the [ADLER32](https://en.wikipedia.org/wiki/Adler-32) sum of the string.

#####Key Points:#####

1,2,3,4,5

#####Commit:#####

Generate a Pull Request with your tested practice code.

→ [index](#index)

####Topic 1: Introduction to Object Oriented Programming Concepts####

#####Reading:#####

1. Beginners: Perl Object Oriented Programming [Tutorial](http://perldoc.perl.org/perlootut.html).
2. Beginners: Introduction to Moose, A postmodern object system for Perl [Moose Introduction](http://www.slideshare.net/davorg/introduction-to-oo-perl-with-moose).
3. Review design patterns! [Design Patterns](http://perldesignpatterns.com/perldesignpatterns.html) 

#####Practice:#####

Follow the article [Attribute types in Perl classes when using Moose](http://perlmaven.com/attribute-types-in-perl-classes-when-using-moose).

1. Write the class described in the article.
2. Read [Moose::Manual](http://search.cpan.org/dist/Moose/lib/Moose/Manual.pod) and create a subclass of Person to handle user logins. It should check a password set on object creation. Throw an exception on wrong passwords.
3. Create tests to prove wrong passwords fail with an exception and correct passwords do not.
4. Create a DB_User class that extends the user login class and uses data from mysql to check for the password. Mysql native encrypted passwords are nice to have.

#####Key Points:#####

3

#####Commit:#####

Generate a Pull Request with your tested practice code.

→ [index](#index)

####Topic 2: CPAN Dependencies####

#####Reading:#####
1. [App::cpanminus](http://search.cpan.org/~miyagawa/App-cpanminus-1.7042/lib/App/cpanminus.pm)
2. Read [cpanm](http://search.cpan.org/~miyagawa/App-cpanminus-1.7042/bin/cpanm) -L option.
3. Re read [Excel::Writer::XLSX](http://search.cpan.org/~jmcnamara/Excel-Writer-XLSX-0.94/lib/Excel/Writer/XLSX.pm), [DBI](http://search.cpan.org/~timb/DBI-1.636/DBI.pm) and [DBD::SQLite](http://search.cpan.org/~ishigaki/DBD-SQLite-1.50/lib/DBD/SQLite.pm).

#####Practice:#####

1. Create a script that exports a users table to Excel. Include Name, Lastname, Login and Password.
2. Password should be masked to show only first and last characters. Apply [Regexp](http://perldoc.perl.org/perlre.html).
3. Add parameters with [Getopt::Long](http://perldoc.perl.org/Getopt/Long.html) to allow command line switches that allow to exclude fields from the Excel output.
4. Create tests that ensure passwords get masked. Oops... what about single caracter passwords?
5. A script does not mean you have no classes. Refactor accordingly.

#####Key Points:#####

1, 4, 5.

#####Commit:#####

Generate a Pull Request with your practice code.

→ [index](#index)

####Topic 3: Test Driven Development####

#####Reading:#####
1. [Test Driven Development](http://www.mclean.net.nz/osdc-tdd-full.pdf)

#####Practice:#####

1. Use TDD to create the 'Recent file list' behaviour. Some examples of this behaviour is:
2. When the program is run for the first time, the list is empty.
3. When a file is opened, it is added to the recent file list.
4. If an opened file already exists in the recent file list, it is bumped to the top, not duplicated in the list.
5. If the recent file list gets full (typical number of items is 15), the oldest item is removed when a new item is added.
6. Add persistence in plain text files. [Perl > Functions > Open](http://perldoc.perl.org/functions/open.html)
7. Refactor your solution to allow both plaintext files or DBI with SQLite.
 
#####Key Points:#####

4, 6

#####Commit:#####

Generate a Pull Request that shows commits for each of your TDD iterations. Commit often! Should those Red, Green, Refactor cycles.

→ [index](#index)

####Topic 4: Services####

#####Reading:#####
1. [REST WS in Perl with Dancer](http://www.techumber.com/2014/08/create-restful-services-using-perl.html). Install modules using cpanm instead of ppm. 
2. [More REST WS in Perl with Dancer](http://www.codeproject.com/Articles/414446/REST-Service-with-Perl-and-Dancer).
3. [RESTful dancing with Dancer::Plugin::REST](http://blogs.perl.org/users/job_van_achterberg/2011/09/making-restful-dancing-easy-with-dancerpluginrest.html)
4. [How to design a good API and why it matters](https://www.youtube.com/watch?v=aAb7hSCtvGw)

#####Practice:#####

1. Create a shopping cart API spec.
2. Implement the specs using TDD.
3. Document services inline with POD as you develop. Include the API docs within the classes. Possible creating a ::Specs class to hold API specs and no code.
4. Design a service that handler CRUD operations.
5. Implement the CRUD service.

Note: Do not worry about persistence. Hardcode data in a separate Package so that it can be easily extended later, keep new users in memory.

#####Key Points:#####

2, 4

#####Commit:#####

Generate a Pull Request showing TDD cycles for your practice code.

→ [index](#index)

####Topic 5: SQL - MySql####

#####Reading:#####
1. [MySql basis](http://www.vogella.com/tutorials/MySQL/article.html)

2. [Optimizaciones en MySql](http://www.arsys.info/programacion/bases-de-datos/como-optimizar-bases-de-datos-mysql/)

#####Practice:#####
This practice is SQL oriented. Do not commit Perl code but SQL scripts unless instructed.

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

6. Identify and optimize all queries.
7. Connect to MySQL using DBI and perform the query you have developed in excercise 5.

#####Key Points:#####

1,2,3,5,7

#####Commit:#####

Pull Request with SQL scripts and script.

→ [index](#index)

####Topic 6: NoSQL - MongoDB####

#####Reading:#####
1. [SQL vs. NoSQL DB](http://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/)

2. [Installing MongoDB](http://docs.mongodb.org/manual/installation)

3. [SQL to MongoDB Mapping Chart](http://docs.mongodb.org/manual/reference/sql-comparison)

4. [MongoDB](http://search.cpan.org/~mongodb/MongoDB-v1.4.1/lib/MongoDB.pm)

5. [MongoDB Tutorial](http://search.cpan.org/~mongodb/MongoDB-v1.4.1/lib/MongoDB/Tutorial.pod)

#####Practice:#####

1. Using the same SQL-MySql data model, map it to the corresponding database, collections and documents.
2. Create data classes that map fields from MongoDB to Perl objects. Read [AUTOLOAD](http://perldoc.perl.org/perlsub.html#Autoloading) for inspiration on how to lazy load remote data. Think [DAO](https://en.wikipedia.org/wiki/Data_access_object).
3. Fetch all students whose notes in a specific course were greater than 4.
4. Fetch all courses ordered by name for a given teacher.

#####Key Points:#####

1,2,4

#####Commit:#####

Generate a Pull Request with your practice code.

→ [index](#index)

####Topic 7: REST####

#####Reading:#####
1. [Introduction to REST](https://www.youtube.com/watch?v=YCcAE2SCQ6k)

2. [Making your Perl Rest](http://www.slideshare.net/zostay/making-your-perl-rest-presentation).

3. [Rasin](https://metacpan.org/pod/Raisin) an alternate REST framework for Perl with a simple DSL.

4. [REST API documentation](http://swagger.io/getting-started/)

5. [Swagger and Perl with Mojolicious](http://thorsen.pm/perl/programming/2015/07/05/mojolicious-swagger2.html)

#####Practice:#####

1. Expose the shopping cart created in the topic 3.
2. Write the swagger file for point 1.
3. Create and document with swagger a REST API to register users. The API must provide: add, delete, update and find by name and find by nickname operations. Note that the username must be unique.

#####Key Points:#####

3

#####Commit:#####

Generate a Pull Request with your practice code.

→ [index](#index)

###Your First Project Starts Now!

####Final Project (7 days)

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

Thanks for reading!
