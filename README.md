# RedditUserTransfer
Transfers the transferrable components of a reddit user:

1. Saved posts/comments
2. Subscribed subreddits
3. User preferences

You need to add a client/src/config.json as such:

```
{
    "clientId": "TfzbgEd4MNPSlA",
    "clientSecret": "mqMn5AaE93q3eK-ekIlIH_dR6VE",
    "redirectURI": "http://localhost:3000"
}
```

Where the client id and secret are for the Reddit API, and the redirect URI is for the site.
