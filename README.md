Ding fix：

针对数据库是PostgreSQL的情况下，text的最大长度不能大于1G，修改/db/migrate/001_create_import_actions.rb，调整字段的最大长都为1G

Redmine版本信息：

Environment:

*Redmine version                3.2.0.stable

*Ruby version                   2.1.8-p440 (2015-12-16) [x86_64-linux-gnu]

*Rails version                  4.2.5

*Environment                    production

*Database adapter               PostgreSQL


redmine_import_issues
==============================

This a rework of the https://github.com/javiferrer/redmine_import_issues plugin,just test redmine 3.x with Rails 4.2.

==============================

This plugin allows users to import issues and time_entries

Features
--------

* Import issues and its custom fields values
* Update issues by Issue ID or Custom Value
* Import time entries
* Create journals on updated issues
* Works with Excel and ODS formats
* Save import templates for recurring imports


Licence
-------

GNU General Public License Version 2

