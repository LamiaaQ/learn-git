
<div dir='rls' align='right'>

# tag مقدمة في أمر

<br>

بتعليم نقطة معينه  في تاريخ المخزن كما هو الحال بتعليم الإصدارات  ` tag ` يستخدم أمر


: ` tag `إضافة
</div

```git

git tag -a -m "tag message" <tagName> <commitNumber>

```
<div dir='rls' align='right'>

مثال للإصدارات 
</div>

```git

git tag -a -m "version 1 " v0.1 ee74f0c

```


<div dir='rls' align='right'>

طريقة الإستعلام عن (tag) 
</div>

```git

git tag

```

<div dir='rls' align='right'>
  
طريقة حذف (tag) 
</div>

```git
git tag -d  <tagName>

```
<div dir='rls' align='right'>
  
مثال للحذف: 
</div>

```git
git tag -d  v0.1 

```

<div dir='rls' align='right'>
  
طريقة عرض معلومات (tag)

</div>

```git

git show <tagName>

``` 

<div dir='rls' align='right'>
  
مثال للعرض:

  </div>


```git
$ git show v0.1

```
