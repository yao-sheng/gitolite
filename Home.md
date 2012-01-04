# Welcome to the gitolite wiki!!

**Gitolite allows you to host Git repositories easily and securely.**

Please start reading [here](http://sitaramc.github.com/gitolite/) to learn about gitolite.

----

**Support**

  * Please **don't** send me messages via github's "issues" system, linkedin comments/discussion, stackoverflow questions, google+ "streams", and any other Web 3.0 "coolness".
  * Please **don't** send me pull requests via github.  Instead, send me an email saying what URL and what branch to pull.  (My reasons are at the bottom of this page).

The main support page for gitolite is [here](http://sitaramc.github.com/gitolite/support.html).  Email addresses and contact info are [here](http://sitaramc.github.com/gitolite/index.html#contact_and_license_)

Support requests that indicate insufficient reading or understanding of the enormous amount of documentation that comes with gitolite will be answered only if time permits.  This applies especially to **ssh issues**.

----

My gpg key (should be available at least from pgp.mit.edu keyserver, probably most others as well):

    pub   4096R/088237A5 2011-10-25
          Key fingerprint = 560A DA64 7542 816F 412E  5891 A442 9085 0882 37A5
    uid                  Sitaram Chamarty (work email) <sitaram@atc.tcs.com>
    uid                  Sitaram Chamarty <sitaramc@gmail.com>
    sub   4096R/8AC76EFB 2011-10-25

----

**Donations**

*Disclaimer: this is my personal opinion and does not necessarily reflect that of my employer.  The disclaimer applies especially strongly to para 3 below*.

I've had people ask me how they can donate to gitolite.  The first part of the answer is that there is no need.  I work for TCS, which is a large IT services firm, and they support my efforts in this and always have.

The second part of the answer is that if you feel the need to donate, please donate to either the [VIM project](http://www.vim.org/sponsor/index.php) or the [Perl Foundation](http://donate.perlfoundation.org/), both of which I consider indispensable to my work.

I have used open source for almost 17 years now, both personally and at work, and until now have never actually given back in any significant way other than evangelism.  Thus the third part of the answer is that you can actually donate to *any* FOSS project (other than projects that use Mono) that you think makes a big difference in your life, and, I will consider myself thanked adequately :-)

----

My reasons for not using the issues system and pull requests:

The issues system does have an email interface, but it is not a substitute for email.  I can't cc anyone else when I want to, for instance (well I can, but any response the original requester then makes using the website will not get cc-d to the person I cc-d).

The pull system forces a --no-ff even if the merge is at the top of my branch and doesn't need one.  It also gives me no chance to fix up minor typos, add any more text to the commit message, etc.  (I can do that afterward, but this forces a "push -f" or a trivial "typofix" commit).