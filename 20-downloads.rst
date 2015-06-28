Be careful about downloads
--------------------------

One of the most common ways viruses get on your computer is through
surfing the web and downloading programs.

Note that the advice in this section build upon previous sections. Using
out of date software and using administrator accounts for daily tasks
makes it easier for viruses to download themselves onto your computer.

There are a lot of sketchy, misleading software sites on the Internet.
Some of them are outright scams: the software they offer comes preloaded
with viruses and other malware. Other sites make money by posting
misleading advertisements intended to make you download stuff you really
don't want on your computer.

Even legitimate software products like Oracle (which makes Java) and
Adobe (which make Flash player) bundle nasty toolbars with their
plugins.

In this section we will cover some good practices for avoiding these
nasties.

Use Ninite for common downloads
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

One of the best resources for installing clean software is Ninite.
Previously we discussed re-running Ninite installers to keep your
existing software up to date, but you can also use Ninite to install new
software. Ninite does not include every piece of software you might ever
want to download, but it does include a selection of the most popular
programs and plugins. It also promises to keep its downloads clean of
toolbars and other unwanted bundles (and in our experience they have
kept this promise so far).

To install new software go to http://ninite.com. Scroll down to see the
list of programs:

.. figure:: pix/20-downloads/05-ninite/00-ninite-homepage.png
   :align: center
   :alt: Ninite homepage

Select the set of programs you would like to install. If you already
have a Ninite installer, you can choose your new programs and also the
ones from your own installer, or you can just select new programs.

When you have chosen the programs you want, click "Get Installer".

.. figure:: pix/20-downloads/05-ninite/05-select-mozy-essentials.png
   :align: center
   :alt: Select programs

The installer should download to your computer.

.. figure:: pix/20-downloads/05-ninite/07-download-finish.png
   :align: center
   :alt: Post-download page

.. figure:: pix/20-downloads/05-ninite/10-download-dialog.png
   :align: center
   :alt: Save installer

Save this installer in a place where you can find it again. You can use
it to keep your software up to date. An easy way to find the installer
is to open the download location:

.. figure:: pix/20-downloads/05-ninite/15-open-download-folder.png
   :align: center
   :alt: Open download dialog

Finally, right-click the installer and choose "Run as Administrator" to
install your programs.

.. figure:: pix/20-downloads/05-ninite/20-run-as-admin.png
   :align: center
   :alt: Run as administrator

You will be prompted for an administrator password, and then you will
see the program downloading and installing files:

.. figure:: pix/20-downloads/05-ninite/25-simple-interface.png
   :align: center
   :alt: Download: simple interface

Click the "Show details" link to get more information about Ninite's
progress:

.. figure:: pix/20-downloads/05-ninite/30-detailed-interface.png
   :align: center
   :alt: Download: detailed interface

Not every program offered by Ninite is perfect, but it is our first
choice for recommended downloads (which is why we chose to recommend
MozyHome as our remote backup program).

To update your programs, simply run the installer as administrator
again. You do not need to go back to the Ninite homepage to re-download
an installer.

Install an ad blocker
~~~~~~~~~~~~~~~~~~~~~

Many viruses get on your computer when you click the wrong window on
your screen, or click a misleading advertisement that downloads unwanted
software to your computer. For this section, we'll use the example of
downloading a software program from a popular download site. This site
contains many misleading advertisements intended to trick you into
downloading things you do not want. (We have documented several other
examples of misleading downloads [WHERE?])

.. figure:: pix/20-downloads/10-adblock/03-majorgeeks.png
   :align: center
   :alt: Misleading advertisements

If you use an ad-blocking plugin for your web browser, many of these
malicious advertisements will not show up, making your website safer. We
will demonstrate how to install the ad blocker AdBlockPlus for Firefox.

To start, run Firefox and navigate to Ad-Ons:

.. figure:: pix/20-downloads/10-adblock/05-add-ons-link.png
   :align: center
   :alt: Navigate to add-ons link

In the search bar, type "AdBlock Plus"

.. figure:: pix/20-downloads/10-adblock/10-adblock-search.png
   :align: center
   :alt: Search for Adblock Plus

Choose the AdBlock Plus plugin and choose to install it. Be careful that
you choose the right product -- as you can see there are many different
adblock plugins. Most of them are probably okay, but there may be some
that are themselves malicious.

Once you have chosen to install the plugin, Firefox should then indicate
that the plugin is installed.

.. figure:: pix/20-downloads/10-adblock/15-installed.png
   :align: center
   :alt: Adblock Plus installed

Ironically, the Adblock Plus website will then pop up in a browser
window:

.. figure:: pix/20-downloads/10-adblock/20-abp-popup.png
   :align: center
   :alt: Adblock Plus website

Now when you navigate to websites in Firefox, AdBlock Plus will block
obnoxious ads.

.. figure:: pix/20-downloads/10-adblock/25-majorgeeks-adblocked.png
   :align: center
   :alt: Misleading ads are gone!

However, it will not block all advertisements. By default, it will
continue to display "non-obtrusive" ads:

.. figure:: pix/20-downloads/10-adblock/30-unobtrusive-ad.png
   :align: center
   :alt: Supposedly unobtrusive advertisement

This brings up an important ethical issue about ad-blocking software.
Using an ad blocker is a good practice to avoid scary popups and
inadvertant downloads. However, many internet sites get much of their
revenue by displaying advertisements, and when you use an ad blocker you
deprive those websites of their revenue stream. That means those
websites could go out of business, depriving you of future content.

Thus, it might be advisable to allow websites that you like and trust to
display advertisements to you. To do this, you "whitelist" the website.
To do this, first navigate to the website.

.. figure:: pix/20-downloads/10-adblock/35-mefi-blocked.png
   :align: center
   :alt: Website worth supporting

Choose the AdBlock Plus icon in the corner, and select "disable" for
this website:

.. figure:: pix/20-downloads/10-adblock/40-unblock-dialog.png
   :align: center
   :alt: Unblock dialog box

Then the website will be able to display advertisements to you.

.. figure:: pix/20-downloads/10-adblock/45-mefi-ads-allowed.png
   :align: center
   :alt: The website shows ads now

If you allow ads on trustworthy websites you enjoy, then it is less
likely that those websites will go out of business.

Unfortunately ethical issues around ad-blocking get even more
complicated ethically. Advertisements on the Internet are also tracking
mechanisms: they track where you go and what you do on the Internet.
Some people are okay with this. Other feel it is intrusive, and so use
ad blockers to block as many ads as they can. As if that is not enough,
there is not guarantee that the ad-blocking software itself is
trustworthy! There are no easy answers to this quandry; you will have to
decide your own values and comfort level and act accordingly.

Be careful about email attachments
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Another common way for viruses to get on your computer is if you
mistakenly open an email attachment that contains a virus. Email
providers are getting better about screening out virus-laden attachments
from the email your receive, but infected attachments are still common.

Here are some rules of thumb to follow:

If you are not expecting an attachment, then do not open it. For
example, the following email from a stranger is suspect:

[SCREENSHOT]

Even if you get an email from a friend or relative you might be in
trouble. Be particularly wary if the email has strange wording or does
not sound as if it came from the recipient in question, or if the email
is asking you for money. In such situations the email account of your
friend or relative may have been hacked, and is sending out virus-laden
emails to everybody in their contact list:

[SCREENSHOT]

You should almost never open attachments that have two filename
extensions, such as .zip.exe :

[SCREENSHOT]

Such attachments are named to confuse you, and very often contain
viruses.

If you are unsure about whether a particular attachment is safe to open
or not, you should contact the sender in question -- preferably over the
phone or an instant messenger program, not email! Many antivirus
programs will also attempt to scan the attachment for viruses, but this
is not always foolproof.

Be careful about links in email
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Distinguishing legitimate email from scam emails takes a lot of
practice. Often you will see plausible-looking emails containing links
for you to click. Here is an example:

.. figure:: pix/20-downloads/20-emaillinks/10-fake-url.png
   :align: center
   :alt: Fake Paypal Email

There are many clues that suggest this email is fake: - misspelled words
- pressure tactics to get you to click the link - an address of
"hostme@interac.com" instead of an address from paypal.com - the
destination of the link going to a different web URL (you can see this
by hovering over the "Confirm My Address" link)

Even if you do not catch any of these clues, you still should not click
links in emails you do not expect. If you are worried that the warnings
might be legitimate, go to the web service directly (in this case, go to
the PayPal website by searching for "paypal" in a search engine) and
then log in there. If the warning is legitimate you will probably be
able to confirm this after logging in.

If you don't have a PayPal account at all, then you can be sure that
this message is fake.

If the link is to a website then make sure the displayed link text
matches the link destination.

.. figure:: pix/20-downloads/20-emaillinks/05-easy-spam.png
   :align: center
   :alt: Fake WhatsApp Email

This message wants to fool you into thinking that somebody sent you a
link to a video via WhatsApp (a social networking platform). If you
hover over the link, however, it goes to "creamnetwork.com", which is
probably a hacked website. Sometimes the misleading links can be pretty
close to the real one. For example, instead of "whatsapp.com" a link
might be spoofed as "whatsapp.someotherwebsite.com".

It takes a fair amount of practice to learn how to distinguish fake
emails from real ones. And the problem is not limited to email! Spammers
have invaded Facebook, Twitter, blogs, and many other platforms, and all
of these platforms contain links intended to get you in trouble. But
even if you are not a computer genius, there are some rules of thumb
that can help keep you safe:

-  If you are not expecting the email in question, **don't click the
   link**.
-  If you get a link to a website in your email, **go to the website
   directly**, not by clicking the link.
-  If you get an email from a friend or family member that seems fishy,
   **don't follow instructions**. Spammers routinely break into email
   accounts and send spam emails to everybody in the victim's contact
   list.
-  If you do click a link and it takes you to a login page, **do not log
   in, and close your browser window**. Often such login pages are fake,
   intended to get your username and password.
-  If you click a link and it takes you to weird site, **close the
   window**.
-  If you click a link and it downloads a file to your computer, **do
   not open the file**. It could very easily contain malware that will
   infect your computer.

Be careful where you download software
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

There are many places to get software on the Internet. Some websites
(such as download.com, MajorGeeks, and SoftPedia) serve as "software
mirrors", providing (possibly modified) copies of popular software
downloads. These websites show up high in web search results, so it is
easy to visit them when you are looking for software.

Many mirror websites use ads that try to mislead you into clicking links
for things you do not want. In the section **Install an Ad-blocker**
[CHECK] above we saw one example of this. Here is another:

.. figure:: pix/20-downloads/25-mirrorsites/10-download-cnet.png
   :align: center
   :alt: Misleading links on CNet

Other websites bundle toolbars and other undesirable software along with
the download you want. Often there is legalese on the site claiming that
you can opt-out of the extra software, but you have to look carefully:

.. figure:: pix/20-downloads/25-mirrorsites/15-free-download-ad.png
   :align: center
   :alt: Tricky legalese allowing extra downloads

In addition, some mirror websites provide software that is out of date,
but that is a lesser concern.

Not all mirror websites are equally bad, but it is easy to be misled
when using them. Overall you are best avoiding mirror sites entirely. If
the software is available on Ninite, use that service instead.
Otherwise, look for the official software website:

.. figure:: pix/20-downloads/25-mirrorsites/20-google-search.png
   :align: center
   :alt: Official site in download results

Unfortunately, you have to be careful even in this case, because
sometimes official downloads are bundled with toolbars and other junk.
The Greenshot software in this example does not, but other software
downloads do.

For example, this Java installer changes your homepage and search
provider, unless you remember to uncheck the box below:

.. figure:: pix/20-downloads/25-mirrorsites/25-java-yahoo.png
   :align: center
   :alt: Yahoo search bundled with Java

This download of Adobe Flash Player wants to install a McAfee plugin
along with it:

.. figure:: pix/20-downloads/25-mirrorsites/30-adobe-flash-player.png
   :align: center
   :alt: Tricky Adobe download

And this download of PDFCreator wants to install an "Ad-Aware Web
Companion", as well as changing your search provider to Bing:

.. figure:: pix/20-downloads/25-mirrorsites/35-pdfcreator-bundleware.png
   :align: center
   :alt: Ad-Aware and Bing with PDFCreator

You almost always want to avoid installing this extra software with your
downloads.

Astute readers might notice that we recommend https://ninite.com, which
is also a sort of mirror website. As of this writing, we believe Ninite
does not engage in these kinds of questionable practices.

Once in a while you cannot find legitimate downloads on official sites.
In this case you may want to seek help. People at Computer Recycling can
help you locate legitimate downloads, or you may have a friend who is
both knowledgable about computers and whose judgement you trust.

Avoid toolbars
~~~~~~~~~~~~~~

Many programs come bundled with web browsing toolbars, such as the
Google Toolbar, the Ask Toolbar, the Bing Bar, or Conduit Search. For
the most part, these are bad news. At the very least they track your
movements on the Internet and report your activities to their central
servers. In worse cases they can infect your computer with malicious
software that is very difficult to remove.

.. figure:: pix/20-downloads/30-toolbars/10-toolbars-yuck.png
   :align: center
   :alt: Google Bar and Bing Bar

You do not need toolbars to surf the web effectively. You can use
favorites or bookmarks to visit websites you care about easily. You can
also change your preferred search engine easily. Contact Computer
Recycling if you would like help in doing these things.

Avoid pirated software and key generators
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Some software is expensive. It is very tempting to download
illegally-distributed ("pirated") copies of this software from so-called
"warez" sites or torrents. Sometimes you might be tempted to download
key generating software that will activate demo versions of software
without you having to register or pay for the software.

As a general rule, this is a bad idea! Often the people who are making
illegal software available for download have ulterior motives. Many of
them want to make money, and one way to do so is by including viruses
along with the illegal downloads. People who have no moral compunctions
about redistributing other company's software often have no moral
compunctions about infecting your computer with viruses either.

Often there are free and legal alternatives to the software you are
looking for. These free alternatives may not be as sophisticated as the
commercial software you are tempted to pirate, but often they will get
the job done. One good resource for finding such software is the
Alternatives To site: http://alternativeto.net/

.. figure:: pix/20-downloads/35-pirating/10-alternativeto.png
   :align: center
   :alt: alternativeto site

You can also ask knowledgable friends or volunteers at Computer
Recycling for suggestions.

When deciding upon alternative software, you want to make good choices.
Poorly-written or infrequently-updated software can also make your
computer more vulnerable to viruses. It can be helpful to ask yourself a
few questions:

-  Is the software regularly updated for security issues?
-  Do the software developers take security issues seriously?
-  Is there a sizable community of people who use the software and
   report problems?
-  Does the software work well? Does it do most of what you need?
