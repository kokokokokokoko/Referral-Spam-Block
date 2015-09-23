# Referral Spam Block
A simple .htaccess file for redirecting referral spammers, and improving bounce rate on small or new websites.
This project came out of frustration with the referral spam not only throwing off the statistics on my smaller/ new websites, but also effecting SEO on these sites as well.

Bounce rate is something many search engines take into account. It helps gauge how good a result was, and ranks accordingly (after combining with many other factors obviously).

Referral spam can be damaging because of this, especially with low traffic sites. New sites can be 90%+ referral spam, with 100% bounce rate.

## Useage

* Make sure your server is running Apache. Most linux based servers do. 

* Check for an .htaccess file in your root directory, you may need to unhide hidden files.

* If there's one already there: Back up your old file(s), then append our list to the end of your .htaccess file(s).

* If theres not one in place: create one. Each directory can only have one htaccess file. Putting this in your root dir is sufficient.

## Warnings etc.

Always back up your htaccess file before editing it! You can break your site if you make a mistake.

Although we do work to only block spam, this file may block wanted traffic as well. Use at your own risk.

If you see any errors, or think something should be removed, please comment.

## FAQ

Where is the spam traffic sent?

* Currently: http://pastebin.com/raw.php?i=aZByQFvc

