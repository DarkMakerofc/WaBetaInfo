<h2 align="center">🪀 WaBetaInfo 🪀</h2>

<h6 align="center">
This is unofficial scraper of whatsapp beta news site, created by Mr nima. all posts credits goes to wabetainfo.com site </h6>
<br>

[ Using This Npm Package ]
* [Get All News](#allnews)
* [Get News Using Link](#latest)
* [Get Latest News](#fromlink)



#### ⬇️ Install Package.
```
yarn add nima-wabeta-info
```
or 
```
npm install nima-wabeta-info
```


#### 📡 Require Package 
```
const nimaWabetaInfo = require("nima-wabeta-info")
```


<a name= "allnews">

#### 🔍 Get All Results  
```
async function TEST_ALLRESULTS() {
    var result = await nimaWabetaInfo.getAll();
    console.log(result)
}
TEST_ALLRESULTS()

```
#### ✅ Result 
```
{
    "creator": "MR NIMA",
    "status": true,
    "result": [
      {
        "no": 1,
        "title": "WhatsApp news of the week: redesigned typing and recording indicator for iOS and Android",
        "date": "Oct 6, 2024",
        "tags": [
          "ANDROID",
          "IOS"
        ],
        "link": "https://wabetainfo.com/whatsapp-news-of-the-week-redesigned-typing-and-recording-indicator-for-ios-and-android/"
      },
      {
        "no": 2,
        "title": "WhatsApp beta for Android 2.24.21.26: what's new?",
        "date": "Oct 5, 2024",
        "tags": [
          "ANDROID"
        ],
        "link": "https://wabetainfo.com/whatsapp-beta-for-android-2-24-21-26-whats-new/"
      },
      {
        "no": 3,
        "title": "WhatsApp beta for iOS 24.20.10.76: what's new?",
        "date": "Oct 4, 2024",
        "tags": [
          "IOS"
        ],
        "link": "https://wabetainfo.com/whatsapp-beta-for-ios-24-20-10-76-whats-new/"
      },
      {
        "no": 4,
        "title": "WhatsApp beta for Android 2.24.21.22: what's new?",
        "date": "Oct 4, 2024",
        "tags": [
          "ANDROID"
        ],
        "link": "https://wabetainfo.com/whatsapp-beta-for-android-2-24-21-22-whats-new/"
      },
      {
        "no": 5,
        "title": "WhatsApp is rolling out new status like reaction and mention features on iOS and Android",
        "date": "Oct 3, 2024",
        "tags": [
          "ANDROID",
          "IOS"
        ],
        "link": "https://wabetainfo.com/whatsapp-is-rolling-out-new-status-like-reaction-and-mention-features-on-ios-and-android/"
      },
      {
        "no": 6,
        "title": "WhatsApp beta for iOS 24.20.10.73: what's new?",
        "date": "Oct 3, 2024",
        "tags": [
          "IOS"
        ],
        "link": "https://wabetainfo.com/whatsapp-beta-for-ios-24-20-10-73-whats-new/"
      },
      {
        "no": 7,
        "title": "WhatsApp beta for Android 2.24.21.18: what's new?",
        "date": "Oct 3, 2024",
        "tags": [
          "ANDROID"
        ],
        "link": "https://wabetainfo.com/whatsapp-beta-for-android-2-24-21-18-whats-new/"
      },
      {
        "no": 8,
        "title": "WhatsApp beta for iOS 24.20.10.72: what's new?",
        "date": "Oct 2, 2024",
        "tags": [
          "IOS"
        ],
        "link": "https://wabetainfo.com/whatsapp-beta-for-ios-24-20-10-72-whats-new/"
      },
      {
        "no": 9,
        "title": "WhatsApp beta for Android 2.24.21.15: what's new?",
        "date": "Oct 2, 2024",
        "tags": [
          "ANDROID"
        ],
        "link": "https://wabetainfo.com/whatsapp-beta-for-android-2-24-21-15-whats-new/"
      },
      {
        "no": 10,
        "title": "Mark Zuckerberg announced filters and backgrounds for WhatsApp video calls",
        "date": "Oct 1, 2024",
        "tags": [
          "ANDROID",
          "IOS"
        ],
        "link": "https://wabetainfo.com/mark-zuckerberg-announced-filters-and-backgrounds-for-whatsapp-video-calls/"
      }
    ]
  }
```
</a>
<br>


<a name= "latest">

#### 🔍 Get Latest Result 
```
async function TEST_LATEST_POST() {
    var result = await nimaWabetaInfo.getLatest();
    console.log(result)
}
TEST_LATEST_POST()
```
#### ✅ Result 
```
{
  "creator": "MR NIMA",
  "status": true,
  "result": {
    "title": "WhatsApp news of the week: redesigned typing and recording indicator for iOS and Android",
    "link": "https://wabetainfo.com/whatsapp-news-of-the-week-redesigned-typing-and-recording-indicator-for-ios-and-android/",
    "image": "https://wabetainfo.com/wp-content/uploads/2024/10/WA_NEW_TYPING_RECORDING_INDICATOR_INTERFACE_GROUP_CHATS_FEATURE_IOS_ANDROID.webp",
    "category": [
      "ANDROID",
      "IOS"
    ],
    "date": "Oct 6, 2024",
    "subtitle": "WHATSAPP NEWS OF THE WEEK",
    "desc": "Missed our weekly WhatsApp beta updates? Catch up now with our summary! Among our 13 stories we shared, the best news of the week is about a redesigned typing and recording indicator available on iOS and Android!Stay tuned with us to discover new features and updates about WhatsApp, coming your way next week!Following WABetaInfo on X is the best way to discover new features under development and released to users on WhatsApp beta for Android, iOS, Web, and Desktop. Keep yourself informed and up-to-date by following us.Do you like this news? Please, let us know on X: we love hearing your feedback! If you're curious to see where you can find WABetaInfo, there is a dedicated page where you can discover our services. In addition, we have set up a Discord Server where you can chat with other people, get help and advice, and stay up to date with the latest announcements from WABetaInfo.We are using cookies to give you the best experience on our website.You can find out more about which cookies we are using or switch them off in settings.This website uses cookies so that we can provide you with the best user experience possible. Cookie information is stored in your browser and performs functions such as recognising you when you return to our website and helping our team to understand which sections of the website you find most interesting and useful.Strictly Necessary Cookie should be enabled at all times so that we can save your preferences for cookie settings.If you disable this cookie, we will not be able to save your preferences. This means that every time you visit this website you will need to enable or disable cookies again.This website uses Google Analytics to collect anonymous information such as the number of visitors to the site, and the most popular pages.Keeping this cookie enabled helps us to improve our website.Please enable Strictly Necessary Cookies first so that we can save your preferences!More information about our Cookie Policy",
    "QandA": [
      {
        "question": "Story about?",
        "answer": "WhatsApp news of the week"
      },
      {
        "question": "I've installed the latest update of WhatsApp for Android, iOS, and Desktop, but some of these features are not currently available. Is there a particular reason for this?",
        "answer": "Some features in the app may be under development and not yet available to all testers, or they may be gradually rolling out to users. If you're unable to access a certain feature, you'll need to wait for a future update. Keep reading for more information."
      },
      {
        "question": "News of last week?",
        "answer": "WhatsApp news of the week: poll feature for status updates in development on iOS!"
      },
      {
        "question": "Previous article?",
        "answer": "WhatsApp beta for Android 2.24.21.26: what's new? WhatsApp is rolling out a new privacy feature to manage the contact syncing option!"
      }
    ]
  }
}
```


</a>
  
<br>

<a name= "fromlink">
  
#### 🔍 Get Result From Link
```
const link = "https://wabetainfo.com/whatsapp-news-of-the-week-redesigned-typing-and-recording-indicator-for-ios-and-android/";
async function TEST_GETFROM_LINK() {
    var result = await nimaWabetaInfo.getFromLink(link);
    console.log(result);
}
TEST_GETFROM_LINK()

```
#### ✅ Result 
```
{
  "creator": "MR NIMA",
  "status": true,
  "result": {
    "title": "WhatsApp news of the week: redesigned typing and recording indicator for iOS and Android",
    "link": "https://wabetainfo.com/whatsapp-news-of-the-week-redesigned-typing-and-recording-indicator-for-ios-and-android/",
    "image": "https://wabetainfo.com/wp-content/uploads/2024/10/WA_NEW_TYPING_RECORDING_INDICATOR_INTERFACE_GROUP_CHATS_FEATURE_IOS_ANDROID.webp",
    "category": [
      "ANDROID",
      "IOS"
    ],
    "date": "Oct 6, 2024",
    "subtitle": "WHATSAPP NEWS OF THE WEEK",
    "desc": "Missed our weekly WhatsApp beta updates? Catch up now with our summary! Among our 13 stories we shared, the best news of the week is about a redesigned typing and recording indicator available on iOS and Android!Stay tuned with us to discover new features and updates about WhatsApp, coming your way next week!Following WABetaInfo on X is the best way to discover new features under development and released to users on WhatsApp beta for Android, iOS, Web, and Desktop. Keep yourself informed and up-to-date by following us.Do you like this news? Please, let us know on X: we love hearing your feedback! If you're curious to see where you can find WABetaInfo, there is a dedicated page where you can discover our services. In addition, we have set up a Discord Server where you can chat with other people, get help and advice, and stay up to date with the latest announcements from WABetaInfo.We are using cookies to give you the best experience on our website.You can find out more about which cookies we are using or switch them off in settings.This website uses cookies so that we can provide you with the best user experience possible. Cookie information is stored in your browser and performs functions such as recognising you when you return to our website and helping our team to understand which sections of the website you find most interesting and useful.Strictly Necessary Cookie should be enabled at all times so that we can save your preferences for cookie settings.If you disable this cookie, we will not be able to save your preferences. This means that every time you visit this website you will need to enable or disable cookies again.This website uses Google Analytics to collect anonymous information such as the number of visitors to the site, and the most popular pages.Keeping this cookie enabled helps us to improve our website.Please enable Strictly Necessary Cookies first so that we can save your preferences!More information about our Cookie Policy",
    "QandA": [
      {
        "question": "Story about?",
        "answer": "WhatsApp news of the week"
      },
      {
        "question": "I've installed the latest update of WhatsApp for Android, iOS, and Desktop, but some of these features are not currently available. Is there a particular reason for this?",
        "answer": "Some features in the app may be under development and not yet available to all testers, or they may be gradually rolling out to users. If you're unable to access a certain feature, you'll need to wait for a future update. Keep reading for more information."
      },
      {
        "question": "News of last week?",
        "answer": "WhatsApp news of the week: poll feature for status updates in development on iOS!"
      },
      {
        "question": "Previous article?",
        "answer": "WhatsApp beta for Android 2.24.21.26: what's new? WhatsApp is rolling out a new privacy feature to manage the contact syncing option!"
      }
    ]
  }
}
```

</a>

<br><br>

### 👨‍💻 Author : [Mr Nima](https://github.com/darkmakerofc)
### Credits : [wabetainfo.com](https://wabetainfo.com/)

## UPDATES
* Fix all news , latest news and get from link errors.
* Add categories ( platforms )
* Date: [10/06/2024]

