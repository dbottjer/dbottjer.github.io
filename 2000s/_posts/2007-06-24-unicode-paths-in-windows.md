---
layout: post
title: unicode paths in windows
---

something cool i've never heard of. quoted from http://blogs.msdn.com/dougste/ about a path value of `\\?\C:\WEBSites\WWWMyApp\scripts:`

> First of all, what is illegal about this path? Well, nothing, if you are a Unicode Win32 API. As you can read in Naming a File on MSDN, certain Unicode Win32 file handling APIs allow a path to be prefixed with \\?\ which allow paths to be up to 32,000 characters in length among other things. It also tells the operating system to not canonicalize the path by interpreting things such as .. to mean 'go to the parent directory'. Unfortunately not all parts of the System.IO namespace in .NET have yet caught up with this reality and still consider ? in a path to be illegal.
