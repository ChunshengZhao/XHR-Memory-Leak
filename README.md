# XHR-Memory-Leak

IE 11.0.9600.19326. When there is a long link XHR request on the page, a memory leak occurs when you click # to navigate. The leak caused by the timer can be ruled out because no leak will occur before the jump #.
A high-performance computer is needed to ensure testing, because I found that on some computers with low performance, even if I don't click the # link, it will leak. But the leaked memory is different from the content after clicking the # link.

![Screenshots](https://github.com/ChunshengZhao/XHR-Memory-Leak/blob/master/screenshot.png)
