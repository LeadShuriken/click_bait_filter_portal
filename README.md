# CLICKBAIT-FILTER-PORTAL

[![ClickBaitSite](https://click-bait-filtering-plugin.com/assets/images/icon-128-122x122.png)](https://click-bait-filtering-plugin.com/index.html)

## Description

This application is a part of a group of services who plot to rid the web of clickbait by relying on user input and machine learnig. The completed application functions by storing it’s user clicked items and using them to disseminate what is clickbait and what is legitimate news, stories, etc. This is done in conjunction with a machine learning classificator. The full application functions on all sites and thus can allow you to be more productive while browsing the web. It functions by providing the user with a slider giving him possibility to filter content, deemed clickbait and at the same time highlight content that is deemed not. In addition it can show it’s user a topology of the most clickbaity content of each domain.
</br>
</br>
This application is a service/information portal for the Click Bait Filtering Plugin. For more info visit the deployed application [CLICKBAIT-PORTAL] and download the build of this plugin from the [CHROME-STORE].

## Technologies

CLICKBAIT-FILTER-PORTAL uses a number of open source projects:

  * [MOBIRISE] - OFFLINE WEBSITE BUILDER

## Applications Scopes

This service is a part of a multi application project that features the following git repositories:

| Service Name                                  | Description                         | Maintainer              |
| ----------------------------------------      |:------------------------------------|:------------------------|
| [click_bait_filter_extension]                 | Chrome Extensions Plugin            | [LeadShuriken]          |
| [click_bait_filter_be]\(TEST_SERVER)           | Node Application Test Server        | [LeadShuriken]          |
| [click_bait_filter_j]                         | Spring Production Server            | [LeadShuriken]          |
| [click_bait_filter_tflow]                     | Java Tensor Flow Server             | [LeadShuriken]          |
| [click_bait_filter_ml]                        | TensorFlow Model Generator/Updater  | [LeadShuriken]          |
| [click_bait_filter_portal]                    | Service and Information Portal      | [LeadShuriken]          |


For development the application should have the following structure:
```sh
 | .
 | +-- click_bait_filter_extension
 | +-- click_bait_filter_be
 | +-- click_bait_filter_j
 | +-- click_bait_filter_tflow
 | +-- click_bait_filter_ml
 | +-- click_bait_filter_portal
```
This is as the 'click_bait_filter_ml' uses the 'click_bait_filter_be' api's for filtering links. 'click_bait_filter_portal' is just static html which can preside anywhere. 

## Installation

Given that this is generated HTML, CSS and JAVASCRIPT there is no set up needed. The deployed result can be seen at [CLICKBAIT-PORTAL] as well as staticaly served locally.

### Todos

 - Tests and Docs

  [MOBIRISE]: <https://mobirise.com>

  [click_bait_filter_extension]: <https://github.com/LeadShuriken/click_bait_filter_extension>
  [click_bait_filter_be]: <https://github.com/LeadShuriken/click_bait_filter_be>
  [click_bait_filter_ml]: <https://github.com/LeadShuriken/click_bait_filter_ml>
  [click_bait_filter_portal]: <https://github.com/LeadShuriken/click_bait_filter_portal>
  [click_bait_filter_j]: <https://github.com/LeadShuriken/click_bait_filter_j>
  [click_bait_filter_tflow]: <https://github.com/LeadShuriken/click_bait_filter_tflow>

  [LeadShuriken]: <https://github.com/LeadShuriken>

  [CHROME-STORE]: <https://chrome.google.com/webstore/detail/clickbait-filtering-plugi/mgebfihfmenffogbbjlcljgaedfciogm>
  [CLICKBAIT-PORTAL]: <https://click-bait-filtering-plugin.com>

  [MONGO CONNECTION STRING]: <https://docs.mongodb.com/manual/reference/connection-string>
