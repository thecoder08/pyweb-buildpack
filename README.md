# Pyweb buildpack

This allows developers to deploy their Pyweb apps to Heroku. To use it, go into the app settings and enter `thecoder08/pyweb` as your buildpack.

To let the buildpack know that you are using it, create a blank file called `pyweb` (no extension) in the root of your project. This will allow heroku to detect that you are using Pyweb and load the Pyweb buildpack.
