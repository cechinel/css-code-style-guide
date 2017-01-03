# CSS Code Style Guide

1. [Syntax](#)
1. [Statements](#)
1. [Comment](#)

### Syntax

Use tab-size with four spaces:

```css
/* good */
.btn {
	color: #ccc;
}

/* bad */
.btn {
   color: #ccc;	
}
```

Always use double quotes:

```css
/* good */
.btn {
    background-image: url("picture.jpg");
    font-family: "Helvetica Neue", sans-serif;
}

/* bad */
.btn {
    background-image: url('picture.jpg');
    font-family: 'Helvetica Neue', sans-serif;
}
```

Include a space before opening the rule keys:

```css
/* good */
.btn {
    color: #fff;
}

/* bad */
.btn{
    color: #fff;
}
```

Closes the keys on a new line:

```css
/* good */
.btn {
    color: #fff;
}

/* bad */
.btn {
    color: #fff;}
```

Include a space after the: statement:

```css
/* good */
.btn {
    color: #fff;
}

/* bad */
.btn {
    color:#fff;
}
```

Always use one; at the end of the declaration:

```css
/* good */
.btn {
    color: #fff;
}

/* bad */
.btn {
    color: #fff
}
```

Always keep one statement per line:

```css
/* good */
.nav,
.footer,
.btn {
    color: #fff;
}

/* bad */
.nav, .footer, .btn {
    color: #fff;
}
```

Separate the rules by a blank line:

```css
/* good */
.btn {
    color: #fff;
}

.nav-item {
    color: #fff;
}

/* bad */
.btn {
    color: #fff;
}
.nav-item {
    color: #fff;
}
```

Always use cashier:

```css
/* good */
.nav-item {
    color: #fff;
}

/* bad */
.Nav-item {
    color: #fff;
}
```

Use hyphens to separate names:

```css
/* good */
.nav-item {
    color: #fff;
}

/* bad */
.nav_item {
    color: #fff;
}
```

Whenever using hexadecimal values always use reduced values:

```css
/* good */
.nav-item {
    color: #fff;
}

/* bad */
.nav-item {
    color: #ffffff;
}
```

Do not specify units when the value is zero:

```css
/* good */
.nav-item {
    padding: 0;
}

/* bad */
.nav-item {
    padding: 0px;
}
```

Do not use values starting with zero:

```css
/* good */
.nav-item {
    transition: color .3s;
}

/* bad */
.nav-item {
    transition: color 0.3s;
}
```

### Statements

All statements must be in alphabetical order.

```css
/* good */
.btn {
    background: #000;
    color: #fff;
    display: inline-block;
    margin: 0;
    padding: 10px;
}

/* bad */
.btn {
    color: #fff;
    background: #000;
    margin: 0;
    padding: 10px;
    display: inline-block;
}
```

Comments

```css
/* Section comment block
======================================== */

/* Sub-section comment block
==================== */

/* Basic comment */
```


