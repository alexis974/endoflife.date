---
title: PHPMyAdmin
category: server-app
iconSlug: phpmyadmin
permalink: /phpmyadmin
releasePolicyLink: https://www.phpmyadmin.net/downloads/#support
changelogTemplate: https://www.phpmyadmin.net/files/__LATEST__/
activeSupportColumn: true
releaseDateColumn: true
releaseColumn: true

auto:
-   git: https://github.com/phpmyadmin/phpmyadmin.git
    regex: '^RELEASE_(?<major>\d+)_(?<minor>\d+)_(?<patch>\d+)(_(?<tiny>\d+))?$'
    template: '{{major}}.{{minor}}.{{patch}}{%if tiny %}.{{tiny}}{%endif%}'

releases:
-   releaseCycle: "5.2"
    releaseDate: 2022-05-11
    support: true
    eol: false
    latest: "5.2.1"
    latestReleaseDate: 2023-02-07

-   releaseCycle: "5.1"
    releaseDate: 2021-02-24
    support: 2022-05-11
    eol: 2022-05-11
    latest: "5.1.4"
    latestReleaseDate: 2022-05-11

-   releaseCycle: "5.0"
    releaseDate: 2019-12-26
    support: 2021-02-24
    eol: 2021-02-24
    latest: "5.0.4"
    latestReleaseDate: 2020-10-15

-   releaseCycle: "4.9"
    releaseDate: 2019-06-04
    support: 2019-12-31
    eol: false
    lts: true
    latest: "4.9.11"
    latestReleaseDate: 2023-02-07

-   releaseCycle: "4.8"
    releaseDate: 2018-04-07
    support: 2019-06-04
    eol: 2019-06-04
    latest: "4.8.5"
    latestReleaseDate: 2019-01-25

-   releaseCycle: "4.7"
    releaseDate: 2017-03-29
    support: 2018-04-07
    eol: 2018-04-07
    latest: "4.7.9"
    latestReleaseDate: 2018-03-05

-   releaseCycle: "4.6"
    releaseDate: 2016-03-17
    support: 2017-04-01
    eol: 2017-04-01
    latest: "4.6.6"
    latestReleaseDate: 2017-01-23

-   releaseCycle: "4.5"
    releaseDate: 2015-09-23
    support: 2016-04-01
    eol: 2016-04-01
    latest: "4.5.5.1"
    latestReleaseDate: 2016-02-29

-   releaseCycle: "4.4"
    releaseDate: 2015-04-01
    support: 2016-10-01
    eol: 2016-10-01
    latest: "4.4.15.10"
    latestReleaseDate: 2017-01-23

-   releaseCycle: "4.3"
    releaseDate: 2014-12-05
    support: 2015-10-01
    eol: 2015-10-01
    latest: "4.3.13.3"
    latestReleaseDate: 2015-09-09

-   releaseCycle: "4.2"
    releaseDate: 2014-05-08
    support: 2015-07-01
    eol: 2015-07-01
    latest: "4.2.13.3"
    latestReleaseDate: 2015-05-13

-   releaseCycle: "4.1"
    releaseDate: 2013-12-11
    support: 2015-01-01
    eol: 2015-01-01
    latest: "4.1.14.8"
    latestReleaseDate: 2014-12-03

-   releaseCycle: "4.0"
    releaseDate: 2013-05-03
    support: 2013-12-31
    eol: 2017-04-01
    lts: true
    latest: "4.0.10.20"
    latestReleaseDate: 2017-03-28

---

> [PHPMyAdmin](https://www.phpmyadmin.net/) is a free software tool written in PHP, intended to
> handle the administration of MySQL over the Web. phpMyAdmin supports a wide range of operations on
> MySQL and MariaDB.

Only the last release is usually supported. LTS branches are also maintained (security fixes only)
to support older PHP versions.

## Compatibility Matrix

| PHPMyAdmin | PHP          | MySQL/MariaDB |
|------------|--------------|:--------------|
| 5.2        | >=7.2        | >= 5.5        |
| 5.0 - 5.1  | >=7.1        | >= 5.5        |
| 4.9        | >=5.5, <=7.4 | >= 5.5        |
| 4.8        | >=5.5, <=7.2 | >= 5.5        |
| 4.6 - 4.7  | >=5.5, <=7.1 | >= 5.5        |
| 4.5        | >=5.5, <=7.0 | >= 5.5        |
| 4.4        | >=5.3, <=7.0 | >= 5.5        |
| 4.1 - 4.3  | >=5.3, <=5.6 | >= 5.5        |
| 4.0        | >=5.2, <=5.4 | >= 5          |
