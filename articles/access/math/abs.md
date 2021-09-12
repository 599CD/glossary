---
title: Abs
description: Abs
author: alexhedley
---

# Abs

Using the Abs Function

In this tutorial you will learn how to use the Abs Function.

> Abs(number)

> The required *number* argument can be any valid numeric expression. If *number* contains Null, **Null** is returned; if it is an uninitialized variable, zero is returned.

> Info from MS

[Office VBA Reference](https://docs.microsoft.com/en-us/office/vba/language/reference/user-interface-help/abs-function)

---

Function Engine

In this example we will use -1.

![Abs](images/Abs.png "Abs")

The result is 1.

---

![Query](../../images/16/Query.png "Query") Query

```sql
SELECT Abs(-1);
```

![Form](../../images/16/Form.png "Form") Form

```vb
=Abs(-1)
```

![VBA](../../images/16/VBA.png "VBA") VBA

```vb
Private Sub Form_Load()
    txtAbs = Abs(-1)
End Sub
```

---

## Courses

![Access 2013](../../images/16/Access_2013.png "Access 2013") [Access Expert 26](https://www.599cd.com/site/courselist/access2013/expert/x26/)

## Seminars

![Access 2007](../../images/16/Access_2007.png "Access_2007") [Access 2007 SQL 2](https://www.599cd.com/site/courselist/seminars/access-sql/access-sql2/)

<!-- ## Tips / Tech Help

See [this](/tips/access/##/) FREE Tip on X and many others -->

<!-- ## Blog

See [this](/blog/display-article.asp?ID=#) Blog Post on X -->

## ![Magnifying Glass](../../images/MagnifyingGlass.png "Magnifying Glass") Search

You can find more about this by [searching](https://www.599cd.com/search/?Q=#) the website.
