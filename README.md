# Coding Journal
## This is my log for all of my learnings that aren’t necessarily reflected in code
~4/16/20~
* discovered freeCodeCamp complete entry-level AWS course. Watched first 90 minutes or so
~4/17/20~
* ~another hour of AWS course

~4/18/20~
* finished AWS video
* began studying review questions for the exam

~4/19/20~
* began studying more questions, but then realized most fun way to learn this stuff would be by doing. Begin tinkering with S3

~4/20/20~
* reviewed AWS cloud cert questions. Learned you can host static websites on S3. Will look into hosting portfolio site on there.

~4/21/20~
* reviewed some more exam questions. 
* Exploring S3 Glacier as a long-term backup solution for hard drive that’s just been collecting dust

~4/22/20~
* backed up personal hard drive to S3. Experienced minor heart attack when I received an email saying 85% of my monthly S3 PUT usage had already been used up. Assumed someone must have gotten access either trying to fetch or insert files into my bucket, but confirmed all public access had been turned off. Took me a minute to realize that must have been *my* initial giant file transfer ☺️
* created file backup logging bucket - though not sure it’s necessarily configured properly
* need to create an IAM role as I’ve been doing everything through root user
* create bucket to try and host portfolio site on, moving from GitHub pages