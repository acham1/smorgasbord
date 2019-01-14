# Core
Mono-repo for the alanch.am web project. 

## App Engine Services
Project responsibilites are predominantly divided across [GAE](https://cloud.google.com/appengine/) services.

### Default
As the project's UI entry point, an [Express.js](https://github.com/expressjs/express) serves generated assets developed with [React](https://reactjs.org/).

## Assets
Static assets are stored in public [GCS](https://cloud.google.com/storage/) bucket `gs://assets.alanch.am`, which comprises a backend bucket for the https://alanch.am load balancer. Resources can be accessed over the web at URL `https://alanch.am/<resource path>`.
