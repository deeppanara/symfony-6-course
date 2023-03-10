# Symfony Course

## Technical Requirements
- PHP 8.2 or higher
- Composer installed

## Prerequisites
- Basic PHP knowledge <br>
- Low level HTML & CSS knowledge <br>
- Object-Oriented Programming <br>

## Course Overview

> - Introduction to Symfony
> - MVC Explained
> - Installation & Setup for Mac
> - Setting up VS Code for Symfony
> - Setting up our project & directory explained
> - Controllers in Symfony
> - Route Parameters in Symfony
> - Views in Symfony
> - Twigs layouts & blocks explained
> - How to create a database
> - Introduction to Doctrine
> - Doctrine Relationships Explained


## Installation


### **Symfony installer** <br>
```
Mac -  curl -sS https://get.symfony.com/cli/installer | bash
Linux - wget https://get.symfony.com/cli/installer -O - | bash
Windows – Download the setup.exe right here -> https://get.symfony.com/cli/setup.exe
```

```
export PATH=”$HOME/.symfony/bin:$PATH”
```


This command will install a Symfony

### **Composer installer** <br>
```
composer create-project symfony/skeleton movies
```

### **Check if settings are OK** <br>

If you’re not sure if you got that installed, you can run the following command to see if your local machine meets the requirements.
```
symfony check:requirements
```

If you have your environment setup correctly, you will be hit with the following message:
```ruby
[OK]
Your system is ready to run Symfony projects
```

### Open project in the browser
Symfony’s CLI comes with a web server that is very easy to use. 
```
symfony server:start 
```

This will return back a message which says that your web server is indeed listening, and it can be accessed through your localhost. 

```ruby 
EXAMPLE
 [OK] Web server listening
 	The Web server is using PHP CLI 8.1.16	
	http://127.0.0.1:8000     
```

127.0.0.1 is the standard ipv4 address for projects that run on localhost and :8000 is the first available port.

You can copy the link and paste it inside the browser, or you can perform the following command which will open it directly in the browser through the CLI:
```
symfony open:local
```
