# CS50-Final-Project

My Final Project for CS50 is a web application using Flask, Python and SQL based in part on the web track's distribution code. The application is named Web Portfolio and it provides the visitor with the possibility to contact and join email newletter and. The input data will save on a database in two seperate tabales and also user will resive confirmation email after joiing on email newsletter form.<br/>

# Features

- [Flask](https://flask.palletsprojects.com/en/1.1.x/)
- [Flask-mail](https://pythonhosted.org/Flask-Mail/)
- [CS50 Library for Python](https://cs50.readthedocs.io/libraries/cs50/python/)
- [smtplib](https://pypi.org/project/secure-smtplib/)<br/>
<br/>
I've used Flask web framework based in Python. I have used cs50 library for manage SQL database with sqlite and db.execute for upload files and forms extensions and also smtplib for sending email server.<br/>


# Explaining the project and the database

My final project is a website that allow the visitor register in email newsletter and send message by contact form. All information about name, email message and phon, after filling will save in a database and also server will sent confirmation email to them. I used cs50-sql extension for connect the database to application and sqlite3 to manage it.

# SQL and sqlite3:

I needed two tables for my database:
-First, table subscribers. Where I put, id, first_name, last_name, email, notice that id must be a primary key here.
-Second, table forms. I put id, name, email, phone, message. <br/>

# Sending email server

TO send email server I used SMTP protocol client by calling smtplib.SMTP to send mail and STARTTLS to connect server to my email, server,login to loging my email as admin and finally server.sendmail to sent email by my email adress to user and sendiin confirmation email.<br/>


# My Project video 
- Link: [https://youtu.be/blfQiLjTKEc](https://youtu.be/blfQiLjTKEc)
# About CS50
This is CS50x , Harvard University's introduction to the intellectual enterprises of computer science and the art of programming for majors and non-majors alike, with or without prior programming experience. An entry-level course taught by David J. Malan, CS50x teaches students how to think algorithmically and solve problems efficiently. Topics include abstraction, algorithms, data structures, encapsulation, resource management, security, software engineering, and web development. Languages include C, Python, SQL, and JavaScript plus CSS and HTML. Problem sets inspired by real-world domains of biology, cryptography, finance, forensics, and gaming. The on-campus version of CS50x , CS50, is Harvard's largest course. 

- CS50 course[https://cs50.harvard.edu/x/2020/](https://cs50.harvard.edu/x/2020/)











