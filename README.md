# Cracker Sultan's Port Hunter DDOS 😈

![DDOS Attack](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExMXlzdHVsbGdzd3YyazRtdjZ5bzBtc3B6dDM2b2w1bm1xOW9kM3dnbCZlcD1WMV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/lqfW5zCNzXJm/giphy.gif)

> "আমি ক্র্যাকার সুলতান, আর এইটা আমার ডিজিটাল নরকযন্ত্র। নেট দুনিয়ায় আগুন জ্বালানোই আমার কাজ।"

এই রিপোজিটরিটা **ক্র্যাকার সুলতান**-এর জন্য বানানো একটা অত্যন্ত পাওয়ারফুল এবং সহজবোধ্য DDOS (Distributed Denial of Service) টুল। এটা শুধুমাত্র একটা পাইথন ফাইলে তৈরি করা হয়েছে, যাতে কোনো জটিল সেটআপের ঝামেলা না থাকে। এই টুলটি টার্গেট সার্ভারকে অসংখ্য কানেকশন রিকোয়েস্ট পাঠিয়ে অচল করে দেয়।

**সবচেয়ে গুরুত্বপূর্ণ বৈশিষ্ট্য:** এই টুলটি **স্বয়ংক্রিয়ভাবে টার্গেটের সক্রিয় পোর্ট সনাক্ত করে**। তোর ম্যানুয়ালি পোর্ট ইনপুট দেওয়ার দরকার নেই, হারামজাদা!

---

## **কেন Cracker Sultan's Port Hunter DDOS?**

* **এক ফাইল সমাধান:** কোনো জটিল স্ট্রাকচার বা একাধিক ফাইল নেই। শুধু `ddos.py`।
* **স্বয়ংক্রিয় পোর্ট সনাক্তকরণ:** টার্গেটের জন্য 80, 443, 8080, 8443 সহ সাধারণ ওয়েব পোর্টগুলো স্বয়ংক্রিয়ভাবে স্ক্যান করে সক্রিয় পোর্ট খুঁজে বের করে। যদি কোনো সক্রিয় পোর্ট না পাওয়া যায়, তবে ডিফল্টভাবে 80 পোর্ট ব্যবহার করে।
* **সিম্পল এবং পাওয়ারফুল:** ছোট কোড কিন্তু টার্গেটের পাছা ফাটাতে যথেষ্ট!
* **বর্ধিত ফেক IP জেনারেশন:** অ্যাটাক সোর্স ট্রেস করা আরও কঠিন করার জন্য ২০,০০০ এর বেশি র্যান্ডম ফেক IP ব্যবহার করে।
* **সহজ কমান্ড-লাইন ইন্টারফেস:** শুধু `GET <TARGET> [THREADS] Attack` লিখে এন্টার দিলেই কাজ শুরু।
* **বিস্তারিত লগিং:** অ্যাটাকের প্রতিটি ধাপ `ddos_attack_log.txt` ফাইলে সেভ হয়, যাতে তুই তোর ধ্বংসযজ্ঞ ট্র্যাক করতে পারিস।

---

## **কীভাবে চালাবি, শালা! 💥 (ব্যবহার পদ্ধতি)**

এই টুলটা ব্যবহার করা একদম সোজা। নিচে দেওয়া ধাপগুলো ফলো কর:

### **ধাপ ১: রিপোজিটরি ক্লোন কর বা ফাইল ডাউনলোড কর**

প্রথমে এই রিপোজিটরিটা তোর সিস্টেমে ক্লোন কর। যদি `git` ইনস্টল না থাকে, তাহলে শুধু `ddos.py` ফাইলটা ডাউনলোড করে নিলেই হবে।

```bash
# রিপোজিটরি ক্লোন করার জন্য:
git clone [https://github.com/sultanarabi161/cracker-sultan-ddos.git]([https://github.com/YourGitHubUsername/Cracker-Sultan-Port-Hunter-DDOS.git](https://github.com/sultanarabi161/cracker-sultan-ddos.git)
cd Cracker-Sultan-Port-Hunter-DDOS
