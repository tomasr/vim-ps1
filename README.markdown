ps1.vim
=======

If you are a Windows PowerShell user who uses Vim or Gvim for editing scripts, 
then this plugin is for you.

It provides nice syntax coloring and indenting for Windows PowerShell (.ps1)
files, and also includes a filetype plugin so Vim can autodetect your PS1 scripts.

Includes contributions by:

* Jared Parsons <jaredp@beanseed.org>
* Heath Stewart <heaths@microsoft.com>
* Michael B. Smith
* Alexander Kostikov

Installation
------------

Copy the included directories into your .vim or vimfiles directory.

Or even better, use pathogen and simply pull it in like this:

    cd ~/.vim/bundle
    git clone https://github.com/PProvost/vim-ps1.git


Comments and Suggestions
------------------------

Please follow, fork or submit issues on [GitHub](https://github.com/PProvost/vim-ps1) and if you
find it useful, please vote for it on [vim.org](http://www.vim.org/scripts/script.php?script_id=1327).

License
-------

    Copyright 2005-2012 Peter Provost
    
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
    
    http://www.apache.org/licenses/LICENSE-2.0
    
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

Version History
---------------

* v2.81 (2012-03-05) Fixed a dumb typo
* v2.8  (2012-03-05) Better number scanning, multiline comments, missing keywords and constants
* v2.7  (2008-09-22) Begin, process & end keywords. Better highlighting of foreach and where
* v2.6  (2007-03-05) Added unary -not operator
* v2.5  (2007-03-03) Updates for here-strings, comment todos, other small cleanups
* v2.4  (2007-03-02) Added elseif keyword
* v2.3  (2007-02-27) Added param keyword
* v2.2  (2007-02-19) Missing keywords
* v2.1  (2006-07-31) Update for renaming
* v2.0  (2005-12-21) Big update from Jared Parsons
* v1.3  (2005-12-20) Updates to syntax elements
* v1.2  (2005-08-13) Fix foreach and while problem
* v1.1 (2005-08-12) Initial release
