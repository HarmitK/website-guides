# Title  #
Install an ad-blocker on Firefox - Privacy Badger

# Summary #
In this guide, you'll learn how to install Privacy Badger on Firefox, a browser add-on devcelopped by the Electronic Frontier Foundation to block malicious ads and trackers.

# Body #
Privacy Badger is a browser add-on to block ads and trackers preventing companies from tracking your online activities. It keeps an up-to-date list of known trackers that it finds through automated tests (not conducted from your computer but by dedicated servers), and regularly pushes the updated list to your browser. This means that as soon as new ad servers are detected (say a new tracking company launch its product or an existing company deploys a new domain) they are blocked for Privacy Badger users. As such, it works well alongside other addons such as [uBlock Origin](/node/3392), which keeps a manually curated list on malicious services. 

Note that Privacy Badger is a project of the Electronic Frontier Foundation and its [privacy policy can be found here][1].

### Installation ###
Like any other add-on, install Privacy Badger by visiting the [Mozilla Firefox Add-ons page][2] and clicking **Add to Firefox** (Fig. 1) and then clicking on **Add** when prompted (Fig. 2).

![Fig. 1: Download Privacy Badger](../../images/Firefox/badger-add.png?raw=true)

![Fig. 2: Add Privacy Badger to Firefox](../../images/Firefox/badger-prompt.png?raw=true)

![Fig. 3: Notification of successful installation](../../images/Firefox/badger-notify.png?raw=true)

Upon successful installation, a notification appears on the top-right corner and the Privacy Badger icon is added to your toolbar (Fig. 3). 

When you visit a website, Privacy Badger automatically blocks malicious trackers and ads, and sets a privacy protection level (green, yellow, or red) which you can manually adjust by clicking the toolbar icon (Fig. 4). To learn more about how Privacy Badger works, click the icon and then click **Learn how Privacy Badger protects your privacy** (Fig. 5), or visit its [official documentation][3]

![Fig. 4: Privacy Badger pop-up interface](../../images/Firefox/badger-test.png?raw=true)

![Fig. 5: Learn more about Privacy Badger](../../images/Firefox/badger-learn.png?raw=true)

[1]: https://www.eff.org/code/privacy/policy

[2]: https://addons.mozilla.org/en-US/firefox/addon/privacy-badger17/

[3]: https://privacybadger.org/
