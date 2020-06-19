muparserx 4.0.9
===========================
![titleimage](http://beltoforion.de/en/muparser/images/title.jpg)

This is the main repository of muparserx. 

The evaluation of a mathematical expression is a standard task required in many applications. It can be solved by either using a standard math expression parser such as muparser or by embedding a scripting language such as Lua. There are however some limitations: Although muparser is pretty fast it will only work with scalar values and although Lua is very flexible it does neither support binary operators for arrays nor complex numbers. So if you need a math expression parser with support for arrays, matrices and strings muparserx may be able to help you.

For details please consult the [muparserx documentation](https://beltoforion.de/article.php?a=muparserx)

V4.0.9 (20200619)
-----------------
Changes:
  - Copied unit tests from muparser (no new failures)
  - Introduced a maximum expression length of 10000
  - Expressions will be checked for non printable characters
  
Bugfixes:
  - Issue 68: 	Integer test causes floating point exceptions; fixed as suggested

V4.0.7 (20160331)
-----------------
Bugfixes:
  - Issue 68: 	Assertion fails (i.e "abs(-3)>abs(2)")
  - untracked issue: cbrt function did not work properly
  - new functions: atan2, reminder, fmod

