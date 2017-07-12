# Rails static site generator

The last week-end I decided to try to staticize a Rails website without external dependecies, a sort of fullpage cache.

Here you can find a task to do it: `rake static:generate_all`

To generate only a specific route: `rake static:generate_all[page]`

To generate a single resource: `rake static:generate[page,id,2]`

It could also be expandend to generate the sitemap (with a gem like *xml-sitemap*)