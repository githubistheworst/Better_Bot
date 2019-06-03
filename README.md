# Better_Bot (BetterBlankBot)

A set of utilities and classes to aid in creating FRC robot code.

## How To Use

Add

```java
repositories {
    maven {
        url 'https://raw.githubusercontent.com/Team4308/Better_Bot/master/'
        credentials(HttpHeaderCredentials) {
            name = "Authorization"
            value = "Bearer a1a1dfc95e7162e74dbfd5b6f5f0f339fc420447"
        }
        authentication {
            header(HttpHeaderAuthentication)
        }
    }
}

dependencies {
    compile 'cf.githubistheworst.bbbTokenBot:b_b:0.1.2'
}
```

To your repositories in your `build.gradle`.

You may also replace the token with your own token, but I reconmmend you to use the one supplied.

If you don't know how to create a github repo token with access to organization repos, dm me on discord `wozeparrot#8603`.

Also, if you don't know how to use this dm me as well.
