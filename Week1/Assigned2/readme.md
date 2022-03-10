#*التكليف الاول 

###Q1 ما هو ال السطر الذي يتم كتابته لتخبر المتصفح أن إصدار اللغة المستخدم في إنشاء الصفحة هو HTML5?
!DOCTYPE
###Q2 ما هو ال Rendering Mode الذي سوف يتبعه المتصفح إذا لم تكتب السطر الخاص بتحديد الإصدار ؟
دي حاجه خاصة بالDOCTYPE  ، بمعني انه لازم نحدد الversion بتاع الHTML قبل ما نشتغل بحيث ان الbrowser يتعرف عليها بسهولة وميدخلش في مشكلة الquirks mode او بالمعني الحرفي مشكلة المراوغات مابيكونش عارف الtags الي جاية دي جاية منين

###Q3 هل من السليم إستخدام أكثر من h1 في الصفحة جاوب بنعم أو لا ؟
NO

###Q4 لديك عنصر يحتوي على بيانات المنتج وعنوان المنتج مكتوب ب h3 هل من المنطقي وضع عنوان h2 داخل نفس المنتج أم لا؟

NO

###Q5 إلى ماذا ترمز العناصر h1, h2, h3, h4, h5, h6?
Heading of the page.

___
#*التكليف التانى
###ََQ1 هل هناك إختلاف بين هذه العناصر عندما يتم إظهارهم في الصفحة أم لا ؟
```
<p class="element">Welcome To The New World</p>
<p class='element'>Welcome To The New World</p>
<p class=element>Welcome To The New World</p>
```
NO
___
#*التكليف التالت 
###Q1 هل هناك إختلاف بين هذه العناصر عندما يتم إظهارهم في الصفحة أم لا ؟
```
<p class=element hidden>Welcome To The New World</p>
<p class="element" hidden>Welcome To The New World</p>
```
NO
___
#*التكليف الرابع
###Q1 هل هذه العناصر سوف تظهر كلها بنفس الشكل أم لا ؟
```
<p>Hello World</p>

<p>
Hello World
</p>

<p>
Hello
World
</p>

<p>
Hello


World
</p>
```
NO
___
#*التكليف الخامس
###Q1 بجانب كل Attribute من الموجودين في المثال قم بكتابة هل هو من ال Global Attributes أم لا ؟
```
title    --->  Global
href     --->  NO
src      --->  NO
hidden   --->  Global
charset  --->  NO
class    --->  Global
id       --->  Global
type     --->  NO