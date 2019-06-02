#Better_Bot (BetterBlankBot)

A set of utilities and classes to aid in creating FRC robot code.

##How To Use

Add

```
repositories {
    maven {
        url 'https://raw.githubusercontent.com/Team4308/Better_Bot/tree/master/cf/githubistheworst/b_b/'
        credentials(HttpHeaderCredentials) {
            name = "Authorization"
            value = "$TOKEN"
        }
        authentication {
            header(HttpHeaderAuthentication)
        }
    }
}

dependencies {
    compile 'cf.githubistheworst:b_b:0.1.0'
}
```

To your repositories in your `build.gradle`.

If you don't know how to create a github repo token with access to organization repos, dm me on discord `wozeparrot#8603`.