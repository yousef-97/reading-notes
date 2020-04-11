# EJS
EJS: **Embedded JavaScript templates** is a simple templating language that lets you generate HTML markup with plain JavaScript. No religiousness about how to organize things.<br />
### Advantages

- Fast development time
- Simple syntax
- Speedy execution
- Easy debugging
- Active development

____________________________________________________________________________
### OPtions

- **cache** Compiled functions are cached, requires filename
- **filename** Used by cache to key caches, and for includes
- **context** Function execution context
- **compileDebug** When false no debug instrumentation is compiled
- **client** Returns standalone compiled function
- **delimiter** Character to use with angle brackets for open/close
- **debug** Output generated function body
- **_with** Whether or not to use with() {} constructs. If false then the locals will be stored in the locals object.
- **localsName** Name to use for the object storing local variables when not using with Defaults to locals
- **rmWhitespace** Remove all safe-to-remove whitespace, including leading and trailing whitespace. It also enables a safer version of -%> line slurping for all scriptlet tags (it does not strip new lines of tags in the middle of a line).
- **escape** The escaping function used with <%= construct. It is used in rendering and is .toString()ed in the generation of client functions. (By default escapes XML).
- **outputFunctionName** Set to a string (e.g., 'echo' or 'print') for a function to print output inside scriptlet tags.
- **async** When true, EJS will use an async function for rendering. (Depends on async/await support in the JS runtime.
------------------------------------------
### Tags

- **<%** Scriptlet tag, for control-flow, no output
- **<%_** Whitespace Slurping Scriptlet tag, strips all whitespace before it
- **<%=** Outputs the value into the template (HTML escaped)
- **<%-** Outputs the unescaped value into the template
- **<%#** Comment tag, no execution, no output
- **<%%** Outputs a literal '<%'
- **%>** Plain ending tag
- **-%>** Trim-mode ('newline slurp') tag, trims following newline
- **_%>** ‘Whitespace Slurping’ ending tag, removes all whitespace after it