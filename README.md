# Formulário de contatos

 

# Códigos

 

# Elementos

 

# < form >

### The <form> HTML element represents a document section containing interactive controls for submitting information.

## 🚀Atributos
###  This element includes the global attributes.

###  accept Deprecated
###  Comma-separated content types the server accepts.
 
###  Note: This attribute has been deprecated and should not be used. Instead, use the accept attribute on < input type=file > elements.


 

#### < p >  
## 🚀<p>: The Paragraph element

 ###  <p> HTML element represents a paragraph. Paragraphs are usually represented in visual media as blocks of text separated from adjacent blocks by blank lines and/or first-line indentation, but HTML paragraphs can be any structural grouping of related content, such as images or form fields.


###  Paragraphs are block-level elements, and notably will automatically close if another block-level element is parsed before the closing ### </p> tag. See "Tag omission" below.


 

#### < Label >
###  < label> HTML element represents a caption for an item in a user interface.
## 🚀tributes
### This element includes the global attributes.

## for 
The value of the for attribute must be a single id for a labelable form-related element in the same document as the < label> element. So, any given label element can be associated with only one form control.

```
Note: To programmatically set the for attribute, use htmlFor.
```
## 📦Styling with CSS

There are no special styling considerations for < label > elements — structurally they are simple inline elements, and so can be styled in much the same way as a < span > or < a > element. You can apply styling to them in any way you want, as long as you don't cause the text to become difficult to read.

 ## 📦Examples
 ## Defining an implicit label

 HTML

#### < label >Click me < input type="text" / >< /label >


### 📋Defining an explicit label with the "for" attribute

HTML

 #### < label for="username"> Click me to focus on the input field </label >
< input type="text" id="username" />

#### < Input >

```
The < input > HTML element is used to create interactive controls for web-based forms in order to accept data from the user; a wide variety of types of input data and control widgets are available, depending on the device and user agent. The < input> element is one of the most powerful and complex in all of HTML due to the sheer number of combinations of input types and attributes.
```
  ## 📦< input> types

### How an < input> works varies considerably depending on the value of its type attribute, hence the different types are covered in their own separate reference pages. If this attribute is not specified, the default type adopted is text

## 🚀Attributes
```
  The < input> element is so powerful because of its attributes; the type attribute, described with examples above, being the most important. Since every < input> element, regardless of type, is based on the HTMLInputElement interface, they technically share the exact same set of attributes. However, in reality, most attributes have an effect on only a specific subset of input types. In addition, the way some attributes impact an input depends on the input type, impacting different input types in different ways. 
  This section provides a table listing all the attributes with a brief description. This table is followed by a list describing each attribute in greater detail, along with which input types they are associated with. Those that are common to most or all input types are defined in greater detail below. Attributes that are unique to particular input types—or attributes which are common to all input types but have special behaviors when used on a given input type—are instead documented on those types' pages.
```

#### < Span >
### The <span> HTML element is a generic inline container for phrasing content, which does not inherently represent anything. It can be used to group elements for styling purposes (using the class or id attributes), or because they share attribute values, such as lang. It should be used only when no other semantic element is appropriate. <span> is very much like a <div> element, but <div> is a block-level element whereas a <span> is an inline-level element.

## 🚀Attributes
### This element only includes the global attributes.
Example 1
HTML

HTML
< p >< span>Some text</span></p>
Play
Copy to Clipboard
Result
Some text


 

#### < Textarea >
### The < textarea> HTML element represents a multi-line plain-text editing control, useful when you want to allow users to enter a sizeable amount of free-form text, for example a comment on a review or feedback form.

## 🚀Attributes
## This element includes the global attributes.

### autocomplete
## 🎁 This attribute indicates whether the value of the control can be automatically completed by the browser. Possible values are:

* off: The user must explicitly enter a value into this field for every use, or the document provides its own auto-completion method; the browser does not automatically complete the entry.
* on: The browser can automatically complete the value based on values that the user has entered during previous uses.


#### < Button >
```
The < button > HTML element is an interactive element activated by a user with a mouse, keyboard, finger, voice command, or other assistive technology. Once activated, it then performs an action, such as submitting a form or opening a dialog.

By default, HTML buttons are presented in a style resembling the platform the user agent runs on, but you can change buttons' appearance with CSS.
```
### 📋 Try it
 HTML Demo: < button>
RESET
HTML
CSS
1 < button class="favorite styled"   type="button">cAdd to favorites</button >
2

## 🚀Attributes
```
This element's attributes include the global attributes.

autofocus
This Boolean attribute specifies that the button should have input focus when the page loads. Only one element in a document can have this attribute.
```

#### < H1 >
### The < h1> to < h6> HTML elements represent six levels of section headings. < h1> is the highest section level and < h6> is the lowest. By default, all heading elements create a block-level box in the layout, starting on a new line and taking up the full width available in their containing block.

## 🚀Attributes
### These elements only include the global attributes.
 


# Atributos

 

## * Methood *
```
The method attribute defines the HTTP method to send the data (it can be "GET" or "POST"
 ```

## * For *
```
The for attribute is an allowed attribute for < label> and < output>. When used on a < label> element it indicates the form element that this label describes. When used on an < output> element it allows for an explicit relationship between the elements that represent values which are used in the output.
```

## 📦Usage
```
When used as an attribute of < label>, the for attribute has a value which is the id of the form element it relates to.
 ```

## * Type *
```
the type is used to specify the type of content this link tag is importing, the attribute value must be a MIME type such as "text/html", "text/css" and so on.
 ```

## * Id *
```
The global id attribute defines a unique identifier (ID) that must be unique throughout the document. Its purpose is to identify the element when navigating by anchors (using a fragment identifier), when using scripts, or when styling (with CSS).
 ```

## Fontes

[form-element](gg.gg/form-element)
 

## Tecnologias utilizadas

 **hmtl5** e **ccs3**

## Colaboradores

 Thays, Luamy, Sarah e Evillin.

## Status de conclusão
iniciado 20/09 - Terminado 29/09.
 

