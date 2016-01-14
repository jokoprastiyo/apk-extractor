#APK Extractor
This project is an attempt to develop a publicly available parser which can parse Android's binary XML. AAPT (Android Asset Packaging Tool) encodes/decodes XML resources in Google's own proprietary binary XML format. It's a common believe that this is a generic WBXML format and any WBXML capable parser can parse it. But this is not true.

If you are planning to explore Android's Binary XML, my code base can help you to start and build service on top of it.

Version 1.0- is capable of parsing Android Manifest, XML layouts etc. and converting DEX/ODEX to CLASS, which can be opened by any de-compiler.
Share your feedback on my <a href='http://prasanta-paul.blogspot.in/' target='_blank'>blog</a>. I'm listening :-)

#Usage in Other Projects
apk-manifest-extractor (https://github.com/matthill/apk-manifest-extractor)
aminc (https://github.com/gregko/aminc)

#License
Copyright 2015 Prasanta Paul (http://prasanta-paul.blogspot.in/)

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
