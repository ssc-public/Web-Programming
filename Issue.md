# حل issue

## مقدمه
هدف از این بخش، آشنایی شما با فرآیند مشارکت درتوسعه‌ی پروژه‌های متن‌باز (open source) و یادگیری روند حل issue و ایجاد pr (pull request) است.

## توضیحات 

- در ﻣﺮﺣﻠﻪ اول ﺷﻤﺎ ﺑﺎﯾﺪ ﺑﺎ جست‌و‌جو در GitHub و ﯾﺎ ﺳﺎﯾﺮ ﻣﺨﺎزن ﮐﺪﻫﺎی ﻣﺘﻦﺑﺎز اﻗﺪام ﺑﻪ اﻧﺘﺨﺎب issue های ﻣﻨﺎﺳﺐ کنید.
- ﺣﻞ issue ﻣﯽﺗﻮاﻧﺪ ﺑﻪ ﺻﻮرت ﻓﺮدی و ﯾﺎ در ﮔﺮوهﻫﺎی ﺣﺪاﮐﺜﺮ ﺳﻪ ﻧﻔﺮه اﻧﺠﺎم ﺷﻮد.
- ﻫﺮ ﻓﺮد ﺑﺎﯾﺪ دو واﺣﺪ issue اﻧﺠﺎم دﻫﺪ؛ ﺑﻨﺎﺑﺮاﯾﻦ یک گروه ﺳﻪ ﻧﻔﺮه ﺑﺎﯾﺪ شش واﺣﺪ issue اﻧﺠﺎم دﻫﺪ. ﻫﺮ issue ﺳﺎده ﻣﻌﺎدل ﯾﮏ واﺣﺪ، ﻫﺮ issue ﻣﺘﻮﺳﻂ ﻣﻌﺎدل دو واﺣﺪ و ﻫﺮ issue ﺳﺨﺖ ﻣﻌﺎدل ﺳﻪ واﺣﺪ است.
- ﺳﺨﺘﯽ و ﺳﺎدﮔﯽ با نظر دستیار آموزشی و بر مبنای اﻧﺪازه ﮐﻞ ﭘﺮوژه و ﺧﻮاﺳﺘﻪ آن issue ﺗﻌﺮﯾﻒ می‌شود.
- پیش از اقدام به کارکردن روی issue، آن را برای دستیار آموزشی ارسال کنید و تاییدیه‌ی حل را بگیرید. این کار جهت مشورت با دستیار آموزشی برای انتخاب issue های مناسب‌تر است.
- توجه کنید که لزومی ندارد pr های شما حتماً merge شوند تا نمره‌ی آن‌ها را بگیرید، اما در صورت merge شدن pr ها با کد اصلی پروژه‌ی هدف، ممکن است که نمره‌ی اضافه‌تری دریافت کنید!
- در issue هایی که به حل آن‌ها می‌پردازید، حتماً باید کد بزنید و پاسخ‌دادن به issue هایی که در آن‌ها سوالی مطرح شده یا اصلاح مستندات پروژه (مانند اصلاح README) هدف این بخش نیست.
-  بعضی از repository ها (مانند [این](https://github.com/thinkswell/javascript-mini-projects)) مجموعه‌ای گردآوری‌شده از پروژه‌های کوچک‌تر هستند که بیشتر به عنوان مثال استفاده می‌شوند و هر پروژه‌ی کوچک، مستقل از پروژه‌های دیگر است. حل issue و ایجاد pr در این repository ها هم مجاز نیست.
- توجه کنید issue اﻧﺘﺨﺎﺑﯽ ﺷﻤﺎ ﺣﺘﻤﺎ ﺑﺎﯾﺪ در وﺿﻌﯿﺖ open ﺑﺎﺷﺪ و ﻓﺮدی از ﻗﺒﻞ و ﺑﻪ ﺗﺎزﮔﯽ ﺷﺮوع به ﮐﺎر روی آن issue را اﻋﻼم ﻧﮑﺮده باشد.
-  حل issue هایی که بنابه‌هردلیلی close شده‌اند، مجاز نیست.

## تجربیات
- مهم‌ترین گام برای گرفتن نمره‌ی کامل این بخش از درس، انتخاب issue ی مناسب وقابل‌حل است.
- دسته‌ای از issue ها با برچسب good-fitst-issue مشخص شده‌اند. پیشنهاد می‌شود برای حل ایشوها ابتدا به سراغ آن‌ها بروید، چرا که خوش‌دست‌تر و راحت‌فهم‌تر هستند.
- وب‌سایت‌هایی وجود دارند که به شما در پیداکردن good-first-issue ها کمک می‌کنند؛ مانند [این](https://goodfirstissue.dev/) و [این](https://github.com/topics/good-first-issue). در این وب‌سایت‌ها می‌توانید بر حسب زبان مورد نظرتان، issue ها را جداسازی کنید.
- یکی از راه‌های به‌دست‌آوردن دید بهتر نسبت به ایشوهای یک پروژه، خواندن documentation آن پروژه است.
- هم‌چنین بالاآوردن پروژه به صورت local و دست‌و‌پنجه‌نرم‌کردن با بخش‌های مختلف آن، در شناخت بهتر پروژه موثر است.
- اگر در پروژه‌ی نسبتاً بزرگی باگی مشاهده کردید، می‌توانید برای اعلام آن باگ issue ای ثبت کنید و سپس خودتان به حل آن ایشو بپردازید.
- آن دسته از issue هایی که پیرامون حل آن‌ها، بحث زیادی شکل گرفته و پیام‌های زیادی زیر آن issue ردوبدل شده، احتمالاً issue های چالشی‌تر و سخت‌تری هستد و به همین علت، تلاش برای حل آن‌ها توصیه نمی‌شود.
- این نکته‌ی مهمی است که باید «شروع» کرد. به قول شاعر:
> تو پای در راه نِه و هیچ مپرس
> 
> خود راه بگویدت که چون باید رفت
- برای پیداکردن این که کجای کد به کار ما ربط دارد، گرپ (یا چیزی معادل آن مثل سرچ vscode) خیلی کمک می کند؛ مثلاً اگر برنامه خطایی برمی‌گرداند، با گرپ‌کردن متن خطا، جایی از کد که باید عوض کنیم مشخص می‌شود.

## لیست issue های میانترم
این لیست شامل تعدادی مخزن پیشنهادی برای حل issue است؛ لزومی ندارد حتماً issue هایتان را از بین مخازن زیر انتخاب کنید و مجاز هستید که از هر منبع دیگری به حل issue بپردازید. موضوع کلی issue های میانترم، بحث Frontend است.

1. https://github.com/browserify/browserify
2. https://github.com/headjs/headjs/
3. https://github.com/dalekjs/dalek
4. https://github.com/angular/protractor/
5. https://github.com/DevExpress/testcafe/
6. https://github.com/avajs/ava
7. https://github.com/Automattic/expect.js
8. https://github.com/gotwarlost/istanbul
9. https://github.com/assaf/zombie
10. https://github.com/laurentj/slimerjs/
11. https://github.com/karma-runner/karma
12. https://github.com/theintern/intern
13. https://github.com/puppeteer/puppeteer
14. https://github.com/getgauge/taiko
15. https://github.com/preactjs/preact
16. https://github.com/NativeScript/NativeScript
17. https://github.com/walmartlabs/thorax
18. https://github.com/marionettejs/backbone.marionette
19. https://github.com/artf/grapesjs
20. https://github.com/twitter/hogan.js
21. https://github.com/handlebars-lang/handlebars.js
22. https://github.com/marko-js/marko
23. https://github.com/chartjs/Chart.js
24. https://github.com/paperjs/paper.js
25. https://github.com/fabricjs/fabric.js
26. https://github.com/NUKnightLab/TimelineJS3
27. https://github.com/handsontable/handsontable
28. https://github.com/frappe/datatable
29. https://github.com/parallax/jsPDF
30. https://github.com/lodash/lodash
31. https://github.com/andrewplummer/Sugar
32. https://github.com/selfrefactor/rambda
33. https://github.com/adamwdraper/Numeral-js
34. https://github.com/marcuswestin/store.js
35. https://github.com/davidmerfield/randomColor
36. https://github.com/DmitryBaranovskiy/raphael
37. https://github.com/visjs/vis-network
38. https://github.com/processing-js/processing-js
39. https://github.com/gwatts/jquery.sparkline
40. https://github.com/visionmedia/page.js
41. https://github.com/nolimits4web/swiper
42. https://github.com/hammerjs/hammer.js
43. https://github.com/gridsome/gridsome
44. https://github.com/jamesallardice/Placeholders.js
45. https://github.com/fullcalendar/fullcalendar
46. https://github.com/dataarts/dat.gui

## لیست issue های پایانترم
این لیست شامل تعدادی مخزن پیشنهادی برای حل issue است؛ لزومی ندارد حتماً issue هایتان را از بین مخازن زیر انتخاب کنید و مجاز هستید که از هر منبع دیگری به حل issue بپردازید. موضوع کلی issue های پایانترم، بحث Backend و DevOps است.

1. https://github.com/sourcegraph/conc
2. https://github.com/stretchr/testify
3. https://github.com/kubernetes/client-go
4. https://github.com/opencontainers/image-spec
5. https://github.com/containerd/containerd
6. https://github.com/redis/go-redis
7. https://github.com/aquasecurity/trivy-operator
8. https://github.com/go-playground/validator
9. https://github.com/spf13/cobra
10. https://github.com/casbin/casbin
11. https://github.com/influxdata/telegraf
12. https://github.com/pingcap/tidb
13. https://github.com/opencost/opencost
14. https://github.com/kubesphere/kubesphere
15. https://github.com/hashicorp/consul
16. https://github.com/go-co-op/gocron
