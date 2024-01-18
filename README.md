<h2 align="center">🪀 WaBetaInfo 🪀</h2>

<h6 align="center">
This is Unofficial Scraper & NPM package , Created by Mr nima. </h6>
<br>

[ Using This Npm Package ]
* [Get All News](#allnews)
* [Get News Using Link](#latest)
* [Get Latest News](#fromlink)



#### ⬇️ Install Package 
```
yarn add nima-wabeta-info
```


#### 📡 Require Package 
```
const nimaWabetaInfo = require("nima-wabeta-info")
```


<a name= "allnews">

#### 🔍 Get All Results  
```
nimaWabetaInfo.getAll()
  .then((result) => {
    console.log(result);
  })
  .catch((error) => {
    console.log(error);
  });

```
#### ✅ Result 
```
{
   "creator": "MR NIMA",
   "status": true,
   "result": [
      {
         "title": "WhatsApp beta for Android 2.24.2.17: what’s new?",
         "link": "https://wabetainfo.com/whatsapp-beta-for-android-2-24-2-17-whats-new/",
         "date": "Jan 18, 2024",
         "categories": [
            "ANDROID"
         ],
         "desc": "WhatsApp is rolling out a new update through the Google Play Beta Program, bringing the version up to 2.24.2.17. What’s new in this update? WhatsApp is working on a feature to transfer the channel ownership, and it will be available in a future update!"
      },
      {
         "title": "Mark Zuckerberg announced voice notes, multiple admins, status sharing, and polls for WhatsApp channels!",
         "link": "https://wabetainfo.com/mark-zuckerberg-announced-voice-notes-multiple-admins-status-sharing-and-polls-for-whatsapp-channels/",
         "date": "Jan 17, 2024",
         "categories": [
            "ANDROID",
            "IOS"
         ],
         "desc": "Mark Zuckerberg recently announced several new features available for WhatsApp channels, including the ability to share voice notes and polls, a feature to promote new admins, and a dedicated interface to share channel content as a status update."
      },
      {
         "title": "WhatsApp for Mac 24.1.77: what’s new?",
         "link": "https://wabetainfo.com/whatsapp-for-mac-24-1-77-whats-new/",
         "date": "Jan 16, 2024",
         "categories": [
            "IOS"
         ],
         "desc": "WhatsApp has just submitted a new stable update for macOS, available on the App Store: the build number is 24.1.77. What’s new in this update? This is a bug-fix update that addresses several issues and offers performance improvements to everyone!"
      },
      {
         "title": "WhatsApp beta for iOS 24.1.10.76: what’s new?",
         "link": "https://wabetainfo.com/whatsapp-beta-for-ios-24-1-10-76-whats-new/",
         "date": "Jan 15, 2024",
         "categories": [
            "IOS"
         ],
         "desc": "WhatsApp has just submitted a new update through the TestFlight beta Program, bringing the version up to 24.1.10.76. The version marked within WhatsApp Settings is 2.24.1.76 and the TestFlight build is 24.1.10 (555067882). What’s new in this update? WhatsApp is rolling out a feature to share polls in channels, and it’s available to some beta testers!"
      },
      {
         "title": "WhatsApp news of the week: additional text formatting tools available on Android beta",
         "link": "https://wabetainfo.com/whatsapp-news-of-the-week-additional-text-formatting-tools-available-on-android-beta/",
         "date": "Jan 14, 2024",
         "categories": [
            "ANDROID",
            "IOS"
         ],
         "desc": "If you missed our stories this week about the latest updates to WhatsApp beta for Android, iOS, and Desktop, this is a good time to catch up thanks to our summary. Among the 8 stories and concepts we shared, the best news of the week is about additional text formatting tools for messages, a new feature available on WhatsApp beta for Android!"
      },
      {
         "title": "WhatsApp beta for Android 2.24.2.13: what’s new?",
         "link": "https://wabetainfo.com/whatsapp-beta-for-android-2-24-2-13-whats-new/",
         "date": "Jan 13, 2024",
         "categories": [
            "ANDROID"
         ],
         "desc": "WhatsApp is rolling out a new update through the Google Play Beta Program, bringing the version up to 2.24.2.13. What’s new in this update? WhatsApp is rolling out a feature to manage app updates with the preinstalled Meta App Manager application, and it’s available to some beta testers!"
      },
      {
         "title": "WhatsApp beta for Android 2.24.2.12: what’s new?",
         "link": "https://wabetainfo.com/whatsapp-beta-for-android-2-24-2-12-whats-new/",
         "date": "Jan 12, 2024",
         "categories": [
            "ANDROID"
         ],
         "desc": "WhatsApp is rolling out a new update through the Google Play Beta Program, bringing the version up to 2.24.2.12. What’s new in this update? This is a bug-fix update that addresses an issue with viewing thumbnails for status updates!"
      },
      {
         "title": "WhatsApp beta for Android 2.24.2.11: what’s new?",
         "link": "https://wabetainfo.com/whatsapp-beta-for-android-2-24-2-11-whats-new/",
         "date": "Jan 11, 2024",
         "categories": [
            "ANDROID"
         ],
         "desc": "WhatsApp is rolling out a new update through the Google Play Beta Program, bringing the version up to 2.24.2.11. What’s new in this update? WhatsApp is rolling out a feature to share polls in channels, and it’s available to some beta testers!"
      },
      {
         "title": "WhatsApp beta for Android 2.24.2.9: what’s new?",
         "link": "https://wabetainfo.com/whatsapp-beta-for-android-2-24-2-9-whats-new/",
         "date": "Jan 11, 2024",
         "categories": [
            "ANDROID"
         ],
         "desc": "WhatsApp is rolling out a new update through the Google Play Beta Program, bringing the version up to 2.24.2.9. What’s new in this update? WhatsApp is rolling out a feature to apply new text formatting tools to messages, and it’s available to some beta testers!"
      },
      {
         "title": "WhatsApp beta for iOS 24.1.10.75: what’s new?",
         "link": "https://wabetainfo.com/whatsapp-beta-for-ios-24-1-10-75-whats-new/",
         "date": "Jan 11, 2024",
         "categories": [
            "IOS"
         ],
         "desc": "WhatsApp has just submitted a new update through the TestFlight beta Program, bringing the version up to 24.1.10.75. The version marked within WhatsApp Settings is 2.24.1.75 and the TestFlight build is 24.1.10 (554773775). What’s new in this update? This is a bug-fix update that addresses some critical crashes introduced in the previous updates!"
      }
   ]
}
```
</a>
<br>


<a name= "latest">

#### 🔍 Get Latest Result 
```
nimaWabetaInfo.getLatest()
  .then((result) => {
    console.log(result);
  })
  .catch((error) => {
    console.log(error);
  });

```
#### ✅ Result 
```
{
   "creator": "MR NIMA",
   "status": true,
   "result": {
      "title": "WhatsApp beta for Android 2.24.2.17: what’s new?",
      "updateFor": [
         "ANDROID"
      ],
      "date": "Jan 18, 2024",
      "image": "https://wabetainfo.com/wp-content/uploads/2024/01/WA_TRANSFER_OWNERSHIP_FEATURE_CHANNEL_ANDROID.jpg",
      "subtitle": "TRANSFER OWNERSHIP",
      "link": "https://wabetainfo.com/whatsapp-beta-for-android-2-24-2-17-whats-new/",
      "desc": "WhatsApp is rolling out a new update through the Google Play Beta Program, bringing the version up to 2.24.2.17.\nWhat’s new in this update? WhatsApp is working on a feature to transfer the channel ownership, and it will be available in a future update!After the latest announcement shared by Mark Zuckerberg from his official WhatsApp channel, WhatsApp is now working on other tools to help channel owners manage their channels with ease. Specifically, thanks to the latest WhatsApp beta for Android 2.24.2.17 update, which is available on the Google Play Store, we discovered that WhatsApp is working on a feature to allow channel owners to transfer the ownership of their channels!As you can see in this screenshot, a new option to transfer the ownership of a channel will be available within the channel info screen in the future. This option will allow channel owners to easily transfer the administrative rights and responsibilities to another channel admin of their choice. This feature is designed to enhance the flexibility and adaptability of WhatsApp channels, enabling transitions in the event of personal decisions by the current channel owner.We believe that this feature might also be useful in other situations, especially for channel owners who manage their channels using two different WhatsApp accounts. In such cases, where a channel owner may have distinct WhatsApp accounts for professional and personal use, the ability to transfer ownership becomes even more important. As the channel grows or undergoes a shift in focus, the channel owner may decide to separate their personal and professional communications by creating a dedicated WhatsApp account for the channel. The introduction of the ownership transfer feature will finally allow for a quick and secure transition between these accounts.The feature to transfer the channel ownership is under development and it will be available in a future update of the app. As always, we are going to publish a new article when we have further information to share with you.",
      "QandA": [
         {
            "question": "Name of the feature?",
            "answer": "Channel ownership"
         },
         {
            "question": "Status?",
            "answer": "Under development"
         },
         {
            "question": "Availability?",
            "answer": "WhatsApp is working on bringing a feature to transfer the channel ownership to a future update of the app."
         },
         {
            "question": "I’ve installed this update but I don’t have this feature. Why?",
            "answer": "This feature is under development so it’s not ready for beta testers, but you can discover a preview in this article."
         },
         {
            "question": "Previous news?",
            "answer": "Mark Zuckerberg announced voice notes, multiple admins, status sharing, and polls for WhatsApp channels!"
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
const link = "https://wabetainfo.com/whatsapp-beta-for-ios-23-15-1-76-whats-new/";

nimaWabetaInfo.getFromLink(link)
  .then((result) => {
    console.log(result);
  })
  .catch((error) => {
    console.log(error);
  });

```
#### ✅ Result 
```
{
   "creator": "MR NIMA",
   "status": true,
   "result": {
      "title": "WhatsApp beta for Android 2.24.2.17: what’s new?",
      "updateFor": [
         "ANDROID"
      ],
      "date": "Jan 18, 2024",
      "image": "https://wabetainfo.com/wp-content/uploads/2024/01/WA_TRANSFER_OWNERSHIP_FEATURE_CHANNEL_ANDROID.jpg",
      "subtitle": "TRANSFER OWNERSHIP",
      "link": "https://wabetainfo.com/whatsapp-beta-for-android-2-24-2-17-whats-new/",
      "desc": "WhatsApp is rolling out a new update through the Google Play Beta Program, bringing the version up to 2.24.2.17.\nWhat’s new in this update? WhatsApp is working on a feature to transfer the channel ownership, and it will be available in a future update!After the latest announcement shared by Mark Zuckerberg from his official WhatsApp channel, WhatsApp is now working on other tools to help channel owners manage their channels with ease. Specifically, thanks to the latest WhatsApp beta for Android 2.24.2.17 update, which is available on the Google Play Store, we discovered that WhatsApp is working on a feature to allow channel owners to transfer the ownership of their channels!As you can see in this screenshot, a new option to transfer the ownership of a channel will be available within the channel info screen in the future. This option will allow channel owners to easily transfer the administrative rights and responsibilities to another channel admin of their choice. This feature is designed to enhance the flexibility and adaptability of WhatsApp channels, enabling transitions in the event of personal decisions by the current channel owner.We believe that this feature might also be useful in other situations, especially for channel owners who manage their channels using two different WhatsApp accounts. In such cases, where a channel owner may have distinct WhatsApp accounts for professional and personal use, the ability to transfer ownership becomes even more important. As the channel grows or undergoes a shift in focus, the channel owner may decide to separate their personal and professional communications by creating a dedicated WhatsApp account for the channel. The introduction of the ownership transfer feature will finally allow for a quick and secure transition between these accounts.The feature to transfer the channel ownership is under development and it will be available in a future update of the app. As always, we are going to publish a new article when we have further information to share with you.",
      "QandA": [
         {
            "question": "Name of the feature?",
            "answer": "Channel ownership"
         },
         {
            "question": "Status?",
            "answer": "Under development"
         },
         {
            "question": "Availability?",
            "answer": "WhatsApp is working on bringing a feature to transfer the channel ownership to a future update of the app."
         },
         {
            "question": "I’ve installed this update but I don’t have this feature. Why?",
            "answer": "This feature is under development so it’s not ready for beta testers, but you can discover a preview in this article."
         },
         {
            "question": "Previous news?",
            "answer": "Mark Zuckerberg announced voice notes, multiple admins, status sharing, and polls for WhatsApp channels!"
         }
      ]
   }
}
```

</a>

<br><br>

### 👨‍💻 Author : [Mr Nima](https://github.com/darkmakerofc)

#### 🛠️ Package Updated.

* Fix Axios Error And Update Scraper Codes.
* Add Catogory For All Results.
* Add Sub-title For All Details.
