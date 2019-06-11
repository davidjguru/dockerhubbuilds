FROM ubuntu:19.04

MAINTAINER davidjguru <davidjguru@gmail.com>

# Initial
RUN apt update && apt -y upgrade

# Basics
RUN apt install -y build-essential            \ 
                   apt-transport-https        \
                   ca-certificates            \
		   jq                         \
                   curl                       \
                   software-properties-common \
                   file                       \
                   mysql-client               \
                   unzip                      \
                   rsync                      \
                   vim                        \
                   nano                       \
                   git                        \
# Apache
RUN apt install -y apache2                    \
                   libapache2-mod-php         \
   
# PHP 
RUN apt install -y php-mysql                  \
                   php7.3                     \
    		   php7.3-bcmath              \
                   php7.3-bz2                 \
                   php7.3-curl                \
                   php7.3-dev                 \
                   php7.3-gd                  \
                   php7.3-dom                 \
                   php7.3-imap                \
                   php7.3-imagick             \
                   php7.3-intl                \
                   php7.3-json                \
                   php7.3-ldap                \
                   php7.3-mbstring            \
                   php7.3-mysql               \
                   php7.3-oauth               \
                   php7.3-odbc                \
                   php7.3-uploadprogress      \
                   php7.3-ssh2                \
                   php7.3-xml                 \
                   php7.3-yaml                \
                   php7.3-solr                \
                   php7.3-zip                 \
                   php7.3-apcu                \
                   php7.3-opcache             \
                   php7.3-redis               \
                   php7.3-opcache             \
                   php7.3-memcached           \
                   php7.3-xdebug              \
                   libapache2-mod-php7.3
# Composer
RUN curl -sS https://getcomposer.org/installer | php && \
    mv composer.phar /usr/local/bin/composer && \
    chmod +x /usr/local/bin/composer && \
    composer global require hirak/prestissimo

# Drush
RUN

# Drush Launcher
RUN

# Drupal Console Launcher
RUN 
