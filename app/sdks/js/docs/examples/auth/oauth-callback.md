let sdk = new Appwrite();

sdk
    setProject('')
    setKey('')
;

let promise = sdk.auth.oauthCallback('[PROJECT_ID]', 'bitbucket', '[CODE]');

promise.then(function (response) {
    console.log(response);
}, function (error) {
    console.log(error);
});