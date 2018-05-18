# Week7
# Project 7 - WordPress 4.2 Pentesting

Time spent: **X** hours spent in total

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

## Pentesting Report

1. (Required) Vulnerability Name or ID: Unauthenticated Stored Cross-Site Scripting(XSS) CVE-2015-3440
  - [ ] Summary: 
    - Vulnerability types: XSS
    - Tested in version: 4.2
    - Fixed in version: 4.2.1
  - [ ] GIF Walkthrough: 
![xss1](https://user-images.githubusercontent.com/38142630/40223455-f649f7a6-5a37-11e8-8dd5-79c05f2cce72.gif) 
  - [ ] Steps to recreate: Insert the tag into the comment section. The comment must be 64kb or larger because due to the large length size it will be truncated by the database.The result is the malformed HTML displayed.
  - [ ] Affected source code: None, it was stored into the database and executes each time it is viewed.
    - [Link 1](https://klikki.fi/adv/wordpress2.html)
1. (Required) Vulnerability Name or ID: User Enumeration
  - [ ] Summary: 
    - Vulnerability types:User Enumeration
    - Tested in version: 4.2
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
  ![user_enum2](https://user-images.githubusercontent.com/38142630/40225432-df84c6ee-5a3d-11e8-8bc5-ace7650c2cf4.gif)
  - [ ] Steps to recreate: Modify the url to query ?author=value in order to view the corresponding username
  - [ ] Affected source code: None
    - [Link 1](https://hackertarget.com/wordpress-user-enumeration/)
    - [Link 2](https://perishablepress.com/stop-user-enumeration-wordpress/)
1. (Required) Vulnerability Name or ID
  - [ ] Summary: 
    - Vulnerability types:
    - Tested in version:
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: 
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
1. (Optional) Vulnerability Name or ID
  - [ ] Summary: 
    - Vulnerability types:
    - Tested in version:
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: 
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
1. (Optional) Vulnerability Name or ID
  - [ ] Summary: 
    - Vulnerability types:
    - Tested in version:
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: 
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php) 

## Assets

List any additional assets, such as scripts or files

## Resources

- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)
- [WordPress Developer Reference](https://developer.wordpress.org/reference/)

GIFs created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while doing the work

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
