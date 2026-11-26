DUEL v4 — Pass Challenge আপডেট

এই সংস্করণে PASS QUESTION যোগ হয়েছে।

ব্যবহার:
• কোনো প্রতিযোগীর প্রশ্ন না পারলে PASS QUESTION চাপুন।
• দুইজন হলে অন্য প্রতিযোগীর কাছে স্বয়ংক্রিয়ভাবে পাস হবে।
• ৩–১০ জন হলে পপ-আপ থেকে একজনকে নির্বাচন করুন।
• পাস পাওয়া প্রতিযোগীর কাউন্টডাউন শুরু হবে।
• সময়ের মধ্যে PASS CORRECT / PASS INCORRECT চাপুন।
• সময় শেষ হলে সেটিংসে নির্ধারিত Timeout deduction স্বয়ংক্রিয়ভাবে কাটা হবে।
• পাসের জন্য মূল Round বাড়বে না। মূল প্রতিযোগীর turn PASSED হিসেবে গণ্য হবে, আর পাস পাওয়া ব্যক্তির পয়েন্ট আলাদাভাবে যোগ/বিয়োগ হবে।
• Pass শেষ হলে স্ক্রিন মূল প্রশ্নদাতার turn-এ ফিরবে; NEXT চাপলে স্বাভাবিক turn order চলবে।

Settings → Pass Challenge Settings:
- Countdown (1–300 seconds)
- Timeout deduction (positive amount; timeout-এ এটি বিয়োগ হবে)
- Pass Correct (স্বতন্ত্র পয়েন্ট)
- Pass Incorrect (স্বতন্ত্র পয়েন্ট)

গুরুত্বপূর্ণ:
1. পুরোনো অ্যাপ থেকে আগে Settings → Export Backup (JSON) করুন।
2. GitHub Pages repository-তে আগের ফাইলগুলো Replace করে এই ZIP-এর ভেতরের ফাইলগুলো Upload করুন।
3. service-worker.js-এ cache version v4 দেওয়া আছে, তাই আগের cache স্বয়ংক্রিয়ভাবে বদলাবে।
4. নতুন ওয়েবসাইটে পুরোনো ডেটা আনতে Settings → Import Backup করুন।
5. পুরোনো local file storage এবং নতুন HTTPS site storage আলাদা; Backup/Import ছাড়া ডেটা নিজে থেকে স্থানান্তর হয় না।

GitHub Pages: Settings → Pages → Deploy from a branch → main → /(root)
