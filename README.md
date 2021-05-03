# Python_practicing
21.05.03(WED)


Hi! This is the first day, I started studying AI python coding in the academy.
Python 3.9.4 (tags/v3.9.4:1f2e308, Apr  6 2021, 13:40:21) [MSC v.1928 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license()" for more information.
>>> abs(7.5)
7.5
>>> abs(-7)
7
>>> a = [5, 6, 2, 3, 8]
>>> a
[5, 6, 2, 3, 8]
>>> type(a)
<class 'list'>
>>> sum(a)
24
>>> min(a)
2
>>> max(a)
8
>>> a.sort()
>>> a
[2, 3, 5, 6, 8]
>>> a.sort(false)
Traceback (most recent call last):
  File "<pyshell#10>", line 1, in <module>
    a.sort(false)
NameError: name 'false' is not defined
>>> a.sort(False)
Traceback (most recent call last):
  File "<pyshell#11>", line 1, in <module>
    a.sort(False)
TypeError: sort() takes no positional arguments
>>> a
[2, 3, 5, 6, 8]
>>> b = ['서울', '대전', '대구', '부산', '인천']
>>> ㅠ
Traceback (most recent call last):
  File "<pyshell#14>", line 1, in <module>
    ㅠ
NameError: name 'ᅲ' is not defined
>>> b'
SyntaxError: EOL while scanning string literal
>>> b
['서울', '대전', '대구', '부산', '인천']
>>> sum(b)
Traceback (most recent call last):
  File "<pyshell#17>", line 1, in <module>
    sum(b)
TypeError: unsupported operand type(s) for +: 'int' and 'str'
>>> min(a)
2
>>> b.sort()
>>> b
['대구', '대전', '부산', '서울', '인천']
>>> ['대구', '대전', '부산', '서울', '인천']
['대구', '대전', '부산', '서울', '인천']
>>> import keyword
>>> keyword.kwlist
['False', 'None', 'True', '__peg_parser__', 'and', 'as', 'assert', 'async', 'await', 'break', 'class', 'continue', 'def', 'del', 'elif', 'else', 'except', 'finally', 'for', 'from', 'global', 'if', 'import', 'in', 'is', 'lambda', 'nonlocal', 'not', 'or', 'pass', 'raise', 'return', 'try', 'while', 'with', 'yield']
>>> 3==3
True
>>> 3 !=2
True
>>> 3 !=3
False
>>> a = [5, 6, 2, 4, 1]
>>> b = a.copy()
>>> a
[5, 6, 2, 4, 1]
>>> b
[5, 6, 2, 4, 1]
>>> a, b = b, a
>>> a
[5, 6, 2, 4, 1]
>>> b
[5, 6, 2, 4, 1]
>>> 4 is a
False
>>> 4 ina
SyntaxError: invalid syntax
>>> 4 in a
True
>>> l in a
Traceback (most recent call last):
  File "<pyshell#37>", line 1, in <module>
    l in a
NameError: name 'l' is not defined
>>> 1 in a
True
>>> 9 in a
False
>>> dir(__builtins__)
['ArithmeticError', 'AssertionError', 'AttributeError', 'BaseException', 'BlockingIOError', 'BrokenPipeError', 'BufferError', 'BytesWarning', 'ChildProcessError', 'ConnectionAbortedError', 'ConnectionError', 'ConnectionRefusedError', 'ConnectionResetError', 'DeprecationWarning', 'EOFError', 'Ellipsis', 'EnvironmentError', 'Exception', 'False', 'FileExistsError', 'FileNotFoundError', 'FloatingPointError', 'FutureWarning', 'GeneratorExit', 'IOError', 'ImportError', 'ImportWarning', 'IndentationError', 'IndexError', 'InterruptedError', 'IsADirectoryError', 'KeyError', 'KeyboardInterrupt', 'LookupError', 'MemoryError', 'ModuleNotFoundError', 'NameError', 'None', 'NotADirectoryError', 'NotImplemented', 'NotImplementedError', 'OSError', 'OverflowError', 'PendingDeprecationWarning', 'PermissionError', 'ProcessLookupError', 'RecursionError', 'ReferenceError', 'ResourceWarning', 'RuntimeError', 'RuntimeWarning', 'StopAsyncIteration', 'StopIteration', 'SyntaxError', 'SyntaxWarning', 'SystemError', 'SystemExit', 'TabError', 'TimeoutError', 'True', 'TypeError', 'UnboundLocalError', 'UnicodeDecodeError', 'UnicodeEncodeError', 'UnicodeError', 'UnicodeTranslateError', 'UnicodeWarning', 'UserWarning', 'ValueError', 'Warning', 'WindowsError', 'ZeroDivisionError', '_', '__build_class__', '__debug__', '__doc__', '__import__', '__loader__', '__name__', '__package__', '__spec__', 'abs', 'all', 'any', 'ascii', 'bin', 'bool', 'breakpoint', 'bytearray', 'bytes', 'callable', 'chr', 'classmethod', 'compile', 'complex', 'copyright', 'credits', 'delattr', 'dict', 'dir', 'divmod', 'enumerate', 'eval', 'exec', 'exit', 'filter', 'float', 'format', 'frozenset', 'getattr', 'globals', 'hasattr', 'hash', 'help', 'hex', 'id', 'input', 'int', 'isinstance', 'issubclass', 'iter', 'len', 'license', 'list', 'locals', 'map', 'max', 'memoryview', 'min', 'next', 'object', 'oct', 'open', 'ord', 'pow', 'print', 'property', 'quit', 'range', 'repr', 'reversed', 'round', 'set', 'setattr', 'slice', 'sorted', 'staticmethod', 'str', 'sum', 'super', 'tuple', 'type', 'vars', 'zip']
>>> help()

Welcome to Python 3.9's help utility!

If this is your first time using Python, you should definitely check out
the tutorial on the Internet at https://docs.python.org/3.9/tutorial/.

Enter the name of any module, keyword, or topic to get help on writing
Python programs and using Python modules.  To quit this help utility and
return to the interpreter, just type "quit".

To get a list of available modules, keywords, symbols, or topics, type
"modules", "keywords", "symbols", or "topics".  Each module also comes
with a one-line summary of what it does; to list the modules whose name
or summary contain a given string such as "spam", type "modules spam".

help> help(1,attribute)
No Python documentation found for 'help(1,attribute)'.
Use help() to get the interactive help utility.
Use help(str) for help on the str class.

help> help()
No Python documentation found for 'help()'.
Use help() to get the interactive help utility.
Use help(str) for help on the str class.

help> 

You are now leaving help and returning to the Python interpreter.
If you want to ask for help on a particular object directly from the
interpreter, you can type "help(object)".  Executing "help('string')"
has the same effect as typing a particular string at the help> prompt.
>>> 
>>> 
>>> 
>>> help
Type help() for interactive help, or help(object) for help about object.
>>> keywords
Traceback (most recent call last):
  File "<pyshell#46>", line 1, in <module>
    keywords
NameError: name 'keywords' is not defined
>>> help()

Welcome to Python 3.9's help utility!

If this is your first time using Python, you should definitely check out
the tutorial on the Internet at https://docs.python.org/3.9/tutorial/.

Enter the name of any module, keyword, or topic to get help on writing
Python programs and using Python modules.  To quit this help utility and
return to the interpreter, just type "quit".

To get a list of available modules, keywords, symbols, or topics, type
"modules", "keywords", "symbols", or "topics".  Each module also comes
with a one-line summary of what it does; to list the modules whose name
or summary contain a given string such as "spam", type "modules spam".

help> kewords
No Python documentation found for 'kewords'.
Use help() to get the interactive help utility.
Use help(str) for help on the str class.

help> ekywords
No Python documentation found for 'ekywords'.
Use help() to get the interactive help utility.
Use help(str) for help on the str class.

help> keywords

Here is a list of the Python keywords.  Enter any keyword to get more help.

False               break               for                 not
None                class               from                or
True                continue            global              pass
__peg_parser__      def                 if                  raise
and                 del                 import              return
as                  elif                in                  try
assert              else                is                  while
async               except              lambda              with
await               finally             nonlocal            yield

help> symbols

Here is a list of the punctuation symbols which Python assigns special meaning
to. Enter any symbol to get more help.

!=                  +                   <=                  __
"                   +=                  <>                  `
"""                 ,                   ==                  b"
%                   -                   >                   b'
%=                  -=                  >=                  f"
&                   .                   >>                  f'
&=                  ...                 >>=                 j
'                   /                   @                   r"
'''                 //                  J                   r'
(                   //=                 [                   u"
)                   /=                  \                   u'
*                   :                   ]                   |
**                  <                   ^                   |=
**=                 <<                  ^=                  ~
*=                  <<=                 _                   

help> modules

Please wait a moment while I gather a list of all available modules...


Warning (from warnings module):
  File "C:\Users\CPB06GameN\AppData\Local\Programs\Python\Python39\lib\site-packages\setuptools\distutils_patch.py", line 25
    warnings.warn(
UserWarning: Distutils was imported before Setuptools. This usage is discouraged and may exhibit undesirable behaviors or errors. Please use Setuptools' objects directly or at least import Setuptools first.
__future__          argparse            heapq               runscript
__main__            array               help                sched
_abc                ast                 help_about          scrolledlist
_aix_support        asynchat            history             search
_ast                asyncio             hmac                searchbase
_asyncio            asyncore            html                searchengine
_bisect             atexit              http                secrets
_blake2             audioop             hyperparser         select
_bootlocale         autocomplete        idle                selectors
_bootsubprocess     autocomplete_w      idle_test           setuptools
_bz2                autoexpand          idlelib             shelve
_codecs             base64              imaplib             shlex
_codecs_cn          bdb                 imghdr              shutil
_codecs_hk          binascii            imp                 sidebar
_codecs_iso2022     binhex              importlib           signal
_codecs_jp          bisect              inspect             site
_codecs_kr          browser             io                  smtpd
_codecs_tw          builtins            iomenu              smtplib
_collections        bz2                 ipaddress           sndhdr
_collections_abc    cProfile            itertools           socket
_compat_pickle      calendar            json                socketserver
_compression        calltip             keyword             sqlite3
_contextvars        calltip_w           lib2to3             squeezer
_csv                cgi                 linecache           sre_compile
_ctypes             cgitb               locale              sre_constants
_ctypes_test        chunk               logging             sre_parse
_datetime           cmath               lzma                ssl
_decimal            cmd                 macosx              stackviewer
_elementtree        code                mailbox             stat
_functools          codecontext         mailcap             statistics
_hashlib            codecs              mainmenu            statusbar
_heapq              codeop              marshal             string
_imp                collections         math                stringprep
_io                 colorizer           mimetypes           struct
_json               colorsys            mmap                subprocess
_locale             compileall          modulefinder        sunau
_lsprof             concurrent          msilib              symbol
_lzma               config              msvcrt              symtable
_markupbase         config_key          multicall           sys
_md5                configdialog        multiprocessing     sysconfig
_msi                configparser        netrc               tabnanny
_multibytecodec     contextlib          nntplib             tarfile
_multiprocessing    contextvars         nt                  telnetlib
_opcode             copy                ntpath              tempfile
_operator           copyreg             nturl2path          test
_osx_support        crypt               numbers             textview
_overlapped         csv                 opcode              textwrap
_peg_parser         ctypes              operator            this
_pickle             curses              optparse            threading
_py_abc             dataclasses         os                  time
_pydecimal          datetime            outwin              timeit
_pyio               dbm                 parenmatch          tkinter
_queue              debugger            parser              token
_random             debugger_r          pathbrowser         tokenize
_sha1               debugobj            pathlib             tooltip
_sha256             debugobj_r          pdb                 trace
_sha3               decimal             percolator          traceback
_sha512             delegator           pickle              tracemalloc
_signal             difflib             pickletools         tree
_sitebuiltins       dis                 pip                 tty
_socket             distutils           pipes               turtle
_sqlite3            doctest             pkg_resources       turtledemo
_sre                dynoption           pkgutil             types
_ssl                easy_install        platform            typing
_stat               editor              plistlib            undo
_statistics         email               poplib              unicodedata
_string             encodings           posixpath           unittest
_strptime           ensurepip           pprint              urllib
_struct             enum                profile             uu
_symtable           errno               pstats              uuid
_testbuffer         faulthandler        pty                 venv
_testcapi           filecmp             py_compile          warnings
_testconsole        fileinput           pyclbr              wave
_testimportmultiple filelist            pydoc               weakref
_testinternalcapi   fnmatch             pydoc_data          webbrowser
_testmultiphase     format              pyexpat             window
_thread             formatter           pyparse             winreg
_threading_local    fractions           pyshell             winsound
_tkinter            ftplib              query               wsgiref
_tracemalloc        functools           queue               xdrlib
_uuid               gc                  quopri              xml
_warnings           genericpath         random              xmlrpc
_weakref            getopt              re                  xxsubtype
_weakrefset         getpass             redirector          zipapp
_winapi             gettext             replace             zipfile
_xxsubinterpreters  glob                reprlib             zipimport
_zoneinfo           graphlib            rlcompleter         zlib
abc                 grep                rpc                 zoneinfo
aifc                gzip                run                 zoomheight
antigravity         hashlib             runpy               zzdummy

Enter any module name to get more help.  Or, type "modules spam" to search
for modules whose name or summary contain the string "spam".

help> topics

Here is a list of available topics.  Enter any topic name to get more help.

ASSERTION           DELETION            LOOPING             SHIFTING
ASSIGNMENT          DICTIONARIES        MAPPINGMETHODS      SLICINGS
ATTRIBUTEMETHODS    DICTIONARYLITERALS  MAPPINGS            SPECIALATTRIBUTES
ATTRIBUTES          DYNAMICFEATURES     METHODS             SPECIALIDENTIFIERS
AUGMENTEDASSIGNMENT ELLIPSIS            MODULES             SPECIALMETHODS
BASICMETHODS        EXCEPTIONS          NAMESPACES          STRINGMETHODS
BINARY              EXECUTION           NONE                STRINGS
BITWISE             EXPRESSIONS         NUMBERMETHODS       SUBSCRIPTS
BOOLEAN             FLOAT               NUMBERS             TRACEBACKS
CALLABLEMETHODS     FORMATTING          OBJECTS             TRUTHVALUE
CALLS               FRAMEOBJECTS        OPERATORS           TUPLELITERALS
CLASSES             FRAMES              PACKAGES            TUPLES
CODEOBJECTS         FUNCTIONS           POWER               TYPEOBJECTS
COMPARISON          IDENTIFIERS         PRECEDENCE          TYPES
COMPLEX             IMPORTING           PRIVATENAMES        UNARY
CONDITIONAL         INTEGER             RETURNING           UNICODE
CONTEXTMANAGERS     LISTLITERALS        SCOPING             
CONVERSIONS         LISTS               SEQUENCEMETHODS     
DEBUGGING           LITERALS            SEQUENCES           

help> assertion
No Python documentation found for 'assertion'.
Use help() to get the interactive help utility.
Use help(str) for help on the str class.

help> modules

Please wait a moment while I gather a list of all available modules...

__future__          argparse            heapq               runscript
__main__            array               help                sched
_abc                ast                 help_about          scrolledlist
_aix_support        asynchat            history             search
_ast                asyncio             hmac                searchbase
_asyncio            asyncore            html                searchengine
_bisect             atexit              http                secrets
_blake2             audioop             hyperparser         select
_bootlocale         autocomplete        idle                selectors
_bootsubprocess     autocomplete_w      idle_test           setuptools
_bz2                autoexpand          idlelib             shelve
_codecs             base64              imaplib             shlex
_codecs_cn          bdb                 imghdr              shutil
_codecs_hk          binascii            imp                 sidebar
_codecs_iso2022     binhex              importlib           signal
_codecs_jp          bisect              inspect             site
_codecs_kr          browser             io                  smtpd
_codecs_tw          builtins            iomenu              smtplib
_collections        bz2                 ipaddress           sndhdr
_collections_abc    cProfile            itertools           socket
_compat_pickle      calendar            json                socketserver
_compression        calltip             keyword             sqlite3
_contextvars        calltip_w           lib2to3             squeezer
_csv                cgi                 linecache           sre_compile
_ctypes             cgitb               locale              sre_constants
_ctypes_test        chunk               logging             sre_parse
_datetime           cmath               lzma                ssl
_decimal            cmd                 macosx              stackviewer
_elementtree        code                mailbox             stat
_functools          codecontext         mailcap             statistics
_hashlib            codecs              mainmenu            statusbar
_heapq              codeop              marshal             string
_imp                collections         math                stringprep
_io                 colorizer           mimetypes           struct
_json               colorsys            mmap                subprocess
_locale             compileall          modulefinder        sunau
_lsprof             concurrent          msilib              symbol
_lzma               config              msvcrt              symtable
_markupbase         config_key          multicall           sys
_md5                configdialog        multiprocessing     sysconfig
_msi                configparser        netrc               tabnanny
_multibytecodec     contextlib          nntplib             tarfile
_multiprocessing    contextvars         nt                  telnetlib
_opcode             copy                ntpath              tempfile
_operator           copyreg             nturl2path          test
_osx_support        crypt               numbers             textview
_overlapped         csv                 opcode              textwrap
_peg_parser         ctypes              operator            this
_pickle             curses              optparse            threading
_py_abc             dataclasses         os                  time
_pydecimal          datetime            outwin              timeit
_pyio               dbm                 parenmatch          tkinter
_queue              debugger            parser              token
_random             debugger_r          pathbrowser         tokenize
_sha1               debugobj            pathlib             tooltip
_sha256             debugobj_r          pdb                 trace
_sha3               decimal             percolator          traceback
_sha512             delegator           pickle              tracemalloc
_signal             difflib             pickletools         tree
_sitebuiltins       dis                 pip                 tty
_socket             distutils           pipes               turtle
_sqlite3            doctest             pkg_resources       turtledemo
_sre                dynoption           pkgutil             types
_ssl                easy_install        platform            typing
_stat               editor              plistlib            undo
_statistics         email               poplib              unicodedata
_string             encodings           posixpath           unittest
_strptime           ensurepip           pprint              urllib
_struct             enum                profile             uu
_symtable           errno               pstats              uuid
_testbuffer         faulthandler        pty                 venv
_testcapi           filecmp             py_compile          warnings
_testconsole        fileinput           pyclbr              wave
_testimportmultiple filelist            pydoc               weakref
_testinternalcapi   fnmatch             pydoc_data          webbrowser
_testmultiphase     format              pyexpat             window
_thread             formatter           pyparse             winreg
_threading_local    fractions           pyshell             winsound
_tkinter            ftplib              query               wsgiref
_tracemalloc        functools           queue               xdrlib
_uuid               gc                  quopri              xml
_warnings           genericpath         random              xmlrpc
_weakref            getopt              re                  xxsubtype
_weakrefset         getpass             redirector          zipapp
_winapi             gettext             replace             zipfile
_xxsubinterpreters  glob                reprlib             zipimport
_zoneinfo           graphlib            rlcompleter         zlib
abc                 grep                rpc                 zoneinfo
aifc                gzip                run                 zoomheight
antigravity         hashlib             runpy               zzdummy

Enter any module name to get more help.  Or, type "modules spam" to search
for modules whose name or summary contain the string "spam".

help> assumption
No Python documentation found for 'assumption'.
Use help() to get the interactive help utility.
Use help(str) for help on the str class.

help> glob
Help on module glob:

NAME
    glob - Filename globbing utility.

MODULE REFERENCE
    https://docs.python.org/3.9/library/glob
    
    The following documentation is automatically generated from the Python
    source files.  It may be incomplete, incorrect or include features that
    are considered implementation detail and may vary between Python
    implementations.  When in doubt, consult the module reference at the
    location listed above.

FUNCTIONS
    escape(pathname)
        Escape all special characters.
    
    glob(pathname, *, recursive=False)
        Return a list of paths matching a pathname pattern.
        
        The pattern may contain simple shell-style wildcards a la
        fnmatch. However, unlike fnmatch, filenames starting with a
        dot are special cases that are not matched by '*' and '?'
        patterns.
        
        If recursive is true, the pattern '**' will match any files and
        zero or more directories and subdirectories.
    
    iglob(pathname, *, recursive=False)
        Return an iterator which yields the paths matching a pathname pattern.
        
        The pattern may contain simple shell-style wildcards a la
        fnmatch. However, unlike fnmatch, filenames starting with a
        dot are special cases that are not matched by '*' and '?'
        patterns.
        
        If recursive is true, the pattern '**' will match any files and
        zero or more directories and subdirectories.

DATA
    __all__ = ['glob', 'iglob', 'escape']

FILE
    c:\users\cpb06gamen\appdata\local\programs\python\python39\lib\glob.py


help> yo
No Python documentation found for 'yo'.
Use help() to get the interactive help utility.
Use help(str) for help on the str class.

help> yes
No Python documentation found for 'yes'.
Use help() to get the interactive help utility.
Use help(str) for help on the str class.

help> nice
No Python documentation found for 'nice'.
Use help() to get the interactive help utility.
Use help(str) for help on the str class.

help> nike
No Python documentation found for 'nike'.
Use help() to get the interactive help utility.
Use help(str) for help on the str class.

help> import

help> copy

help> paste
No Python documentation found for 'paste'.
Use help() to get the interactive help utility.
Use help(str) for help on the str class.

help> cmatyh
No Python documentation found for 'cmatyh'.
Use help() to get the interactive help utility.
Use help(str) for help on the str class.

help> matplotlibe
No Python documentation found for 'matplotlibe'.
Use help() to get the interactive help utility.
Use help(str) for help on the str class.

help> matpltlib
No Python documentation found for 'matpltlib'.
Use help() to get the interactive help utility.
Use help(str) for help on the str class.

help> moduels
No Python documentation found for 'moduels'.
Use help() to get the interactive help utility.
Use help(str) for help on the str class.

help> modules

Please wait a moment while I gather a list of all available modules...

__future__          argparse            heapq               runscript
__main__            array               help                sched
_abc                ast                 help_about          scrolledlist
_aix_support        asynchat            history             search
_ast                asyncio             hmac                searchbase
_asyncio            asyncore            html                searchengine
_bisect             atexit              http                secrets
_blake2             audioop             hyperparser         select
_bootlocale         autocomplete        idle                selectors
_bootsubprocess     autocomplete_w      idle_test           setuptools
_bz2                autoexpand          idlelib             shelve
_codecs             base64              imaplib             shlex
_codecs_cn          bdb                 imghdr              shutil
_codecs_hk          binascii            imp                 sidebar
_codecs_iso2022     binhex              importlib           signal
_codecs_jp          bisect              inspect             site
_codecs_kr          browser             io                  smtpd
_codecs_tw          builtins            iomenu              smtplib
_collections        bz2                 ipaddress           sndhdr
_collections_abc    cProfile            itertools           socket
_compat_pickle      calendar            json                socketserver
_compression        calltip             keyword             sqlite3
_contextvars        calltip_w           lib2to3             squeezer
_csv                cgi                 linecache           sre_compile
_ctypes             cgitb               locale              sre_constants
_ctypes_test        chunk               logging             sre_parse
_datetime           cmath               lzma                ssl
_decimal            cmd                 macosx              stackviewer
_elementtree        code                mailbox             stat
_functools          codecontext         mailcap             statistics
_hashlib            codecs              mainmenu            statusbar
_heapq              codeop              marshal             string
_imp                collections         math                stringprep
_io                 colorizer           mimetypes           struct
_json               colorsys            mmap                subprocess
_locale             compileall          modulefinder        sunau
_lsprof             concurrent          msilib              symbol
_lzma               config              msvcrt              symtable
_markupbase         config_key          multicall           sys
_md5                configdialog        multiprocessing     sysconfig
_msi                configparser        netrc               tabnanny
_multibytecodec     contextlib          nntplib             tarfile
_multiprocessing    contextvars         nt                  telnetlib
_opcode             copy                ntpath              tempfile
_operator           copyreg             nturl2path          test
_osx_support        crypt               numbers             textview
_overlapped         csv                 opcode              textwrap
_peg_parser         ctypes              operator            this
_pickle             curses              optparse            threading
_py_abc             dataclasses         os                  time
_pydecimal          datetime            outwin              timeit
_pyio               dbm                 parenmatch          tkinter
_queue              debugger            parser              token
_random             debugger_r          pathbrowser         tokenize
_sha1               debugobj            pathlib             tooltip
_sha256             debugobj_r          pdb                 trace
_sha3               decimal             percolator          traceback
_sha512             delegator           pickle              tracemalloc
_signal             difflib             pickletools         tree
_sitebuiltins       dis                 pip                 tty
_socket             distutils           pipes               turtle
_sqlite3            doctest             pkg_resources       turtledemo
_sre                dynoption           pkgutil             types
_ssl                easy_install        platform            typing
_stat               editor              plistlib            undo
_statistics         email               poplib              unicodedata
_string             encodings           posixpath           unittest
_strptime           ensurepip           pprint              urllib
_struct             enum                profile             uu
_symtable           errno               pstats              uuid
_testbuffer         faulthandler        pty                 venv
_testcapi           filecmp             py_compile          warnings
_testconsole        fileinput           pyclbr              wave
_testimportmultiple filelist            pydoc               weakref
_testinternalcapi   fnmatch             pydoc_data          webbrowser
_testmultiphase     format              pyexpat             window
_thread             formatter           pyparse             winreg
_threading_local    fractions           pyshell             winsound
_tkinter            ftplib              query               wsgiref
_tracemalloc        functools           queue               xdrlib
_uuid               gc                  quopri              xml
_warnings           genericpath         random              xmlrpc
_weakref            getopt              re                  xxsubtype
_weakrefset         getpass             redirector          zipapp
_winapi             gettext             replace             zipfile
_xxsubinterpreters  glob                reprlib             zipimport
_zoneinfo           graphlib            rlcompleter         zlib
abc                 grep                rpc                 zoneinfo
aifc                gzip                run                 zoomheight
antigravity         hashlib             runpy               zzdummy

Enter any module name to get more help.  Or, type "modules spam" to search
for modules whose name or summary contain the string "spam".

help> 

You are now leaving help and returning to the Python interpreter.
If you want to ask for help on a particular object directly from the
interpreter, you can type "help(object)".  Executing "help('string')"
has the same effect as typing a particular string at the help> prompt.
>>> 
>>> help(int)
Help on class int in module builtins:

class int(object)
 |  int([x]) -> integer
 |  int(x, base=10) -> integer
 |  
 |  Convert a number or string to an integer, or return 0 if no arguments
 |  are given.  If x is a number, return x.__int__().  For floating point
 |  numbers, this truncates towards zero.
 |  
 |  If x is not a number or if base is given, then x must be a string,
 |  bytes, or bytearray instance representing an integer literal in the
 |  given base.  The literal can be preceded by '+' or '-' and be surrounded
 |  by whitespace.  The base defaults to 10.  Valid bases are 0 and 2-36.
 |  Base 0 means to interpret the base from the string as an integer literal.
 |  >>> int('0b100', base=0)
 |  4
 |  
 |  Built-in subclasses:
 |      bool
 |  
 |  Methods defined here:
 |  
 |  __abs__(self, /)
 |      abs(self)
 |  
 |  __add__(self, value, /)
 |      Return self+value.
 |  
 |  __and__(self, value, /)
 |      Return self&value.
 |  
 |  __bool__(self, /)
 |      self != 0
 |  
 |  __ceil__(...)
 |      Ceiling of an Integral returns itself.
 |  
 |  __divmod__(self, value, /)
 |      Return divmod(self, value).
 |  
 |  __eq__(self, value, /)
 |      Return self==value.
 |  
 |  __float__(self, /)
 |      float(self)
 |  
 |  __floor__(...)
 |      Flooring an Integral returns itself.
 |  
 |  __floordiv__(self, value, /)
 |      Return self//value.
 |  
 |  __format__(self, format_spec, /)
 |      Default object formatter.
 |  
 |  __ge__(self, value, /)
 |      Return self>=value.
 |  
 |  __getattribute__(self, name, /)
 |      Return getattr(self, name).
 |  
 |  __getnewargs__(self, /)
 |  
 |  __gt__(self, value, /)
 |      Return self>value.
 |  
 |  __hash__(self, /)
 |      Return hash(self).
 |  
 |  __index__(self, /)
 |      Return self converted to an integer, if self is suitable for use as an index into a list.
 |  
 |  __int__(self, /)
 |      int(self)
 |  
 |  __invert__(self, /)
 |      ~self
 |  
 |  __le__(self, value, /)
 |      Return self<=value.
 |  
 |  __lshift__(self, value, /)
 |      Return self<<value.
 |  
 |  __lt__(self, value, /)
 |      Return self<value.
 |  
 |  __mod__(self, value, /)
 |      Return self%value.
 |  
 |  __mul__(self, value, /)
 |      Return self*value.
 |  
 |  __ne__(self, value, /)
 |      Return self!=value.
 |  
 |  __neg__(self, /)
 |      -self
 |  
 |  __or__(self, value, /)
 |      Return self|value.
 |  
 |  __pos__(self, /)
 |      +self
 |  
 |  __pow__(self, value, mod=None, /)
 |      Return pow(self, value, mod).
 |  
 |  __radd__(self, value, /)
 |      Return value+self.
 |  
 |  __rand__(self, value, /)
 |      Return value&self.
 |  
 |  __rdivmod__(self, value, /)
 |      Return divmod(value, self).
 |  
 |  __repr__(self, /)
 |      Return repr(self).
 |  
 |  __rfloordiv__(self, value, /)
 |      Return value//self.
 |  
 |  __rlshift__(self, value, /)
 |      Return value<<self.
 |  
 |  __rmod__(self, value, /)
 |      Return value%self.
 |  
 |  __rmul__(self, value, /)
 |      Return value*self.
 |  
 |  __ror__(self, value, /)
 |      Return value|self.
 |  
 |  __round__(...)
 |      Rounding an Integral returns itself.
 |      Rounding with an ndigits argument also returns an integer.
 |  
 |  __rpow__(self, value, mod=None, /)
 |      Return pow(value, self, mod).
 |  
 |  __rrshift__(self, value, /)
 |      Return value>>self.
 |  
 |  __rshift__(self, value, /)
 |      Return self>>value.
 |  
 |  __rsub__(self, value, /)
 |      Return value-self.
 |  
 |  __rtruediv__(self, value, /)
 |      Return value/self.
 |  
 |  __rxor__(self, value, /)
 |      Return value^self.
 |  
 |  __sizeof__(self, /)
 |      Returns size in memory, in bytes.
 |  
 |  __sub__(self, value, /)
 |      Return self-value.
 |  
 |  __truediv__(self, value, /)
 |      Return self/value.
 |  
 |  __trunc__(...)
 |      Truncating an Integral returns itself.
 |  
 |  __xor__(self, value, /)
 |      Return self^value.
 |  
 |  as_integer_ratio(self, /)
 |      Return integer ratio.
 |      
 |      Return a pair of integers, whose ratio is exactly equal to the original int
 |      and with a positive denominator.
 |      
 |      >>> (10).as_integer_ratio()
 |      (10, 1)
 |      >>> (-10).as_integer_ratio()
 |      (-10, 1)
 |      >>> (0).as_integer_ratio()
 |      (0, 1)
 |  
 |  bit_length(self, /)
 |      Number of bits necessary to represent self in binary.
 |      
 |      >>> bin(37)
 |      '0b100101'
 |      >>> (37).bit_length()
 |      6
 |  
 |  conjugate(...)
 |      Returns self, the complex conjugate of any int.
 |  
 |  to_bytes(self, /, length, byteorder, *, signed=False)
 |      Return an array of bytes representing an integer.
 |      
 |      length
 |        Length of bytes object to use.  An OverflowError is raised if the
 |        integer is not representable with the given number of bytes.
 |      byteorder
 |        The byte order used to represent the integer.  If byteorder is 'big',
 |        the most significant byte is at the beginning of the byte array.  If
 |        byteorder is 'little', the most significant byte is at the end of the
 |        byte array.  To request the native byte order of the host system, use
 |        `sys.byteorder' as the byte order value.
 |      signed
 |        Determines whether two's complement is used to represent the integer.
 |        If signed is False and a negative integer is given, an OverflowError
 |        is raised.
 |  
 |  ----------------------------------------------------------------------
 |  Class methods defined here:
 |  
 |  from_bytes(bytes, byteorder, *, signed=False) from builtins.type
 |      Return the integer represented by the given array of bytes.
 |      
 |      bytes
 |        Holds the array of bytes to convert.  The argument must either
 |        support the buffer protocol or be an iterable object producing bytes.
 |        Bytes and bytearray are examples of built-in objects that support the
 |        buffer protocol.
 |      byteorder
 |        The byte order used to represent the integer.  If byteorder is 'big',
 |        the most significant byte is at the beginning of the byte array.  If
 |        byteorder is 'little', the most significant byte is at the end of the
 |        byte array.  To request the native byte order of the host system, use
 |        `sys.byteorder' as the byte order value.
 |      signed
 |        Indicates whether two's complement is used to represent the integer.
 |  
 |  ----------------------------------------------------------------------
 |  Static methods defined here:
 |  
 |  __new__(*args, **kwargs) from builtins.type
 |      Create and return a new object.  See help(type) for accurate signature.
 |  
 |  ----------------------------------------------------------------------
 |  Data descriptors defined here:
 |  
 |  denominator
 |      the denominator of a rational number in lowest terms
 |  
 |  imag
 |      the imaginary part of a complex number
 |  
 |  numerator
 |      the numerator of a rational number in lowest terms
 |  
 |  real
 |      the real part of a complex number

>>> 
========================= RESTART: C:/db/21.05.03-2.py =========================
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
>>> 
========================= RESTART: C:/db/21.05.03-2.py =========================
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
>>> 
========================= RESTART: C:/db/21.05.03-2.py =========================
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
>>> 
========================= RESTART: C:/db/21.05.03-2.py =========================
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
프로그래밍은 재밌다
>>> k? = 20
SyntaxError: invalid syntax
>>> 5 + 3 * 2
11
>>> (5+3)*2
16
>>> a = 20
>>> b= 40
>>> c = 20
>>> d = 20
>>> a
20
>>> b
40
>>> c
20
d
>>> 
>>> d
20
>>> id(20)
2663728442256
>>> id(a)
2663728442256
>>> id(d)
2663728442256
>>> id(a) = id(d)
SyntaxError: cannot assign to function call
>>> id(a) == id(d)
True
>>> id(b) == id(d)
False
>>> k= 4500
>>> id(k)
2663764434416
>>> id(30)
2663728442576
>>> s = [2, 4, 6]
>>> s1 = s
>>> s
[2, 4, 6]
>>> s1
[2, 4, 6]
>>> s[0]
2
>>> s1[0]
2
>>> s[1]
4
>>> s[2]
6
>>> s[3]
Traceback (most recent call last):
  File "<pyshell#79>", line 1, in <module>
    s[3]
IndexError: list index out of range
>>> s[0]=9
>>> s
[9, 4, 6]
>>> s1
[9, 4, 6]
>>> s2 = s.copy()
>>> s2
[9, 4, 6]
>>> s[0] = 1
>>> s1
[1, 4, 6]
>>> s2
[9, 4, 6]
>>> id(s) == id(s1)
True
>>> id(s1) == id(s2)
False
>>> 
