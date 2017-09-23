# [GuillemAndreu.com](https://guillemandreu.com)

My personal website and portfolio. Fourth iteration of the site. Using [Ghost](https://ghost.org/) for the content management. The code in this repo is a theme for Ghost.

---

Having the primary tag in the permalink is not officially supported in Ghost via de the UI, to set permalinks this way it needs to be updated directly in the database:

```sql
mysql> UPDATE settings SET `value`='/:primary_tag/:slug/' WHERE `key`='permalinks';
```

---

**Feel free to use some bits of the code if it is useful to you,** that’s why I share the code here on GitHub. I learned (and continue to do so) by looking at other people’s code, this is a small way of giving back on that sense.

---

**Note:** The fonts used for this website are no included in the repository as their license does not allow distribution.
