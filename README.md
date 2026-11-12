# dial

One small page that opens the phone's own Phone or Messages app for the number in its link:

- `https://jwilk2235.github.io/dial/#tel=+13125550100` asks to call that number
- `https://jwilk2235.github.io/dial/#sms=+13125550100` starts a new text message to it

The number goes after the `#`, which browsers never send to the server, and the page stores nothing. It exists because
links to `tel:` and `sms:` can't leave a sandboxed frame, while an ordinary web link can.
