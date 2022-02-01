# bible

---ABOUT---

Bible is a simple python script that outputs a Bible verse from 2 different translations side-by-side: The New World Translation and another translation. The default second translation is the New American Standard Bible. The second translation can be changed by editing 2 variables in the code.

The NWT text is scraped from wol.jw.org, and the second translation is scraped from biblegateway.com.

The second translation can be changed to any translation available on biblegateway.com by editing the "version" and "printed_nas" variables. The version variable for other translations can be found on biblegateway.com, looking up any verse in the desired translation, and viewing the version code at the end of the resulting URL. For example the URL "https://www.biblegateway.com/passage/?search=Joel+1&version=NASB1995" indicates that NASB1995 is the translation code.

---USAGE---

Syntax = bible [full book name in proper case] [book number] [verse number]

Example:
"bible Joel 1 2" (note that the book name must be in proper case - "Joel" not "joel"; there is a list of names in the code)

Output using the example arguments:

NEW WORLD TRANSLATION:

2 “Hear this, you elders, And pay attention, all you inhabitants of the land.  Has anything like this happened in your days Or in the days of your forefathers? 

NEW AMERICAN STANDARD BIBLE:

2 Hear this, O elders, And listen, all inhabitants of the land. Has anything like this happened in your days Or in your fathers’ days?

