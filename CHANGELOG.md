# Supermarket Changelog
<!-- usage documentation: http://expeditor-docs.es.chef.io/configuration/changelog/ -->
<!-- latest_release 3.4.23 -->
## [3.4.23](https://github.com/chef/supermarket/tree/3.4.23) (2021-06-17)

#### Merged Pull Requests
- Bump berkshelf from 7.1.0 to 7.2.2 in /omnibus [#1947](https://github.com/chef/supermarket/pull/1947) ([dependabot[bot]](https://github.com/dependabot[bot]))
<!-- latest_release -->

<!-- release_rollup since=3.4.8 -->
### Changes since 3.4.8 release

#### Security Fixes
- [Security] Bump rexml from 3.2.4 to 3.2.5 in /src/supermarket/engines/fieri [#1910](https://github.com/chef/supermarket/pull/1910) ([dependabot-preview[bot]](https://github.com/dependabot-preview[bot])) <!-- 3.4.9 -->
- [Security] Bump rexml from 3.2.4 to 3.2.5 in /src/supermarket [#1911](https://github.com/chef/supermarket/pull/1911) ([dependabot-preview[bot]](https://github.com/dependabot-preview[bot])) <!-- 3.4.11 -->
- [Security] Bump nokogiri from 1.11.1 to 1.11.5 in /src/supermarket/engines/fieri [#1921](https://github.com/chef/supermarket/pull/1921) ([dependabot-preview[bot]](https://github.com/dependabot-preview[bot])) <!-- 3.4.14 -->
- [Security] Bump nokogiri from 1.11.3 to 1.11.5 in /src/supermarket [#1920](https://github.com/chef/supermarket/pull/1920) ([dependabot-preview[bot]](https://github.com/dependabot-preview[bot])) <!-- 3.4.15 -->
- [Security] Bump actionpack from 5.2.4.5 to 5.2.6 in /src/supermarket/engines/fieri [#1915](https://github.com/chef/supermarket/pull/1915) ([dependabot-preview[bot]](https://github.com/dependabot-preview[bot])) <!-- 3.4.16 -->

#### Merged Pull Requests
- Bump berkshelf from 7.1.0 to 7.2.2 in /omnibus [#1947](https://github.com/chef/supermarket/pull/1947) ([dependabot[bot]](https://github.com/dependabot[bot])) <!-- 3.4.23 -->
- Update PostgreSQL to 9.3.25 [#1977](https://github.com/chef/supermarket/pull/1977) ([tas50](https://github.com/tas50)) <!-- 3.4.22 -->
- Bump omnibus-software from `bdb61f0` to `68f693d` in /omnibus [#1976](https://github.com/chef/supermarket/pull/1976) ([dependabot[bot]](https://github.com/dependabot[bot])) <!-- 3.4.21 -->
- Bump kitchen-vagrant from 1.6.1 to 1.8.0 in /omnibus [#1946](https://github.com/chef/supermarket/pull/1946) ([dependabot[bot]](https://github.com/dependabot[bot])) <!-- 3.4.20 -->
- Bump test-kitchen from 2.5.4 to 2.12.0 in /omnibus [#1944](https://github.com/chef/supermarket/pull/1944) ([dependabot[bot]](https://github.com/dependabot[bot])) <!-- 3.4.19 -->
- Bump omnibus-software from `a7ed951` to `bdb61f0` in /omnibus [#1945](https://github.com/chef/supermarket/pull/1945) ([dependabot[bot]](https://github.com/dependabot[bot])) <!-- 3.4.18 -->
- Bump omnibus from `f8f202c` to `87db446` in /omnibus [#1929](https://github.com/chef/supermarket/pull/1929) ([dependabot[bot]](https://github.com/dependabot[bot])) <!-- 3.4.17 -->
- Update Rails to 5.2.5 [#1912](https://github.com/chef/supermarket/pull/1912) ([tas50](https://github.com/tas50)) <!-- 3.4.10 -->
- Update Ruby to 2.6.7 [#1913](https://github.com/chef/supermarket/pull/1913) ([tas50](https://github.com/tas50)) <!-- 3.4.12 -->
- Stop producing Ubuntu 16.04 packages [#1914](https://github.com/chef/supermarket/pull/1914) ([tas50](https://github.com/tas50)) <!-- 3.4.13 -->
<!-- release_rollup -->

<!-- latest_stable_release -->
## [3.4.8](https://github.com/chef/supermarket/tree/3.4.8) (2021-06-17)

#### Security Fixes
- [Security] Bump nokogiri from 1.10.10 to 1.11.0 in /src/supermarket [#1901](https://github.com/chef/supermarket/pull/1901) ([dependabot-preview[bot]](https://github.com/dependabot-preview[bot]))
- [Security] Bump nokogiri from 1.10.10 to 1.11.1 in /src/supermarket/engines/fieri [#1902](https://github.com/chef/supermarket/pull/1902) ([dependabot-preview[bot]](https://github.com/dependabot-preview[bot]))
- [Security] Bump redcarpet from 3.4.0 to 3.5.1 in /src/supermarket [#1904](https://github.com/chef/supermarket/pull/1904) ([dependabot-preview[bot]](https://github.com/dependabot-preview[bot]))
- [Security] Bump activerecord from 5.2.4.4 to 5.2.4.5 in /src/supermarket/engines/fieri [#1905](https://github.com/chef/supermarket/pull/1905) ([dependabot-preview[bot]](https://github.com/dependabot-preview[bot]))

#### Maintenance Updates
- support PostgreSQL 9.6+ [#1895](https://github.com/chef/supermarket/pull/1895) ([robbkidd](https://github.com/robbkidd))

#### Merged Pull Requests
- clarification for cookbook transfer policy [#1886](https://github.com/chef/supermarket/pull/1886) ([bennyvasquez](https://github.com/bennyvasquez))
- bump openssl-1.0.2y [#1906](https://github.com/chef/supermarket/pull/1906) ([dheerajd-msys](https://github.com/dheerajd-msys))
<!-- latest_stable_release -->

## [3.4.1](https://github.com/chef/supermarket/tree/3.4.1) (2020-11-20)

#### Bug Fixes
- disambiguate columns used in query ordering [#1893](https://github.com/chef/supermarket/pull/1893) ([robbkidd](https://github.com/robbkidd))
- Fix exceptions thrown by displaying an error [#1894](https://github.com/chef/supermarket/pull/1894) ([robbkidd](https://github.com/robbkidd))
- [omnibus] use YAML.dump to serialize simple hashes to disk [#1896](https://github.com/chef/supermarket/pull/1896) ([robbkidd](https://github.com/robbkidd))

#### Security Fixes
- add HTTP strict transport security header when force SSL is enabled [#1855](https://github.com/chef/supermarket/pull/1855) ([robbkidd](https://github.com/robbkidd))

#### Maintenance Updates
- drop support for RHEL6 builds [#1898](https://github.com/chef/supermarket/pull/1898) ([robbkidd](https://github.com/robbkidd))

## [3.3.35](https://github.com/chef/supermarket/tree/3.3.35) (2020-09-29)

#### Security Fixes
- update deps: includes nginx 1.18.0 (addresses CVE-2019-20372 tripping up scanners) [#1874](https://github.com/chef/supermarket/pull/1874) ([tas50](https://github.com/tas50))
- Update Ruby to 2.6.6 to resolve 2 CVEs [#1877](https://github.com/chef/supermarket/pull/1877) ([tas50](https://github.com/tas50))
- [Security] Bump actionview from 5.2.4.3 to 5.2.4.4 (no CVE in Supermarket itself) [#1887](https://github.com/chef/supermarket/pull/1887) ([dependabot-preview[bot]](https://github.com/dependabot-preview[bot]))

#### Enhancements
- Add support for enabling Server Side Encryption when storing cookbooks in AWS S3 [#1888](https://github.com/chef/supermarket/pull/1888) ([bdwyertech](https://github.com/bdwyertech))

#### Maintenance Updates
- Update Foodcritic from 14.3 to 16.3 [#1881](https://github.com/chef/supermarket/pull/1881) ([tas50](https://github.com/tas50))

#### Merged Pull Requests
- add packages for Amazon Linux 2 to the pipeline [#1875](https://github.com/chef/supermarket/pull/1875) ([tas50](https://github.com/tas50))
- Bump Cookstyle / Chefstyle to the latest [#1882](https://github.com/chef/supermarket/pull/1882) ([tas50](https://github.com/tas50))
- Require Chef 14+ in omnibus now [#1883](https://github.com/chef/supermarket/pull/1883) ([tas50](https://github.com/tas50))

## [3.3.26](https://github.com/chef/supermarket/tree/3.3.26) (2020-07-07)

#### Security Fixes
- [Security] Bump rack from 2.0.8 to 2.2.2 in quality metrics engine [#1858](https://github.com/chef/supermarket/pull/1858) ([dependabot-preview[bot]](https://github.com/dependabot-preview[bot]))
- [Security] Bump kaminari from 1.0.1 to 1.2.1 in /src/supermarket [#1862](https://github.com/chef/supermarket/pull/1862) ([dependabot-preview[bot]](https://github.com/dependabot-preview[bot]))
- Rails 5.0 -&gt; 5.1 -&gt; 5.2 upgrade; adoption of ChefStyle [#1867](https://github.com/chef/supermarket/pull/1867) ([robbkidd](https://github.com/robbkidd))
- Bump rack from 2.2.2 to 2.2.3 in /omnibus [#1868](https://github.com/chef/supermarket/pull/1868) ([dependabot[bot]](https://github.com/dependabot[bot]))

#### Merged Pull Requests
- Remove bundler-audit from tests; we&#39;re auditing with GitHub [#1861](https://github.com/chef/supermarket/pull/1861) ([tas50](https://github.com/tas50))
- Resolve upcoming OpenSSL Ruby library deprecation of algorithm constants [#1860](https://github.com/chef/supermarket/pull/1860) ([tas50](https://github.com/tas50))

## [3.3.20](https://github.com/chef/supermarket/tree/3.3.20) (2020-03-16)

#### Security Fixes
- update rubyzip to address CVE-2019-16892 [#1825](https://github.com/chef/supermarket/pull/1825) ([robbkidd](https://github.com/robbkidd))
- Bump loofah from 2.2.3 to 2.3.1 [#1830](https://github.com/chef/supermarket/pull/1830) ([dependabot[bot]](https://github.com/dependabot[bot]))
- update for CVE-2019-13117 &amp; CVE-2019-16782 [#1833](https://github.com/chef/supermarket/pull/1833) ([robbkidd](https://github.com/robbkidd))
- Bump rack from 2.0.7 to 2.0.8 in /omnibus [#1834](https://github.com/chef/supermarket/pull/1834) ([dependabot[bot]](https://github.com/dependabot[bot]))
- include secrets found in secrets.json in runtime omnibus config [#1832](https://github.com/chef/supermarket/pull/1832) ([robbkidd](https://github.com/robbkidd))
- Bump nokogiri from 1.10.7 to 1.10.9 [#1848](https://github.com/chef/supermarket/pull/1848) ([dependabot-preview[bot]](https://github.com/dependabot-preview[bot]))
- Bump rake from 12.3.2 to 13.0.1 [#1844](https://github.com/chef/supermarket/pull/1844) ([dependabot-preview[bot]](https://github.com/dependabot-preview[bot]))
- Bump omniauth from 1.9.0 to 1.9.1 [#1851](https://github.com/chef/supermarket/pull/1851) ([dependabot-preview[bot]](https://github.com/dependabot-preview[bot]))
- generate secrets.json with warning messages [#1849](https://github.com/chef/supermarket/pull/1849) ([robbkidd](https://github.com/robbkidd))
- Prevent unsafe links to cross-origin destinations [#1846](https://github.com/chef/supermarket/pull/1846) ([cattywampus](https://github.com/cattywampus))

#### Merged Pull Requests
- add a version command to supermarket-ctl [#1811](https://github.com/chef/supermarket/pull/1811) ([robbkidd](https://github.com/robbkidd))
- avoid Double Bundler by pinning rubygems version [#1835](https://github.com/chef/supermarket/pull/1835) ([robbkidd](https://github.com/robbkidd))
- upgrade Ruby to 2.6.5 [#1852](https://github.com/chef/supermarket/pull/1852) ([robbkidd](https://github.com/robbkidd))

## [3.3.7](https://github.com/chef/supermarket/tree/3.3.7) (2019-09-18)

#### Security Fixes
- update packaged OpenSSL to 1.0.2s [#1813](https://github.com/chef/supermarket/pull/1813) ([robbkidd](https://github.com/robbkidd))
- update to use curl 7.65.0 [#1814](https://github.com/chef/supermarket/pull/1814) ([robbkidd](https://github.com/robbkidd))
- require POSTs during sign-in (CVE-2015-9284) [#1815](https://github.com/chef/supermarket/pull/1815) ([robbkidd](https://github.com/robbkidd))

#### Merged Pull Requests
- No more Ubuntu 14 builds. Canonical ended support for trusty in April 2019. [#1818](https://github.com/chef/supermarket/pull/1818) ([christopher-snapp](https://github.com/christopher-snapp))
- omnibus build fixes [#1821](https://github.com/chef/supermarket/pull/1821) ([robbkidd](https://github.com/robbkidd))

## [3.3.3](https://github.com/chef/supermarket/tree/3.3.3) (2019-05-15)

#### Security Fixes
- upgrade nokogiri (CVE-2019-11068) [#1808](https://github.com/chef/supermarket/pull/1808) ([robbkidd](https://github.com/robbkidd))

#### Bug Fixes
- fix upload error when cookbook tarball uid/gid is very large [#1810](https://github.com/chef/supermarket/pull/1810) ([robbkidd](https://github.com/robbkidd))
- fix upload error when cookbook tarball uid/gid is very large [#1810](https://github.com/chef/supermarket/pull/1810) ([robbkidd](https://github.com/robbkidd))
- fix upload error when cookbook tarball uid/gid is very large [#1810](https://github.com/chef/supermarket/pull/1810) ([robbkidd](https://github.com/robbkidd))
- fix upload error when cookbook tarball uid/gid is very large [#1810](https://github.com/chef/supermarket/pull/1810) ([robbkidd](https://github.com/robbkidd))

## [3.3.1](https://github.com/chef/supermarket/tree/3.3.1) (2019-04-19)

#### Enhancements
- add support for S3 storage using IAM roles (IAM user and a key no longer required) [#1747](https://github.com/chef/supermarket/pull/1747) ([pavel-kazhavets](https://github.com/pavel-kazhavets))

#### Bug Fixes
- pin inspec to fix &#39;-ctl test&#39; requiring license acceptance [#1802](https://github.com/chef/supermarket/pull/1802) ([robbkidd](https://github.com/robbkidd))

## [3.2.2](https://github.com/chef/supermarket/tree/3.2.2) (2019-03-14)

#### Merged Pull Requests
- upgrade omnibus-embedded nginx [#1790](https://github.com/chef/supermarket/pull/1790) ([robbkidd](https://github.com/robbkidd))
- upgrade OpenSSL, RubyGems, and Rails to address multiple CVEs [#1798](https://github.com/chef/supermarket/pull/1798) ([robbkidd](https://github.com/robbkidd))

## [3.2.0](https://github.com/chef/supermarket/tree/3.2.0) (2018-12-20)

#### Enhancements
- add FIPS 140-2 support [#1768](https://github.com/chef/supermarket/pull/1768) ([robbkidd](https://github.com/robbkidd))

## [3.1.96](https://github.com/chef/supermarket/tree/3.1.96) (2018-12-13)

#### Security Fixes
- update Rails to 5.0.7.1 [#1784](https://github.com/chef/supermarket/pull/1784) ([robbkidd](https://github.com/robbkidd))
- update rack (&amp; other gems) in the omnibus build environment [#1785](https://github.com/chef/supermarket/pull/1785) ([robbkidd](https://github.com/robbkidd))

#### Merged Pull Requests
- update rack for CVE-2018-16471 [#1782](https://github.com/chef/supermarket/pull/1782) ([robbkidd](https://github.com/robbkidd))
- update omnibus to use latest enterprise cookbook [#1788](https://github.com/chef/supermarket/pull/1788) ([robbkidd](https://github.com/robbkidd))
- RFC072 Artifact Yanking: disallow cookbook removal by owner [#1789](https://github.com/chef/supermarket/pull/1789) ([robbkidd](https://github.com/robbkidd))

## [3.1.91](https://github.com/chef/supermarket/tree/3.1.91) (2018-11-01)

#### Bug Fixes
-  fix search engines knowing the correct cookbook create/update datetimes [#1779](https://github.com/chef/supermarket/pull/1779) ([robbkidd](https://github.com/robbkidd))

#### Merged Pull Requests
- update nokogiri to quiet CVE audit [#1771](https://github.com/chef/supermarket/pull/1771) ([robbkidd](https://github.com/robbkidd))
- update omnibus ctl test command for Inspec 3.0 [#1772](https://github.com/chef/supermarket/pull/1772) ([robbkidd](https://github.com/robbkidd))
- reduce package size with compression for omnibus DEB &amp; RPM configs [#1770](https://github.com/chef/supermarket/pull/1770) ([tas50](https://github.com/tas50))
- Update Ruby to 2.5.3 [#1769](https://github.com/chef/supermarket/pull/1769) ([tas50](https://github.com/tas50))
- Update Foodcritic to 14.3 [#1773](https://github.com/chef/supermarket/pull/1773) ([tas50](https://github.com/tas50))
- update to latest omnibus and omnibus-software definitions [#1774](https://github.com/chef/supermarket/pull/1774) ([scotthain](https://github.com/scotthain))
- bring omnibus-internal cookbook up to Chef 14 standards [#1748](https://github.com/chef/supermarket/pull/1748) ([tas50](https://github.com/tas50))
- upgrade rails to 5.0.7 [#1777](https://github.com/chef/supermarket/pull/1777) ([robbkidd](https://github.com/robbkidd))
- upgrade loofah to 2.2.3 [#1778](https://github.com/chef/supermarket/pull/1778) ([robbkidd](https://github.com/robbkidd))

## [3.1.81](https://github.com/chef/supermarket/tree/3.1.81) (2018-09-25)

#### Bug Fixes
- replace periodic job scheduler with one that is maintained [#1756](https://github.com/chef/supermarket/pull/1756) ([robbkidd](https://github.com/robbkidd))

#### Security Fixes
- update rubyzip [#1766](https://github.com/chef/supermarket/pull/1766) ([rhass](https://github.com/rhass))
- omit web server version from response headers [#1765](https://github.com/chef/supermarket/pull/1765) ([Nimesh-Msys](https://github.com/Nimesh-Msys))

#### Merged Pull Requests
- set session cookie to secure when sent over an HTTPS connection [#1750](https://github.com/chef/supermarket/pull/1750) ([Vasu1105](https://github.com/Vasu1105))
- reorganize the fieri subcomponent to make supermarket more container friendly [#1704](https://github.com/chef/supermarket/pull/1704) ([robbkidd](https://github.com/robbkidd))
- upgrade to OpenSSL 1.0.2p [#1752](https://github.com/chef/supermarket/pull/1752) ([robbkidd](https://github.com/robbkidd))
- habitat skeleton to get started [#1761](https://github.com/chef/supermarket/pull/1761) ([jtimberman](https://github.com/jtimberman))
- change &quot;knife cookbook site&quot; references to &quot;knife supermarket&quot; [#1762](https://github.com/chef/supermarket/pull/1762) ([tas50](https://github.com/tas50))
- update ffi gem to reduce CVE audit noise [#1763](https://github.com/chef/supermarket/pull/1763) ([robbkidd](https://github.com/robbkidd))

## [3.1.72](https://github.com/chef/supermarket/tree/3.1.72) (2018-07-19)

#### Merged Pull Requests
- update nokogiri to quiet gem audit finding [#1745](https://github.com/chef/supermarket/pull/1745) ([robbkidd](https://github.com/robbkidd))
- fix markdown rendering links and images with unsafe protocols [#1746](https://github.com/chef/supermarket/pull/1746) ([robbkidd](https://github.com/robbkidd))

## [3.1.70](https://github.com/chef/supermarket/tree/3.1.70) (2018-07-09)

#### Merged Pull Requests
- Upgrade Sprockets [CVE-2018-3760] [#1743](https://github.com/chef/supermarket/pull/1743) ([pwelch](https://github.com/pwelch))
- Update Foodcritic to 14 [#1741](https://github.com/chef/supermarket/pull/1741) ([tas50](https://github.com/tas50))

## [3.1.68](https://github.com/chef/supermarket/tree/3.1.68) (2018-05-16)

#### Merged Pull Requests
- upgrade to Ruby 2.5.1 [#1734](https://github.com/chef/supermarket/pull/1734) ([robbkidd](https://github.com/robbkidd))
- Update Foodcritic to 13.0.1 [#1735](https://github.com/chef/supermarket/pull/1735) ([tas50](https://github.com/tas50))
- Update to Foodcritic 13.1.1 [#1736](https://github.com/chef/supermarket/pull/1736) ([tas50](https://github.com/tas50))
- Remove the librarian wording from the cookbook pages [#1738](https://github.com/chef/supermarket/pull/1738) ([tas50](https://github.com/tas50))
- remove license quality metric (covered by foodcritic rule 78) [#1733](https://github.com/chef/supermarket/pull/1733) ([nathenharvey](https://github.com/nathenharvey))

## [3.1.63](https://github.com/chef/supermarket/tree/3.1.63) (2018-03-26)

#### Merged Pull Requests
- update rails-html-sanitizer (CVE-2018-3741) [#1731](https://github.com/chef/supermarket/pull/1731) ([robbkidd](https://github.com/robbkidd))

## [3.1.62](https://github.com/chef/supermarket/tree/3.1.62) (2018-03-26)

#### Merged Pull Requests
- update loofah (CVE-2018-8048) [#1730](https://github.com/chef/supermarket/pull/1730) ([robbkidd](https://github.com/robbkidd))

## [3.1.61](https://github.com/chef/supermarket/tree/3.1.61) (2018-03-21)

#### Merged Pull Requests
- disable remote fetching in Paperclip [#1719](https://github.com/chef/supermarket/pull/1719) ([robbkidd](https://github.com/robbkidd))
- upgrade to Ruby 2.5.0 [#1722](https://github.com/chef/supermarket/pull/1722) ([robbkidd](https://github.com/robbkidd))
- upgrade nokogiri &amp; libxml2 [#1726](https://github.com/chef/supermarket/pull/1726) ([robbkidd](https://github.com/robbkidd))
- update rack-protection (addresses underlying CVE audit that does not apply to Supermarket installs) [#1728](https://github.com/chef/supermarket/pull/1728) ([robbkidd](https://github.com/robbkidd))
- upgrade Foodcritic to v13.0.0 [#1727](https://github.com/chef/supermarket/pull/1727) ([tas50](https://github.com/tas50))

## [3.1.56](https://github.com/chef/supermarket/tree/3.1.56) (2018-01-24)

#### Merged Pull Requests
- Bump Foodcritic to 12.2.2 [#1708](https://github.com/chef/supermarket/pull/1708) ([tas50](https://github.com/tas50))
- Converge runner with no fork [#1713](https://github.com/chef/supermarket/pull/1713) ([scotthain](https://github.com/scotthain))
- Fix version validation against chef&#39;s required format [#1715](https://github.com/chef/supermarket/pull/1715) ([robbkidd](https://github.com/robbkidd))
- Update Foodcritic to 12.3 [#1717](https://github.com/chef/supermarket/pull/1717) ([tas50](https://github.com/tas50))
- Fix ctl-reconfigure failing in air-gapped environments [#1716](https://github.com/chef/supermarket/pull/1716) ([robbkidd](https://github.com/robbkidd))

## [3.1.51](https://github.com/chef/supermarket/tree/3.1.51) (2017-12-18)

#### Merged Pull Requests
- upgrade version of omnibus-embedded nginx [#1706](https://github.com/chef/supermarket/pull/1706) ([robbkidd](https://github.com/robbkidd))

## [3.1.50](https://github.com/chef/supermarket/tree/3.1.50) (2017-12-08)

#### Merged Pull Requests
- upgrade redis-store to address CVE-2017-1000248 [#1701](https://github.com/chef/supermarket/pull/1701) ([robbkidd](https://github.com/robbkidd))
- fix omnibus build, pin rubygems to 2.6.x [#1703](https://github.com/chef/supermarket/pull/1703) ([robbkidd](https://github.com/robbkidd))
- upgrade omnibus for new openssl [#1702](https://github.com/chef/supermarket/pull/1702) ([robbkidd](https://github.com/robbkidd))

## [3.1.47](https://github.com/chef/supermarket/tree/3.1.47) (2017-12-04)

#### Merged Pull Requests
- Update Foodcritic to 12.1 [#1692](https://github.com/chef/supermarket/pull/1692) ([tas50](https://github.com/tas50))
- InSpec smoke test improvements [#1695](https://github.com/chef/supermarket/pull/1695) ([schisamo](https://github.com/schisamo))
- Use Foodcritic 12.2.1 [#1696](https://github.com/chef/supermarket/pull/1696) ([tas50](https://github.com/tas50))
- Update yajl-ruby [#1697](https://github.com/chef/supermarket/pull/1697) ([robbkidd](https://github.com/robbkidd))
- Convert S3_URLS_EXPIRE to a number on use [#1698](https://github.com/chef/supermarket/pull/1698) ([KierranM](https://github.com/KierranM))

## [3.1.42](https://github.com/chef/supermarket/tree/3.1.42) (2017-10-30)

#### Merged Pull Requests
- add segment.io JS snippet for more analytic options [#1690](https://github.com/chef/supermarket/pull/1690) ([robbkidd](https://github.com/robbkidd))

## [3.1.41](https://github.com/chef/supermarket/tree/3.1.41) (2017-10-25)

#### Merged Pull Requests
- add QM pass rate percentage to search results, show page [#1679](https://github.com/chef/supermarket/pull/1679) ([robbkidd](https://github.com/robbkidd))
- prevent dividing by zero when there are no quality metric results [#1680](https://github.com/chef/supermarket/pull/1680) ([robbkidd](https://github.com/robbkidd))
- add a tooltip to explain the metric pass rate display [#1682](https://github.com/chef/supermarket/pull/1682) ([robbkidd](https://github.com/robbkidd))
- remove some interpolated default attributes for sensible ocid default [#1681](https://github.com/chef/supermarket/pull/1681) ([robbkidd](https://github.com/robbkidd))
- use Forwardable for all the feature flag delegation [#1623](https://github.com/chef/supermarket/pull/1623) ([robbkidd](https://github.com/robbkidd))
- set openssl to install the latest default in omnibus-software [#1683](https://github.com/chef/supermarket/pull/1683) ([robbkidd](https://github.com/robbkidd))
- Upgrade Foodcritic to 12 - new critics for deprecated chef features [#1687](https://github.com/chef/supermarket/pull/1687) ([tas50](https://github.com/tas50))

## [3.1.34](https://github.com/chef/supermarket/tree/3.1.34) (2017-09-28)

#### Merged Pull Requests
- update nokogiri to address CVE-2017-9050 [#1674](https://github.com/chef/supermarket/pull/1674) ([robbkidd](https://github.com/robbkidd))
- Update Foodcritic to 11.4.0 [#1671](https://github.com/chef/supermarket/pull/1671) ([tas50](https://github.com/tas50))
- update embedded libxml2 and libxslt [#1676](https://github.com/chef/supermarket/pull/1676) ([robbkidd](https://github.com/robbkidd))

## [3.1.31](https://github.com/chef/supermarket/tree/3.1.31) (2017-09-15)

#### Merged Pull Requests
- Fix the activity feed, give credit where it is due [#1665](https://github.com/chef/supermarket/pull/1665) ([davidalpert](https://github.com/davidalpert))
- upgrade to Ruby 2.4.2 [#1668](https://github.com/chef/supermarket/pull/1668) ([robbkidd](https://github.com/robbkidd))

## [3.1.29](https://github.com/chef/supermarket/tree/3.1.29) (2017-08-31)

#### Merged Pull Requests
- trigger build for updated RubyGems 2.6.13 [#1664](https://github.com/chef/supermarket/pull/1664) ([robbkidd](https://github.com/robbkidd))

## [3.1.28](https://github.com/chef/supermarket/tree/3.1.28) (2017-08-22)

#### Merged Pull Requests
- Update pipeline to use latest ES patterns [#1657](https://github.com/chef/supermarket/pull/1657) ([schisamo](https://github.com/schisamo))
- update mixlib-authn to fix un/sharing with large keys [#1661](https://github.com/chef/supermarket/pull/1661) ([robbkidd](https://github.com/robbkidd))



## 3.1.25 (2017-08-16)

**Security Updates**

+ updated embedded git to v2.14.1 to address CVE-2017-1000117 [#1653]
+ updated OpenSSL to v1.0.2k (CVE-2017-3731, CVE-2017-3732, CVE-2016-7055) [#1653]
+ updated PostgreSQL to v9.3.18 (CVE-2017-7547, CVE-2017-7546, CVE-2017-7486, CVE-2017-7484, CVE-2017-7485) [#1654]

## 3.1.23 (2017-08-10)

**Fixes**

+ Upgraded sysctl cookbook internal to the omnibus install should fix installs on RHEL-like OSes (e.g. SuSE). [#1649]

**Updates**

+ Upgraded quality metrics to use Foodcritic v11.3.0. [#1648]

## 3.1.22 (2017-07-24)

**Fixes**

+ Fix Foodcritic and No Binaries quality metrics (use the new method signature for retrieving the cookbook tarball). [#1621]

**Updates**

+ Upgraded Ruby to v2.4.1 [#1627]
+ Several changes to internal test/build pipeline.

## 3.1.14 (2017-06-17)

**Security Updates**

+ Includes an updated version of zlib dependency [#1620]

**Updates**

+ Upgraded Foodcritic to v11.2.0 [#1618]
+ Changed links to old IRC to new Chef Community Slack [#1603]

## 3.1.10 (2017-06-14)

**Security Fixes**

+ Fixes secret token checking for Fieri, the quality metrics job runner [#1607]

**Fixes**

+ Fixes a bug in the Collaborator Groups feature where users were not getting added as collaborators when a group they are a member of was added to a cookbook. [#1607]

**Updates**

+ Upgrade web application from Rails 4.2 to 5.0 [#1607]
+ Minor internal changes to the implementation of feature flags [#1616]

**Deprecations/Removals**

+ Individual/Corproate Contributor License Agreement tracking (a.k.a. Curry) has been removed after a period of deprecation. [#1608]

## 3.1.6 (2017-05-19)

**Enhancements**

* More Foodcritic rules included with an upgrade to v11.1.0 [#1610, #1611]

## 3.1.4 (2017-05-15)

**Fixes**

+ Display a useful message when a user's account does not have a public_key associated with it. [#1600]
+ Update versions of embedded monitoring agents (Datadog, New Relic, Sentry). [#1605]

## 3.1.1 (2017-04-24)

**Enhancement**

* Added subcommands to `supermarket-ctl` to change the visibility of quality metrics. [#1599]

## 3.1.0 (2017-04-20)

**New Behavior**

* The cookbook quality metrics currently implemented have all been changed to publicly visible as a default for new installations. For existing pre-3.1.0 Supermarket installations, this release will _not_ automatically change the public visibility of metrics. [#1596]

**Fixes**

* Reënable Foodcritic rule FC045 now that the version of Foodcritic included doesn't alert when a cookbook is published without metadata.rb. [#1593]
* Display quality metric results in a consistent order. [#1595]
* Update links to mailing list to take readers to the Chef Community Mailing List (Discourse site). Thanks to [Roland Moriz](https://github.com/rmoriz) for the catch and fix! [#1598]

## 3.0.2 (2017-04-13)

**Updates**

+ Update to Foodcritic 10.3.1 for new rules, particularly around licensing. (#1590)

**Bugs Fixed**

 + Provide an omnibus configuration default fallback to bare hostname for a Supermarket's FQDN when a host's FQDN is indeterminate. Production Supermarket instances are generally expected to have an FQDN specified in an override—or at least be reliably resolvable via ohai on a single host—so that production SSL certificates have a stable name to match against. This fallback fix is expected to solve a problem that only should occur in test environments. (Fixes #1591 via #1592)

## 3.0.0 (2017-04-10)

**⚠️ Breaking Change ⚠️**

**Attention: AWS S3 Users**

Private Supermarkets using AWS S3 have two new settings to consider following an upgrade to the Paperclip and AWS SDK gems:

+ `s3_region` _must_ be set for the bucket in which cookbooks will be stored.
+ `s3_domain_style` has a new default of `:s3_domain_url`. However, if the S3 bucket name contains periods (`.`), the bucket _must_ be in AWS US-East-1 and the `s3_domain_style` _must_ be `:s3_path_url`.

The `supermarket-ctl reconfigure` action will error with an exception and message if these settings are missing or incompatible.

**Updates**

+ Upgraded Paperclip and AWS SDK gems. (#1411)
+ Upgraded the New Relic and Datadog monitoring agents. (#1588 & #1589)

**Bugs Fixed**

+ Fixed binary file detection to not think zero-byte empty files are binary. (#1584)
+ Added the current ChefDK version of open source license strings as acceptable for the license quality metric. (#1586)
+ Fixed inconsistencies in the display of the navigation menus between the top nav bar and the left side drawer menu. (#1411)

## 2.9.30 (2017-04-04)

**Bugs Fixed**

+ Fixed looking up GitHub repo identifiers from source_url for quality metrics that check on a source repository (same fix as in 2.9.29, but applied to the other workers). (#1583)
+ Upgrade Octokit client to v4+ to support GitHub API's new redirect behavior. (Also #1583)

## 2.9.29 (2017-04-03)

**Enhancements**

+ License quality metric now standardized on checking against SPDX format license strings. (#1577)
+ Upgraded to [Foodcritic 10.2.2](https://github.com/acrmp/foodcritic/blob/master/CHANGELOG.md#1022-2017-03-31) for new rules and fixes. (#1582)
+ Upgraded to latest Ruby 2.3 (2.3.3). (#1581)

**Bugs Fixed**

+ Fixed displaying the first and last name or username of the person publishing a new version of a cookbook in the activity feed. (#1578)
+ Fixed looking up GitHub repo identifiers from source_url for quality metrics that check on a source repository. (#1579)

## 2.9.21 (2017-03-17)

**Enhancements**

+ **New Quality Metrics**:
    + [QM012](https://github.com/chef-cookbooks/cookbook-quality-metrics/blob/fda3f14d9199bfd1bb894d00e7a8e25c85a6b35d/quality-metrics/qm-012-binaries.md) - cookbook artifact does not include binary files
    + [QM014](https://github.com/chef-cookbooks/cookbook-quality-metrics/blob/fda3f14d9199bfd1bb894d00e7a8e25c85a6b35d/quality-metrics/qm-014-version_tags.md) - source repo has a version tag present that matches the version declared in metadata

**Security Update**

+ Upgraded Rails and Nokogiri to address [CVE-2016-4658](http://people.canonical.com/~ubuntu-security/cve/2016/CVE-2016-4658.html) and [CVE-2016-5131](http://people.canonical.com/~ubuntu-security/cve/2016/CVE-2016-5131.html) in [libxml2 vendored within Nokogiri](https://github.com/sparklemotion/nokogiri/issues/1615).


## 2.9.15 (2017-03-14)

**Enhancements**

+ **New Quality Metrics** that check a cookbook's GitHub repository (if present):
    + [QM011](https://github.com/chef-cookbooks/cookbook-quality-metrics/blob/fda3f14d9199bfd1bb894d00e7a8e25c85a6b35d/quality-metrics/qm-011-contributing_doc.md) - cookbook includes instructions on how to contribute (CONTRIBUTING
      document)
    + [QM013](https://github.com/chef-cookbooks/cookbook-quality-metrics/blob/fda3f14d9199bfd1bb894d00e7a8e25c85a6b35d/quality-metrics/qm-013-testing_doc.md) - cookbook includes instructions on how to test (TESTING document)
+ **Rerun Quality Metrics** with supermarket-ctl commands added. A sysadmin/operator can re-run quality metrics on the latest versions of all cookbooks, on the latest version of a single cookbook, or on a specific version of a single cookbook.
+ **Optional Dedicated Redis for Jobs** Provide an optional configuration item
`['supermarket']['redis_jobq_url']` to  specify a Redis connection URL specific
to handling the background job queue. This allows a Supermarket to separate job
processing needs from operations that affect request response times like caching
and feature flag checks.

**Fixes**

+ Remove duplicate quality metric results produced by re-runs.
+ Reliably disable the Datadog application metrics tracer. No more log spam!

## 2.9.7 (2017-02-17)

**Enhancements**

- **Configurable API item limit**:: Use `api_item_limit` in the configuration passed to omnibus install to set the upper limit on the number of items to return for API requests. Defaults to 100 items.
- **Datadog APM Tracer included**:: The Supermarket web application now includes the Datadog APM Tracer agent. The agent defaults to disabled, but can be turned on with `datadog_tracer_enabled` for a Supermarket instance to be monitored with [Datadog APM](https://www.datadoghq.com/apm/).

## 2.9.3 (2017-02-02)

**Enhancements**

- New quality metric to check for [a cookbook declaring what platforms it supports](https://github.com/chef-cookbooks/cookbook-quality-metrics/blob/52be6b20a891e0b2f0915df2ec58beb5588141b5/quality-metrics/qm-006-supports.md).

**Fixes**

- Trim the temporary directory from the foodcritic metric output to reduce the noise in its feedback.
- Fix linkage to the Supermarket API documentation.

**Security Update**
- Update to mixlib-archive used in the Fieri component to address a security vulnerability in handling tar files. If you run Fieri in your private Supermarket, this is a recommended upgrade.

## 2.8.61 (2017-01-30)

**Enhancements**

- Cookbook version API endpoint now includes `published_at` the publication date  on which the version was uploaded to Supermarket.
- Cookbook view displays supported `chef_versions` and `ohai_versions` for currently selected cookbook version if those values exist in the cookbook metadata.
- Several updates to user profile display and management:
  - The Keys tab under user profile management now displays the fingerprint for the public key associated with the user. Instructions are also given for verifying this fingerprint matches the user's local workstation key and for how to tell Supermarket to update its copy of the user's key from the associated Chef Server.
  - Field label text added for contact information. Previously, the label text would only appear in empty fields in the form.
  - JIRA username removed.

**Fixes**

- Upgrade to runit cookbook used in the omnibus install and configuration.
- Upgrade project to Ruby 2.3.1.
- Tweaks to the nginx log format to make it more easily parsed.

**Deprecations**

- CLA signatures and management have been removed from the user profile tabs.

## 2.8.43 (2016-12-05)

**Enhancements**

- **Admin-Only Quality Metrics**: In the effort to add new quality metrics to the system, metrics can now be flagged as only visible to Supermarket admins. As metrics are added and tested, they will start as admin-only. Toggling involves console commands as of this release and will become easier as this feature gets fleshed out!
- **New Quality Metrics** (set to admin-only by default):
  - [QM001](https://github.com/chef-cookbooks/cookbook-quality-metrics/blob/52be6b20a891e0b2f0915df2ec58beb5588141b5/quality-metrics/qm-001-published.md): Cookbook is published to the Supermarket and not deprecated or up for adoption.
  - [QM003](https://github.com/chef-cookbooks/cookbook-quality-metrics/blob/52be6b20a891e0b2f0915df2ec58beb5588141b5/quality-metrics/qm-003-license.md): Cookbook released under a recognized open source license.
- Upgraded Fieri's Foodcritic to v8.1.0+

**Fixes**

- Set default configuration for Foodcritic metric to match that declared by [QM009](https://github.com/chef-cookbooks/cookbook-quality-metrics/blob/52be6b20a891e0b2f0915df2ec58beb5588141b5/quality-metrics/qm-009-foodcritic.md)

**Meta**
- Clarify contributing instructions around the Developer's Certificate of Origin
- Add a [code of conduct](https://github.com/chef/supermarket/blob/master/CODE_OF_CONDUCT.md), referencing the Chef Community Guidelines

## 2.8.34 (2016-11-10)

**Security Updates**

- [#1462] - Upgraded curl to [v7.51.0](https://github.com/chef/omnibus-software/pull/758). curl is bundled in the omnibus package as a dependency of git.

**Enhancements**

- [#1454] - The `tool-search` API endpoint now has two new parameters: `type` to constrain search to a single type of tool and `order` to select alphabetical-by-name (`name`) or reverse-chronological-by-creation-time (`recently_added`). This was added to support searching for compliance profiles from the `inspec` command line tool (see chef/inspec#1219 and chef/inspec#1255 for more).

**Bug Fixes**

- [#1460] - UI was tweaked for the "Advanced Options" search toggle for small viewports, e.g. mobile. (Thanks, @tristanoneil!)


## 2.8.30 (2016-10-17)

**Fixes & Updates**

- [#1452](https://github.com/chef/supermarket/pull/1452) - fixes a bug in 2.8.29 where downloading a cookbook version would break if the version had only the food critic metric result and not the collaborator metric result included with it.


## 2.8.29 (2016-10-10) (2.8.29)

DO NOT USE!  There is a bug in this release!

**Fixes & Updates**

+ [#1433](https://github.com/chef/supermarket/pull/1433) Refactor quality metrics code
+ [#1443](https://github.com/chef/supermarket/pull/1443) Show Fieri Version and tags from Foodcritic runs

## 2.8.27 (2016-10-03) (2.8.27)

**Security Updates**

+ [#1436](https://github.com/chef/supermarket/pull/1436) Upgrades to OpenSSL 1.0.2j

**Fixes & Updates**

+ [#1426](https://github.com/chef/supermarket/pull/1426) Bumps Berkshelf version

## 2.8.25 (2016-09-13) (2.8.25)

**Security Updates**

- [#1427] Upgrade PostgreSQL from 9.3.6 to 9.3.14 to address [several CVEs](https://github.com/chef/supermarket/pull/1427). We don't believe that Supermarket was particularly susceptible to any of the vulnerabilities, but upgrading makes them a non-issue.
- [#1423] Upgrade OpenSSL from 1.0.1t to 1.0.2h in preparation for [1.0.1's end-of-life](https://www.openssl.org/policies/releasestrat.html). No additional CVEs covered as 1.0.1t was the most up-to-date version for 1.0.1.

**Fixes & Updates**

- [#1414] Added Policyfile as an installation example to the cookbook view.
- [#1425] Set the mouse cursor type to `auto` for most of the web UI so that users would see a cursor style for the thing the cursor is over that is consistent with how most other web sites work. Tip of the hat to [Peter Fern](https://github.com/pdf) for pointing the way 😉 to the fix.

## 2.8.0 (2016-07-05) (2.8.0)

**Updates**

- [#1342] Adds Quality Metrics API
- [#1345] Adds tests for Fieri untarring tarballs
- [#1357] Refactor fieri environmental variables


## 2.8.15 (2016-08-31) (2.8.15)

**Fixes**

- [#1418] Fix for an infinite redirect [#1412] from the Supermarket site when uppercase characters appear in the FQDN - Appeared when no fqdn was given and the install defaulted to the node's hostname which was mixed case.
- [#1415] Address deprecation warnings by changing `node.set` to `node.normal` in cookbooks
- Supermarket now built in a Chef Automate pipeline! Adds a build_cookbook for testing and packaging.

## 2.8.3 (2016-08-22)
- [#1402] Use "Chef" and "chef.io" consistently in links.
- [#1405] Use correct URL for Foodcritic project.
- [#1406] Use consistent pluralization of "collaborator metrics"
- [#1409] Upgrade to Rails 4.2 to address [CVE-2016-6316](https://groups.google.com/forum/#!topic/rubyonrails-security/I-VWr034ouk)

## 2.8.2 (2016-08-03)
- [#1312] Adds sending an email to cookbook followers when a cookbook goes up
  for adoption.
- [#1381] Fixed adding the current owner to collaborators when an admin
  initiates a transfer of ownership.
- [#1382] Fixes reevaluating a cookbook when a collaborator is added.
- [#1386] Fixes the database migration command within omnibus to always have a
  HOME set after an update to rb-readline began requiring a HOME.
- [#1387] Fixes config confusion and inconsistencies by no longer requiring FQDN
  and HOME be set and matching in omnibus config. Only a value for FQDN is
  needed now.
- [#1391] Fixes a fieri callback to handle quality metrics results for cookbooks
  with uppercase letters in their name.
- [#1396] Upgrade Ruby to 2.3.0.
- [#1398] Update README with links and Ruby requirements.

## 2.8.1 (2016-07-25)
- [#1370] Support use of systemd on Ubuntu 16.04
- [#1374] Fix wording for passing collaboration metric
- [#1375] Change fieri_results_endpoint to fieri_supermarket_endpoint
- [#1366] Create the log directory to avoid failures which assume it's created
- [#1371] Fix Fieri's handling of cookbook tarballs with non-dir/file entries

## 2.8.0 (2016-07-05)
- [#1342] Adds Quality Metrics API
- [#1345] Adds tests for Fieri untarring tarballs
- [#1357] Refactor fieri environmental variables

## 2.7.4 (2016-06-29)
- [#1350] Airgap feature flag to disable calls to 3rd parties
- [#1357] Upgrade OpenSSL to v1.0.1t (via omnibus & omnibus-software update)
- [#1358] Upgrade Sidekiq & Sidetiq to resolve a stack too deep error when
  scheduling critique of certain cookbooks

## 2.7.3 (2016-06-22)
- [#1343] Untar things as binary in Fieri

## 2.7.2 (2016-06-15)
- [#1328] Add pop-up to confirm putting a cookbook up for adoption
- [#1338] Fix Quality tab not displaying foodcritic feedback when there are no failures

## 2.7.1 (2016-06-10)
- Same as 2.7.0, increments version number after an error with the build and release of 2.7.0

## 2.7.0 (2016-06-09)
- [#1323] Fix platform search wording
- [#1313] Changes Food Critic tab to Quality tab
- [#1300] Adds option to add the current owner as a collaborator when transferring ownership
- [#1324] Add a guard to supermarket specific ctl commands being run as a supermarket service user
- [#1330] Update nokogiri
- [#1303] Makes Fieri an engine within the Supermarket code base
- [#1331] Removes as-supermarket-user guard from '-ctl test' command

## 2.6.1 (2016-05-31)
- [#1285] Add documentation route and page for guides, tutorials, and documentation
- [#1286] "Recently Updated" cookbooks list now refers to  list of recently shipped new versions
- [#1287] Allow admins to view users' emails
- [#1290] Fix for disappearing browser when clicking a cookbook's changelog tab
- [#1293] Changing supermarket activity stream to report correct user for releases
- [#1306] Do not allow a cookbook version to be destroyed if it is the last version of a cookbook
- [#1320] Remove PR assignment from Curry
- [#1299] Move the cache_path into the omnibus var dir to avoid warnings
- [#1322] Reverts changing paperclip to use path urls

## 2.6.0 (2016-05-04)
- [#1289] Upgrade node things
- [#1292] Schedules in CCLA
- [#1275] Shrink SVGs
- [#1284] Hide Announcements
- [#1281] Make S3 Location Agnostic
- [#1270] Fieri use with on disk cookbooks
- [#1278] Add Ubuntu 1204 to Kitchen
- [#1280] Fix Readme
- [#1279] Updates for publishing licensing information

## 2.5.2 (2016-04-14)
Updates package number in omnibus software definition

## 2.5.1 (2016-04-14)
- [#1252] Update deprecation form text
- [#1253] Refine deprecation form and banner
- [#1255] Bring in omnibus omnibus packager
- [#1260] Fix badges for CodeClimate and InchCI
- [#1261] Update Paperclip
- [#1267] Fix upgrades on RHELish systems
- [#1268] Add license info to omnibus project
- [#1264] Add zLinux platform
- [#1274] Fix Rails console
- [#1273] Add opensuseleap support
- [#1272] Make the readme badges SVGs
- [#1269] Fix seeds with new location of README


## 2.5.0 (2016-03-24)
- [chef/supermarket#1245] Allow cookbook to be deprecated without specifying
  a replacement. (Closes #1223)

## 2.4.2 (2016-03-08)
- [chef/supermarket#1240] Upgrade Rails to 4.1.14.2 to address CVEs
- [chef/omnibus-supermarket#49] Upgrade omnibus install for OpenSSL 1.0.1s update
- [chef/supermarket#1242] Update steps/links to create/login to Chef account

## 2.4.1 (2016-02-26)
- Revert chef/omnibus-supermarket#48 Fix https/http proxy header when https is disabled -
  needs a more comprehensive fix for various https/http scenarios

## 2.4.0 (2016-02-25)
- [chef/supermarket#1220] Turn on Rails Rubocops and update controllers & models
- [chef/supermarket#1222] Add search to Contributors page
- [chef/supermarket#1229] Add supported platform filter to cookbook index API endpoint
  (Thanks, Joel Freedman at Pivotal Sydney!)
- [chef/omnibus-supermarket#48] Fix https/http proxy header when https is disabled

## 2.3.3 (2016-02-03)
- [#1215] Upgrade rspec
- [#1199] Add partner badges
- [#1214] Increase contributors shown per page
- [#1216] Add badges to advanced search for cookbooks
- [#1217] Add rake task to spin up PostgreSQL and Redis in Docker
- [#1218] Fix display of dependencies for cookbook versions
- [#1211] Add Chef and Ohai attributes to cookbook versions
- [#1219] Add Guard to run tests
- [chef/omnibus-supermarket#46] Update omnibus and software for openssl 1.0.1r

## 2.3.2 (2016-01-27)
- [chef/omnibus-supermarket#45] Pin embedded berkshelf to prevent net-ssh upgrade

## 2.3.1 (2016-01-26)
- [1188] Prevent test suite from calling out to 3rd party services.
- [1189] Increase changelog content included in email notifications.
- [1206] Fix omission of PostgreSQL extension requirement in migrations.
- [1205] Fix people and titles disappearing from dashboard on small displays.
- [1162] Increase number of contributors displayed on a page from 10 to 50.
- [1209] Upgrade Nokogiri to address CVE
- [1212] Upgrade Rails to address CVEs

## 2.3.0 (2016-01-08)
- [1196] Add Compliance Profile as a new type of tool
- [1195, 1195] Update ROADMAP items
- [1191] Upgrade Nokogiri
- [omnibus-supermarket#44] Upgrade libxml2 via omnibus-software update

## 2.2.2 (2015-12-23)
- [omnibus-supermarket#42] Fix sitemap permissions
- [omnibus-supermarket#40] Add supermarket-ctl console command
- [omnibus-supermarket#43] Fix broken specs

## 2.2.1 (2015-12-18)
- Same as 2.2.0
- Corrects release error

## 2.2.0 (2015-12-18)
- [1151] Add Collaborator Groups feature to Supermarket
- [1185] Bring Ruby version back to 2.1.x
- [omnibus-supermarket#38] Add documentation for collaborator groups feature
- [omnibus-supermarket#41] Change Ruby to v2.1.8

## 2.1.4-alpha.0 (2015-12-10)
- [1161] Upgrade Ruby to 2.2.3
- [omnibus-supermarket#39] Upgrade embedded Ruby, RubyGems, cacerts and OpenSSL

## 2.1.3-alpha.0 (2015-12-08)
- [1172] Update nokogiri to address CVEs
- [1163] Update README with correct current URLs to GitHub repos and mailing list
- [1163] Configure Travis CI to use container infrastructure
- [1167] Fix Curry's computation of what the GitHub repo webhook callback URL should be in production
- [1173] Update README to have consistent use of `bundle exec`
- [1174] Fix `db/seeds.rb` by providing a default callback URL in development

## 2.1.2-alpha.0 (2015-11-25)
- [1170] - No longer invoke foundation tooltips with user supplied content (High Priority Security Fix)

## 2.1.1-alpha.0 (2015-11-24)
- [1146, 1147] Refactor collaborator processing into a reusable concern
- [1153] Update gems (shoulda-matchers, uglifier, chef, sidekiq) for security vulnerability patches
- [1154] Add bundler-audit to test suite
- [1157] Fix deprecation warnings in test suite
- [1160] Add more detail to error given during dependency version validation
- [omnibus-supermarket#37] Add logrotate to supermarket install to handle nginx logs

## 2.1.0-alpha.0 (2015-10-20)
- [1125] - updates changelog
- [1126] - updates README
- [1134] - updates doc to clarify ICLA vs CCLA
- [1136] - update roadmap
- [1138] - fix signer creation in seeds
- [1143] - update docs for minimum requirements for a Supermarket server
- [1142] - change Time.now to Time.current
- [1140] - Export CLA signatures rake task
- [1144] - Fix Postgresql requirement in README

## 2.0.2-alpha.0 (2015-09-17)
- [1103] Add link to Chef Status page to footer
- [1123] Allow admin users to add collaborators, remove collaborators, and transfer ownership

## 2.0.1-alpha.0 (2015-09-10)
- [1102] Corrects maintainers file
- [1106] Corrects profile links
- [1109] Correct output of noisy spec
- [1105] Correct docs
- [1111] Add simple branding
- [1112] Remove double at in keys help text
- [1114] Correct closing link tag
- [1070] Ensure we set a maintainer only once
- [1118] Fix adoption email url

## 2.0.0-alpha.0 (2015-08-13)
- [1073] Convert owners file to maintainers file
- [1074] Update making an admin user docs
- [1075] Update security vulnerable gems
- [1072] Allow admins to add collaborators
- [1084] remove cookbooks survey
- [1083] Add private key documentatino
- [1077] Add log level docs
- [1085] Add linke to feedback site
- [1079] Remove download counts
- [1078] Add roadmap
- [1087] Fix type on ICLA duplicate signature message
- [1092] Update changelog
- [1089] Remove coveralls
- [1091] Enhance adoption email
- [1095] Add mail instructions
- [1097] Clarify Supermarket Omnibus Instructions
- [1099] Update omnibus to handle no ssl on port 443

## 1.12.1-alpha.0 (2015-08-11)
- Updated Omnibus to handle diabling SSL on port 443

## 1.12.0-alpha.0 (2015-06-23)
- [1067] - Automatically assign maintainers to pull requests
- [1063] - Ability to specify s3 bucket paths

## 1.11.0-alpha.0 (2015-06-18)
- [1066] - remove gitter reference from announcement banner
- [1064] - Be more liberal in our configuration tools config
- [1055] - part #2 of removing cookbook self-deps
- [1054] - Make user admin task
- [21] - updating the Gemfile.lock version of omnibus for an error fix
- [22] - Add supermarket ctl command
- [23] - Support rds for postgres
- [25] - Dhparam Options
- [29] - PostgreSQL Credentials

## 1.10.1-alpha.0 (2015-05-15)
Upping version to account for changes in [omnibus-supermarket](https://github.com/chef/omnibus-supermarket/tree/1.10.0-alpha.0)

These changes include (remember, these changes are on omnibus-supermarket)
- [16] - Update omnibus software versions
- [17] - Fix Postgres configuration typos
- [18] - Updating README to point to the most recent version of a Supermarket setup blog post
- [19] - Make Gravatar feature enabled by default

## 1.10.0-alpha.0 (2015-05-14)
- [1028] - Add advanced search functionality to search for cookbooks based on platform
- [1040] - Fix search bar width
- [1039] - Remove Ruby 2.1.3 from the Gemfile
- [1043] - Prevent the universe endpoint from a cookbook showing itself as a dependency on itself
- [1041] - When ownership is transferred, make the previous owner a collaborator on the cookbook
- [1045] - Add zebra striping to adoptable cookbooks list
- [1044] - Add rake tasks to verify development/test env
- [1047] - Remove obsolete info from the README
- [1038] - Add option to disable Gravatars

## 1.9.0-alpha.0 (2015-04-30)
- [#1027] Close an XSS hole
- [#1029] Add notes about chef server url and dev mode configuration
- [#1031] Cookbooks available for adoption
- [#1032] Fix Custom Chef Oauth2 URL
- [#1033] Add link to survey
- [#1034] Add in documentation for Admin users

## 1.8.0-alpha.0 (2015-04-16)
- [#1020] Temporary urls for private s3 storage
- [#1015] adding in links to Chef corporate legalese in common footer
- [#1023] Remove commas from platform names in seed.rb
- [#1014] correcting OWNERS file to reflect current ownership
- [#1019] Add some platforms and dependencies to seed.rb
- [#1013] Update link to supermarket cookbook in README.md
- [#940] Make log level configurable
- [#1001] Update Chef's office address

## 1.7.0-alpha.0 (2015-03-13)
- Updated omnibus and omnibus-software with bug fixes
- [#1004] Remove incorrect dev environment instructions
- [#995] Fixes for blog links
- [#992] Fix universe endpoint name
- [#988] Documentation improvements
- [#982] Fix mailing lists URL
- [#979] Update README
- [#978] Revise Curry navigation link copy
- [#976] Make destruction message less scary
- [#970] Remove links to old wiki

## 1.6.0-alpha.0 (2015-01-21)
- [#934] Only show source/issues URLs if they're present
- [#936] Add powershell modules and dsc resources to available tool types
- [#937] List which FEATURES are enabled in the health endpoint
- [#942] Add a button for sorting search results by release date
- [#945] Show contributors even if GH is disabled
- [#946] Show code of conduct in the footer
- [#951] Adding changelogs to more Atom feeds
- [#952] Add docs on feature flags to the README
- [#953] Fix error with empty collections in atom feeds
- [#959] Return an error message when processing a corrupted tarball
- [#968] Added AIX platform logo
- [#971] Fix incorrect training URL

## 1.5.0-alpha.0 (2014-12-04)
- Update yanked mixlib-shellout version in Omnibus cookbook
- Fix for OAuth2 URL in Omnibus configuration
- [#928] Update Rails to 4.1.8 (CVE-2014-7829)
- [#925] Fix "Get Chef" link in navigation
- [#923] Fix VCR specs for chef.io
- [#922] Update yanked mixlib-shellout version
- [#919] Change default Chef domain to chef.io
- [#916] Allow empty READMEs
- [#915] Make categories optional
- [#912] Add privacy flag
- [#908] Adoption feature for tools and cookbooks
- [#907] Make robots.txt configurable

## 1.4.0 (2014-11-06)
- [#902] More removal of segment.io
- [#901] Gem updates
- [#900] DRY up full host URL generation

## 1.3.0-alpha.0 (2014-10-30)
- [#898] Make sitemap generation configurable
- [#895] Add URL helpers
- [#893] Gem updates
- [#883] Updates to contribution docs
- [#881] Fixes for specs that would not run independently
- [#880] Update Ruby to 2.1.3
- [#878] Fix post-sign-out URL
- [#877] Fix for missing full host in OmniAuth configuration
- [#875] Update README to point to waffle.io instead of Trello
- [#872] Allow disabling of GitHub features
- [#871] Fix warnings from Factory Girl
- [#870] Cache Bundler dependencies on Travis
- [#869] Gem updates
- [#859] Make more Chef server URLs configurable
- [#858] Ensure cookbook update emails are for the version that was uploaded
- [#857] Correct pluralization when only one user or cookbook is on the site
- [#852] Improve cookbook ownership transfer UI
- [#851] Gem updates
- [#850] Improve highlighting of View Source button
- [#849] Remove timed spec for Universe changes
- [#848] Fix typo in cookbook notification
- [#820] Initial builds of Omnibus packages
- [#773] Parse source and issue URLs from cookbook metadata

## 1.2.0 (2014-10-10)
- [#846] Lazily initialize ROLLOUT

## 1.1.0 (2014-10-09)
- [#831] Make email notifications configurable
- [#834] Update README
- [#837] Cleanup old email notifications
- [#838] Upgrade to Ruby 2.1.3
- [#840] Adjust chat redirects
- [#844] Remove segment.io

# 1.0.0 (2014-10-01)
- Initial 1.0 release