# 1.5.1
- fix bugs

# 1.5
- fix Activity resource leak
- add fastOAuth

# 1.4.2
- fix bug that AuthorizeActivity may crash if the deprecated "static" version of XiaomiOAuthorize#startGetAccessToken()/startGetOAuth() are called. This bug is instroduced in 1.2 version.

# 1.4.1
- fix vulnerability that AuthorizeActivity can be DDOS-attacked by passing unrecognized Serializable in Intent's extra.

# 1.4
- fix vulnerability that AuthorizeActivity can be DDOS-attacked by passing unrecognized Parceable in Intent's extra.

# 1.3
- fix bug that AuthorizeActivity crashes on MIUI V6.4 and above version, which is intruduced in 1.2 version.

# 1.2
- fix bug that oauth may fail if redirectUrl has upper-case letters, which is introduced in 1.1.
- fix bug that NoTitleBar-themed AuthorizeActivity may crash if network error is met, which is introduced in 1.1.
- add XiaomiOAuthorize#setCustomizedAuthorizeActivityClass.

# 1.1
- fix bug that can't register Mi Account by Gmail in OAuth webview.
- add progress bar in OAuth webview Activity.
- add refresh button in OAuth webview Activity.

# 1.0
Init version
