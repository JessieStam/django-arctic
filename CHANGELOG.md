#Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) 
and this project adheres to [Semantic Versioning](http://semver.org/).

Always reference the ticket number at the end of the issue description.


##0.9.6 (2017-04-25)

###Changed

- Added support for read-only fields in update view - [#72][72]
- Added support for media assets in Views and default templates - [#195][195]
- Bumped django-filters to 1.0.1 and fixed breaking changes - [#171][171]

[72]: //github.com/sanoma/django-arctic/issues/72
[171]: //github.com/sanoma/django-arctic/issues/171
[195]: //github.com/sanoma/django-arctic/issues/195


##0.9.5 (2017-03-16)

###Changed

- Added full Django 1.10 compatibility - [#164][164]
- Added submenu icons display option - [#178][178]
- Considerate improved performance; no query per has_permission call - [#182][182]
- Check that 'next' redirect in the login view only goes to own host - [#186][186]

[164]: //github.com/sanoma/django-arctic/issues/164
[178]: //github.com/sanoma/django-arctic/issues/178
[182]: //github.com/sanoma/django-arctic/issues/182
[186]: //github.com/sanoma/django-arctic/issues/186


##0.9.4 (2017-02-23)

###Changed

- Simplified the frontend tooling, removing Bower and foundation-cli, setup is 
  now based on npm and gulp - [#161][161]

###Fixed

- In the listview, don't generate NoReverseMatch exception if any value of 
  the arguments is None.

[161]: //github.com/sanoma/django-arctic/issues/161


##0.9.3 (2016-10-27)

###Changed

- `FormView`, `CreateView` and `UpdateView` added a `layout` property to 
  easily customize positioning and width of form fields - [#75][75]
- Added support for virtual fields in `ListView` - [#73][73]
- Improved the date/time picker in Date/Time fields - [#78][78]

[73]: //github.com/sanoma/django-arctic/issues/73
[75]: //github.com/sanoma/django-arctic/issues/75
[78]: //github.com/sanoma/django-arctic/issues/78
