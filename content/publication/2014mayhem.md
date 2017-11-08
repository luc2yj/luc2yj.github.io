+++
title = "Mayhem in the push clouds: Understanding and mitigating security hazards in mobile push-messaging services"
date = "2014-07-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Tongxin Li", "Xiaoyong Zhou", "Luyi Xing", "**Yeonjoon Lee**", "Muhammad Naveed", "XiaoFeng Wang", "Xinhui Han"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "Proceedings of the 2014 ACM SIGSAC Conference on Computer and Communications Security"
publication_short = "In *CCS*"

# Abstract and optional shortened version.
abstract = "Push messaging is among the most important mobile-cloud services, offering critical supports to a wide spectrum of mobile apps. This service needs to coordinate complicated interactions between developer servers and their apps in a large scale, making it error prone. With its importance, little has been done, however, to understand the security risks of the service. In this paper, we report the first security analysis on those push-messaging services, which reveals the pervasiveness of subtle yet significant security flaws in them, affecting billions of mobile users. Through even the most reputable services like Google Cloud Messaging (GCM) and Amazon Device Messaging (ADM), the adversary running carefullycrafted exploits can steal sensitive messages from a target device, stealthily install or uninstall any apps on it, remotely lock out its legitimate user or even completely wipe out her data. This is made possible by the vulnerabilities in those services protection of deviceto-cloud interactions and the communication between their clients and subscriber apps on the same devices. Our study further brings to light questionable practices in those services, including weak cloud-side access control and extensive use of PendingIntent, as well as the impacts of the problems, which cause popular apps or system services like Android Device Manager, Facebook, Google+, Skype, PayPal etc. to leak out sensitive user data or unwittingly act on the adversarys command. To mitigate this threat, we developed a technique that helps the app developers establish end-to-end protection of the communication with their apps, over the vulnerable messaging services they use."
abstract_short = "Push messaging is among the most important mobile-cloud services, offering critical supports to a wide spectrum of mobile apps. This service needs to coordinate complicated interactions between developer servers and their apps in a large scale, making it error prone. With its importance, little has been done, however, to understand the security risks of the service. In this paper, we report the first security analysis on those push- messaging services, which reveals the pervasiveness of subtle yet significant security ..."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false


# Links (optional).
url_pdf = "https://www.informatics.indiana.edu/xw7/papers/li2014mayhem.pdf"


# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++

More detail can easily be written here using *Markdown* and $\rm \LaTeX$ math code.
