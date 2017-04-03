# Entry 2: Twitter Gem

I read through multiple Github tutorials to find out how to install the Twitter gem will no issue. The Twitter gem will basically allow me to run through the already streaming API.

## First Tweet

<img src="../twitterbot-images/tenor.gif">

At first I connected the API key & secret and Token key & secret to my personal Twitter account, then I realized, oh gosh, if I wanted others to see that I actually generated an automated tweet saying "I AM A BOT!!" on a twitter account, it's best that it is not on my personal. So I purposely created a new account and tried to connect my cloud 9 to my other account, which happened to be disabled for some reason. I was so darn frustrated because I kept hovering the same spot for the whole period and trust me, it's stressful to find the smallest error.

```
client = Twitter::REST::Client.new do |config|
  config.consumer_key        = "YOUR_CONSUMER_KEY"
  config.consumer_secret     = "YOUR_CONSUMER_SECRET"
  config.access_token        = "YOUR_ACCESS_TOKEN"
  config.access_token_secret = "YOUR_ACCESS_SECRET"
end
```

## Takeaways
1. Always ask a friend because two pair of eyes are better than one!
2. If you're really irritated by how the code doesn't work, I copied and pasted the older, original code and see my other commits -- hoping to find ANYTHING, literally anything that would help me if I could find a difference in the code.
3. Lastly, I always and will always resort to my best friend, Google :)


[Previous](entry1-intro.md) , [Next]()

[Table of Contents](../README.md)