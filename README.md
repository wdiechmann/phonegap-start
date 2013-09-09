# 4Caddies

> 4Caddies is a mobile app built from Web sources (HTLM,CSS and js) to offer golfers a toolbelt when playing
> To learn more go visit [The golfers Toolbelt][4caddies]

## Usage

### Run Application

    /www/index.html

### Run Tests

    /www/spec.html

### PhoneGap/Build

Create a new app with the following repository:

    https://github.com/wdiechmann/4caddies.git

## Updating the Application

The application is based on the [Apache Cordova Hello World][cordova-app] app, and the [Phonegap Starter App][phonegap-start].

But it does not lend itself to easy updating from its roots - too much has changed since that :/

### 1. Update the Source

    cp cordova-app-hello-world/www www/

__Do not replace `www/config.xml`.__

__Do not replace `www/img/logo.png`.__

### 2. Update index.html

Replace `<h1>Apache Cordova</h1>` with `<h1>PhoneGap</h1>`.

### 3. Update PhoneGap Version

    <preference name="phonegap-version" value="x.x.x" />

### 4. Commit

    $ git commit -am "Version x.x.x"

### 5. Tag

    $ git tag x.x.x

[4caddies]: http://4caddies.com
[cordova-app]: http://github.com/apache/cordova-app-hello-world
[phonegap-start]: https://github.com/phonegap/phonegap-start.git
