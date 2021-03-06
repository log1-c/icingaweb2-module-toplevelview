# Change Log

## [v0.3.1](https://github.com/Icinga/icingaweb2-module-toplevelview/tree/v0.3.1) (2019-03-06)
[Full Changelog](https://github.com/Icinga/icingaweb2-module-toplevelview/compare/v0.3.0...v0.3.1)

**Fixed bugs:**

- Implement Notification Period ignoring for TLVServiceNode [\#36](https://github.com/Icinga/icingaweb2-module-toplevelview/pull/36) ([lazyfrosch](https://github.com/lazyfrosch))
- HostgroupsummaryQuery: Ignore hostgroups that are empty [\#35](https://github.com/Icinga/icingaweb2-module-toplevelview/pull/35) ([lazyfrosch](https://github.com/lazyfrosch))

## [v0.3.0](https://github.com/Icinga/icingaweb2-module-toplevelview/tree/v0.3.0) (2019-02-28)
[Full Changelog](https://github.com/Icinga/icingaweb2-module-toplevelview/compare/v0.2.1...v0.3.0)

**Implemented enhancements:**

- Allow ignoring a list of notification periods for handled problems [\#34](https://github.com/Icinga/icingaweb2-module-toplevelview/pull/34) ([lazyfrosch](https://github.com/lazyfrosch))

**Closed issues:**

- You need the PHP extension "yaml" in order to use TopLevelView \(rh-php71\) [\#33](https://github.com/Icinga/icingaweb2-module-toplevelview/issues/33)

## [v0.2.1](https://github.com/Icinga/icingaweb2-module-toplevelview/tree/v0.2.1) (2018-02-13)
[Full Changelog](https://github.com/Icinga/icingaweb2-module-toplevelview/compare/v0.2.0...v0.2.1)

**Fixed bugs:**

- UTC timeperiod calculation is wrong [\#29](https://github.com/Icinga/icingaweb2-module-toplevelview/issues/29)

**Merged pull requests:**

- Don't use UTC timestamps for calculating timeperiods [\#30](https://github.com/Icinga/icingaweb2-module-toplevelview/pull/30) ([lazyfrosch](https://github.com/lazyfrosch))

## [v0.2.0](https://github.com/Icinga/icingaweb2-module-toplevelview/tree/v0.2.0) (2018-01-25)
[Full Changelog](https://github.com/Icinga/icingaweb2-module-toplevelview/compare/v0.1.0...v0.2.0)

**Implemented enhancements:**

- style: Update handled colors with material design [\#28](https://github.com/Icinga/icingaweb2-module-toplevelview/pull/28) ([lazyfrosch](https://github.com/lazyfrosch))

**Fixed bugs:**

- Undefined index: unknown coming from TLVServiceNode [\#22](https://github.com/Icinga/icingaweb2-module-toplevelview/issues/22)

**Closed issues:**

- Apply monitoring filter to views [\#25](https://github.com/Icinga/icingaweb2-module-toplevelview/issues/25)
- Document requirement for Icingaweb2 \>= 2.5.0 [\#23](https://github.com/Icinga/icingaweb2-module-toplevelview/issues/23)
- You need the PHP extension "yaml" in order to use TopLevelView [\#21](https://github.com/Icinga/icingaweb2-module-toplevelview/issues/21)

## [v0.1.0](https://github.com/Icinga/icingaweb2-module-toplevelview/tree/v0.1.0) (2017-10-17)
**Implemented enhancements:**

- Add documentation [\#15](https://github.com/Icinga/icingaweb2-module-toplevelview/issues/15)
- Add badges [\#8](https://github.com/Icinga/icingaweb2-module-toplevelview/issues/8)
- Activate auto-reload and show counter [\#6](https://github.com/Icinga/icingaweb2-module-toplevelview/issues/6)
- Add caching layer [\#3](https://github.com/Icinga/icingaweb2-module-toplevelview/issues/3)
- Integrate notification\_period behavior [\#2](https://github.com/Icinga/icingaweb2-module-toplevelview/issues/2)
- Add documentation [\#19](https://github.com/Icinga/icingaweb2-module-toplevelview/pull/19) ([lazyfrosch](https://github.com/lazyfrosch))
- Add caching layer [\#9](https://github.com/Icinga/icingaweb2-module-toplevelview/pull/9) ([lazyfrosch](https://github.com/lazyfrosch))

**Fixed bugs:**

- host\_never\_unhandled should affect service\_handled [\#20](https://github.com/Icinga/icingaweb2-module-toplevelview/issues/20)
- Host down should be visible [\#7](https://github.com/Icinga/icingaweb2-module-toplevelview/issues/7)
- Auto create missing config dir [\#5](https://github.com/Icinga/icingaweb2-module-toplevelview/issues/5)

**Closed issues:**

- Make notification\_period an option [\#18](https://github.com/Icinga/icingaweb2-module-toplevelview/issues/18)
- Fix single services in convert [\#17](https://github.com/Icinga/icingaweb2-module-toplevelview/issues/17)
- Add de\_DE translation [\#16](https://github.com/Icinga/icingaweb2-module-toplevelview/issues/16)
- Config option for host handled [\#14](https://github.com/Icinga/icingaweb2-module-toplevelview/issues/14)
- Add docker test and dev environment [\#13](https://github.com/Icinga/icingaweb2-module-toplevelview/issues/13)
- Config Files should be created with group write permission [\#12](https://github.com/Icinga/icingaweb2-module-toplevelview/issues/12)
- SOFT states should be ignored [\#11](https://github.com/Icinga/icingaweb2-module-toplevelview/issues/11)
- Convert in downtime and notifications disabled to a downtime state [\#10](https://github.com/Icinga/icingaweb2-module-toplevelview/issues/10)

**Merged pull requests:**

- Add CLI convert tool for sqlite database [\#1](https://github.com/Icinga/icingaweb2-module-toplevelview/pull/1) ([lazyfrosch](https://github.com/lazyfrosch))



\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*