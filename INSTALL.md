# Installation

1. Clone project from this git repo
2. Run ```composer install``` (see https://getcomposer.org/download/)
3. Leave default parameters when installation prompts
4. Set permissions : http://symfony.com/doc/master/setup/file_permissions.html

# Web Server configuration

see http://symfony.com/doc/current/setup/web_server_configuration.html

# Access test page

1. Simple Hello World display : http://your_host.com/
2. Form Display with csrf_token generated : http://your_host.com/form : the request header has to change in order to force a new csrf_token generation
