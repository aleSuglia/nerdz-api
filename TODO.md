TODO
====

+ Complete full refactoring (needs to drop every specific method in favour of generics)
+ Complete the implementation of existing* interface
+ Make everything works again
+ Rewrite tests using new methods and syntax

+ Fixes the ORM issue related to the primary key value (drops the tables if is zero)
+ Add a method for every user action (follow, update post/comment, create things and so on)
+ Obviously write test for every method
+ Use of [Osin](https://github.com/RangelReale/osin) to create OAuth 2 authorization server
+ Create database support (OAuth2 needs to store lots of values)
+ Create HTTP REST API, following some standard (oData maybe?)

And so on...


# What has been done

+ Created types (ORM model)
+ Fetch comments and posts (with related options: from friends only, in a language only and these options can be mixed).
+ Add/Del comment/post
+ Rereiving user information (numeric (fast) or complete)
+ ...

Contributed to the [gorm](https://github.com/jinzhu/gorm/) project several times:

- [Add support for primary key different from id](https://github.com/jinzhu/gorm/pull/85)
- [Add support to fields with double quotes](https://github.com/jinzhu/gorm/pull/105)
- ...
- ...