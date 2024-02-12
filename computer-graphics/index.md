# Computer Graphics


## 01. What is Computer Graphics

Computer graphics is a field of study concerned with the generation and manipulation of images, videos, and animations using computers and digital technologies.

### Applications of Computer Graphics

Computer Graphics has numerous applications, some of which are listed below:
- Graphical User Interface (GUI)
- Business Presentation Graphics
- Cartography (ম্যাপ আঁকানো)
- Weather Maps
- Satellite Imaging
- Photo Enhancement
- Medical Imaging
- Engineering Drawings (থ্রিডি মডেলিং, CAD ইত্যাদি)
- Typography
- Architecture
- Art (গ্রাফিক্স ডিজাইনিং, ডিজিটাল আর্ট)
- Training (সিমুলেশনের মাধ্যমে প্লেন চালানো শেখানো)
- Entertainment (ভিডিও গেমস, মুভির ভিজুয়াল ইফেক্টস ইত্যাদি)
- Simulation and Modeling

## 02. Colors

> কালার বা রঙ নিয়ে আলোচনা করার সময় একটা জিনিস নিয়ে ভুল করার সম্ভাবণা খুবই বেশি থাকে, সেটা হচ্ছে আলো/লাইট এবং পেইন্টকে এক ভাবা। লাল রঙের আলো আর লাল রং/পেইন্ট কিন্তু একই জিনিস না।

![](https://imagizer.imageshack.com/img924/396/dLMJs5.jpg)

একটা লাল আলোর টর্চ 🔴, একটা সবুজ আলোর টর্চ 🟢 আর একটা নিল আলোর টর্চ 🔵 একসাথে জ্বালালে সাদা আলো ⚪ পাওয়া যাবে। কিন্তু লাল, নিল আর সবুজ রঙ মিশালে/গুলালে কিন্তু কখনই সাদা পাবা না।

এর কারণ আলো মিশালে সেটা Additive অর্থাৎ রঙগুলো যোগ হচ্ছে, আর রঙ/পেইন্ট মিশালে সেটা Substractive অর্থাৎ আলো বাদ হচ্ছে। নিচের ছবিটা দেখলে বিষয়টা পরিষ্কার হবেঃ

![](https://imagizer.imageshack.com/img922/8681/RlXdjj.png)

### RGB

The **RGB color model** is an *additive* color model in which the red 🔴, green 🟢and blue 🔵 primary colors of light are added together in various ways to reproduce a broad array of colors.

![](https://imagizer.imageshack.com/img923/6201/evkAFz.png)

নিচের ভিডিওটা দেখঃ


{{< youtube H6unlDDMceM >}}


### CMY

The **CMY color model** is a *subtractive* color model in which the cyan, magenta and yellow colors are mixed together in various ways to reproduce a broad array of colors.

![](https://imagizer.imageshack.com/img922/5141/H0iQgc.png)

![](https://imagizer.imageshack.com/img922/4263/GxcGA8.jpg)

## 03. Image Depth/Bit Depth

Bit depth is the amount of color information contained in each pixel in an image.

অর্থাৎ, কোনো ইমেজের একটা পিক্সেল যতগুলো কালার প্রকাশ করতে পারবে সেটাই হচ্ছে সে ইমেজের বিট ডেপথ।

> খেয়াল রাখবা, ইমেজ ডেপথ শুধু 1-bit হলে সেটাকে Bitmap ইমেজ বলে। আর একের বেশি হলে সেটাকে Pixmap ইমেজ বলে।

### 1-Bit

1-bit মানে একটাই বিট। আর একটা বিট দিয়ে 2<sup>1</sup> = 2 টা কালার প্রকাশ করা যায়। অর্থাৎ, ==1-bit ইমেজের একটা পিক্সেল শুধু দুই ধরণের কালার প্রকাশ করতে পারবে।== যেমন - সাদা আর কালো।

#### Examples

![1 bit Image](https://imagizer.imageshack.com/img924/4706/OALtPb.png)

### 8-Bit

8-bit মানে আটটা বিট। আর আটটা বিট দিয়ে 2<sup>8</sup> = 256 টা কালার প্রকাশ করা যায়। অর্থাৎ, ==8-bit ইমেজের একটা পিক্সেল 256 ধরণের কালার প্রকাশ করতে পারবে।==

#### 8-bit Grayscale Image
শুধু সাদা-কালোর ২৫৬টা শেড দিয়ে এ ছবি গঠিত।

![8 bit image](https://imagizer.imageshack.com/img924/5667/uTDAqO.png)

## 04. Raster Graphics vs Vector Graphics

![](https://imagizer.imageshack.com/img924/862/CGJUbV.png)

### Vector Graphics

ভেক্টর গ্রাফিক্স হচ্ছে সেসব গ্রাফিক্স যেগুলো জুম করলেও ফেটে যায় না। অর্থাৎ, scale করলে distorted হয় না। ফন্টস হচ্ছে ভেক্টর গ্রাফিক্স-এর একটা ভালো উদাহরণ, তুমি কোনো পিডিএফ জুম করতে থাকলেও দেখবা যে ফন্ট গুলো ফেটে যাচ্ছে না।

![](https://imagizer.imageshack.com/img922/296/G3cnWt.png)

### Raster Graphics

র‍্যাস্টার গ্রাফিক্স হচ্ছে সেসব গ্রাফিক্স যেগুলো পিক্সেল দিয়ে গঠিত। র‍্যাস্টার গ্রাফিক্স জুম করতে তাকলে একসময় আমরা পিক্সেলগুলোকে আলাদা করে দেখতে পাই যেটাকে আমরা ছবি ফেটে যাওয়া বলে থাকি।

![](https://imagizer.imageshack.com/img923/7109/iyg5lx.png)

## 05. Cathode Ray Tube (CRT) Monitor

> একটা গ্রাফিকাল সিস্টেমের প্রধাণ একটা আউটপুট ডিভাইস হচ্ছে মনিটর। কারণ আমরা মনিটোরের মাধ্যমেই কোনো গ্রাফিক্স দেখে থাকি। এখন অনেক ধরণের মনিটরের রয়েছে, তার মধ্য একটা হচ্চে CRT মনিটার যেটা এখন প্রায় উঠেই গেছে।

![CRT TV](https://imagizer.imageshack.com/img924/1904/yf5Xdj.jpg)

A **CRT (Cathode Ray Tube)** monitor is an older type of computer display that was commonly used in the past.

### How it Works

It works by firing an *electron beam* at a *phosphor-coated screen* to produce a visual image. The electron beam scans the screen line by line, lighting up the phosphor dots to create the image.

![](https://imagizer.imageshack.com/img924/3134/OPp5Sf.jpg)

### Raster Scan

In a **raster scan system**, the electron beam is swept across the screen, one row at a time from top to bottom. As the electron beam moves across each row, the beam intensity is turned on and off to create a pattern of illuminated spots.

![](https://imagizer.imageshack.com/img922/1391/pLNcnN.png)

নিচের ভিডিওটা দেখলে বিষয়টা ক্লিয়ার হবে।

{{< youtube ovEFpmz9R-c >}}

### Example


![](https://imagizer.imageshack.com/img923/4083/NNrLdQ.png)


