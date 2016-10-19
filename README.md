[![build status](https://secure.travis-ci.org/fabien-d/alertify.js.png)](http://travis-ci.org/fabien-d/alertify.js)

Alertify is an unobtrusive customizable JavaScript notification system.

## Publish as npm package

To publish this to AtScale's Artifactory as an npm package, you first need to fetch the authentication params using your Artifactory <USERNAME> and <PASSWORD> credentials.
```
curl -u<USERNAME>:<PASSWORD> "http://artifactory.corp.atscale.com/api/npm/npm-local/auth/atscale"
```

The response, which will look similar to the following code block, should be pasted into your ~/.npmrc file.
```
@atscale:registry=http://artifactory.corp.atscale.com/api/npm/npm-local/
/artifactory.corp.atscale.com/api/npm/npm-local/:_password=<BASE64_PASSWORD>
/artifactory.corp.atscale.com/api/npm/npm-local/:username=<USERNAME>
/artifactory.corp.atscale.com/api/npm/npm-local/:email=youremail@email.com
/artifactory.corp.atscale.com/api/npm/npm-local/:always-auth=true
```

Now you can publish.
```
npm publish
```

## Features

* Fully customizable alert, confirm and prompt dialogs
* Fully customizable unobtrusive notification system
* Callback parameter handling both OK and Cancel button clicks
* Chaining which allows queued dialogs

## Examples

http://fabien-d.github.com/alertify.js/

## Usage

See wiki [How to Use](http://github.com/fabien-d/alertify.js/wiki/How-to-Use)

## Changeset

See wiki [Changeset](http://github.com/fabien-d/alertify.js/wiki/Changeset)

## Contributing

See wiki [Submitting a Pull Request](https://github.com/fabien-d/alertify.js/wiki/Submitting-a-Pull-Request)

## Where is it being tested?

* Microsoft Internet Explorer 7+ (Standards Mode)
* Google Chrome
* Mozilla FireFox
* Apple Safari
* Opera
* iOS
* Android

## License

Alertify is licensed under MIT http://www.opensource.org/licenses/MIT

### Copyright

Copyright (c) 2012, Fabien Doiron  
<fabien.doiron@gmail.com>, [@fabien_doiron](http://twitter.com/fabien_doiron)
