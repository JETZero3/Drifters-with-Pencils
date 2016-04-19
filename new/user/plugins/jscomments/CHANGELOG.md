# v1.2.10
## 09/13/2015

1. [](#improved)
    * Added translations for the admin plugin form fields.
1. [](#bugfix)
    * Change the main translation key from JSCOMMENTS to PLUGIN_JSCOMMENTS for following the Grav design.

# v1.2.9
## 09/13/2015

1. [](#bugfix)
    * Remove useless field "provider" from configuration. Now this field used only for call the provider based on provider plugin options saved.

# v1.2.8
## 09/13/2015

1. [](#bugfix)
    * Fixed CHANGELOG.md format.
    * Clear code.
    * Added js escape into disqus template.
    * Added translation for muut template.
    * Added multi languages support into muut template.
    * Added js escape into intensedebate template.
1. [](#improved)
    * Update facebook widget to v2.4.
    * Change facebook param from "numposts" to "num_posts" for following the facebook comments param.
    * Change twig translation function to twig filter.
1. [](#new)
    * Added multi language support for facebook template, use this format ({grav_lang}\_{grav_lang|upper}). I'm not sure if this is the best way, but in most case working fine.
    * Added new param for facebook comments "order_by" configurable from page options or into page header. Default is "Social".

# v1.2.7
## 09/12/2015

1. [](#new)
    * Added languages.yaml for translations (_some useless but nice to have it <3_).
1. [](#bugfix)
    * Enabled plugin by default.
    * Fixed small bugs into admin plugin integration.
1. [](#improved)
    * Change how to working code into the header page for use into admin plugin options tab, read the README.md.
    * Refactoring plugin settings page into admin plugin.

# v1.2.6
## 09/12/2015

1. [](#bugfix)
    * Change from onPageContentRaw event to onPageInitialized because not working very well with the cache system.

# v1.2.5
## 09/12/2015

1. [](#improved)
    * Update to working fine with the latest version of Grav.
    * Prepare for the admin plugin the possible to setup the plugin directly with form settings.
    * Added the validation of jscomments header, if setup to true or with data array the plugin parsing, overwise no.
    * Improve Grav cache for parsing jscomments when setup to page header.

# v1.2.4
## 06/28/2015

1. [](#improved)
    * Added multilang support for Disqus.
1. [](#bugfix)
    * Fixed Twig parsing bug.

# v1.2.3
## 02/04/2015

1. [](#bugfix)
    * Update Plugin::mergeConfig() problem.

# v1.2.2
## 02/04/2015

1. [](#improved)
    * Update blueprints.yaml.

# v1.2.1
## 01/10/2015

1. [](#improved)
    * Add complete support for plugin configuration on Admin Plugin.

# v1.2.0
## 01/01/2015

1. [](#new)
    * Rewrite how to add jscomments to page/template. Now working with Twig function. Check the [README.md](README.md) for update.

# v1.1.2
## 12/31/2014

1. [](#bugfix)
    * Fix config typo.

# v1.1.1
## 12/23/2014

1. [](#bugfix)
    * Update the merge config with php function array_replace_recursive instead merge_array.
1. [](#new)
    * Added CHANGELOG.md with partial changelog update, I update in the next release.

# v1.1.0
## 12/06/2014

1. [](#bugfix)
    * Correct version number

# v1.0.9
## 12/05/2014

1. [](#improved)
    * Remove $page variable, not need.
    * Improve plugin events.
    * Update README.md with new configuration values.
1. [](#new)
    * Add methods for reading/writing/merge configuration with page header.

# v1.0.8
## 11/01/2014

1. [](#new)
    * Added Admin Plugin check.
    * Added demo link into the blueprints.yaml.

# v1.0.7
## 10/24/2014

1. [](#new)
    * Start changelog.
