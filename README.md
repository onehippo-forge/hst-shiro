
# HST - Apache Shiro Integration Support

[Apache Shiro](http://shiro.apache.org/) is a powerful and easy-to-use Java security framework that performs
authentication, authorization, cryptography, and session management.

HST - Apache Shiro Integration Support project provides seamless integration with Apache Shiro for HST-2 SITE applications.

Mainly, HST - Apache Shiro Integration Support project provides the following:

- [Hippo Repository based Realm component](https://onehippo-forge.github.io/hst-shiro/hipporepo-realm.html)
  providing authentication/authorization against Hippo Repository security data store.
- Because Apache Shiro provides a lot of out-of-box security integration solutions such as RDBMS,
  LDAP and CAS authentication, you can take advantage of those with HST-2!

# Documentation 

Documentation is available at [onehippo-forge.github.io/hst-shiro/](https://onehippo-forge.github.io/hst-shiro/)

The documentation is generated by this command:

```bash
$ mvn clean site:site
```

The output is in the docs directory; push it and GitHub Pages will serve the site automatically. 
