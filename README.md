# Bugggy Login Form Example

This Flutter project is created to demonstrate keyboards bug of Flutter Windows applications at master branch (2.4.0-1.0.pre.208).

## Problem 1: AltGr Button
Once you try to enter your email address, for example "johndoe@gmail.com", what you will see on the login form is "johndoe@@ggmmaaiill..ccoomm"


## Problem 2: Left Ctrl Button
Same here, either you press LCtrl or AltGr button, your keyboard starts to type twice. You need to press one of these buttons again to fix the problem.



### Flutter Doctor Logs:

[√] Flutter (Channel master, 2.4.0-1.0.pre.208, on Microsoft Windows [Version 10.0.19042.1083], locale en-US)
    • Flutter version 2.4.0-1.0.pre.208 at C:\src\flutter
    • Upstream repository https://github.com/flutter/flutter.git
    • Framework revision d2057d50c4 (3 hours ago), 2021-07-13 11:01:03 -0700
    • Engine revision 07d04041d5
    • Dart version 2.14.0 (build 2.14.0-301.0.dev)

[√] Visual Studio - develop for Windows (Visual Studio Community 2019 16.9.4)
    • Visual Studio at C:\Program Files (x86)\Microsoft Visual Studio\2019\Community
    • Visual Studio Community 2019 version 16.9.31205.134
    • Windows 10 SDK version 10.0.18362.0