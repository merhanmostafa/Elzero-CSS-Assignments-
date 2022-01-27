# Assignments

## Assignment 1

اكتب في تعليق كل Selector ما الذي يعبر عنه

```code
/* Any Element With Class Title */
.title {
}

/* Any Element With Id nav */
#nav {
}

/* Any div elemnt in the page*/
div {
}

/* Any h2 elemnt in the page */
h2 {
}
```
---
## Assignment 2

اكتب في تعليق نوع كل Style من التالي

```code
<!-- Externel Style -->
<link rel="stylesheet" href="css/file.css" />

<!-- Internel Style -->
<style>
p {
  color: red;
}
</style>

<!-- Inline Style -->
<p style="color: blue;">This Is Our Paragraph</p>
```

---

## Assignment 3

قم بإستدعاء ملف Style خارجي موجود في مجلد بجانب ال index.html بإسم assets وداخله مجلد باسم css وإسم الملف هو master.css

```code
<!-- Write Path -->
<link rel="stylesheet" href="assets/css/master.css" />
```

---

## Assignment 4

قم بإستدعاء ملف Style خارجي موجود في مجلد خارج المجلد الموجود فيه ملف ال index.html بإسم source وداخله مجلد بإسم css وإسم الملف هو main.css

```code
<!-- Write Path -->
<link rel="stylesheet" href="../source/css/main.css" />
```

---

## Assignment 5

في أسماء ال Identifiers التالية حدد ما هو صالح وما هو غير صالح عن طريق كتابة Valid أو Not Valid في التعليق قبل الإسم

```code
/* Valid */
._user-name {
}

/* Valid */
.-user-name {
}

/* Valid */
.-user-name {
}

/* Not Valid */
.1user-name {
}

/* Not Valid */
.@user-name {
}

/* Not Valid */
.user@name {
}

/* Valid */
._user10name {
}

/* Valid */
.u {
}
```

---

## Assignment 6

في أسماء ال Identifiers التالية حدد ما الذي يتبع ال Best Practice عن طريق كتابة Good أو Bad في التعليق قبل الإسم

```code
/* Bad */
.USERNAME {
}

/* Bad */
.UserName {
}

/* Good */
.user-name {
}

/* Bad */
.userName {
}

/* Bad */
.usernameprofile {
}
```
