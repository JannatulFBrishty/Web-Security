# Project 7 - WordPress Pentesting

Time spent: 16 hours spent in total

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

## Pentesting Report

1. (Required) User Enumeration
  - [ ] Summary: 
    - Vulnerability types:User enumeration
    - Tested in version:4.2
    - Fixed in version: 4.7.5
  - [ ] GIF Walkthrough: 
  ![](https://github.com/JannatulFBrishty/Web-Security/blob/master/Week7/User%20enumeration.gif)
  - [ ] Steps to recreate: 
  Enter same user ID and different passwrod to check and then enter different used ID and same passwrod to check.
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
2. (Required) Authenticated Stored Cross-Site Scripting (XSS) in YouTube URL Embeds
  - [ ] Summary: 
    - Vulnerability types:XSS
    - Tested in version:4.2
    - Fixed in version:  4.2.13
  - [ ] GIF Walkthrough: 
  ![](https://github.com/JannatulFBrishty/Web-Security/blob/master/Week7/Authenticated%20Stored%20Cross-Site%20Scripting%20(XSS)%20in%20YouTube%20URL%20Embeds.gif)
  - [ ] Steps to recreate:
  Add new post. Then copy the following link to the text editor and Publish. 
  View post!
  - [ ] Affected source code:
    - [Link 2](https://github.com/WordPress/WordPress/commit/419c8d97ce8df7d5004ee0b566bc5e095f0a6ca8)
3. (Required) Authenticated Stored Cross-Site Scripting (XSS)
  - [ ] Summary: 
    - Vulnerability types:XSS
    - Tested in version:4.2
    - Fixed in version: 4.0.16
  - [ ] GIF Walkthrough: 
  ![](https://github.com/JannatulFBrishty/Web-Security/blob/master/Week7/Authenticated%20Stored%20Cross-Site%20Scripting%20(XSS).gif)
  - [ ] Steps to recreate: Edit an existing post with the code as given in the gif. 
  Publish.
  View post!
  - [ ] Affected source code:
    - [Link 3](https://core.trac.wordpress.org/browser/tags/4.0.16/src/wp-admin/post-new.php)
4. Malicious Filename
  - [ ] Summary: 
    - Vulnerability types:XSS
    - Tested in version: 4.2
    - Fixed in version: 4.6.1
  - [ ] GIF Walkthrough: 
  ![](https://github.com/JannatulFBrishty/Web-Security/blob/master/Week7/Xss3.gif)
  - [ ] Steps to recreate: Add new post with the following click me link as the gif above.
  Publish.
  View!
  - [ ] Affected source code:
    - [Link 4](https://github.com/WordPress/WordPress/commit/c9e60dab176635d4bfaaf431c0ea891e4726d6e0)

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
