## Version 0.3.1 2013-05-23

* Use the "alternate" object writing syntax. The primary method (as documented)
  only uploads the path itself rather than the file.

## Version 0.3.0 2013-05-23

* Pass the file path directly to aws-sdk to prevent upload timeouts stemming
  incorrect `content_length`.

## Version 0.2.1 2013-04-20

* Provide a `to_file` method on AWS::File in an attempt to prevent errors when
  re-uploading a cached file.

## Version 0.2.0 2013-04-19

* Update aws-sdk depdendency to 1.8.5
* Clean up some internal storage object passing

## Version 0.1.1 2013-04-09

* Fix storage bug when if `aws_attributes` is blank [#1]

## Version 0.1.0 2013-02-04

* Initial release, experimental with light expectation based spec coverage.
