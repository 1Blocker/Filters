# 1Blocker Filters

The content-blocking rules used by [1Blocker](https://1blocker.com), built from community filter lists and optimized for Safari.

## About

1Blocker's filter packages are derived from the most popular and trusted community filter lists available. Because Safari's content-blocker format supports only a subset of common filter syntax, we optimize the source lists specifically for Safari: unsupported rules are removed, some rules are simplified, and the lists are merged and deduplicated. These optimized rules compile faster on devices and make content blocking in Safari more reliable.

The upstream lists are licensed under the GNU General Public License, and this repository publishes our modified rules under the same license.

This repository is generated and updated automatically. It does not accept contributions.

## Sources

Each file in this repository is derived from one or more of the following projects:

- [EasyList](https://easylist.to) — including EasyPrivacy, EasyList Cookie List, Fanboy's lists, and EasyList's regional and supplementary lists (dual-licensed GPL-3.0 / CC BY-SA 3.0; used here under GPL-3.0)
- [AdGuard filters](https://github.com/AdguardTeam/AdguardFilters) (GPL-3.0)
- [uBlock Origin filters](https://github.com/uBlockOrigin/uAssets) (GPL-3.0)
- [NoCoin Filter List](https://github.com/hoshsadiq/adblock-nocoin-list) (MIT)

In addition, some of the rules are 1Blocker's own, curated by our team. We are grateful to the maintainers and contributors of the projects above.

## License

This repository is licensed under the GNU General Public License, version 3 — see [LICENSE](LICENSE). The files are substantially modified versions of the upstream lists: rules have been simplified, merged, deduplicated, and filtered for Safari compatibility. Modification dates are given by the commit history. Copyright in the upstream rules remains with their respective authors, and their original license notices are available in the linked repositories.

## Use in other content blockers

These lists exist solely as an input for 1Blocker's rule compiler and are not general-purpose filter lists. The license grants you the right to reuse them, and nothing in this section limits that right; however, we strongly discourage importing them into other ad blockers. The lists are optimized for our compiler and are not tested anywhere else; we make no guarantee that they will load or behave correctly in other content blockers. If you use another content blocker, subscribe to the upstream lists directly instead — they are designed and tested for those environments.

## Allowlisting

We do not add allowlist entries of our own, we do not accept payment or requests to unblock ads or domains, and we do not participate in any "acceptable ads" program. Exception rules that appear in these lists come from the upstream sources unchanged.

## Reporting issues

We do not accept filter fixes in this repository. If a rule breaks a website, or you believe a request should not be blocked, report it to the relevant upstream project — whether anything is excluded is up to them. Once a fix lands upstream, it is inherited here automatically with a subsequent update. If you believe a problem is caused by our optimization or rule-conversion process rather than by an upstream rule, contact us at [support@1blocker.com](mailto:support@1blocker.com).

## Contact

For any other questions or feedback, contact [support@1blocker.com](mailto:support@1blocker.com).
