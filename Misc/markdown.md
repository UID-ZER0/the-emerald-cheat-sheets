# Markdown

Markdown is a text-to-HTML conversion tool for web writers. Markdown allows you to write using an easy-to-read, easy-to-write plain text format, then convert it to structurally valid XHTML (or HTML).

Documentation: [Markdown Docs](https://daringfireball.net/projects/markdown/)
RFC: [RFC 7763](https://www.rfc-editor.org/rfc/rfc7763)
GitHub Documentation: [Writing Markdown on GitHub](https://docs.github.com/en/get-started/writing-on-github)

---
## Cheat-Sheet

### Headings
```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

Here is a heading: `# Heading`, **don't do this:** `#Heading` 

### Emphasis
```markdown
Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~
```

### Line Breaks
```markdown
First line with two spaces after.  
And the next line.
```

### Lists

#### Ordered Lists
```markdown
1. First item
2. Second item
3. Third item
```

#### Unordered Lists
```markdown
- First item
- Second item
- Third item
```

### Links
```markdown
Link with text: [link-text](https://www.google.com)
```

### Images
```markdown
Image with alt text: ![alt-text](https://camo.githubusercontent.com/4d89cd791580bfb19080f8b0844ba7e1235aa4becc3f43dfd708a769e257d8de/68747470733a2f2f636e642d70726f642d312e73332e75732d776573742d3030342e6261636b626c617a6562322e636f6d2f6e65772d62616e6e6572342d7363616c65642d666f722d6769746875622e6a7067)

Image without alt text: ![](https://camo.githubusercontent.com/4d89cd791580bfb19080f8b0844ba7e1235aa4becc3f43dfd708a769e257d8de/68747470733a2f2f636e642d70726f642d312e73332e75732d776573742d3030342e6261636b626c617a6562322e636f6d2f6e65772d62616e6e6572342d7363616c65642d666f722d6769746875622e6a7067)
```

### Code Blocks

#### Inline Code Block
```markdown
Inline `code` has `back-ticks around` it.
```

#### Blocks of Code
<pre>
```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
 
```python
s = "Python syntax highlighting"
print s
```
 
```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
```
</pre>

### Full list of supported languages:

- Cucumber ('*.feature')
- abap ('*.abap')
- ada ('_.adb', '_.ads', '*.ada')
- ahk ('_.ahk', '_.ahkl')
- apacheconf ('.htaccess', 'apache.conf', 'apache2.conf')
- applescript ('*.applescript')
- as ('*.as')
- as3 ('*.as')
- asy ('*.asy')
- bash ('_.sh', '_.ksh', '_.bash', '_.ebuild', '*.eclass')
- bat ('_.bat', '_.cmd')
- befunge ('*.befunge')
- blitzmax ('*.bmx')
- boo ('*.boo')
- brainfuck ('_.bf', '_.b')
- c ('_.c', '_.h')
- cfm ('_.cfm', '_.cfml', '*.cfc')
- cheetah ('_.tmpl', '_.spt')
- cl ('_.cl', '_.lisp', '*.el')
- clojure ('_.clj', '_.cljs')
- cmake ('*.cmake', 'CMakeLists.txt')
- coffeescript ('*.coffee')
- console ('*.sh-session')
- control ('control')
- cpp ('_.cpp', '_.hpp', '_.c++', '_.h++', '_.cc', '_.hh', '_.cxx', '_.hxx', '*.pde')
- csharp ('*.cs')
- css ('*.css')
- cython ('_.pyx', '_.pxd', '*.pxi')
- d ('_.d', '_.di')
- delphi ('*.pas')
- diff ('_.diff', '_.patch')
- dpatch ('_.dpatch', '_.darcspatch')
- duel ('_.duel', '_.jbst')
- dylan ('_.dylan', '_.dyl')
- erb ('*.erb')
- erl ('*.erl-sh')
- erlang ('_.erl', '_.hrl')
- evoque ('*.evoque')
- factor ('*.factor')
- felix ('_.flx', '_.flxh')
- fortran ('_.f', '_.f90')
- gas ('_.s', '_.S')
- genshi ('*.kid')
- glsl ('_.vert', '_.frag', '*.geo')
- gnuplot ('_.plot', '_.plt')
- go ('*.go')
- groff ('_.(1234567)', '_.man')
- haml ('*.haml')
- haskell ('*.hs')
- html ('_.html', '_.htm', '_.xhtml', '_.xslt')
- hx ('*.hx')
- hybris ('_.hy', '_.hyb')
- ini ('_.ini', '_.cfg')
- io ('*.io')
- ioke ('*.ik')
- irc ('*.weechatlog')
- jade ('*.jade')
- java ('*.java')
- js ('*.js')
- jsp ('*.jsp')
- lhs ('*.lhs')
- llvm ('*.ll')
- logtalk ('*.lgt')
- lua ('_.lua', '_.wlua')
- make ('_.mak', 'Makefile', 'makefile', 'Makefile._', 'GNUmakefile')
- mako ('*.mao')
- maql ('*.maql')
- mason ('_.mhtml', '_.mc', '*.mi', 'autohandler', 'dhandler')
- markdown ('*.md')
- modelica ('*.mo')
- modula2 ('_.def', '_.mod')
- moocode ('*.moo')
- mupad ('*.mu')
- mxml ('*.mxml')
- myghty ('*.myt', 'autodelegate')
- nasm ('_.asm', '_.ASM')
- newspeak ('*.ns2')
- objdump ('*.objdump')
- objectivec ('*.m')
- objectivej ('*.j')
- ocaml ('_.ml', '_.mli', '_.mll', '_.mly')
- ooc ('*.ooc')
- perl ('_.pl', '_.pm')
- php ('_.php', '_.php(345)')
- postscript ('_.ps', '_.eps')
- pot ('_.pot', '_.po')
- pov ('_.pov', '_.inc')
- prolog ('_.prolog', '_.pro', '*.pl')
- properties ('*.properties')
- protobuf ('*.proto')
- py3tb ('*.py3tb')
- pytb ('*.pytb')
- python ('_.py', '_.pyw', '_.sc', 'SConstruct', 'SConscript', '_.tac')
- r ('*.R')
- rb ('_.rb', '_.rbw', 'Rakefile', '_.rake', '_.gemspec', '_.rbx', '_.duby')
- rconsole ('*.Rout')
- rebol ('_.r', '_.r3')
- redcode ('*.cw')
- rhtml ('*.rhtml')
- rst ('_.rst', '_.rest')
- sass ('*.sass')
- scala ('*.scala')
- scaml ('*.scaml')
- scheme ('*.scm')
- scss ('*.scss')
- smalltalk ('*.st')
- smarty ('*.tpl')
- sourceslist ('sources.list')
- splus ('_.S', '_.R')
- sql ('*.sql')
- sqlite3 ('*.sqlite3-console')
- squidconf ('squid.conf')
- ssp ('*.ssp')
- tcl ('*.tcl')
- tcsh ('_.tcsh', '_.csh')
- tex ('_.tex', '_.aux', '*.toc')
- text ('*.txt')
- v ('_.v', '_.sv')
- vala ('_.vala', '_.vapi')
- vbnet ('_.vb', '_.bas')
- velocity ('_.vm', '_.fhtml')
- vim ('*.vim', '.vimrc')
- xml ('_.xml', '_.xsl', '_.rss', '_.xslt', '_.xsd', '_.wsdl')
- xquery ('_.xqy', '_.xquery')
- xslt ('_.xsl', '_.xslt')
- yaml ('_.yaml', '_.yml')

### Tables

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the raw Markdown line up prettily.

```markdown
| Heading 1 | Heading 2 | Heading 3 |
|---|---|---|
| col1 | col2 | col3 |
| col1 | col2 | col3 |
```

### Task list

To create a task list start line with square brackets with an empty space.
Ex: [ <space> ] and add text for task.
To check the task replace the space between the bracket with "x".

```markdown
[x] Write the post
[ ] Update the website
[ ] Contact the user
```

## Reference

Link: [markdown guide](https://www.markdownguide.org/cheat-sheet)
