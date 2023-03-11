## এসাইনমেন্ট রিকুয়ারমেন্ট:

মডিউল ৬ এ আমরা react এবং redux toolkit ব্যবহার করে কিভাবে একটি প্রোজেক্ট করা যায় সেটি দেখেছি। কিভাবে সার্ভার থেকে আমরা ডেটা নিয়ে আসতে পারি, ট্যাগ ফিল্টার করতে পারি, সার্চিং এবং রাউটিং সম্পর্কেও জেনেছি। এবার একই ধরনের একটি প্রোজেক্ট আপনাকে একদম শুরু থেকে করতে হবে। এই এসাইনমেন্ট এ আপনাদের যা করতে হবে তা হচ্ছে, একটি ব্লগ সাইট এর State Manage করতে হবে। সেখানে বেশ কিছু ফিচার যুক্ত করতে হবে।

রেফারেন্স ট্যাবে দেয়া গিটহাব রিপোজিটরির 6.13 ব্রাঞ্চের 'html' ফোল্ডারে এসাইনমেন্টের জন্যে একটি HTML template দিয়ে দেয়া হয়েছে। সেই সাথে লোকাল সার্ভারের জন্যে JSON Place Holder কনফিগার করে দেয়া হয়েছে যেটি আপনারা 'server' ফোল্ডারে পাবেন। সেই কনফিগারেশন অনুযায়ীই সার্ভারটি ব্যবহার করতে হবে এবং অবশ্যই সার্ভারটি '9000' পোর্টে চালাতে হবে।

**উল্লেখ্য যে, এসাইনমেন্ট এর ডিজাইনে কোন ধরনের পরিবর্তন করা যাবে না এবং HTML template এ দেয়া কোনো বাটন বা এলিমেন্ট এর ক্লাস বা আইডি পরিবর্তন করা যাবে না। সেই ক্লাস বা আইডি দিয়েই আপনাকে এসাইনমেন্টটি সম্পন্ন করতে হবে। অন্যথায় এসাইনমেন্টটি গ্রহনযোগ্য হবে না এবং এসাইনমেন্ট এর কোনো মার্ক নাও পেতে পারেন।**

#### এসাইনমেন্ট এ আপনাকে যা যা করতে হবেঃ

✓ আমরা Fake JSON Server দিয়ে দিয়েছি এবং সেখানে বেশ কিছু ব্লগ থাকবে, সেগুলো আপনাকে fetch করে নিয়ে এসে হোম পেজে দেখাতে হবে।

✓ ব্লগ গুলো প্রথম অবস্থায় সারিবদ্ধ ভাবে দেখাবে অর্থাৎ API থেকে যেই সিরিয়ালে পাঠাবে সেই সিরিয়ালেই দেখাতে হবে। পরবর্তীতে Sort মেনু থেকে "Newest", "Most Liked" এ ক্লিক করলে পর্যায়ক্রমে নতুন গুলো এবং সব থেকে বেশি লাইক পাওয়া গুলো ফিল্টার দেখাবে।

✓ লাইকে ক্লিক করলে লাইকের সংখ্যা বাড়বে, যেহেতু Authentication নেই, সেহেতু যত ইচ্ছা লাইক দেয়া যাবে এবং সেটি সার্ভারের সাথে Sync থাকবে।

✓ বাম পাশের মেনুতে "Saved" এ ক্লিক করলে, যে গুলো সেভ করা হয়েছে সেগুলোই দেখাবে।

✓ কার্ডের Title বা Thumbnail এ ক্লিক করলে, Details পেজে নিয়ে যাবে। এক্ষেত্রে অবশ্যই 'react-router-dom' প্যাকেজের মাধ্যমে রাউটিং ম্যানেজ করতে হবে। এসাইনমেন্ট Deploy করার পরে এটি নিশ্চিত হবেন, যেন সরাসরি ওই পেজে গেলেও, Blog Details দেখা যায়।

✓ Details পেজে "Save" বাটনে ক্লিক করলে, সেটি আলাদা ভাবে বুক মার্ক হবে, অর্থাৎ 'Save' লেখাটি 'Saved' হবে এবং নীল রং হবে (এটির জন্যে 'active' নামে একটি CSS ক্লাস বানিয়ে দেয়াই আছে)।

✓ Details পেজে, 'Related Blogs' সেকশনে ট্যাগ অনুযায়ী রিলেটেড ব্লগ গুলো দেখাবে।

✓ যেই ব্লগ পোষ্ট এর ডিটেইল পেজে যাবো, সেই পোষ্ট যেন 'Related Blogs' এর লিস্ট এ না আসে।

## কিভাবে সাবমিট করবেন:

সবচেয়ে সহজে বুঝার জন্য [এই ভিডিওটি](https://learnwithsumit.com/courses/think-in-a-redux-way/how-to-submit-assignment) দেখে ফেলুন।

এসাইনমেন্টে আপনাকে মাত্র দুইটা জিনিস সাবমিট করতে হবে।

1. **GitHub private repository link:** অবশ্যই সঠিক গিটহাব রিপোজিটরি লিংক দিতে হবে। ভুলে অন্য কোনো লিংক দিলে আপনি এসাইনমেন্টের মার্ক পাবেন না তাই সাবমিট করার আগে নিউ ট্যাবে লিংক ওপেন করে চেক করে নিবেন সঠিক লিংক জমা দিচ্ছেন কিনা।

2. **Live site link:** নেটলিফাইতে সাইট হোস্ট করে সাইটের লাইভ লিংক দিতে হবে। ভুলে অন্য কোনো লিংক দিলে আপনি এসাইনমেন্টের মার্ক পাবেন না তাই সাবমিট করার আগে নিউ ট্যাবে লিংক ওপেন করে চেক করে নিবেন সঠিক লিংক জমা দিচ্ছেন কিনা। নেটলিফাইতে কি ভাবে হোস্ট করতে হয় তা আপনি না জানলে [এইখানে ক্লিক](https://learnwithsumit.com/courses/think-in-a-redux-way/how-to-submit-assignment) করে দেখে নিতে পারেন।

**সাবমিট একবারই করতে পারবেন তাই ভালো করে দেখে সাবমিট করবেন।**

## GitHub private repository কিভাবে তৈরি করবেন:

Github Private repositoty তৈরি করতে [এইখানে ক্লিক করুন](https://classroom.github.com/a/ZGJGL5fh) অথবা ব্রাউজারে এই লিংকে **https://classroom.github.com/a/ZGJGL5fh** ভিজিট করুন। লিংকে যাওয়ার পরে **Accept this assignment** এ ক্লিক করুন। সর্বোচ্চ ১মিনিট পরে পেইজটি রিলোড দিলে আপনি আপনার রিপোজেটরি লিংক পেয়ে যাবেন। মনে রাখবেন, আপনাকে এই লিংকটি আমাদের প্লাটফর্মে সাবমিট করতে হবে। না বুঝলে উপরে বলা ভিডিও টিউটোরিয়ালটি দেখে নিন।

## Assignment এর জন্য প্রয়োজনীয় template HTML এবং server কোথায় পাবেন:

প্রতিটি assignment এর সাথে প্রয়োজনীয় HTML template এবং "server" folder (API) আমরা দিয়ে দিয়েছি যেন আপনাকে HTML template এবং সার্ভার সাইড কাজ নিয়ে সময় নষ্ট না করতে হয়। কোর্সের GitHub repository এর সংশ্লিষ্ট ব্রাঞ্চে গেলেই আপনারা 'html' folder এর ভিতর HTML template পাবেন। একই ভাবে 'server' folder এ server API পেয়ে যাবেন। না বুঝলে [এইখানে ক্লিক](https://learnwithsumit.com/courses/think-in-a-redux-way/how-to-submit-assignment) করে টিউটোরিয়াল দেখে নিতে পারেন।

## এসাইনমেন্ট মার্কস পলিসি:

আপনি নির্ধারিত সময়ে এসাইনমেন্ট জমা দিলে এবং সব কিছু সঠিকভাবে করলে সম্পূর্ণ মার্ক পাবেন। এর পরে জমা দিলে আপনার মার্ক নিচের নিয়মে কাটা যাবে -

1. ডেডলাইনের পরে এক ঘণ্টার মধ্যে জমা দিলে 10% মার্ক কাটা যাবে।
2. ডেডলাইনের পরে এক ঘণ্টার বেশি কিন্তু 24 ঘণ্টার মধ্যে জমা দিলে 30% মার্ক কাটা যাবে।
3. ডেডলাইনের পরে 24 ঘণ্টার বেশি পরে জমা দিলে 50% মার্ক কাটা যাবে।
4. কোর্স ডিউরেশনের পরে আমরা এসাইনমেন্ট গ্রহণ করবো না।

অবশ্যই কোর্স চলাকালিন সময়ে এসাইনমেন্ট জমা দিতে হবে। কোর্সের ডিউরেশন শেষ হয়ে গেলে তার পরে আপনি এসাইনমেন্টে জমা দিলে এসাইনমেন্টের মার্ক পাবেন না।

## সাবমিট করার পর কোড পরিবর্তন:

আপনি ভেবে নিতে পারেন আপনি ওয়েবসাইটে সঠিক সময়ে এসাইনমেন্ট সাবমিট করে নীরবে পরে গিটহাবে কোড পুশ করতে থাকবেন! আপনার গিটহাবের সর্বশেষ কমিট দেখলেই আমরা বুঝতে পারবো আপনি কখন কোড আপডেট করেছেন। সে অনুযায়ী আমরা আপনার মার্ক কেটে নিবো। তাই এসাইনমেন্ট এর সময় পার হবার পরে আমরা আশা করবো আপনি চালাকি করে আর কোড পুশ করবেন না আপনার রিপোজিটরিতে। এটা করলে আপনার সম্পূর্ণ মার্ক কাটা যেতে পারে।

## এসাইনমেন্ট মার্কস কবে পাবেন:

আমরা সর্বোচ্চ ৭ দিনের ভিতরে এসাইনমেন্টের মার্ক দিয়ে দেওয়ার চেষ্টা করবো। ক্ষেত্র বিশেষে একটু দেরি হতে পারে কারো কারো মার্ক পেতে।
# video-website-with-redux
