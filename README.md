# StashAyloTracker

This plugin was built for my specific requirements. As such, it's unlikely to
work out-of-the box for anyone else, but it should be fairly simple to
configure.

Out-of-the-box, the plugin searches Stash for all female performers to get their
disambiguation, which is where I am storing their Aylo model ID. This is then
used to query the Aylo API for their scenes. This data is then returned in a table.

This plugin is built for a Stash instance that exclusively contains Aylo data,
which I use as part of a pipeline to manipulate data before it reaches a final
"production" Stash instance. As such, this plugin won't be suitable for most
users. Please do not ask for assistance.
