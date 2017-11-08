+++
title = "What's in Your Dongle and Bank Account? Mandatory and Discretionary Protection of Android External Resources."
date = "2015-02-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Soteris Demetriou", "Xiaoyong Zhou", "Muhammad Naveed", "**Yeonjoon Lee**", "Kan Yuan", "XiaoFeng Wang", "Carl A Gunter"]

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
publication = "Network and Distributed System Security (NDSS) Symposium, February 2015"
publication_short = "In *NDSS*"

# Abstract and optional shortened version.
abstract = "The pervasiveness of security-critical external resources (e.g accessories, online services) poses new challenges to Android security. In prior research we revealed that given the BLUETOOTH and BLUETOOTH_ADMIN permissions, a malicious app on an authorized phone gains unfettered access to any Bluetooth device (e.g., Blood Glucose meter, etc.). Here we further show that sensitive text messages from online banking services and social networks (account balance, password reset links, etc.) are completely exposed to any app with either the RECEIVE_SMS or the READ_SMS permission. Similar security risks are present in other channels (Internet, Audio and NFC) extensively used to connect the phone to assorted external devices or services. Fundamentally, the current permission-based Discretionary Access Control (DAC) and SEAndroid-based Mandatory Access Control (MAC) are too coarse-grained to protect those resources: whoever gets the permission to use a channel is automatically allowed to access all resources attached to it. To address this challenge, we present in this paper SEACAT, a new security system for fine-grained, flexible protection on external resources. SEACAT supports both MAC and DAC, and integrates their enforcement mechanisms across the Android middleware and the Linux kernel. It extends SEAndroid for specifying policies on external resources, and also hosts a DAC policy base. Both sets of policies are managed under the same policy engine and Access Vector Cache that support policy checks within the security hooks distributed across the framework and the Linux kernel layers, over different channels. This integrated security model was carefully designed to ensure that misconfigured DAC policies will not affect the enforcement of MAC policies, which manufacturers and system administrators can leverage to define their security rules. In the meantime, a policy management service is offered to the ordinary Android users for setting policies that protect the resources provided by the third party. This service translates simple user selections into SELinux-compatible policies in the background. Our implementation is capable of thwarting all known attacks on external resources at a negligible performance cost."
abstract_short = "The pervasiveness of security-critical external resources (eg accessories, online services) poses new challenges to Android security. In prior research we revealed that given the BLUETOOTH and BLUETOOTH_ADMIN permissions, a malicious app on an authorized phone gains unfettered access to any Bluetooth device (eg, Blood Glucose meter, etc.). Here we further show that sensitive text messages from online banking services and social networks (account balance, password reset links, etc.) are completely exposed to any app ..."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false


# Links (optional).
url_pdf = "http://seclab.illinois.edu/wp-content/uploads/2015/03/Demetriou+15.pdf"


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
