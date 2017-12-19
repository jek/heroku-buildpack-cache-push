# Heroku Build Caching buildpack

Proof of concept: if the current BUILD_DIR has not been built before,
cache a copy for use in future slug compiles.

Why would you want this? You probably wouldn't, unless you're doing
some wacky monorepo stuff.
