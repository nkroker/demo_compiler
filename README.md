---


---

<h1 id="demo-compiler">Demo Compiler</h1>
<p>A demo compiler written in ruby which generates JavaScript its not a fully fledged compiler it just process single expression</p>
<p>Resource: <a href="https://www.destroyallsoftware.com/screencasts/catalog/a-compiler-from-scratch">https://www.destroyallsoftware.com/screencasts/catalog/a-compiler-from-scratch</a><br>
This tutorial is used to make this compiler/transpiler</p>
<p>This compiler works this way:</p>
<div class="mermaid"><svg xmlns="http://www.w3.org/2000/svg" id="mermaid-svg-iAGQxyI22WWyUkgI" width="100%" style="max-width: 310.921875px;" viewBox="0 0 310.921875 89.515625"><g transform="translate(-12, -12)"><g class="output"><g class="clusters"></g><g class="edgePaths"><g class="edgePath" style="opacity: 1;"><path class="path" d="M129.171875,56.7578125L185.2890625,56.7578125L241.40625,56.7578125" marker-end="url(#arrowhead1551)" style="fill:none"></path><defs><marker id="arrowhead1551" viewBox="0 0 10 10" refX="9" refY="5" markerUnits="strokeWidth" markerWidth="8" markerHeight="6" orient="auto"><path d="M 0 0 L 10 5 L 0 10 z" class="arrowheadPath" style="stroke-width: 1; stroke-dasharray: 1, 0;"></path></marker></defs></g></g><g class="edgeLabels"><g class="edgeLabel" transform="translate(185.2890625,56.7578125)" style="opacity: 1;"><g transform="translate(-31.1171875,-13)" class="label"><foreignObject width="62.234375" height="26"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; white-space: nowrap;"><span class="edgeLabel">Transpile</span></div></foreignObject></g></g></g><g class="nodes"><g class="node" id="A" transform="translate(74.5859375,56.7578125)" style="opacity: 1;"><rect rx="0" ry="0" x="-54.5859375" y="-23" width="109.171875" height="46"></rect><g class="label" transform="translate(0,0)"><g transform="translate(-44.5859375,-13)"><foreignObject width="89.171875" height="26"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; white-space: nowrap;">Source Code</div></foreignObject></g></g></g><g class="node" id="B" transform="translate(278.1640625,56.7578125)" style="opacity: 1;"><circle x="-36.7578125" y="-23" r="36.7578125"></circle><g class="label" transform="translate(0,0)"><g transform="translate(-26.7578125,-13)"><foreignObject width="53.515625" height="26"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; white-space: nowrap;">JS code</div></foreignObject></g></g></g></g></g></g></svg></div>
<p>It contains a <code>test.src</code> file where the only valid code is written<br>
the code contains a function block exactly like this</p>
<pre><code>def f (x,y)
  add(299, add(100, add(10, 5)))
end
</code></pre>
<p>and here you can add multiple add statement like this</p>
<pre><code>def f (x,y)
  add(1222, add(299, add(100, add(10, 5))))
end
</code></pre>
<h2 id="how-to-run-then-🤔">How to run then 🤔</h2>
<blockquote>
<p>Make sure you have ruby installed on your system ✌️<br>
<code>git clone https://github.com/nkroker/demo_compiler.git</code><br>
<code>cd demo_compiler</code><br>
<code>chmod +x compiler.rb</code><br>
<code>ruby compiler.rb</code> or <code>./compiler.rb</code></p>
</blockquote>
<p>The main motive behind writing this compiler is just for learning purpose so that you can play along with it 😊</p>

