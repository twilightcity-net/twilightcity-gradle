# Gradle Distribution

DreamScale Gradle distributions, to avoid having to repeatedly declare repository setup.


## Publishing to Bintray

Make sure you have a bintray account and are a member of the [DreamScale organization](https://bintray.com/dreamscale/organization/edit)

Open your [user profile](https://bintray.com/profile/edit/organizations) and retrieve your API Key

Execute bintray upload `gw bintrayUpload -Pbintray.user=<bintray user> -Pbintray.key=<api key>`

Open the DreamScale [common-test](https://bintray.com/dreamscale/maven-public/org.dreamscale%3Agradle-distributions) package and
click the [Publish](https://bintray.com/dreamscale/maven-public/org.dreamscale%3Agradle-distributions/publish) link
