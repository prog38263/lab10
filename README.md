# Lab 10 - Malicious File Uploads

## Building The Lab

* git clone <a href="https://github.com/prog38263/lab10">https://github.com/prog38263/lab10</a>
* <code>cd lab10/code</code>
* <code>sudo chown www-data files</code>
* <code>cd ../</code>
* <code>docker-compose build && docker-compose up</code>
* In a browser, navigate to the root directory of your virtual machine

## Malicious File Uploads

* Try uploading some images and observe the method the program uses for validation.
* Try uploading a PHP script instead of an image.
* Try navigating to the uploaded script.
* Experiment with other scripts.

## Fixing

* Modify the program to prevent malicious file uploads by enforcing more rigerous validation.

