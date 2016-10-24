# Change Log
All notable changes to this project will be documented in this file. This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased](https://github.com/bueltge/wordpress-multisite-enhancements/compare/1.3.7...HEAD)

## [1.3.7](https://github.com/bueltge/wordpress-multisite-enhancements/compare/1.3.6...1.3.7) - 2016-10-24
* Fix the usage of plugins for each site in the network on the plugin network view. #32
* Add helpers to remove transient caching for development, debugging, if `WP_DEBUG` is true.
* Fix markup error of missing closing tag in footer text. #31
* Fix markup error on comment admin bar menu item in each site item of the item 'My Sites'. #31
* Add possibility to translate the plugin.

## [1.3.6](https://github.com/bueltge/wordpress-multisite-enhancements/compare/1.3.5...1.3.6) - 2016-10-07
* Switch to new core function `get_sites`
* Remove Plugin Search, now inside the core, since WP 3.6.0
* Add Theme filter search to single and network theme page to find fast and simple the result.

## [1.3.5](https://github.com/bueltge/wordpress-multisite-enhancements/compare/1.3.4...1.3.5) - 2016-05-30
* Performance: Change the function to get all sites of a user to set favicon. [#25](https://github.com/bueltge/wordpress-multisite-enhancements/issues/25)

## [1.3.4](https://github.com/bueltge/wordpress-multisite-enhancements/compare/1.3.3...1.3.4) - 2016-05-19
* Fix value type for nodes from admin bar.
* Enhance the Multisite requirements check.

## [1.3.3](https://github.com/bueltge/wordpress-multisite-enhancements/compare/1.3.2...1.3.3) - 2016-01-15
* Fix Blog Id enhancement, change filter type.
* Change different code topics for better performance and stability.

## [1.3.2](https://github.com/bueltge/wordpress-multisite-enhancements/compare/1.3.1...1.3.2) - 2015-12-17
* Prevent PHP Warning. Props noelboss

## [1.3.1](https://github.com/bueltge/wordpress-multisite-enhancements/compare/1.3.0...1.3.1) - 2015-12-03
* Enhance the external domain check for more exactly check, that's also work on root domain of multisite. Props Matt [Thread](https://wordpress.org/support/topic/main-blog-being-tagged-as-external-domain)

## [1.3.0](https://github.com/bueltge/wordpress-multisite-enhancements/compare/1.2.1...1.3.0) - 2015-11-28
* Add new functionality to filter plugin list live.
* Improve status label filter `multisite_enhancements_status_label`, now with the parameters `$blogname` and `$blog`.

## [1.2.1](https://github.com/bueltge/wordpress-multisite-enhancements/compare/1.2.0...1.2.1) - 2015-09-24
* Bugfix: Correction for the site icon topic. The functions "has_site_icon" and "get_site_icon_url" aren't compatible with multisites. Icon only displayed when on that blog, in network or other blog the WP logo showed.
* Enhancement: Check for active usage of admin bar before add favicon to Admin Bar.

## [1.2.0](https://github.com/bueltge/wordpress-multisite-enhancements/compare/1.1.0...1.2.0) - 2015-09-03
* Add support for Favicon feature `wp_site_icon` since WP 4.3, probs [JoryHogeveen](https://github.com/JoryHogeveen)
* Add status label to each site in the admin bar, probs JoryHogeveen
* Codex changes
* Add hook `multisite_enhancements_autoload` to unset files, there not necessary on autoload, see also the [Wiki](https://github.com/bueltge/wordpress-multisite-enhancements/wiki) for more information

## [1.1.0](https://github.com/bueltge/wordpress-multisite-enhancements/compare/1.0.7...1.1.0) - 2015-02-26
* Some modifications to plugin and theme admin columns for better performance and usage on Multisites with more as 100 blogs, plugins, themes [Issue #16](https://github.com/bueltge/wordpress-multisite-enhancements/pull/16)
* Code inspections
* Enhance the value to get sites inside the network form WordPress default 100 to 9999
* Add hook `multisite_enhancements_sites_limit` to change this value, see [wiki page](https://github.com/bueltge/wordpress-multisite-enhancements/wiki/Large-Network-Problem)

## [1.0.7](https://github.com/bueltge/wordpress-multisite-enhancements/compare/1.0.6...1.0.7) - 09/23/2014
* Code maintenance
* Add parameters for custom favicon, see [documentation](https://github.com/bueltge/WordPress-Multisite-Enhancements/wiki/Filter-Hook-for-Favicon-File-Path)

## [1.0.6](https://github.com/bueltge/wordpress-multisite-enhancements/compare/1.0.5...1.0.6) - 09/13/2014
* Add check for child theme, that you fast see, if is a child and what is the parent inside the network view of themes

## [1.0.5](https://github.com/bueltge/wordpress-multisite-enhancements/compare/1.0.4...1.0.5) - 05/15/2014
* Fix list of active plugin in plugin network view
* Add hook for custom favicon path, see [documentation](https://github.com/bueltge/WordPress-Multisite-Enhancements/wiki/Filter-Hook-for-Favicon-File-Path)

## [1.0.4](https://github.com/bueltge/wordpress-multisite-enhancements/compare/1.0.3...1.0.4) - 04/27/2014
* Add break, if no plugin is active, fixed [Error in "Active In" column](http://wordpress.org/support/topic/error-in-active-in-column)

## [1.0.3](https://github.com/bueltge/wordpress-multisite-enhancements/compare/1.0.2...1.0.3) - 03/09/2014
* Remove Super Admin check, that works the enhancements also on other roles.
* Add indicator for "Network Only" Plugins.
* Add Favicon Indicator also in Admin Bar on Front end side.

## [1.0.2](https://github.com/bueltge/wordpress-multisite-enhancements/compare/1.0.1...1.0.2) - 02/03/2014
 * Add Favicon in Admin Bar also in Front end
 * Enhance style for favicon size
 * Grammar fix in tags, readme
 * Small changes for columns and 3.8 design

## [1.0.1](https://github.com/bueltge/wordpress-multisite-enhancements/compare/1.0.0...1.0.1) - 01/03/2014
 * Add CSS rule for new WP 3.8 back end design](https://github.com/bueltge/wordpress-multisite-enhancements/compare/1.3.4...1.3.5) - mp6 plugin)
 * Add more whitespace on the comment count in admin bar
 * Enhance the filter to list active plugins [#1](https://github.com/bueltge/WordPress-Multisite-Enhancements/issues/1)


## 1.0.0 - 2013-10-31
* First release on wordpress.org after different installs with different users.