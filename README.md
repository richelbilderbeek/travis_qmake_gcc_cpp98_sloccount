# travis_qmake_gcc_cpp98_sloccount

Branch|[![Travis CI logo](TravisCI.png)](https://travis-ci.org)
---|---
master|[![Build Status](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp98_sloccount.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp98_sloccount)
develop|[![Build Status](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp98_sloccount.svg?branch=develop)](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp98_sloccount)

This GitHub is part of [the Travis C++ Tutorial](https://github.com/richelbilderbeek/travis_cpp_tutorial).

The goal of this project is to have a clean Travis CI build, with specs:
 * Build system: `qmake`
 * C++ compiler: `gcc`
 * C++ version: `C++98`
 * Libraries: `STL` only
 * Code coverage: none
 * Source: one single file, `main.cpp`
 * SLOCcount: yes

More complex builds:

 * Use C++11: [travis_qmake_gcc_cpp11_sloccount](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp11_sloccount)
 * Use C++14: [travis_qmake_gcc_cpp14_sloccount](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp14_sloccount)

Les complex builds:

 * No SLOCcount: [travis_qmake_gcc_cpp98](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp98)

## `SLOCcount`

This is the result of this project:

```
Creating filelist for travis_qmake_gcc_cpp98_sloccount
Categorizing files.
Finding a working MD5 command....
Found a working MD5 command.
Computing results.
SLOC	Directory	SLOC-by-Language (Sorted)
267     travis_qmake_gcc_cpp98_sloccount sh=263,cpp=4
Totals grouped by language (dominant language first):
sh:             263 (98.50%)
cpp:              4 (1.50%)
Total Physical Source Lines of Code (SLOC)                = 267
Development Effort Estimate, Person-Years (Person-Months) = 0.05 (0.60)
 (Basic COCOMO model, Person-Months = 2.4 * (KSLOC**1.05))
Schedule Estimate, Years (Months)                         = 0.17 (2.06)
 (Basic COCOMO model, Months = 2.5 * (person-months**0.38))
Estimated Average Number of Developers (Effort/Schedule)  = 0.29
Total Estimated Cost to Develop                           = $ 1,130
 (average salary = $22,611/year, overhead = 1.00).
SLOCCount, Copyright (C) 2001-2004 David A. Wheeler
SLOCCount is Open Source Software/Free Software, licensed under the GNU GPL.
SLOCCount comes with ABSOLUTELY NO WARRANTY, and you are welcome to
redistribute it under certain conditions as specified by the GNU GPL license;
see the documentation for details.
Please credit this data as "generated using David A. Wheeler's 'SLOCCount'."
```

SLOCcount was used for a single-person project with Dutch minimum wages.