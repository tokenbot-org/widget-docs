# TokenBot Widget HTML Documentation

[TokenBot®](htttps://tokenbot.com) is a chat-bot membership platform for traders on Telegram. You can read more about TokenBot here: http://tokenbot.com.

The **TokenBot Subscribe Widget** allows you to display a subscribe button on any external webpage. 

The **TokenBot Subscribe Widget** contains the following functionality:

- Displays the total number of subscribers
- When clicked takes the web browser to the sign up page for the given user

**TokenBot Subscribe Widget**

![Image of Subscribe Widget Screenshot](https://s3.us-east-2.amazonaws.com/assets.tokenbot.com/widget-screenshot_.png)

**Widget IFRAME HTML code**

```html
<iframe scrolling="no" frameborder="0" allowtransparency="true" allowfullscreen="true"
            style="position: static; visibility: visible; width: 300px; height: 30px; background: transparent"
            src='https://tokenbot.com/widget-[light|dark]?u=[MY_TELEGRAM_USERNAME]'></iframe>
```

The **TokenBot Widget** requires the following argument:
 - *Telegram username* - querystring parameter - i.e /widget-light?u=[MY TELEGRAM_USERNAME]
 - *Theme color* - light or dark - i.e. https://tokenbot.com/widget-[light|dark]

 
 Please contact us at team@tokenbot.com for any questions.
