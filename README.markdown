中文在线文档地址为：https://openresty.org/download/agentzh-nginx-tutorials-zhcn.html

为了防止在线地址以及原github库失效或删除，特此fork做以留存。因此该fork出来的库会将停留在当前fork的日期（2019年11月13日），建议优先前往原地址查看最新版本。

---

This repository holds the source scripts for my Nginx tutorial series
published here:

http://openresty.org/download/agentzh-nginx-tutorials-en.html

Versions in other languages are expected to be maintained by the community.

Pre-generated e-books can be downloaded directly from here:

http://openresty.org/#eBooks

How to generate HTML and other ebook format files on your side:

1. install perl 5.8.1+ into your system (usually it is already
   installed on \*NIX systems.
2. install the Perl CPAN module List::MoreUtils with the
   command:

        sudo cpan List::MoreUtils

3. Install Calibre from here: http://calibre-ebook.com/
4. Build the ebook files \*.mobi and \*.epub
        make
   Note that Gnu make is also required. On most \*BSD systems,
   it's usually required to run "gmake" instead of "make" here.

