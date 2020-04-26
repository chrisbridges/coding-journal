# Coding Journal
## This is my log for all of my learnings that aren’t necessarily reflected in code
__4/16/20__
* discovered freeCodeCamp complete entry-level AWS course. Watched first 90 minutes or so

__4/17/20__
* ~another hour of AWS course

__4/18/20__
* finished AWS video
* began studying review questions for the exam

__4/19/20__
* began studying more questions, but then realized most fun way to learn this stuff would be by doing. Begin tinkering with S3

__4/20/20__
* reviewed AWS cloud cert questions. Learned you can host static websites on S3. Will look into hosting portfolio site on there.

__4/21/20__
* reviewed some more exam questions. 
* Exploring S3 Glacier as a long-term backup solution for hard drive that’s just been collecting dust

__4/22/20__
* backed up personal hard drive to S3. Experienced minor heart attack when I received an email saying 85% of my monthly S3 PUT usage had already been used up. Assumed someone must have gotten access either trying to fetch or insert files into my bucket, but confirmed all public access had been turned off. Took me a minute to realize that must have been *my* initial giant file transfer ☺️
* created file backup logging bucket - though not sure it’s necessarily configured properly
* need to create an IAM role as I’ve been doing everything through root user
* create bucket to try and host portfolio site on, moving from GitHub pages

__4/26/20__
* uploaded portfolio static assets to S3
* setting up cloud front - just waiting for the certificates to go through - got one
