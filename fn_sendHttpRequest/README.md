# Extending the Wait-Retry Pattern in Power Query

Microsoft suggests a custom <a href="https://learn.microsoft.com/en-us/power-query/wait-retry">Wait-Retry Pattern</a> to modify the default behavior of the Web.Contents function in Power Query. The solution is concise and elegant, but it is unsuitable for implementing parallel requests batching. Here is an extension of the standard pattern using the so-called "API throttling" technique.
