Tweet has two parts:

- tweet.html.twig, the markup for a tweet
- tweet.less, a stylesheet for styling the tweet partial

v1.4.1 supports
- text tweets
- retweets
- links in the tweet
- attached media (if `images` is "1" or true)
- web intents
- avatar support (if `avatars` is "1" or true)
    
Useage:
- Wrap a group of `.tweet`s in a `.tweets`
- Customize the styles listed between `//<site values>` and `//</site values>`