<h1>Activity: Section 9 Project 2</h1>

<h2>Overview</h2>

In the previous section, we added Internationalization to the application. If you have been following closely, you will have noticed several statements which print to the standard output stream. This is never a good idea in a production application. Using a proper logging library like log4j is the correct way to generate log messages.

Using a library allows us to send log messages to a file, instead of standard output. This way a user can mail us a log file if something does not work. The log file can be examined by developers to determine what may have gone wrong. Besides this, there are several advantages of using a logging library, like suppressing certain messages in different environment, sending the same message to multiple destinations, formatting the output, and so on.

In this exercise, we have added a jar file for log4j in the lib folder. You have to add this file to the classpath, and replace every System.out.println(...) with a corresponding log statement. One of the advantages of logging as opposed to using sysout, is that we can log at different levels such as debug, info, warn, error, and fatal. When you replace sysouts with log statements, you will also have to figure out which level each log statement should be logged  at. 

You will have to figure out how to initialize log4j to create a root logger, and a console appender. It is also recommended that you create an instance of Logger in every class that needs to emit log statements. 

Keeping up the trend we started in the past few exercises, we won't tell you much more than mentioned above. Do your research, ask questions, make your best judgment, and most importantly write some kick-ass code.

