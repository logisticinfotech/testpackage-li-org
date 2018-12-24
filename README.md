# testpackage

# Steps 1
    $ npm init --scope=logisticinfotech

    this will create package.json

# Step 2
    create index.js file with following content.

    exports.printMsg = function() {
        console.log("This is a message from the demo package at LogisticInfotech");
    };

# Step 3
    Enable two factor authentication in npmjs account profile
    Need to use google authenticator app in ios/android

# Step 4
    $ npm adduser

# Step 5
    make sure your package name is unique. Other wise it will give error like
    You do not have permission to publish "testpackage". Are you logged in as the correct user? : testpackage

    $ npm publish --access=public

