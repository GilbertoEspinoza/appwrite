let sdk = new Appwrite();

sdk
    setProject('')
    setKey('')
;

let promise = sdk.teams.getTeam('[TEAM_ID]');

promise.then(function (response) {
    console.log(response);
}, function (error) {
    console.log(error);
});