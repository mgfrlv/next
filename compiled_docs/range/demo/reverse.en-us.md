{"title":"Reverse","meta":{"title":"Reverse","description":"\n<p>When reverse is set to true, the selected part is reversed.</p>\n","order":"7"},"codes":{"jsx":"import { Range } from '@alifd/next';\n\n\nconst style = {\n    marginBottom: '15px'\n};\n\nReactDOM.render(\n    <div style={{width: '400px', margin: '50px'}}>\n        <Range defaultValue={30} style={style} hasTip={false} />\n        <Range defaultValue={30} style={style} reverse hasTip={false} />\n        <Range slider={'double'} defaultValue={[20, 40]} style={style} />\n        <Range slider={'double'} defaultValue={[20, 40]} style={style} reverse />\n        <Range defaultValue={30} disabled style={style} />\n        <Range defaultValue={30} disabled style={style} reverse />\n        <Range slider={'double'} defaultValue={[20, 40]} disabled style={style} />\n        <Range slider={'double'} defaultValue={[20, 40]} disabled style={style} reverse />\n    </div>, mountNode);\n"},"body":"\n````jsx\nimport { Range } from '@alifd/next';\n\n\nconst style = {\n    marginBottom: '15px'\n};\n\nReactDOM.render(\n    <div style={{width: '400px', margin: '50px'}}>\n        <Range defaultValue={30} style={style} hasTip={false} />\n        <Range defaultValue={30} style={style} reverse hasTip={false} />\n        <Range slider={'double'} defaultValue={[20, 40]} style={style} />\n        <Range slider={'double'} defaultValue={[20, 40]} style={style} reverse />\n        <Range defaultValue={30} disabled style={style} />\n        <Range defaultValue={30} disabled style={style} reverse />\n        <Range slider={'double'} defaultValue={[20, 40]} disabled style={style} />\n        <Range slider={'double'} defaultValue={[20, 40]} disabled style={style} reverse />\n    </div>, mountNode);\n````","html":"<script>(function(){'use strict';\n\nvar _next = require('@alifd/next');\n\nvar style = {\n    marginBottom: '15px'\n};\n\nReactDOM.render(React.createElement(\n    'div',\n    { style: { width: '400px', margin: '50px' } },\n    React.createElement(_next.Range, { defaultValue: 30, style: style, hasTip: false }),\n    React.createElement(_next.Range, { defaultValue: 30, style: style, reverse: true, hasTip: false }),\n    React.createElement(_next.Range, { slider: 'double', defaultValue: [20, 40], style: style }),\n    React.createElement(_next.Range, { slider: 'double', defaultValue: [20, 40], style: style, reverse: true }),\n    React.createElement(_next.Range, { defaultValue: 30, disabled: true, style: style }),\n    React.createElement(_next.Range, { defaultValue: 30, disabled: true, style: style, reverse: true }),\n    React.createElement(_next.Range, { slider: 'double', defaultValue: [20, 40], disabled: true, style: style }),\n    React.createElement(_next.Range, { slider: 'double', defaultValue: [20, 40], disabled: true, style: style, reverse: true })\n), mountNode);})()</script><div class=\"highlight\"><pre class=\"language-jsx\"><code class=\"language-jsx\"><span class=\"token keyword\">import</span> <span class=\"token punctuation\">{</span> Range <span class=\"token punctuation\">}</span> <span class=\"token keyword\">from</span> <span class=\"token string\">'@alifd/next'</span><span class=\"token punctuation\">;</span>\n\n\n<span class=\"token keyword\">const</span> style <span class=\"token operator\">=</span> <span class=\"token punctuation\">{</span>\n    marginBottom<span class=\"token punctuation\">:</span> <span class=\"token string\">'15px'</span>\n<span class=\"token punctuation\">}</span><span class=\"token punctuation\">;</span>\n\nReactDOM<span class=\"token punctuation\">.</span><span class=\"token function\">render</span><span class=\"token punctuation\">(</span>\n    <span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>div</span> <span class=\"token attr-name\">style</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token punctuation\">{</span>width<span class=\"token punctuation\">:</span> <span class=\"token string\">'400px'</span><span class=\"token punctuation\">,</span> margin<span class=\"token punctuation\">:</span> <span class=\"token string\">'50px'</span><span class=\"token punctuation\">}</span><span class=\"token punctuation\">}</span></span><span class=\"token punctuation\">></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>Range</span> <span class=\"token attr-name\">defaultValue</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token number\">30</span><span class=\"token punctuation\">}</span></span> <span class=\"token attr-name\">style</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span>style<span class=\"token punctuation\">}</span></span> <span class=\"token attr-name\">hasTip</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token boolean\">false</span><span class=\"token punctuation\">}</span></span> <span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>Range</span> <span class=\"token attr-name\">defaultValue</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token number\">30</span><span class=\"token punctuation\">}</span></span> <span class=\"token attr-name\">style</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span>style<span class=\"token punctuation\">}</span></span> <span class=\"token attr-name\">reverse</span> <span class=\"token attr-name\">hasTip</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token boolean\">false</span><span class=\"token punctuation\">}</span></span> <span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>Range</span> <span class=\"token attr-name\">slider</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token string\">'double'</span><span class=\"token punctuation\">}</span></span> <span class=\"token attr-name\">defaultValue</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token punctuation\">[</span><span class=\"token number\">20</span><span class=\"token punctuation\">,</span> <span class=\"token number\">40</span><span class=\"token punctuation\">]</span><span class=\"token punctuation\">}</span></span> <span class=\"token attr-name\">style</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span>style<span class=\"token punctuation\">}</span></span> <span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>Range</span> <span class=\"token attr-name\">slider</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token string\">'double'</span><span class=\"token punctuation\">}</span></span> <span class=\"token attr-name\">defaultValue</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token punctuation\">[</span><span class=\"token number\">20</span><span class=\"token punctuation\">,</span> <span class=\"token number\">40</span><span class=\"token punctuation\">]</span><span class=\"token punctuation\">}</span></span> <span class=\"token attr-name\">style</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span>style<span class=\"token punctuation\">}</span></span> <span class=\"token attr-name\">reverse</span> <span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>Range</span> <span class=\"token attr-name\">defaultValue</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token number\">30</span><span class=\"token punctuation\">}</span></span> <span class=\"token attr-name\">disabled</span> <span class=\"token attr-name\">style</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span>style<span class=\"token punctuation\">}</span></span> <span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>Range</span> <span class=\"token attr-name\">defaultValue</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token number\">30</span><span class=\"token punctuation\">}</span></span> <span class=\"token attr-name\">disabled</span> <span class=\"token attr-name\">style</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span>style<span class=\"token punctuation\">}</span></span> <span class=\"token attr-name\">reverse</span> <span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>Range</span> <span class=\"token attr-name\">slider</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token string\">'double'</span><span class=\"token punctuation\">}</span></span> <span class=\"token attr-name\">defaultValue</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token punctuation\">[</span><span class=\"token number\">20</span><span class=\"token punctuation\">,</span> <span class=\"token number\">40</span><span class=\"token punctuation\">]</span><span class=\"token punctuation\">}</span></span> <span class=\"token attr-name\">disabled</span> <span class=\"token attr-name\">style</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span>style<span class=\"token punctuation\">}</span></span> <span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n        </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;</span>Range</span> <span class=\"token attr-name\">slider</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token string\">'double'</span><span class=\"token punctuation\">}</span></span> <span class=\"token attr-name\">defaultValue</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span><span class=\"token punctuation\">[</span><span class=\"token number\">20</span><span class=\"token punctuation\">,</span> <span class=\"token number\">40</span><span class=\"token punctuation\">]</span><span class=\"token punctuation\">}</span></span> <span class=\"token attr-name\">disabled</span> <span class=\"token attr-name\">style</span><span class=\"token script language-javascript\"><span class=\"token script-punctuation punctuation\">=</span><span class=\"token punctuation\">{</span>style<span class=\"token punctuation\">}</span></span> <span class=\"token attr-name\">reverse</span> <span class=\"token punctuation\">/></span></span><span class=\"token plain-text\">\n    </span><span class=\"token tag\"><span class=\"token tag\"><span class=\"token punctuation\">&lt;/</span>div</span><span class=\"token punctuation\">></span></span><span class=\"token punctuation\">,</span> mountNode<span class=\"token punctuation\">)</span><span class=\"token punctuation\">;</span></code></pre></div>"}