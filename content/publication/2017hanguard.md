+++
title = "HanGuard: SDN-driven protection of smart home WiFi devices from malicious mobile apps"
date = "2017-07-18"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Soteris Demetriou", "Nan Zhang", "**Yeonjoon Lee**", "XiaoFeng Wang", "Carl A Gunter", "Xiaoyong Zhou", "Michael Grace"]

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
publication = "Proceedings of the 10th ACM Conference on Security and Privacy in Wireless and Mobile Networks"
publication_short = "In *WISEC*"

# Abstract and optional shortened version.
abstract = "A new development of smart-home systems is to use mobile appsto control IoT devices across a Home Area Network (HAN). As veri!edin our study, those systems tend to rely on the Wi-Fi router toauthenticate other devices. This treatment exposes them to the attackfrom malicious apps, particularly those running on authorizedphones, which the router does not have information to control. Mitigatingthis threat cannot solely rely on IoT manufacturers, whichmay need to change the hardware on the devices to support encryption,increasing the cost of the device, or software developers whowe need to trust to implement security correctly. In this work, wepresent a new technique to control the communication between theIoT devices and their apps in a unified, backward-compatible way.Our approach, called HanGuard, does not require any changes to theIoT devices themselves, the IoT apps or the OS of the participatingphones. HanGuard uses an SDN-like approach to o$er fine-grainedprotection: each phone runs a non-system userspace Monitor appto identify the party that a%empts to access the protected IoT deviceand inform the router through a control plane of its accessdecision; the router enforces the decision on the data plane afterverifying whether the phone should be allowed to talk to the device.We implemented our design over both Android and iOS (> 95% ofmobile OS market share) and a popular router. Our study showsthat HanGuard is both e&cient and effective in practice."
abstract_short = "A new development of smart-home systems is to use mobile apps to control IoT devices across a Home Area Network (HAN). As veri ed in our study, those systems tend to rely on the Wi-Fi router to authenticate other devices. is treatment exposes them to the attack from malicious apps, particularly those running on authorized phones, which the router does not have information to control. Mitigating this threat cannot solely rely on IoT manufacturers, which may need to change the hardware on the devices to support encryption, increasing ..."


# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false


# Links (optional).
url_pdf = "http://seclab.illinois.edu/wp-content/uploads/2017/08/demetriou2017hanguard.pdf"


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
