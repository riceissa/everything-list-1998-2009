# everything-list archives, 1998–2009

Produced using [Hypermail](http://www.hypermail-project.org/) version 2.3.0.

For the hypermail config file I used, see [`hypermail.rc`](https://github.com/riceissa/everything-list-1998-2009/blob/master/hypermail.rc).

To get the mbox I used, see https://groups.google.com/d/msg/everything-list/UehP0dLy8cM/8Z9yLBSlbu4J

Mailing list announcement: <http://www.weidai.com/everything.html>. As
mentioned on that page, the Google Groups archive is missing early emails,
which is why I've made this repo.

To obfuscate the email addresses, I ran (in the Hypermail output directory
after producing the HTML files with Hypermail):

```bash
find . -type f -exec sed -i 's/-AT_SYMBOL-[A-Za-z0-9.-]\+/.domain.name.hidden/g' {} \;
```

Hypermail seems to be pretty aggressive at converting the at-symbol, so if you
see `-AT_SYMBOL-` or `.domain.name.hidden` in an email body, that probably
means it used to be `@`.
