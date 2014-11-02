# plushu-buildstep

This Plushu build hook plugin builds an App Container using
[progrium/buildstep][].

[progrium/buildstep]: https://github.com/progrium/buildstep

## This plugin is deprecated

The monolithic container approach used by buildstep isn't particularly elegant,
and in its build process, buildstep itself misses the mark in a few ways. For a
more modular, Plushu-friendly build system, one should use
[plushu-build-cedarish][], while using the [plushu-buildpacks][] plugin to
manage buildpacks, using a meta-plugin like [plushu-heroku-buildpacks][] to get
a default set of plugins.

[plushu-build-cedarish]: https://github.com/plushu/plushu-build-cedarish
[plushu-buildpacks]: https://github.com/plushu/plushu-buildpacks
[plushu-heroku-buildpacks]: https://github.com/plushu/plushu-heroku-buildpacks
