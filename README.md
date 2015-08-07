# Passmarked README Specs

![Passmarked Text Logo](http://static.passmarked.com/text64.png)

Community descriptions of the specs for use on [passmarked.com](http://passmarked.com) to describe and provide descriptions for each of our tests.

These contents are made public with the intent for the community at large to use and help improve. 

Our system pulls from the **#master** branch to display the information when we show results to help users fix any issues we may have found on their websites.

# Contribute

We love contributions !

Read about our file structure and view a few **pull-requests** to get a sense of our community. Then fork and make changes to improve the documentation, we'll review any **pull-request** and merge making it live on [passmarked.com](http://passmarked.com) to help users fix issues on their websites !

We have a active team on **#Slack** for discussions, login on [passmarked.com](http://passmarked.com) to help us decide on rule importance and receive a invite.

# File Structure

**Passmarked** allows browsing and viewing rules that explains.

## {category}/readme.md

Overall description to what is checked in the category. This is aimed to provide general overview at to what the users can expect for any tests listed in the category.

Example [compatibility/readme.md](https://github.com/passmarked/suite/blob/master/compatibility/readme.md)

## {category}/{test}/readme.md

General description of the goals for the test and examples of why it's necessary to check for these issues.

Example [compatibility/html/readme.md](https://github.com/passmarked/suite/blob/master/compatibility/html/readme.md)

## {category}/{test}/rule.md

The overview of what the rule entails and how to fix it. This is intended to be shown for users when the problem is detected on their page.

Each **README** should contain atleast:

* what the problem is and why it affects users as part of the selected category and test
* how to go about fixing the issue, on various platforms if applicable
* links to more resources if the user is interested

Example [compatibility/html/attribute-not-allowed-on-element-at-this-point.md](https://github.com/passmarked/suite/blob/master/compatibility/html/attribute-not-allowed-on-element-at-this-point.md)

# License

Copyright 2015 **Passmarked Inc**

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. 

You may obtain a copy of the License at [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.

See the License for the specific language governing permissions and limitations under the License.