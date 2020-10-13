# Title 1 #

- [Title 1](#title-1)
  - [Title 2](#title-2)
    - [Title 3](#title-3)
      - [Title 4](#title-4)
        - [Title 5](#title-5)
          - [Title 6](#title-6)
  - [Ordered List (number)](#ordered-list-number)
  - [Non-ordered List (-/+/*)](#non-ordered-list--)
  - [Nested List (Tab)](#nested-list-tab)
    - [List Notes](#list-notes)
  - [Dividing line line (*/-/_)](#dividing-line-line--_)
    - [\*](#)
    - [Image](#image)
    - [Hyper Linkage](#hyper-linkage)
  - [Code](#code)
  - [Reference](#reference)
  - [Others](#others)

## Title 2 ##

### Title 3 ###

#### Title 4 ####

##### Title 5 #####

###### Title 6 ######

Title have **6** levels in Markdown,  
and leave blank line before/after title line.  
\# and title text have *1* whitespace.

**Bold** text: two \* wrapped;
*Italic* text: one \* wrapped.

Hello, everyone! I am studying markdown...Hope you also like it...  
It is very helpful when writing article in simple and good format...I am studying markdown on a blog, [Learning markdown](https://www.cnblogs.com/nickchen121/p/10821946.html)...
You can also find useful info from [Google Markdown style Guide]...

[Google Markdown style Guide]: https://github.com/google/styleguide/blob/gh-pages/docguide/style.md

## Ordered List (number) ##

1. I have a dream
2. I have two dreams
3. I have many dreams

## Non-ordered List (-/+/*) ##

- I have not a dream
- I have not two dreams
- I have not many dreams

## Nested List (Tab) ##

1. I have a dream
   - No, you have not dream
   - What?!
2. I have two dreams
3. I have many dreams

### List Notes ###

-   for non-ordered list, if list item need break line, please use 3 whitespace after line number, and insert blank line before/after item; else, leave 1 whitespace, and no need blank line
  
1.  for ordered list, if list item need break line, please use 2 whitespace after line, and insert blank line before/after item; else, leave 1 whitespace, and no need blank line

## Dividing line line (*/-/_) ###

### \* ###

***
* * *
************

### Image ###

![Unknown image]()
![Local image](./../img/firefox.png)
![Local image](D:/Workspace/github/MarkdownStudy/img/firefox.png)
![Web image 1](https://www.firefox.com.cn/media/protocol/img/logos/firefox/browser/logo-lg.3d9087ac44e8.png)

### Hyper Linkage ###

I study Markdown via websites [cnBlog], [Google] and [Stack Overflow]

[cnBlog]: https://www.cnblogs.com/
[Google]: https://www.google.com/
[Stack Overflow]: https://stackoverflow.com/

If you want study with me, my email address is <houtong_an@163.com>.

## Code ##

Recently, I am studying asp.net core also...
If you know asp.net core, you must know the meaning of `dotnet build`. Below is a sample code (start with a Tab/ 4 whitespace in blank line):

    dotnet new console
    dotnet build
    dotnet run

```CSharp
    static void Main()
    {
        Console.WriteLine("Hello Markdown!");
    }
```

## Reference ##

> Making IT happen

Our Core Values:
> Challenger Spirit
Please give a demo on this...
> Customer Focus
> Integrity
> Personal Excellence
> Teamwork

## Others ##

==High light==
~~StrikeThrough~~
<u>Underline</u>
This is ^SuperScript^, and this is ~SubScript~
H~2~O, X^2^+Y^2^
<!--This is comments-->
