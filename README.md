Start Project - PHP
===================

This is a skeleton for any new project using PHP.


Requirements
------------
- PHP ^7.4 or PHP ^8.0.


Installation
------------

The best way to install Start Project for PHP is using [Composer](https://getcomposer.com).

```
composer create-project -s dev vaclavpavek/start-project-php
```


### View suggested packages for optional installation

```
composer suggests
```


Initial setup
-------------
- modify `composer.json`
    - name
    - description
    - keywords
    - homepage
    - autoload
    - autoload-dev
- modify `.github/workflows/qa.yaml`
- modify `.gitlab/gitlab-ci.yaml` 
- GitLab repository: Settings > CI / CD > General pipelines > Custom CI configuration path
