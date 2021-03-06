---
title: Devel Releases 1.0 for Drupal 8
image: https://github.com/weitzman/blog/raw/master/assets/devel/webprofiler.gif 
---
With pride and pleasure, the Devel maintainers have released [1.0 for Drupal 8](*****). Even at the ripe age of 14, Devel is an active, popular, and nimble project. Devel has been downloaded 3.5M times, and 200,000 sites currently report Devel as an enabled project. Devel's whole codebase was deeply improved in this release. A few highlights are below, with annotated screenshots and gifs below each section. Please upgrade and report your success or failure using the new features!

## Webprofiler 
- A new submodule in Devel that reports all sorts of useful details abut a  Drupal response.
- Dive into Cache-hit ratio, DB queries, Events, Forms, Session, Assets, and much more.
- Add your own data collectors.
- [Learn more at our demo video](https://s3.amazonaws.com/webprofiler/webprofiler.mov).

![Webprofiler]({{ site.url }}/assets/devel/webprofiler.gif)
![Webprofiler toolbar expanded]({{ site.url }}/assets/devel/webprofiler_toolbar_expanded.png)
![Webprofiler toolbar]({{ site.url }}/assets/devel/webprofiler_toolbar.png)
![Webprofiler database]({{ site.url }}/assets/devel/webprofiler_database.gif)
![Webprofiler widgets list]({{ site.url }}/assets/devel/webprofiler_widgets_list.png)

## Devel Module
- Integrated into the new toolbar as a top level menu (configurable).
- New pages and Drush commands list available Services, Routes, Events, etc.
- New State and Configuration editors
- 3 Twig extensions for debugging
- A new plugin system for showing dumps like dpm(). Enable and configure the new Kint submodule for pretty dumps.
- Supports Drush 8 and [Drush 9](https://github.com/drush-ops/drush/releases).

![Devel configuration]({{ site.url }}/assets/devel/devel_configuration_edit.png)
![Devel drush services]({{ site.url }}/assets/devel/devel_drush_services.gif)
![Devel drush uuid]({{ site.url }}/assets/devel/devel_drush_uuid.gif)
![Devel dumpers]({{ site.url }}/assets/devel/devel_dumpers.png)
![Devel state editor]({{ site.url }}/assets/devel/devel_state_editor.png)
![Devel toolbar]({{ site.url }}/assets/devel/devel_toolbar.png)
![Devel toolbar items list]({{ site.url }}/assets/devel/devel_toolbar_items_list.png)

## Devel Generate
- We moved the generation of text/int/bool/etc. for Fields into Drupal 8 core. Now all field types, even custom and obscure ones, are supported. 
- Supports Drush 8 and [Drush 9](https://github.com/drush-ops/drush/releases).
 

<p style="background-color: #008A3C; color: white; padding: 10px;">Moshe is available for hire as a consultant. Moshe has worked on Drupal core since 2001, and loves mentoring Drupal teams. Moshe loves to set up CI and developer workflows for PHP/JS teams.</p>