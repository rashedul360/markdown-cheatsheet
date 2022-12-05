<!-- এভাবে যত # দিবেন সেহিসেবে হেডিং আসবে  -->

# আজকে আমরা শিখব গিটহাব মার্কডাউন সম্পর্কে ।

### কিভাবে আমরা হেডিং লেখতে পারি ?

আমাদের H1 থেকে H6 পর্যন্ত হেডিং ট্যাগ রয়েছে । আমরা যদি এগুলো মার্কডাউনের মাধ্যমে প্রকাশ করতে চাই তাহলে আমরা এভাবে করতে পারি ।

```markdown
# heading 1 for <H1> Tag

## heading 1 for <H2> Tag

### heading 1 for <H3> Tag

#### heading 1 for <H4> Tag

##### heading 1 for <H5> Tag

###### heading 1 for <H6> Tag
```

    মার্কডাউনে html এঁর প্রায় বা সকল ট্যাগ সাপোর্ট করবে । কারণ মার্কডাউন এক প্রকার এইচটিএমএল

### প্যারাগ্রাফ বা কোন টেক্সট দেখাতে চাইলে কি করতে পারি ?

শুধু .md ফাইলে গিয়ে লেখা শুরু করলেই হবে ।

```markdown
আমি রাশেদুল ইসলাম । আমি একজন ওয়েব ডেভেলপার । এখন আমি মার্কডাউন শিখছ
```

### অউটপুট

আমি রাশেদুল ইসলাম । আমি একজন ওয়েব ডেভেলপার । এখন আমি মার্কডাউন শিখছ

### কোনও প্যারাগ্রাফের আগে যদি একটা ট্যাব অথবা ৪ টা স্পেস দেয় তাহলে অউটপুট এমন দেখাবে ।

\# একটা ট্যাব দিলে সেটা আর প্যারাগ্রাফ থাকবে না । সেটা ব্লক হয়ে যাবে

###### ভিসুয়াল স্টুডিও কোডের দৃশ্য

```markdown
    lorem ipsum dolor sit amet, consectetuer adip lorem ipsum d lorem ipsum dolor lorem ipsum dolor
    lorem ipsum dolor sit amet, consectetuer adip
```

###### আউটপুট

    lorem ipsum dolor sit amet, consectetuer adip lorem ipsum d lorem ipsum dolor lorem ipsum dolor
    lorem ipsum dolor sit amet, consectetuer adip

### কিভাবে আমরা একটা লেখাকে align করতে পারি ?

```markdown
<p align="center">lorem ipsume 
  </br>
 lorem ipsume 
</p>

এখানে align="center" দিয়ে দেখানো হয়েছে আমরা চাইলেই একে left বা right করতে পারি ।
```

### অউটপুট

<p align="center">lorem ipsume <br>lorem ipsume </br></p>

### কোনও লেখাকে বোল্ড করতে চাইলে ।

\# লেখার প্রথমে ও শেষে \*\* (২ টা স্টার) দিলে সেটা বোল্ড হয়ে দেখাবে ।

```markdown
**this is a bold line**

<!-- __এভাবে সামনে ২ টা আন্ডারস্কোর দিলেও বোল্ড হয়ে দেখাবে__  -->
```

### আউটপুট

২ ভাবে লেখার আউটপুট একই দেখাবে ।
**this is a bold line**

### কোন লেখাকে ইতালিক করার নিয়ম ।

```markdown
এভাবেও লেখা যায় আমি কমেন্ট করে রেখেছি

<!-- *this is a italic line* -->

আবার এভাবেও দেখা যায় ।
_this is a italic line_
```

### আউটপুট

_আমার নাম রাশেদুল ইসলাম সিহাব_

### একটা লাইনের যেকোনো একটা ওয়ার্ড বা অংশ বোল্ড করতে চাইলে ।

```markdown
this is line where this **world** will be bo**LD**
```

### আউটপুট

this is line where this **world** will be bo**LD**

# কোনও লেখাকে বোল্ড ও ইতালিক একসাথে করতে চাইলে

আমরা \*\*\* (৩ টা স্টার) দিয়ে লেখব তাহলেই হবে । কারণ VS code এ ফাইল সেভ করার সাথে সাথে তার সিনট্যাক্স অনুযায়ী সাজিয়ে নিবে ।

```markdown
<!-- ***এভাবেও হবে*** -->

**_lorem ipsum dolor sit amet, consectetur adip_**
```

### অউটপুট

**_lorem ipsum dolor sit amet, consectetur adip_**

### কোনও লেখাকে কেটে দিতে বা strikethrough করতে চাইলে কিভাবে করতে পারি ?

```markdown
২ টা ~~ চিহ্ন দিলেই কাজটি হয়ে যাবে  
~~strikethrough~~
```

### আউটপুট

~~strikethrough বা লেখা কেটে দেওয়া~~

###### এটা ভাল করে লেখব হাহা

<!-- blockquote তৈরি করার উপায়  -->
<!-- ওভাবেও হয় তবে আমরা এভাবে করব না । markdown এ কেন এইচটিএমএল লেখব  -->
<blockquote>lorem doctor
   <blockquote>lorem doctor
       <blockquote>lorem doctor</blockquote>
   </blockquote>
</blockquote>

### কিভাবে আমরা একটা লিস্ট তৈরি করতে পারি ?

আমরা প্রথমে দেখব ol বা orderd list তৈরি করা । এটা খুব সিম্পলে অনেকভাবে এটা করা যাবে ।

###### নিয়ম ১

যেকোনো নাম্বার লেখে . (ডট) দিয়ে স্পেস দিলেই orderd list তৈরি হয়ে যাবে ।

```markdown
1. orderd list number 1
1. orderd list number 2
1. orderd list number 3
1. orderd list (nested)
   1. nested list number 1
   1. nested list number 2
   1. nested list number 3
1. another one orderd list
```

    এখানে আমি সব নাম্বারকে ১ দিয়ে লেখেছি এটা কোনও ব্যাপার না । কারণ আমরা আউটপুট দেখলেই বুঝে যাব । কেননা আউটপুটে সব সিরিয়াল অনুযায়ী সাজিয়ে নিবে ।

### আউটপুট

1. orderd list number 1
1. orderd list number 2
1. orderd list number 3
1. orderd list (nested)
   1. nested list number 1
   1. nested list number 2
   1. nested list number 3
1. another one orderd list

<!-- unorderd list  -->

### এখন আমরা শিখব unorderd list তৈরি করা ।

```markdown
- unorderd list
- unorderd list
- nested unorderd list
  - nested item
  - nested item
  - nested item
- another unorderd list
```

### আউটপুট

- unorderd list
- unorderd list
- nested unorderd list
  - nested item
  - nested item
  - nested item
- another unorderd list

### অন্যভাবে unorderd list তৈরির নিয়ম

###### নিয়ম ১

```markdown
এভাবেও করা যাবে কোনও সমস্যা নেই ।

<!--

* first item
* second item
* third item
  * nested item

-->
```

###### নিয়ম ২

```markdown
এভাবেও করা যাবে কোনও সমস্যা নেই ।

<!--

+ first item
+ second item
+ third item
  +nested item

-->
```

### লিঙ্ক তৈরি করার নিয়ম

```markdown
[গুগলে যাও](https://google.com/)
```

### অউটপুট

[গুগলে যাও](https://google.com/)

##### লিঙ্কের সাথে টাইটেল যুক্ত করতে পাইলে

এই টাইটেল মাউস হোভার করলে দেখাবে

```markdown
[গুগলে যাও with title on hover](https://google.com/ "go to google.com")
```

##### আউটপুট

[গুগলে যাও with title on hover](https://google.com/ "go to google.com")

##### ইমেইল লিঙ্ক তৈরি

ইমেইল লিঙ্ক বলতে বুঝাতে চাওয়া হচ্ছে যে একটা ইমেইল এড্রেসে ক্লিক করলে তা সরাসরি ইমেইল অ্যাপ ওপেন করে দিবে এবং সেখান থেকেই ইমেইল প্রেরণ করা যাবে ।

```markdown
<rashedul360rs@gmail.com>
```

##### আউটপুট

<rashedul360rs@gmail.com>
এই লিঙ্কে ক্লিক করলে সরাসরি ইমেইল ওপেন হবে ।

<!-- advanced link -->

##### এখন আমরা লিঙ্কের উন্নত কাজ দেখব ।

যেমন আমাদের এমন হতে পারে যে, একটা লিঙ্ক বার বার কর্মকার হচ্ছে বা লিঙ্ক তৈরি করার সাধারণ সিনট্যাক্স মেনে কাজ করতে গেলে সেটা পড়ার উপযোগিতা থাকছেনা । তখন আমরা কিভাবে কাজ করব ? আমরাতো শুধু নিজেই লেখে নিখেই পরব না এটা অন্যকেও পড়তে পারে । তাই না ? তাদেরকেও তো বুঝার মত করে লেখতে হবে সেটা আমরা কিভাবে মরতে পারি ? ঠিক এভাবে

```markdown
[rashedul][1] islam is a web developer. [rashedul][1] islam created a [muhurta-pata website][2] and his [facebook ID][3] link in here

[1]: https://dev-rashedul.web.app/ "website link"
[2]: https://muhurto-pata.web.app/ "muhurta-pata"
[3]: https://www.facebook.com/rashedul2004/ "facebook id"
```

##### আউটপুট

[rashedul][1] islam is a web developer. [rashedul][1] islam created a [muhurta-pata website][2] and his [facebook ID][3] link in here

[1]: https://dev-rashedul.web.app/ "website link"
[2]: https://muhurto-pata.web.app/ "muhurta-pata"
[3]: https://www.facebook.com/rashedul2004/ "facebook id"

### ইমেজ কিভাবে আমাদের ফাইলে যুক্ত করব ।

###### সিনট্যাক্স

```markdown
![altitude](link)
```

##### ব্যাবহার

```markdown
![image name if not image not loaded](https://i.ibb.co/Pr7gfMq/Screenshot-3-removebg-preview.png "image title on hover")
```

### আউটপুট

![image name if not image not loaded](https://i.ibb.co/Pr7gfMq/Screenshot-3-removebg-preview.png "image title on hover")

##### এখন আমরা একটা কাজ করব সেটা হচ্ছে, যখন আমরা একটা ইমেজে ক্লিক করব তখন জেন একটা ওয়েবপেজে রিডাইরেক্টকরে দেয় ।

```markdown
[![image name if not image not loaded](https://i.ibb.co/Pr7gfMq/Screenshot-3-removebg-preview.png "image title on hover")](https://dev-rashedul.web.app/)
```

### আউটপুট

[![image name if not image not loaded](https://i.ibb.co/Pr7gfMq/Screenshot-3-removebg-preview.png "image title on hover")](https://dev-rashedul.web.app/)

### এখন আমন সময় আসতে পারে যে আমাদের ইমেজ গুলোকে align করতে হবে তখন কিভাবে করব ?

খুব সহজ , এমন একটা এলেমেন্টের ভেতরে মোরিয়ে দিব যেটা ব্লক লেভেল এলেমেন্ট

```markdown
<p align="center">
   <img src="https://muhurto-pata.web.app/static/media/banner.2b78f2216301c9ccd559.webp" width="200px" />
</p>
```

### আউটপুট

<p align="center">
<img src="https://muhurto-pata.web.app/static/media/banner.2b78f2216301c9ccd559.webp" width="200px" /></p>

### এখন আমরা টেবিল বানানো শিখব

```markdown
| name     | roll | class          |
| -------- | ---- | -------------- |
| rashedul | 12   | inter 1st year |
| rashedul | 12   |                |
| rashedul | 12   | inter 1st year |
```

### আউটপুট

| name     | roll | class          |
| -------- | ---- | -------------- |
| rashedul | 12   | inter 1st year |
| rashedul | 12   |                |
| rashedul | 12   | inter 1st year |

### কিভাবে কোড ব্লক তৈরি করতে হয় - create code block

```markdown
now i am displaying the `<img src=".." ></img>` tag
```

### আউটপুট

now i am displaying the `<img src=".." ></img>` tag

###### এমন সময় আসতে পারে যে আপনাকে পুরো একটা কোড এঁর মকআপ তৈরি করতে হবে তখন আপনি এভাবে লিখতে পারেন ।

```
<body>
   <header>
      <title>learning markdown<title>
   </header>
</body>
```

<!-- github flaver markdown -->

```html
<body>
   <header>
      <title>github flever markdown<title>
   </header>
</body>
```

```javascript
console.log("i am logged");
```

### কিভাবে চেকবক্স তৈরি করতে হয় . চেকবক্স দেখার জন্য github markdown Preview VS code extension টি প্রয়োজন হবে

###### কোড

```markdown
- [ ] unchecked checkbox
- [x] checked checkbox
```

### আউটপুট

- [ ] unchecked checkbox
- [x] checked checkbox

### ড্রপডাউন তৈরি করা

```markdown
<details>
   <summary>dropdown item </summary>
ড্রপডাউনে ক্লিক করলে এই লেখাগুলো দেখাবে 
# টাইটেল
lorem ipsum dolor sit amet, consectet
</details>
```

### আউটপুট

<details>
   <summary>dropdown item </summary>
ড্রপডাউনে ক্লিক করলে এই লেখাগুলো দেখাবে 
# টাইটেল
lorem ipsum dolor sit amet, consectet
</details>

### হরিযন্টাল লাইন তৈরি করার নিয়ম

হরিযন্টাল লাইন তৈরি করতে চাইলে ৩ টা --- (ড্যাশ) অথবা ৩ টা \*\*\* (স্টার) অথবা ৩ টা \_\_\_ (underscores) দিলেই একটা হরিযন্টাল লাইন তৈরি হয়ে যাবে

###### কোড

```markdown
---
```

### আউটপুট

---

#### কিভাবে কিবোর্ড এঁর সিম্বল তৈরি করা যায় ?

###### কোড

```markdown
to copy <kbd> CTRL</kbd >+ <kbd>C</kbd>
```

### আউটপুট

to copy <kbd> CTRL</kbd >+ <kbd>C</kbd>

### কিভাবে ব্যাজ তৈরি করতে হয় ?

প্রথমত <kbd>shields.io</kbd> ওয়েবসাইটে জেতে হবে । তারপর static অপশনে গিয়ে আপনার জন্য একটি ব্যাজ তৈরি করে নিন । ব্যাজ তৈরি হলে একটা লিঙ্ক পাবেন সেটা কপি করে নিন , তারপর এইভাবে আপনার কোডে ইনক্লুড করুন । তারপর আউটপুট দেখুন ।

```html
<img src="copied url" />
```

### গুরুত্বপূর্ণ কথা

##### যদি আপনি চান যে, +,-,#,## ইত্যাদি চিহ্ন আউটপুটে দেখাবেন তাহলে কিভাবে করতে পারেন ? দেখিয়ে দিচ্ছি

```markdown
\# এটা একটা হেডিং
\+ এটা একটা লিস্ট
\- এটা আর একটা লিস্ট
\ সহ দেখতে চাইলে
\\# এটা একটা হেডিং
\\+ এটা একটা লিস্ট
\\- এটা আর একটা লিস্ট
```

### আউটপুট

\# এটা একটা হেডিং
\+ এটা একটা লিস্ট
\- এটা আর একটা লিস্ট
\ সহ দেখতে চাইলে
\\# এটা একটা হেডিং
\\+ এটা একটা লিস্ট
\\- এটা আর একটা লিস্ট

### কিভাবে কমেন্ট লেখতে পারি ? - how to write a comment

```markdown
[comment]: <> (i am written a comment)
[//]: <> (i am a comment)

platform independent syntex
[//]: # (i am a comment)
```

### making a table of content

#####table of content

- [about me](#about)
- [contact us](#contact)

<a name="about"></a>

## about me

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

## contact us

<a name="contact"></a>
Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
