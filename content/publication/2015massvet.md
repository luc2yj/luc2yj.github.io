+++
title = "Finding Unknown Malice in 10 Seconds: Mass Vetting for New Threats at the Google-Play Scale"
date = "2015-07-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Kai Chen",
            "Peng Wang",
            "**Yeonjoon Lee**",
            "XiaoFeng Wang",
            "Nan Zhang",
            "Heqing Huang",
            "Wei Zou",
            "Peng Liu"]

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
publication = "24th USENIX Security Symposium"
publication_short = "In *USENIX Security*"

# Abstract and optional shortened version.
abstract = "An app markets vetting process is expected to be scalableand effective. However, todays vetting mechanismsare slow and less capable of catching new threats. Inour research, we found that a more powerful solutioncan be found by exploiting the way Android malware isconstructed and disseminated, which is typically throughrepackaging legitimate apps with similar malicious components.As a result, such attack payloads often stand outfrom those of the same repackaging origin and also showup in the apps not supposed to relate to each other.Based upon this observation, we developed a newtechnique, called MassVet, for vetting apps at a massivescale, without knowing what malware looks likeand how it behaves. Unlike existing detection mechanisms,which often utilize heavyweight program analysistechniques, our approach simply compares a submittedapp with all those already on a market, focusing onthe difference between those sharing a similar UI structure(indicating a possible repackaging relation), and thecommonality among those seemingly unrelated. Oncepublic libraries and other legitimate code reuse are removed,such diff/common program components becomehighly suspicious. In our research, we built this DiffComanalysis on top of an efficient similarity comparisonalgorithm, which maps the salient features of anapps UI structure or a methods control-flow graph toa value for a fast comparison. We implemented MassVetover a stream processing engine and evaluated it nearly1.2 million apps from 33 app markets around the world,the scale of Google Play. Our study shows that the techniquecan vet an app within 10 seconds at a low falsedetection rate. Also, it outperformed all 54 scanners inVirusTotal (NOD32, Symantec, McAfee, etc.) in termsof detection coverage, capturing over a hundred thousandmalicious apps, including over 20 likely zero-daymalware and those installed millions of times. A closelook at these apps brings to light intriguing new observations:e.g., Googles detection strategy and malwareauthors countermoves that cause the mysterious disappearanceand reappearance of some Google Play apps."
abstract_short = "An app market's vetting process is expected to be scalable and effective. However, today's vetting mechanisms are slow and less capable of catching new threats. In our research, we found that a more powerful solution can be found by exploiting the way Android malware is constructed and disseminated, which is typically through repackaging legitimate apps with similar malicious components. As a result, such attack payloads often stand out from those of the same repackaging origin and also show up in the apps not ..."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false


# Links (optional).
url_pdf = "https://www.usenix.org/system/files/conference/usenixsecurity15/sec15-paper-chen-kai.pdf"


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
