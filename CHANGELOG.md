# Migration Manager Changelog

## 3.0.0 - 2018-04-19
### Added
- Initial release for Craft 3

## 3.0.1 - 2018-04-20
### Fixed
- Edition check for user group permissions

## 3.0.2 - 2018-04-23
### Fixed
- Exporting of Redactor field 
- SuperTable field export no longer throws errors
- Removed unnecessary asset bundle for sidebar
- Field migrations for Matrix and SuperTable fixed to prevent orphaned data

## 3.0.3 - 2018-04-25
### Fixed
- Deprecation errors in templates
- Null value when creating Asset Volume migration

## 3.0.4 - 2018-04-26
### Fixed
- Fixed escaping for backslashes in settings

## 3.0.5 - 2018-04-26
### Fixed
- Fixed volume folder references in Asset and Redactor field settings

## 3.0.6 - 2018-05-02
### Fixed
- Fixed query table prefix error when retrieving field groups

## 3.0.7 - 2018-05-03
### Fixed
- Retrieve default site handle instead of using 'default'
- Better error reporting for Entry errors

## 3.0.8 - 2018-05-10
### Fixed
- Fixed a template issue when migrations run with 'backupOnUpdate' set to 'false'

## 3.0.9 - 2018-05-25
### Fixed
- Fixed json decoding that resulted in null migration error

## 3.0.10 - 2018-05-31
### Fixed
- Fixed null field error for empty content migrations

## 3.0.11 - 2018-07-06
### Fixed
- Fixed entry dates for content migrations
- Fixed invalid volume error when exporting asset fields
- Fixed null item error for custom field types




