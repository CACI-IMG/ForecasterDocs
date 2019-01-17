# Markdown examples \(temp\)

## Gitbbok Examples

# tests!

## Getting Super Powers

Becoming a super hero is a fairly straight forward process:

```
$ give me super-powers
```

{% hint style="info" %}
 Info hint
{% endhint %}

{% hint style="warning" %}
Warning hint
{% endhint %}

{% hint style="danger" %}
Danger hint
{% endhint %}

{% hint style="success" %}
Success hint
{% endhint %}

Once you're strong enough, save the world:

```
// Ain't no code for that yet, sorry
echo 'You got to trust me on this, I saved the world'
```

{% page-ref page="tests.md" %}

{% api-method method="get" host="" path="" %}
{% api-method-summary %}

{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="" type="string" required=false %}

{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}


{% page-ref page="markdown-examples.md" %}

{% file src="../.gitbook/assets/car-insurance.csv" caption="Car-Insurance.csv" %}

{% tabs %}
{% tab title="First Tab" %}


Text in the 1st tab





Text in the 1st tab





Text in the 1st tab
{% endtab %}

{% tab title="Second Tab" %}


Text in the second tab





Text in the second tab





Text in the second tab
{% endtab %}

{% tab title="3rd Tab" %}
Text in the 3rd tab





Text in the 3rd tab



Text in the 3rd tab
{% endtab %}
{% endtabs %}

> This is a quote from Achilles
>
> fds

fds


#### Features

* Support Standard Markdown / CommonMark and GFM\(GitHub Flavored Markdown\);
* Full-featured: Real-time Preview, Image \(cross-domain\) upload, Preformatted text/Code blocks/Tables insert, Code fold, Search replace, Read only, Themes, Multi-languages, L18n, HTML entities, Code syntax highlighting...;
* Markdown Extras : Support ToC \(Table of Contents\), Emoji, Task lists, @Links...;
* Compatible with all major browsers \(IE8+\), compatible Zepto.js and iPad;
* Support identification, interpretation, fliter of the HTML tags;
* Support TeX \(LaTeX expressions, Based on KaTeX\), Flowchart and Sequence Diagram of Markdown extended syntax;
* Support AMD/CMD \(Require.js & Sea.js\) Module Loader, and Custom/define editor plugins;

## Editor.md

![](https://pandao.github.io/editor.md/images/logos/editormd-logo-180x180.png)
![](https://pandao.github.io/editor.md/images/logos/editormd-logo-180x180.png )

<img src="image.png" width="640" height=360 />

<img src="image.png" width="100" height=100 />

# Heading

Here is an 200x100 image:

<img src="image.png" width="200" height="100" />

![](https://img.shields.io/github/stars/pandao/editor.md.svg) ![](https://img.shields.io/github/forks/pandao/editor.md.svg) ![](https://img.shields.io/github/tag/pandao/editor.md.svg) ![](https://img.shields.io/github/release/pandao/editor.md.svg) ![](https://img.shields.io/github/issues/pandao/editor.md.svg) ![](https://img.shields.io/bower/v/editor.md.svg)

**Table of Contents**

\[TOCM\]

\[TOC\]

## H1 header

### H2 header

#### H3 header

**H4 header**

**H5 header**

**H6 header**

## Heading 1 link [Heading link](https://github.com/pandao/editor.md)

### Heading 2 link [Heading link](https://github.com/pandao/editor.md)

#### Heading 3 link [Heading link](https://github.com/pandao/editor.md)

**Heading 4 link Heading link Heading link Heading link**

**Heading 5 link Heading link**

**Heading 6 link Heading link**

### Headers \(Underline\)

## H1 Header \(Underline\)

### H2 Header \(Underline\)

#### Characters

~~Strikethrough~~ Strikethrough \(when enable html tag decode.\) _Italic_ _Italic_ **Emphasis** **Emphasis** _**Emphasis Italic**_ _**Emphasis Italic**_

Superscript: X2，Subscript: O2

**Abbreviation\(link HTML abbr tag\)**

The HTML specification is maintained by the W3C.

#### Blockquotes

> Blockquotes

Paragraphs and Line Breaks

> "Blockquotes Blockquotes", [Link](http://localhost/)。

#### Links

[Links](http://localhost/)

[Links with title](http://localhost/)

`<link>` : [https://github.com](https://github.com)

[Reference link](http://link-url/)

GFM a-tail link @pandao

#### Code Blocks \(multi-language\) & highlighting

**Inline code**

`$ npm install marked`

**Code Blocks \(Indented style\)**

Indented 4 spaces, like `<pre>` \(Preformatted Text\).

```text
<?php
    echo "Hello world!";
?>
```

Code Blocks \(Preformatted text\):

| First Header | Second Header |
| :--- | :--- |
| Content Cell | Content Cell |
| Content Cell | Content Cell |

**Javascript**

```javascript
function test(){
    console.log("Hello world!");
}

(function(){
    var box = function(){
        return box.fn.init();
    };

    box.prototype = box.fn = {
        init : function(){
            console.log('box.init()');

            return this;
        },

        add : function(str){
            alert("add", str);

            return this;
        },

        remove : function(str){
            alert("remove", str);

            return this;
        }
    };

    box.fn.init.prototype = box.fn;

    window.box =box;
})();

var testBox = box();
testBox.add("jQuery").remove("jQuery");
```

**HTML code**

```markup
<!DOCTYPE html>
<html>
    <head>
        <mate charest="utf-8" />
        <title>Hello world!</title>
    </head>
    <body>
        <h1>Hello world!</h1>
    </body>
</html>
```

#### Images

Image:

![](https://pandao.github.io/editor.md/examples/images/4.jpg)

> Follow your heart.

![](https://pandao.github.io/editor.md/examples/images/8.jpg)

> 图为：厦门白城沙滩 Xiamen

图片加链接 \(Image + Link\)：

[![](https://pandao.github.io/editor.md/examples/images/7.jpg)](https://pandao.github.io/editor.md/examples/images/7.jpg)

> 图为：李健首张专辑《似水流年》封面

#### Lists

**Unordered list \(-\)**

* Item A
* Item B
* Item C

**Unordered list \(\*\)**

* Item A
* Item B
* Item C

**Unordered list \(plus sign and nested\)**

* Item A
* Item B
  * Item B 1
  * Item B 2
  * Item B 3
* Item C
  * Item C 1
  * Item C 2
  * Item C 3

**Ordered list**

1. Item A
2. Item B
3. Item C

#### Tables

| First Header | Second Header |
| :--- | :--- |
| Content Cell | Content Cell |
| Content Cell | Content Cell |

| First Header | Second Header |
| :--- | :--- |
| Content Cell | Content Cell |
| Content Cell | Content Cell |

| Function name | Description |
| :--- | :--- |
| `help()` | Display the help window. |
| `destroy()` | **Destroy your computer!** |

| Item | Value |
| :--- | ---: |
| Computer | $1600 |
| Phone | $12 |
| Pipe | $1 |

| Left-Aligned | Center Aligned | Right Aligned |
| :--- | :---: | ---: |
| col 3 is | some wordy text | $1600 |
| col 2 is | centered | $12 |
| zebra stripes | are neat | $1 |

**HTML entities**

© & ¨ ™ ¡ £ & &lt; &gt; ¥ € ® ± ¶ § ¦ ¯ « ·

X² Y³ ¾ ¼ × ÷ »

18ºC " '

### Escaping for Special Characters

\*literal asterisks\*

### Markdown extras

#### GFM task list

* [x] GFM task list 1
* [x] GFM task list 2
* [ ] GFM task list 3
  * [ ] GFM task list 3-1
  * [ ] GFM task list 3-2
  * [ ] GFM task list 3-3
* [ ] GFM task list 4
  * [ ] GFM task list 4-1
  * [ ] GFM task list 4-2

#### Emoji mixed :smiley:

> Blockquotes :star:

**GFM task lists & Emoji & fontAwesome icon emoji & editormd logo emoji :editormd-logo-5x:**

* [x] :smiley: @mentions, :smiley: \#refs, [links](markdown-examples.md), **formatting**, and ~~tags~~ supported :editormd-logo:;
* [x] list syntax required \(any unordered or ordered list supported\) :editormd-logo-3x:;
* [x] \[ \] :smiley: this is a complete item :smiley:;
* [ ] \[\]this is an incomplete item [test link](markdown-examples.md) :fa-star: @pandao; 
* [ ] \[ \]this is an incomplete item :fa-star: :fa-gear:;
  * [ ] :smiley: this is an incomplete item [test link](markdown-examples.md) :fa-star: :fa-gear:;
  * [ ] :smiley: this is  :fa-star: :fa-gear: an incomplete item [test link](markdown-examples.md);

#### TeX\(LaTeX\)

$$E=mc^2$$

Inline $$E=mc^2$$ Inline，Inline $$E=mc^2$$ Inline。

$$\(\sqrt{3x-1}+(1+x)^2\)$$

$$\sin(\alpha)^{\theta}=\sum_{i=0}^{n}(x^i + \cos(f))$$

#### FlowChart

```text
st=>start: Login
op=>operation: Login operation
cond=>condition: Successful Yes or No?
e=>end: To admin

st->op->cond
cond(yes)->e
cond(no)->op
```

#### Sequence Diagram

```text
Andrew->China: Says Hello 
Note right of China: China thinks\nabout it 
China-->Andrew: How are you? 
Andrew->>China: I am good thanks!
```

#### End

