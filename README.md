# Open LMS Enterprise S3 Content Access Service

This repository contains documentation and code examples for the Open LMS
Enterprise S3 Content Access service.  Open LMS Enterprise clients can use this
service for direct access to an S3 bucket containing database backups, various
logs, and the Moodle file store for their Moodle.

## Audience

The target audience for this documentation is technical staff within
organisations using Open LMS Enterprise.  It's publically available so it's
easy to share within those organisations where different people are responsible
for different parts of it.

## Index

* [About the Service](docs/00-what-is-this.md)
* [Prerequisites](docs/01-prerequisites.md)
* [Requesting Access](docs/02-requesting-access.md)
* [Configuring IAM Users](docs/03-configuring-iam-users.md)
* [Configuring the AWS CLI](docs/04-configuring-awscli.md)
* [Access to Database Backups](docs/05-accessing-database-backups.md)
* [Plain Format Database Backups](docs/06-plain-format-backups.md)
* [Directory Format Database Backups](docs/07-directory-format-backups.md)
* [Access to Log Files](docs/08-accessing-logs.md)
* [Access to Moodle Content](docs/09-accessing-moodle-content.md)
* [Fileless Course Backups](docs/10-fileless-course-backups.md)
* [Using S3 Event Notifications](docs/11-s3-event-notifications.md)
