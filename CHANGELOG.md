# Change-Log for the Jekyll Heroku Starter Kit

Below is a detailed change-log, along with specific tasks completed, for each
version released to date for the Jekyll Heroku Starter Kit.

## Version 1.2.0 (27/05/2018)

- [#new](#new)
  - Configured and added the settings for `@jekyll-paginate-v2` to `_config.yml`
  - Configured and added the settings for `@jekyll-paginate-v2` to `index.md`
  - Configured and added the settings for `@jekyll-last-modified-at` to `index.md`
- [#bugfix](#bugfix)
  - Removed `last_modified_at:` setting out of `sitemp.xsl`.
  - Disabled `@jekyll-paginate-v2` as it messes up homepage layout. Template
    files need to be edited for this plugin to work.

## Version 1.1.0 (27/05/2018)

- [#new](#new)
  - Configured and added the settings for `@jekyll-seo-tag` to `_config.yml`
  - Configured and added the settings for `@jekyll-seo-tag` to `index.md`
  - Configured and added the settings for `@jekyll-sitemap` to `index.md`
  - Defined collections for use in `_config.yml`
  - Added customised `sitemap.xml` and a `sitemap.xsl` template file
    `<https://jekyll-heroku-starter-kit.herokuapp.com/sitemap.xml>`.
  - Added customised `feed.xml` and a `feed.xslt.xml` template file.
    `<https://jekyll-heroku-starter-kit.herokuapp.com/feed.xml>`.
  - New `humans.md` file that outputs a file to
    `<https://jekyll-heroku-starter-kit.herokuapp.com/humans.txt>`.
- [#enhancement](#enhancement)
  - Updated `README.md` and `index.md`.
  - Various enhancements with `static.json` edits.
  - Major enhancement to the `Procfile`.
- [#bugfix](#bugfix)
  - Fixed a build bug with the Gem dependencies.
  - Update `_config.yml` by removing a duplicate `logo` key.
  - Fixed bug where neither `sitemap.xml` nor `feed.xml` were rendering.

## Version 1.0.1 (26/05/2018)

Minor edits; don't affect functionality.

- [#new](#new)
  - New settings added to VS Code Workspace file.
- [#bugfix](#bugfix)
  - Fixed broken link in `README.md`.
  - Removed unnecessary whitespace in `README.md` and `index.md`.

## Version 1.0.0 (26/05/2018)

First _production-ready_ release. Works out the box.

- [#new](#new)
  - Added the following files required by Heroku:
    - `config.ru`
    - `Procfile`
  - Added `Gemfile` to install Jekyll.
  - New `static.json` for the Heroku buildpack.
  - New `Rakefile` for the Heroku buildpack.
  - `index.md` that contains the contents of the `README.md` for the main site.
  - Added a default minimal site theme (jekyll-theme-minimal).
- [#enhancement](#enhancement)
  - Updated all the `*.md` files from the @justinhartman/.github project.
  - Updated `.gitignore` to exclude all project build files.
  - Added some Visual Studio Code settings to the workspace file.
  - Completed the contents for the `README.md` file with full setup and install
    instructions.

## Version 0.0.1 (26/05/2018)

- [#new](#new)
  - Initial Commit

[blog]: https://blog.heroku.com/using-http-headers-to-secure-your-site
