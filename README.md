# edge-devtools-poc
PoC for a DevTools enabler in MS Edge for Xbox
# Why is this an exploit?
This attack could be leveraged if a exploit is found in the backend of `ntp.msn.com`, so even in its current state it could be considered as a XSS attack. The amount of leverage (since most browsers are heavily sandboxed) in its current state is minimal, so there shouldn't be much worry, yet. Any attacks would neeed social engineering to be effective.<br>
Demo:<br> ![ezgif com-video-to-gif](https://github.com/JamesIsWack/edge-devtools-poc/assets/94473358/e0a0da1f-397b-4de6-86f9-e8b58fe4bed9)<br>
Basic functions such as `alert`, `console.log`, and `console.clear` seem to work using this method. Why this was left in is beyond me.<br>
# Limitations
HTTP GET requests are not supported, so you cannot use external scripts:<br>
![image](https://github.com/JamesIsWack/edge-devtools-poc/assets/94473358/6881ef2b-14fe-4605-8a18-3821c4221138)
