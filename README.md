# Awesome Webex with stars

A curated list of [Webex Developer Resources](https://developer.webex.com), inspired by [awesome-go](https://github.com/avelino/awesome-go) ⭐ 181,085 | 🐛 209 | 🌐 Go | 📅 2026-08-14 and [awesome-python](https://github.com/vinta/awesome-python) ⭐ 314,029 | 🐛 27 | 🌐 Python | 📅 2026-08-05.

> Note that this list covers Webex Messaging, Meetings and Devices APIs and SDKs, as well as Webex Admin APIs.
> Check [awesome-xapi](https://github.com/CiscoDevNet/awesome-xapi) ⭐ 72 | 🐛 18 | 📅 2022-11-22 if you are interested in developer resources for on-premises Cisco Collaboration Devices.<br/>

### Contributing

Please take a quick gander at the [Contribution guidelines](./CONTRIBUTING.md) first. Thanks to all contributors; you rock!

If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!

### Contents

DISCLAIMER: Cisco does not make any commitments about the resources listed in this document, nor the accuracy of the third party resources and any content accessible via the links below.

* [Bot frameworks](#bot-frameworks)
* [Clients SDKs](#client-sdks)
  * [REST API](#rest-api-clients)
  * [Advanced APIs](#advanced-apis)
* [Code samples](#code-samples)
  * [REST API samples](#rest-api-samples)
  * [Bot samples](#bot-samples)
  * [Mobile samples](#mobile-samples)
  * [Web SDK & Widgets samples](#web-sdk--widgets-samples)
* [Developer Tools](#developer-tools)
  * [Postman collections](#postman)
* [Integration Services](#integration-services)
* [Reference](#reference)

## Bot frameworks

*Libraries to code your own bots and integrations implementing Webhooks and/or the OAuth Grant Flow.*

* Java
  * [odl-sparkbot](https://github.com/CiscoDevNet/odl-sparkbot) ⭐ 2 | 🐛 1 | 🌐 Java | 📅 2016-12-20 - An SDK for developing clients and bots on top of the OpenDaylight platform (by jmedved).
* JavaScript
  * [Botkit](https://github.com/howdyai/botkit/tree/master/packages/botbuilder-adapter-webex) ⚠️ Archived - Build conversational bots that can live on multiple platforms (by Howdy.ai).
  * [bot-connector](https://github.com/RecastAI/bot-connector/wiki/Channel-Cisco) ⚠️ Archived - Connect your bot to multiple messaging channels (by Recast.ai).
  * [flint](https://github.com/flint-bot/flint) ⭐ 86 | 🐛 20 | 🌐 JavaScript | 📅 2023-01-11 - Bot SDK for Node.js (by nmarus).
  * [webex-bot-node-framework](https://github.com/webex/webex-bot-node-framework) ⭐ 65 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-20 - A port of flint using the webex-js-sdk (by jpjpjp).
  * [node-sparkbot](https://github.com/CiscoDevNet/node-sparkbot) ⭐ 24 | 🐛 0 | 🌐 JavaScript | 📅 2019-09-12 - Build bots in Node.js and experiment webhooks (by ObjectIsAdvantag).
  * [hubot-spark](https://github.com/tonybaloney/hubot-spark) ⚠️ Archived - A Hubot integration (by tonybaloney).
  * [hubot-sparkwebhook](https://github.com/marchfederico/hubot-sparkwebhook) ⭐ 4 | 🐛 0 | 🌐 CoffeeScript | 📅 2017-01-16 - A Hubot adapter (by marchfederico).
* Perl
  * [cisco\_spark-perl](https://github.com/akalinux/cisco_spark-perl) ⭐ 3 | 🐛 0 | 🌐 Perl | 📅 2025-09-17 - Asynchronous Bot and HTTP Client Library for Perl (by akalinux).
* PHP
  * [botman](https://github.com/botman/driver-cisco-spark) ⭐ 3 | 🐛 4 | 🌐 PHP | 📅 2019-03-11 - Driver to connect with BotMan (by mpociot).
* Python
  * [webexteamsbot](https://github.com/hpreston/webexteamsbot) ⭐ 55 | 🐛 12 | 🌐 Python | 📅 2022-12-26 - A framework for simple '/command' bots (by hpreston)
  * [err-backend-cisco-webex-teams](https://github.com/marksull/err-backend-cisco-webex-teams) ⭐ 24 | 🐛 2 | 🌐 Python | 📅 2026-03-07 - An errbot backend (by marksull).
  * [err-backend-cisco-spark](https://github.com/panholt/err-backend-cisco-spark) ⚠️ Archived - An errbot backend (by panholt).

## Client SDKs

### REST API clients

* C#
  * [SparkDotNet](https://github.com/darrenparkinson/SparkDotNet) ⭐ 13 | 🐛 4 | 🌐 C# | 📅 2022-06-22 - An unofficial dotnet library for consuming the RESTful APIs (by darrenparkinson).
* Elixir
  * [ex\_webexteams](https://github.com/zpeters/ex_webexteams) ⭐ 4 | 🐛 12 | 🌐 Elixir | 📅 2023-12-11 - Elixir package (by zpeters).
* Go
  * [go-cisco-webex-teams](https://github.com/jbogarin/go-cisco-webex-teams) ⭐ 37 | 🐛 7 | 🌐 Go | 📅 2022-10-09 - A Go client library (by jbogarin).
* Haskell
  * [webex-teams-api](https://github.com/nshimaza/webex-teams-api) ⭐ 7 | 🐛 0 | 🌐 Haskell | 📅 2020-07-29 - A Haskell binding (by nshimaza).
* Java
  * [webex-java-sdk](https://github.com/webex/webex-java-sdk) ⭐ 70 | 🐛 3 | 🌐 Java | 📅 2021-10-19 - A Java library for consuming the RESTful APIs (by Cisco Webex).
* Node.js
  * [webex-js-sdk](https://github.com/webex/webex-js-sdk/tree/master/packages/node_modules/webex) ⭐ 203 | 🐛 100 | 🌐 TypeScript | 📅 2026-08-13 - Wrapper maintained by Cisco's engineering group (by Cisco Webex).
  * [sparky](https://github.com/flint-bot/sparky) ⭐ 17 | 🐛 16 | 🌐 JavaScript | 📅 2022-12-07 - A simple API wrapper for Node.js (by nmarus).
  * [sparkclient](https://github.com/marchfederico/node-sparkclient) ⭐ 7 | 🐛 1 | 🌐 JavaScript | 📅 2017-03-29 - A simple Node.js module (by marchfederico).
* Perl
  * [cisco\_spark-perl](https://github.com/akalinux/cisco_spark-perl) ⭐ 3 | 🐛 0 | 🌐 Perl | 📅 2025-09-17 - Asynchronous Bot and HTTP Client Library (by akalinux).
* PHP
  * [SparkBundle](https://github.com/CiscoVE/SparkBundle) ⭐ 1 | 🐛 0 | 🌐 PHP | 📅 2018-03-29 - Symfony bundle (by CiscoVE).
* Python
  * [webexteamssdk](https://github.com/CiscoDevNet/webexteamssdk) ⭐ 256 | 🐛 6 | 🌐 Python | 📅 2026-05-24 (formerly ciscosparkapi) - Work with the REST APIs in native Python (by cmlccie).
  * [pyCiscoSpark](https://github.com/brbester/pyCiscoSpark) ⭐ 30 | 🐛 1 | 🌐 Python | 📅 2017-11-16 - Python library (by brbester).
  * [aiociscospark](https://github.com/andriyko/aiociscospark) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2020-03-16 - Python 3 asynchronous API client (by andriyko).
  * [spark-python-sdk](https://github.com/Bassintag551/spark-python-sdk) - Python module for consuming the RESTful APIs (by Bassintag551).
* Ruby
  * [cisco\_spark-ruby](https://github.com/NGMarmaduke/cisco_spark-ruby) ⭐ 9 | 🐛 2 | 🌐 Ruby | 📅 2024-06-07 - Ruby client (by NGMarmaduke).
  * [ciscospark-ruby](https://github.com/Cloverhound/ciscospark-ruby) ⭐ 2 | 🐛 1 | 🌐 Ruby | 📅 2016-11-18 - REST kit for Ruby (by chadstachowicz).

### Advanced APIs

* [SDK for Browsers](https://github.com/webex/webex-js-sdk#a-note-on-browser-usage) ⭐ 203 | 🐛 100 | 🌐 TypeScript | 📅 2026-08-13 - Integrate calling into your client-side JavaScript applications (by Cisco Webex).
* [Widgets](https://github.com/webex/react-ciscospark) ⭐ 85 | 🐛 15 | 🌐 JavaScript | 📅 2026-05-27 - React components that mimic the Web user experience (by Cisco Webex).
* [SDK for iOS](https://github.com/webex/spark-ios-sdk) ⭐ 35 | 🐛 1 | 🌐 Swift | 📅 2019-04-04 - Integrate messaging and calling in your iOS apps (by Cisco Webex).
* [SDK for Android](https://github.com/webex/spark-android-sdk) ⭐ 10 | 🐛 1 | 🌐 Java | 📅 2019-04-03 - Integrate messaging and calling in your Android apps (by Cisco Webex).
* [SDK for Windows](https://github.com/webex/spark-windows-sdk) ⭐ 2 | 🐛 3 | 🌐 C# | 📅 2018-08-03 - Integrate messaging and calling in your Windows apps (by Cisco Webex).

## Code samples

### REST API samples

* Node.js
  * [integration-sample](https://github.com/CiscoDevNet/webex-integration-sample) ⭐ 26 | 🐛 1 | 🌐 JavaScript | 📅 2021-07-28 - Creating a server-side OAuth integration (by ObjectIsAdvantag).
  * [spark-messages](https://github.com/brh55/spark-messages) ⭐ 3 | 🐛 1 | 🌐 JavaScript | 📅 2017-02-18 - A collection of helpers to ensure consistent formatting of markdown messages (by brh55).
  * [node-sparky-samples](https://github.com/CiscoDevNet/node-sparky-samples) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2017-12-07 - Client samples with node-sparky (by ObjectIsAdvantag).
* Python
  * [Blog companions](https://github.com/webex/Spark-API-Demos) - Simple scripts and bots (by Webex Developer support).
* Ruby
  * [Fault Report](https://github.com/jfield44/TropoFaultReport) ⭐ 2 | 🐛 0 | 🌐 CSS | 📅 2016-05-22 - Reporting dystem for efficient Fault Resolution (by jfield44).

### Bot samples

* Java
  * [Midori](https://github.com/midoricorp/jabbot/tree/master/bindings/jabbot-spark-binding) ⭐ 12 | 🐛 18 | 🌐 Java | 📅 2022-11-16 - An extensible chat robot platform (by midoricorp).
  * [QuizBot](https://github.com/LucaCalabrese/codemotion-spark-bot) ⭐ 3 | 🐛 0 | 🌐 Java | 📅 2017-05-30 - Answer a technology quiz, get scored (by LucaCalabrese).
* Node.js
  * [sparkbot-samples](https://github.com/CiscoDevNet/node-sparkbot-samples) ⭐ 21 | 🐛 11 | 🌐 JavaScript | 📅 2022-12-10 - Examples of bots, leveraging the node-sparkbot framework (by ObjectIsAdvantag).
  * [email2spark](https://github.com/marchfederico/email2spark/blob/master/email2spark.js) ⭐ 6 | 🐛 0 | 🌐 JavaScript | 📅 2017-06-08 - Move an email thread to a space using Mailgun (by marchfederico).
  * [generator-spark-bot](https://github.com/brh55/generator-spark-bot) ⭐ 6 | 🐛 2 | 🌐 JavaScript | 📅 2017-03-21 - A yeoman generator that scaffolds out a bot with usability and simplicity in mind (by brh55).
  * [sparkbotstarter](https://github.com/valgaze/sparkbotstarter) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2018-03-19 - Starter kit for a simple bot leveraging flint (by valgaze).
  * [zbot](https://github.com/akalsey/zbot) ⭐ 5 | 🐛 1 | 🌐 JavaScript | 📅 2017-12-16 - Play the Zork interactive game in spaces (by akalsey).
* Node.js (Botkit)
  * [botkit samples](https://github.com/CiscoDevNet/botkit-ciscospark-samples) ⭐ 47 | 🐛 12 | 🌐 JavaScript | 📅 2022-12-12 - Conversational bot samples built with Botkit (by ObjectIsAdvantag).
  * [botkit-template](https://github.com/CiscoDevNet/botkit-template) ⭐ 47 | 🐛 6 | 🌐 JavaScript | 📅 2023-02-16 - Best practices to bootstrap a Botkit project (by ObjectIsAdvantag).
  * [ciscospark-jira](https://github.com/promptworks/ciscospark-jira) ⚠️ Archived - Jira bot built with Botkit (by patricksmith).
  * [spark-botkit-servicenow](https://github.com/asynchrony-ringo/spark-botkit-servicenow) ⭐ 6 | 🐛 0 | 🌐 JavaScript | 📅 2017-05-31 - ServiceNow bot built with Botkit (by asynchrony-ringo).
  * [spark-botkit-salesforce](https://github.com/asynchrony-ringo/spark-botkit-salesforce) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2017-05-31 - SalesForce bot built with Botkit (by asynchrony-ringo).
* PHP
  * [botman-spark-demo](https://github.com/mpociot/botman-spark-demo) ⭐ 5 | 🐛 0 | 🌐 PHP | 📅 2017-09-27 - Use BotMan in combination with the REST API (by mpociot).
* Python
  * [ciscosparkapi bots](https://github.com/CiscoDevNet/ciscosparkapi/tree/master/examples) ⭐ 256 | 🐛 6 | 🌐 Python | 📅 2026-05-24 - Flask, webpy and pyramid bot examples (by cmlccie).
  * [Room Finder](https://github.com/Guismo1/roomfinder/tree/master/roomfinder_spark) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2018-02-12 - Bot to a meeting room finder interfaced with Microsoft Exchange (by Guismo1).
  * [pyIntegration](https://github.com/CTGTME/pyIntegration) ⭐ 5 | 🐛 6 | 🌐 HTML | 📅 2022-12-08 - Flask OAuth example utilizing ciscosparkapi (by lorashley).
  * [My Hero](https://github.com/hpreston/myhero_spark) ⭐ 1 | 🐛 2 | 🌐 Python | 📅 2018-01-03 - Vote for your favorite superhero, deploy as a docker container on Mantl.io (by hpreston).
  * [Walkthrough](https://developer.webex.com/blog/blog-details-8110.html) - Quick walkthrough to build a simple bot (by JustinDupree).

### Mobile samples

* Android
  * [Kitchen Sink](https://github.com/webex/spark-android-sdk-example) ⭐ 7 | 🐛 0 | 🌐 Java | 📅 2018-08-23 - Developer friendly sample to showcase the Android SDK features (by Cisco Webex).
  * [Goggles](https://github.com/promptworks/spark-goggles) ⚠️ Archived - ‘You See What I See’ remote expert app for augmented reality headsets (by Promptworks).
  * [Wrapper](https://github.com/weddle/webex-teams-sdk-wrapper) - Embed video calls into your Android App in a few lines of code (by weddle).
* iOS
  * [Kitchen Sink](https://github.com/webex/spark-ios-sdk-example) ⭐ 12 | 🐛 1 | 🌐 Swift | 📅 2018-08-09 - Developer friendly sample to showcase the iOS SDK features (by Cisco Webex).
  * [iOS SDK Wrapper](https://github.com/jfield44/SparkSDKWrapper) ⭐ 6 | 🐛 0 | 🌐 Swift | 📅 2017-06-17 - Wrapper library offering a drop in voice and video calling component (by jfield44).
  * [Buddies](https://github.com/webex/spark-ios-sdk-example-buddies) ⭐ 3 | 🐛 1 | 🌐 Swift | 📅 2018-08-10 - Application which combines message/call in a UI (by Cisco Webex).
  * [Notification Server](https://github.com/webex/spark-ios-sdk-example-push-notification-server) ⭐ 0 | 🐛 2 | 🌐 Java | 📅 2024-02-22 - Receive Incoming Call Notifications using Apple Push Notification Service (by Cisco Webex).

### Web SDK & Widgets samples

* SDK for Browsers
  * [call samples](https://developer.webex.com/docs/sdks/browser#samples) - Offical samples of the Browser SDK in action (by Cisco Webex).
* Widgets
  * [custom-menu](https://github.com/adamweeks/spark-widget-custom-menu) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2018-01-26 - Creating custom activities (by adamweeks).
  * [oauth-example](https://github.com/adamweeks/spark-widget-oauth-example) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2018-01-26 - Widget OAuth example with the JavaScript SDK (by adamweeks).
  * [webdialer](https://github.com/achhabra2/webdialer) ⭐ 1 | 🐛 1 | 🌐 JavaScript | 📅 2018-10-18 - Test calls and overlay an existing Web site (by achhabra2).
  * [widget-samples](https://github.com/CiscoDevNet/widget-samples) ⭐ 7 | 🐛 2 | 🌐 HTML | 📅 2020-05-27 - Examples for the Space and Recents widgets (by ObjectIsAdvantag).
  * [widget-space-demo](https://github.com/webex/react-ciscospark/tree/master/packages/node_modules/%40ciscospark/widget-space-demo) ⭐ 85 | 🐛 15 | 🌐 JavaScript | 📅 2026-05-27 - Source code for the Space Widget Demo (by Cisco Webex).

## Developer Tools

*Handy tools to browse or interact with the APIs*

* [teams-space-archive](https://github.com/DJF3/Webex-Teams-Space-Archive-v2) ⭐ 78 | 🐛 1 | 🌐 Python | 📅 2026-06-20 - Archive messages to a single HTML file (by DJF3).
* [websocket-events](https://github.com/marchfederico/ciscospark-websocket-events) ⭐ 19 | 🐛 9 | 🌐 JavaScript | 📅 2024-06-29 - An unsupported hack to get events thru a native websocket (by marchfederico).
* [sparkcli](https://github.com/tdeckers/sparkcli) ⭐ 14 | 🐛 4 | 🌐 Go | 📅 2017-05-09 - A command line interface (by tdeckers).
* [whproxy](https://github.com/sgrimee/whproxy) ⭐ 6 | 🐛 0 | 🌐 Go | 📅 2016-08-03 - Proxy incoming webhooks to established websockets (by sgrimee).
* [guestissuer](https://github.com/ObjectIsAdvantag/guestissuer) ⭐ 5 | 🐛 3 | 🌐 JavaScript | 📅 2022-12-22 - CLI to generate Persistent Guest tokens (by ObjectIsAdvantag).
* [admin sandbox](https://developer.webex.com/docs/api/guides/admin-api#administration-sandbox) - apply for administrator rights to a Sandbox Organization (by Cisco Webex).
* [interactive documentation](https://developer.webex.com/quick-reference.html) - Toogle "Test mode" in the API documentation (by Webex for Developers).
* <a name="postman">Postman</a>
  * [postman-webex](https://github.com/CiscoDevNet/postman-webex) ⭐ 111 | 🐛 4 | 📅 2025-01-31 - Scripted collections for Messaging API, Admin API and Cards (by ObjectIsAdvantag).
  * [postman-webex-calling](https://github.com/webex/postman-webex-calling) ⭐ 28 | 🐛 2 | 📅 2023-11-07 - Collection to demonstrate using the Calling APIs (by Cisco Webex).
  * [postman-webex-meetings](https://github.com/webex/postman-webex-meetings) ⭐ 15 | 🐛 0 | 📅 2022-09-15 - Collection to demonstrate using the Meetings REST APIs (by Cisco Webex).
* [Space widget demo](https://code.s4d.io/widget-space/latest/demo/index.html) - Teams Space widget demo (by Cisco Webex).
* [webex-tokens](https://webex-token.herokuapp.com) - Generate scoped tokens for admins (by ObjectIsAdvantag).

## Integration services

*Cloud platforms and wiring engines to build applications with little to no coding*

* <a name="cis">Cloud Services</a> - Create integrations or assemble from pre-built modules (priced services with trials)
  * [API.AI](https://docs.api.ai/docs/spark-integration) - Create Teams bots with natural language understanding.
  * [Built.io](https://flow.built.io/#/library/cisco-spark/all) - Pre-defined Teams templates (signin required).
  * [Gupshup](https://www.gupshup.io/developer/docs/bot-platform/guide/build-deploy-bot-on-cisco-spark) - How to build and deploy a Teams bot.
  * [IFTTT](https://ifttt.com/cisco_spark/recipes) - Webex Teams recipies.
  * [Recast](https://botconnector.recast.ai/integrations) - Collaborative platform to build, train, deploy and monitor bots.
  * [Stamplay](https://stamplay.com/integrations/cisco%20spark) - Integrate and automate Webex Teams.
  * [Workato](https://www.workato.com/integrations/cisco_spark) - Get more out of Webex Teams by connecting it.
  * [Zapier](https://zapier.com/zapbook/cisco-spark/) - Recommended zaps for Webex Teams.
* Wiring Engines
  * [node-red](https://github.com/cumberlandgroup/node-red-contrib-spark) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-03 - Node-RED Node.js binding to Webex Teams (by nmarus).

## Reference

*Resources maintained by Cisco Product teams and Developer Communities*

* Developer Community Spaces
  * [#webex4devs](https://developer.webex.com/support.html) - Get help from developer support and community (by Webex for Developers).
  * [Botkit devs](https://eurl.io/#SyNZuomKx) - The Botkit developer community space.
  * [Flint devs](https://eurl.io/#rkwLEq4fZ) - The node-flint developer community space.
  * [Node Bot Framework devs](https://eurl.io/#BJ7gmlSeU) - The node-bot-framework developer community space.
  * [Python devs](https://eurl.io/#HkMxO-_9-) - The Python developer community space.
* Learn
  * [API documentation](https://developer.webex.com/quick-reference.html) - The reference documentation (by Webex for Developers).
  * [Blog](https://developer.webex.com/blog-home.html) - Samples and API updates (by Webex for Developers).
  * [Learning track](https://learninglabs.cisco.com/tracks/collab-cloud) - Learn the REST API, build bots, embed Video Calls (by CiscoDevNet).
  * [Rate limiting](https://developer.webex.com/blog/blog-details-8193.html) - Explains 429 & Retry-After HTTP header (by Webex for Developers).
  * [Videos](https://www.youtube.com/playlist?list=PLF2B449AC79859DC5) - A YouTube playlist to discover how to setup and manage Webex Teams (by Cisco).
  * [What's new and coming](https://collaborationhelp.cisco.com/article/en-us/8dmbcr) - New and upcoming features (by Cisco).
* Security
  * [Firewall traversal](https://www.cisco.com/c/dam/en/us/td/docs/voice_ip_comm/cloudCollaboration/spark/whitepapers/cisco-spark-firewall-traversal-white-paper.pdf) - Whitepaper about deployment requirements (by Cisco).
  * [Network requirements](https://collaborationhelp.cisco.com/article/en-us/WBX264) - For firewall and web security administrators (by Cisco).
  * [Privacy Data Sheet](https://www.cisco.com/c/dam/en_us/about/doing_business/trust-center/docs/cisco-webex-privacy-data-sheet.pdf) - Describes how "personal data" are processed (by Cisco).
  * [Security FAQs](https://www.cisco.com/c/dam/en/us/td/docs/voice_ip_comm/cloudCollaboration/spark/esp/Cisco-Spark-Security-Frequently-Asked-Questions.pdf) - Tech Ops and Security FAQs (by Cisco).
  * [Security whitepaper](http://www.cisco.com/c/dam/en/us/solutions/collateral/collaboration/cloud-collaboration/cisco-spark-security-white-paper.pdf) - Details the end-to-end secured service (by Cisco).
* Share
  * [ambassadors](https://ambassador.webex.com/about/) - A worldwide network of professionals (by Cisco).
  * [app hub](https://apphub.webex.com/) - Catalog for bots & integrations (by Cisco).
  * [community of interest](https://developer.cisco.com/site/spark/) - Share your passion for bots and integrations, learn from others (by CiscoDevNet).
  * [creations](https://developer.cisco.com/site/devnetcreations/) - Inspire others by sharing your code (by CiscoDevNet).
  * [partner program](https://help.webex.com/en-us/article/n1v7fqh/Get-Certified-as-a-Webex-Partner) - Get Started as a Webex Partner (by Cisco).
* Support
  * [devsupport](https://developer.webex.com/support.html) - 24/7 developer support community (by Webex for Developers).
  * [geos](http://cs.co/geos) - Quickly check where Webex Teams is available (by Cisco Webex).
  * [media test](https://mediatest.ciscospark.com/) - Test your TCP/UDP network eligibility (by Cisco Webex).
  * [release notes](https://collaborationhelp.cisco.com/article/en-us/mqkve8) - Improvements and fixes for Webex Teams applications (by Cisco).
  * [status page](https://status.ciscospark.com/) - Service availability page for the APIs (by Cisco Webex).

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-15._
