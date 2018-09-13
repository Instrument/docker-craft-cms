# Craft CMS with Docker compose

## Prerequisites
1. `docker-compose` > v1.20

## Installation

2. Install Docker for Mac
2. Download a copy of [Craft 2](https://craftcms.com/latest-v2.zip) and unzip it into `web`, overwriting the placeholder `craft` and `public` folders therein.
3. Run `docker-compose up`
4. Open http://localhost:8080 in your browser.
5. Set your DB credentials in `web/craft/config/db.php` to the following:
```
    'server' => 'db',
    'database' => 'craftcms',
    'user' => 'docker',
    'password' => 'docker',
```
