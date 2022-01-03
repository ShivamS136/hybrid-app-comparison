# Hybrid App Development: Comparison among React Native, Ionic and Flutter

I am a web developer and performed this research in May 2021 for my organization. We currently have separate Android, iOS, and web teams. We thought to create a new platform that can be served as a separate website and can be embedded into the current website and native apps. We were not trying to build and launch a separate App. So below R&D is done keeping that thing in mind. I thought it should be shared with the community so here it is.

I have compared them from a web developer's point of view and provided medals(Gold, Silver, Bronze) which is purely based on my understanding and my scenario, it can be different for you.

**Table of Content:**
- [Comparison](#comparison)
- [Medal Tally](#medal-tally)
- [Conclusion](#conclusion)
- [Articles](#articles)


## Comparison <a name="comparison"></a>
We will be comparing all the three options [**React Native**](https://reactnative.dev/), [**Ionic**](https://ionicframework.com/) and [**Flutter**](https://flutter.dev/) on the basis of below parameters:

- [Language](#language)
- [Learning Curve](#learning-curve)
- [Initial Release](#initial-release)
- [Powered By](#powered-by)
- [Community](#community)
- [Github Issues Opened](#github-issues)
- [Performance](#performance)
- [Popularity](#popularity)
- [Framework Nature](#framework-nature)
- [Coding Architecture](#coding-architecture)
- [Supported Platform](#supported-platform)
- [Pricing](#pricing)
- [Integration](#integration)
- [Build size](#build-size)
- [Testing](#testing)
- [Code Reusability](#code-reusability)
- [UI Components](#ui-components)
- [StackOverflow Questions Trend](#stackoverflow-questions)
- [Udemy Trends](#udemy-trends)
- [Developer Availability](#developer-availability)
- [Last 2 years' Share in Hybrid Frameworks used](#last-2years)
- [Poll](#poll)
- [OTA(Over the air) Update](#ota)
- [SEO](#seo)

### Language <a name="language"></a>
|Framework|Language|Medal|
|--|--|--|
|React Native|JavaScript & React|🥈|
|Ionic|HTML+CSS+JSS (with React/Angular/Vue)|🥇|
|Flutter|Dart|🥉|

Ionic and React Native uses JS which matches with the tech stack used by a web developer usually. Dart is by google and it has C language-like syntax which is not similar to JS. So we might need devs who can learn Dart if we go for Flutter. Ionic can be written in Vanilla JS as well.



---
### Learning Curve <a name="learning-curve"></a>
Time required to learn (for Web Developers):
|Framework|Time to Learn|Medal|
|--|--|--|
|React Native|Low (React Dev), Medium (other Web Dev)|🥈|
|Ionic|Low|🥇|
|Flutter|High|🥉|

Flutter and Dart are new so it might take more time to learn.


---
### Initial Release <a name="initial-release"></a>
|Framework|Release Year|Medal|
|--|--|--|
|React Native|2015|🥇|
|Ionic|2013|🥇|
|Flutter|2017|🥈|

Flutter is relatively new but gaining popularity rapidly.


---
### Powered By <a name="powered-by"></a>
|Framework|Powered By|Medal|
|--|--|--|
|React Native|Facebook|🥇|
|Ionic|Drifty Co.|🥈|
|Flutter|Google|🥇|

All are Open Source so community support is there, but React-Native and Flutter have the upper hand here.


---
### Community <a name="community"></a>
|Framework|Github Stars|Github Forks|Medal|
|--|--|--|--|
|[React Native](https://github.com/facebook/react-native)|100K|21.6K|🥈|
|[Ionic](https://github.com/ionic-team/ionic-framework)|45.9K|13.5K|🥉|
|[Flutter](https://github.com/flutter/flutter)|134K|20K|🥇|

React and Ionic has old and strong communities. Flutter is relatively new, however, it has made its space and attracted developers to learn Dart.


---
### Github Issues Opened <a name="github-issues"></a>
|Framework|Github Issues Opened/Total|Medal|
|--|--|--|
|[React Native](https://github.com/facebook/react-native/issues)|1.9K / 20.3K|🥈|
|[Ionic](https://github.com/ionic-team/ionic-framework/issues)|673 / 18.8K|🥇|
|[Flutter](https://github.com/flutter/flutter/issues)|9.9K / 53.3K|🥉|

Flutter is new and attracted more developers recently but still, 9.9K+ is a high number of issues opened.

---
### Performance <a name="performance"></a>
As far as I understood in terms of performance of these frameworks while interacting with the Native OS as an App:

|Framework|Performance|Medal|
|--|--|--|
|React Native|Bridge Based|🥈|
|Ionic|Plugin Based|🥉|
|Flutter|Native Channels|🥇|

Communication via Bridge and Plugins takes more time, though React is working on resolving Bridge Jam situations. Flutter works via direct platform channels so it's faster. Flutter team states that Flutter Web is for Web Apps not for static or minimal sites. *So for small web apps, Flutter gets -ve there.*


---
### Popularity <a name="popularity"></a>
In this section we'll be seeing some of the top products using these frameworks:

|Framework|Popularity|Medal|
|--|--|--|
|React Native|Most Popular <br/>*(Facebook, Instagram, Pinterest, Skype, Tesla, Uber, Walmart, Salesforce, Vogue)*|🥇|
|Ionic|Popular among web developers <br/>*(MarketWatch, Pacifica, Sworkit, Nationwide)*|🥈|
|Flutter|Gaining popularity faster <br/>*(Alibaba, Hamilton Musical, Greentea, Google Ads. eBay, BMW)*|🥇|

React Native is more popular than the other two as many tech giants are using it in their production environment. Ionic is very popular among web and mobile app developers due to its easy learning curve. Flutter has just entered the market but has grown in popularity in very little time.


---
### Framework Nature <a name="framework-nature"></a>
|Framework|Framework Nature|
|--|--|
|React Native|App First|
|Ionic|Web First|
|Flutter|App First|

App and Web have different UI structures, so choosing "first platform" may help to decide the framework. If you want your product to be a website first then Ionic is +ve there else -ve.


---
### Coding Architecture <a name="coding-architecture"></a>
|Framework|Coding Architecture|Medal|
|--|--|--|
|React Native|Component based, <br/>Hot Reloading, <br/>React JS UI|🥇|
|Ionic|One codebase, <br/>Plugin based, <br/>Web UI|🥈|
|Flutter|Hot Reloading, <br/>Different achitecture with Dart, <br/>Enhanced graphics & UI|🥇|

All have their qualities, but due to hot reloading, development and Unit testing are faster on React-Native and Flutter.

---
### Supported Platform <a name="supported-platform"></a>
|Framework|Supported Platform|Medal|
|--|--|--|
|React Native|Android, iOS, UWP (Windows 10) <br/><br/>Web support by github pkg [react-native-web](https://github.com/necolas/react-native-web)(18.8K Stars), used by some org on production like MMT, Twitter Lite, Flipkart Lite, Uber Eats|🥈|
|Ionic|Web, Android, iOS <br/><br/>Native support via plugins Capacitor, Cordova|🥈|
|Flutter|Android, iOS, Web, Microsoft Desktop <br/><br/>Web support is launched in Mar'21, Microsoft support is in beta|🥇|

Web support on React is by open-source package, on Flutter it's new and Native support on Ionic is via plugins. So a trade-off to choose from.  
  
RNW example [source.](https://necolas.github.io/react-native-web/docs/about-project/) Flipkart Lite [Source](https://tech.flipkart.com/the-journey-of-react-native-flipkart-47dcd0c3d1c6)


---
### Pricing <a name="pricing"></a>
|Framework|Pricing|Medal|
|--|--|--|
|React Native|Free and Open Source|🥇|
|Ionic|Open Source with Paid Support|🥇|
|Flutter|Free and Open Source|🥇|

All are Open Source.


---
### Integration <a name="integration"></a>
Hereby Integration I mean how easily can a hybrid sub-app be integrated into an already built mobile app (Android/iOS).

|Framework|Integration|Medal|
|--|--|--|
|React Native|Only a single app can be integrated <br/>If multiple, then need to be merged first|🥈|
|Ionic|Only a single app can be integrated <br/>If multiple, then need to be merged first|🥈|
|Flutter|Only a single app can be integrated <br/>If multiple, then need to be merged first|🥈|

So for all the options, if there are multiple Hybrid Apps available then they need to be merged first. Merge time depends on, how merge-friendly the separate apps are written. So Merging guidelines will be needed to make integration smooth.


---
### Build size <a name="build-size"></a>

Here I created the "Hello World!" app by using these frameworks and the below calculation is the size of the build for the android app. *(Not a Mac User so can't create the iOS app)*

|Framework|Build size|Medal|
|--|--|--|
|React Native|7MB|🥈|
|Ionic|3.5MB|🥇|
|Flutter|7.5MB|🥉|

For small apps, Ionic size is smaller but for bigger apps, it gets worse due to separate HTML+CSS+JS files. For bigger apps, Flutter works best. ([Source](https://medium.com/android-news/comparing-apk-sizes-a0eb37bb36f))

---
### Testing <a name="testing"></a>
|Framework|Testing|Medal|
|--|--|--|
|React Native|Ranges between unit testing to automated testing <br/>Testing frameworks are available|🥇|
|Ionic|Ranges between component testing and end-to-end testing <br/>Ionic CLI and Browser based|🥈|
|Flutter|Multiple testing frameworks are available|🥇|

For big applications, component or widget level testing is helpful. React-Native and Flutter have many Testing Frameworks available, while Ionic has normal web-based testing.


---
### Code Reusability <a name="code-reusability"></a>
|Framework|Code Reusability|Medal|
|--|--|--|
|React Native|90%|🥈|
|Ionic|98%|🥇|
|Flutter|<90%|🥉|

As Ionic uses HTML+CSS+JS for all platforms, It has most of the code reusable, In React-Native components can be reused, but when we add web support then only the components without native functionality can be reused. Same for Flutter.


---
### UI Components <a name="ui-components"></a>
|Framework|UI Components|Medal|
|--|--|--|
|React Native| The same feel as Native UI component, UI Libraries also available|🥇|
|Ionic|Big set of pre-built and pre-styled components.|🥇|
|Flutter|SKIA engine powered UI in the app and Flutter web engine for web, Extensive list of widgets. <br/><br/>Flutter web pages are not usual web pages, they are on canvas default but using HTML renderer it can be like a normal HTML web page.|🥈|

Flutter Web Pages in Canvas can lead to bad SEO and compatibility issue on very old browsers. React Native provides a Native feel and can be styled with external libraries.


---
### StackOverflow Questions Trend <a name="stackoverflow-questions"></a>
Here we can see the number of questions on StackOverflow for the tags of these Hybrid Frameworks. This indirectly shows how much developers are working on the particular framework actively.

|Framework|Mar'18|Mar'19|Mar'20|Mar'21|Medal|
|--|--|--|--|--|--|
|React Native|2053|2370|2861|2808|🥇|
|Ionic|1084|865|751|467|🥉|
|Flutter|590|1857|3764|5185|🥇|


![SO Questions trend](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/asm2omyjxxirc6b0ryc7.png)

React Native seems consistently popular among developers while Ionic seems losing its fame. However, Flutter is gaining a lot of attraction. [(Source)](http://sotagtrends.com/?tags=ionic-framework+react-native+flutter&relative=false)


---
### Udemy Trends <a name="udemy-trends"></a>
Udemy is one of the most popular learning platforms with a high number of students and teachers. Below stats tells about the active status of students and teachers on these frameworks:

|Framework|Courses|Students|Medal|
|--|--|--|--|
|[React Native](https://www.udemy.com/topic/react-native/)|132+|1M+|🥈|
|[Ionic](https://www.udemy.com/topic/ionic/)|103+|649K+|🥉|
|[Flutter](https://www.udemy.com/topic/google-flutter/)|292+|1.9M+|🥇|
|[Dart](https://www.udemy.com/topic/dart-programming-language/)|64+|796K+||

So Dart and Flutter are gaining popularity with enough resources available. [(Source)](https://www.thedroidsonroids.com/blog/flutter-vs-react-native-what-to-choose-in-2021)


---
### Developer Availability <a name="developer-availability"></a>

This is the number of people available in India and globally as per Linkedin Search via my account.

|Framework|In India|Worldwide|Medal|
|--|--|--|--|
|React Native|[42K+](https://www.linkedin.com/search/results/people/?geoUrn=%5B%22102713980%22%5D&keywords=%22react%20native%22&origin=GLOBAL_SEARCH_HEADER)|[235K+](https://www.linkedin.com/search/results/people/?keywords=%22react%20native%22&origin=FACETED_SEARCH)|🥇|
|Ionic| [26K+](https://www.linkedin.com/search/results/people/?geoUrn=%5B%22102713980%22%5D&keywords=%22ionic%22&origin=GLOBAL_SEARCH_HEADER) | [172K+](https://www.linkedin.com/search/results/people/?keywords=%22ionic%22&origin=FACETED_SEARCH)|🥉|
|Flutter|[44K+](https://www.linkedin.com/search/results/people/?geoUrn=%5B%22102713980%22%5D&keywords=%22flutter%22&origin=GLOBAL_SEARCH_HEADER)|[175K+](https://www.linkedin.com/search/results/people/?keywords=%22flutter%22&origin=FACETED_SEARCH)|🥈|


---
### Last 2 years' Share in Hybrid Frameworks used <a name="last-2years"></a>
|Framework|in 2019|in 2020|Medal|
|--|--|--|--|
|React Native|42%|42%|🥇|
|Ionic|28%|18%|🥉|
|Flutter|30%|39%|🥈|

Flutter's share is increasing sharply while for Ionic it's decreasing in the same trend. [(Source: Statista)](https://www.statista.com/statistics/869224/worldwide-software-developer-working-hours/)


---
### Poll <a name="poll"></a>
I conducted a poll on LinkedIn for the same, but with a short description of my need,  it didn't get that many responses but this sample response seems to verify my above research:

|Framework|Vaotes Received|Medal|
|--|--|--|
|React Native|50.53%|🥇|
|Ionic|7.37%|🥉|
|Flutter|42.11%|🥈|

Total Votes: 95

[Public Voting](https://www.linkedin.com/posts/shivams136_hybridweb-hybridnative-rnd-activity-6802937489939165184-4VOq)

![Public Poll Results](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/9r5d9pi266jwqht66hcq.png)

[Technical group Voting](https://www.linkedin.com/feed/update/urn:li:activity:6802932767106703360)

![Group Poll Result](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/kxt3jtjxjj8nuzae2eqy.png)


---
### OTA(Over the air) Update <a name="ota"></a>
|Framework|OTA Compatibility|Medal|
|--|--|--|
|React Native|Via CodePush ([Source](https://pagepro.co/blog/react-native-over-the-air-updates/))|🥇|
|Ionic|Via CodePush ([Source](https://ionicframework.com/docs/native/code-push))|🥇|
|Flutter|Very [Limited OTA support](https://flutter.dev/docs/cookbook/networking/update-data), App release is required ([Source](https://stackoverflow.com/questions/63759459/how-to-automatically-update-a-flutter-mobile-app-to-newer-version-when-the-appli))|🥉|



---
### SEO <a name="seo"></a>
I know, I'm not that good at this point but still mentionable.
|Framework|SEO|Medal|
|--|--|--|
|React Native|Same like React App (Doable)|🥈|
|Ionic|Doable|🥈|
|Flutter|Doable with Router|🥈|

SEO can be achieved like other SPA frameworks but not as simple as a PHP website.

---

## Medal Tally <a name="medal-tally"></a>

| Framework | 🥇|🥈|🥉|Total Score <br/>(3G+2S+1B)|
|--|--|--|--|--|
|React Native|12|11|0|58|
|Ionic|9|7|7|48|
|Flutter|10|7|6|52|

---

## Conclusion <a name="conclusion"></a>

As a developer, for my use case, I found React Native better so I went for that and created a sample React Native App: [Harry Potter Dictionary](https://github.com/ShivamS136/harry-potter-dictionary) with [web support](https://github.com/ShivamS136/hp-dict-web-demo). Now my organization is working on replacing some modules in android with React Native sub-apps.

---

## Articles <a name="articles"></a>
For this research I've read some articles, which can be found [here](https://github.com/ShivamS136/hybrid-app-comparison/blob/main/articles.md). You can also have a look at them.
