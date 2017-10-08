# Cpp Con 2017 Notes

Notes, talk summaries, trip reports from Cpp Con 2017

## Intro

Links

* [Github with the slides and other materials](https://github.com/CppCon/CppCon2017)
* [YouTube channel](https://www.youtube.com/user/CppCon/videos)

## Trip Reports

* [Matt Godbolt’s CppCon 2017 Trip Report](https://xania.org/201710/cppcon-2017-trip-report)
* [Ben Deane's CppCon 2017 Trip Report](http://www.elbeno.com/blog/?p=1542)
* [Charles L. Wilcox's Trip Report](http://web.cynd.net/~willo/cppcon-2017-trip-report/)
* [Oliver Smith's Cpp Con 2017 Report](https://kfsone.wordpress.com/2017/10/01/cppcon-2017/)
* [Eva "Bunny" Conti: A Beginner's Guide to CPPCon 2017](https://bunnyladame.blogspot.no/2017/09/a-beginners-guide-to-cppcon-2017.html)
* [Viktor Kirilov - Cpp Con 2017 Trip report](http://onqtam.com/misc/2017-10-04-cppcon-2017-trip-report/)

## Talks

Here's a list of talks with a summary and they key points.

### Bjarne Stroustrup "Learning and Teaching Modern C++"

[CppCon 2017: Bjarne Stroustrup “Learning and Teaching Modern C++” - YouTube](https://www.youtube.com/watch?v=fX2W3nNjJIo)

* "We're all teachers" - this is a good talk, especially for all the people who teach other how to code: but not only bloggers, proffesors... but even for you when you advice/help your collegues from time to time.
* C++ was tought sometimes in a messy way, so we can do better.
* "if you write your own linked list (and use it in production code) you're cool". We cannot teach that way any more. It's just better to use STL.
* Simple example: Why range for loop is better than the old for loop (with i as the index).

### Matt Godbolt “What Has My Compiler Done for Me Lately? Unbolting the Compiler's Lid”

[CppCon 2017: Matt Godbolt “What Has My Compiler Done for Me Lately? Unbolting the Compiler's Lid”](https://www.youtube.com/watch?v=bSkpMdDe4g4)

[PDF slides](https://github.com/CppCon/CppCon2017/blob/master/Keynotes/What%20Has%20My%20Compiler%20Done%20for%20Me%20Lately%20-%20Unbolting%20the%20Compiler's%20Lid/What%20Has%20My%20Compiler%20Done%20for%20Me%20Lately%20-%20Unbolting%20the%20Compiler's%20Lid%20-%20Matt%20Godbolt%20-%20CppCon%202017.pdf)

* Matt's story: why he loves asm and how he started with Compiler Explorer.
* ASM 101, it's really not that hard to read some of the basic code. It might help you to understand your code better.
* Examples of how compilers might be smart. Math stuff mostly, but intresting to see how it's usually best to rely on the code generation.
* Tech stack behind Compiler Explorer

### Herb Sutter "Meta - Thoughts on Generative C++"

[PDF slides](https://github.com/CppCon/CppCon2017/blob/master/Keynotes/Meta%20-%20Thoughts%20on%20Generative%20C%2B%2B/Meta%20-%20Thoughts%20on%20Generative%20C%2B%2B%20-%20Herb%20Sutter%20-%20CppCon%202017.pdf)

[YouTube presentation](https://www.youtube.com/watch?v=4AfRAVcThyA&list=PLHTh1InhhwT6bwIpRk0ZbCA0N2p1taxd6&index=3)

At the beginning of the talk, Herb Sutter smartly “smuggled” very interesting concept of “Consistent comparison” in C++ which details you can find in proposal material [P0515 R0](http://open-std.org/JTC1/SC22/WG21/docs/papers/2017/p0515r0.pdf).

Main part was based on C++ static reflection – many links about this topic you can find on
[Jens Weller site](https://meetingcpp.com/blog/items/reflections-on-the-reflection-proposals.html). Herb shown how C++ can be easily extended using meta-classes that introduce another kind of abstraction. That was announcement of great changes that will come in near future.


## Other

## Contributors

* (author) [Bartek from bfilipek.com](http://www.bfilipek.com)
