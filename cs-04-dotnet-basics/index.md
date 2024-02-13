# Let's Learn C# (04) — Basics of .NET


You might have noticed the term ".NET" popping up quite a bit. It's a key part of learning C#, as C# is essentially the go-to language for .NET development. To get started with C#, it's important to grasp what .NET is all about.

## .NET Platform
Think of .NET as a big toolbox that helps you build and run software. When you create apps with C#, they need .NET to work. Over time, different versions of .NET have been developed, like .NET Framework, .NET Core, and .NET Standard.

{{<admonition>}}
If you're on Windows 10, you likely already have .NET Framework 4.5 or a newer version installed.
{{</admonition>}}

## History
To make sense of the various .NET versions, let's take a quick trip through their history.

### .NET Framework
The journey of .NET as well as C# started in 2002 with the .NET Framework (version 1.0). Although Microsoft had plans to make the .NET Framework cross-platform in the distant future, the framework only ran on Windows. Another problem was that the .NET Framework was not backward compatible before version 4.5. That is, an app made in one version would not run in previous versions without modification.

### Mono
.NET Framework only runs on Windows, so what about Linux or Mac users? Can't they use the .NET Framework and C# then?

From this problem, around 2004, a smart programmer named Miguel de Icaza started an open-source project called The Mono Project. The goal of this project was to create an implementation of the .NET Framework that would run on Linux. This effort is really smart because his team was able to create another .NET like .NET Framework for Linux based only on the documentation, without looking at the original source code.

### .NET Core
After Satya Nadella became CEO in 2014, Microsoft changed their business model. They start leaning towards the cloud and realize that the future of the cloud is not Windows, but Linux. So they started building an open-source and cross-platform implementation of the .NET Framework from scratch. As a result, .NET Core was born in 2016.

.NET Core has been completely redesigned by removing many redundant parts of the .NET Framework. It also has no problem with backward compatibility as before.

### .NET Standard
With so many .NETs, it's natural to get confused between them. For example, developers had to rush to share code from one platform to another. Microsoft came up with .NET Standard as a solution in an attempt to eliminate this problem.

It would be better to call the .NET Standard a specification rather than another implementation. Because its job is to specify a set of APIs that will support more than one .NET implementation. Which implementation will be supported can be understood by looking at the version of .NET Standard.

### .NET
Microsoft has been trying to unify all .NET implementations for a long time. This effort finally led to .NET 5 in 2020. .NET 5 is the next version of .NET Core 3.1. In terms of naming, "Core" has been removed and the new name has been changed to ".NET". And the version number has been changed directly from 3 to 5, because doing 4 would have created confusion with .NET Framework version 4.

{{<admonition>}}
The .NET Framework is now considered a legacy platform for Windows, while .NET (without "Framework" or "Core" in the name) is the modern, open-source, cross-platform version.
{{</admonition>}}

### Wrapping Up
That's a brief overview of .NET. Hopefully, it gives you a clearer picture of what .NET is and why it's important for C# development. In the next post, we'll dive into how C# fits into the .NET ecosystem.
