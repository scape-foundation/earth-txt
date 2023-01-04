## robots.txt

contains information and instructions for robots (so it should be read/used by web crawlers, spiders and other kind of bots)

link:   http://www.robotstxt.org
        https://en.wikipedia.org/wiki/Robots_exclusion_standard


## humans.txt

contains useful information to be consumed by humans, according to http://humanstxt.org/
link:   http://humanstxt.org/
https://www.reddit.com/r/webdev/comments/2u4p41/companies_with_humanstxt/


## hackers.txt

should be targeted towards hackers, so it should contain any information the site owner might want to transmit to a hacker, 
as Ze'ev pointed out. I don't think this should be a place for hackers to write anything, 
but rather to get information from the site owner (perhaps on how to report vulnerabilities, as others suggested).
As with humans.txt, there also seems to be a hackers.txt site at h


link:   http://www.hackerstxt.org/


## security.txt

Details and a nifty tool to generate your own security.txt can be found at 
A proposed standard which allows websites to define security policies.

link:   https://securitytxt.org/
        https://github.com/securitytxt/securitytxt.org
        https://github.com/securitytxt/security-txt
        https://securitytxt.io/
        https://github.com/securitytxt/security-txt/tree/master/docs


## licence.txt

License.txt is simply a generic name for any license file. There is no web "standard" or convention for "license.txt" 
files like there is for, say, robots.txt or humans.txt. However, many web "applications" (those written in scripting
languages, for example) will use a "license.txt" file to convey the terms under which the application is distributed 
(common to open source projects especially). This file often resides in the root of an application directory.

As pointed out in the comments, retrieval of the "license.txt" file can give various kinds of clues about the system 
that provides it that may be of use to someone who wishes to exploit the site, even if this information doesn't specifically 
relate to "license.txt." That said, simply having a "license.txt" file doesn't mean your system is vulnerable.

There is no reason to keep this file available (or any non-essential file after setup for that matter) and it should be 
removed to discourage bad behavior and thwart any real exploit attempts.

link:   




https://en.wikipedia.org/wiki/Pretty_Good_Privacy
https://github.com/public/OpenPGP-SDK


References:
https://stackoverflow.com/questions/15358356/what-is-the-use-of-the-hackers-txt-file/15358794#15358794

Contributions from the public are welcome. Refer to the [contribution guidelines](CONTRIBUTING.md) for information on contributing to this project.

