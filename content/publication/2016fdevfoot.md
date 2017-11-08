+++
title = "Following devil's footprints: Cross-platform analysis of potentially harmful libraries on android and ios"
date = "2014-07-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Kai Chen", "Xueqiang Wang", "Yi Chen", "Peng Wang", "**Yeonjoon Lee**", "XiaoFeng Wang", "Bin Ma", "Aohui Wang", "Yingjun Zhang", "Wei Zou"]

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
publication = "Security and Privacy (SP), 2016 IEEE Symposium on"
publication_short = "In *S&P*"

# Abstract and optional shortened version.
abstract = "It is reported recently that legitimate libraries are repackaged for propagating malware. An in-depth analysis of such potentially-harmful libraries (PhaLibs), however, has never been done before, due to the challenges in identifying those libraries whose code can be unavailable online (e.g., removed from the public repositories, spreading underground, etc.). Particularly, for an iOS app, the library it integrates cannot be trivially recovered from its binary code and cannot be analyzed by any publicly available anti-virus (AV) systems. In this paper, we report the first systematic study on PhaLibs across Android and iOS, based upon a key observation that many iOS libraries have Android versions that can potentially be used to understand their behaviors and the relations between the libraries on both sides. To this end, we utilize a methodology that first clusters similar packages from a large number of popular Android apps to identify libraries, and strategically analyze them using AV systems to find PhaLibs. Those libraries are then used to search for their iOS counterparts within Apple apps based upon the invariant features shared cross platforms. On each discovered iOS PhaLib, our approach further identifies its suspicious behaviors that also appear on its Android version and uses the AV system on the Android side to confirm that it is indeed potentially harmful. Running our methodology on 1.3 million Android apps and 140,000 popular iOS apps downloaded from 8 markets, we discovered 117 PhaLibs with 1008 variations on Android and 23 PhaLibs with 706 variations on iOS. Altogether, the Android PhaLibs is found to infect 6.84% of Google Play apps and the iOS libraries are embedded within thousands of iOS apps, 2.94% among those from the official Apple App Store. Looking into the behaviors of the PhaLibs, not only do we discover the recently reported suspicious iOS libraries such as mobiSage, but also their Android counterparts and 6 other back-door libraries never known before. Those libraries are found to contain risky behaviors such as reading from their host apps' keychain, stealthily recording audio and video and even attempting to make phone calls. Our research shows that most Android-side harmful behaviors have been preserved on their corresponding iOS libraries, and further identifies new evidence about libraries repackaging for harmful code propagations on both sides."
abstract_short = "It is reported recently that legitimate libraries are repackaged for propagating malware. An in-depth analysis of such potentially-harmful libraries (PhaLibs), however, has never been done before, due to the challenges in identifying those libraries whose code can be unavailable online (eg, removed from the public repositories, spreading underground, etc.). Particularly, for an iOS app, the library it integrates cannot be trivially recovered from its binary code and cannot be analyzed by any publicly available anti-virus (AV) systems. In ..."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false


# Links (optional).
url_pdf = "https://www.informatics.indiana.edu/xw7/papers/chen2016following.pdf"


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
