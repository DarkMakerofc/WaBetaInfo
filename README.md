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
nimaWabetaInfo.getAll().then((result) => {

console.log(result)

}).catch(error => console.log(error))
```
#### ✅ Result 
```
{
  creator: 'MR NIMA',
  status: true,
  result: [
    {
      no: 1,
      title: 'WhatsApp beta for iOS 23.15.1.76: what’s new?',
      date: 'July 28, 2023July 28, 2023',
      link: 'https://wabetainfo.com/whatsapp-beta-for-ios-23-15-1-76-whats-new/',
      desc: 'WhatsApp has just submitted a new update through the TestFlight beta Program, bringing the version up to 23.15.1.76. The version marked within WhatsApp Settings is 2.23.15.76 and the TestFlight build is 23.15.1 (498983352).\n' +
        'What’s new in this update? WhatsApp is widely rolling out a video message feature, and it is available to more users starting today! '
    },
    {
      no: 2,
      title: 'WhatsApp beta for Android 2.23.16.7: what’s new?',
      date: 'July 27, 2023',
      link: 'https://wabetainfo.com/whatsapp-beta-for-android-2-23-16-7-whats-new/',
      desc: 'WhatsApp is rolling out a new update through the Google Play Beta Program, bringing the version up to 2.23.16.7.\n' +
        'What’s new in this update? This is a bug fix update that addresses an issue with sorting chats! '
    },
    {
      no: 3,
      title: 'WhatsApp beta for Android 2.23.16.6: what’s new?',
      date: 'July 27, 2023July 27, 2023',
      link: 'https://wabetainfo.com/whatsapp-beta-for-android-2-23-16-6-whats-new/',
      desc: 'WhatsApp is rolling out a new update through the Google Play Beta Program, bringing the version up to 2.23.16.6.\n' +
        'What’s new in this update? WhatsApp is rolling out safety tools when receiving messages from unknown phone numbers, and they are available to some beta testers! '
    },
    {
      no: 4,
      title: 'WhatsApp beta for Android 2.23.16.5: what’s new?',
      date: 'July 26, 2023July 26, 2023',
      link: 'https://wabetainfo.com/whatsapp-beta-for-android-2-23-16-5-whats-new/',
      desc: 'WhatsApp is rolling out a new update through the Google Play Beta Program, bringing the version up to 2.23.16.5.\n' +
        'What’s new in this update? WhatsApp is releasing a redesigned search bar, and it is available to some lucky beta testers! '
    },
    {
      no: 5,
      title: 'WhatsApp beta for Android 2.23.16.3: what’s new?',
      date: 'July 26, 2023July 26, 2023',
      link: 'https://wabetainfo.com/whatsapp-beta-for-android-2-23-16-3-whats-new/',
      desc: 'WhatsApp is rolling out a new update through the Google Play Beta Program, bringing the version up to 2.23.16.3.\n' +
        'What’s new in this update? WhatsApp is rolling out a feature that allows users to create a new group while forwarding messages, and it is available to some beta testers! '
    },
    {
      no: 6,
      title: 'WhatsApp beta for iOS 23.15.1.71: what’s new?',
      date: 'July 25, 2023July 25, 2023',
      link: 'https://wabetainfo.com/whatsapp-beta-for-ios-23-15-1-71-whats-new/',
      desc: 'WhatsApp has just submitted a new update through the TestFlight beta Program, bringing the version up to 23.15.1.71. The version marked within WhatsApp Settings is 2.23.15.71 and the TestFlight build is 23.15.1 (497978377).\n' +
        'What’s new in this update? WhatsApp is widely rolling out a message reaction feature for community announcement groups, and it’s available to more users today! '
    },
    {
      no: 7,
      title: 'WhatsApp is rolling out channels to additional countries starting today',
      date: 'July 24, 2023July 24, 2023',
      link: 'https://wabetainfo.com/whatsapp-is-rolling-out-channels-to-additional-countries-starting-today/',
      desc: 'Following the initial release of the ability to create and follow WhatsApp Channels in Singapore and Colombia, WhatsApp has now shared an announcement that this feature is finally available to additional countries for those users on the latest version of WhatsApp for iOS, Android, and Desktop. '
    },
    {
      no: 8,
      title: 'WhatsApp for iOS 23.14.79: what’s new?',
      date: 'July 24, 2023July 24, 2023',
      link: 'https://wabetainfo.com/whatsapp-for-ios-23-14-79-whats-new/',
      desc: 'WhatsApp has just submitted a new stable update for iOS, available on the App Store: the build number is 23.14.79.\n' +
        'What’s new in this update? WhatsApp is widely rolling out a chat transfer feature, the landscape mode support for video calls, and a silence unknown callers option! '
    },
    {
      no: 9,
      title: 'WhatsApp news of the week: open chat with unknown phone numbers, message reaction feature',
      date: 'July 23, 2023July 25, 2023',
      link: 'https://wabetainfo.com/whatsapp-news-of-the-week-open-chat-with-unknown-phone-numbers-message-reaction-feature/',
      desc: 'If you missed our stories this week about the latest updates to WhatsApp beta for Android, iOS, and Desktop, this is a good time to catch up thanks to our summary. Among the 10 stories we shared, the best news of the week is about a feature that allows users to open a chat with unknown phone numbers! '
    },
    {
      no: 10,
      title: 'WhatsApp beta for Android 2.23.15.24: what’s new?',
      date: 'July 22, 2023July 22, 2023',
      link: 'https://wabetainfo.com/whatsapp-beta-for-android-2-23-15-24-whats-new/',
      desc: 'WhatsApp is rolling out a new update through the Google Play Beta Program, bringing the version up to 2.23.15.24.\n' +
        'What’s new in this update? WhatsApp is widely rolling out enhancements to the interface of the app by following Material Design 3, making them available to an expanded group of beta testers starting today! '
    }
  ]
}
```
</a>
<br>


<a name= "latest">

#### 🔍 Get Latest Result 
```
nimaWabetaInfo.getLatest().then((result) => {

console.log(result)

}).catch(error => console.log(error))
```
#### ✅ Result 
```
{
  title: 'WhatsApp beta for iOS 23.15.1.76: what’s new?',
  link: 'https://wabetainfo.com/whatsapp-beta-for-ios-23-15-1-76-whats-new/',
  image: 'https://usercontent.one/wp/wabetainfo.com/wp-content/uploads/2023/06/WA_VIDEO_MESSAGES_FD445_IOS.png',
  date: '2023-07-28 | 08:22:33',
  desc: 'WhatsApp has just submitted a new update through the TestFlight beta Program, bringing the version up to 23.15.1.76. The version marked within WhatsApp Settings is 2.23.15.76 and the TestFlight build is 23.15.1 (498983352).\n' +
    'What’s new in this update? WhatsApp is widely rolling out a video message feature, and it is available to more users starting today!In our article regarding the WhatsApp beta for iOS 23.12.0.71 update, we announced that WhatsApp was finally releasing the ability to record and share video messages. Specifically, this feature allows users to share real-time videos lasting up to 60 seconds, and it works as effortlessly as sending a voice note. Mark Zuckerberg has also announced that this feature will soon be released on WhatsApp and is expected to reach all users over the coming weeks. After installing the latest WhatsApp beta for iOS 23.15.1.76 update, which is available on the TestFlight app, we can confirm that this feature is now widely rolling out to a larger group of users!As you can see in this screenshot, you need to tap the microphone icon within a conversation to transform it into a camera button. Users also have the option to swipe up to enable a hands-free experience while recording the video. It’s worth noting that when video messages are opened in a chat, they will automatically play in mute mode, and sound will only be played with a tap on the video. Video messages you share in your chats and groups are always end-to-end encrypted, making sure they can only be played by the intended recipient.Using video messages also provide users with a benefit compared to regular videos. they mainly offer a faster and more straightforward way to show your emotions and share moments with others. In addition, video messages are always unique as they cannot be edited, modified, or normally forwarded. They always remain genuine and authentic. This also means that when someone sends you a video message, that video message was recorded exclusively for you.The video messages feature is now available to more users who have installed the latest WhatsApp beta for iOS updates from the TestFlight app, and it will be gradually rolling out to an even broader audience in the coming days. However, since this is a wider release, several users that installed the latest update of WhatsApp from the App Store may be able to get the same feature today.Stay up-to-date on WhatsApp news by following WABetaInfo on Twitter. You can also discover other new features for WhatsApp beta for Android, iOS, Web/Desktop, and Windows.',
  QandA: [
    { question: 'Name of the feature?', answer: 'Video messages' },
    { question: 'Status?', answer: 'Rolling out' },
    {
      question: 'Compatibility?',
      answer: 'WhatsApp beta for iOS 23.15.1.76 is marked as a compatible update.'
    },
    {
      question: 'I have the same version but I don’t have this feature, why?',
      answer: 'This feature is available to more beta testers starting today, and it’s expected to be available to more people over the coming days.'
    },
    {
      question: 'Thanks:',
      answer: 'FastenM, for testing and reporting!'
    },
    {
      question: 'Previous news?',
      answer: 'WhatsApp beta for Android 2.23.16.7: what’s new? This is a bug fix update that addresses an issue with sorting chats!'
    }
  ]
}
```


</a>
  
<br>

<a name= "fromlink">
  
#### 🔍 Get Result From Link
```
var link = "https://wabetainfo.com/whatsapp-beta-for-ios-23-15-1-76-whats-new/"

nimaWabetaInfo.getFromLink(link).then((result) => {

console.log(result)

}).catch(error => console.log(error))
```
#### ✅ Result 
```
{
  title: 'WhatsApp beta for iOS 23.15.1.76: what’s new?',
  link: 'https://wabetainfo.com/whatsapp-beta-for-ios-23-15-1-76-whats-new/',
  image: 'https://usercontent.one/wp/wabetainfo.com/wp-content/uploads/2023/06/WA_VIDEO_MESSAGES_FD445_IOS.png',
  date: '2023-07-28 | 08:22:33',
  desc: 'WhatsApp has just submitted a new update through the TestFlight beta Program, bringing the version up to 23.15.1.76. The version marked within WhatsApp Settings is 2.23.15.76 and the TestFlight build is 23.15.1 (498983352).\n' +
    'What’s new in this update? WhatsApp is widely rolling out a video message feature, and it is available to more users starting today!In our article regarding the WhatsApp beta for iOS 23.12.0.71 update, we announced that WhatsApp was finally releasing the ability to record and share video messages. Specifically, this feature allows users to share real-time videos lasting up to 60 seconds, and it works as effortlessly as sending a voice note. Mark Zuckerberg has also announced that this feature will soon be released on WhatsApp and is expected to reach all users over the coming weeks. After installing the latest WhatsApp beta for iOS 23.15.1.76 update, which is available on the TestFlight app, we can confirm that this feature is now widely rolling out to a larger group of users!As you can see in this screenshot, you need to tap the microphone icon within a conversation to transform it into a camera button. Users also have the option to swipe up to enable a hands-free experience while recording the video. It’s worth noting that when video messages are opened in a chat, they will automatically play in mute mode, and sound will only be played with a tap on the video. Video messages you share in your chats and groups are always end-to-end encrypted, making sure they can only be played by the intended recipient.Using video messages also provide users with a benefit compared to regular videos. they mainly offer a faster and more straightforward way to show your emotions and share moments with others. In addition, video messages are always unique as they cannot be edited, modified, or normally forwarded. They always remain genuine and authentic. This also means that when someone sends you a video message, that video message was recorded exclusively for you.The video messages feature is now available to more users who have installed the latest WhatsApp beta for iOS updates from the TestFlight app, and it will be gradually rolling out to an even broader audience in the coming days. However, since this is a wider release, several users that installed the latest update of WhatsApp from the App Store may be able to get the same feature today.Stay up-to-date on WhatsApp news by following WABetaInfo on Twitter. You can also discover other new features for WhatsApp beta for Android, iOS, Web/Desktop, and Windows.',
  QandA: [
    { question: 'Name of the feature?', answer: 'Video messages' },
    { question: 'Status?', answer: 'Rolling out' },
    {
      question: 'Compatibility?',
      answer: 'WhatsApp beta for iOS 23.15.1.76 is marked as a compatible update.'
    },
    {
      question: 'I have the same version but I don’t have this feature, why?',
      answer: 'This feature is available to more beta testers starting today, and it’s expected to be available to more people over the coming days.'
    },
    {
      question: 'Thanks:',
      answer: 'FastenM, for testing and reporting!'
    },
    {
      question: 'Previous news?',
      answer: 'WhatsApp beta for Android 2.23.16.7: what’s new? This is a bug fix update that addresses an issue with sorting chats!'
    }
  ]
}
```

</a>

<br><br>

### 👨‍💻 Author : [Mr Nima](https://github.com/darkmakerofc)

#### 🛠️ Package Updated.

* Fix Image undefined Error
