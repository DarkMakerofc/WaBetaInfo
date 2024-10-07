<h2 align="center">🪀 WaBetaInfo 🪀</h2>

<h6 align="center">
This is unofficial scraper of whatsapp beta news site, created by Mr nima. all posts credits goes to wabetainfo.com site </h6>
<br>

[ Using This Npm Package ]
* [Get All News](#allnews)
* [Get News Using Link](#latest)
* [Get Latest News](#fromlink)



#### ⬇️ Install Package 
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
      "title": "WhatsApp for iOS 24.20.71: what's new?",
      "date": "Oct 7, 2024",
      "platforms": [
        "IOS"
      ],
      "link": "https://wabetainfo.com/whatsapp-for-ios-24-20-71-whats-new/"
    },
    {
      "no": 2,
      "title": "WhatsApp news of the week: redesigned typing and recording indicator for iOS and Android",
      "date": "Oct 6, 2024",
      "platforms": [
        "ANDROID",
        "IOS"
      ],
      "link": "https://wabetainfo.com/whatsapp-news-of-the-week-redesigned-typing-and-recording-indicator-for-ios-and-android/"
    },
    {
      "no": 3,
      "title": "WhatsApp beta for Android 2.24.21.26: what's new?",
      "date": "Oct 5, 2024",
      "platforms": [
        "ANDROID"
      ],
      "link": "https://wabetainfo.com/whatsapp-beta-for-android-2-24-21-26-whats-new/"
    },
    {
      "no": 4,
      "title": "WhatsApp beta for iOS 24.20.10.76: what's new?",
      "date": "Oct 4, 2024",
      "platforms": [
        "IOS"
      ],
      "link": "https://wabetainfo.com/whatsapp-beta-for-ios-24-20-10-76-whats-new/"
    },
    {
      "no": 5,
      "title": "WhatsApp beta for Android 2.24.21.22: what's new?",
      "date": "Oct 4, 2024",
      "platforms": [
        "ANDROID"
      ],
      "link": "https://wabetainfo.com/whatsapp-beta-for-android-2-24-21-22-whats-new/"
    },
    {
      "no": 6,
      "title": "WhatsApp is rolling out new status like reaction and mention features on iOS and Android",
      "date": "Oct 3, 2024",
      "platforms": [
        "ANDROID",
        "IOS"
      ],
      "link": "https://wabetainfo.com/whatsapp-is-rolling-out-new-status-like-reaction-and-mention-features-on-ios-and-android/"
    },
    {
      "no": 7,
      "title": "WhatsApp beta for iOS 24.20.10.73: what's new?",
      "date": "Oct 3, 2024",
      "platforms": [
        "IOS"
      ],
      "link": "https://wabetainfo.com/whatsapp-beta-for-ios-24-20-10-73-whats-new/"
    },
    {
      "no": 8,
      "title": "WhatsApp beta for Android 2.24.21.18: what's new?",
      "date": "Oct 3, 2024",
      "platforms": [
        "ANDROID"
      ],
      "link": "https://wabetainfo.com/whatsapp-beta-for-android-2-24-21-18-whats-new/"
    },
    {
      "no": 9,
      "title": "WhatsApp beta for iOS 24.20.10.72: what's new?",
      "date": "Oct 2, 2024",
      "platforms": [
        "IOS"
      ],
      "link": "https://wabetainfo.com/whatsapp-beta-for-ios-24-20-10-72-whats-new/"
    },
    {
      "no": 10,
      "title": "WhatsApp beta for Android 2.24.21.15: what's new?",
      "date": "Oct 2, 2024",
      "platforms": [
        "ANDROID"
      ],
      "link": "https://wabetainfo.com/whatsapp-beta-for-android-2-24-21-15-whats-new/"
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
    "title": "WhatsApp for iOS 24.20.71: what's new?",
    "link": "https://wabetainfo.com/whatsapp-for-ios-24-20-71-whats-new/",
    "image": "https://tmpfiles.org/dl/13997902/mrnima-temporary-uploader.webp",
    "platforms": [
      "IOS"
    ],
    "date": "Oct 7, 2024",
    "short_desc": "WhatsApp has just submitted a new stable update for iOS, available on the App Store: the build number is 24.20.71.\nWhat's new in this update? WhatsApp is rolling out a feature to choose a chat theme among 20 different colors, and it is available to some users!",
    "subtitle": "CHAT THEMES",
    "desc": "\nIn the article about the WhatsApp beta for iOS 24.17.10.71 update, we announced that WhatsApp was working on a feature to choose a chat theme. This feature was designed to enhance personalization, allowing users to apply different themes to specific chats instead of being confined to a single theme for the entire app. By customizing their themes, users can better express their mood and adapt their messaging experience to suit the context of specific conversations. Recently, the WhatsApp for iOS 24.20.71 update was released on the App Store. Currently, the official changelog doesn't provide useful information regarding which new features are available in the latest version of the app. However, we just discovered that WhatsApp is rolling out a feature to choose a chat theme to some users!\n\nThe official changelog still mentions new features for community group chats, including group visibility and community ownership, as discussed in our article about the WhatsApp for iOS 24.18.77 update. However, despite not being noted in the official changelog, we can confirm that WhatsApp is also rolling out a feature to set chat themes to specific conversations. With this new feature, users will have access to 22 distinct themes and 20 colors to choose from, significantly expanding their customization options. Within the app settings, users can select a default chat theme that will be applied to all chats, providing a consistent look and feel throughout the application. In addition, for users who want more variety, they can choose different themes for specific conversations within the chat info screen, making it easier to differentiate between personal, work, and group chats.\nWhatsApp will automatically set a wallpaper based on the selected message color, ensuring that the overall aesthetic of the chat aligns with the chosen theme. However, users can also choose different wallpapers that better reflect their preferences or the context of the conversation. This means that even if two chats share the same theme, they can still look distinct with varying wallpapers. It is very important to note that the privacy of theme settings is a priority, as selecting a theme for a specific chat will not affect how that conversation appears on the recipient's phone. As a result, each user can enjoy their personalized theme without imposing any changes on their contacts.\nIf you don't have this feature yet, please note that some accounts may receive it over the coming weeks, even though it hasn't been mentioned in the official changelog. This feature is currently available to a limited number of users through the App Store and TestFlight app, including those participating in the beta program. WhatsApp is rolling out themes gradually to gather feedback and ensure optimal performance before a wider release. This means that the developers can also identify and address any issues that may arise during this testing phase. We will update you in a future article once the feature becomes available to a broader audience.\nA feature to choose a chat theme is available to some iOS users who install the latest update of WhatsApp from the App Store, and it's rolling out to more people over the coming weeks.\n",
    "QandA": [
      {
        "question": "Changelog about?",
        "answer": "Chat themes"
      },
      {
        "question": "Status?",
        "answer": "Rolling out"
      },
      {
        "question": "Compatibility?",
        "answer": "WhatsApp for iOS 24.20.71 is marked as a compatible update."
      },
      {
        "question": "I have the same version but I don't have this feature. Why?",
        "answer": "This feature is available to some users and it's rolling out to more people over the coming weeks."
      },
      {
        "question": "Thanks:",
        "answer": "Akan and Thiago, for testing and reporting."
      },
      {
        "question": "Previous news?",
        "answer": "WhatsApp news of the week: redesigned typing and recording indicator for iOS and Android!"
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
const link = "https://wabetainfo.com/whatsapp-for-ios-24-20-71-whats-new/";
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
    "title": "WhatsApp for iOS 24.20.71: what's new?",
    "link": "https://wabetainfo.com/whatsapp-for-ios-24-20-71-whats-new/",
    "image": "https://tmpfiles.org/dl/13997902/mrnima-temporary-uploader.webp",
    "platforms": [
      "IOS"
    ],
    "date": "Oct 7, 2024",
    "short_desc": "WhatsApp has just submitted a new stable update for iOS, available on the App Store: the build number is 24.20.71.\nWhat's new in this update? WhatsApp is rolling out a feature to choose a chat theme among 20 different colors, and it is available to some users!",
    "subtitle": "CHAT THEMES",
    "desc": "\nIn the article about the WhatsApp beta for iOS 24.17.10.71 update, we announced that WhatsApp was working on a feature to choose a chat theme. This feature was designed to enhance personalization, allowing users to apply different themes to specific chats instead of being confined to a single theme for the entire app. By customizing their themes, users can better express their mood and adapt their messaging experience to suit the context of specific conversations. Recently, the WhatsApp for iOS 24.20.71 update was released on the App Store. Currently, the official changelog doesn't provide useful information regarding which new features are available in the latest version of the app. However, we just discovered that WhatsApp is rolling out a feature to choose a chat theme to some users!\n\nThe official changelog still mentions new features for community group chats, including group visibility and community ownership, as discussed in our article about the WhatsApp for iOS 24.18.77 update. However, despite not being noted in the official changelog, we can confirm that WhatsApp is also rolling out a feature to set chat themes to specific conversations. With this new feature, users will have access to 22 distinct themes and 20 colors to choose from, significantly expanding their customization options. Within the app settings, users can select a default chat theme that will be applied to all chats, providing a consistent look and feel throughout the application. In addition, for users who want more variety, they can choose different themes for specific conversations within the chat info screen, making it easier to differentiate between personal, work, and group chats.\nWhatsApp will automatically set a wallpaper based on the selected message color, ensuring that the overall aesthetic of the chat aligns with the chosen theme. However, users can also choose different wallpapers that better reflect their preferences or the context of the conversation. This means that even if two chats share the same theme, they can still look distinct with varying wallpapers. It is very important to note that the privacy of theme settings is a priority, as selecting a theme for a specific chat will not affect how that conversation appears on the recipient's phone. As a result, each user can enjoy their personalized theme without imposing any changes on their contacts.\nIf you don't have this feature yet, please note that some accounts may receive it over the coming weeks, even though it hasn't been mentioned in the official changelog. This feature is currently available to a limited number of users through the App Store and TestFlight app, including those participating in the beta program. WhatsApp is rolling out themes gradually to gather feedback and ensure optimal performance before a wider release. This means that the developers can also identify and address any issues that may arise during this testing phase. We will update you in a future article once the feature becomes available to a broader audience.\nA feature to choose a chat theme is available to some iOS users who install the latest update of WhatsApp from the App Store, and it's rolling out to more people over the coming weeks.\n",
    "QandA": [
      {
        "question": "Changelog about?",
        "answer": "Chat themes"
      },
      {
        "question": "Status?",
        "answer": "Rolling out"
      },
      {
        "question": "Compatibility?",
        "answer": "WhatsApp for iOS 24.20.71 is marked as a compatible update."
      },
      {
        "question": "I have the same version but I don't have this feature. Why?",
        "answer": "This feature is available to some users and it's rolling out to more people over the coming weeks."
      },
      {
        "question": "Thanks:",
        "answer": "Akan and Thiago, for testing and reporting."
      },
      {
        "question": "Previous news?",
        "answer": "WhatsApp news of the week: redesigned typing and recording indicator for iOS and Android!"
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
* Fix comming erros when using image.
* Add categories ( platforms )
* Date: [10/07/2024]

